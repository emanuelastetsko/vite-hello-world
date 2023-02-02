<script>

// Importo il componente
import AppTitle from './components/HelloWorld.vue';

export default {
  name: 'Hello World',
  data(){

    return {
      msg: 'Ciao Vite!',
      count: 0
    };
  },

  // Registro il componente 
  components: {
    AppTitle,
  },

};

</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>

  <!--Utilizzo il componente come tag HTML-->
  <AppTitle />
</template>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>