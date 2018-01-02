<template>
  <div class="layout">
    <navbar></navbar>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  import Navbar from './navbar/Navbar'
  import Sidebar from './sidebar/Sidebar'
  import Footer from './footer/footer'

  export default {
    name: 'layout',
    components: {
      Navbar,
      Sidebar,
      Footer
    },
    data () {
      return {
        msg: 'Welcome to Latte-Dash'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
