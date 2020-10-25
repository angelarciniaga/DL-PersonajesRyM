<template>
  <main>
    <InfoPersonajes :datosRyM="datosRyM"/>
  </main>
</template>

<script>
import InfoPersonajes from './mainComponents/InfoPersonaje.vue';

export default {
  name: 'Personajes',
  components: {
    InfoPersonajes
  },

  data() {
    return {
      datosRyM: [
        {name: 'Rick Sanchez', image: 'https://rickandmortyapi.com/api/character/avatar/1.jpeg'},
        {name: 'Morty Smith', image: 'https://rickandmortyapi.com/api/character/avatar/2.jpeg'},
        {name: 'Summer Smith', image: 'https://rickandmortyapi.com/api/character/avatar/3.jpeg'},
        {name: 'Beth Smith', image: 'https://rickandmortyapi.com/api/character/avatar/4.jpeg'},
        {name: 'Jerry Smith', image: 'https://rickandmortyapi.com/api/character/avatar/5.jpeg'},
        {name: 'Abadango Cluster Princess', image: 'https://rickandmortyapi.com/api/character/avatar/6.jpeg'},
      ]
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
