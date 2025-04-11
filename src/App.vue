<script >
import HelloWorld from './components/HelloWorld.vue';
import AboutView from './views/HomeView.vue';
import Navbar from './components/UI/Navbar.vue';

export default {
  name: "App",
  components:{
    Navbar,
  }
}
</script>

<template>
  <v-app>
  <Navbar/>
  <v-main>
    
  </v-main>
</v-app>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
