<!-- src/components/ListaItens.vue -->
<template>
    <div>
      <!-- Lista não ordenada com v-for -->
      <ul>
        <li v-for="(item, index) in itens" :key="index">{{ item }}</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    // Definindo um array de itens
    data() {
      return {
        itens: ["Item 1", "Item 2", "Item 3"]
      };
    }
  };
  </script>
  
  <style scoped>
  /* Estilo para os itens da lista */
  ul {
    padding: 0;
  }
  li {
    list-style: none;
    font-size: 18px;
    color: #333;
  }
  </style>
  