<template>
  <v-app>
    <HomeView/>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import HomeView from './components/HomeView.vue';

export default {
    name: "App",
    data: () => ({
    //
    }),
    components: {  HomeView }
};
</script>
