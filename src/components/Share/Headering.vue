<template>
  <header>
    <span @click="changeHeaderText"> {{ introText }}</span>
  </header>
</template>

<script>
  export default {
    data: function() {
      return {
        introText: 'Header'
      }
    },
    methods: {
      changeHeaderText: function() {
        this.introText = 'Changed Text'
      }
    }
  }
</script>
