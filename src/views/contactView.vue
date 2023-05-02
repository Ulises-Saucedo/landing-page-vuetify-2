<template>
    <div>
        <div class="d-flex d-sm-none">
            <v-col cols="12" class="d-flex justify-start">
                    <v-container>
                        <v-card height="550px">
                            <v-row>
                                <v-col cols="12">
                                    <v-card-title class="justify-center">CONTACT US</v-card-title>
                                </v-col>
                            </v-row>
                            <v-form ref="form" v-model="valid" lazy-validation>
                                <v-container>
                                    <v-row>
                                        <v-col cols="6">
                                            <v-text-field v-model="name" outlined label="Name" :rules="nameRules" required></v-text-field>
                                        </v-col>
                                        <v-col cols="6">
                                            <v-text-field v-model="lastname" outlined label="Lastname" :rules="nameRules" required></v-text-field>
                                        </v-col> 
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12">
                                            <v-text-field v-model="email" outlined type="email" label="Email" :rules="emailRules" required ></v-text-field>
                                        </v-col>
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12">
                                            <v-textarea  v-model="message" no-resize label="Message" :rules="messageRules" required>

                                            </v-textarea>
                                        </v-col>
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12" class="d-flex justify-end">
                                            <v-btn color="success" type="submit">
                                                Submit
                                            </v-btn>
                                        </v-col>
                                    </v-row>
                                </v-container>
                            </v-form>
                        </v-card>
                    </v-container>
                </v-col>
            </div>

            
        
    <div class="d-none d-sm-flex">
            <v-col cols="6" class="d-flex justify-start align-center">
                <v-img src="../assets/images/woove-resources/5afc29162182359.63d16257678b2.gif" height="500px" width="100px"></v-img>
            </v-col>
            <v-col cols="6" class="d-flex justify-start">
                    <v-container>
                        <v-card height="550px">
                            <v-row>
                                <v-col cols="12">
                                    <v-card-title class="justify-center">CONTACT US</v-card-title>
                                </v-col>
                            </v-row>
                            <v-form ref="form" v-model="valid" lazy-validation>
                                <v-container>
                                    <v-row>
                                        <v-col cols="6">
                                            <v-text-field v-model="name" outlined label="Name" :rules="nameRules" required></v-text-field>
                                        </v-col>
                                        <v-col cols="6">
                                            <v-text-field v-model="lastname" outlined label="Lastname" :rules="nameRules" required></v-text-field>
                                        </v-col> 
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12">
                                            <v-text-field v-model="email" outlined type="email" label="Email" :rules="emailRules" required ></v-text-field>
                                        </v-col>
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12">
                                            <v-textarea  v-model="message" no-resize label="Message" :rules="messageRules" required>

                                            </v-textarea>
                                        </v-col>
                                    </v-row>
                                    <v-row>
                                        <v-col cols="12" class="d-flex justify-end">
                                            <v-btn color="success" type="submit">
                                                Submit
                                            </v-btn>
                                        </v-col>
                                    </v-row>
                                </v-container>
                            </v-form>
                        </v-card>
                    </v-container>
                </v-col>
            </div>
        </div>
</template>

<script>
    export default {
        name: 'FormView',
        data: () => ({
            name: '',
            lastname :'',
            message: '',
            email:'',
            valid: true,

        
            nameRules: [
                        v => !!v || 'Name is required',
                         v => (v && v.length <= 20) || 'Name must be less than 20 characters',
            ],
            emailRules: [
                        v => !!v || 'E-mail is required',
                        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
            ],
            messageRules: [
                        v => !!v || 'Provide a description',
                        v => (v && v.length <= 1000) || 'Message must be less than 1000 characters',
            ],
        }),
    };
</script>