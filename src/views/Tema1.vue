<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Tizado, trazo y corte
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-8
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t1/imag01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El tizado, trazo y corte consiste en toda la optimización o acomodación de moldes sobre el material textil, las técnicas y conocimientos para el área de prototipado y el corte de una prenda. El proceso de trazo y corte es donde se procede a estudiar y analizar el mejor aprovechamiento de los tejidos mediante técnicas de marcadas, de lo que depende, en gran parte, la calidad de la confección de la prenda; por tal motivo, constituye una parte importante en el costo total del producto. #[br]
              | Ver Video 1.

    .titulo-sexto.color-primario(data-aos="fade")
      h5 Video 1.
      span Introducción trazo y corte

    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-8.col-sm-6.col-md-2.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t1/img-cta.svg")
            .col-md.col-lg-6
              h4 Video – Introducción al trazo 
              p.mb-4 Conozca la introducción al trazo, corte, maquinarias implementadas, herramientas, hilos de tela, anchos y orillos de los textiles.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?app=desktop&v=lPY6Ffc509c&feature=youtu.be')" target="_blank")
                span Ver video
                i.fas.fa-video

    figcaption(data-aos="fade") Nota. Tomado de SENA (2020).
    

    Separador
    #t_1_1.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.1 Las herramientas, insumos y espacio en el trazo y corte


    .row.align-items-center.mb-4
      .col-lg-8(data-aos="fade-right")
        p En el taller de una costurera o un sastre, es importante contar con las herramientas, equipo, materiales e insumos necesarios para su buen funcionamiento, así como darles una adecuada distribución y orden para optimizar su funcionamiento. #[b Las herramientas y máquinas utilizadas para llevar a cabo estos procesos requieren de instrumentos para corte, medición y trazo, entre los que se encuentran las tijeras, el desbaratador, la rueda de trazado para sastrería, el cepillo electrostático, el punzón, el cúter textil, la máquina perforadora y la máquina cortadora.] Entre las herramientas de medición y trazo, se encuentran reglas, regla T de sastrería, escuadras y cinta métrica. Para el equipo, en cuanto utensilios, instrumentos y aparatos especiales, se encuentran los alfileres, el alfiletero, la carretilla, pesas de corte y mesa de trazo y corte. Además, los materiales necesarios también incluyen papel calca, greda, papel bond, papel micro, papel kraft, tiza o lápiz para marcar, greda o jaboncillo, entre otros. A continuación, se relaciona lo que se puede encontrar en el espacio del taller:
      .col-lg-4.col-md-7.col-10.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/t1/imag02.png', alt='')
    

    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 1.
          span Almacenamiento en corte
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Mobiliario
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              th.text-center Anaqueles
              td Son muebles que se tienen en el almacén para acomodar y seleccionar los materiales a utilizar.
            tr
              th.text-center Almacén de telas
              td Es el lugar donde se tiene gran variedad de telas y se seleccionan por sus características. 
            tr.bg-white
              th.text-center Canastos o cestos
              td Son los botes de basura que se utilizan para tirar los desperdicios o sobrantes de tela.

    .row.align-items-center.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 2.
          span Herramientas para cortar
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Herramientas corte
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              td #[b Tijeras de castellanas:] tienen los dos orificios para los dedos del mismo tamaño, suelen tener un tamaño medio y son bastante ligeras; se recomiendan para textiles de peso liviano.
              td #[b Tijeras sastre:] por uno de los lados, la hoja no sobresale en su mango, permitiendo de esta manera apoyar la tijera en la mesa a la hora de cortar la tela. Se caracterizan por tener un tamaño y peso mayor, por lo que se recomienda ser utilizadas para textiles de peso mediano a alto.
            tr
              td #[b Tijeras de zigzag:] poseen dientes en las hojas, lo que crea un patrón de corte en zigzag. La función principal de este tipo de tijeras es la de evitar que se deshilache el textil después del corte.
              td #[b Cortadores térmicos:] estos cortadores se emplean para el corte de acrílico y textiles. Una vez cortado, el corte queda sellado lo que evita que se deshilache.
            tr.bg-white
              td(colspan="2") #[b Cúter rotatorio:] se caracteriza por ser el mejor cortador para telas, lonas, láminas plásticas, hule, vinilos y otros materiales textiles, tejidos o no tejidos (fieltro). Su mango facilita el manejo, perfección y agilidad a la hora de cortar, por lo que se puede apoyar con reglas y elementos para la precisión del corte.      
    

    Separador
    #t_1_2.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.2 Proceso del extendido
    
    p.mb-4(data-aos="fade") Para ejecutar un buen proceso de extendido es necesario reconocer las características del material textil para realizar una identificación previa y así comprender el comportamiento que puede tener durante el proceso de extendido, como encogimiento, deslizamiento, despiste en el hilado, etc. Según el análisis obtenido mediante la observación del textil, se puede determinar la ubicación de los moldes, las herramientas óptimas a utilizar, si requiere o no un reposo previo y la dirección. #[b Los puntos que debes tener identificados son: 1. La urdimbre y la trama, 2. Hilo de tela y 3. Anchos de las telas] (Ver Tabla 3).
    
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 3.
          span Anchos de telas
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 División de anchos de fábrica
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              th.text-center Ancho simple
              td Están elaborados a partir de 70 cm a 90 cm de ancho. En este grupo se encuentran: cambre, paños, fieltro, blonda, satén, lino, etc.
            tr
              th.text-center Ancho angosto
              td Están elaborados a partir de 0,5 mm hasta 25 cm de ancho. En este grupo se encuentran: encajes, franjas, cintas, elásticos, etc. 
            tr.bg-white
              th.text-center Doble ancho
              td Están elaborados a partir de 140 cm hasta 150 cm de ancho. En este grupo se encuentran: paños, tafetán, popelina, crepé, entretelas, denim, etc.
            tr
              th.text-center Ancho especial
              td Están elaborados a partir de 2,8 cm. En este grupo se encuentran: tapicería y decoración, etc.
    
    p.mb-4(data-aos="fade") Una parte muy importante de este proceso del extendido son los orillos de tela, los cuales son bordes longitudinales de la tela, que están tejidos con una apariencia diferente y densa. Surgen como consecuencia de tratamientos de humectación y secado que sufren las telas una vez han sido tejidas para su estabilización. Se perfora el tejido desde el revés hacia el derecho, por lo que, por regla general, las rebabas de las perforaciones en los orillos indican el derecho de la tela. Ver Tabla 4
    
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 4.
          span Clasificación de orillos
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Tipos de orillos
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              th.text-center Orillos metidos
              td Una aguja especial, en forma de gancho, impulsada por una leva. Después de que esta se corta, la inserción del extremo del hilo retorna, formando así un borde fuerte. Este sistema es usado generalmente para las telas de peso ligero a medio.
            tr
              th.text-center Orillos Leno
              td Estos orillos se obtienen uniendo la trama con fuertes hilos adicionales, trabajando en tejido de gasa y eliminando mediante corte los extremos que sobresalen. Este sistema es usado generalmente para las telas pesadas. 
            tr.bg-white
              th.text-center Orillos de puntada cadeneta
              td Este tipo de orillos se producen mayoritariamente en un mecanismo de tejido de punto, el cual se realiza principalmente en una máquina de tejer, por medio de agujas.
            tr
              th.text-center Orillos fundidos
              td Se obtienen presionando unos elementos mecánicos calientes en el borde de la tela. Este método se puede aplicar en textiles de fibras sintéticas.
            tr.bg-white
              th.text-center Orillos lisos
              td Este tipo de orillos, también llamados orillos de estampación, son usados para controlar los colores básicos de los que consta el dibujo, enumerándolos en el orden de estampación, además de añadir la marca del fabricante. 
            tr
              th.text-center Orillos de cinta
              td Este tipo de orillos son utilizados por los fabricantes de textiles clásicos, como los paños. También tejen sus nombres en el orillo para que sean identificados fácilmente en las sastrerías a medida. 
    
    p(data-aos="fade") Para el proceso de tendido, se inicia con el reconocimiento de las partes que componen una prenda de vestir. Es sumamente importante para el proceso de trazo y corte, ya que de esto depende una adecuada interpretación de los requerimientos. Es por ello que el dibujo técnico es el insumo que permite identificar de forma detallada todas las características, como pespuntes, botones, costuras, pinzas y acabados. A esto se le conoce como extendido de la tela. 
    p.mb-4(data-aos="fade") Para identificar cada pieza, se deben analizar los componentes, que son los elementos y partes de las que están formadas las prendas de vestir, que pueden ser:
    
    .row.align-items-center.justify-content-center.mb-5
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 5.
          span Análisis en una prenda
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Tipos de componentes en prenda de vestir
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              td #[b Componentes exteriores:] son todas las partes del material textil base o textil con que está elaborada la prenda en el exterior. 
              td.no-border-right
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Delanteros y posteriores.
                  li
                    i.fas.fa-circle
                    | Cuellos.
                  li.mb-0
                    i.fas.fa-circle
                    | Mangas.
              td.no-border-left 
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Bolsillos.
                  li
                    i.fas.fa-circle
                    | Puños.
                  li.mb-0
                    i.fas.fa-circle
                    | Otros.
            tr
              td #[b Componentes interiores:] son todos aquellos elementos y partes que van en el interior o revés de la prenda.
              td.no-border-right
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Forro.
                  li.mb-0
                    i.fas.fa-circle
                    | Entretela.
              td.no-border-left
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Guata.
                  li.mb-0
                    i.fas.fa-circle
                    | Sesgo.
            tr.bg-white
              td #[b Hilos:] es uno de los elementos principales, son los que logran unir las diferentes partes de la prenda.
              td.no-border-right
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Pespuntes.
                  li.mb-0
                    i.fas.fa-circle
                    | Puntadas decorativas.
              td.no-border-left
                ul.lista-ul--color.color-secundario.mb-0
                  li
                    i.fas.fa-circle
                    | Bastas. 
                  li.mb-0
                    i.fas.fa-circle
                    | Puntadas manuales.
            tr
              td #[b Fornituras y complementos:] las fornituras son el conjunto de accesorios y adornos que puede llevar una prenda de vestir.
              td(colspan="2") Botones, cremalleras, corchetes, broches de presión, hebillas, ojetes, vivos, puntillas, cintas, apliques, gomas, cordones, etc.

    .row.fondo-t1.align-items-center.py-4.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center

          .col-lg-6(data-aos="fade-right")
            p.mb-5 Ahora que se ha trabajado sobre el análisis de la prenda, es importante conocer qué es el extendido. Este se entiende como un tipo de tendido, el cual consiste en ubicar la tela sobre una superficie plana (mesa de corte), ya sea una capa de tela o varias, según la orden de producción. Se extiende la tela, considerando las características del textil, y se preparan y seleccionan los materiales e instrumentos necesarios para la ejecución de la tarea. De acuerdo con lo anterior, la extendida se puede realizar de dos formas: con carro extendedor (manual y automático) o manualmente.
            .row.align-items-center.mb-4
              .col-2.col-md-1
                img(src='@/assets/curso/temas/t1/subt1.svg', alt='')
              .col-10.col-md-11
                h4.mb-0 Extendido manual:
            p Se sitúa la pieza de textil en un extremo de la mesa y se efectúa el estirado, mediante dos operarios/as o utilizando un carro de extendido, hasta el largo previamente establecido. Ver Figura 1.
          .col-lg-6.col-md-10.mb-4(data-aos="fade-left")
            .titulo-sexto.color-primario.mb-2
              h5 Figura 1.
              span Tizado en material textil
            img(src='@/assets/curso/temas/t1/imag03.png', alt='')
            figcaption Nota. Tomada de SENA (2021). #[br]
              a(:href="('https://sumarcapacitacion.cl/programas-sociales/corte-y-confeccion-de-prendas-de-vestir-para-ninos-y-adultos/')" target="_blank") https://sumarcapacitacion.cl/programas-sociales/corte-y-confeccion-de-prendas-de-vestir-para-ninos-y-adultos/
    
    p.text-center.mb-4 Cuando se trabaja con un extendido manual (Ver Video 2), es importante tener en cuenta las siguientes recomendaciones:
    
    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono02.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Alineación:
                p.text-center el textil debe estar completamente alineado al orillo. De ser posible, se deben alinear los dos orillos.
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono03.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Tensión:
                p.text-center en lo posible evitar la tensión en la tela, ya que, después del corte, las piezas cortadas quedarán reducidas (pequeñas en relación con el tamaño real del molde).
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono04.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Arrugas:
                p.text-center evitar que la tela se encuentre arrugada en el tendido, para que no se formen burbujas de aire en este, ocasionando distorsiones en el corte. 
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono05.svg' alt='AvatarTop')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Consumo:
                p.text-center cortar solamente lo necesario para evitar más consumo de tela, controlando el desperdicio, de acuerdo con la acomodación de los moldes. 
    
    .titulo-sexto.color-primario
      h5 Video 2.
      span Proceso de extendido

    .row.fondo-cta2.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-8.col-sm-6.col-md-2.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t1/img-cta2.svg")
            .col-md.col-lg-6
              h4 Video – Proceso de extendido 
              p.mb-4 Conozca el proceso de extendido, teniendo en cuenta las diferentes maquinarias y herramientas implementadas, los diferentes tendidos abiertos y cerrados, pero además un barrido respecto al extendido industrial.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?app=desktop&v=Mnnt4AAnKJQ&feature=youtu.be')" target="_blank")
                span Ver video
                i.fas.fa-video

    figcaption(data-aos="fade") Nota. Tomado de SENA (2020).


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
