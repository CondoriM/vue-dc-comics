<template>
    <div class="col-3">
        <div class="product">
            <img :src="src" :alt="titolo"/>
            <h3>{{titolo}}</h3>
        </div>
    </div>
</template>

<script>
    export default{
        nome:'Product',

        props:{
            src:String,
            titolo:String
        }
    }
</script>

<style lang="scss" scoped>
    .col-3{
        width: calc(100% / 12) * 2;
        color: var(--bg-nav);
        margin: 2rem 0;
        
        .img{
            aspect-ratio: 1 / 1;
        }
    }

</style>
