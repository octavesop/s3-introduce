<template>
  <v-container>
    <h1>To-Do-List</h1>
    <input type="text" @change=handleFileUpload>
    <input type="submit">
  </v-container>
</template>

<script>
//import AWS from 'aws-sdk'

export default {
  /*
  data: {
    
  },
  */
  methods: {
    handleFileUpload() {
      console.log("업로드 댓당 야호~")
    }
  }
}
</script>
