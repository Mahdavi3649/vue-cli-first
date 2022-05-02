<template>
  <div id="app">
    <TitleComponent />
    <HeroComponent />
  </div>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue'
import HeroComponent from './components/HeroComponent.vue'

export default {
  name: 'App',
  components: {
    TitleComponent,
    HeroComponent,
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
