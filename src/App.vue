<template>
  <div id="app">
    <mainTabBar></mainTabBar>
  </div>
</template>

<script>

  import mainTabBar from './components/content/mainTabbar/MainTabBar'
  export default {
    name: 'app',
    components: {
      mainTabBar: mainTabBar
    }
  }
</script>

<style>
  @import 'assets/css/base.css';
</style>