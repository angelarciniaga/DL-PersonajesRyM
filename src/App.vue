<template>
  <div>
    <Personajes />
  </div>
</template>

<script>
import Personajes from './components/Personajes';

export default {
  name: 'App',
  components: {
    Personajes
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
