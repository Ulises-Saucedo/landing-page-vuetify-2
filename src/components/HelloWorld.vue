<template>
  <v-container>
    <div class="relative">
      <v-img  src="../assets/images/woove-resources/753cd5162182359.63d1626546e52.jpg"></v-img>
      <v-btn outlined rounded class="absolute">Winter sale</v-btn>
    </div>
  
    <div class="d-flex justify-center">
      <v-carousel hide-delimiters  cycle class="mt-12 carousel">
        <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
        </v-carousel-item>
      </v-carousel>
    </div>  

        

        <div class="justify-center mt-12 	d-flex d-sm-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Other products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_09.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Last products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_04.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Muscle shirt
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_13.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 	d-none d-sm-flex d-md-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Other products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_09.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Last products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_04.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="12">
                              <v-row>
                                <v-col cols="12" class="d-flex justify-center">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Muscle shirt
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_13.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 	d-none d-md-flex d-lg-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Other products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_09.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Last products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_04.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Muscle shirt
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_13.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>


            <div class="justify-center mt-12 	d-none d-lg-flex d-xl-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Other products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_09.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Last products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_04.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Muscle shirt
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_13.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 	d-none d-xl-flex">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Other products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_09.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Last products
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_04.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                            <v-col cols="4">
                              <v-row>
                                <v-col cols="12">
                                  <router-link to="/products">
                                    <v-card width="300px" color="teal darken-3" class="white--text">
                                      <v-card-title>
                                        Muscle shirt
                                      </v-card-title>
                                      <v-img src="../assets/images/sportwear/13234-001_1_13.jpg"></v-img>
                                    </v-card>
                                  </router-link>
                                </v-col>
                              </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data() {
      return {
      items: [
        {
          src: require('../assets/images/sportwear/13234-001_1_01.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_03.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_08.jpg'),
        }
      ]
    }
      
  }}
  

  
</script>

<style>
  .relative{
    position: relative;
  }
  .absolute{
    position: absolute;
    top: 75%;
    left: 15%;
  }
  .carousel{
    width: 50%;
  }
  
</style>
