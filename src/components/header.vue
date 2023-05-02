<template>
        <v-app-bar app color="teal darken-3" width="100vw">
            
        <v-container class="d-flex d-sm-none">
            <v-row>
                <v-col cols="12" xs="12">
                    <v-row>
                        <v-col cols="3">
                            <div class="d-flex d-sm-none">
                                <div class="d-flex align-center d-sm-none">
                                    <v-img alt="Woove logo" contain src="../assets/images/icons/logo_woove_white.svg" width="40"/>
                                </div>
                            </div>
                        </v-col>
                        <v-col cols="9">
                            <div class="d-flex d-sm-none justify-space-around">
                                <v-btn text>
                                    <router-link to="/">
                                        <v-icon class="white--text">mdi-home</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/products">
                                        <v-icon class="white--text">mdi-bag-personal</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/about">
                                        <v-icon class="white--text">mdi-account-question</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/contact">
                                        <v-icon class="white--text">mdi-tooltip-account</v-icon>
                                    </router-link>
                                </v-btn>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-container>
        
        
        <v-container class="d-none d-sm-flex d-md-none">
            <v-row>
                <v-col cols="12" sm="12">
                    <v-row>
                        <v-col cols="3">
                            <div class="d-none d-sm-flex d-md-none">
                                <div class="d-flex align-center ">
                                    <v-img alt="Woove logo" contain src="../assets/images/icons/logo_woove_white.svg" width="40"/>
                                </div>
                            </div>
                        </v-col>
                        <v-col cols="9">
                            <div class="d-none d-sm-flex d-md-none justify-space-around">
                                <v-btn text>
                                    <router-link to="/">
                                        <v-icon class="white--text">mdi-home</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/products">
                                        <v-icon class="white--text">mdi-bag-personal</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/about">
                                        <v-icon class="white--text">mdi-account-question</v-icon>
                                    </router-link>
                                </v-btn>
                                <v-btn text>
                                    <router-link to="/contact">
                                        <v-icon class="white--text">mdi-tooltip-account</v-icon>
                                    </router-link>
                                </v-btn>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-container>

        <v-col class="d-none d-md-flex d-lg-none" cols="12" md="12">
            <v-row>
                <v-col md="12">
                    <v-row>
                        <v-col md="12">
                            <div class="d-none d-md-flex d-lg-none justify-space-between">
                                <router-link to="/">
                                    <v-btn text>
                                        <v-img alt="Woove logo" src="../assets/images/icons/logo_woove_white.svg" width="40px"/>
                                    </v-btn>
                                </router-link>

                                <router-link to="/">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Home</span>
                                        <v-icon class="white--text">mdi-home</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/products">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Products</span>
                                        <v-icon class="white--text">mdi-bag-personal</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/about">
                                    <v-btn text>
                                        <span class="mr-2 white--text">About us</span>
                                        <v-icon class="white--text">mdi-account-question</v-icon>
                                    </v-btn>
                                </router-link>

                                <router-link to="/contact">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Contact</span>
                                        <v-icon class="white--text">mdi-tooltip-account</v-icon>
                                    </v-btn>
                                </router-link>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-col>

        <v-col class="d-none d-lg-flex d-xl-none" cols="12" lg="12">
            <v-row>
                <v-col lg="12">
                    <v-row>
                        <v-col lg="12">
                            <div class="d-none d-lg-flex d-xl-none justify-space-between">
                                <router-link to="/">
                                    <v-btn text>
                                        <v-img alt="Woove logo" src="../assets/images/icons/logo_woove_white.svg" width="40px"/>
                                    </v-btn>
                                </router-link>

                                <router-link to="/">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Home</span>
                                        <v-icon class="white--text">mdi-home</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/products">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Products</span>
                                        <v-icon class="white--text">mdi-bag-personal</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/about">
                                    <v-btn text>
                                        <span class="mr-2 white--text">About us</span>
                                        <v-icon class="white--text">mdi-account-question</v-icon>
                                    </v-btn>
                                </router-link>

                                <router-link to="/contact">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Contact</span>
                                        <v-icon class="white--text">mdi-tooltip-account</v-icon>
                                    </v-btn>
                                </router-link>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-col>

        <v-col class="d-none d-xl-flex" xl="12">
            <v-row>
                <v-col xl="12">
                    <v-row>
                        <v-col xl="12">
                            <div class="d-none d-xl-flex justify-space-between">
                                <router-link to="/">
                                    <v-btn text>
                                        <v-img alt="Woove logo" src="../assets/images/icons/logo_woove_white.svg" width="40px"/>
                                    </v-btn>
                                </router-link>
                                <v-spacer></v-spacer>

                                <router-link to="/">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Home</span>
                                        <v-icon class="white--text">mdi-home</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/products">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Products</span>
                                        <v-icon class="white--text">mdi-bag-personal</v-icon>
                                    </v-btn>
                                </router-link>
                                
                                <router-link to="/about">
                                    <v-btn text>
                                        <span class="mr-2 white--text">About us</span>
                                        <v-icon class="white--text">mdi-account-question</v-icon>
                                    </v-btn>
                                </router-link>

                                <router-link to="/contact">
                                    <v-btn text>
                                        <span class="mr-2 white--text">Contact</span>
                                        <v-icon class="white--text">mdi-tooltip-account</v-icon>
                                    </v-btn>
                                </router-link>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-col>

    </v-app-bar>
</template>

<script>

export default {
  name: 'headerView',

  data: () => ({
    
  }),
};
</script>
