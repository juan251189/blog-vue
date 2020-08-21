<template>
  <nav>
    <v-toolbar  dark app>

      <v-toolbar-title class="text-uppercase yellow--text">
        Juan's<span class="font-weight-light">Mind</span> Admin
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn >New Post</v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </nav>
</template>


<script>
  export default{
    name:'Navbar',
    data(){
      return{
        drawer:false,
        newPostDialog:false,
        newPost:{}
      }
    }
  }
</script>
