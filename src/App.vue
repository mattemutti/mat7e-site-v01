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

  <div class="container">
    <div class="row">
      <div class="col">

        <h1 class="text-center text-white">{{ message }}</h1>

        <div class="text-center text-white p-4">
          <a class="text-reset"
            href="https://open.spotify.com/intl-it/artist/2BreedZj1Hl5gzMpY0WZzt?si=Lo5c0l2VQWWTjjaRc_qbnA">Spoty</a>
        </div>
        <div class="text-center text-white p-4">
          <a class="text-reset" href="https://www.youtube.com/@mat7e">YouTube</a>
        </div>

      </div>
    </div>
  </div>



</template>

<style lang="scss"></style>