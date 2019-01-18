<template lang="pug">
  div
    p {{ message }}
    button(@click="reverseMessage") Reverse
    input(v-model="message")
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