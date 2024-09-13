<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Tizado, trazo y corte
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-9.col-md-10
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t1/imag01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El tizado, trazo y corte consiste en toda la optimización o acomodación de moldes sobre el material textil, las técnicas y conocimientos para el área de prototipado y el corte de una prenda. El proceso de trazo y corte es donde se procede a estudiar y analizar el mejor aprovechamiento de los tejidos mediante técnicas de marcadas, de lo que depende, en gran parte, la calidad de la confección de la prenda; por tal motivo, constituye una parte importante en el costo total del producto. #[br]
            

    .titulo-sexto.color-primario(data-aos="fade")
      h5 Video 1.
      span Introducción trazo y corte

    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-7.col-md-3.col-lg-2.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t1/img-cta.svg")
            .col-md.col-lg-6
              h4 Video – Introducción al trazo 
              p.mb-4 Conozca la introducción al trazo, corte, maquinarias implementadas, herramientas, hilos de tela, anchos y orillos de los textiles.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?app=desktop&v=lPY6Ffc509c&feature=youtu.be')" target="_blank")
                span  Video
                i.fas.fa-video

    figcaption(data-aos="fade") Nota. Tomado de SENA (2020).
    

    Separador
    #t_1_1.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.1 Las herramientas, insumos y espacio en el trazo y corte

    .row.align-items-center.justify-content-center.mb-4
      .col-lg-8(data-aos="fade-right")
        p En el taller de una costurera o un sastre, es importante contar con las herramientas, equipo, materiales e insumos necesarios para su buen funcionamiento, así como darles una adecuada distribución y orden para optimizar su funcionamiento.  Las herramientas y máquinas utilizadas para llevar a cabo estos procesos requieren de instrumentos para corte, medición y trazo, entre los que se encuentran las tijeras, el desbaratador, la rueda de trazado para sastrería, el cepillo electrostático, el punzón, el cúter textil, la máquina perforadora y la máquina cortadora. Entre las herramientas de medición y trazo, se encuentran reglas, regla T de sastrería, escuadras y cinta métrica. Para el equipo, en cuanto utensilios, instrumentos y aparatos especiales, se encuentran los alfileres, el alfiletero, la carretilla, pesas de corte y mesa de trazo y corte. Además, los materiales necesarios también incluyen papel calca, greda, papel bond, papel micro, papel kraft, tiza o lápiz para marcar, greda o jaboncillo, entre otros. A continuación, se relaciona lo que se puede encontrar en el espacio del taller:
      .col-lg-4.col-md-7.col-10.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/t1/imag02.png', alt='')
    

    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 1.
          span Mobiliario en el taller
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Descripción
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
          
          table
            caption Nota. Tomada de SENA (2021).
            thead
              tr
                th.w-25-th.tabla-b__header.h4.mb-0.txt-start Herramienta
                th.tabla-b__header.h4.mb-0.txt-start Descripción
            tbody
              tr.bg-white
                td #[b Tijeras de castellanas] 
                td Tienen los dos orificios para los dedos del mismo tamaño, suelen tener un tamaño medio y son bastante ligeras; se recomiendan para textiles de peso liviano.
              tr.bg-white  
                td #[b Tijeras sastre] 
                td Por uno de los lados, la hoja no sobresale en su mango, permitiendo de esta manera apoyar la tijera en la mesa a la hora de cortar la tela. Se caracterizan por tener un tamaño y peso mayor, por lo que se recomienda ser utilizadas para textiles de peso mediano a alto.
              tr
                td #[b Tijeras de #[i zigzag]] 
                td Poseen dientes en las hojas, lo que crea un patrón de corte en #[i zigzag]. La función principal de este tipo de tijeras es la de evitar que se deshilache el textil después del corte.
              tr.bg-white  
                td #[b Cortadores térmicos] 
                td Estos cortadores se emplean para el corte de acrílico y textiles. Una vez cortado, el corte queda sellado lo que evita que se deshilache.
              tr.bg-white
                td #[b Cúter rotatorio] 
                td Se caracteriza por ser el mejor cortador para telas, lonas, láminas plásticas, hule, vinilos y otros materiales textiles, tejidos o no tejidos (fieltro). Su mango facilita el manejo, perfección y agilidad a la hora de cortar, por lo que se puede apoyar con reglas y elementos para la precisión del corte.      
    

    Separador
    #t_1_2.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.2 Proceso del extendido
    
    p.mb-4(data-aos="fade") Para ejecutar un buen proceso de extendido es necesario reconocer las características del material textil para realizar una identificación previa y así comprender el comportamiento que puede tener durante el proceso de extendido, como encogimiento, deslizamiento, despiste en el hilado, etc. Según el análisis obtenido mediante la observación del textil, se puede determinar la ubicación de los moldes, las herramientas óptimas a utilizar, si requiere o no un reposo previo y la dirección. #[b Los puntos que debes tener identificados son: 1. La urdimbre y la trama, 2. Hilo de tela y 3. Anchos de las telas].
    
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 3.
          span Anchos de telas
        .tabla-b.color-acento-contenido.borde-top-table
          
          table
            caption Nota. Tomada de SENA (2021).
            thead
              tr
                th.w-35-th.tabla-b__header.h4.mb-0.txt-start Anchos de fábrica
                th.tabla-b__header.h4.mb-0.txt-start Descripción
            tbody
              tr.bg-white
                th Ancho simple
                td Están elaborados a partir de 70 cm a 90 cm de ancho. En este grupo se encuentran: cambre, paños, fieltro, blonda, satén, lino, etc.
              tr
                th Ancho angosto
                td Están elaborados a partir de 0,5 mm hasta 25 cm de ancho. En este grupo se encuentran: encajes, franjas, cintas, elásticos, etc. 
              tr.bg-white
                th Doble ancho
                td Están elaborados a partir de 140 cm hasta 150 cm de ancho. En este grupo se encuentran: paños, tafetán, popelina, crepé, entretelas, #[i denim], etc.
              tr
                th Ancho especial
                td Están elaborados a partir de 2,8 cm. En este grupo se encuentran: tapicería y decoración, etc.
    
    p.mb-4(data-aos="fade") Una parte muy importante de este proceso del extendido son los orillos de tela, los cuales son bordes longitudinales de la tela, que están tejidos con una apariencia diferente y densa. Surgen como consecuencia de tratamientos de humectación y secado que sufren las telas una vez han sido tejidas para su estabilización. Se perfora el tejido desde el revés hacia el derecho, por lo que, por regla general, las rebabas de las perforaciones en los orillos indican el derecho de la tela.
    
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
          span Componentes en prenda

        .tabla-b.color-acento-contenido.borde-top-table
          
          table
            caption Nota. Tomada de SENA (2021).
            thead
              tr
                th.w-50-th.tabla-b__header.h4.mb-0.txt-start Tipos de componentes en prenda de vestir
                th(colspan="2").tabla-b__header.h4.mb-0.txt-start Usos
            tbody
              tr.bg-white
                td #[b Componentes exteriores:] son todas las partes del material textil base o textil con que está elaborada la prenda en el exterior. 
                td.no-border-right
                  ul.lista-ul--color.color-secundario.f-12.mb-0
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
                  ul.lista-ul--color.color-secundario.f-12.mb-0
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
                  ul.lista-ul--color.color-secundario.f-12.mb-0
                    li
                      i.fas.fa-circle
                      | Forro.
                    li.mb-0
                      i.fas.fa-circle
                      | Entretela.
                td.no-border-left
                  ul.lista-ul--color.color-secundario.f-12.mb-0
                    li
                      i.fas.fa-circle
                      | Guata.
                    li.mb-0
                      i.fas.fa-circle
                      | Sesgo.
              tr.bg-white
                td #[b Hilos:] es uno de los elementos principales, son los que logran unir las diferentes partes de la prenda.
                td.no-border-right
                  ul.lista-ul--color.color-secundario.f-12.mb-0
                    li
                      i.fas.fa-circle
                      | Pespuntes.
                    li.mb-0
                      i.fas.fa-circle
                      | Puntadas decorativas.
                td.no-border-left
                  ul.lista-ul--color.color-secundario.f-12.mb-0
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
            p Se sitúa la pieza de textil en un extremo de la mesa y se efectúa el estirado, mediante dos operarios/as o utilizando un carro de extendido, hasta el largo previamente establecido.
          .col-lg-6.col-md-11.mb-4(data-aos="fade-left")
            .titulo-sexto.color-primario.mb-2
              h5 Figura 1.
              span Tizado en material textil
            img(src='@/assets/curso/temas/t1/imag03.png', alt='En la figura se presenta la tela extendida sobre una superficie plana')
            figcaption Nota. Tomada de SENA (2021). 
              
    p.text-center.mb-4 Cuando se trabaja con un extendido manual (Video 2), es importante tener en cuenta las siguientes recomendaciones:
    
    .row.mb-5
      .col-md-6.col-lg.mb-4.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono02.svg' alt='')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Alineación:
                p.text-center El textil debe estar completamente alineado al orillo. De ser posible, se deben alinear los dos orillos.
      .col-md-6.col-lg.mb-4.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono03.svg' alt='')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Tensión:
                p.text-center En lo posible evitar la tensión en la tela, ya que, después del corte, las piezas cortadas quedarán reducidas (pequeñas en relación con el tamaño real del molde).
      .col-md-6.col-lg.mb-4.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono04.svg' alt='')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Arrugas:
                p.text-center Evitar que la tela se encuentre arrugada en el tendido, para que no se formen burbujas de aire en este, ocasionando distorsiones en el corte. 
      .col-md-6.col-lg.mb-4.mb-lg-0
        .tarjeta-avatar
            img(src='@/assets/curso/temas/t1/icono05.svg' alt='')
            .tarjeta.bg2.w-100
              .color-sistema-texto.p-4
                h4.text-center Consumo:
                p.text-center Cortar solamente lo necesario para evitar más consumo de tela, controlando el desperdicio, de acuerdo con la acomodación de los moldes. 
    
    .titulo-sexto.color-primario
      h5 Video 2.
      span Proceso de extendido

    .row.fondo-cta2.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-7.col-sm-6.col-md-3.col-lg-2.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t1/img-cta2.svg")
            .col-md.col-lg-6
              h4 Video – Proceso de extendido 
              p.mb-4 Conozca el proceso de extendido, teniendo en cuenta las diferentes maquinarias y herramientas implementadas, los diferentes tendidos abiertos y cerrados, pero además un barrido respecto al extendido industrial.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?app=desktop&v=Mnnt4AAnKJQ&feature=youtu.be')" target="_blank")
                span  Video
                i.fas.fa-video

    figcaption.mb-5(data-aos="fade") Nota. Tomado de SENA (2020).

    .row.justify-content-center
      .col-lg-6(data-aos="fade-right")
        .row.align-items-center.mb-2
          .col-2.col-md-1
            img(src='@/assets/curso/temas/t1/subt2.svg', alt='')
          .col-10.col-md-11
            h4.mb-0 Preparación del textil:
        p.mb-4 Algunos textiles pueden encogerse o elongarse después de ser sometidos al lavado o planchado; por tal motivo, se sugiere que, antes de realizar cualquier proceso de extendido y corte, el textil sea sometido a pruebas de % de elongación o reducción, pruebas de fusionado, lavado, planchado, e identificación de defectos textiles.
        .row.align-items-center.mb-2  
          .col-2.col-md-1
            img(src='@/assets/curso/temas/t1/subt3.svg', alt='')
          .col-10.col-md-11
            h4.mb-0 Características del material:
        p Para lo cual deben tenerse en cuenta diferentes tipos de trazos, como requerimientos desde patronaje, tendido y marcación, además las características del material.
      .col-lg-6.col-md-10.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/t1/imag04.png', alt='')
    

    Separador
    #t_1_3.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.3 Proceso de tizado
    
    p.mb-4(data-aos="fade") El tizado es un procedimiento que se realiza sobre el material textil con jaboncillo o tiza, teniendo en cuenta las características dimensionales del tejido a cortar. Este trazo se debe realizar por cada material, por ejemplo: trazos en tela, forro y entretelas. Pero además se tienen en cuenta algunos aspectos importantes, como: 

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul" data-aos="fade-down")
      .row.justify-content-center(titulo="Señalización")
        .col-lg-2.col-md-2.col-4.mb-3
          img.px-lg-4(src='@/assets/curso/temas/t1/acordion.svg', alt='')
        .col-lg-9.col-md-8.mb-4.mb-md-0
          p Para tener claro los requerimientos desde el área de patronaje, es importante identificar y conocer la respectiva señalización de patrones.
          .row
            .col-md-6
              ul.lista-ul--color.color-acento-botones.f-12.mb-0
                li
                  i.fas.fa-play
                  | Hilo de tela.
                li
                  i.fas.fa-play
                  | Referencia o diseño.
                li
                  i.fas.fa-play
                  | Nombre de la pieza.
                li
                  i.fas.fa-play
                  | Número de veces a cortar.
            .col-md-6
              ul.lista-ul--color.color-acento-botones.f-12.mb-0
                li
                  i.fas.fa-play
                  | Tipo de material.
                li
                  i.fas.fa-play
                  | Número de pieza en el tendido.
                li
                  i.fas.fa-play
                  | Piquetes.
                li
                  i.fas.fa-play
                  | Plantilla.
      .row.justify-content-center(titulo="Trazo bidireccional - vello en ambos sentidos")
        .col-md-2.mb-3.col-4
          img.px-lg-3(src='@/assets/curso/temas/t1/acordion2.svg', alt='')
        .col-lg-4.col-md-12
          p Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza doble; se pueden ubicar los patrones en dos sentidos de dirección. El material textil que se utilice no debe tener restricción con respecto a sus características.
          
        .col-lg-5.col-md-12
          .titulo-sexto.color-acento-botones.mb-2
            h5 Figura 2.
            span Señalización en dos direcciones
          figure
            img(src='@/assets/curso/temas/t1/acordion3.png', alt='En la imagen se presenta  la marcación en la tela en dos direcciones,  primero el trazo  representado en una flecha vertical de doble saeta,  luego el trazo  en el molde de  un bolsillo  con la flecha de doble saeta y posteriormente en el molde en la tela,   dos bolsillos  en diferentes sentidos,con las flechas hacía arriba y hacía abajo significando ambas direcciones.')      
            figcaption Nota. Tomada de SENA (2021). 
      .row.justify-content-center(titulo="Trazo direccional")
        .col-md-2.col-4.mb-3
          img.px-lg-3(src='@/assets/curso/temas/t1/acordion4.svg', alt='')
        .col-lg-4.col-md-12
          p Vello en un solo sentido: este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza hacia arriba o hacia abajo; se deben colocar los patrones en una sola dirección. Este procedimiento de marcado tendrá por resultado un producto con la más elevada calidad, pues este tipo de trazo se usa para materiales que tienen restricción con respecto a características como brillo, cambio de color al tacto, estampados, dirección de pelo/vello, entre otras.
        .col-lg-5.col-md-12
          .titulo-sexto.color-acento-botones.mb-2
            h5 Figura 3.
            span Señalización en una dirección
          figure
            img(src='@/assets/curso/temas/t1/acordion5.png', alt='La figura hace referencia a la señalización en una dirección, primero se presenta el trazo representado por dos flechas verticales hacía arriba y hacía abajo, también el marcado en el molde de un bolsillo con la flecha hacía arriba y finalmente dos bolsillos con el trazo en una sola dirección ambos, con las flechas hacía arriba')      
            figcaption Nota. Tomada de SENA (2021). 

      .row.justify-content-center(titulo="Trazo en sesgo - vello en diagonal")
        .col-md-2.col-4.mb-3
          img.px-lg-3(src='@/assets/curso/temas/t1/acordion6.svg', alt='')
        .col-lg-4.col-md-12
          p Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza inclinada en diagonal; se deben colocar los patrones en ese sentido de dirección.
          
        .col-lg-5.col-md-12
          .titulo-sexto.color-acento-botones.mb-2
            h5 Figura 4.
            span Señalización para sesgar
          figure
            img(src='@/assets/curso/temas/t1/acordion7.png', alt='En la imagen se representa la señalización para sesgar con tres flechas diagonales, la primera flecha con la saeta hacía abajo la segunda con la saeta hacía arriba y la tercera en doble saeta, también se presenta el trazado sobre el molde del bolsillo representado con flecha con doble saeta y el marcado en la tela sobre el bolsillo inclinado en diagonal hacía la izquierda.')
            figcaption Nota. Tomada de SENA (2021). 

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-8
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t1/imag05.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p Para la señalización se debe tener en cuenta: #[br]
              | #[b Referencia o nombre de cliente:] ref:20201208. #[br]
              | #[b Nombre de la pieza:] delantero o frente. #[br]
              | #[b Tipo de material:] Tela 1. Material base. #[br]
              | Tela 2. Material forro. #[br]
              | Tela 3. Material entretela. #[br]
              | #[b Número de pieza en el tendido:] ½.

    
    Separador
    #t_1_4.titulo-segundo.color-primario(data-aos="fade-right")
      h2 1.4 Proceso de corte
    
    p.mb-5(data-aos="fade") El corte se define como proceso de transformación de la materia prima textil (tejido o tela) en piezas útiles para confeccionar prendas de vestir. Este proceso de transformación se realiza utilizando máquinas especializadas de corte o con tijeras convencionales.

    h3(data-aos="fade-right") Corte 
    p.mb-4(data-aos="fade") Existen diferentes tipos de corte. El manual, que requiere de la utilización de tijeras, más o menos de 8 pulgadas, como las usadas solo para corte de tela; se colocan directamente los moldes y se procede a cortar. El convencional, que utiliza maquinaria y equipos electromecánicos; disminuye la intervención de operaciones manuales. Y el automático, que tiene una unidad de control conformada por el ordenador con #[i software] especializado, el cabezal de corte y el carro extendedor automático; aumenta el rendimiento de espacio y tiempos de corte.
    
    .row.justify-content-center.mb-5
      .col-lg-9.mb-4(data-aos="fade-right")
        TabsA.t1-4.color-secundario
          .tarjeta.color-acento-contenido.p-4(titulo="a) Introducción:")
            p El tendido y marcación son una parte clave para el proceso de corte, este procedimiento requiere de precisión y técnica. Una vez identificados los requerimientos desde el área de patronaje, se procede a realizar el tendido y la marcación. Para ello, es importante seguir los siguientes pasos: identificar el ancho útil, la ubicación de patrones, la marcación y el corte.
          .tarjeta.color-acento-contenido.p-4(titulo="b) Ancho útil:")
            p Es importante su identificación en el material textil antes de empezar a desarrollar el trazo, para lo cual se sugiere la identificación del #[b ancho total del textil y la medición del orillo]. Es importante indicar que el #[b ancho útil se halla restando el orillo al ancho total de la tela].
          .tarjeta.color-acento-contenido.p-4(titulo="c) Ubicar patrones:")
            p La ubicación de los patrones es una tarea indispensable, y, una vez esto se hace, se debe analizar y alistar el tipo de extendido/tendido a trabajar y el ancho útil, a partir de los requerimientos del patrón desde el área de patronaje.
            p.mb-4 Luego de esto, se procede a hacer el trazo o marcación del molde o patrón en el textil. 
            .bg9.px-5.py-4.w-75.mb-4
              .titulo-sexto.color-primario.mb-2
                  h5 Figura 5.
                  span Acomodación de patrones
              figure
                img(src='@/assets/curso/temas/t1/figura5.png', alt='En la figura se disponen sobre la tela extendida los diferentes patrones.')  
                figcaption Nota. Tomada de SENA (2021). 
            p De acuerdo con lo anterior, es importante saber cómo transferir patrones. Para transferir patrones al textil, existen dos formas que son las más implementadas: marcar con tiza o jabón y pinar o utilizar alfileres.      
          .tarjeta.color-acento-contenido.p-4(titulo="d) Pesas para sujetar:")
            p.mb-4 Son bloques con diferentes pesos y de superficie plana. Su función es ayudar a que el patrón no se mueva en el momento del tizado. Es importante forrarlos para que no contaminen la tela.  
            .bg9.px-5.py-4.mb-4
              .titulo-sexto.color-primario.mb-2
                  h5 Figura 6.
                  span Pesas
              figure
                img(src='@/assets/curso/temas/t1/figura6.png', alt='En la figura se disponen sobre la tela extendida los diferentes patrones.')  
                figcaption Nota. Tomada de SENA (2021).    
          .tarjeta.color-acento-contenido.p-4(titulo="e) Tipos de marcación  -Hilván (<i>tailor tacks</i>):")
            p.mb-4 Es el método más utilizado por los sastres para marcaciones especiales sobre el textil. Este método tiene puntos con hebras de hilo que sirven de guía, sin llegar a manchar el textil, se trata de una puntada suelta, en bucle, como una indicación de dónde coser finalmente. 
            .bg9.px-5.py-4.mb-4
              .titulo-sexto.color-primario.mb-2
                  h5 Figura 7.
                  span #[i Tailor tacks]
              figure
                img(src='@/assets/curso/temas/t1/figura7.png', alt='En la imagen se  presenta la marcación  con  puntadas sueltas en hebras de hilo rojo.')  
                figcaption Nota. Tomada de SENA (2021).  
          .tarjeta.color-acento-contenido.p-4(titulo="f) Tipos de marcación - alfileres:")
            p Es importante fijar los patrones con alfileres, los cuales vienen en una variedad de tamaños. Para el caso de telas gruesas, se deben utilizar alfileres grandes y largos. En caso de telas delgadas y delicadas, como la seda, se utilizan alfileres pequeños y cortos para evitar dañarlas. Para esto, se insertan los alfileres cada 3 cm alrededor del patrón y en puntos clave. Se recomienda no coger mucha cantidad del textil, para evitar los bucles y malformaciones a la hora de pinar. Es recomendable ubicar los alfileres de forma diagonal.      
          .tarjeta.color-acento-contenido.p-4(titulo="g) Pinar:")
            p Es la inserción de alfileres en el textil para asegurar el molde. Es importante tener en cuenta que no es adecuado asegurar la tela con cinta, fijar los patrones, cortar el margen del patrón de forma inadecuada o marcar con tiza de forma inadecuada, porque esto podría dañar la tela.      
          .tarjeta.color-acento-contenido.p-4(titulo="h) Proceso de corte:")
            p Luego de realizar y seguir cada uno de los pasos, para una adecuada calidad del proceso, se continúa con el corte del textil de acuerdo con la marcación. Para ello es importante conocer las herramientas fundamentales para este proceso y elegir las adecuadas y que garantizan una mejor calidad.      
          .tarjeta.color-acento-contenido.p-4(titulo="i) <i>Tips</i> de corte: ")
            p Para el proceso de corte es importante tener en cuenta algunos aspectos elementales que favorecen el proceso, como sostener el material con la mano contraria a su lateralidad; realizar cortadas amplias; evitar que el tendido se mueva, solo debe hacerlo la tijera, la mano y el cortador, de acuerdo con la necesidad; en cada piquete se debe hacer un pequeño corte de máximo 3 mm de profundidad.
            a.anexo.mb-4(:href="obtenerLink('/downloads/CF6_Anexo6_Corte_De_Las_Telas.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p.mb-0 #[b Anexo.] Corte de las telas. Conozca la importancia de examinar la tela para hacer un corte adecuado en el patronaje.
          .tarjeta.color-acento-contenido.p-4(titulo="j) Textiles con <i>nap</i>-vello -pelusa de un textil:")
            p #[i Nap] es la textura de los textiles que van en una dirección particular; esta propiedad de la prenda es fundamental para garantizar su calidad. En algunos textiles se logra evidenciar el #[i nap] a simple vista, como en #[i velvet, fleece], piel sintética, #[i denim] cepillado, franela, gamuza sintética, sarga elástica, tela de felpa, etc. El #[i nap] es muy importante para determinar cómo se establece el patrón en el textil; en este caso, se trabaja siempre un trazo direccional, para lo cual se deben tener en cuenta los acabados de la prenda y determinar el consumo del textil.
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?app=desktop&v=OfsjJ8VdU8A&feature=youtu.be" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p.mb-0 #[b  Video 3.] Características del material desde trazo y corte. Conozca las características especiales de gran parte de materiales textiles y algunas recomendaciones respecto a su proceso de tendido, marcado y corte.
      .col-lg-3.col-md-5.col-7(data-aos="fade-left")
        img(src='@/assets/curso/temas/t1/imag06.png', alt='')
      


    p.mb-4(data-aos="fade") Para identificar un buen #[i nap]/pelusa es importante pasar las manos suavemente para sentirlo. Se debe tener en cuenta que la sensación más suave es la dirección "con el #[i nap]/pelusa" y la sensación más áspera es la dirección "contra el #[i nap]/pelusa". Es importante precisar que el brillo de la tela es diferente cuando se ve desde diferentes direcciones. A continuación, se relacionan algunas consideraciones: 

    SlyderF.mb-5(columnas="col-lg-4" data-aos="fade-down")
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Acabado de la prenda:] si no se tiene en cuenta el #[i nap] al momento de cortar la prenda, esta puede terminar con brillos diferentes en cada pieza. Se debe tener en cuenta que se necesita un color y una textura uniforme en toda la pieza.        
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder2.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Consumo de material:] se debe determinar qué tanto consumo de material se va a implementar en la prenda, para garantizar que todo el textil sea suficiente para el corte. Si esto no se hace, se puede desperdiciar mucha tela.      
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder3.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Trazado o marcado:] se recomienda que cuando se utilice este tipo de textiles con #[i nap], el proceso de transferir los moldes al textil se trabaje preferiblemente en un tendido abierto sujetado con alfileres. Para marcar pinzas o elementos clave, se recomiendan los hilvanes o <i>tailor tacks</i>.      
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder4.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Piel sintética:] la piel sintética también cuenta con #[i nap]/pelusa. Es mucho más sencillo identificar la dirección del vello. Algunas tienen el vello más largo que otras, por eso es importante realizar el trazo, marcado y corte de forma adecuada; para ello es indispensable tener presente:
            ul.lista-ul--color.fa-ul.color-acento-botones.mb-0
              li.mb-1
                i.fas.fa-angle-right
                | Trazo direccional.
              li.mb-1
                i.fas.fa-angle-right
                | Tendido abierto.
              li.mb-0
                i.fas.fa-angle-right
                | Marcación por el revés, con tiza.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder5.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b #[i Tips] de corte - piel sintética:] cortar en el sentido del vello/#[i nap]. Para ello, es importante realizar cortadas pequeñas, preferiblemente con la punta de la tijera. Una vez cortado, se recomienda eliminar el exceso de vello/pelo por el margen de costura, teniendo en cuenta la dirección del pelo. Se recomienda confeccionarlo en esa misma dirección.      
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder6.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Textiles estampados:] estos se deben trabajar con un trazo direccional, ya que de esto depende la dirección del estampado que se desee en la prenda terminada. Esto significa que todas las piezas deben cortarse en la misma dirección para que el estampado quede acorde al diseño.      
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder7.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Textiles de cuadros:] la continuidad de las líneas y el dibujo/cuadros en las prendas produce un efecto agradable a la vista. Casar cada una de las líneas, cuadros o elementos del dibujo del textil requiere de precisión. Esto se utiliza en prendas de muy altos estándares de calidad, ya que el corte se debe hacer preferiblemente individual. Algunos #[i tips] para este tipo de cortes son: 
            ul.lista-ul--color.fa-ul.color-acento-botones.mb-0
              li.mb-0
                i.fas.fa-angle-right
                | Ubicar los patrones en el textil y alinearlos para que coincidan las líneas.
              li.mb-0
                i.fas.fa-angle-right
                | Trazar en los patrones las líneas.
              li.mb-0
                i.fas.fa-angle-right
                | Realizar esto con cada una de las piezas de la prenda.
              li.mb-0
                i.fas.fa-angle-right
                | Una vez ubicados, se deben ir pintando y agregando margen de costura con tiza.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t1/slyder8.svg' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p #[b Tendido y corte:] para los textiles de cuadros, se recomienda trabajarlos de la siguiente manera:
            ul.lista-ul--color.color-acento-botones.mb-0
              li.mb-1
                i.fas.fa-angle-right
                | Trabajar despiece sin costura.
              li.mb-1
                i.fas.fa-angle-right
                | Trazo direccional.
              li.mb-1
                i.fas.fa-angle-right
                | Tendido abierto cara arriba.
              li.mb-1
                i.fas.fa-angle-right
                | Marcación por el revés con tiza.
              li.mb-0
                i.fas.fa-angle-right
                | Fijar los patrones con alfileres.
      
    .titulo-sexto.color-primario(data-aos="fade")
      h5 Video 4.
      span Ejemplo de tipos de tendido con diferentes características del material

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/-nkWodY_bPE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Tipos de tendido con diferentes características del material

    //.row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-8.col-sm-6.col-md-4.col-lg-3.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t1/imagvideo.svg")
            .col-md.col-lg-6
              h4 Video - Tipos de tendido con diferentes características del material. 
              p.mb-4 Conozca el trazo de los básicos, prendas de vestir, despiece y análisis de cada una de las partes que componen una prenda.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=-nkWodY_bPE')" target="_blank")
                span Consultar video
                i.fas.fa-video

    
    h3(data-aos="fade-right") Marcación y revisión
    p.mb-4(data-aos="fade") Para realizar la marcación y revisión, se debe partir desde un fusionado. Una vez se cortan la tela y la entretela, existen piezas programadas para entretelar, por eso se requiere utilizar fusionado con calor o con técnica de sastre.
    
    .row.justify-content-center
      .col-11.col-md-9.col-lg-6.mb-4(data-aos="fade-right")
        .titulo-sexto.color-primario
          h5 Figura 8.
          span Fusionado de entretela
        img(src='@/assets/curso/temas/t1/imag07.png', alt='En tres imágenes se presenta la manera como se aplica el calor sobre la tela y la entretela con una plancha ')
        figcaption Nota. Tomada de Únicosé (2019).
      .col-11.col-md-9.col-lg-6.mb-4(data-aos="fade-left")
        .titulo-sexto.color-primario
          h5 Figura 9.
          span Picado de solapa
        img(src='@/assets/curso/temas/t1/imag08.png', alt='En la figura se representa el picado de solapa para fusionar la tela y la entretela mediante la técnica de sastre.')
        figcaption Nota. Tomada de Flo (2020).
        
        


    


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
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
