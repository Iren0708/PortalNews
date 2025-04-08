<script >
import HelloWorld from './components/HelloWorld.vue';
import AboutView from './views/HomeView.vue';
import Shapka from './components/UI/Shapka.vue';

export default {
  name: "App",
  components:{
    Shapka,
  }
}
</script>

<template>
  <v-app>
    <shapka/>
    <v-main>
    <v-btn/>
    <a href="https://vite.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  <HelloWorld msg="Vite + Vue" />
  <HomeView />
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
