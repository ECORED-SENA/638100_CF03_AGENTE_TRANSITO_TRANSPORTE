<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p(data-aos="fade-down") Conocer y dar estricto cumplimiento a las normas, procesos y procedimientos dentro del ámbito del tránsito y el transporte pues la aplicación de la normatividad reduce riesgos en cuanto a normativa ambiental, al amparo de accidentes, la idoneidad de los operadores de estos vehículos y reduce la comisión de delitos asociados.
    p(data-aos="fade-down").mb-5 Explore el siguiente esquema y haga su propia síntesis de los temas y conceptos estudiados en este componente formativo:


    .row.justify-content-center
      .col-lg-10.mb-5(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="Esquema general de este componente formativo, que enuncia las temáticas desarrolladas en el mismo y destaca aspectos clave estudiados: Tema central: Agente de tránsito y transporte - implementación de registros según procedimiento técnico de policía y marco legal. Temas integradores: 1 Generalidades del tránsito y del transporte: Autoridades, ámbitos de aplicación, marco normativo. 2 Actores de tránsito. 3 Licencias de conducción: requisitos, facultades, renovación, otras. 4 Reglamentación para el transporte. 5 Requisitos legales para vehículos automotores: Licencias, revisiones, condiciones, otras. 6 Actuaciones especiales en casos de embriaguez: procedimientos, medidas, pruebas. 7 Axiología y valores asociados a la función pública.8 Manual de funciones de la ocupación laboral. 9 Régimen sancionatorio de la función pública.")
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
