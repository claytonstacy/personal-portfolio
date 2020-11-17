<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Coffee Logo"
          contain
          src="./assets/coffee-mug-small.png"
          transition="scale-transition"
          width="65"
        />

        <h1>
          C:/Dad Code
        </h1>
      </div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <Home/>
    </v-main>
  </v-app>
</template>

<script>
import Home from './components/Home.vue';

export default {
  name: 'App',

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
