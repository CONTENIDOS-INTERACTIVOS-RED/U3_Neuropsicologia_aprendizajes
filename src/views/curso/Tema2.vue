<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Desarrollo cerebral y aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-19.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-verde.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") La <strong>neuropsicología</strong> se centra en el cerebro como núcleo principal del procesamiento, almacenamiento y recepción de la información captada a través de los sentidos. Este análisis aborda los elementos y características que intervienen en el proceso de aprendizaje, destacando que el desarrollo cerebral depende de las experiencias vividas por cada persona. Como explica Siegel (2007), las experiencias activan vías cerebrales, fortalecen conexiones neuronales y generan nuevas, mientras que la falta de estímulos puede conducir a la pérdida de conexiones, fenómeno conocido como "muerte neuronal".

    h2 Importancia de las experiencias y etapas críticas del desarrollo

    .row.mb-4
      .col-2.d-none.d-lg-block(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-20.png', alt='Texto que describa la imagen')
      .col-12.col-lg-10(data-aos="fade-left")
        span El entendimiento del ser humano desde una perspectiva holística representa un desafío considerable, pues somos el resultado de diversas esferas: biológica, psicológica, química, neurológica, física y genética. En respuesta a esta complejidad surge la neuropsicología, una ciencia que busca integrar estas dimensiones para comprender quiénes somos y cómo se originan nuestras conductas.

    h2 Patrones de desarrollo cerebral
    p.mb-4 El desarrollo cerebral sigue cuatro patrones principales:

    .row.mb-5
      .col-12.col-xl-8(data-aos="fade-right")
        AcordionA(tipo="b")
          .div(titulo="De atrás hacia adelante")
            p Las áreas visuales se desarrollan primero, seguidas de las auditivas y finalmente las frontales, responsables del pensamiento abstracto y la planificación.
          .div(titulo="De adentro hacia afuera")
            p Las estructuras centrales del sistema límbico se desarrollan antes que la corteza cerebral, encargada de procesar información y planificación.
          .div(titulo="De abajo hacia arriba")
            p El bulbo raquídeo, encargado de funciones vitales como la respiración y el ritmo cardíaco, se desarrolla antes que las funciones emocionales y motoras.
      .col-12.col-lg-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-21.png', alt='Texto que describa la imagen')

    h2 Componentes principales del cerebro
    p Los componentes principales del cerebro y sus funciones:

    .row.position-relative.mb-4.py-4.bg-verde.bg-full-width
      .px-4.px-md-5.py-md-3
        p.mb-4 <strong>Figura 1</strong> Componentes principales del cerebro

        .row
          .col-8.col-xl-4.col-xxl-5(data-aos="fade-right")
            img(src='@/assets/curso/unidad/img-22.png', alt='Texto que describa la imagen')
          .col-12.col-xl-8.col-xxl-7(data-aos="fade-left")
            ol.lista-ol--cuadro.d-flex.flex-column.justify-content-center
              li.d-flex 
                .lista-ol--cuadro__vineta.bg-rosa-oscuro
                  span 1
                p.mb-0 <strong>Bulbo raquídeo.</strong> Regula funciones vitales como la respiración y el ritmo cardíaco.
              li.d-flex
                .lista-ol--cuadro__vineta.bg-rosa-oscuro
                  span 2 
                p.mb-0 <strong>Sistema límbico.</strong> Procesa información emocional, clasifica experiencias y motiva las acciones. 
              li.d-flex
                .lista-ol--cuadro__vineta.bg-rosa-oscuro
                  span 3
                p.mb-0 <strong>Córtex cerebral.</strong> Responsable de funciones como atención, memoria, toma de decisiones y aprendizaje.

    h2 Desarrollo cerebral por etapas
    p.mb-4 El desarrollo cerebral se produce a lo largo de diferentes etapas, cada una caracterizada por procesos clave que moldean sus funciones y capacidades

    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        AcordionA(tipo="b")
          .div(titulo="Prenatal")
            p Neurogénesis, migración celular y sinaptogénesis. Las neuronas se forman y posicionan, creando conexiones hacia el final del embarazo.
          .div(titulo="Infancia")
            p Alta plasticidad cerebral, desarrollo sensorial y motor significativo.
          .div(titulo="Adolescencia")
            p Poda sináptica para optimizar conexiones, mielinización y predominio de la amígdala sobre la corteza prefrontal, generando impulsividad y cambios emocionales.
          .div(titulo="Adultez")
            p Consolidación y especialización cerebral, mielinización de la corteza prefrontal, aunque con menor neuroplasticidad.
          .div(titulo="Envejecimiento")
            p Disminución cognitiva que puede ser compensada por la reserva cognitiva, manteniendo funciones esenciales mediante estimulación constante.
      .col-12.col-xl-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-23.png', alt='Texto que describa la imagen')

    p.mb-5 El desarrollo cerebral es un proceso dinámico y continúo influido por experiencias y estímulos en todas las etapas de la vida. Comprender los patrones de desarrollo y las características específicas de cada etapa permite promover estrategias que potencien el crecimiento integral y el mantenimiento de funciones cognitivas, asegurando un desarrollo saludable a lo largo del ciclo vital.

    #t_2_1.titulo-segundo
      div.d-flex
        span.me-3 2.1  
        h2 Aprendizaje

    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-24.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-amarillo.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") El aprendizaje es un proceso mediante el cual un individuo adquiere conocimientos, habilidades, actitudes o comportamientos a través de la experiencia, la educación o la práctica. Su estudio, que abarca diversas disciplinas, ha evolucionado significativamente a lo largo del tiempo bajo la influencia de diferentes corrientes filosóficas, psicológicas y pedagógicas. A continuación, se realiza un recorrido histórico por las principales teorías y enfoques que han moldeado nuestra comprensión del aprendizaje:

    h2 Condicionamiento clásico
    p.mb-4 Esta teoría, liderada por el fisiólogo Ivan Pávlov, plantea que toda conducta no proviene del pensamiento, sino de la estimulación sensorial externa, que genera dicho pensamiento. Describe un aprendizaje en el que un organismo establece una asociación entre un estímulo neutro y un estímulo incondicionado que provoca una respuesta natural.
    p.mb-4.text-strong Los componentes principales del condicionamiento clásico son:

    .row.mb-4
      .col-12.col-xl-8(data-aos="fade-right")
        AcordionA(tipo="b")
          .div(titulo="Estímulo incondicionado (EI)")
            p Provoca una respuesta automática sin necesidad de aprendizaje (e.g., la comida que genera salivación en un perro).
          .div(titulo="Respuesta incondicionada (RI)")
            p Reacción automática y no aprendida provocada por el estímulo incondicionado (e.g., la salivación al ver la comida).
          .div(titulo="Estímulo neutro (EN)")
            p No genera inicialmente la respuesta incondicionada (e.g., el sonido de una campana).
          .div(titulo="Estímulo condicionado (EC)")
            p El estímulo neutro, tras asociarse repetidamente con el estímulo incondicionado, provoca una respuesta aprendida (e.g., la campana que induce salivación).
          .div(titulo="Respuesta condicionada (RC)")
            p La respuesta aprendida ante el estímulo condicionado (e.g., la salivación al oír la campana).
      .col-12.col-xl-4.d-none.d-xl-block(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-25.png', alt='Texto que describa la imagen')

    .row.position-relative.mb-0.py-4.bg-fondo-1.bg-full-width
      .px-4.px-md-5.py-md-3
        
        h2 Teoría del ensayo y error
        p.mb-4 Propuesta por Edward L. Thorndike, esta teoría plantea que, cuando dos eventos ocurren repetidamente en proximidad temporal, se forma una asociación entre ellos: estímulo (E), respuesta (R) y conexión (*). Thorndike formuló tres leyes fundamentales:

        .row.mb-4.justify-content-center 
          .col-10.col-md-8.col-lg-6.col-xl-4.mb-4.mb-xl-0
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100(data-aos="fade-right")
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-26.svg', style="width: 80px")
              p.text-bold.mb-4.text-center  Ley del efecto
              p.px-1.text-small.mb-0.d-flex.text-center Las respuestas seguidas de consecuencias satisfactorias tienden a repetirse, mientras que las insatisfactorias tienden a descartarse.
          .col-10.col-md-8.col-lg-6.col-xl-4.mb-4.mb-xl-0(data-aos="fade-up")
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-27.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Ley del ejercicio
              p.px-1.text-small.mb-0.d-flex.text-center Cuanto más se repite una respuesta en una situación particular, más fuerte se vuelve la conexión entre estímulo y respuesta.
          .col-10.col-md-8.col-lg-6.col-xl-4(data-aos="fade-left")
            .custom-image-card.d-flex.flex-column.p-4.py-md-5.h-100
              img.mx-auto.mb-4(src='@/assets/curso/unidad/img-28.svg', style="width: 80px")
              p.text-bold.mb-4.text-center Ley de preparación
              p.px-1.text-small.mb-0.d-flex.text-center La respuesta se facilita si las conexiones nerviosas están listas para responder.

    p.mb-4 El aprendizaje ha sido abordado desde diversas perspectivas teóricas, cada una enfocándose en aspectos específicos del proceso. Estas teorías han aportado valiosos conceptos que permiten entender cómo las personas adquieren conocimientos, habilidades y actitudes. A continuación, se describen cuatro enfoques principales:

    TabsC.mb-4
      .tabs-content.bg-verde-claro.border.px-4.p-md-5.py-3(titulo="Conductismo", :iconUrl="require('@/assets/curso/unidad/img-29.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-30.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Conductismo
            p(data-aos="fade-up") Se centra en el comportamiento observable y como  puede ser modelado y reforzado para promover el aprendizaje (B.F. Skinner).
      .tabs-content.bg-verde-claro.border.px-4.p-md-5.py-3(titulo="Constructivismo", :iconUrl="require('@/assets/curso/unidad/img-29.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-31.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Constructivismo
            p(data-aos="fade-up") Plantea que el conocimiento se construye mediante experiencias y reflexiones, relacionando nueva información con conocimientos previos (Jean Piaget y Lev Vygotsky).
      .tabs-content.bg-verde-claro.border.px-4.p-md-5.py-3(titulo="Aprendizaje significativo", :iconUrl="require('@/assets/curso/unidad/img-29.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-32.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Aprendizaje significativo
            p(data-aos="fade-up") Propone que el aprendizaje depende de conectar la nueva información con la estructura cognitiva previa del estudiante para otorgarle un significado relevante (David Ausubel).
      .tabs-content.bg-verde-claro.border.px-4.p-md-5.py-3(titulo="Aprendizaje social", :iconUrl="require('@/assets/curso/unidad/img-29.svg')")
        .row
          .d-none.d-lg-block.col-md-12.col-lg-5.col-xl-4(data-aos="fade-right")
            figure
              img(src='@/assets/curso/unidad/img-33.png', alt='Texto que describa la imagen')
          .col-md-12.col-lg-7.col-xl-8.mb-4.mb-md-0(data-aos="fade-left")
            h4 Aprendizaje social
            p(data-aos="fade-up") Destaca que las personas aprenden no solo por experiencia directa, sino también observando e imitando modelos (Albert Bandura).

    p.mb-4 Es importante destacar que ninguna teoría prevalece sobre las demás, ya que cada una aporta elementos valiosos que enriquecen el entendimiento del aprendizaje. Este proceso complejo puede originarse de múltiples factores y manifestarse de diversas formas, como el aprendizaje por imitación, observable en bebés desde los dos o tres meses.
    img.mb-4(src='@/assets/curso/unidad/img-34.png', alt='Texto que describa la imagen').mb-4

    .row.mb-5
      .d-flex.align-items-center
        div.d-flex.align-items-center.bg-rosa.px-3.py-4(data-aos="fade-up")
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-35.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 El estudio del aprendizaje es amplio y multidimensional, lo que sugiere que no hay un único enfoque que funcione para todos. Cada teoría y forma de aprendizaje ofrece insights valiosos que pueden ser aplicados en la educación formal y en el desarrollo personal. Lo que sí se puede concluir es que el proceso de aprender para el ser humano no finaliza, sin embargo sus primeros años de vida, su entorno cultural y social, así como la interacción con adultos o educadores, tiene una incidencia alta en el proceso.

    .bg-full-width.border-top-9-azul
      .px-4.px-md-5.pt-5.pb-0
        h2 Material complementario
        .row
          .col-12.col-md-6.col-lg-8
            p.text-small
            p.d-flex.my-4
              img.me-3.mb-auto.mt-1(src='@/assets/componentes/youtube-icon.svg' :style="{'max-width':'16px'}")
              a.text-small.text-primary(target="_blank", href="https://www.youtube.com/watch?v=ElgUy_7eYLQ") Universidad de Deusto / Deustuko Unibertsitatea. 2015 Introducción al Business Intelligence.
            p.d-flex.my-4
              img.me-3.mb-auto.mt-1(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a.text-small.text-primary(target="_blank", href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/101030") Curto Díaz, J. (2016). Introducción al business intelligence: ( ed.). Editorial UOC. 
          .col-12.col-md-6.col-lg-3
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='Texto que describa la imagen')


</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema2',
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

<style lang="sass"></style>
