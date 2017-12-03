<template>
  <!--we have to wrap our code with some div-->
  <div>
    <ServerStatus v-for="server in 5"></ServerStatus>
  </div>
</template>


<script>
  import ServerStatus from './ServerStatus.vue'
  export default {
    components: {
      'ServerStatus' : ServerStatus
    }
  }
</script>
<style></style>
