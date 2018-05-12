<template>
  <div id="app">
    <Home/>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import Home from '@/components/Home'
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style lang="stylus">
@import './common/styl/reset.styl'
</style>
