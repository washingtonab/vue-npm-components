<template>
  <div id="app">
    <Topo></Topo>
    <Centro></Centro>
    <Rodape></Rodape>
  </div>
</template>

<script>

import Topo from './components/Topo.vue'
import Centro from './components/Centro.vue'
import Rodape from './components/Rodape.vue'

export default {
  name: 'ss',
  components: {
    Topo,
    Centro,
    Rodape
  }
}

</script>

<style>
</style>
