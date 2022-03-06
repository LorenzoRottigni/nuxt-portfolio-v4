<template lang="pug">
#app.full-height.bg-circuit.bg-dark.border-primary
  //position absolute overlay
  FPSOverlay
  //vue router pages, pages extend pug layout
  main.h-100
    Nuxt
</template>

<script lang="ts">
import Vue from 'vue'
import FPSOverlay from '~/components/FPSOverlay.vue'
export default Vue.extend({
    components: { FPSOverlay }
})
</script>

<style lang="sass" scoped>
#app
  border: ridge 10px
</style>
