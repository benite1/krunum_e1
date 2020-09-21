<template>

<div>
    <center>
      <br><br>
     <v-img src="lg1.png" width="200"></v-img>
     <h1>MDI STYLE</h1>
    </center>
     <br>
 

    <v-hover
        open-delay="500"
      >
      <center>
        <v-card
          class="mx-auto"
          height="300"
          max-width="1000"
          color="#d49a89"
         
        >
         <v-form
      ref="form"
      v-model="valid"
      :lazy-validation="lazy"
     
    >
     <br><br>
 <v-text-field
            label="Username"
            placeholder="Username"
            width="20px"
            outlined
            dense
          ></v-text-field>

       <v-text-field
            label="Password"
            placeholder="Password"
            outlined
            dense
          ></v-text-field>

      

      <v-checkbox
        v-model="checkbox"
        :rules="[v => !!v || 'You must agree to continue!']"
        label="Do you agree?"
        required
      ></v-checkbox>

      <v-btn
      
        color="success"
        class="mr-4"
        @click="Signin"
      >
        Signin
      </v-btn>

      <v-btn
        color="error"
        class="mr-4"
        @click="reset"
      >
        Reset Form
      </v-btn>
    </v-form>

        </v-card>
        </center>
      </v-hover>
      
</div>
</template>


<script>
export default {
    layout:'bord3',
}
</script>
<style scoped>
img{
  margin: 50px;
}
h1{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
</style>