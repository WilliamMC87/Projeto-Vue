<!-- src/App.vue -->
<template>
    <div id="app">
      <Mensagem />
      <Contador />
      <MostrarOcultar />
      <ListaItens />
      <EntradaTexto />
      <EstiloScoped />
    </div>
  </template>
  
  <script>
  // Importando os componentes criados
  import Mensagem from './components/Mensagem.vue';
  import Contador from './components/Contador.vue';
  import MostrarOcultar from './components/MostrarOcultar.vue';
  import ListaItens from './components/ListaItens.vue';
  import EntradaTexto from './components/EntradaTexto.vue';
  import EstiloScoped from './components/EstiloScoped.vue';
  
  export default {
    name: 'App',
    components: {
      Mensagem,
      Contador,
      MostrarOcultar,
      ListaItens,
      EntradaTexto,
      EstiloScoped
    }
  };
  </script>
  
  <style>
  /* Estilos globais para o App (não Scoped) */
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #2c3e50;
  }
  </style>
  