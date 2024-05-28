<template>
    <div class="board">
      <div v-for="row in 9" :key="row" class="board__row">
        <Cell v-for="col in 9" :key="col" :modifiers="'cell-' + row + '-' + col"/>
      </div>
    </div>
  </template>
  
  <script>
  import Cell from '../atomos/Cell.vue';
  
  export default {
    name: 'Board',
    components: {
      Cell
    }
  }
  </script>
  
  <style scoped>
  .board {
    display: grid;
    grid-template-rows: repeat(9, 1fr);
    grid-template-columns: repeat(9, 1fr);
  }
  
  .board__row {
    display: flex;
  }
  </style>