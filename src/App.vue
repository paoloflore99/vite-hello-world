<script>
import HelloWorld from './components/HelloWorld.vue'
import esercizio from './components/esercizio.vue';
import terzo from './components/terzo.vue';

export default{
  components: {   //cosi posso utilizzarlo nel html
    esercizio,     //per poi inserire il nome come tag
    terzo          //sotto nel html
  }
}
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div> -->
    <esercizio></esercizio>
    <terzo></terzo>
  <HelloWorld msg="Vite + Vue" />
</template>

<style>
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
