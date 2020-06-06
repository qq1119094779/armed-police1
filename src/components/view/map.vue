<template>
  <div>
    <img class="header" src="../../assets/top-title.png"/>
    <div class="notice"></div>
    <div id="cesiumContainer" style="width: 100%; height:100%"></div>
  </div>
</template>

<script>
export default {
  name: "map",
  mounted() {
    this.innitMap()
  },
  methods: {
    innitMap () {
      Cesium.Ion.defaultAccessToken = URL_CONFIG.TOKEN_TIANDITU;
      var viewer = new Cesium.Viewer('cesiumContainer');
    }
  }
}
</script>

<style scoped>
  .header{
    position: fixed;
    z-index: 300;
    top:0;
    left: 0;
    right: 0;
    width: 100%;
  }
  .notice{
    position: fixed;
    left: 100px;
    background: url("../../assets/top-title.png") no-repeat center center;

  }
</style>
