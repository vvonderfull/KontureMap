<template>
    <div class="map-background">
        <img src="../assets/map.svg">
        <div class="one">
        </div>
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

    .one {
        background-color: blue;
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 47.3%;
        left: 79.6%;
    }

</style>