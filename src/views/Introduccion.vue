<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        p.mb-4 La neuroplasticidad, definida como la capacidad del cerebro para reorganizarse y adaptarse a lo largo de la vida, es un concepto central para comprender el aprendizaje y el desarrollo cognitivo. Esta unidad explora cómo este fenómeno permite a los individuos aprender en diversos contextos, además de ofrecer estrategias para diseñar intervenciones educativas efectivas que respondan a las necesidades de cada estudiante.
        .bg-rojo.p-4
          span El enfoque de esta unidad se centrará en aplicar la neuroplasticidad en el diseño de intervenciones educativas, promoviendo el aprendizaje y desarrollo cognitivo en todas las etapas de la vida. Se proporcionarán herramientas para crear aulas inclusivas y estimulantes, atendiendo las diferencias individuales y potenciando el aprendizaje, particularmente en estudiantes con necesidades diversas.
      .col-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-1.png', alt='Texto que describa la imagen')

    .row.mb-4
      .d-flex.align-items-center
        div.d-flex.align-items-center.bg-verde.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-2.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 La estructura abarca tres áreas: los principios de la neuroplasticidad, su relación con el desarrollo cognitivo y sus implicaciones para la enseñanza. Este enfoque permitirá a los estudiantes adquirir habilidades prácticas y una comprensión integral del tema, preparándolos para enfrentar los desafíos educativos actuales de manera efectiva y profesional.


</template>

<script>
import BannerInterno from '../components/plantilla/BannerInterno'
import Muestras from '../components/muestras/Muestras.vue'

export default {
  name: 'Introduccion',
  components: {
    BannerInterno,
    Muestras,
  },
  data: () => ({
    globalData: global,
  }),
}
</script>

<style lang="sass"></style>
