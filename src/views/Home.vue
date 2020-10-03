<template>
  <div class="home">
    <img alt="Hackoberfest logo" src="../assets/download.jpeg">
    <HelloWorld msg="Welcome to Hacktoberfest 2020"/>
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
