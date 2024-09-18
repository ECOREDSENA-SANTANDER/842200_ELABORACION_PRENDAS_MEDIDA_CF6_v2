<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Técnicas básicas de sastrería
    
    .row.align-items-center.justify-content-center
      .col-lg-4.col-md-7.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t2/imag01.png', alt='')
      .col-lg-8(data-aos="fade-left")
        p La elaboración de prendas de vestir femeninas y masculinas exteriores, basadas en las medidas deducidas de cada cliente y en cuya construcción se aplican técnicas manuales específicas, recibe el nombre de sastrería. Los inicios de la sastrería datan de la antigua Roma, cuando era vista como una tarea simple realizada por los artesanos; su fin era satisfacer los caprichos de la clase dominante, conocida como los patricios. Ya durante la edad media, desaparece la túnica y se introducen prendas más ajustadas, generando la necesidad de ser más precisos en el calce y concibiendo desafíos para las personas que desempeñaban esta labor. Es en esos tiempos donde el sastre alcanza un nivel más artístico, pero es durante el renacimiento cuando los sastres y costureros llegan a ser considerados especialistas del arte de vestir. Sin embargo, aparece en el año 1820 el francés M. Guillermo Campaugne, con un método de corte y normas que transformaron por completo el oficio de sastre.
    
    
    Separador
    #t_2_1.titulo-segundo.color-primario(data-aos="fade-right")
      h2 2.1 Introducción a la sastrería
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t2/imag02.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Durante la línea de tiempo desde la antigua Roma hasta el día de hoy, la sastrería ha ido combinando sus procesos artesanales con avances tecnológicos que facilitan su desempeño, como son las planchas de vapor, las máquinas de coser sin pedal, puntadas programables y otros sistemas más desarrollados. En concordancia con lo expuesto, los procesos operativos que se desarrollan en este módulo siguen el método de construcción de un sastre mezclado con técnicas utilizadas a nivel industrial para facilitar la realización de las prendas.
    
    .row.align-items-center.mb-4(data-aos="fade-right")
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t2/icono.svg', alt='')
      .col-10.col-md-10
        h4.mb-0 Costuras manuales
    
    p.mb-4(data-aos="fade") Para iniciar con el proceso de formación de un sastre, es preciso conocer y dominar los principales tipos de puntadas a mano, donde solo se requiere una aguja, el hilo y la tela. Son técnicas artesanales que se emplean en la construcción de la prenda y en sus acabados. En las siguientes figuras se ilustran las costuras manuales más importantes.
    
    SlyderF.mb-5(columnas="col-lg-6" data-aos="fade-down")
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 10.
              span Puntada de pespunte o continua
            img(src='@/assets/curso/temas/t2/slyder.svg' alt='En la imagen hay un dibujo en el que con aguja e hilo sobre un trozo de tela se presenta la puntada de pespunte continua.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).       
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 11.
              span  Puntada punto atrás posterior o máquina
            img(src='@/assets/curso/temas/t2/slyder2.svg' alt='En la imagen hay un dibujo en el que con aguja e hilo se presenta la puntada punto atrás posterior o máquina.')
            figcaption Nota. Tomada de Celestecielo (2018).       
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 12.
              span  Punto de hilván
            img(src='@/assets/curso/temas/t2/slyder3.svg' alt='En la imagen hay un dibujo en el que con aguja e hilo se presenta la puntada de hilván.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 13.
              span  Puntada posterior separada
            img(src='@/assets/curso/temas/t2/slyder4.png' alt='En la imagen hay una foto de unas manos realizando, con aguja e hilo sobre un trozo de tela la puntada posterior separada.')
            figcaption Nota. Tomada de López (2020).       
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 14.
              span  Puntada de bastilla o de frunce
            img(src='@/assets/curso/temas/t2/slyder5.svg' alt='En la imagen se presenta un dibujo que representa la puntada de bastilla o de frunce.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 15.
              span Puntada de sobrehilado
            img(src='@/assets/curso/temas/t2/slyder6.svg' alt='En la imagen hay un dibujo de un trozo de tela en el que con aguja e hilo se presenta la puntada de sobrehilado.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 16.
              span Punto de lado o inglés (para dobladillos)
            img(src='@/assets/curso/temas/t2/slyder7.svg' alt='En la imagen hay un dibujo de un trozo de tela con aguja e hilo en el que se presenta el punto de lado utilizado para dobladillos.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 17.
              span Puntada doble sobrehilado
            img(src='@/assets/curso/temas/t2/slyder8.svg' alt='En la imagen hay un dibujo de un trozo de tela con aguja e hilo en el que se presenta la puntada doble sobrehilado.')
            figcaption Nota. Tomada de Celestecielo (2018).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 18.
              span Punto de picado o espiga
            img(src='@/assets/curso/temas/t2/slyder9.svg' alt='En la imagen hay un dibujo en el que con aguja e hilo se presenta la puntada de picado o espiga, de arriba hacía abajo y de abajo hacía arriba.')
            p Se hace de arriba hacia abajo o de abajo hacia arriba, dando pequeñas puntadas con regularidad, que calen muy poco por el otro lado. Se utiliza para unir la entretela con el tejido exterior.
            figcaption Nota. Tomada de Hymsa (1991).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 19.
              span Punto deslizado
            img(src='@/assets/curso/temas/t2/slyder10.svg' alt='En la imagen hay un dibujo en el que con aguja e hilo se presenta el punto deslizado.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 20.
              span Puntada invisible 
            img(src='@/assets/curso/temas/t2/slyder11.svg' alt='En la imagen hay un dibujo de un trozo de tela en el que, con aguja e hilo, se presenta la puntada invisible.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 21.
              span Punto de cruz
            img(src='@/assets/curso/temas/t2/slyder12.svg' alt='En la imagen hay un dibujo de un trozo de tela en el que, con aguja e hilo, se presenta el punto de cruz.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 22.
              span Puntada de filete, festón o manta
            img(src='@/assets/curso/temas/t2/slyder13.svg' alt='En la imagen hay un dibujo de un trozo de tela, en el que , con aguja e hilo se presenta la puntada de filete, festón o manta.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 23.
              span Puntada cadeneta
            img(src='@/assets/curso/temas/t2/slyder14.svg' alt='En la imagen hay un dibujo de la puntada cadeneta.')
            figcaption Nota. Tomada de Hymsa (1991).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 24.
              span Puntada de ojal
            img(src='@/assets/curso/temas/t2/slyder15.svg' alt='En la imagen hay un dibujo en el que en un trozo de tela, con aguja e hilo, se presenta la puntada de ojal.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).       
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 25.
              span Hilván flojo
            img(src='@/assets/curso/temas/t2/slyder16.svg' alt='En la imagen hay dos dibujos , en el primero , en un trozo de tela con aguja e hilo se presenta la puntada hilván flojo y en el segundo el trozo de tela se levanta para dejarla ver.')
            figcaption Nota. Tomada de Manos Maravillosas (2019).      
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-11
            .titulo-sexto.color-secundario.mb-2
              h5 Figura 26.
              span Puntada escapulario o gaviado
            img(src='@/assets/curso/temas/t2/slyder17.svg' alt='En la imagen hay un dibujo en el que, con aguja e hilo, se presenta la puntada escapulario o gaviado.')
            figcaption Nota. Tomada de Celestecielo (2018).

    .titulo-sexto.color-primario(data-aos="fade")
      h5 Video 5.
      span Puntadas básicas para bordar a mano
    
    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-8.col-md-4.col-lg-3.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t2/imagvideo.svg")
            .col-md.col-lg-6
              h4 Video - 11 puntadas a mano básicas 
              p.mb-4 Conozca cómo se repara, decora, fija apliques y accesorios a las labores de bordado, costura y confección.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=d-8rJrzXRIQ&list=TLPQMjEwNDIwMjGTkED5jSqnWA&index=3&ab_channel=PuntadasCountry')" target="_blank")
                span Consultar Video
                i.fas.fa-video

    figcaption.mb-5(data-aos="fade") Nota. Tomado de López (2020).
    
    h4.text-center.mb-4(data-aos="fade-down") Pasos para realizar un ruedo con #[i roulette]
    p(data-aos="fade") El término #[i roulette] viene del verbo francés #[i rouler], que significa #[b ‘rodar’.] Este tipo de costura es utilizada para hacer dobladillos en prendas finas de tejidos livianos. Se tienen dos opciones: con técnica manual o con máquina de coser. A continuación, se presenta el paso a paso para realizarlo. 
    p.mb-4(data-aos="fade") Conozca los pasos para hacer un ruedo tipo #[i roulette].

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-4.col-md-6.mb-4
        img.mb-4(src="@/assets/curso/temas/t2/imag03.svg")
        h4.mb-4 Paso 1. 
        p Con los dedos pulgar e índice se debe doblar 3 mm del ruedo de la tela e introducir la aguja en el borde superior del doblez, tomando 1 mm de tela y sacándola en la misma dirección. Esta misma acción se debe repetir, pero ya hacia la izquierda, sin tensionar el hilo.
        a.boton.color-acento-botones.indicador__container.mb-4(@click="modal1 = true")
          span.fw-bold Consultar imagen
      .col-lg-4.col-md-6.mb-4
        img.mb-4(src="@/assets/curso/temas/t2/imag04.svg")
        h4.mb-4 Paso 2. 
        p Una vez cosidos 3 cm de borde, se debe presionar con los dedos el inicio del doblez y tirar suavemente el hilo hasta que las puntadas queden tensas. Al tirar el hilo las puntadas se irán ocultando, formando automáticamente el #[i roulette].
        a.boton.color-acento-botones.indicador__container.mb-4(@click="modal2 = true")
          span.fw-bold Consultar imagen
          .indicador--click(v-if="mostrarIndicador")
      .col-lg-4.col-md-6.mb-4
        img.mb-4(src="@/assets/curso/temas/t2/imag05.svg")
        h4.mb-4 Paso 3. 
        p Se debe repetir esta acción hasta terminar el ruedo e ir tirando siempre el hilo cada 3 cm para lograr una mejor tensión del ruedo.
        a.boton.color-acento-botones.indicador__container.mb-4(@click="modal3 = true")
          span.fw-bold Consultar imagen
    
    ModalA(:abrir-modal.sync="modal1")
      .row.align-items-center.justify-content-center
        .col-11.col-md-10.col-lg-6
          .titulo-sexto.color-acento-botones.mb-2
            h5 Paso 1.
          figure
            img(src='@/assets/curso/temas/t2/paso1.png', alt='') 
    ModalA(:abrir-modal.sync="modal2")
      .row.align-items-center.justify-content-center
        .col-11.col-md-10.col-lg-6
          .titulo-sexto.color-acento-botones.mb-2
            h5 Paso 2.
          figure
            img(src='@/assets/curso/temas/t2/paso2.png', alt='') 
    ModalA(:abrir-modal.sync="modal3")
      .row.align-items-center.justify-content-center
        .col-11.col-md-10.col-lg-5
          .titulo-sexto.color-acento-botones.mb-2
            h5 Paso 3.
          figure
            img(src='@/assets/curso/temas/t2/paso3.png', alt='') 

    .row.justify-content-center
      .col-lg-6(data-aos="fade-right")
        .row.align-items-center.mb-4
          .col-2.col-md-1
            img(src='@/assets/curso/temas/t2/icono.svg', alt='')
          .col-10.col-md-11
            h4.mb-0 Cojines de sastre.
        p Los cojines de sastre son soportes de apoyo para planchar costuras e ir generando las curvas requeridas en la tela. Vienen en diferentes tamaños y formas. Generalmente, están forrados en tela de algodón y rellenados con picadillo de tela o aserrín. El cojín en forma de lágrima y el cojín rodillo tienen las mismas funciones, su utilización va a depender principalmente de la pieza o necesidad requerida.
      .col-lg-6.col-md-11.mb-4(data-aos="fade-left")
        .titulo-sexto.color-primario.mb-2
          h5 Figura 27.
          span Cojines de sastre
        img(src='@/assets/curso/temas/t2/imag06.png', alt='En la figura se presenta una fotografía de cuatro cojines de sastre de diferentes formas y tamaños.')
        figcaption Nota. Tomada de SENA (2021). 
    Separador
    #t_2_2.titulo-segundo.color-primario(data-aos="fade-right")
      h2 2.2 Preparación y detalles en las piezas

    p.mb-4(data-aos="fade") La preparación de insumos y de detalles en las piezas es un proceso que se va realizando antes del armado, son pasos característicos en el quehacer de un sastre. Buscan no solo la adaptación perfecta de la tela en el cuerpo, sino que cada insumo se adapte de forma precisa en el momento de adherirse a la prenda o pieza textil. Existen varios pasos que se deben seguir para su preparación, entre ellos se encuentran la realización de cambrado del cierre, planchado de costuras y pinzas, y colocación de broches. A continuación, se presenta la información relacionada: 
    
    .row.fondo-t1.align-items-center.py-4.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center

          h4.text-center.mb-4(data-aos="fade-down") Pasos para realizar un cambrado del cierre 

          .row.justify-content-center.mb-5(data-aos="fade-down")
            .col-sm-6.col-lg-4.mb-4.mb-lg-0
              .tarjeta--boton.color-primario.bg3.p-4.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure
                      img(src='@/assets/curso/temas/t2/imag07.png', alt='')
                p Para iniciar este proceso, se debe humedecer la tela del cierre.
            .col-sm-6.col-lg-4.mb-4.mb-lg-0
              .tarjeta--boton.color-primario.bg3.p-4.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure
                      img(src='@/assets/curso/temas/t2/imag08.png', alt='')
                p Luego, colocar la plancha teniendo cuidado de no quemarlo. Con la mano contraria, se estira el cierre hasta que vaya cediendo y genere ondulación. Este paso se debe realizar en ambos lados.       
            .col-sm-6.col-lg-4.mb-4.mb-lg-0
              .tarjeta--boton.color-primario.bg3.p-4.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure
                      img(src='@/assets/curso/temas/t2/imag09.png', alt='')
                p De este modo el cierre se ajustará perfectamente a la curvatura del cuerpo.
          
          h4.text-center.mb-4(data-aos="fade-down") Pasos para planchado de costuras y pinzas 

          .tarjeta.tarjeta--verde.p-4.mb-5(data-aos="fade-down")
            SlyderA.t2-2
              .row.justify-content-center.align-items-center
                .col-10.col-md-5.mb-4.mb-md-0
                  img(src='@/assets/curso/temas/t2/imag10.png', alt='')
                .col-10.col-md-5
                  h5 Paso 1.
                  p.mb-3 Se inicia humedeciendo la prenda y ubicándola sobre una pieza plana de madera, mármol o fornica.
                  p.mb-3 Los dedos deben anteponerse cerca de la plancha para ir presionando la costura y así evitar imperfecciones en el planchado. 
                  p Para las telas que puedan tener brillo se debe utilizar un paño húmedo.
              
              .row.justify-content-center.align-items-center
                .col-10.col-md-5.mb-4.mb-md-0
                  img(src='@/assets/curso/temas/t2/imag11.png', alt='')
                .col-10.col-md-5
                  h5 Paso 2.
                  p Las pinzas se doblan en dirección a los costados y se deben planchar siguiendo los pasos anteriores. 
          
          h4.text-center.mb-4 Pasos para la colocación de broches

          .row
            .col-lg-6.mb-4.mb-md-0(data-aos="fade-right")
              .row.align-items-center.justify-content-center
                .col-md-5.col-8.z-99
                  img(src='@/assets/curso/temas/t2/t22-tarj1.png', alt='')
                .col-md-7
                  .bg4.p-4.ps-5.mn-l.mh-170
                    p.ps-4.mb-0 Ubica el broche evitando que sobrepase el borde de la pieza y que el ojo superior apoye en la costura, si la hay. Cubrir ambos ojos con puntadas seguidas del centro hacia afuera. No cortar el hilo.              
            .col-lg-6.mb-4.mb-md-0(data-aos="fade-left")
              .row.align-items-center.justify-content-center
                .col-md-7
                  .bg4.p-4.pe-5.mn-r.mh-170
                    p.pe-4.mb-0 Después de haber fijado la parte posterior del broche (los ojos), sin cortar el hilo, realizar 3 puntadas en el otro extremo del broche.
                .col-md-5.col-8.z-99
                  img(src='@/assets/curso/temas/t2/t22-tarj2.png', alt='')

    p.mb-4(data-aos="fade") Para dar continuidad al proceso de preparación y detalles de las piezas, es hora de conocer el molde para las hombreras. A continuación, se presenta el procedimiento que se debe seguir: 
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade")
      h5 Figura 28.
      span Molde para hombreras
    
    .row.align-items-center
      .col-lg-4.col-md-8.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t2/imag12.svg', alt='En la figura se presenta esquema del molde para hombreras, con las instrucciones sobre el procedimiento que se debe seguir para su preparación y detalles de las piezas.')
      .col-lg-8(data-aos="fade-left")
        ul.lista-ul--color.color-acento-botones.lista-ul--separador.fa-ul
          li 
            i.fas.fa-check
            | Ubicar el molde frente abajo, como lo indica el esquema, y girar el molde de la espalda con el cuello hacia abajo. Calcarlos unidos por los hombros. Tener presente no tener incorporados los centímetros de costura en las líneas de hombro.
          li 
            i.fas.fa-check
            | Del punto escote/hombro (A), bajar por toda la línea de hombro 2/3.
          li 
            i.fas.fa-check
            | Del punto hombro/sisa (B), bajar hacia el frente 1/3 del perímetro sisa frente, quedando ubicado el punto D.
          li 
            i.fas.fa-check
            | Del punto hombro/sisa (B), subir por la espalda ½ del perímetro de la sisa espalda, donde quedará ubicado el punto E.
          li 
            i.fas.fa-check
            | Dibujar la forma de la hombrera como lo indica el esquema; recortar y agregar los cm de costura según la terminación deseada.
        figcaption Nota. Tomada de Delego (1983).
    

    Separador
    #t_2_3.titulo-segundo.color-primario(data-aos="fade-right")
      h2 2.3 Tipos de entretela y uso
    
    p.mb-5(data-aos="fade") Para alcanzar un buen calce en la prenda y una perfecta caída de la tela, no basta con realizar buenos moldes, pues no solo el tejido y la construcción son importantes, sino también, en gran medida, la forma como se utilizan las entretelas. Aunque no se puede evidenciar este refuerzo en el derecho de la tela, en el momento de usar dicha prenda, marcará la diferencia. Para chaquetas y abrigos ligeros, se recomienda utilizar una entretela de tejido fino; para telas gruesas, se recomienda elegir una entretela de crin o lana.
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.mb-4(data-aos="fade-right")
        .row.align-items-center.mb-4
          .col-2.col-md-1.w-60
            img(src='@/assets/curso/temas/t2/icono.svg', alt='')
          .col-10.col-md-10
            h4.mb-0 Tipos de entretelas
        p.mb-4 Las entretelas tienen como propósito lograr resultados con alta calidad. Al ser usadas aportan a reforzar y a estructurar ciertas partes de la prenda para mantener su forma y mejorar los acabados. Debemos tener en cuenta que su aplicación modifica el tacto y la durabilidad de la prenda; también nos permite coser con agilidad y, si es empleada en tejidos con elastómeros, hace que pierdan parcialmente su elasticidad.
        p.mb-4 Las entretelas se fabrican de diferentes tipos de fibras y grosores; dependiendo de la prenda, se pueden utilizar varios tipos de entretela. Otra cosa para tener en cuenta para la selección es el grosor de la tela, el cual dependerá de la caída que se desee en la misma. 
        .cajon.color-primario.bg5.p-4
          p.mb-0 En el mercado textil existe una gran variedad de entretelas con diferentes usos. Algunas son para termo-fijar con calor (son más utilizadas a nivel industrial), otras para coserse a la prenda y otras varias entretelas son específicas para campos como los tejidos elásticos, cuero o pieles. También existe una inmensa gama de artículos de ayuda, como cintas, cintas perforadas y formas troqueladas, que aseguran una producción económica. A continuación, se relaciona la clasificación de entretelas: 
      .col-lg-4.col-md-6.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/t2/imag13.png', alt='')
    
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg6" data-aos="fade-down")
      .row.justify-content-center(titulo="Tela")
        .col-md-11
          p Las telas usadas como entretelas pueden ser tejidas, no tejidas o de punto. Las características de la construcción de estas darán diferentes propiedades a las telas. En este sentido, no todas las que se utilizan como entretelas son producidas para tal fin. Hay algunos tipos de forros, batistas, muselinas, e inclusive la misma tela exterior, que pueden usarse como entretela.
      .row.justify-content-center(titulo="Entretelas no tejidas")
        .col-md-11
          p Por lo general, están hechas de poliéster, rayón, nailon o una mezcla de diferentes fibras, las cuales son distribuidas al azar y juntadas por acción química o térmica. Ya que no tienen una dirección de hilo o grano, no se desmechan y pueden ser cortadas en cualquier dirección o ángulo. Hay que ser muy cuidadoso para seleccionar la más apropiada.
      .row.justify-content-center(titulo="Entretelas fusionables")
        .col-md-11
          p Son diseñadas para proveer las ventajas de la entretela cuando esté unida a la superficie interna de la tela externa, bajo la influencia de temperatura, tiempo y presión. De hecho, la adherencia de la entretela fusionable a la tela externa produce un laminado nuevo a la tela, en el cual las características de la entretela se agregan a las de la tela externa.
      .row.justify-content-center(titulo="Entretelas de punto o malla")
        .col-md-11
          p Están disponibles por inserción de trama, inserción de urdimbre y tricota. Las de nailon tienen estiramiento a lo ancho y estabilidad a lo largo. Este tipo añade forma y cuerpo a prácticamente cualquier tela, tejida o de punto. 
      .row.justify-content-center(titulo="Entretelas tejidas")
        .col-md-11
          p Pueden ser de algodón, rayón, lana, poliéster o mezclas de fibras. Se tejen de la misma forma que las telas normales (urdimbre / trama). Usualmente, cuando se cortan al sesgo, estiran más y se utilizan entonces para dar forma. Son ideales para aplicar en tejidos de algodón, piqué, lino, lonetas, etc. 

    p.mb-4(data-aos="fade") Además de conocer la clasificación de entretelas, también es importante conocer las más utilizadas. A continuación, se relacionan algunos nombres:      
    
    .row.tarj-t23.mb-5(data-aos="fade-down")
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Friselina:] primero se adhiere con calor al primer tejido, se retira el papel y se vuelve a aplicar la plancha para adherirse a la otra tela.
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta2.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
             p.mb-0 #[b Sidó:] es el tejido de poliéster, viscosa, pelo de animal y lana, que se presenta en una amplia variedad de gramajes. Posee un muy buen rebote y recuperación, por lo que es utilizado para la construcción de plastrones, refuerzo de plastrones y cabezas de manga.
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta3.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Plastrón:] tejido de poliéster, viscosa, pelo de animal y lana, que se presenta en una amplia variedad de gramajes. Posee un muy buen rebote y recuperación, por lo que es utilizado para la construcción de plastrones, refuerzo de plastrones y cabezas de manga.	
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta4.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Entretelas afieltradas:] con textura similar al fieltro, sirven para aplicar sobre tejidos gruesos, como abrigos. Son muy útiles, ya que por su disposición permiten ser aplicadas de forma sencilla sobre la tela final sin que esta se aplaste, pues se pegan con total facilidad. Al observar, tienen dos caras, una con una textura «de pelo» y otra donde se aprecia el pegamento que fijará a la tela. 
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta5.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Hidrosolubles:] se trata de unas entretelas «mágicas», pues desaparecen con el lavado, al ser solubles en agua. Es un tejido muy fino que se puede aplicar sobre telas delicadas o para realizar bordados. Se fija sobre la tela base, por el revés, y cuando hemos terminado la labor, se lava, desapareciendo por completo y dejando únicamente el tejido final.
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta6.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Papel o para bordados:] se utilizan como refuerzos en las labores de bordar, sirviendo de base para las mismas. Una vez se ha finalizado la labor, se retira fácilmente rasgando la entretela.
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta7.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Cinturilla y bordes:] ideales para realizar cinturillas, puños, bajos, solapas e incluso asas de bolsos. Tienen aspecto de cinta con pequeñas perforaciones lineales que sirven de guía. Son termoadhesivas. 
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta8.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Boatina:] es similar al plastrón. De trama de algodón o lana, o ambos, entrelazada de cabello de diferentes animales. También se emplea para plastrones. Al tener un tacto más suave, se coloca en la posición más cercana al cuerpo. 
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta9.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Percalina:] su composición es 100 % algodón y su principal función es endurecer. Las hay termofijables o de coser, de trama cerrada o trama abierta. Se emplean como entretela base para delantero y las diferentes piezas. 
      .col-lg-6.mb-4
        .tarjeta-avatar-b.h-100
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t2/tarjeta10.png' alt='')
          .tarjeta.color-acento-contenido
            .p-4
              p.mb-0 #[b Beta de algodón:] cinta de algodón termoadhesiva de un ancho de unos 3 a 5 mm, que se emplea en el canto de ciertas costuras que requieren refuerzo en el momento de la confección.
    
    p.mb-4(data-aos="fade") A continuación, se relacionan algunos consejos para el uso de entretelas: 

    ImagenInfografica.color-secundario.mb-5(data-aos="fade-down")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/t2/infografia.svg', alt='')
      .tarjeta.color-acento-botones.p-3(x="18.5%" y="23%" numero="")
        p.mb-0 #[b Tejidos ligeros:] entretelas no tejidas y finas, el adhesivo debe ser sin gránulos.
      .tarjeta.color-acento-botones.p-3(x="18.5%" y="48.6%" numero="")
        p.mb-0 #[b Tejidos gruesos:] grano grueso de adhesivo.
      .tarjeta.color-acento-botones.p-3(x="18.5%" y="75%" numero="")
        p.mb-0 #[b Tejidos de punto o elásticos:] entretelas de punto para que no pierdan elasticidad.
      .tarjeta.color-acento-botones.p-3(x="68%" y="18%" numero="")
        p.mb-0 #[b Tejidos no elásticos:] entretelas tejidas respetando la dirección del hilo de la pieza.      
      .tarjeta.color-acento-botones.p-3(x="73.5%" y="39%" numero="")
        p.mb-0 #[b Entretela tejida:] se encoge con los lavados; debido a esto, se aconseja que sean humedecidas, lavadas o planchadas con vapor antes de su aplicación.      
      .tarjeta.color-acento-botones.p-3(x="66%" y="62.5%" numero="")
        p.mb-0 #[b Entretela tradicional:] se corta del mismo tamaño que la pieza a entretelar; en el caso de la entretela termoadhesiva, se debe cortar entre 0,5 a 1 cm más pequeña.
        
    .row.align-items-center.mb-4
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t2/icono.svg', alt='')
      .col-10.col-md-11
        h4.mb-0 Preparación del cuello
    
    p.mb-4(data-aos="fade") El cuello es una de las piezas que necesita firmeza para conservar su estructura; por este motivo, requiere entretelarse. Este proceso también es el utilizado para bandas, solapas, perillas, charreteras, puños, pretinas y tapas de bolsillos que necesitan, igualmente, obtener mejor resistencia, tanto en cuerpo como en fricción. Después de cortar el molde del cuello en el textil correspondiente y en la entretela elegida, según el tipo de necesidad, se aplica una técnica de picado utilizada en la sastrería, que aporta un mejor comportamiento y funcionalidad para la prenda.  En la siguiente presentación interactiva se describen los pasos para la preparación del cuello.

    .tarjeta.fondo-slyder.p-4.mb-5(data-aos="fade-down")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se deben ubicar los moldes sobre la tela para recortar dos piezas de cuello y dos piezas de banda.
            p Se continúa con la ubicación de los moldes sobre la entretela, para recortar dos piezas de cuello y dos piezas de banda. 
            p Para cada uno de los cortes se debe incluir un centímetro para realizar la costura.   
          .col-md-6
            img(src='@/assets/curso/temas/t2/imag14.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se une con hilván recto a un centímetro del borde, es decir, un cuello en tela con un cuello en entretela.
            p Este procedimiento se debe realizar con las demás piezas.  
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag15.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se unen con hilván flojo ambos cuellos enfrentados derecho con derecho de la tela.
            p Se deja sin costura la base por donde irá la banda. 
            p Antes de coser a máquina, se humedecen las costuras recién hechas y se planchan para evitar imperfecciones. 
            p Se da la vuelta al cuello y se hilvana la base del cuello que queda abierta, se humedece y se plancha nuevamente. 
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag16.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se sostiene con hilván recto la cara externa de la banda, por la base del cuello, partiendo de la mitad de ambas piezas. 
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag17.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se hilvana la otra cara de la banda quedando el cuello en el centro de las bandas.
            p Posterior se cose tomando como guía la costura manual.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag18.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se retiran los hilvanes dando vuelta a las bandas mostrando el lado derecho de las piezas.  
            p Se pasa un hilván suelto alrededor de la banda para sostener mientras se realiza el planchado.  
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag19.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se hilvana el escote a un centímetro del borde, para realizar un pequeño doblez en la base de la banda con puntada de hilván, humedeciendo y planchando. 
            p Se une de forma manual la banda a la prenda que ya está armada con frentes, espalda y cartera por el lado externo de la prenda. 
            p En esta acción se deben tomar como guía las costuras de la banda y la del escote. 
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag20.png', alt='')
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            p Se hilvana la parte interna de la banda con la parte interna de frente y espalda. 
            p Se finaliza planchando con un paño humedecido.  
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t2/imag21.png', alt='')

    p.mb-4(data-aos="fade") A continuación, se presenta el proceso para picar piezas como el cuello.  
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-8
        SlyderF.t-23.mb-5(columnas="col-lg-4" data-aos="fade-down")
          .tarjeta.bg-white.separacion.p-3
            img.mb-4(src='@/assets/curso/temas/t2/imag22.png' alt='')
            p Marcar en forma de flecha hacia el centro del cuello con puntadas irregulares.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3
            img.mb-4(src='@/assets/curso/temas/t2/imag23.png' alt='')
            p.mb-4 Comenzar a picar en la nueva marca hacia la parte de debajo de la pieza.
            p Intentar formar espigas con las puntadas.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3
            img.mb-4(src='@/assets/curso/temas/t2/imag24.png' alt='')
            p.mb-4 Avanzar hasta completar el nuevo cuello, para marcar sin sobrepasar el borde de un centímetro que debe quedar libre de costura.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag25.png' alt='')
            p.mb-4 Hacer espigas con mucho cuidado en las puntas de la pieza, sin sobrepasar el centímetro que se debe dejar libre. Se termina de picar con las puntadas el resto del cuello.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3
            img.mb-4(src='@/assets/curso/temas/t2/imag26.png' alt='')
            p.mb-4 Humedecer la pieza y asentar con la plancha el cuello, del lado de la entretela, sin estirar. De esta forma quedará totalmente plana.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag27.png' alt='')
            p.mb-4 Apreciar el cuello en su totalidad.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag28.png' alt='')
            p.mb-4 Humedecer y estirar con la plancha suavemente.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag29.png' alt='')
            p.mb-4 Planchar girando levemente la totalidad del ancho del cuello.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag30.png' alt='')
            p.mb-4 Recortar un centímetro de entretela en toda la longitud de la pieza como se presenta en la imagen.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
          .tarjeta.bg-white.separacion.p-3        
            img.mb-4(src='@/assets/curso/temas/t2/imag31.png' alt='')
            p.mb-4 Doblar el centímetro de la tela para sostenerlo con costuras manuales de hilván y punto atrás en todo el recorrido. Finalizar con el planchado.
            img.w-105(src='@/assets/curso/temas/t2/icono2.svg' alt='')
      


</template>

<script>
export default {
  name: 'Tema2',
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
