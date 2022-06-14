<script>
export default {
  name: 'HelloMalandriner',
  props: ['message'],
}
</script>

<template>
  <h1>{{ message }}</h1>

  <p>
    Modifica el fichero <code>/src/App.vue</code> y cambia el atributo <code>message</code> del elemento <code>HelloMalandriner</code> (línea 9)
  </p>

</template>

<style scoped>
a {
  color: #42b983;
}
</style>
