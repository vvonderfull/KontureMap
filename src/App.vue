<template>
  <div id="app">
    <Map />
  </div>
</template>

<script>
import Map from "./components/Map.vue";

export default {
  name: "App",
  components: {
    Map
  }
};
</script>

<style>
#app {
}
body {
  background: url("./assets/map.svg") no-repeat;
}
</style>
