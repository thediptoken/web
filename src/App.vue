<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
@font-face {
  font-family: Poppins;
  font-weight: normal;
  src: url(assets/fonts/Poppins-Regular.ttf);
}

@font-face {
  font-family: Poppins;
  font-weight: bold;
  src: url(assets/fonts/Poppins-Bold.ttf);
}

@font-face {
  font-family: Abril;
  font-weight: bold;
  src: url(assets/fonts/AbrilFatface-Regular.ttf);
}

#app {
  font-family: TitilliumWeb, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
  background-color:#000;
}
</style>
