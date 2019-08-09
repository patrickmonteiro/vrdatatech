<template>
  <q-page class="flex flex-center">
    <img alt="Quasar logo" src="statics/logoDataTech.png" width="250rem">
    <q-btn color="purple-8"
      class="full-width q-mt-xs"
      push
      label="Iniciar Realidade Aumentada"
      @click="routeModify()"/>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  methods: {
    routeModify () {
      this.$router.push({ name: 'aframe' })
    }
  }
}
</script>
