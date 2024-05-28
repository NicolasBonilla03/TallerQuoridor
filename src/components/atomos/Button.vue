<template>
    <button class="btn" :class="modifiers">{{ label }}</button>
  </template>
  
  <script>
  export default {
    name: 'Button',
    props: {
      label: String,
      modifiers: String
    }
  }
  </script>
  
  <style scoped>
  .btn {
    /* Estilos del botón */
  }
  </style>