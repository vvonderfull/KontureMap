<template>
  <div class="map-background">
    <img src="../assets/map.svg" />
    <div class="tomsk"></div>
    <div class="burgas"></div>
    <div class="varna"></div>
    <div class="belgorod"></div>
    <div class="keninsberg"></div>
    <div class="kaunas"></div>
    <div class="vitebsk"></div>
    <div class="riga"></div>
    <div class="orsha"></div>
    <div class="smolensk"></div>
    <div class="elnya"></div>
    <div class="asino"></div>
    <div class="novosibirsk"></div>
    <div class="yurga"></div>
    <div class="vologda"></div>
    <div class="moskva"></div>
    <div class="vyazma"></div>
    <div class="white"></div>
    <div class="duhovshina"></div>
    <div class="kastornoe"></div>
    <div class="stalingrad"></div>
    <div class="zaporoje"></div>
    <div class="odessa"></div>
    <div class="odessa-korovel"></div>
    <div class="korovel"></div>
    <div class="lubvin"></div>
    <div class="lodz"></div>
    <div class="berlin"></div>
    <div class="st-russa"></div>
    <div class="kr-rog"></div>
    <div class="poznan"></div>
    <div class="magdeburg"></div>
    <div class="sinyavino"></div>
    <div class="tihvin"></div>
    <div class="myasnoy-bor"></div>
    <div class="vel-luki"></div>
    <div class="riga-left"></div>
    <svg width="2000px" height="2000px" class="svg">
      <!-- <path class="path123" 
            :d = "asino1.x, asino1.y tomsk1.x, tomsk1.y"
      stroke="blue" fill="none"/>-->
      <line
        :x1="asino1.x - 1.5"
        :y1="asino1.y - 1.5"
        :x2="tomsk1.x - 1.5"
        :y2="tomsk1.y - 1.5"
        stroke="blue"
        stroke-width="5"
      />
      <a href="#">
        ////////////// RED PATH
        <path
          :d="'M'+ novosibirsk1.x + ',' + novosibirsk1.y + ' ' + 'C' + (novosibirsk1.x - 200) + ',' + (novosibirsk1.y - 100) + ' ' + (moskva1.x + 120) + ',' + (moskva1.y - 40) + ' ' + moskva1.x + ',' + moskva1.y"
          stroke="red"
          fill="none"
          stroke-width="5"
        />
        <line
          :x1="tomsk1.x"
          :y1="tomsk1.y"
          :x2="novosibirsk1.x"
          :y2="novosibirsk1.y"
          stroke="red"
          stroke-width="5"
        />
        <line
          :x1="tomsk1.x"
          :y1="tomsk1.y"
          :x2="yurga1.x"
          :y2="yurga1.y"
          stroke="red"
          stroke-width="5"
        />
        <line
          :x1="moskva1.x"
          :y1="moskva1.y"
          :x2="vyazma1.x"
          :y2="vyazma1.y"
          stroke="red"
          stroke-width="5"
        />
        <line
          :x1="white1.x"
          :y1="white1.y"
          :x2="vyazma1.x"
          :y2="vyazma1.y"
          stroke="red"
          stroke-width="5"
        />
        <line
          :x1="white1.x"
          :y1="white1.y"
          :x2="duhovshina1.x"
          :y2="duhovshina1.y"
          stroke="red"
          stroke-width="5"
        />
        <line
          :x1="vyazma1.x"
          :y1="vyazma1.y"
          :x2="duhovshina1.x"
          :y2="duhovshina1.y"
          stroke="red"
          stroke-width="5"
        />
      </a>
      /////// LIGHT BLUE PATH
      <a href="#">
        <line
          :x1="asino1.x + 1.5"
          :y1="asino1.y + 1.5"
          :x2="tomsk1.x + 1.5"
          :y2="tomsk1.y + 1.5"
          stroke="deepskyblue"
          stroke-width="5"
        />
        <line
          :x1="novosibirsk1.x + 3"
          :y1="novosibirsk1.y + 3"
          :x2="tomsk1.x + 3"
          :y2="tomsk1.y + 3"
          stroke="deepskyblue"
          stroke-width="5"
        />
        <line
          :x1="novosibirsk1.x"
          :y1="novosibirsk1.y"
          :x2="stalingrad1.x"
          :y2="stalingrad1.y"
          stroke="deepskyblue"
          stroke-width="5"
        />
        <line
          :x1="belgorod1.x"
          :y1="belgorod1.y"
          :x2="stalingrad1.x"
          :y2="stalingrad1.y"
          stroke="deepskyblue"
          stroke-width="5"
        />
        <line
          :x1="belgorod1.x"
          :y1="belgorod1.y"
          :x2="kr_rog1.x"
          :y2="kr_rog1.y"
          stroke="deepskyblue"
          stroke-width="5"
        />
        <path
          :d="'M'+ varna1.x + ',' + varna1.y + ' ' + 'C' + (varna1.x - 0) + ',' + (varna1.y - 30) + ' ' + (kr_rog1.x - 110) + ',' + (kr_rog1.y - 80) + ' ' + kr_rog1.x + ',' + kr_rog1.y"
          stroke="deepskyblue"
          fill="none"
          stroke-width="5"
        />
        <line
          :x1="varna1.x"
          :y1="varna1.y"
          :x2="burgas1.x"
          :y2="burgas1.y"
          stroke="deepskyblue"
          stroke-width="5"
        />
      </a>
    </svg>
  </div>
</template>

<script>
export default {
  name: "Map.vue",
  data() {
    return {
      tomsk1: {},
      asino1: {},
      moskva1: {},
      novosibirsk1: {},
      yurga1: {},
      vyazma1: {},
      white1: {},
      duhovshina1: {},
      stalingrad1: {},
      belgorod1: {},
      kr_rog1: {},
      varna1: {},
      burgas1: {}
    };
  },
  mounted() {
    for (let i = 0; i < document.all.length; i++) {
      if (
        document.all[i].className != "map-background" &&
        document.all[i].className != ""
      ) {
        if (document.all[i].className == "tomsk") {
          this.tomsk1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "asino") {
          this.asino1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "moskva") {
          this.moskva1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "novosibirsk") {
          this.novosibirsk1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "yurga") {
          this.yurga1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "vyazma") {
          this.vyazma1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "white") {
          this.white1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "duhovshina") {
          this.duhovshina1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "stalingrad") {
          this.stalingrad1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "belgorod") {
          this.belgorod1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "kr-rog") {
          this.kr_rog1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "varna") {
          this.varna1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        } else if (document.all[i].className == "burgas") {
          this.burgas1 = {
            x: document.all[i].offsetLeft + 5,
            y: document.all[i].offsetTop + 5
          };
        }
      }
    }
  }
};
</script>

<style scoped>
img {
  width: 100%;
  height: 100%;
}

.map-background {
  width: 100%;
  height: 100%;
}

.tomsk {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 47.3%;
  left: 79.6%;
}

.burgas {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 24.6%;
  bottom: 6%;
}

.varna {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 25.8%;
  bottom: 12.2%;
}

.belgorod {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 41.7%;
  bottom: 38.7%;
}

.keninsberg {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 23.2%;
  bottom: 52.1%;
}

.kaunas {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 26.2%;
  bottom: 53.7%;
}

.vitebsk {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 33.5%;
  bottom: 54.6%;
}

.riga {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 29.9%;
  bottom: 61.9%;
}

.orsha {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 33.2%;
  bottom: 53.7%;
}

.smolensk {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 35.4%;
  bottom: 53.3%;
}

.elnya {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 37.9%;
  bottom: 53%;
}

.asino {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 65.5%;
  left: 82.6%;
}

.novosibirsk {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 53%;
  left: 75.8%;
}

.yurga {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 53.9%;
  left: 84%;
}

.vologda {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 75.4%;
  left: 50.9%;
}

.moskva {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 64.4%;
  left: 45.9%;
}

.vyazma {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 61.5%;
  left: 41.8%;
}

.white {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 65.8%;
  left: 37.1%;
}

.duhovshina {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 64.4%;
  left: 37.5%;
}

.kastornoe {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 58.7%;
  left: 47.7%;
}

.stalingrad {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 48.7%;
  left: 54.1%;
}

.zaporoje {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 41.8%;
  left: 40.6%;
}

.odessa {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 41.7%;
  left: 32.6%;
}

.odessa-korovel {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 42.9%;
  left: 28.2%;
}

.korovel {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 53.8%;
  left: 26.1%;
}

.lubvin {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 56.1%;
  left: 22.3%;
}

.lodz {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 61.5%;
  left: 20.2%;
}

.berlin {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 72%;
  left: 15.6%;
}

.st-russa {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 78%;
  left: 38.6%;
}

.kr-rog {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 51.1%;
  left: 37.9%;
}
.poznan {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 70%;
  left: 19.8%;
}
.magdeburg {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 78.5%;
  left: 13.8%;
}
.sinyavino {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 92.8%;
  left: 37.8%;
}
.tihvin {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 90.8%;
  left: 39.8%;
}
.myasnoy-bor {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 90.5%;
  left: 38.3%;
}
.vel-luki {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  bottom: 85.6%;
  left: 35.4%;
}
.riga-left {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 28.4%;
  bottom: 89%;
}
.svg {
  position: absolute;
  top: 0;
}
</style>
