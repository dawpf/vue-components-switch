<template>
  <div class="home">
    <img class="img" alt="Vue logo" src="../assets/logo.png" />
    <XSwitch></XSwitch>
  </div>
</template>

<script>
import XSwitch from '@c/switch/index.vue'
export default {
  name: 'Home',
  components: { XSwitch }
}
</script>


<style lang="less" scoped>
.img {
  display: block;
  margin: 0 auto;
}
</style>
