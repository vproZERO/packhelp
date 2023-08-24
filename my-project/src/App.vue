<template>
  <div class="container mx-auto p-4 font-sans">
    <div class="content">
      <Header/>
      <From/>
      <Design/>
      <For/>
      <Value/>
      <Trusted/>
      <Custom/>
      <Instant/>
      <Turn/>
    </div>
    <div class="content border-t-2">
      <Footer/>
    </div>
  </div>
</template>
<script>
import Header from './components/header/header.vue'
import From from './components/from/from.vue'
import Design from './components/design/design.vue'
import For from './components/for/for.vue'
import Value from './components/value/value.vue'
import Trusted from './components/trusted/trusted.vue'
import Custom from './components/custom/custom.vue'
import Instant from './components/instant/instant.vue'
import Turn from './components/turn/turn.vue'
import Footer from './components/footer/footer.vue'
export default {
  components: {
    Header,
    From,
    Design,
    For,
    Value,
    Trusted,
    Custom,
    Instant,
    Turn,
    Footer,

  }
}
</script>
<style scoped>
  .content{
    padding: 10px 190px;
  }
</style>