<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 Las prendas adquieren un valor especial cuando se realizan acabados a mano de sastrería básica, en este componente se realiza un recorrido por los diferentes procedimientos de sastrería básica, trazo y corte, adicionalmente se mencionan procesos específicos para básicos femeninos y masculinos. En el siguiente diagrama se presentan los diferentes conceptos y temas más importantes del componente. 
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="el diagrama presenta el contenido de la unidad, sus cuatro temas con subtemas y conceptos importantes.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
