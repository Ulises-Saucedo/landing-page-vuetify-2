<template>
  <v-app>
    <headerView></headerView>

    <v-main>
      <router-view/>
    </v-main>

    <footerView></footerView>
  </v-app>
</template>

<script>
import headerView from './components/header.vue';
import footerView from './components/footer.vue';

export default {
  name: 'App',
  components:{
    headerView,
    footerView,
  },
  data: () => ({
    //
  }),
};
</script>
