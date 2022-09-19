<template>
  <HomePage/>
</template>

<script>
import HomePage from './Page/HomePage.vue'
export default {
  name: 'App',

  components: {
    HomePage,
  }
}
</script>
  
<style>
@import url('./style/reset.css');

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  padding: 0 20px;
}
</style>