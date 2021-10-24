<template>
  <div class="home">
    <img alt="Vue logo" src="./images/logo.png" />
    <HelloWorld msg="Vue3 Boilerplate" />
  </div>
</template>

<script lang="ts">
import HelloWorld from './components/hello-world.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
}
</script>
