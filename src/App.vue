<script>
export default {

  name: 'App', 							// nome del componente

  //qui ci va il codice di vue
  data() {
    return {
      message: 'By'
    }
  },
  methods: {
    // qui le funzioni
  },
  mounted() {
    // qui i log nell hook mounted
  }
}
</script>

<template>





  <!-- // qui scriveremo il codice html -->
  <h1>{{ message }}</h1>
</template>

<style>
//qui scriveremo lo stile del foglio css
* {
  border: 1px solid black;
  background-color: red;
}
</style>