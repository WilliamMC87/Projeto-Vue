<!-- src/components/EstiloScoped.vue -->
<template>
    <div>
      <!-- Parágrafo estilizado com CSS Scoped -->
      <p>Este texto é estilizado com CSS scoped.</p>
    </div>
  </template>
  
  <script>
  export default {
    // Não há dados necessários para este exercício
  };
  </script>
  
  <style scoped>
  /* Alterando a cor do texto para verde */
  p {
    color: green;
  }
  </style>
  