<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 7
      h1 Régimen sancionatorio de la función pública

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7.my-3
        p(data-aos="fade-down") El régimen sancionatorio de la función pública está reglamentado en la Ley 1474 del 12 de julio de 2011 por medio del cual las normas están orientadas a fortalecer los mecanismos de prevención, investigación y sanción de actos de corrupción y la efectividad del control de la gestión pública, que busca salvaguardar la moralidad pública, transparencia y legalidad dentro del desempeño del empleo en cargo público.     
        .bg12.p-4
          h4.t1(data-aos="fade-down").mb-0 ¡Nota importante!

          p(data-aos="fade-down").mb-0 La aplicación de medidas sancionatorias se efectúa teniendo en cuenta dos formas: medidas penales y medidas administrativas. En ambos casos es fundamental tener en cuenta las leyes, artículos y funcionalidades de la reglamentación vigente.
                    
      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/83.png', alt='')

    .row.justify-content-center.align-items-center
      .col-lg-3.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/84.png', alt='')       
      .col-lg-9.my-3
        .tarjeta.color-secundario.p-3.mb-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/7.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.ts
                  h4 Medidas penales para lucha contra corrupción
                  p.mb-0 Descargue el archivo Medidas penales para lucha contra corrupción y reconozca el marco legal de la función pública, según la ley 1474 de 2011.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Medidas_penales_para_lucha_contra_corrupcion.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download      

        .tarjeta.color-secundario.p-3.mb-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/7.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.ts
                  h4 Medidas administrativas para lucha contra corrupción
                  p.mb-0 Descargue el archivo Medidas administrativas para lucha contra corrupción y reconozca el marco legal de la función pública, según la ley 1474 de 2011.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Medidas_administrativas_para_lucha_contra_corrupcion.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download      
                    
     

</template>

<script>
export default {
  name: 'Tema7',
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
