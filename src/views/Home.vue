<template>
  <div class="home">
    <h1>Homepage</h1>
   <v-btn class="pink white--text">Click Me</v-btn>
   <v-btn depressed color="pink">Click Me</v-btn>
   <v-btn flat color="pink">Click Me</v-btn>
   <v-btn depressed color="pink white--text">
     <v-icon left>email</v-icon>
     <span>email me</span>
   </v-btn>
   <v-btn depressed small color="pink white--text">
     <v-icon left small>email</v-icon>
     <span>email me</span>
   </v-btn>
   <v-btn depressed large color="pink white--text">     
     <span>email me</span>
     <v-icon right large>email</v-icon>
   </v-btn>
   <v-btn fab depressed small dark color="purple white--text">          
     <v-icon>favorite</v-icon>
   </v-btn>
  </div>
</template>

<script>  

  export default {
    components: {
      
    }
  }
</script>
