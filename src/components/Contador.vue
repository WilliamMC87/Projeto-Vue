<!-- src/components/Contador.vue -->
<template>
    <div>
      <!-- Exibindo o contador -->
      <p>Contador: {{ contador }}</p>
      <!-- Botão que chama o método 'incrementar' ao ser clicado -->
      <button @click="incrementar">Clique aqui</button>
    </div>
  </template>
  
  <script>
  export default {
    // Definindo a propriedade 'contador' e inicializando com 0
    data() {
      return {
        contador: 0
      };
    },
    methods: {
      // Método para incrementar o contador
      incrementar() {
        this.contador++;
      }
    }
  };
  </script>
  
  <style scoped>
  /* Estilos para o componente de contador */
  button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
  }
  </style>
  