<template>
  <v-app>

    <Navbar />

  <v-container fluid></v-container>
  </v-app>
</template>

<script>

  import Navbar from '../components/NavBar'

  export default {
    name: 'HomeView',

    components: {
      Navbar,
    },
  }
</script>
