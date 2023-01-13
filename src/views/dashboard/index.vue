<template>
  <div class="map-page">
    <Map/>
  </div>
</template>

<script>
import Map from "./map.vue"
export default {
  name: 'Dashboard',
  components:{
    Map
  }
}
</script>

<style lang="scss" scoped>
 .map-page {
  height: 695.6px;
  width: 100%;
}
</style>
