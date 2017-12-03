<template>
  <ul>
    <li v-for="server in servers"> {{ server }}</li>
  </ul>
</template>


<script>
  export default {
    data: function() {
      return {
        servers: ['server-1', 'server-2', 'server-3']
      }
    }
  }
</script>
