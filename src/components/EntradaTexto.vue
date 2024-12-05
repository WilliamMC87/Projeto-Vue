<!-- src/components/EntradaTexto.vue -->
<template>
    <div>
      <!-- Campo de entrada vinculado ao 'nome' com v-model -->
      <input v-model="nome" type="text" placeholder="Digite seu nome" />
      <!-- Exibindo o valor digitado -->
      <p>O nome digitado é: {{ nome }}</p>
    </div>
  </template>
  
  <script>
  export default {
    // Definindo a propriedade 'nome' com valor inicial vazio
    data() {
      return {
        nome: ""
      };
    }
  };
  </script>
  
  <style scoped>
  /* Estilo para o campo de entrada */
  input {
    padding: 10px;
    font-size: 16px;
    width: 100%;
    max-width: 300px;
    margin: 10px 0;
  }
  </style>
  