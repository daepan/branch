<template>
  <div id="app">

    <daekan/>
  </div>
</template>

<script>
  import daekan from './components/super.vue'

  export default {
    name: 'app',
    components: {
      daekan
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
