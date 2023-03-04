<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1 class="name">test.com</h1>
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
  </div>
</template>

<script>
import HelloWorld from '/@/components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
.name {
  color:green;
}
</style>
