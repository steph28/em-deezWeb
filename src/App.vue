<template>
  <div id="app">
    <Navbar/>
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from './components/navbar'

export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat');

#app {
  font-family: 'Montserrat', sans-serif;
}
</style>