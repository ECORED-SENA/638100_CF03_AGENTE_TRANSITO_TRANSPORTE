<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .bg1.p-4.brad.mb-5(data-aos="flip-down")   
      .row.justify-content-center.align-items-center         
        .col-lg-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/1.svg', alt='')

        .col-9.my-3
          p(data-aos="fade-down") Realizar los respectivos controles y aplicar adecuadamente las normas, genera confianza entre los actores viales y apoyo a las autoridades, ya que el tránsito y el transporte son actividades muy riesgosas en las que un accidente o cualquier desviación de la norma puede tener consecuencias graves es importante la correcta aplicación de la normatividad. Esto enmarcado desde la responsabilidad de la función pública y su régimen sancionatorio. 

          p(data-aos="fade-down").mb-0 Se puede ver los aspectos introductorios con más profundidad en el siguiente video.        

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-12(data-aos="fade-left")     
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Video.             
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
