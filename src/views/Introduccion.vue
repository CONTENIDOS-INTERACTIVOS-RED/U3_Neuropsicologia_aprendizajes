<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    p.mb-4 El entendimiento del ser humano desde una perspectiva holística representa un desafío considerable, pues somos el resultado de diversas esferas: biológica, psicológica, química, neurológica, física y genética. En respuesta a esta complejidad surge la neuropsicología, una ciencia que busca integrar estas dimensiones para comprender quiénes somos y cómo se originan nuestras conductas.
    
    .row
      .col-12.col-md-6.col-xl-4(data-aos="fade-right").bg-verde.p-4.mb-3.rounded.d-flex.align-items-center
        p.my-auto En esta unidad, se espera que al finalizar el estudiante sea capaz de: comprender los principios fundamentales de la neuropsicología y sus aplicaciones en el aprendizaje, explicar su relevancia en el proceso de enseñanza-aprendizaje, y relacionar los conceptos de neuropsicología con ejemplos prácticos de aprendizaje.
      .col-4.d-none.d-md-block(data-aos="fade-up").mb-3.rounded
        img(src='@/assets/curso/unidad/img-1.png', alt='')
      .col-12.col-md-6.col-xl-4(data-aos="fade-left").bg-rosa.p-4.mb-3.rounded.d-flex.align-items-center
        p.my-auto La unidad se organiza en torno al tema principal Fundamentos de la Neuropsicología del Aprendizaje, dividido en tres subtemas principales: definición y principios de la neuropsicología, análisis del desarrollo cerebral y aprendizaje, y estructuras cerebrales involucradas en procesos de memoria, atención y aprendizaje.



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
