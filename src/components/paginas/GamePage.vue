<template>
    <div class="game-page">
      <GameTemplate />
    </div>
  </template>
  
  <script>
  import GameTemplate from '../plantillas/GameTemplate.vue';
  
  export default {
    name: 'GamePage',
    components: {
      GameTemplate
    }
  }
  </script>
  
  <style scoped>
  .game-page {
    /* Estilos de la página del juego */
  }
  </style>