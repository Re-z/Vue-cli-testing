<template>
  <p @click="changeStatus">home component is {{ status }}</p>
</template>


<script>
  export default {
    data: function() {
      return {
        status: true
      }
    },
    methods: {
      changeStatus: function() {
        this.status = !this.status
      }
    }
  }
</script>
<style></style>
