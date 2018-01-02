<template>
  <div class="jumbotron">
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
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
