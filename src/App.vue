<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <Header></Header>
    <router-view/>
  </div>
</template>

<script>
import Header from '@/components/globals/Header'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
#app {
}
</style>
