<template>
  <v-app>  
    <div>
      <v-img
      src="3.jpg"
      >
         <v-container>
          <v-row>
              <v-col cols="4" md="6">
                   <v-icon color="#0f3460" >mdi-view-grid  </v-icon>
              </v-col>

                   <v-col cols="4" md="6">
                  <h3>MEDI</h3>
              </v-col>
                
                   <v-col cols="4" md="6">
                       <v-avatar>
                   <v-img src="fm.jpg"></v-img>
                   </v-avatar>
              </v-col>
          </v-row>
         <v-content>
        <v-container>
          <nuxt />
        </v-container>
         </v-content>
      </v-container>     
      </v-img>

          <v-bottom-navigation
    v-model="bottomNav"
    dark
    shift
  >
    <v-btn>
      <span>แจ้งเตือน</span>
      <v-icon>mdi-bell-ring</v-icon>
    </v-btn>

    <v-btn>
      <span>ชื่นชอบ</span>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn>
      <span>Book</span>
      <v-icon>mdi-book</v-icon>
    </v-btn>

   <v-chip
      class="ma-2"
      color="indigo"
      text-color="white"
    >
    <v-avatar left>
    <v-icon right> mdi-apple-safari</v-icon>
    </v-avatar>
         Eexplor
      
    </v-chip>
  </v-bottom-navigation>
    </div>  
    
  </v-app>
</template>

<style scoped>
    .row{
        text-align: center;
    }
    h3{
        color: #0f3460;
       font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
</style>

