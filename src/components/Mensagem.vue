<!-- src/components/Mensagem.vue -->
<template>
    <div>
      <!-- Exibindo a mensagem utilizando interpolação -->
      <p>{{ mensagem }}</p>
    </div>
  </template>
  
  <script>
  export default {
    // Definindo a propriedade 'mensagem' no objeto 'data'
    data() {
      return {
        mensagem: "Bem-vindo ao Vue.js!"
      };
    }
  };
  </script>
  
  <style scoped>
  /* Aqui podemos adicionar estilos específicos para o componente */
  p {
    font-size: 20px;
    color: #333;
  }
  </style>
  