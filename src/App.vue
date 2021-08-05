<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Layout/Header.vue'

export default {
  components: { Header },
  name:'App',
  component: {
    Header
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
