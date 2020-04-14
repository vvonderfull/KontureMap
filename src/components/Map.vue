<template>
  <div class="map-background">
    <h1>JHGJHGJGJ</h1>
    <img src="../assets/map.svg" />
    <div class="tomsk"></div>
    <div class="burgas"></div>
    <div class="varna"></div>
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
  left: 10%;
  top: 80%;
}
</style>