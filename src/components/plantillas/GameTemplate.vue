<template>
    <div class="game-template">
      <Board />
      <!-- Agregar otros organismos como controles de juego -->
    </div>
  </template>
  
  <script>
  import Board from '../organismos/Board.vue';
  
  export default {
    name: 'GameTemplate',
    components: {
      Board
    }
  }
  </script>
  
  <style scoped>
  .game-template {
    /* Estilos de la plantilla de juego */
  }
  </style>