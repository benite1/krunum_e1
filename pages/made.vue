<template>
<div>
     <v-img
      class="white--text align-end"
      height="250px"
      src="mt.jpg"
    >
  <v-row>
    <v-col cols="6" md="6">
        <nuxt-link to="/mdi"><v-icon>mdi-chevron-left mdi-36px</v-icon></nuxt-link>
    </v-col>
    
  </v-row>
  
    
    <v-container>
     
      <v-card-title>Meditation</v-card-title>
      <v-list-item-subtitle style="color:#ffffff; font-size:6px;">
        Lorem ipsum dolor sit amet, <br>
        consectetuer adipiscing elit, <br>
        sed diam nonummy nibh euismod. <br>
           <v-chip
      class="ma-2"
      color="indigo"
      text-color="white"
    >
         Eexplor
       <v-icon right> mdi-apple-safari</v-icon>
    </v-chip>
      </v-list-item-subtitle>
      </v-container>
    </v-img>

<br><br>
    <h3>Let's Begin</h3>
    <v-spacer></v-spacer>
    <p>play all</p>
  <v-container>
           
    <v-row>
          <v-col cols="6" md="4">
                    <v-card>
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">session</div>
        <center>
        <v-list-item-title class="headline mb-1">01</v-list-item-title>
        <v-icon color="#e97171" >mdi-play-circle mdi-48px</v-icon>
        </center>
      </v-list-item-content>
    </v-list-item>
  </v-card>
                </v-col>
                <v-col cols="6" md="4">
                    <v-card>
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">session</div>
        <center>
        <v-list-item-title class="headline mb-1">02</v-list-item-title>
        <v-icon color="#e97171" >mdi-play-circle mdi-48px</v-icon>
        </center>
      </v-list-item-content>
    </v-list-item>
  </v-card>
                </v-col>
            </v-row>
              <v-row>
                <v-col cols="6" md="4">
                     <v-card>
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">session</div>
        <center>
        <v-list-item-title class="headline mb-1">03</v-list-item-title>
        <v-icon color="#e97171" >mdi-play-circle mdi-48px</v-icon>
        </center>
      </v-list-item-content>
    </v-list-item>
  </v-card>
                </v-col>
                <v-col cols="6" md="4">
                   <v-card>
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">session</div>
        <center>
        <v-list-item-title class="headline mb-1">04</v-list-item-title>
        <v-icon color="#e97171" >mdi-play-circle mdi-48px</v-icon>
        </center>
      </v-list-item-content>
    </v-list-item>
  </v-card>
                </v-col>
            </v-row>
           
        </v-container>


    </div>
</template>
<script>
export default {
    layout:'bord2',
}
</script>
<style scoped>
.icon1{
  padding-top: 20px;
}
h3{
  color: black;
}
p{
  color: black;
}
</style>