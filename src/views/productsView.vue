<template> 
    <div>
        <v-banner color="teal darken-1">
            <div class="d-flex justify-space-around">
                <a href="#ms">
                    <v-btn text tile class="white--text">Muscle shirt</v-btn>
                </a>
                <a href="#ts">
                    <v-btn text tile class="white--text">T-shirt</v-btn>
                </a>
                <a href="#np">
                    <v-btn text tile class="white--text">New products</v-btn>
                </a>
            </div>
        </v-banner>
        <v-img src="../assets/images/illustrations/3d0c33168582879.643d6d473bad1.png" width="100vw"></v-img>
        <v-container>
            
            <div class="justify-center mt-12 	d-flex d-sm-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="12">
                                <a name="ms"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">Muscle shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="12">
                                <a name="ts"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">T-shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(autism,a) in autism" :key="a" :src="autism.src">
                                              
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="12">
                                <a name="np"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">New products</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(image,m) in images" :key="m" :src="image.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
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
                                <a name="ms"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">Muscle shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="12">
                                <a name="ts"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">T-shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(autism,a) in autism" :key="a" :src="autism.src">
                                              
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="12">
                                <a name="np"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">New products</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(image,m) in images" :key="m" :src="image.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 d-none d-md-flex d-lg-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                                <a name="ms"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">Muscle shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="ts"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">T-shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(autism,a) in autism" :key="a" :src="autism.src">
                                              
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="np"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">New products</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(image,m) in images" :key="m" :src="image.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 d-none d-lg-flex d-xl-none">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                                <a name="ms"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">Muscle shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="ts"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">T-shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(autism,a) in autism" :key="a" :src="autism.src">
                                              
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="np"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">New products</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(image,m) in images" :key="m" :src="image.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>

            <div class="justify-center mt-12 d-none d-xl-flex">
                <v-row>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="4">
                                <a name="ms"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">Muscle shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="ts"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">T-shirt</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(autism,a) in autism" :key="a" :src="autism.src">
                                              
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                            <v-col cols="4">
                                <a name="np"></a>
                                <v-card color="teal darken-3" width="100vw">
                                    <div class="d-block">
                                        <h2 class="d-flex justify-center white--text">New products</h2>
                                        <v-carousel hide-delimiters  cycle >
                                            <v-carousel-item v-for="(image,m) in images" :key="m" :src="image.src">
                                            </v-carousel-item>
                                        </v-carousel>
                                    </div>
                                </v-card>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
            </div>
        </v-container>

        <v-container>
            <v-row class="py-4" justify="center">
                <v-col cols="12" md="8">
                    <h1 class="text-center pt-4">Satisfied customers</h1>
                    <v-divider class="my-4"></v-divider>
                    <v-carousel cycle :height="500">
                    <v-carousel-item v-for="(testimonial, index) in testimonials" :key="index">
                        <v-card>
                        <v-img :src="testimonial.image" height="300"></v-img>
                        <v-card-title class="text-center">{{ testimonial.name }}</v-card-title>
                        <v-card-subtitle class="text-center">{{ testimonial.role }}</v-card-subtitle>
                        <v-card-text class="text-center">{{ testimonial.comment }}</v-card-text>
                        </v-card>
                    </v-carousel-item>
                    </v-carousel>
                </v-col>
            </v-row>
        </v-container>

        
    </div>
</template>

<script>
  export default {
    data() {
      return {
        testimonials: [
        {
          name: 'Maria Fernandez',
          role: 'Runner',
          image: require('../assets/images/woove-resources/th (1).jpg'),
          comment: 'I love sportswear from Woove! The quality of their products is excellent and the designs are very beautiful.'
        },
        {
          name: 'Carla Martinez',
          role: 'Coach',
          image: require('../assets/images/woove-resources/coach.jpg'),
          comment: 'I recommend Woove to all my clients. Its fabrics are comfortable and fit perfectly to the body in each workout.'
        },
        {
          name: 'Pedro Gonzalez',
          role: 'Cyclist',
          image: require('../assets/images/woove-resources/th.jpg'),
          comment: 'Since I met Woove, I have not stopped buying their sportswear. They help me perform better and push my own limits.',
        },
      ],
      items: [
        {
          src: require('../assets/images/sportwear/13234-001_1_12.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_13.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_14.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_15.jpg'),
        }
      ],
      autism: [
        {
          src: require('../assets/images/sportwear/13234-001_1_01.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_02.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_10.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_11.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_16.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_17.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_18.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13245-001_1.jpg'),
        }
      ],
      images: [
        {
          src: require('../assets/images/sportwear/13234-001_1_03.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_04.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_05.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_06.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_07.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_08.jpg'),
        },
        {
          src: require('../assets/images/sportwear/13234-001_1_09.jpg'),
        }
      ]
    }
    }
}
  
</script>

