<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <!--<router-view></router-view>-->
    <vheader></vheader>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<script>
  import vheader from '@/components/header/header'
  import tab from '@/components/tab/tab'

  export default {
    components: {
      vheader,
      tab
    }
  }
</script>

<style>

</style>
