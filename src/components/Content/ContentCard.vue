<script>
export default {
    name: 'ContentCard',
    props: {
        contentItem: Object
    }, 
    data() {
    return {
     
    }
  },
}
</script>

<template>
<div class="content-card">
    <img :src="contentItem.thumbs" :alt="contentItem.series">
    <h3>{{ contentItem.series }}</h3>
</div>
  
</template>

<style lang="scss" scoped>
 .content-card {
            


            img {
                display: block;
            }
        }

</style>