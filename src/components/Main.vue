<template>
  <div>
    <h2 v-for='friend in friends'>{{ friend }}</h2>
  </div>
</template>

<script>

import Hello from '@/components/Hello'


  export default {
    data () {
      return {
        friends: ['Scott', 'Sean', 'Brett'],
        msg: 'Hello there',
      }
    }
  }
</script>

<style scoped>
  h2 {
    color: red
  }
</style>
