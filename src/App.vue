<template>
  <div id="app">
   <Titolo/>
   <Jumbotron/>
  </div>
</template>

<script>
import Titolo from './components/TitleComponent.vue'
import Jumbotron from './components/HeroComponent.vue'

export default {
  name: 'App',
  components: {
    Titolo,
    Jumbotron,
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
