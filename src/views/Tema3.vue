<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Proceso de levantamiento y construcción de básicos superiores femenino con técnica de sastrería
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-9
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t3/imag01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 En el proceso de levantamiento de patrones, generalmente se parte de una base que se ajusta con las medidas del cliente. Cada detalle juega un papel importante en la horma y la parte interna de la prenda no es la excepción, así que es cuidadosamente construida para crear una estructura, caída y encaje perfectos.
    
    
    Separador
    #t_3_1.titulo-segundo.color-primario(data-aos="fade-right")
      h2 3.1 Manga básico de la manga sastre
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-4.mb-4
        p Para hacer el desarrollo de una manga sastre, se debe tener en cuenta la posición anatómica del brazo y cuál es el objetivo principal de la manga.
        .titulo-sexto.color-secundario.mb-2
          h5 Figura 29.
          span Trazo de la manga sin inclinación
        img(src="@/assets/curso/temas/t3/imag02.png" alt="En la figura se presenta dibujo de modelo con tela sobrepuesta que indica el trazo de manga convencional sin inclinación del brazo, así como el respectivo molde.")
        figcaption Nota. Tomada de SENA (2021). 
      .col-lg-8.mb-4
        p Cuando se habla de prendas sastre, son todas aquellas que permiten o fortalecen una buena postura sobre el cuerpo, en este caso, la manga sastre lleva la inclinación anatómica del brazo, es decir, desde el plano se genera una serie de pinzas que permiten tener en la prenda o en la manga la forma anatómica del cuerpo. 
        .titulo-sexto.color-secundario.mb-2
          h5 Figura 30.
          span Trazo de la manga con inclinación
        .row
          .col-lg-6.mb-3.mb-lg-0
            img(src="@/assets/curso/temas/t3/imag03.png" alt="En la figura se presenta el mismo dibujo de la figura anterior pero esta vez con tela sobrepuesta para indicar trazo de manga con inclinación anatómica del brazo  y el molde en la respectiva tela con indicación de la pinza y la bajera. ")
            figcaption Nota. Tomada de SENA (2021). 
          .col-lg-6
            p Conocer el trazo de las mangas es muy importante para el proceso de un sastre. A continuación, se puede identificar que, sin importar el tipo de trazo, explicación o metodología, la funcionalidad y el objetivo principal de la pieza, en este caso la manga sastre, deben apuntar a lo mismo: cubrir el brazo dando la forma anatómica del cuerpo.

    .row.fondo-cta3.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .col-8.col-sm-6.col-md-4.mb-4.mb-md-0.d-none.d-lg-flex
            img(src="@/assets/curso/temas/t3/imag04.png")
          .col-11.col-lg-6
            ul.lista-ul--color.color-white.fa-ul.mb-0
              li.mb-0
                i.fas.fa-circle
                | #[h4 PDF – Manual de patronaje básico e interpretación de diseños]   
            p.mb-4 Conozca las formas o explicaciones metodológicas para trazar una manga sastre. Es importante tener en cuenta que cualquiera de los pasos o métodos aplicados llevan al mismo punto, en este caso, una manga sastre funcional. #[b Ver p. 27.]
            ul.lista-ul--color.color-white.fa-ul.mb-0
              li.mb-0
                i.fas.fa-circle
                | #[h4 PDF – Manual de patronaje básico e interpretación de diseños]   
            p.mb-4 Conoce el trazo de una manga sastre con una explicación diferente o con unos pasos diferentes a los anteriores. Se debe tener en cuenta que el resultado, sin importar los pasos o la técnica que se utilice, al final va a ser el mismo, la única diferencia son las variaciones en los cortes que corresponden al diseño. #[b Ver p. 44.]
            ul.lista-ul--color.color-white.fa-ul.mb-0
              li.mb-0
                i.fas.fa-circle
                | #[h4 PDF – Manual de patronaje básico e interpretación de diseños]   
            p.mb-4 Conoce otro tipo de trazo para el desarrollo de una manga sastre. Es importante mencionar que en todas se identifica una hoja ancha y una hoja angosta, que corresponden a simera y bajera. #[b Ver p. 46.]
            ul.lista-ul--color.color-white.fa-ul.mb-0
              li.mb-0
                i.fas.fa-circle
                | #[h4 PDF – Manual de patronaje básico e interpretación de diseños]   
            p.mb-4 Identifica tipos de trazo para hacer el desarrollo de una manga. #[b Ver p. 74, 77.]
            a.boton.color-acento-botones(:href="('https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=CFE7A758461AB5A9DC7AF8DE14F9412D?sequence=1')" target="_blank")
              span Descargar
              i.fas.fa-file-download  


    Separador
    #t_3_2.titulo-segundo.color-primario(data-aos="fade-right")
      h2 3.2 Molde base superior sastre femenino
    
    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4(data-aos="fade-right")
        p En el desarrollo de prendas femeninas, se identifica gran variedad de productos. A nivel comercial, existen diversos nombres para referirse a las prendas. Desde el punto de vista funcional, las características principales de una prenda sastre femenina corresponden al aplome, forma y ajuste sobre el cuerpo. Sin embargo, existen diversos tipos de prendas, con gran variedad de largos, variación en cuellos, escotes, bolsillos, mangas, que reciben el nombre o se categorizan como prendas sastre.
        p En esta ocasión se va a hacer el análisis de una chaqueta sastre clásica femenina sobre una imagen. No quiere decir que este diseño o tipo de prenda sea el único que existe o el que oficialmente se trabaja como sastrería. Se tomará únicamente como un referente visual para contextualizar y hacer el desarrollo de patronaje con las características mínimas que debe tener una prenda sastre superior.  
      .col-lg-4.mb-4.d-none.d-lg-flex(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/imag05.png', alt='')
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-6.col-10.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t3/imag06.png', alt='')
      .col-lg-8.mb-4(data-aos="fade-left")
        .cajon.color-primario.bg5.p-4.mb-4
          p.mb-0 #[b Para el desarrollo de sastrería femenina, a diferencia de la sastrería masculina, no se tiene una base o un básico específico, se trabaja sobre el mismo básico superior industrial desarrollado en ocasiones anteriores.]
        p Con el fin de tener referencias visuales y profundizar cada vez más en la interpretación de prendas, se irá asignando una serie de imágenes para hacer el desarrollo del patrón y el análisis de proporciones bajo requerimiento real de un cliente.  
        p Las proporciones son medidas que se obtienen de una imagen, muestra física, ficha técnica, dibujo plano o diseño que, al hacer un paralelo con los básicos o moldes bases de la línea, silueta o talla que se esté trabajando, permiten obtener medidas o dimensiones de referencia para el desarrollo o trazo del molde correspondiente al diseño. Si bien en ocasiones anteriores se han desarrollado ejercicios sobre análisis de proporciones, es importante resaltar que las medidas y el análisis de proporciones varía de acuerdo con  tamaño, diseño, impresión, dibujo, básico y sistema de medida. Las referencias implementadas son solo ejemplos detallados de cómo y de qué manera se debe implementar el desarrollo.
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        p.mb-4 La finalidad del ejercicio es poder aplicar todo el conocimiento y manejo de conceptos adquirido hasta el momento, llevando la implementación de los básicos hacia diferentes tipos de prendas y líneas de producto.
        .bloque-texto-g.color-primario.p-3.p-sm-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/t3/imag07.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Es importante tener en cuenta que, con el fin de adquirir cada vez más destreza y fortaleza en patronaje, lo ideal es poder cortar, pegar, trasladar y experimentar desde su proceso de aprendizaje. Cuando se empieza a trabajar el trazo de prendas desde los básicos, estos siempre deben ir alineados o aplomados sobre una línea base de construcción; en prendas superiores, la línea de aplome o línea base será la línea de profundidad de sisa.
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade")
      h5 Video 6. 
      span Trazo de chaqueta tipo sastre
    
    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-8.col-md-4.col-lg-3.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t3/slider.svg")
            .col-md.col-lg-6
              h4 Video - Trazo de chaqueta tipo sastre  
              p.mb-4 Conozca los trazos de la chaqueta sastre femenina
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=ZGgZuhG8L2s')" target="_blank")
                span Consultar video
                i.fas.fa-video

    figcaption.mb-5(data-aos="fade") Nota. Tomado de SENA (2021c).

    p.mb-4(data-aos="fade") Se debe tener en cuenta que las medidas implementadas o referenciadas en los videos son solo ejemplos y guías. Cada plano o cada uno tendrá referencias diferentes; esto depende del tipo de trazo, elementos o incluso el tipo de lápiz que se trabaje; #[b lo importante es siempre referenciar las medidas de aproximación del cliente con respecto al cuadro de tallas] o las medidas directamente del cliente y las fórmulas referenciadas.
    
    .row.fondo-t1.align-items-center.py-4.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center

          .row.align-items-center.mb-4(data-aos="fade-right")
            .col-2.col-md-1.w-60
              img(src='@/assets/curso/temas/t3/icono.svg', alt='')
            .col-10.col-md-10
              h4.mb-0 Trazo manga chaqueta sastre femenina: 
          
          .row.justify-content-center.mb-5(data-aos="fade-down")
            .col-lg-4.col-md-12.mb-4
              p Para este tipo de trazo, se deben tener en cuenta las características de forma, no solamente de la manga, sino del comportamiento o diseño. En este caso, que se está trabajando sobre una imagen en la cual se identifican características específicas, como cortes, caja y botonadura, es importante mencionar que no solamente se trabajan estas piezas externas, sino que, para hacer el desarrollo desde patronaje y pasar al proceso de confección o ensamble, se desarrollan piezas internas como borra flojos, refuerzos, entretelas, falsos y forros.
            .col-lg-4.col-md-10.mb-4
              .titulo-sexto.color-acento-contenido.mb-2
                h5 Figura 31. 
                span Traje sastre femenino
              img(src="@/assets/curso/temas/t3/imag08.png" alt="En la imagen se presenta fotografía de modelo con estilo sastre femenino de color negro.")
              figcaption Nota. Tomada de Luis (2017).
            .col-lg-4.col-md-12.mb-4
              p En este punto, se tienen claras las generalidades para el desarrollo o trazo de una manga sastre. Sin embargo, hace falta fortalecer las piezas internas para la elaboración o el desarrollo de esta. Una de las piezas más características dentro de la manga sastre es el borra flojo que, como su nombre lo indica, es una pieza interna que en el proceso de confección facilita o permite borrar el flojo que se genera entre el recorrido de la cabeza de manga y la sisa de la prenda. Esta pieza se traza de diferentes maneras; en este caso, se explican las dos más comunes a nivel general.
          
          .row.justify-content-center(data-aos="fade-down")
            .col-lg-10
              .tarjeta.bg-white.py-4
                .row.justify-content-center
                  .col-md-6.col-lg-5.mb-3
                    .titulo-sexto.color-acento-contenido.mb-2
                      h5 Figura 32.  
                      span Borra flojo paso 1
                    img(src="@/assets/curso/temas/t3/imag09.png" alt="En la figura se detalla en un molde de una manga de sastre el trazado de una pieza denominada borra flojo la cual tiene una forma curva y va en el borde de la cimera.")
                    figcaption.mb-4 Nota. Tomada de SENA (2021).
                  .col-md-6.col-lg-5.mb-3
                    .titulo-sexto.color-acento-contenido.mb-2
                      h5 Figura 33. 
                      span Borra flojo paso 2
                    img(src="@/assets/curso/temas/t3/imag11.png" alt="Al igual que en la figura anterior se detalla en un molde de una manga de sastre el trazado de una pieza denominada borra flojo la cual tiene una forma recta en sentido horizontal y va separada de la cimera.")
                    figcaption.mb-4 Nota. Tomada de SENA (2021).
                .row.justify-content-center
                  .col-md-6.col-lg-5.mb-3
                    .titulo-sexto.color-acento-contenido.mb-2
                      h5 Figura 34. 
                      span Refuerzo sastre 
                    img(src="@/assets/curso/temas/t3/imag10.png" alt="En la figura se presenta una foto de una prenda que tiene un refuerzo de sastre  en el hombro derecho.")
                    figcaption.mb-4 Nota. Tomada de Pinterest (2021).
                  .col-md-6.col-lg-5.mb-3
                    .titulo-sexto.color-acento-contenido.mb-2
                      h5 Figura 35. 
                      span Hombrera sastre 
                    img(src="@/assets/curso/temas/t3/imag12.png" alt="En la figura se presenta el refuerzo sastre en una hombrera,  con entretela.")
                    figcaption.mb-4 Nota. Tomada de Pinterest (2021).
    
    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-10
        p Para el trazo o desarrollo de la manga, se deben tener en cuenta el análisis de proporciones y el trazo de la interpretación de chaqueta sastre femenina.
    
    .titulo-sexto.color-primario(data-aos="fade")
      h5 Video 7.
      span Trazo manga chaqueta sastre femenina 
    
    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-5.col-md-3.col-lg-2.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t3/slider2.svg")
            .col-md.col-lg-6
              h4 Video - Trazo manga chaqueta sastre femenina 
              p.mb-4 Conozca el paso a paso para realizar la manga sastre de chaqueta femenina.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=nf2vjjxt55Y&t=40s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA')" target="_blank")
                span Consultar video
                i.fas.fa-video

    figcaption.mb-5(data-aos="fade") Nota. Tomado de SENA (2020l)

    .row.align-items-center.mb-4(data-aos="fade-right")
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t3/icono2.svg', alt='')
      .col-10.col-md-10
        h4.mb-0 Despiece chaqueta sastre femenina: 
    
    p.mb-4(data-aos="fade") Al momento de despiezar una chaqueta sastre se deben tener en cuenta diferentes características, como qué tipo de acabado va a tener internamente, debido a que en algunos países, por la temporada o la estación, se le asignan diferentes acabados internos, los cuales van de la mano con el desarrollo de patronaje. En este caso, se va a hacer el despiece de una chaqueta sastre completamente forrada. Es importante aclarar que existen diferentes formas de hacer los acabados internos o refuerzos que va a llevar la chaqueta.
    
    .row.justify-content-center.mb-5
      .col-lg-5.col-md-6.mb-4(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 36. 
          span Despiece chaqueta paso 1
        img(src="@/assets/curso/temas/t3/imag13.png" alt="En la imagen se presenta el patrón del despiece de la chaqueta. (Paso 1).")
        figcaption Nota. Tomada de Pinterest (2021).
      .col-lg-5.col-md-6.mb-4(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 37. 
          span Despiece chaqueta paso 2
        img(src="@/assets/curso/temas/t3/imag14.png" alt="En la imagen se presenta el patrón del despiece de la chaqueta. (Paso 2).")
        figcaption Nota. Tomada de Pinterest (2021).
    
    p.mb-4(data-aos="fade") Para el desarrollo de los moldes de refuerzos, entretelas y forros, al igual que en las mangas, son elementos que no se identifican en la parte externa de la prenda, es decir, no se ven a través de una imagen, dibujo plano, incluso muestra físicas; sin embargo, son piezas que definitivamente complementan el desarrollo de la prenda.
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-7.mb-4(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 38. 
          span Entretelas
        img(src='@/assets/curso/temas/t3/imag15.png', alt='En la figura se presenta foto de prenda sobre maniquí en el que se resalta el refuerzo con entretelas en hombros y cuello.')
        figcaption Nota. Tomada de Pinterest (2021).
      .col-lg-8.mb-4(data-aos="fade-left")
        .cajon.color-primario.bg5.p-4.mb-4
          p.mb-0 #[b Para el trazo o desarrollo del despiece de la chaqueta sastre, es necesario tener en cuenta el trazo de la interpretación de chaqueta y manga sastre femenina.]
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Video 8. 
          span Despiece chaqueta sastre femenina
        .fondo-cta32.p-4
          .row.justify-content-evenly.align-items-center
            .col-7.col-md-4.col-lg-3.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t3/slider3.svg")
            .col-md.col-lg-7
              h4 Video - Despiece chaqueta sastre femenina  
              p.mb-4 Conozca el trazo o desarrollo del despiece de la chaqueta sastre. Es necesario tener en cuenta el trazo de la interpretación de chaqueta y manga sastre femenina.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=ZpaVPWnxItE&t=501s')" target="_blank")
                span Consultar video
                i.fas.fa-video
        figcaption.mb-5(data-aos="fade") Nota. Tomado de SENA (2021c).
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-8.col-md-10
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 39. 
          span Cuello alto
        img(src="@/assets/curso/temas/t3/imag16.png" alt="En la figura se detallan los trazos para cuello alto en chaqueta de frente y de espaldas, señalando las líneas para cuello alto con pinza y manga tipo sastre con pinza.")
        figcaption Nota. Tomada de SENA (2021).
    
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade")
      h5 Video 9. 
      span Chaqueta cuello alto traslados de pinza
    
    .row.fondo-cta.align-items-center.py-4(data-aos="fade")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-evenly.align-items-center
            .col-7.col-md-4.col-lg-3.mb-4.mb-md-0
              img(src="@/assets/curso/temas/t3/slider4.svg")
            .col-md.col-lg-6
              h4 Video - Chaqueta cuello alto  
              p.mb-4 Conozca el trazo de la chaqueta de cuello alto a partir de los traslados de pinza.
              a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?app=desktop&v=yKwVapWExPo&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA')" target="_blank")
                span Consultar video
                i.fas.fa-video

    figcaption(data-aos="fade") Nota. Tomado de SENA (2020f).


    Separador
    #t_3_3.titulo-segundo.color-primario(data-aos="fade-right")
      h2 3.3 Procedimiento manual del sastre
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-2.col-md-5.col-8.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/temas/t3/imag17.svg', alt='')
      .col-lg-10.mb-4(data-aos="fade-left")
        p La sastrería a medida es el método tradicional de confección, que consiste en disponer distintas capas de refuerzo y estructura, entretelas y forro. Estas telas van cosidas y trabajadas con vapor para dar forma y estabilidad a la prenda (no se utilizan nunca entretelas adhesivas). Para lograr un ajuste perfecto y evitar luego cambios importantes en el patrón, se confecciona primero una prenda de prueba, generalmente de percal o de algodón. Tradicionalmente, las prendas sastre a medida se ajustan cómodamente al cuerpo y permiten libertad de movimiento

    .row.align-items-center.mb-4(data-aos="fade-right")
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t2/icono.svg', alt='')
      .col-10.col-md-10
        h4.mb-0 Elección de las telas
    
    p.mb-4(data-aos="fade") El montado de prendas en la sastrería clásica requiere en su proceso de diferentes tipos de entretela según la prenda en la que se está trabajando; también necesita de guatas y forros, que son elegidos según la tela del diseño. Un tejido grueso necesita entretelas más gruesas que un tejido fino, aunque las técnicas utilizadas en la confección de la prenda sean las mismas.

    .row.justify-content-center.mb-5
      .col-lg-5.col-md-6.mb-4(data-aos="fade-right")
        .bg7.h-100.br-tl.br-tr
          .p-4.pb-0
            p.mb-4 #[b Tejidos gruesos:] acá se presentan unos ejemplos. Estos tejidos se deben combinar con diferentes tipos de entretelas según la ubicación y la construcción que se busca.
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 40. 
              span Tejidos gruesos
            img(src="@/assets/curso/temas/t3/imag18.png" alt="En la figura se incluyen cuatro muestras de entretelas con tejidos gruesos. (Duplos de seda, guateado de muselina, entretela de cañamazo fino, forro de seda habutai)")
        figcaption Nota. Tomada de Kinderley (2005).
      .col-lg-5.col-md-6.mb-4(data-aos="fade-left")
        .bg7.h-100.br-tl.br-tr
          .p-4.pb-0
            p.mb-4 #[b Tejidos finos:] la seda y el lino también son utilizados para trajes sastre; se debe elegir un grosor que dé estructura. Para guatear se utilizan materiales como la muselina, y para entretelas lo mejor es el cañamazo fino.
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 41. 
              span Tejidos finos
            img(src="@/assets/curso/temas/t3/imag19.png" alt="En la figura se incluyen cuatro muestras de entretelas tejidos finos (lana 100%, entretela de domeñe, entretela de cañamazo intermedio y forro de cuero rayón)")
        figcaption Nota. Tomada de Kinderley (2005).
    
    .row.align-items-center.mb-4(data-aos="fade-right")
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t2/icono.svg', alt='')
      .col-10.col-md-10
        h4.mb-0 Análisis del modelo a realizar
    
    p.mb-4(data-aos="fade") La prenda sastre se forra según un patrón preciso. Para ello, es necesario ajustar al contorno del cuerpo y al mismo tiempo resultar cómoda y permitir una buena movilidad. Como dato importante, en la sastrería, la chaqueta siempre lleva forro para proteger el entretelado.
    
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-primario
          h5 Tabla 6.
          span El traje femenino
        .tabla-b.color-acento-contenido.borde-top-table
          .tabla-b__header
            h4.mb-0 Análisis del traje sastre femenino
          table
            caption Nota. Tomada de SENA (2021).
            tr.bg-white
              td.col-40(rowspan="11")
                .titulo-sexto.color-primario
                  h5 Figura 42.
                  span Partes del traje sastre falda
                figure
                  img(src="@/assets/curso/temas/t3/imag20.png" alt="En la imagen se incluye fotografía de modelo con traje sastre falda, en la que se detallan cada una de sus partes así: Costura de cuello, Abertura de bocamanga, bolsillo ribeteado, forro de la chaqueta, hombreras, corona de la manga, manga encajada, pasador de cinturón, largo de la chaqueta, el bajo de la falda.")
                  figcaption Nota. Tomada de Kinderley (2005).
              td #[b Costura del cuello:] une el cuello con la solapa.  
            tr
              td #[b Ojales ribeteados:] son terminados a mano por el derecho de la prenda sastre. Los botones se cosen con el cuello ya armado.
            tr.bg-white
              td #[b Abertura de la bocamanga:] se hace una abertura. Estos botones no están hechos para desabrocharlos.
            tr
              td #[b Bolsillo ribeteado:] queda pegado a la tela y no interfiere con la línea de la prenda.  
            tr.bg-white
              td #[b Forro de la chaqueta:] refuerza, arma a la prenda y oculta la construcción interna.
            tr
              td #[b Hombreras:] se utilizan para armar y dar firmeza a los hombros de una chaqueta.
            tr.bg-white
              td #[b Corona de la manga:] se añade a la manga después de ser cosida, esta ayuda a sostener y levantar la copa de la manga.
            tr
              td #[b Manga encajada:] embeber, hilvanar y coser.
            tr.bg-white
              td #[b Pasador de cinturón:]  si lleva correa.
            tr
              td #[b Largo de la chaqueta:] un modelo clásico llega por debajo de la altura de cadera.
            tr.bg-white
              td #[b El bajo de la falda:] debe quedar más largo que el del forro y debe estar suelto para que caiga mejor y evitar que tire.
    
    p.mb-4(data-aos="fade") A continuación, se presenta un ejemplo para la elaboración del toile.

    SlyderF.t33.mb-5(columnas="col-lg-4" data-aos="fade-down")
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Cortar todos los patrones en el textil de prueba, respetando las reglas de trazo y corte.        
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta2.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Por el revés de las piezas cortadas, se deben transferir las marcas interiores del patrón con papel carbón o con hilvanes. Se marcan las líneas de costura y los piquetes.    
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta3.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Calcar las marcas exteriores sobre el derecho de la tela. Marcar el hilo y el contrahílo, el centro del delantero, la línea de cintura, la posición de bolsillos y botonadura. Retirar el papel carbón del percal.     
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta4.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Hilvanar las piezas por los piquetes o marcas dibujadas. Unir con hilvanes las piezas de las mangas. Planchar las costuras aplastadas y luego las abiertas.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta5.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Pasar las dos filas de puntadas de frunces de la manga. Se debe fijar con los alfileres a la sisa y así poder repartir de una forma homogénea la tela de la copa. Cuando se haga la distribución del frunce se hilvana cada manga en su sisa.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta6.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Unir con hilván las piezas del cuello y la espalda por el centro de ambas. Se une la parte inferior del cuello con el escote, haciendo coincidir las líneas de costura y montando los bordes. Se prende e hilvana siguiendo el escote.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta7.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p Por el derecho de la prenda, se marcan con la plancha el margen de costura entre el piquete del cuello y de la solapa. 
            p.mb-0 Se repite el proceso por el revés de la prenda y se planchan las costuras aplastadas.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta8.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p Doblar hacia arriba la solapa y verificar el ruedo de las mangas. Prender las hombreras en su sitio y los delanteros por las marcas de la botonadura.
            p.mb-0 Comprobar que las líneas de hilo y de contrahílo estén bien alineadas.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/t3/tarjeta9.png' alt='')
        .tarjeta.color-acento-contenido
          .p-4
            p.mb-0 Para finalizar, se verifica el calce en la persona o maniquí, marcando las líneas de ajuste, si son necesarias. 
    
    p.mb-4(data-aos="fade") A continuación, se presenta un ejemplo para el análisis de la prueba de calce.

    .tarjeta.bg8.p-4.mb-5
      LineaTiempoC.color-acento-botones
        .row.justify-content-center(titulo="1")
          .col-md-8.col-lg-3.mb-4.mb-lg-0
            img(src='@/assets/curso/temas/t3/imag21.png', alt='')
          .col-md-12.col-lg-6
            p Comprobar cómo asienta la costura delantera, verificando que ambos hombros estén alineados, al igual que las pinzas hacia el punto de pivote.        
        .row.justify-content-center(titulo="2")
          .col-md-7.col-lg-3.mb-4.mb-lg-0
            img(src='@/assets/curso/temas/t3/imag22.png', alt='')
          .col-md-12.col-lg-6
            h4 Rectificar el pratrón
            p Se comprueba cómo asienta la espalda y se presenta la holgura entre hombros y la parte de la espalda al mover los brazos. Se verifica la comodidad para la zona de cintura y las caderas, al sentarse. Además se observa la forma del cuerpo y el encajado con el escote. A continuación, se observan diferentes problemas, sus causas y la forma adecuada de corregirlos.         
        .row.justify-content-center(titulo="3")
          .row.justify-content-center
            h4.text-center Corregir problemas de espalda en prototipo
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag23.png")
              p #[b Problema:] espalda que tira y se mueven los hombros, lo que generan arrugas desde la parte alta hacia las sisas. El ruedo de la espalda se ondula hacia arriba.
              p #[b Causa:] espalda corta.        
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag24.png")
              p #[b Solución:] hacer un corte horizontal por la espalda alta donde inicie la zona problemática en arrugas. Dentro del corte, introducir una pieza cortada en percal, dacrón o liencillo, ir bajando lentamente el corte de la espalda que contiene el ruedo hasta que desaparezcan las arrugas y el ruedo caiga recto.       
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag25.png")
              p #[b Modificación en el patrón:] se copia la nueva espalda con el ajuste y se coloca la sisa del antiguo patrón para que no sea necesario ajustar el perímetro de la manga.        
        .row.justify-content-center(titulo="4")
          .row.justify-content-center
            h4.text-center Corregir problemas de espalda en prototipo
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag26.png")
              p #[b Problema:] una espalda con arruga horizontal similar a un pequeño globo, arrugas que bajan desde los hombros y el ruedo pueden ondularse.
              p #[b Causa:] espalda larga.        
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag27.png")
              p #[b Solución:] ir recogiendo el exceso de tela y fijarlo con alfileres o bastas iniciando siempre desde el centro hacia las sisas. Tener presente que las sisas no se deben modificar.       
            .col-lg-4.col-md-6
              img.mb-4(src="@/assets/curso/temas/t3/imag28.png")
              p #[b Modificación en el patrón:] medir los centímetros recogidos en el centro de la espalda y dibujarlo en dos líneas para generar una pinza de corrección horizontal.  Se debe tener en cuenta que la sisa no se debe modificar.        
        .row.justify-content-center(titulo="5")
          .row.justify-content-center
            h4.text-center Rectificar la espalda estrecha en prototipo
            .col-lg-4.col-md-11
              img.mb-3(src="@/assets/curso/temas/t3/imag29.png")
              p #[b Problema:] volumen horizontal en la espalda.
              p #[b Causa:] espalda estrecha.         
            .col-lg-8.col-md-11
              .row
                .col-md-6
                  img.mb-3(src="@/assets/curso/temas/t3/imag30.png")   
                .col-md-6       
                  img.mb-3(src="@/assets/curso/temas/t3/imag31.png")
              p #[b Solución:] descoser el centro de la espalda desde el escote hasta la cintura, para disminuir la bolsa que se presenta fijando de manera vertical la nueva línea de centro espalda hilvanada.
          h5.txt1 Si después de realizar el paso anterior la sisa se encuentra tirando, se debe descoser, prender con un alfiler la copa y, por fuera, ir repartiendo o moviendo desde el espacio del centímetro de costura hasta corregirla.
        .row.justify-content-center(titulo="6")
          .row.justify-content-center
            .col-lg-5.col-md-11
              img.mb-4(src="@/assets/curso/temas/t3/imag32.png")
            .col-lg-5.col-md-11
              img.mb-4(src="@/assets/curso/temas/t3/imag33.png")
            .col-lg-10
              p #[b Modificación en el patrón:] ubicar el papel calco bajo la espalda y trazar las nuevas líneas. Si se hizo reducción en el escote del centro espalda, se debe reducir la misma cantidad en la mitad del cuello; si fue aumento en la sisa de la espalda, se debe aumentar la misma cantidad en el perímetro de la manga.
    
    .row.align-items-center.mb-4(data-aos="fade-right")
      .col-2.col-md-1.w-60
        img(src='@/assets/curso/temas/t2/icono.svg', alt='')
      .col-10.col-md-10
        h4.mb-0 Proceso artesanal y técnico de un sastre
    
    p.mb-4(data-aos="fade") El patrón de la entretela se realiza utilizando el mismo de la pieza original. Para ello se debe tener en cuenta que no siempre toda la entretela quedará sujeta, en algunos modelos quedará sin costura en alguno de sus lados para facilitar el movimiento.
    
    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 7.
      span Corte de entretelas

    .tabla-b.color-acento-contenido.borde-top-table.table33
        .tabla-b__header
          span
        table
          tr
            td.col-33
              .titulo-sexto.color-acento-contenido.mb-2
                h5 Figura 43. 
                span Entretelado 1
              img.mb-4(src="@/assets/curso/temas/t3/imag34.png" alt="En la figura se presenta el patrón de la entretela indicando expresamente el corte y el proceso de entretelado.")
              p.mb-4 Se debe tomar como guía el patrón del frente, bajar 5 cm desde la sisa por el costado y realizar la forma pasando por la separación de busto hasta la cintura.
              figcaption Nota. Tomada de Kinderley (2005).
            td.col-33 
              .titulo-sexto.color-acento-contenido.mb-2
                h5 Figura 44. 
                span Entretelado 2
              img.mb-4(src="@/assets/curso/temas/t3/imag35.png" alt="Al igual que en al figura anterior se presenta el patrón de la entretela de una pieza indicando medidas precisas y línea de costura de la espalda, línea de costura de la sisa.")
              p.mb-4 En este paso, se debe bajar 5 cm por costado, partiendo de la sisa; por el centro espalda bajar 12.5 cm y unir los puntos con línea curveada, como presenta la figura. Además, se deben trasladar pinzas, costuras y piquetes a la entretela.
              figcaption Nota. Tomada de Kinderley (2005).
            td.col-33 
              .titulo-sexto.color-acento-contenido.mb-2
                h5 Figura 45. 
                span Entretelado 3
              img.mb-4(src="@/assets/curso/temas/t3/imag36.png" alt="Sobre un dibujo se indican y se señalan con puntos la manera exacta de hacer el entretelado en tejidos que ceden.")
              p.mb-4 Para los tejidos que ceden, esta sería la opción adecuada: marcar 5 cm bajando por el costado y, partiendo de la sisa, por el centro espalda, bajar 2.5 cm. Unir ambos puntos con curva y, al final, montar los bordes del centro y coser solo por la línea de costura.
              figcaption Nota. Tomada de Kinderley (2005).


    Separador
    #t_3_4.titulo-segundo.color-primario(data-aos="fade-right")
      h2 3.4 Molde base superior sastre femenino
    
    .row.justify-content-center.mb-4
      .col-lg-9.mb-4(data-aos="fade-right")
        p.mb-4 Las proporciones son medidas que se obtienen de una imagen, muestra física, ficha técnica, dibujo plano o diseño que, al hacer un paralelo con los básicos o moldes bases de la línea, silueta o talla que se esté trabajando, permiten obtener medidas o dimensiones de referencia para el desarrollo o trazo del molde correspondiente al diseño. Si bien en ocasiones anteriores se han desarrollado ejercicios sobre análisis de proporciones, es importante resaltar que las medidas y el análisis de proporciones varía de acuerdo con tamaño, diseño, impresión, dibujo, básico y sistema de medida. Las referencias implementadas son solo ejemplos detallados de cómo y de qué manera se debe implementar el desarrollo.
        .cajon.color-primario.bg5.p-4.mb-4
          p.mb-0 La finalidad del ejercicio es poder aplicar todo el conocimiento y manejo de conceptos adquirido hasta el momento, llevando la implementación de los básicos hacia diferentes tipos de prendas y líneas de producto. Es importante recordar que, con el fin de adquirir cada vez más destreza y fortaleza en patronaje, lo ideal es poder cortar, pegar, trasladar y experimentar desde su proceso de aprendizaje.
      .col-lg-3.col-md-6.col-8.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/imag37.png', alt='')   
    
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
      h5 Video 10.
      span Análisis e interpretación de capas
    
    p(data-aos="fade") Conozca sobre la interpretación de capas.
    
    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/N-2DugIICpw?si=CZDLU3lVzOJC31__" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Análisis e interpretación de capas 
    
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
      h5 Video 11.
      span Abrigo asimétrico
    
    p(data-aos="fade") Conozca la asimetría de los abrigos.

    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/aga8T_qGAFs?si=ZGDMpVCG0kR0_X7P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Abrigo asimétrico
    
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
      h5 Video 12.
      span Interpretación de pantalón sastre femenino.
    
    p(data-aos="fade") Conozca sobre la Interpretación de pantalón sastre femenino.

    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/VZZQsjRcc7k?si=CGvyh89LlYHDcyOz " title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Interpretación de pantalón sastre femenino.
    
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Video 13.
      span Análisis e interpretación de pantalón sudadera.
    
    p(data-aos="fade") Conozca el trazo del pantalón tipo sudadera.

    figure(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/8vgwqHz6Qio?si=CPmEnuti6kXLsRQ-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Análisis e interpretación de pantalón sudadera 

      
</template>

<script>
export default {
  name: 'Tema3',
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
