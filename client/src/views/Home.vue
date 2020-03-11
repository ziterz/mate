<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/mate-logo.png" width="200px">
    <HelloWorld msg="Welcome to Mate App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
