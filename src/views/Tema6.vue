<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 6
      h1 Actuaciones especiales en casos de embriaguez 
    p(data-aos="fade-down").mb-5 Los casos de embriaguez por parte de conductores vehiculares ya sea de transporte particular o de servicio público, conllevan a poner en riesgo la integridad propia del conductor y de los actores viales involucrados, acciones que acarrean sanciones y multas de acuerdo a los lineamientos de ley establecidos.

    .row.justify-content-start.mb-3   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4.btop2
            h4.mb-0 Procedimientos

    .row.justify-content-center.align-items-start.mb-4          
      .col-lg-2.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/71.svg', alt='')
      .col-lg-10.my-3
        h4.t1(data-aos="fade-down") Artículo 150 de la Ley 769 de 2002
        p(data-aos="fade-down") Las autoridades de tránsito están en la capacidad y potestad de solicitar al o los conductores la práctica del examen de embriaguez, para determinar si él mismo se encuentra bajo un estado de embriaguez, drogas, estupefacientes, alucinógenas o hipnóticas. 
        p(data-aos="fade-down") Todos los casos en los que se demuestre por medio del examen de embriaguez que el conductor del vehículo automotor se encuentra bajo el estado de embriaguez el vehículo será inmovilizado, en el caso en que el conductor se niegue a practicarse el examen se le impondrá una multa por $44.971.000 valor establecido en el año 2022. 

      .col-lg-2.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/72.svg', alt='')
      .col-lg-10.my-3
        h4.t1(data-aos="fade-down") El artículo 151 de la ley 769 de 2002
        p(data-aos="fade-down") Establece que para los casos en los que un conductor en estado de embriaguez cause lesiones y homicidio en un accidente de tránsito o que sin justificación abandone el lugar del accidente, adicional a las sanciones establecidas en el Código Penal, al mismo se le aplicará la suspensión de su licencia por el término de cinco (5) años.

      .col-lg-2.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/73.svg', alt='')
      .col-lg-10.my-3
        h4.t1(data-aos="fade-down") La ley 1696 de 2013
        p(data-aos="fade-down") Establece en su Artículo 131. Multas, el conducir en estado de embriaguez o bajo los efectos de sustancias psicoactivas, será conducta sancionada por medio de las multas establecidas en la presente ley, adicional a lo mencionado para los conductores en la modalidad de servicio público, transporte escolar o instructores de conducción, las sanciones o multas establecidas se duplicarán. Las sanciones al conductor serán aplicadas de acuerdo a los grados de alcoholemia y el nivel de reincidencia, establecido de la siguiente manera en la tabla:                

    .row.justify-content-center.align-items-center         
      .col-lg-10(data-aos="fade-right")
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/7.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.ts
                  h4 Sanciones según grado de alcoholemia y nivel de reincidencia
                  p.mb-0 Descargue el archivo Sanciones según grado de alcoholemia y nivel de reincidencia y reconozca el detalle de cada caso y sus acciones de regulación.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Sanciones_segun_grado_alcoholemia_nivel_reincidencia.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download  

    .row.justify-content-start.mb-3   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4.btop2
            h4.mb-0 Medidas penales

    p(data-aos="fade-down").mb-5 Las medidas penales establecidas para las actuaciones especiales en casos de embriaguez están definidas en la Ley 1696 de 2013, Artículo 2° por medio del cual adiciona un numeral al Artículo 110 de la Ley 599 de 2000, Código penal, en el cual se dictan las siguientes medidas en la tabla:

    .row.justify-content-center.mb-5     
      .col-lg-8(data-aos="fade-down") 
        .titulo-sexto.color-acento-contenido
          h5 Tabla 13.
          span Medidas penales para conductores en estado de embriaguez
        .tabla-a.color-acento-contenido(data-aos="fade-left") 
          table
            caption.bgfig Nota: tomado de Función Pública- Ley 1969 de 2013
            tbody.bgw.text-center
              tr
                td.w-300.bgt1.text-center.text-bold Ley
                td.bgt1.text-center.text-bold Ley 1696 de 2012 (19 de Diciembre) 
              tr
                td.w-300.text-bold Disposiciones
                td.text-start Por medio de la cual se dictan disposiciones penales y administrativas para sancionar la conducción bajo el influjo del alcohol u otras sustancias psicoactivas.                    
              tr
                td.w-300.text-bold Artículo
                td.text-start Artículo  2°. Adiciónese un numeral al artículo 110 de la Ley 599 de 2000, Código Penal, el cual quedará así: #[br]#[br] Artículo 110. Circunstancias de agravación punitiva para el homicidio culposo. La pena prevista en el artículo anterior se aumentará: #[br]#[br] (…) #[br]#[br] 6. Si al momento de cometer la conducta el agente estuviese conduciendo vehículo automotor bajo el grado de alcoholemia igual o superior al grado 1° o bajo el efecto de droga o sustancia que produzca dependencia física o síquica, y ello haya sido determinante para su ocurrencia, la pena se aumentará de las dos terceras partes al doble, en la pena principal y accesoria.

    .row.justify-content-start.mb-3   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4.btop2
            h4.mb-0 Medidas administrativas

    p(data-aos="fade-down").mb-5 Las medidas establecidas para las actuaciones especiales en casos de embriaguez están definidas en la Ley 1696 de 2013, Artículo 3° por medio del cual se modifica el parágrafo 26 de la Ley 769 de 2002, artículo modificado por el Artículo 7° de la Ley 1383 de 2010, el cual queda definido en la siguiente tabla de la siguiente manera:

    .row.justify-content-center.mb-5     
      .col-lg-8(data-aos="fade-down") 
        .titulo-sexto.color-acento-contenido
          h5 Tabla 14.
          span Medidas administrativas para conductores en estado de embriaguez
        .tabla-a.color-acento-contenido(data-aos="fade-left") 
          table
            caption.bgfig Nota: tomado de Función Pública- Ley 1969 de 2013. 
            tbody.bgw.text-center
              tr
                td.w-300.bgt1.text-center.text-bold Ley
                td.bgt1.text-center.text-bold Ley 1696 de 2012 (19 de Diciembre) 
              tr
                td.w-300.text-bold Disposiciones
                td.text-start Por medio de la cual se dictan disposiciones penales y administrativas para sancionar la conducción bajo el influjo del alcohol u otras sustancias psicoactivas.                    
              tr
                td.w-300.text-bold Artículo
                td.text-start Artículo  3°. Modifíquese el parágrafo del artículo 26 de la Ley 769 de 2002, artículo modificado por el artículo 7° de la Ley 1383 de 2010, el cual quedará así: #[br]#[br]Parágrafo. La suspensión o cancelación de la Licencia de Conducción implica la entrega obligatoria del documento a la autoridad de tránsito competente para imponer la sanción por el periodo de la suspensión o a partir de la cancelación de ella. #[br]#[br]La resolución de la autoridad de tránsito que establezca la responsabilidad e imponga la suspensión o cancelación de la licencia de conducción, deberá contener la prohibición expresa al infractor de conducir vehículos automotores durante el tiempo que se le suspenda o cancele la licencia. #[br]#[br]La notificación de la suspensión o cancelación de la licencia de conducción se realizará de conformidad con las disposiciones aplicables del Código de Procedimiento Administrativo y de lo Contencioso Administrativo. #[br]#[br]Una vez se encuentre en firme la resolución de la autoridad de tránsito mediante la cual cancela la licencia de conducción, por las causales previstas en los numerales 6° y 7° de este artículo, se compulsarán copias de la actuación administrativa a la Fiscalía General de la Nación, para lo de su competencia. #[br]#[br]Transcurridos veinticinco (25) años desde la cancelación, el conductor podrá volver a solicitar una nueva licencia de conducción.
  
    .row.justify-content-start.mb-3   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4.btop2
            h4.mb-0 Pruebas directas e indirectas

    .row.justify-content-center.align-items-center.mb-4           
      .col-lg-3.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/74.png', alt='')

      .col-lg-9.my-3
        h4.t1(data-aos="fade-down") La resolución 1844 de 18 de diciembre de 2015:  
        p(data-aos="fade-down") El Instituto de Medicina Legal y Ciencias Forenses, adoptó la segunda versión de la Guía para la Medición Indirecta de Alcoholemia a través de aire aspirado en la cual se establece que la muestra idónea para calcular la alcoholemia mediante prueba indirecta corresponde al aire de los alvéolos pulmonares, sin embargo al ser esta prueba mediante aire es una medición que se agota por lo cual no procede la cadena de custodia sobre la misma.        
        p(data-aos="fade-down") La medición de la prueba indirecta de alcoholemia se realiza con un analizador de etanol en aire espirado que cumpla con los requisitos establecidos en las Resoluciones 64189 del 2015 y 88650 del 2015 de la Superintendencia de Industria y Comercio, debidamente calibrado por un proveedor con la competencia técnica para efectuar, adicional a lo anterior previo a efectuar la medición se debe efectuar la verificación del estado de la batería, el funcionamiento de la conexión medidor de alcohol-impresora, la configuración establecida para el medidor, la disponibilidad de boquillas desechables, un huellero y formato para garantizar el diligenciamiento de la medición efectuada.

    p(data-aos="fade-down").mb-5 Dentro del proceso para efectuar la medición de la prueba indirecta de alcoholemia se debe tener en cuenta los siguientes puntos: 

    .row.justify-content-center.align-items-start.mb-4
      .col-lg-7.my-3
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg16")
          .row.justify-content-center(titulo="Medición de la prueba de Alcoholemia")
            .col-12
              p Informar al conductor el objeto y tipo de prueba a practicar, los efectos y consecuencias que proceden de no permitirse efectuar la medición, el trámite y proceso administrativo para defenderse si se inicia una orden de comparendo y todas las demás consideraciones que garanticen la información al conductor previo a efectuar la prueba.  
          .row.justify-content-center(titulo="Preguntas previas a la prueba")
            .col-12
              p Informar al conductor el objeto y tipo de prueba a practicar, los efectos y consecuencias que proceden de no permitirse efectuar la medición, el trámite y proceso administrativo para defenderse si se inicia una orden de comparendo y todas las demás consideraciones que garanticen la información al conductor previo a efectuar la prueba.
          .row.justify-content-center(titulo="Instrucciones al examinado")
            .col-12
              p Debe respirar, retener el aire y luego soplar de manera sostenida dentro de la boquilla (desechable) hasta que se le indique, luego debe detenerse al contar con el volumen de aire requerido para efectuar la medición.
  
          .row.justify-content-center(titulo="Los resultados")
            .col-12
              p Se le mostrarán al examinado y se procederá a imprimirlos. 
          .row.justify-content-center(titulo="Segunda medición")
            .col-12
              p Para el caso en el que la primera medición arroje un resultado mayor o igual a 20 mg/100 ml se debe practicar una segunda medición que no supere un rango de tiempo entre una prueba y otra como mínimo de 2 minutos y no superior a 10 minutos.  
          .row.justify-content-center(titulo="Diligenciamiento de la Declaración")
            .col-12
              p Aplicación de un sistema de aseguramiento de la calidad en la medición de alcoholemia a través del aire aspirado, del cual se le entregará una copia al conductor con copia de los resultados de la medición. 
          .row.justify-content-center(titulo="Método invasivo de prueba directa")
            .col-12
              p Para establecer los niveles de alcohol en la sangre, dependiendo de la concentración y grados volumétricos, dicha prueba requiere una toma de muestra de sangre venosa para un análisis de laboratorio donde se establece la cromatografía de gases junto con la cantidad de etanol en la sangre y concentración en el celebro, los anteriores parámetros van ligados al análisis de peso, talla y sexo del examinado.                                                              
      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/75.png', alt='')

    .row.justify-content-start.mb-3.pt-5   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Axiología
    p(data-aos="fade-down") La axiología estudia identifica, y hace medición de los valores, dependiendo de su naturaleza y los juicios que se generan a partir de ellos y, por lo tanto, se deduce que un valor es un principio para establecer un juicio, por eso la relación es tan estrecha entre la axiología y la ética.
    .row.justify-content-center.align-items-center.pb-5
      .col-lg-auto.my-3 
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/76.svg', alt='')     
      .col.my-3 
        p(data-aos="fade-down") Estos valores mencionados están organizados de manera distinta en cada persona y afectan en su conducta. Es así, como desde la axiología, es posible encontrar maneras de cambiar ciertos aspectos éticos de las sociedades y sus individuos.

        p(data-aos="fade-down").mb-0 A continuación, se enuncian algunos aspectos generales y claves que, sobre la axiología, se deben tener en cuenta: 

    .bg14
      .row.justify-content-center.align-items-start           
        .col-lg-4.p-0
          img.img-t.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/36.png', alt='')

        .col-lg-8
          .bgw.p-5.brad 
            SlyderE(indicadores="derecha")
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-0
                  h4 La axiología como disciplina 
                  p La axiología se encarga de hacer análisis, estudio y reflexión sistemática de los valores instaurados en colectivos, sociedades y entornos grupales de personas. A partir de ello, aporta a la construcción de criterios del orden ético y normativo.          
                .col-md-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/77.svg', alt='')         

              .row.justify-content-center
                .col-md-10.mb-4.mb-md-0
                  h4 Aporte a la construcción de saberes y organización social 
                  p Mediante los procesos axiológicos es posible establecer la compresión del pensamiento humano y afianzar la gestación y transformación de los valores que rigen las conductas y las reglas de comportamiento social. Los valores siempre son objetivos, dinámicos, permanentes.          
                .col-md-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/77.svg', alt='') 

              .row.justify-content-center
                .col-md-10.mb-4.mb-md-0
                  h4 Configuración de la interacción armónica de las sociedades 
                  p La suma de todos los comportamientos establece el modo de actuar en una sociedad; por lo tanto, desde la axiología hay manera de cambiar ciertos actos de la sociedad a través de la perspectiva ética.          
                .col-md-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/77.svg', alt='') 

              .row.justify-content-center
                .col-md-10.mb-4.mb-md-0
                  h4 Los valores y la función pública 
                  p Los valores, en el ámbito de la institucionalidad pública, resultan imprescindibles dado que el contexto cultural y el concepto de nación, predisponen las formas de actuar y proceder de las personas y, para el logro de una armonía general, la axiología agrupa los criterios e insta a una visión colectiva en los individuos.          
                .col-md-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/77.svg', alt='') 

              .row.justify-content-center
                .col-md-10.mb-4.mb-md-0
                  h4 Actuaciones transparentes del Servidor Público 
                  p En relación con el plano axiológico, el funcionario público tiene la obligación de actuar siempre de manera transparente, predecible y comprensible. La transparencia, imparcialidad y justicia, son valores clave que fundamentan su rol, desde lo ético.          
                .col-md-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/77.svg', alt='') 

    .row.justify-content-start.mb-3.pt-5   
      .col-auto(data-aos="flip-down")
        .list
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/3.svg', alt='')
          .list__txt.bg2.p-0.px-4
            h4.mb-0 Manual de funciones de la ocupación laboral

    .row.justify-content-center.align-items-center
      .col-lg-7.my-3
        p(data-aos="fade-down") Esta es una herramienta en gestión del talento humano que básicamente se constituye en un documento que permite reunir las diferentes descripciones de puestos de trabajo dentro de cualquier organización, con el objetivo de establecer las funciones y competencias laborales de esos mismos empleos que conforman la planta de personal en una institución pública, además involucra en estas descripciones requerimientos de conocimiento, experiencia y otras competencias para lograr desempeñar adecuadamente el cargo.       
        p(data-aos="fade-down") A nivel gerencial es un insumo importante en procesos de planeación, pues propende por gestionar los ingresos, la permanencia y el desarrollo del personal contratado en las organizaciones públicas, esta información debe ser compartida a todo nivel para su conocimiento.       
        .bg12.p-4.brad.mb-4
          p(data-aos="fade-down").mb-0 Que estos manuales de funciones estén implementados permite que cada uno de los trabajadores tenga claridad de lo que se espera de él y que logre los objetivos planteados. Esto se va a ver reflejado en organizaciones más sólidas, menos posibilidad de conflictos entre las áreas que se relacionen y se define claramente las responsabilidades.
                    
      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/82.png', alt='')

                                                                                                           
</template>

<script>
export default {
  name: 'Tema6',
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
