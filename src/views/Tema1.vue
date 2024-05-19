<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Escalado manual de prendas
    
    
    .titulo-segundo.pri.mb-4
      h2.pri \\\ Introducción y conceptualización - escalado

    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center
            .col-lg-7.col-md-12.col-12
              p.mt-4.negro ¿Qué es el escalado?
              p.mb-0 Es el método o técnica implementado para ampliar o reducir un patrón base, molde o trazo de una talla a otra proporcionalmente. Las proporciones se identifican de acuerdo con el cuadro de tallas o medidas estandarizadas, para llevar a cabo un escalado se implementan planos cartesianos que permiten identificar puntos de referencia, en las medidas de largos, anchos y contornos con sus proporciones que se diferencian entre una talla y otra.
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img1.svg', alt='tema1')
              
    .titulo-segundo.pri.mb-4
      h2.pri \\\ Plano cartesiano

    p.mb-4 Está formado por dos rectas perpendiculares, una horizontal y otra vertical que se entrecruzan en un punto.
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja3.p-4
          .row.justify-content-center
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img2.png', alt='tema1')
            .col-lg-7.col-md-12.col-12.my-5
              ul.lista-ul--color.f-1
                li.mb-4
                  i.fas.fa-circle
                  | #[b La recta horizontal, ] es llamada eje de las abscisas o de las equis #[b (X)]
                li.mb-4
                  i.fas.fa-circle
                  | #[b La recta vertical, ]  eje de las ordenadas o de las yes #[b (Y)]
                li.mb-4
                  i.fas.fa-circle 
                  | #[b El punto donde se cortan ] recibe el nombre de origen #[b (punto cero o punto muerto)]
    
    p.mb-5 #[b El plano cartesiano tiene como finalidad describir la posición de puntos,] los cuales se representan por sus coordenadas o pares ordenados. Para la implementación del plano cartesiano trabajaremos con el #[b sistema de medidas de mayor dominio.]  
    
    .row.justify-content-center.mb-5
      .col-lg-8.col-md-12.col-12
        .caja2.rad.p-4
          p.mb-0.text-center Sistema de medida universal: #[b metro - centímetro - milímetro]
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja4.p-4
          .row.justify-content-center
            .col-lg-3.col-md-8.col-8.my-5
              img.img-a.img-t.my-5.d-none.d-lg-block(src='@/assets/curso/tema1/img3.svg', alt='tema1')
            .col-lg-7.col-md-12.col-12
              p.mt-4.negro Ejemplo:
              p.mb-4 Si tomamos como punto de partida 
                strong el punto de origen 
                | al hablar de reducir o aumentar, podríamos acudir a los espacios negativos o positivos del plano cartesiano, según corresponda.
              .row.justify-content-center
                .col-lg-6.col-md-12.col-12.mb-4
                  .caja2.rad.p-4
                    p.mb-3.negro.text-center Aumenta
                      .cajablanca.radi.mb-4
                        p.mb-4.negro.text-center Ancho: 3 - Largo: 1
                      .cajablanca.radi.mb-4
                        p.mb-4.negro.text-center Ancho: 1 - Largo: 3
                .col-lg-6.col-md-12.col-12
                  .caja2.rad.p-4
                    p.mb-3.negro.text-center Reduce
                      .cajablanca.radi.mb-2
                        p.mb-4.negro.text-center Ancho: -3 - Largo: -1
                      .cajablanca.radi.mb-2
                        p.mb-4.negro.text-center.my-4 Ancho: -1 - Largo: -3
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center
          .col-lg-4.col-md-12.col-12.mb-4
            .caja31.p-3
              img.img-a.img-t(src='@/assets/curso/tema1/img4.svg', alt='tema1')
          .col-lg-4.col-md-12.col-12.mb-4
            .caja31.p-3
              img.img-a.img-t(src='@/assets/curso/tema1/img5.svg', alt='tema1')
          .col-lg-4.col-md-12.col-12.mb-4
            .caja31.p-3
              img.img-a.img-t(src='@/assets/curso/tema1/img6.svg', alt='tema1')

    p.mb-5 Para entender cómo funciona el escalado desde plano cartesiano, vamos a tomar como referencia un cuadrado, este cuadrado es el molde base o talla base a trabajar, para mayor comprensión de este cuadrado deben salir dos figuras más para un total de tres figuras, siendo este el punto intermedio.
    
    .row.justify-content-center.mb-5
      .col-lg-8.col-md-12.col-12
        .caja22.rad.p-4
          .row.justify-content-center
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color.f-1
                li.mb-0
                  i.fas.fa-circle
                  | La diferencia de #[b ancho] es 2 cm
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color.f-1
                li.mb-0
                  i.fas.fa-circle
                  | La diferencia de #[b alto] es 2 cm
    
    .row.mb-5.align-items-center.justify-content-center
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center
          .col-2
            .avatar
              img.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img7.svg")
          .col-lg-10.col-md-12.col-12.caj.p-3
            .row
              .col-1
              .col-10
                p.my-3 Se debe sacar un cuadrado más pequeño y un cuadrado más grande. Recuerde que todos los lados del cuadrado deben quedar iguales.
    
    .titulo-segundo.pri.mb-4
      h2.pri \\\ Análisis sobre plano cartesiano

    SlyderB.bg11.mb-5(:datos="datosSlyder")
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img8.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Análisis sobre plano cartesiano
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el análisis sobre plano cartesiano.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    .titulo-segundo.pri.mb-5
      h2.pri \\\ Conclusiones
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-8.col-md-12.col-12
            .cajon.color-primario.p-4.mb-4
              p.mb-0 El manejo del punto de origen - punto cero - punto muerto, es el primer acercamiento a la comprensión de trasladar, modificar, mover puntos de referencia o construcción.
            p.mb-4 El concepto de positivo o negativo sobre el plano depende del punto de origen; aplicar en escalado se refiere a cada vez que se trabaja una medida sobre el plano cartesiano:
            .row.justify-content-center.mb-0
              .col-lg-9.col-md-12.col-12
                .caja22.rad.p-4
                  .row.justify-content-center
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color.f-1
                        li.mb-0
                          i.fas.fa-circle
                          | #[b Negativa:] reducción
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color.f-1
                        li.mb-0
                          i.fas.fa-circle
                          | #[b Positiva:] aumento
          
          .col-lg-4.col-md-8.col-8
            img.img-a.img-t(src='@/assets/curso/tema1/img9.png', alt='tema1')

    .titulo-segundo.pri.mb-5
      h2.pri \\\ Proporciones
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja4.p-4
          .row.justify-content-center
            .col-lg-3.col-md-8.col-8.my-5
              img.img-a.img-t.my-5.d-none.d-lg-block(src='@/assets/curso/tema1/img3.svg', alt='tema1')
            .col-lg-7.col-md-12.col-12
              p.mt-4.negro Ejemplo:
              p.mb-4 Para identificar las proporciones a usar se debe trabajar con las siguientes medidas. En este caso el punto base o el punto de partida es el mediano, la diferencia entre medida y medida es: 
                strong 2cm para aumentar y -2cm para reducir.
              p.mb-4 Para aplicar el escalado se trabaja con las proporciones, no con la diferencia.
              .row.justify-content-center
                .col-lg-10.col-md-12.col-12.mb-4
                  img.img-a.img-t(src='@/assets/curso/tema1/img10.jpg', alt='tema1')

    .titulo-segundo.pri.mb-4
      h2.pri \\\ Cómo identificar las proporciones                

    p.mb-5 Si la diferencia entre una medida y otra es de 2cm. La proporción equivale a #[b la manera en la que se aplica en el plano,] es decir:
    
    .row.justify-content-center.mb-5
      .col-lg-9.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-4.col-md-12.col-12
            img.img-a.img-t(src='@/assets/curso/tema1/img11.png', alt='tema1')
          .col-lg-8.col-md-12.col-12
            .caja5.p-5
              ul.lista-ul--color.f-1
                li.mb-4
                  i.fas.fa-circle
                  | #[b Si sobre el plano se aplica la medida completa,] dicha medida equivale a una proporción, entonces una proporción será 2cm.
                li.mb-0
                  i.fas.fa-circle
                  | #[b Si sobre el plano se aplica la mitad de la medida, ]  esto equivale a 1/2 proporción, 1/2 proporción será 1 cm.
    
    TabsC.color-primario.mb-5(data-aos="zoom-in-left")
      .py-3.py-md-4.bg26.px-3(titulo="Plano completo")
        .row.justify-content-center
          .col-lg-5.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/tema1/img41.svg', alt='')
          .col-lg-7.col-md-12.my-3
            p En este caso se aplica una proporción porque en el plano se está trabajando la medida total.
      .py-3.py-md-4.bg26.px-3(titulo="Plano por mitad")
        .row.justify-content-center
          .col-lg-5.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/tema1/img42.svg', alt='')
          .col-lg-7.col-md-12.my-3
            p En este caso en el ancho se debe aplicar 1/2 proporción, porque en el plano se está trabajando la mitad de la medida total.
          
    
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center
            .col-lg-6.col-md-12.col-12
              p.mt-4.negro Ejercicio de análisis 
              p.mb-4 Realice el #[b escalado de la siguiente figura] teniendo en cuenta:
              ul.lista-ul--color.f-1
                li.mb-1
                  i.fas.fa-circle
                  | El cuadro de tallas asignado
                li.mb-1
                  i.fas.fa-circle
                  | Las diferencias entre talla y talla
                li.mb-1
                  i.fas.fa-circle
                  | La talla base y las medidas
                li.mb-1
                  i.fas.fa-circle
                  | La asignación de proporciones, según tipo de plano a trabajar
                li.mb-1
                  i.fas.fa-circle
                  | El punto de origen sobre el plano cartesiano y la ubicación de la figura
            .col-lg-5.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img12.svg', alt='tema1')
    
    
    .row.justify-content-center.mb-5
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.mb-0
          .col-lg-5.col-md-12.col-12
            .caja5.p-4.mb-4
              ul.lista-ul--color.f-2
                li.mb-0
                  i.fas.fa-square
                  | El cuadro de tallas asignado
                li.mb-0
                  i.fas.fa-square
                  | Las diferencias entre talla y talla
                li.mb-0
                  i.fas.fa-square
                  | La talla base y las medidas
          .col-lg-5.col-md-12.col-12
            .caja5.p-4.mb-4
              ul.lista-ul--color.f-2
                li.d-flex.my-3
                  i.fas.fa-square.mb-5
                  |  Asignación de proporciones, plano por mitad.
    
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12.col-md-12.col-12            
        .caja5.p-4
          .row.justify-content-center.align-items-center.mb-0
            .col-lg-5.col-md-12.col-12
              img.img-a.img-t(src='@/assets/curso/tema1/img13.svg', alt='tema1')
            .col-lg-6.col-md-12.col-12
              p.mb-4 En este caso que el punto de origen está en un punto que divide el largo total.
              p.mb-2 Se debe tomar la proporción y aplicar mitad hacia arriba - mitad hacia abajo para el largo total y no perder la proporción de la figura.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12.col-md-12.col-12            
        .caja5.p-4
          .row.justify-content-center.align-items-center.mb-0
            .col-lg-5.col-md-12.col-12
              img.img-a.img-t(src='@/assets/curso/tema1/img14.svg', alt='tema1')
            .col-lg-6.col-md-12.col-12
              p.mb-4 En este caso que el punto de origen está en un punto base de construcción.
              p.mb-2 Se debe tomar la proporción y aplicar toda hacia arriba para largo total y no perder la proporción de la figura.
              p.mb-0 Sin embargo, debe tener en cuenta el vértice A.b modifica a su altura, para no perder la proporción de la figura.

    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center.align-items-center
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t.d-none.d-lg-block(src='@/assets/curso/tema1/img15.svg', alt='tema1')
            .col-lg-8.col-md-12.col-12
              p.mt-4.negro Ejercicios de elaboración
              p.mb-4 Teniendo en cuenta el ejercicio de análisis y sus respectivas explicaciones 
                strong realice el escalado de la figura en todas las tallas, 
                | con los dos puntos de origen propuestos en la explicación anterior. 
              p.mb-4 Para poder realiza dicha actividad necesita:
              .row.justify-content-between
                .col-lg-12.col-md-12.col-12
                  .row.justify-content-center
                    .col-lg-3.col-md-8.col-8.mb-4
                      img.img-a.img-t.mb-2(src='@/assets/curso/tema1/img16.svg', alt='tema1')
                      ul.lista-ul--color.f-1
                        li.mb-0.d-flex.mx-5
                          i.fas.fa-circle
                          | Lapiz
                    .col-lg-3.col-md-8.col-8.mb-4
                      img.img-a.img-t.mb-2(src='@/assets/curso/tema1/img17.svg', alt='tema1')
                      ul.lista-ul--color.f-1
                        li.mb-0.d-flex.mx-1
                          i.fas.fa-circle
                          | Lapices de colores
                    .col-lg-3.col-md-8.col-8.mb-4
                      img.img-a.img-t.mb-2(src='@/assets/curso/tema1/img18.svg', alt='tema1')
                      ul.lista-ul--color.f-1
                        li.mb-0.d-flex.mx-5
                          i.fas.fa-circle
                          | Papel
                    .col-lg-3.col-md-8.col-8.mb-4
                      img.img-a.img-t.mb-2(src='@/assets/curso/tema1/img19.svg', alt='tema1')
                      ul.lista-ul--color.f-1
                        li.mb-0.d-flex.mx-0
                          i.fas.fa-circle
                          | Reglas en centímetros

    .titulo-segundo.pri.mb-5
      h2.pri \\\ Tipos de escalado

    TabsC.color-primario.mb-5(data-aos="zoom-in-left")
      .py-3.py-md-4.bg26.px-3(titulo="Escalado monobásico")
        .row.justify-content-center
          .col-lg-4.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/tema1/img43.png', alt='')
          .col-lg-7.col-md-12.my-3
            p.mb-0 Partiendo de tallas base se obtienen las demás por aumento o reducción.
            p.mb-0 En este caso los incrementos entre tallas se mantienen constantes en toda la serie.
            p.mb-4 Crecimiento de estatura se produce aumentando ancho y largos, llamándose también escalado de crecimiento real.
            ul.lista-ul--color.f-1
              li.mb-4.d-flex.mx-0
                i.fas.fa-circle
                | Simple o relativo/diferencial Se aplica cuando los incrementos de tallas varían dentro de la serie ejemplo, no se produce incremento de estatura, solo anchos.                ul.lista-ul--color.f-1
              li.mb-4.d-flex.mx-0
                i.fas.fa-circle
                | Compuesto o absoluto propocional Los incrementos entre tallas se mantienen constantes en toda la serie, por ejemplo, se produce incremento de estatura, se aumenta anchos y largos, llamado también escalado de crecimiento real.
      .py-3.py-md-4.bg26.px-3(titulo="Escalado bibásico")
        .row.justify-content-center
          .col-lg-4.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/tema1/img44.png', alt='')
          .col-lg-7.col-md-12.my-3
            p.mb-4 Tomamos dos tallas básicas para obtener una intermedia, lo ideal es disponer de dos patrones, talla prototipo y talla límite.
            p.mb-4 Superponer patrón prototipo en el patrón límite con base en líneas comunes, una horizontal y una vertical.
            p.mb-4 Las tallas intermedias se trazan uniendo los vértices de ambos patrones por medio de puntos y dividiéndolos por el número de patrones a hallar.
      .py-3.py-md-4.bg26.px-3(titulo="Escalado tribásico")
        .row.justify-content-center
          .col-lg-4.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/tema1/img45.png', alt='')
          .col-lg-7.col-md-12.my-3
            p.mt-4 Se toman tres tallas para obtener una intermedia, por ejemplo, 10 – 14 – 18 para obtener la intermedia 12 - 16.

    .titulo-segundo.pri.mb-5
      h2.pri \\\ Análisis de cuadros de tallas
      
    p.mb-5 Para el análisis de cuadros de tallas se determina:
    
    .row.mb-5
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Límites
              p La más pequeña y la más grande. 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img46.svg')})`}")
              .tarjeta-slide_contenido.p-4.mt-5
                h1.text-center.lim Límites
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Frecuencia
              p Aumento de medida talla a talla (secuencial y no secuencial - constantes y variables).
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img47.svg')})`}")
              .tarjeta-slide_contenido.p-4.mt-5
                h1.text-center.lim Frecuencia
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Incremento
              p Magnitud de crecimiento de la medida talla por talla. 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img48.svg')})`}")
              .tarjeta-slide_contenido.p-4.mt-5
                h1.text-center.lim Incremento

    .row.justify-content-center.mb-5
      .col-lg-8.col-md-12.col-12
        .caja2.rad.p-4
          p.mb-0 El análisis de los anteriores dará como resultado: 
            strong valores – proporciones - rupturas de talla
    
    p.mb-5 En este caso se hace el análisis desde la talla base hasta la ruptura, identificando las medidas aplicar en el escalado del patrón base.

    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img20.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Cuadro de tallas femeninas
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el cuadro de tallas femeninas.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img21.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Tallas de 6 a 14
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre las Tallas de 6 a 14.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja4.p-4
          .row.justify-content-center.align-items-center
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t.d-none.d-lg-block.mt-3(src='@/assets/curso/tema1/img3.svg', alt='tema1')
            .col-lg-8.col-md-12.col-12
              p.mt-4.negro Para el procedimiento de patronaje en todas las prendas se debe tener en cuenta:
              p.mb-4 Si son prendas básicos o desarrollo de diseños, si se incluye o no margen de costura y las validaciones necesarias como producto final o insumo en el caso de básico para el desarrollo de otros modelos o análisis de tallaje, se trabaja el escalado en diferentes tallas propuestas, de igual manera se debe tener en cuenta el tipo de escalado que se va a trabajar, los aumentos y disminuciones por talla.

    p.mb-5 Al iniciar el proceso de escalado para trabajar los casos a realizar a continuación, utilizar referentes como cuadros de tallas, metodología y lógica de construcción, pieza o molde que se va  a escalar.
    
    .row.justify-content-center.mb-5
      .col-lg-9.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-4.col-md-12.col-12
            img.img-a.img-t(src='@/assets/curso/tema1/img22.jpg', alt='tema1')
          .col-lg-8.col-md-12.col-12
            .caja5.wid.p-5
              ul.lista-ul--color.f-1
                li.mb-4
                  i.fas.fa-circle
                  | Hacer el análisis del cuadro de tallas.
                li.mb-0
                  i.fas.fa-circle
                  | Hacer el análisis de diferencia por talla e identificar la medida a aplicar en el escalado.
                li.mb-0
                  i.fas.fa-circle
                  | Hacer el análisis de los puntos de escalado que se van a referenciar o modificar.
    Separador 
    #t_1_1.titulo-segundo.mb-4
      h2 1.1 Escalado de falda

    p.mb-5 Para iniciar el proceso de escalado se debe tener en cuenta el procedimiento anteriormente mencionado y las especificaciones para trabajar en esta prenda, haciendo claridad que es un molde que no tiene margen de costura y tampoco es una prenda. Importante verificar por ejemplo el escaldo en las pinzas, y que las medidas sean iguales en lateral delantero y posterior, entre otras.
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/ddrsedOxtKA?si=Y0XBIbjUFR2rxSNN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado de falda.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img23.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Escalado de falda - femenino
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el escalado de falda - femenino.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    Separador 
    #t_1_2.titulo-segundo.mb-5
      h2 1.2 Escalado de base con pinzas - superior
    
    .row.align-items-center.justify-content-center.mb-5
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            .avatar
              img.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img49.svg")
          .col-lg-10.col-md-12.col-12.caj.p-2
            .row
              .col-1
              .col-10
                p.my-3 El proceso de escalado debe ser seguido conforme a lo planteado anteriormente, haciendo claridad que es un molde que no tiene margen de costura y tampoco es una prenda. Es importante analizar el escalado de pinzas, además verificaciones en medidas laterales, cintura, entre otras. 

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/mN8946qBeGU?si=92rIKl-Gp91xT-0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado de base con pinzas - superior.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/ui7cNs-qD1k?si=BIaAZ5EY_DV70nDz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado de base con pinzas - superior.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img24.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Escalado de base con pinzas - superior
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el escalado de base con pinzas - superior.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

    Separador 
    #t_1_3.titulo-segundo.mb-4
      h2 1.3 Escalado de básico de pantalón

    .row.justify-content-center.mb-5
      .col-lg-1.col-md-12.col-12
        img.img-a.img-t.d-none.d-lg-block(src='@/assets/curso/tema1/img25.svg', alt='tema1')
      .col-lg-11.col-md-12.col-12
        p.mb-4 De igual manera en las prendas inferiores, en el caso de trabajar un básico de pantalón, se sigue el procedimiento de escalado, quiere decir un molde que no tiene margen de costura, ni es una prenda. Para este caso es importante verificar todas las medidas y su correspondencia tanto en posterior y delantero, por ejemplo, que las medidas de los laterales sean iguales, además en la entrepierna; otro lado de especial atención es el tiro, para que no afecte la horma de la prenda.
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/GS5jZ-Tw9vc?si=Ghstt2xJl9elO2TD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado de básico de pantalón.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img26.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Escalado de básico de pantalón
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el escalado de básico de pantalón.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

    Separador 
    #t_1_4.titulo-segundo.mb-4
      h2 1.4 Escalado cortes, manga, cuello

    p.mb-5 Como se ha mencionado en los anteriores escalados trabajados se debe seguir el procedimiento para estos casos, se hace referencia a prendas que ya han sido modificadas, que pueden tener margen de costura y validaciones como producto final. 
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-8.col-md-12.col-12
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Es importante analizar la simetría requerida en las piezas, en el caso de cortes la distribución de las proporciones a escalar.
      
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/5r4mM6naN40?si=igeK9hqMrzdHcmRX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado cortes, manga, cuello.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img27.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Escalado cortes, manga, cuello
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el escalado cortes, manga, cuello.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    Separador 
    #t_1_5.titulo-segundo.mb-4
      h2 1.5 Base superior masculina - análisis de escalado bibásico
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-8.col-md-12.col-12
            p.mb-4 En la metodología del #[b manual de patronaje SENA] se identifican análisis y modificaciones en cada una de las líneas, la línea femenina tiene un manejo diferente en masculino e infantil, en infantil y  masculino se suele trabajar medidas deducidas, partiendo en la mayoría de las ocasiones con solo dos medidas del cuerpo y dejando de lado el cuadro de tallas. 
            p.mb-4 Con el fin de explorar y afianzar las diferentes formas y técnicas de escalado se abordará un escalado bibásico tomando como referencia dos moldes de diferentes tallas o en su defecto tallas de por medio, en el video “Base superior masculina – análisis de escalado bibásico” podrá identificar la manera de hacer el trazo y el análisis de los aspectos a trabajar.
            .cajon.color-primario.p-4.mb-4
              p.mb-0 Este tipo de escalado se implementa para evitar el análisis del cuadro de tallas, se realiza el análisis desde la construcción o de la parte anatómica lógica del molde, despiece o la pieza. 
          .col-lg-4.col-md-8.col-8
            img.img-a.img-t(src='@/assets/curso/tema1/img28.png', alt='tema1')
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/mN8946qBeGU?si=aH5AtrPicz9jW1W1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Escalado base superior masculina - análisis de escalado bibásico.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img29.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Base superior masculina
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el base superior masculina.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    Separador 
    #t_1_6.titulo-segundo.mb-5
      h2 1.6 Análisis y construcción de cuadro de tallas masculino - dxt

    .row.justify-content-center.mb-5
      .col-lg-4.col-md-8.col-8
        img.img-a.img-t.d-none.d-lg-block(src='@/assets/curso/tema1/img30.png', alt='tema1')
      .col-lg-8.col-md-12.col-12
        p.mb-4.my-4 En la metodología del manual de patronaje SENA la línea de masculino e infantil se debe identificar bajo la fórmula o el tipo de construcción de los planos o moldes para poder tener las medidas e incrementos por talla que se van a trabajar en el escalado, si bien se identifica en el manual un cuadro de tallas para cada una de estas líneas, se debe tener en cuenta que desde la construcción, por lo menos en las bases superiores, no se trabaja con el cuadro de tallas, es decir, que se debe hacer la construcción y el análisis del cuadro de tallas basándose en las fórmulas que indica cada una de las construcciones de las bases que se están trabajando, con el fin de poder identificar las diferencias por tallas que se van a aplicar en el escalado.
        p.mb-4 Ya después de tener la construcción del cuadro de tallas o identificar las tallas reales que se aplican sobre el trazo o molde se debe hacer el análisis de los puntos y movimientos de escalado que se van a referenciar o modificar.

    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/O-_ANTDpnLg?si=HIjHgrHeyXx9ubry" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Nota. Adaptado de Análisis y construcción de cuadro de tallas masculino - dxt.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img31.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Análisis y construcción de cuadro de tallas masculino - dxt
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el análisis y construcción de cuadro de tallas masculino.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

    Separador 
    #t_1_7.titulo-segundo.color-primario.mb-5
      h2 1.7 Modificación de moldes - análisis sobre medidas
    
    .row.mb-5.align-items-center.justify-content-center
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            .avatar
              img.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img7.svg")
          .col-lg-10.col-md-12.col-12.caj.p-2
            .row
              .col-1
              .col-10
                p.my-3 Para el desarrollo de prendas y escalado de moldes se debe tener en cuenta que en algunas ocasiones se hace un análisis sobre medidas o sobre requerimientos de clientes específicos, algunas de ellas pueden ser modificaciones por talles, por anchos o por contornos. Este tipo de modificaciones se deben tener en cuenta al momento de realizar las prendas.

    
    p.mb-5 En el presente video se podrá encontrar una explicación general sobre cómo y de qué manera se puede implementar este tipo de modificaciones, con mayor relevancia en los moldes que se han desarrollado a lo largo del programa.
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12.col-10
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="1280" height="720" src="https://youtube.com/embed/2Aa8iCb_Zpo" title="mantenimiento de maquinaria y equipos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Nota. Adaptado de Modificación de moldes - Análisis sobre medidas.
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema1/img32.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Modificación de moldes - Análisis sobre medidas
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre la modificación de moldes - Análisis sobre medidas.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        titulo: 'Ubicación en plano cartesiano:',
        texto: ' punto de origen.',
        imagen: require('@/assets/curso/tema1/img33.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img34.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img35.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img36.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img37.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img38.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img39.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/curso/tema1/img40.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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
