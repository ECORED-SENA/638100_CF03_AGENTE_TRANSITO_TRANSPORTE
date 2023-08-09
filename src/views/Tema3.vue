<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 3
      h1 Licencia de conducción

    .row.justify-content-center.align-items-center.bg8.mb-5          
      .col-lg-8.my-3.p-0
        .p-4.j
          p(data-aos="fade-down").mb-0 Este es un documento público, el cual es personal e intransferible, el cual es expedido por la autoridad designada para este fin y con la cual acredita para la conducción de vehículos automotores dependiendo de la categoría que se obtenga con validez en todo el territorio nacional.
      .col-lg-4.p-0
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/23.png', alt='')     

    .row.justify-content-start.mb-3
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Requisito

    p(data-aos="fade-down").mb-5 De acuerdo a lo establecido en la Ley 769 de 2022 por la cual se expide el Código Nacional de Tránsito Terrestre y se dictan otras disposiciones. A continuación, se muestran algunos requisitos que establece en su Artículo 19:                 
    h4(data-aos="fade-down").text-center.mb-4 REQUISITOS ESTABLECIDOS EN LA LEY 769 DE 2002

    .row.justify-content-center.mb-4           
      .col-lg-6.my-3.p-0(data-aos="fade-left")
        .bg8.brad.h-100.p-4
          img.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/24.svg', alt='')              
          h4 Para vehículos de servicio diferentes al servicio público
          ul.lista-ul.fa-ul
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Saber leer y escribir. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Mínimo de edad de 16 años cumplidos. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Aprobar examen teórico-práctico de conducción realizado por un organismo de tránsito o presentar certificado de aptitud de conducción otorgado por un centro de enseñanza automovilística aprobado por el Ministerio de Educación Nacional en coordinación con el Ministerio de Transporte. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Certificado de aptitud física y mental para conducir expedido por un médico registrado ante el Ministerio de Salud.              
      .col-lg-6.my-3.p-0(data-aos="fade-right")
        .bg9.brad.h-100.p-4
          img.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/25.svg', alt='')              
          h4 Para Vehículos de servicio público
          ul.lista-ul.fa-ul
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Saber leer y escribir. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Mínimo de edad de 18 años cumplidos. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Aprobar examen teórico-práctico de conducción realizado por un organismo de tránsito o presentar certificado de aptitud de conducción otorgado por un centro de enseñanza automovilística aprobado por el Ministerio de Educación Nacional en coordinación con el Ministerio de Transporte. 
            li 
              i.fas.fa-angle-right.c1
              p.mb-0 Certificado de aptitud física y mental para conducir expedido por un médico registrado ante el Ministerio de Salud, referidos a la conducción de vehículos de servicio público.   
              
    p(data-aos="fade-down").mb-5 Para los casos en los que se va a tramitar la licencia de conducción por primera vez, o se va a efectuar la recategorización y/o refrendación de la misma, se deberá demostrar la aptitud física, mental y de coordinación motriz, cumpliendo con los parámetros y límites nacionales establecidos, como se enuncia en el siguiente esquema:

    .bg10
      .row.justify-content-center.mb-5     
        .col-lg-8(data-aos="fade-left") 
          .titulo-sexto.color-acento-contenido
            h5 Figura 1.
            span Condiciones para tramitar Licencia de Conducción 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/27.svg', alt='Esquema circular que muestra las condiciones más importantes para tramitar licencia de conducción, los cuales son: 1 Capacidad de visión 2 Orientación auditiva 3 Agudeza visual, tiempos de reacción y recuperación de encandilamiento. 4 Coordinación entre aceleración y frenado. 5 Coordinación integral motriz. 6 Discriminación de colores y phoria horizontal y vertical.')
          figcaption.bgfig.mt-3 Nota: tomado de Secretaría Distrital de Movilidad (2002).     

    .row.justify-content-start.mb-3
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Facultades

    p(data-aos="fade-down").mb-5 El Artículo 18 de la Ley 769 de 2002, establece las facultades del titular de la licencia de conducción, se especifica que la misma habilita al titular para manejar vehículos automotores de acuerdo a la categoría que está establecida en el reglamento, categorías que son expuestas en la siguiente tabla:

    .row.justify-content-center.mb-5     
      .col-lg-10(data-aos="fade-down") 
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span Categorías de Licencias de Conducción      
        .tabla-a.color-acento-contenido(data-aos="fade-left") 
          table
            caption Nota. Normatividad en Tránsito y Transporte. Agentes. SENA (2022)
            tbody
              tr
                td.bgt1.text-center.text-bold(rowspan='2') Vehículos particulares
                td.text-bold MOTOCICLETAS
                td #[b A1:] Motocicletas con cilindrada hasta 125 c.c.
                td #[b A2:] Motocicletas, motociclos y mototriciclos con cilindrada mayor a 125 c.c.
                td 
              tr
                td.text-bold VEHÍCULOS
                td #[b B1:] Automóviles, motocarros, cuatrimotos, camperos, camionetas y microbuses de servicio particular.
                td #[b B2:] Camiones rígidos, busetas y buses de servicio particular.
                td #[b B3:] Vehículos articulados servicio particular.
              tr
                td.bgt1.text-center.text-bold Servicio público
                td.text-bold VEHÍCULOS
                td #[b C1:] Automóviles, camperos, camionetas y microbuses de servicio público.
                td #[b C2:] Camiones rígidos, busetas y buses de servicio público.
                td #[b C3:] Vehículos articulados servicio público.          

    p(data-aos="fade-down").mb-5 No es restrictivo que en la licencia de conducción de mayor categoría se pueda operar vehículos de categoría inferior. 

    .row.justify-content-start.mb-3
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Renovación 

    .bg4.p-4.brad.mb-5(data-aos="flip-down")   
      .row.justify-content-center.align-items-center
        .col.my-3
          p(data-aos="fade-down").mb-0 Es importante resaltar que la solicitud de renovación de las licencias de conducción no se efectuará si precede una sanción contra su tenencia o el titular de misma, donde se configure como deudor de pago de infracciones ejecutoriadas, para la renovación de la misma se tendrá en cuenta las siguientes vigencias establecidas para la licencia de conducción:             
        .col-lg-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/28.svg', alt='')

    h4(data-aos="fade-down").t1 Vigencia de la Licencia de Conducción   
    p(data-aos="fade-down").mb-5 De acuerdo a las nuevas vigencias de las licencias de conducción, la renovación procederá en los siguientes periodos: 

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-12.up(data-aos="fade-left")     
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/surZaIoYGN4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Video. Licencia de conducción - Renovación de la Licencia de Conducción            
    .bg11                   
      p(data-aos="fade-down").mb-5 La obligatoriedad de renovar la licencia de conducción de acuerdo al rango de edad y la vigencia contemplada en el Decreto 19 de 2012, en la siguiente tabla se muestra las condiciones:

      .row.justify-content-center.mb-5     
        .col-lg-10(data-aos="fade-down") 
          .titulo-sexto.color-acento-contenido
            h5 Tabla 2.
            span Categorías de Licencias de Conducción      
          .tabla-a.color-acento-contenido(data-aos="fade-left") 
            table
              caption.bgfig Nota. Tomado de Secretaría Distrital de Movilidad (2002)
              tbody.bgw.text-center
                tr
                  td.bgt1.text-center.text-bold RANGO DE EDAD
                  td.bgt1.text-center.text-bold VIGENCIA DE LA LICENCIA
                  td.w-300.bgt1.text-center.text-bold EDAD EN 2012 AL MOMENTO DE LA EXPEDICIÓN DEL DECRETO
                  td.w-300.bgt1.text-center.text-bold OBLIGACIÓN DE RENOVAR

                tr
                  td(rowspan='3') Menor de 60 años
                  td(rowspan='3')  10
                  td.w-300 20 años
                  td.w-300.text-start Cuando cumpla 30 años en el 2022
                tr
                  td 55 años
                  td.text-start Cuando cumpla 65 años en el 2022
                tr
                  td.w-300 59 años
                  td.w-300.text-start Cuando cumpla 65 años en el 2018
                tr
                  td(rowspan='3') Entre 60 y 80 años
                  td(rowspan='3') 5
                  td.w-300 62 años
                  td.w-300.text-start Cuando cumpla 67 años en el 2017
                tr
                  td 65 años
                  td.text-start Cuando cumpla 70 años en el 2017
                tr
                  td.w-300 78 años
                  td.w-300.text-start Cuando cumpla 81 años en el 2015
                tr
                  td(rowspan='3') Mayor de 80 años
                  td(rowspan='3') 1
                  td.w-300 80 años
                  td.w-300.text-start Cuando cumpla 81 años en el 2013
                tr
                  td.w-300 81 años
                  td.w-300.text-start Cuando cumpla 82 años en el 2013
                tr
                  td.w-300 83 años
                  td.w-300.text-start Cuando cumpla 84 años en el 2013

      .row.justify-content-start.mb-3
        .col-auto(data-aos="flip-down")
          .list
            .list__item
              .list__item__icon
                img(src='@/assets/curso/temas/3.svg', alt='')
            .list__txt.bg2.p-0.px-4.btop1
              h4.mb-0 Causales de suspensión

      p(data-aos="fade-down").mb-5 El Artículo 26 de la Ley 769 de 2002, establece las siguientes causales de suspensión o cancelación de la licencia de conducción: 

      .row.justify-content-center.mb-4           
        .col-lg-6.my-3(data-aos="fade-left")
          .bga.brad.h-100.p-4
            img.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/31.svg', alt='')              
            h4 CAUSALES DE SUSPENSIÓN
            ul.lista-ul.fa-ul
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por disposición de las autoridades ante una imposibilidad física o mental transitoria que le imposibilite conducir, misma que debe ser soportada medicamente. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por decisión judicial. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Cuando las autoridades competentes encuentran en flagrancia al conductor en estado de embriaguez o bajo los efectos de drogas alucinógenas. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por reincidencia en la violación de las normas de tránsito en un periodo no superior a un año, efectuándose una suspensión por un término de seis meses. Por prestar el servicio público de transporte en vehículos particulares, salvo que las condiciones de orden público lo justifiquen. 
      
        .col-lg-6.my-3(data-aos="fade-right")
          .bga.brad.h-100.p-4
            img.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/32.svg', alt='')              
            h4 CAUSALES DE TERMINACIÓN
            ul.lista-ul.fa-ul
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por disposición de las autoridades ante una imposibilidad física o mental permanente que le imposibilite conducir, debe ser soportada medicamente. Por decisión judicial. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por muerte del titular. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Cuando las autoridades competentes encuentran en flagrancia al conductor en estado de embriaguez o bajo los efectos de drogas alucinógenas, presentando reincidencia en estas condiciones. 
              li 
                i.fas.fa-angle-right.c1
                p.mb-0 Por reincidencia al prestar el servicio público de transporte en vehiculos particulares sin justa causa. 

    p(data-aos="fade-down") La suspensión o cancelación aplicada a la licencia de conducción implica la entrega del documento a la autoridad competente para imponer la sanción ya sea para el periodo de suspensión o para la cancelación establecida sobre la misma.


</template>

<script>
export default {
  name: 'Tema3',
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
