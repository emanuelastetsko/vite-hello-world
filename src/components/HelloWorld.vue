<script>

export default {
  name: 'AppTitle',
  data(){

    return {
      msg: 'La mia prima app con Vite!',
    };

  },
};

</script>

<template>

  <h1>{{ msg }}</h1>

</template>

<style scoped>
h1{
  font-size: 3em;
}
</style>