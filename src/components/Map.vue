<template>
    <div class="map-background">
        <img src="../assets/map.svg">
        <div class="tomsk">
        </div>
        <div class="asino">
        </div>
        <div class="novosibirsk">
        </div>
        <div class="yurga">
        </div>
        <div class="vologda">
        </div>
        <div class="moskva">
        </div>
        <div class="vyazma">
        </div>
        <div class="white">
        </div>
        <div class="duhovshina">
        </div>
        <div class="kastornoe">
        </div>
        <div class="stalingrad">
        </div>
        <div class="zaporoje">
        </div>
        <div class="odessa">
        </div>
        <div class="odessa-korovel">
        </div>
        <div class="korovel">
        </div>
        <div class="lubvin">
        </div>
        <div class="lodz">
        </div>
        <div class="berlin">
        </div>
    </div>
</template>

<script>
    export default {
        name: "Map.vue",
        mounted() {
            console.log(window)
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

    .asino {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 56.3%;
        left: 82.6%;
    }

    .novosibirsk {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 43.7%;
        left: 75.8%;
    }

    .yurga {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 44.7%;
        left: 84.0%;
    }

    .vologda {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 66.3%;
        left: 50.9%;
    }

    .moskva {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 55.1%;
        left: 45.9%;
    }

    .vyazma {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 52.3%;
        left: 41.8%;
    }

    .white {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 56.6%;
        left: 37.1%;
    }
    .duhovshina {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 55.1%;
        left: 37.5%;
    }
    .kastornoe {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 49.5%;
        left: 47.7%;
    }
    .stalingrad {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 39.4%;
        left: 54.1%;
    }
    .zaporoje {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 32.5%;
        left: 40.6%;
    }
    .odessa {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 32.4%;
        left: 32.6%;
    }
    .odessa-korovel {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 33.6%;
        left: 28.2%;
    }
    .korovel {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 44.5%;
        left: 26.1%;
    }
    .lubvin {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 46.8%;
        left: 22.3%;
    }
    .lodz {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 52.3%;
        left: 20.2%;
    }
    .berlin {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 62.8%;
        left: 15.6%;
    }
</style>