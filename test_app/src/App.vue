<template>
  <div id="app">
    <Titolo/>
  </div>
</template>

<script>
import Titolo from '@./components/Title.vue'

export default {
  name: 'App',
  components: {
    Titolo
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
