<!-- src/App.vue -->

<template>
  <div id="app">
    <MyComponent />
  </div>
</template>

<script>
import MyComponent from '@/components/MyComponent.vue';

export default {
  components: {
    MyComponent,
  },
};
</script>

<style>
/* Estilos globales si es necesario */
body {
  font-family: 'Arial', sans-serif;
}
#app {
  text-align: center;
  margin-top: 20px;
}
</style>
