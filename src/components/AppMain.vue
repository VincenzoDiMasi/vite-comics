<script>
export default {
    name: 'AppMain',
    data() {
    return {

    }
  },
}
</script>

<template>
<main>
    <section id="content-section">
        <div class="container">
            Content goes here!
        </div>
    </section>
    <section id="icon-section"></section>
</main>
  
</template>

<style lang="scss" scoped>
#content-section {
    background-color: black;
    height: 100px;
    color: white;
    padding-top: 30px;
    font-size: 25px;
    
}
#icon-section {
    background-color: dodgerblue;
    height: 120px;
}
</style>