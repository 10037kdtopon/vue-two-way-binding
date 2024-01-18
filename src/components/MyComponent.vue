<!-- src/components/MyComponent.vue -->

<template>
    <div>
      <input v-model="mensaje" placeholder="Ingrese un mensaje" />
      <p>{{ mensaje }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        mensaje: '',
      };
    },
  };
  </script>
  
  <style scoped>
  /* Estilos específicos del componente si es necesario */
  div {
    margin: 20px;
  }
  input {
    padding: 5px;
    margin-right: 10px;
  }
  </style>
  