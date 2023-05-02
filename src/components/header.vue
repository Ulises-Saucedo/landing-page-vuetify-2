<template>
    <v-app-bar app color="teal darken-3">
        <div class="d-flex align-center">
            <v-img alt="Woove logo" contain src="../assets/images/icons/logo_woove_white.svg" width="40"/>
        </div>

        <v-spacer></v-spacer>

            <!-- Buttons type text -->
            <router-link to="/">
                <v-btn href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank" text class="white--text">
                    <span class="mr-2">Home</span>
                    <v-icon>mdi-home</v-icon>
                </v-btn>
            </router-link>

            <v-btn href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank" text class="white--text">
                <span class="mr-2">Products</span>
                <v-icon>mdi-bag-personal</v-icon>
            </v-btn>

            <router-link to="/about">
                <v-btn text class="white--text">
                    <span class="mr-2">About us</span>
                    <v-icon>mdi-account-question</v-icon>
                </v-btn>
            </router-link>

            <v-btn href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank" text class="white--text">
                <span class="mr-2">Contact</span>
                <v-icon>mdi-tooltip-account</v-icon>
            </v-btn>
    </v-app-bar>
</template>

<script>

export default {
  name: 'headerView',

  data: () => ({
    
  }),
};
</script>
