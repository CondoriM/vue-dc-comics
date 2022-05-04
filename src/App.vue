<template>
  <div id="app">
    <SiteHeader/>
    <div class="jumb">
      
    </div>
    <SiteMain/>
    <SiteFooter/>
    <SiteCredit/>
  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue';
import SiteCredit from '@/components/CreditComponent.vue';
import SiteMain from '@/components/MainComponent.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    SiteCredit,
    SiteMain
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
  --bg-nav: #ffffff;
  --bg-foot-second: #303030;
  --text-foot: #6d6d6f;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-color: var(--bg-foot-second);
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

.jumb{
  width: 100%;
  background-image: url(@/assets/img/jumbotron.jpg);
  height: 300px;
  background-size: cover;
}
</style>
