
<template>
  <div id="app">
    <h1>Lista de usuarios</h1>

    
    <datosDeEntrada />
    <tablaCompo />

  </div>
</template>

<script>


import datosDeEntrada from './components/datosDeEntrada.vue';
import tablaCompo from './components/tablaCompo.vue' ;

export default {
  components: {
    tablaCompo,
    datosDeEntrada,
  },
};
</script>


