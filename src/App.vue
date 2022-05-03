<template>
  <div id="app">
    <SiteHeader/>
    <SiteFooter/>
    <SiteCredit/>
  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue';
import SiteCredit from '@/components/CreditComponent.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    SiteCredit
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root{
  --bg-foot: #0182f9;
  --bg-foot-second: #303030;
  --text-foot: #6d6d6f;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

/* Grid Syn */
.row{
  display: flex;
  align-items: center;
  width: 80%;
  margin: auto;
}

.col{
  width: 20%;
}

</style>
