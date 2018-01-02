<template>
  <div id="app">
    <layout></layout>
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

</style>
