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
  </div>
</template>

<script>
export default {
  name: "Map.vue"
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
  bottom: 12.1%;
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
  bottom: 52%;
}
.kaunas {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 26.1%;
  bottom: 53.6%;
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
  bottom: 61.8%;
}
.orsha {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 33.2%;
  bottom: 53.6%;
}
.smolensk {
  background-color: blue;
  width: 10px;
  height: 10px;
  position: relative;
  left: 35.5%;
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
</style>