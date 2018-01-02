<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  import Layout from './components/layout/Layout'
  import AuthLayout from './components/layout/AuthLayout'

export default {
    name: 'app',
    components: {
      AuthLayout,
      Layout
    },
    computed: {
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
