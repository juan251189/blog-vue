<template>
  <v-app>
      <Navbar></Navbar>
    <v-main>
<Dashboard :posts="posts"></Dashboard>
</v-main>
</v-app>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Dashboard from "./components/Dashboard.vue";
export default {
  name: 'App',

  components: {
    Navbar,
    Dashboard

  },

  data: () => ({
      posts:[
        {
          _id:1,
          title:"Post 1",
          content:"Content",
          author:"Juan David"
        }
      ]
  })
};
</script>
