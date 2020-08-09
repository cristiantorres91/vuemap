<template>
  <div id="app">
    <div class="row">
       <h1 style="text-align: center;">Proyecto Vue Google Map</h1>
       <GoogleMap :latitude= 13.7013266 :longitude= -89.226622 :title="'Titulo Marcador'" />
    </div>

  </div>
</template>

<script>
import GoogleMap from "./components/GoogleMap";

export default {
  name: 'App',
  components: {
    GoogleMap
  }
}
</script>

<style>

</style>
