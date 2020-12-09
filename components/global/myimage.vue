<template>
  
    <v-img
      :src='msrc'
      :max-height='mheight'   
      contain  
    >
      
    </v-img>  
   
</template>

<script>
  export default {
    props: {
      msrc: {
        type: String,
      },
      mheight: {                
        type: Number,
        default: 500
      }
    },
    data () {
      return {
      }
   
    },
  }
</script>
