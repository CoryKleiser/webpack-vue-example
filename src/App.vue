<template>
  <div id="app">
    <my-component :imgUrl="image" />
    <router-view />
  </div>
</template>

<script>
import MyComponent from '@/components/MyComponent.vue'
import image from '@/assets/logo.png'

export default {
  name: 'App',
  components: {
    MyComponent
  },
  data() {
    return { image }
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
