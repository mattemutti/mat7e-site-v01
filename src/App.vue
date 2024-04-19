<script>
export default {

  name: 'App', 							// nome del componente

  //qui ci va il codice di vue
  data() {
    return {
      message: 'Mat7e'
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
  <h1 class="text-center text-white">{{ message }}</h1>
</template>

<style lang="scss"></style>