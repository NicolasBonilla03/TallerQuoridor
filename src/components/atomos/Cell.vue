<template>
    <div class="cell" :class="modifiers"></div>
  </template>
  
  <script>
  export default {
    name: 'Cell',
    props: {
      modifiers: String
    }
  }
  </script>
  
  <style scoped>
  .cell {
    /* Estilos de la celda */
  }
  </style>