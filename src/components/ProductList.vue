<template>
    <div class="col-3">
        <div class="product">
            
            <img :src="src" :alt="titolo"/>
            <h4>{{titolo}}</h4>
            
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
    }

</style>
