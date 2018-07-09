<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-link to="/">home</router-link>
    <router-link to="/a">page one</router-link>
    <router-link to="/b">page two</router-link>
    <router-link to="/c">page three</router-link>
    <router-view/>

  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {

    }
  },
  methods: {

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
