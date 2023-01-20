<script>
export default {
    name: 'AppFooter',
    data() {
    return {

    }
  },
  
}
</script>

<template>
<footer>
    <section id="navbar-footer-section"></section>
    <section id="c2a-footer-section"></section>
</footer>
  
</template>

<style lang="scss" scoped>
#navbar-footer-section {
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 285px;
}
#c2a-footer-section {
    height: 100px;
    background-color: gray;
}
</style>