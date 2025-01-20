<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Comportamiento del consumidor y segmentación de mercados'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
