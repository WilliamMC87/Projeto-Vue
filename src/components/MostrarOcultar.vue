<!-- src/components/MostrarOcultar.vue -->
<template>
    <div>
      <!-- Botão que alterna entre mostrar e ocultar o texto -->
      <button @click="mostrar = !mostrar">{{ mostrar ? 'Ocultar' : 'Mostrar' }} Texto</button>
      <!-- Texto exibido apenas quando 'mostrar' for verdadeiro -->
      <p v-if="mostrar">Este é um texto que pode ser mostrado ou ocultado.</p>
    </div>
  </template>
  
  <script>
  export default {
    // Definindo a propriedade 'mostrar' como false inicialmente
    data() {
      return {
        mostrar: false
      };
    }
  };
  </script>
  
  <style scoped>
  /* Estilo simples para o botão e o texto */
  button {
    padding: 10px;
    font-size: 16px;
    margin: 10px 0;
  }
  p {
    font-size: 18px;
    color: #555;
  }
  </style>
  