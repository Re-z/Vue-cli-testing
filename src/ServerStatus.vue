<template id="ServerStatus">
  <!--we have to wrap our code with some div-->
  <div>
    <p @click="changeStatus">ServerStatus component is {{ status }}</p>
  </div>
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
