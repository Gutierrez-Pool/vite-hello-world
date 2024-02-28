<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero,
  },

  data() {
    return {

    }
  },
}
</script>


<template>
  <div class="jumbotron">
    <div>
      <img src="/vite.svg" class="logo" alt="Vite logo" />
      <AppTitle></AppTitle>
    </div>
    <div class="testo">
      <AppHero></AppHero>
    </div>
  </div>
</template>


<style>
.logo {
  height: 10em;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.jumbotron {
  display: flex;
  justify-content: space-around;


  width: 600px;

  padding: 50px;

  background-color: cadetblue;
  border-radius: 20px;
}
</style>