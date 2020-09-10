<template>
  <v-app>
    <v-toolbar color="#00ADFF" dark>
      <v-app-bar-nav-icon to="/"></v-app-bar-nav-icon>

      <v-toolbar-title>codevue.io</v-toolbar-title>

      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down"> 
      <v-btn flat to="/signup">Sign Up</v-btn>

      <v-btn flat to="/login">Login</v-btn>
    </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <router-view/>
    </v-content>
    <v-footer color="#00ADFF" dark>
    <v-spacer></v-spacer>
    <div>codevue.io &nbsp; &copy; {{ new Date().getFullYear() }}</div>
  </v-footer>   
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    //HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
