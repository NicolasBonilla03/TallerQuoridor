<template>
    <div class="player" :class="modifiers">
      <img :src="image" alt="Player">
    </div>
  </template>
  
  <script>
  export default {
    name: 'Player',
    props: {
      image: String,
      modifiers: String
    }
  }
  </script>
  
  <style scoped>
  .player {
    /* Estilos del jugador */
  }
  </style>