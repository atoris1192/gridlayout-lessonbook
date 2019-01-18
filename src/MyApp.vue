<template lang="pug">
</template>

<style>
</style>

<script>

  export default {
    data() {
      return({
        message: 'hello',

      });
    },
    methods: {
      reverseMessage() {
        this.message = this.message.split('').reverse().join('')
      }
    }
  }
</script>