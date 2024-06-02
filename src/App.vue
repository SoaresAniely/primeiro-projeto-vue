<template>
  <img width="30%" alt="Vue logo" src="./assets/Suelmara-33.jpeg">
  <ApresentacaoCima msg="Aniely Photography and Beauty."/>
  <MeiodaPagina msg=" "/>
  <img width="30%" src="./assets/IMG_7972 (1).jpeg" alt="">
  <img width="30%" src="./assets/IMG_6416certa.jpeg" alt="">
  <img width="30%" src="./assets/claudia-site.jpeg" alt="">
  <AlgumBottom msg=" "/>
  <img width="95%" src="./assets/IMG_64.jpeg" alt="">
  <RodaPe msg=" "/>
</template>

<script>
import ApresentacaoCima from './components/ApresentacaoCima.vue';
import MeiodaPagina from './MeiodaPagina.vue';
import AlgumBottom from './AlgumBottom.vue';
import RodaPe from './RodaPe.vue';

export default {
  name: 'App',
  components: {
    MeiodaPagina, ApresentacaoCima,
    RodaPe, AlgumBottom
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  background-color: #f1f1f0;
  margin-left: 5px;
  margin-right: 5px;
}
img {
  margin-block: 20px;
}
</style>
