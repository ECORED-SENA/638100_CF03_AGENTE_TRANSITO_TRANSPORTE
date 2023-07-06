<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Aspectos generales del tránsito y el transporte 
    .bg3.mb-4
      .row.justify-content-center.align-items-center.mb-4           
        .col-lg-7.my-3
          p(data-aos="fade-down") El tránsito está definido como la movilización de personas, animales o vehículos por una infraestructura que puede ser una vía.

          p(data-aos="fade-down") El transporte es el traslado de personas, animales o cosas de un punto a otro a través de un medio físico, el cual puede ser un medio de transporte específico.

          p(data-aos="fade-down") La seguridad vial integra una serie de acciones y mecanismos para que se garantice el buen funcionamiento de la circulación en las vías previniendo accidentes.

          p(data-aos="fade-down") Todo lo anterior definido desde las normas que permiten una justa articulación de los actores viales y unos parámetros que se deben cumplir.      
        .col-lg-5.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/2.png', alt='')
        
      .row.justify-content-start.mb-3   
        .col-auto(data-aos="flip-down")
          .list
            .list__item
              .list__item__icon
                img(src='@/assets/curso/temas/3.svg', alt='')
            .list__txt.bg2.p-0.px-4
              h4.mb-0 Autoridades 

      .row.justify-content-center.align-items-center.mb-4
        .col.my-3.order-1
          p(data-aos="fade-down").mb-0 Es vital la presencia de las autoridades de tránsito en todos los rincones del territorio nacional garantizando la seguridad de los actores viales y la multiplicación del conocimiento de las normas de tránsito. Además la normatividad referenciada en el Código Nacional de Tránsito permite regular a las autoridades de control operativo, su actuación y procedimientos.              
        .col-lg-auto.my-3.order-lg-2
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/4.svg', alt='')

      p(data-aos="fade-down").mb-5 A nivel nacional se tiene las siguientes autoridades de tránsito en orden jerárquico:        
      img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/5.svg', alt='Esquema semicircular que muestra, en cadena, las autoridades de tránsito en Colombia, en orden jerárquico, asi:  1. Ministerio de transporte 2. Superintendencia general de puertos y transporte 3. Gobernadores y alcaldes 4. Organismos de tránsito 5. Agentes de tránsito y transporte 6. Policía nacional, Dirección de Tránsito y Transporte 7. Inspectores de: policía, tránsito y transporte, corregidores 8. Fuerzas militares')

    .row.justify-content-start.mb-3.pt-5   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Ámbito de aplicación

    p(data-aos="fade-down").mb-5 De acuerdo a la Ley 769 “Por la cual se expide el Código Nacional de Tránsito Terrestre y se dictan otras disposiciones”, este rige en absolutamente todo el territorio nacional y cobija a todos los peatones, usuarios, pasajeros, conductores, motociclistas, ciclistas, agentes de tránsito, y vehículos por las vías públicas o privadas que están abiertas al público, o en las vías privadas, que internamente circulen.            


    .row.justify-content-start.mb-3.pt-5   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Marco normativo del tránsito y el transporte

    p(data-aos="fade-down").mb-5 El transporte y el tránsito en Colombia están fundamentados en una serie de normas las cuales se mencionarán a continuación, específicamente para este componente formativo, tendientes a ilustrar la actividad del Agente de Tránsito y Transporte. En la siguiente tabla se encuentra la normatividad de tránsito y transporte: 
    .row.justify-content-start.align-items-center         
      .col-lg-10(data-aos="fade-right")
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/7.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.ts
                  h4 Normatividad de Tránsito y Transporte – Agentes
                  p.mb-0 Descargue el archivo Normatividad de Tránsito y Transporte – Agentes y reconozca las normas generales relacionadas y su descripción.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Normatividad_de_Transito_Transporte_Agentes.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download       
        
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
