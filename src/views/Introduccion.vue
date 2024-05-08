<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.align-items-center
      .col-lg-4.col-md-7.col-10.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/intro.png', alt='')
      .col-lg-8.mb-4(data-aos="fade-left")
        p Apreciado(a) aprendiz, en el desarrollo de proyectos que tienen como finalidad la elaboración de prendas de vestir, es elemental incorporar métodos y procedimientos apropiados con altos modelos de calidad. La creación de las prendas de vestir se trabaja a partir de técnicas manuales, las cuales deben lograr la generación de impacto en el consumidor-cliente desde el valor y la calidad frente a las terminaciones de las piezas que, en su integralidad, conforman la prenda de vestir. Se recomienda ver la siguiente animación.
        .cajon.color-primario.bg1.p-4
          p.mb-0 Para la elaboración de este componente, se abordaron varios autores conocidos en la elaboración de prendas de vestir a la medida, de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido que el conocimiento es social y, por lo tanto, es para usarlo por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de la confección a la medida.
    
    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    
    .row.align-items-center.mb-4
      .col-lg-8(data-aos="fade-right")
        p Hablar de sastrería básica, trazo y corte permitirá que se aborden técnicas manuales que han sido utilizadas por sastres desde hace muchos años y que, a partir de la realización de levantamientos de patrones e ir construyendo artesanalmente las piezas textiles con acabados finos, posibilitan el incremento de la calidad en la prenda elaborada. Para esto, se deberá hacer un recorrido minucioso sobre la preparación de las piezas, a través del cual se conozcan los tipos de entretela y cómo serán sus usos; asimismo, procesos de levantamiento para la construcción de básicos superiores femeninos, desde la elaboración de los moldes hasta conocer el procedimiento, iniciando desde la elección de las telas, el análisis del modelo que se realiza y el proceso artesanal.
      .col-lg-4.col-md-7.col-10.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/intro1.png', alt='')

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
