<template>
    <div id="app-template">
      <Headering></Headering>

      <Servers></Servers>

      <Footering></Footering>
    </div>

</template>

<script>
  import Headering from './components/Share/Headering.vue'
  import Footering from './components/Share/Footering.vue'
  import Servers from './components/Server/Servers.vue'

  export default {
    components: {
      Headering: Headering,
      Footering: Footering,
      Servers: Servers
    }
  }

</script>

<style lang="scss" >
</style>
