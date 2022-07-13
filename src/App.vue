<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex">
        <h2>Graphic IMG practice app</h2>
      </div>
    </v-app-bar>

    <v-main>
      <imageMap />
    </v-main>
  </v-app>
</template>

<script>
import imageMap from './components/imageMap.vue';
export default {
  name: 'App',

  components: {imageMap},

  data: () => ({
    //
  })
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap');
* {
  font-family: 'Open Sans', sans-serif;
}
h2 {
  width: 100%;
  text-align: center;
  font-weight: 300;
}
</style>
