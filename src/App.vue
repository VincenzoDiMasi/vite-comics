<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }

}
</script>

<template>
<header>
  <AppHeader></AppHeader>
</header>
<main>
  <AppMain></AppMain>
</main>
<footer>
  <AppFooter></AppFooter>
</footer>
</template>

<style>
/* CSS RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* GENERICS */
body {
  font-family: sans-serif;
  min-height: 100vh;
}

a {
  text-decoration: none;
}

/* UTILS */
.container {
  max-width: 1140px;
  margin: 0 auto;
}
</style>
