<template>
  <div class="box-index">
    <left-bav></left-bav>
    <pl-notice></pl-notice>
    <pl-map></pl-map>
    <right-nav></right-nav>
    <bottom-Nav></bottom-Nav>
  </div>
</template>

<script>
import map from '@/components/view/map'
import leftNav from "@/components/view/leftNav";
import rightNav from "@/components/view/rightNav";
import bottomNav from "@/components/view/bottomNav";
import notice from "@/components/view/notice";
export default {
  name: "index",
  components: {
    'pl-map': map,
    'left-bav': leftNav,
    'right-nav': rightNav,
    'bottom-Nav': bottomNav,
    'pl-notice': notice
  }
}
</script>

<style scoped>
</style>
