<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Proceso de levantamiento y construcción de básicos masculino
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-9
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t4/imag01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Cuando se habla de prendas sastre o más específicamente chaqueta sastre masculina, se debe tener en cuenta que el enfoque principal va hacia el ajuste y la horma. En masculino, el volumen o el ajuste de pinzas se trabaja hacia la parte posterior, teniendo en cuenta que el ancho de espalda es uno de los puntos más protuberantes en la parte superior de la silueta masculina.
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.mb-4(data-aos="fade-right")
        .cajon.color-primario.bg5.p-4.mb-4
          p.mb-0 En el manual de patronaje básico SENA, se identifica como punto de partida, en la página 71, el trazo base para chaqueta sastre masculina, el cual consiste en un básico con ciertas modificaciones o traslados de los puntos base del cuerpo, para obtener una mejor forma y ajuste sobre la estructura o silueta característica de las prendas sastre.
        p Para el trazo de una chaqueta sastre, en las páginas 73 y 76 de este mismo manual, se identifica una serie de sugerencias o especificaciones frente a las modificaciones en plano que se pueden trabajar para el desarrollo de este mismo tipo de chaqueta, para lo cual se debe tener en cuenta que en masculino no solamente se trabaja por silueta sino por ocasión de uso, es decir, que cada prenda o cada diseño tiene unas especificaciones diferentes. A nivel general, se puede categorizar la finalidad de la prenda por la cantidad de botones, el ancho de la solapa, la forma en la división del cuello y solapa, el ancho de una tapa de bolsillo, la forma de una boca de bolsillo, los ribetes, el canto o la forma del largo, el forro, los acabados en las partes internas de la prenda; incluso hasta la cantidad de aberturas o cajas corresponden o suplen necesidades diferentes. Por esto se recomienda desde patronaje siempre trabajar la parte funcional de la prenda, dejando de lado la segmentación o el nombre comercial.  
      .col-lg-4.col-md-10.mb-4.d-none.d-lg-flex(data-aos="fade-left")
        img(src='@/assets/curso/temas/t4/imag02.png', alt='')
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-7.col-11.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t4/imag03.png', alt='')
      .col-lg-8.mb-4(data-aos="fade-left")
        p En el desarrollo de productos para la línea masculina, se identifican diferentes tipos de variaciones, dependiendo del costo de producción o línea de venta. En esta ocasión se va a hacer el desarrollo de una chaqueta bomber. Si bien la chaqueta bomber es una prenda informal o que puede ser categorizada dentro de un rango de prendas casuales, en esta ocasión se va a hacer el desarrollo partiendo desde la base sastre masculina. A la hora de patronar o desarrollar un producto, se debe tener en cuenta siempre el requerimiento de la empresa o cliente. Si lo que se busca es un estándar de calidad mayor o un costo de producción más elevado, lo ideal es asegurar la horma y el ajuste desde patronaje. Por eso, en esta ocasión se trabajará el desarrollo de la chaqueta partiendo desde una base sastre y no desde una base normal. 
      
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Video 14.
      span Base sastre masculina
    
    p(data-aos="fade") Conozca sobre las bases del sastre masculino.
    
    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/0QCgguWkbA8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: BASE SASTRE MASCULINA
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Video 15.
      span Trazo de chaqueta sastre masculina
    
    p(data-aos="fade") Conozca sobre el trazo para las chaquetas tipo sastre masculina.

    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/oH9SmGbFdDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: 11 2 TRAZO DE CHAQUETA SASTRE MASCULINA
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Video 16.
      span Interpretación de chaqueta bomber
    
    p(data-aos="fade") Conozca sobre las chaquetas bomber.

    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/oITM6TFD734" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: 11 3 INTERPRETACIÓN DE CHAQUETA BOMBER
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Video 17.
      span Generalidades de pantalón sastre masculino interpretación
    
    p(data-aos="fade") Conozca sobre las generalidades de pantalón sastre masculino.

    figure(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/FJZ4-R6Jn7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: 11 7 GENERALIDADES DE PANTALÓN SASTRE MASCULINO INTERPRETACIÓN


</template>

<script>
export default {
  name: 'Tema4',
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
