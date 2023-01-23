<script>
import ContentCard from './Content/ContentCard.vue';
export default {
    name: 'AppMain',
    components: [ ContentCard ],
    props: {
        title: String,
        contentItems: Object
    },
    data() {
    return {
        

    }
  },

}
</script>

<template>
<main>
    <section id="content-section">
        <div class="container ">        
            <div class="contents-box">
                <ContentCard v-for="contentItem in contentItems" :key="series" :contentItem="contentItem"></ContentCard>
            </div>

        </div>
    </section>
    <section id="icon-section"></section>
</main>
  
</template>

<style lang="scss" scoped>
#content-section {
    background-color: black;
    min-height: 100px;
    color: white;
    padding-top: 30px;
    font-size: 25px;

    .contents-box {
        display: flex;
        flex-wrap: wrap;
        
        .content-card {
            flex-basis: calc(100% / 6);


        }
    }
    
    
}
#icon-section {
    background-color: dodgerblue;
    min-height: 120px;
}
</style>