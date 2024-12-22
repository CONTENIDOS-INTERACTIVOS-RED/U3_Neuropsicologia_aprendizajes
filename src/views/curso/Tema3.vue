<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Estructuras cerebrales involucradas en los procesos de memoria, atención y aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-36.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-verde.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") El cerebro, como órgano principal del sistema nervioso, desempeña un papel esencial en la percepción y comprensión de la realidad. A través de los sentidos (olfato, vista, oído, gusto y tacto), recoge estímulos que generan experiencias y aprendizajes. Este proceso depende de la activación de señales cerebrales que despiertan la curiosidad y motivan el aprendizaje, el cual varía según las tareas, habilidades y actividades, involucrando distintas áreas del cerebro.


    .row.position-relative.mb-0.py-4.bg-fondo-1.bg-full-width
      div.px-4.px-md-5.py-md-3

        h2 Memoria
        p.mb-4 La memoria es fundamental para almacenar y recuperar información, recordar eventos pasados, evocar emociones y ejecutar habilidades previamente aprendidas. Este proceso se divide en distintos sistemas:

        .row.mb-4
          .col-12.col-xl-8(data-aos="fade-right")
            AcordionA(tipo="b")
              .div(titulo="Memoria sensorial")
                p Retiene información por periodos breves (milisegundos a pocos segundos), captando estímulos inmediatos.
              .div(titulo="Memoria a corto plazo u operativa")
                p Almacena información temporalmente (15-30 segundos) con capacidad limitada de 7 ± 2 elementos. Ejemplo: recordar un número de teléfono mientras se marca.
              .div(titulo="Memoria a corto plazo u operativa")
                p.mb-4 Almacena información durante periodos extendidos y se clasifica en:
                .d-flex.flex-column
                  div.d-flex
                    img.me-2.d-flex.align-self-base(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
                    p.mb-0.text-bold Explícita o declarativa:
                  p.ms-4 - Episódica: recuerdos de eventos específicos, como un cumpleaños.
                  p.ms-4 - Semántica: conocimientos generales, como conceptos o datos históricos.
                div.d-flex
                  img.me-2.d-flex.align-self-base(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
                  p.mb-0 <strong>Implícita o no declarativa:</strong> recuerdos que no requieren esfuerzo consciente, como habilidades motoras (andar en bicicleta).
                div.d-flex
                  img.me-2.d-flex.align-self-base(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
                  p.mb-0  <strong>Autobiográfica:</strong> recuerdos relacionados con la propia vida.
                div.d-flex
                  img.me-2.d-flex.align-self-base(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
                  p.mb-0  <strong>Prospectiva:</strong> permite recordar acciones futuras, como citas médicas.
          .col-12.col-xl-4.d-none.d-xl-block(data-aos="fade-left")
            img(src='@/assets/curso/unidad/img-37.png', alt='Texto que describa la imagen')
        
        p.mb-4 Estructuras cerebrales implicadas en la memoria: 

        .row.mb-0
          .col-10.col-md-6.col-lg-6.mb-4.mx-auto(data-aos="fade-right")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-38.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Hipocampo
                p.text-small.px-4.text-center.pb-2 Hubicado en el lóbulo temporal, es clave en la formación de recuerdos nuevos y la consolidación de la memoria a largo plazo, especialmente la declarativa.
          .col-10.col-md-6.col-lg-6.mb-4.mx-auto(data-aos="fade-left")
            div.custom-image-card.rounded-8px
              img.mb-4(src='@/assets/curso/unidad/img-39.png', alt='Texto que describa la imagen')
              div.mb-4
                p.text-bold.text-center Corteza cerebral 
                p.text-small.px-4.text-center.pb-2 El lóbulo frontal y temporal son esenciales para el almacenamiento y procesamiento de recuerdos. La corteza prefrontal participa en la recuperación de información y en funciones ejecutivas, como la planificación.

    h2 Atención
    p.mb-4 La atención permite seleccionar, concentrarse y dirigir los recursos mentales hacia estímulos relevantes, ignorando los irrelevantes. Está vinculada con funciones como la percepción, memoria y aprendizaje. Existen varios tipos de atención:

    ImagenInfografica.color-secundario.mb-0
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/unidad/img-40.png', alt='Texto que describa la imagen')

      .tarjeta.bg-white.p-4(x="25.6%" y="22.2%" numero="+")
        .h5.mb-2 Selectiva
        p Enfoca en un estímulo ignorando otros. Ejemplo: escuchar una conversación específica en un lugar ruidoso.
      .tarjeta.bg-white.p-4(x="75%" y="22.2%" numero="+")
        .h5.mb-2 Dividida
        p Permite atender a múltiples estímulos o realizar varias tareas simultáneamente. Ejemplo: conducir y escuchar música.
      .tarjeta.bg-white.p-4(x="74.2%" y="75.5%" numero="+")
        .h5.mb-2 Alternante
        p Cambia el enfoque entre tareas de forma flexible. Ejemplo: ver televisión y conversar.
      .tarjeta.bg-white.p-4(x="25.6%" y="82.5%" numero="+")
        .h5.mb-2 Sostenida
        p Mantiene la concentración durante un periodo prolongado. Ejemplo: leer un libro durante media hora.

    .row.mb-4
      .d-flex.align-items-center
        div.d-flex.align-items-center.bg-morado.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-41.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 Ambos procesos cognitivos, memoria y atención, son cruciales para la adaptación, el aprendizaje y la interacción humana. Estudiar sus características y estructuras cerebrales asociadas contribuye a una comprensión integral del funcionamiento cerebral y su impacto en la vida diaria.
    
    h2 Estructuras cerebrales en las funciones ejecutivas y el aprendizaje
    p.mb-4 El cerebro humano, con su notable plasticidad, coordina procesos cognitivos y de aprendizaje mediante un conjunto de estructuras especializadas. Estas áreas no solo sostienen las funciones ejecutivas, como la atención y la toma de decisiones, sino que también facilitan la adquisición de nuevos conocimientos y habilidades. A continuación, se describen las principales estructuras cerebrales involucradas en estos procesos:

    p.mb-4 <strong>Figura 2.</strong> Estructuras cerebrales en las funciones ejecutivas y el aprendizaje 
    img(src='@/assets/curso/unidad/img-42.png', alt='Texto que describa la imagen').mb-4

    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        AcordionA(tipo="b")
          .div(titulo="Corteza prefrontal")
            p Responsable de las funciones ejecutivas como la atención, planificación, toma de decisiones y control de impulsos. Lesiones en esta área pueden afectar significativamente la concentración y la capacidad de mantener la atención.
          .div(titulo="Corteza cingulada anterior")
            p Crucial para la regulación emocional y la atención en tareas demandantes. Su disfunción puede provocar dificultades en situaciones estresantes o de alta carga cognitiva.
          .div(titulo="Circuito de atención (red de atención)")
            p Incluye áreas como la corteza parietal, la corteza prefrontal y el tálamo, integradas para facilitar la atención selectiva y sostenida.
          .div(titulo="Hipocampo")
            p Parte del sistema límbico, esencial para la formación de nuevas memorias y el aprendizaje espacial.
      .col-12.col-xl-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-43.png', alt='Texto que describa la imagen')
    .row.mb-4
      .col-12.col-xl-4.d-none.d-xl-block(data-aos="fade-right")
        img(src='@/assets/curso/unidad/img-44.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8(data-aos="fade-left")
        AcordionA(tipo="b")
          .div(titulo="Ganglios basales")
            p Involucrados en el aprendizaje de habilidades y hábitos, especialmente en el aprendizaje implícito y la adquisición de habilidades motoras.
          .div(titulo="Sistema de recompensa")
            p Incluye el núcleo accumbens y el área tegmental ventral (VTA), relacionados con la motivación y el refuerzo. Facilitan la repetición de comportamientos aprendidos mediante recompensas.
          .div(titulo="Conectividad cerebral")
            p Implica la plasticidad sináptica, la capacidad de las sinapsis para fortalecerse  o debilitarse con el tiempo, permitiendo la adaptación neuronal en respuesta a experiencias y aprendizajes.

    h2 Funciones ejecutivas y la atención

    .row.mb-5.mx-0
      .col-12.col-xl-8.d-flex.align-items-center.bg-amarillo.p-4(data-aos="fade-right")
        p.mb-0(data-aos="fade-up") La atención es un proceso cognitivo esencial que permite al individuo interactuar eficazmente con su entorno al seleccionar y enfocar recursos mentales en estímulos relevantes. Las áreas cerebrales implicadas en este proceso, como la corteza prefrontal y la red de atención, trabajan en conjunto para garantizar que el cerebro pueda priorizar información clave en situaciones complejas o demandantes.
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-45.png', alt='Texto que describa la imagen')

    h2 Aprendizaje y plasticidad cerebral
    p.mb-4 El aprendizaje, como lo explica Navarro et al. (2015), se fundamenta en la plasticidad cerebral, que permite al cerebro adaptarse y cambiar su estructura a lo largo de la vida. Esta flexibilidad es más eficiente en los primeros años de desarrollo, los denominados periodos sensibles, y es fundamental para adquirir nuevas habilidades.

    .row.position-relative.mb-5.py-4.bg-morado.bg-full-width
      div.px-4.px-md-5.py-md-3
        SlyderA(tipo="b").bg-white
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Corteza cerebral
              p Crucial para el aprendizaje, especialmente la corteza prefrontal, que regula funciones ejecutivas esenciales.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-46.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Sistema límbico
              p El hipocampo permite la formación de memorias nuevas, mientras que el sistema de recompensa motiva el aprendizaje mediante la asignación de valor a experiencias.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-47.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Ganglios basales
              p Facilitan el aprendizaje implícito y motor, consolidando hábitos y habilidades a través de la práctica.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-48.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Plasticidad sináptica
              p Refleja la capacidad de las conexiones neuronales para adaptarse, asegurando la retención y adaptación de conocimientos.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-49.png', alt='Texto que describa la imagen')

    p.mb-4 Las estructuras cerebrales responsables de las funciones ejecutivas y el aprendizaje destacan la extraordinaria capacidad del cerebro humano para adaptarse y evolucionar a lo largo de la vida. La corteza prefrontal, el hipocampo, los ganglios basales y el sistema de recompensa desempeñan roles esenciales en la regulación de procesos cognitivos y motivacionales. 

    .row.mb-5
      .col-12.col-xl-7.col-xxl-8.d-flex.flex-column
        .d-flex.align-items-start.bg-rosa.p-4.h-100(data-aos="fade-right")
          img.me-3(style="width: 90px" src='@/assets/curso/unidad/img-50.svg', alt='Texto que describa la imagen')
          .d-flex.flex-column
            p.pe-xl-3.mb-0(data-aos="fade-up") La plasticidad sináptica refuerza las conexiones neuronales en respuesta a las experiencias, subrayando la importancia de un entorno enriquecido para potenciar el desarrollo cerebral y el aprendizaje continuo. Este entramado dinámico de interacciones neuronales subraya la necesidad de estrategias educativas y prácticas que estimulen estas áreas para maximizar el potencial humano.
      .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-51.png', alt='Texto que describa la imagen')  


</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.material-complementario
  padding-top: 3rem
  border-top: 9px solid $color-sistema-e
</style>
