<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Tizado, trazo y corte
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t1/imag01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El tizado, trazo y corte consiste en toda la optimización o acomodación de moldes sobre el material textil, las técnicas y conocimientos para el área de prototipado y el corte de una prenda. El proceso de trazo y corte es donde se procede a estudiar y analizar el mejor aprovechamiento de los tejidos mediante técnicas de marcadas, de lo que depende, en gran parte, la calidad de la confección de la prenda; por tal motivo, constituye una parte importante en el costo total del producto. Ver Video 1.

    .titulo-sexto.color-primario
          h5 Video 1.
          span Introducción trazo y corte
    

    Separador
    #t_1_1.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.1 Las herramientas, insumos y espacio en el trazo y corte


    .row.align-items-center.mb-4
      .col-lg-8(data-aos="fade-left")
        p En el taller de una costurera o un sastre, es importante contar con las herramientas, equipo, materiales e insumos necesarios para su buen funcionamiento, así como darles una adecuada distribución y orden para optimizar su funcionamiento. #[b Las herramientas y máquinas utilizadas para llevar a cabo estos procesos requieren de instrumentos para corte, medición y trazo, entre los que se encuentran las tijeras, el desbaratador, la rueda de trazado para sastrería, el cepillo electrostático, el punzón, el cúter textil, la máquina perforadora y la máquina cortadora.] Entre las herramientas de medición y trazo, se encuentran reglas, regla T de sastrería, escuadras y cinta métrica. Para el equipo, en cuanto utensilios, instrumentos y aparatos especiales, se encuentran los alfileres, el alfiletero, la carretilla, pesas de corte y mesa de trazo y corte. Además, los materiales necesarios también incluyen papel calca, greda, papel bond, papel micro, papel kraft, tiza o lápiz para marcar, greda o jaboncillo, entre otros. A continuación, se relaciona lo que se puede encontrar en el espacio del taller:
      .col-lg-4.col-md-7.col-10.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t1/imag02.png', alt='')
    
    .row.align-items-center.mb-4
      .titulo-sexto.color-primario
            h5 Tabla 1.
            span Almacenamiento en corte
      .tabla-b.color-acento-contenido.mb-5
        .tabla-b__header
          h5.mb-0 Mobiliario
        table
          caption Nota. Tomada de SENA (2021).
          tr
            th Anaqueles
            td Son muebles que se tienen en el almacén para acomodar y seleccionar los materiales a utilizar.
          tr
            th Almacén de telas
            td Es el lugar donde se tiene gran variedad de telas y se seleccionan por sus características. 
          tr
            th Canastos o cestos
            td Son los botes de basura que se utilizan para tirar los desperdicios o sobrantes de tela.

    .row.align-items-center.mb-4
      .titulo-sexto.color-primario
            h5 Tabla 2.
            span Herramientas para cortar
      .tabla-b.color-acento-contenido.mb-5
        .tabla-b__header
          h5.mb-0 Herramientas corte
        table
          caption Nota. Tomada de SENA (2021).
          tr
            td Tijeras de castellanas: tienen los dos orificios para los dedos del mismo tamaño, suelen tener un tamaño medio y son bastante ligeras; se recomiendan para textiles de peso liviano.
            td Tijeras sastre: por uno de los lados, la hoja no sobresale en su mango, permitiendo de esta manera apoyar la tijera en la mesa a la hora de cortar la tela. Se caracterizan por tener un tamaño y peso mayor, por lo que se recomienda ser utilizadas para textiles de peso mediano a alto.
          tr
            td Tijeras de zigzag: poseen dientes en las hojas, lo que crea un patrón de corte en zigzag. La función principal de este tipo de tijeras es la de evitar que se deshilache el textil después del corte.
            td Cortadores térmicos: estos cortadores se emplean para el corte de acrílico y textiles. Una vez cortado, el corte queda sellado lo que evita que se deshilache.
          tr
            td Cúter rotatorio: se caracteriza por ser el mejor cortador para telas, lonas, láminas plásticas, hule, vinilos y otros materiales textiles, tejidos o no tejidos (fieltro). Su mango facilita el manejo, perfección y agilidad a la hora de cortar, por lo que se puede apoyar con reglas y elementos para la precisión del corte.      
    
    Separador
    #t_1_2.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.2 Proceso del extendido
    
    p.mb-4 Para ejecutar un buen proceso de extendido es necesario reconocer las características del material textil para realizar una identificación previa y así comprender el comportamiento que puede tener durante el proceso de extendido, como encogimiento, deslizamiento, despiste en el hilado, etc. Según el análisis obtenido mediante la observación del textil, se puede determinar la ubicación de los moldes, las herramientas óptimas a utilizar, si requiere o no un reposo previo y la dirección. #[b Los puntos que debes tener identificados son: 1. La urdimbre y la trama, 2. Hilo de tela y 3. Anchos de las telas] (Ver Tabla 3).
    
    .row.align-items-center.mb-4
      .titulo-sexto.color-primario
            h5 Tabla 3.
            span Anchos de telas
      .tabla-b.color-acento-contenido.mb-5
        .tabla-b__header
          h5.mb-0 División de anchos de fábrica
        table
          caption Nota. Tomada de SENA (2021).
          tr
            th Ancho simple
            td Están elaborados a partir de 70 cm a 90 cm de ancho. En este grupo se encuentran: cambre, paños, fieltro, blonda, satén, lino, etc.
          tr
            th Ancho angosto
            td Están elaborados a partir de 0,5 mm hasta 25 cm de ancho. En este grupo se encuentran: encajes, franjas, cintas, elásticos, etc. 
          tr
            th Doble ancho
            td Están elaborados a partir de 140 cm hasta 150 cm de ancho. En este grupo se encuentran: paños, tafetán, popelina, crepé, entretelas, denim, etc.
          tr
            th Ancho especial
            td Están elaborados a partir de 2,8 cm. En este grupo se encuentran: tapicería y decoración, etc.
    
    p.mb-4 Una parte muy importante de este proceso del extendido son los orillos de tela, los cuales son bordes longitudinales de la tela, que están tejidos con una apariencia diferente y densa. Surgen como consecuencia de tratamientos de humectación y secado que sufren las telas una vez han sido tejidas para su estabilización. Se perfora el tejido desde el revés hacia el derecho, por lo que, por regla general, las rebabas de las perforaciones en los orillos indican el derecho de la tela. Ver Tabla 4
    
    .row.align-items-center.mb-4
      .titulo-sexto.color-primario
            h5 Tabla 4.
            span Clasificación de orillos
      .tabla-b.color-acento-contenido.mb-5
        .tabla-b__header
          h5.mb-0 Tipos de orillos
        table
          caption Nota. Tomada de SENA (2021).
          tr
            th Orillos metidos
            td Una aguja especial, en forma de gancho, impulsada por una leva. Después de que esta se corta, la inserción del extremo del hilo retorna, formando así un borde fuerte. Este sistema es usado generalmente para las telas de peso ligero a medio.
          tr
            th Orillos Leno
            td Estos orillos se obtienen uniendo la trama con fuertes hilos adicionales, trabajando en tejido de gasa y eliminando mediante corte los extremos que sobresalen. Este sistema es usado generalmente para las telas pesadas. 
          tr
            th Orillos de puntada cadeneta
            td Este tipo de orillos se producen mayoritariamente en un mecanismo de tejido de punto, el cual se realiza principalmente en una máquina de tejer, por medio de agujas.
          tr
            th Orillos fundidos
            td Se obtienen presionando unos elementos mecánicos calientes en el borde de la tela. Este método se puede aplicar en textiles de fibras sintéticas.
          tr
            th Orillos lisos
            td Este tipo de orillos, también llamados orillos de estampación, son usados para controlar los colores básicos de los que consta el dibujo, enumerándolos en el orden de estampación, además de añadir la marca del fabricante. 
          tr
            th Orillos de cinta
            td Este tipo de orillos son utilizados por los fabricantes de textiles clásicos, como los paños. También tejen sus nombres en el orillo para que sean identificados fácilmente en las sastrerías a medida. 
    
    p.mb-4 Para el proceso de tendido, se inicia con el reconocimiento de las partes que componen una prenda de vestir. Es sumamente importante para el proceso de trazo y corte, ya que de esto depende una adecuada interpretación de los requerimientos. Es por ello que el dibujo técnico es el insumo que permite identificar de forma detallada todas las características, como pespuntes, botones, costuras, pinzas y acabados. A esto se le conoce como extendido de la tela. 
    p.mb-4 Para identificar cada pieza, se deben analizar los componentes, que son los elementos y partes de las que están formadas las prendas de vestir, que pueden ser:
    
    .row.align-items-center.mb-4
      .titulo-sexto.color-primario
            h5 Tabla 5.
            span Análisis en una prenda
    

    .row.align-items-center.mb-4
      .col-lg-6(data-aos="fade-left")
        p.mb-4 Ahora que se ha trabajado sobre el análisis de la prenda, es importante conocer qué es el extendido. Este se entiende como un tipo de tendido, el cual consiste en ubicar la tela sobre una superficie plana (mesa de corte), ya sea una capa de tela o varias, según la orden de producción. Se extiende la tela, considerando las características del textil, y se preparan y seleccionan los materiales e instrumentos necesarios para la ejecución de la tarea. De acuerdo con lo anterior, la extendida se puede realizar de dos formas: con carro extendedor (manual y automático) o manualmente.
        h4 Extendido manual:
        p Se sitúa la pieza de textil en un extremo de la mesa y se efectúa el estirado, mediante dos operarios/as o utilizando un carro de extendido, hasta el largo previamente establecido. Ver Figura 1.
      .col-lg-6.col-md-7.col-10.mb-4(data-aos="fade-right")
        .titulo-sexto.color-primario
            h5 Figura 1.
            span Tizado en material textil
        img(src='@/assets/curso/temas/t1/imag03.png', alt='')
        caption Nota. Tomada de SENA (2021).
    
    p.text-center.mb-4 Cuando se trabaja con un extendido manual (Ver Video 2), es importante tener en cuenta las siguientes recomendaciones:
    
    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono02.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h2.text-center Alineación:
                p el textil debe estar completamente alineado al orillo. De ser posible, se deben alinear los dos orillos.
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono03.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h2.text-center Tensión:
                p en lo posible evitar la tensión en la tela, ya que, después del corte, las piezas cortadas quedarán reducidas (pequeñas en relación con el tamaño real del molde).
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono04.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h2.text-center Arrugas:
                p evitar que la tela se encuentre arrugada en el tendido, para que no se formen burbujas de aire en este, ocasionando distorsiones en el corte. 
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono05.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h2.text-center Consumo:
                p cortar solamente lo necesario para evitar más consumo de tela, controlando el desperdicio, de acuerdo con la acomodación de los moldes. 
    
    .titulo-sexto.color-primario
          h5 Video 2.
          span Proceso de extendido

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
