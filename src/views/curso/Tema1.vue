<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Definición y principios de la neuropsicología'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-4 El entendimiento del ser humano desde una perspectiva holística representa un desafío considerable, pues somos el resultado de diversas esferas: biológica, psicológica, química, neurológica, física y genética. En respuesta a esta complejidad surge la neuropsicología, una ciencia que busca integrar estas dimensiones para comprender quiénes somos y cómo se originan nuestras conductas.

    .row.mb-4
      .col-12.col-xl-7.col-xxl-8.d-flex.flex-column
        .d-flex.align-items-start.bg-rosa.p-4.mb-4(data-aos="fade-left")
          img.me-3(style="width: 90px" src='@/assets/curso/unidad/img-2.svg', alt='Texto que describa la imagen')
          .d-flex.flex-column
            p.pe-xl-3.mb-0(data-aos="fade-up") Según Portellano (2005), la neuropsicología es un campo interdisciplinar que analiza aspectos del sistema nervioso como anatomía, funcionamiento, patologías, desarrollo, genética, farmacología y química, con el propósito de entender a fondo los procesos cognitivos y el comportamiento humano. Su alcance no se limita a la relación cerebro-conducta, sino que incluye también un enfoque social que resalta la influencia del entorno, estableciendo un triángulo de análisis entre cerebro, individuo y medio ambiente.
        p.mb-4 El cerebro, como órgano complejo, no solo regula funciones biológicas básicas, sino que también sostiene procesos cognitivos superiores. Su estudio permite entender cómo las áreas y redes neuronales interactúan para influir en nuestras conductas, emociones y pensamientos, identificando además alteraciones que afectan procesos cognitivos como percepción, atención, pensamiento, memoria, lenguaje y relaciones sociales.
        span.text-bold A modo introductorio, se destacan algunos de estos procesos:
      .d-none.d-xl-block.col-xl-5.col-xxl-4.mx-auto.mt-4.mt-xl-0(data-aos="fade-right")
        img(src='@/assets/curso/unidad/img-3.png', alt='Texto que describa la imagen')  

    .row.position-relative.mb-5.py-4.bg-morado.bg-full-width
      div.px-4.px-md-5.py-md-3
        SlyderA(tipo="b").bg-white
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Memoria
              p Se fundamenta en el almacenamiento de recuerdos a través del hipocampo y la corteza cerebral. Alteraciones en estas regiones pueden provocar amnesia o dificultades para aprender.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-4.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Lenguaje
              p Depende de áreas como Broca y Wernicke. Su análisis permite comprender trastornos como la afasia, evidenciando cómo el daño cerebral afecta la capacidad de comunicación.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-5.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Aprendizaje
              p Vinculado a la plasticidad cerebral, implica la reorganización neuronal. Su estudio es esencial en personas con dificultades relacionadas con el aprendizaje.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-6.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Relaciones sociales
              p La neurociencia social ha identificado que circuitos cerebrales específicos fomentan la empatía y la comprensión emocional. Las alteraciones en estos sistemas pueden afectar negativamente las interacciones personales.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-7.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Percepción
              p Proceso por el cual el cerebro interpreta estímulos sensoriales, influenciado por experiencias previas, emociones y el contexto en que ocurren.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-8.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Atención
              p Permite enfocarse en estímulos específicos, siendo fundamental para procesar información relevante de manera eficiente.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-9.png', alt='Texto que describa la imagen')
          .row.p-4.px-md-5.py-lg-5.justify-content-between
            .col-md-12.col-lg-7.mb-4.mb-md-0
              p.text-bold Pensamiento
              p Incluye procesos como memoria, razonamiento y creatividad, esenciales para resolver problemas y tomar decisiones.
            .d-none.d-lg-block.col-md-6.col-lg-4
              figure
                img(src='@/assets/curso/unidad/img-10.png', alt='Texto que describa la imagen')

    .row.mb-4
      .col-12.col-xl-10(data-aos="fade-right")
        p.mb-4 La neuropsicología no solo profundiza en las capacidades cognitivas, sino que también propone estrategias para optimizar el aprendizaje y la comunicación, contribuyendo al bienestar general. Su aplicación es amplia, especialmente en entornos clínicos donde evalúa, diagnostica y trata alteraciones como lesiones cerebrales, enfermedades neurodegenerativas o trastornos del desarrollo. Las pruebas neuropsicológicas permiten identificar déficits cognitivos, formular diagnósticos y desarrollar programas de rehabilitación personalizados.
        span.text-bold Entre sus principios fundamentales, la neuropsicología destaca:
      .col-2.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-11.png', alt='Texto que describa la imagen')
      
    .row.mb-4
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-right")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-12.svg', alt='Texto que describa la imagen')
            span Su carácter neurocientífico, basado en métodos analíticos y experimentales.
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-down")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-13.svg', alt='Texto que describa la imagen')
            span El estudio de funciones mentales superiores como memoria, lenguaje, razonamiento y percepción.
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-left")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-14.svg', alt='Texto que describa la imagen')
            span La relación bidireccional entre cognición y emoción, que evidencia cómo influyen mutuamente.
    .row.mb-4
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-right")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-15.svg', alt='Texto que describa la imagen')
            span La individualidad en los diagnósticos y tratamientos, considerando factores como edad, género, educación y cultura.
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-up")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-16.svg', alt='Texto que describa la imagen')
            span La neuroplasticidad, que permite al cerebro reorganizarse tras lesiones.
        .col-12.col-md-6.col-xl-4.d-flex.align-items-center.fs-16(data-aos="fade-left")
          .d-flex.align-items-center.bg-rosa.px-3.py-4.rounded.h-100
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-17.svg', alt='Texto que describa la imagen')
            span La localización de funciones, que asigna roles específicos a distintas áreas cerebrales, facilitando intervenciones dirigidas.
    .row.mb-5
        .col-12.d-flex.align-items-center.fs-16(data-aos="fade-up")
          .d-flex.align-items-center.bg-verde.px-3.py-4.rounded
            img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-18.svg', alt='Texto que describa la imagen')
            span En conclusión, la <strong>neuropsicología</strong> es una disciplina clave para abordar la complejidad del ser humano desde una visión integradora que combina biología, psicología y neurociencia. Su contribución no solo amplía el entendimiento del comportamiento y las capacidades cognitivas, sino que también promueve estrategias prácticas para mejorar la calidad de vida, las relaciones interpersonales y el bienestar general.

    .bg-full-width.border-top-9-azul
      .px-4.px-md-5.pt-5.pb-0
        h2 Material complementario
        .row
          .col-12.col-md-6.col-lg-8
            p.text-small
            p.d-flex.my-4
              img.me-3.mb-auto.mt-1(src='@/assets/componentes/youtube-icon.svg' :style="{'max-width':'16px'}")
              a.text-small.text-primary(target="_blank", href=" https://www.youtube.com/watch?v=09Knu34bYdw") Universidad de Deusto / Deustuko Unibertsitatea. 2015 Conceptos básicos del Business Intelligence.
            p.d-flex.my-4
              img.me-3.mb-auto.mt-1(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a.text-small.text-primary(target="_blank", href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/114035 ") Curto Díaz, J. & Conesa Caralt, J. (Il.). (2015). ¿Cómo crear un data warehouse?: ( ed.). Editorial UOC. 
          .col-12.col-md-6.col-lg-3
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='Texto que describa la imagen')


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

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1
</style>
