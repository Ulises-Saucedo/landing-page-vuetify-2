<template>
  <v-app>
    <headerView></headerView>

    <v-main>
      <router-view/>
    </v-main>

    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </v-app>
</template>

<script>
import headerView from './components/header.vue'

export default {
  name: 'App',
  components:{
    headerView,
  },
  data: () => ({
    //
  }),
};
</script>
