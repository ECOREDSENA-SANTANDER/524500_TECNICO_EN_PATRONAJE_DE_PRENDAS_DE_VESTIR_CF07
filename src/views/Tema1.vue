<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Escalado manual de prendas
    
    
    #t_3_2.titulo-segundo.mb-4
      h2 Introducción y conceptualización - escalado
    
    .row.justify-content-center
      .col-lg-10.col-md-12.col-12
        .titulo-sexto.color-acento-contenido
          h5 Figura 2
          |  Análisis de división de cuerpo 

    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center
            .col-lg-7.col-md-12.col-12
              p.mt-4.negro ¿Qué es el escalado?
              p.mb-0 Es el método o técnica implementado para ampliar o reducir un patrón base, molde o trazo de una talla a otra proporcionalmente. Las proporciones se identifican de acuerdo con el cuadro de tallas o medidas estandarizadas, para llevar a cabo un escalado se implementan planos cartesianos que permiten identificar puntos de referencia, en las medidas de largos, anchos y contornos con sus proporciones que se diferencian entre una talla y otra.
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img1.svg', alt='tema1')
              
    #t_3_2.titulo-segundo.mb-4
      h2 Plano cartesiano

    p.mb-4 Está formado por dos rectas perpendiculares, una horizontal y otra vertical que se entrecruzan en un punto.
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja3.p-4
          .row.justify-content-center
            .col-lg-3.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img2.png', alt='tema1')
            .col-lg-7.col-md-12.col-12.my-5
              ul.lista-ul--color
                li.mb-4
                  i.fas.fa-bullseye
                  | #[b La recta horizontal, ] es llamada eje de las abscisas o de las equis #[b (X)]
                li.mb-4
                  i.fas.fa-bullseye
                  | #[b La recta vertical, ]  eje de las ordenadas o de las yes #[b (Y)]
                li.mb-4
                  i.fas.fa-bullseye 
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
              ul.lista-ul--color
                li.mb-0
                  i.fas.fa-bullseye
                  | La diferencia de #[b ancho] es 2 cm
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color
                li.mb-0
                  i.fas.fa-bullseye
                  | La diferencia de #[b alto] es 2 cm
    
    .row.justify-content-center.mb-5
      .col-lg-9.col-md-12.col-12
        .caja22.rad.p-4
          .row.justify-content-center.mb-5
            .col-lg-2.col-md-12.col-12
              img.img-a.img-t(src='@/assets/curso/tema1/img7.svg', alt='tema1')
            .col-lg-8.col-md-12.col-12
              p.mb-0 Se debe sacar un cuadrado más pequeño y un cuadrado más grande. Recuerde que todos los lados del cuadrado deben quedar iguales.
    
    #t_3_2.titulo-segundo.mb-4
      h2 Análisis sobre plano cartesiano


    

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
    
    #t_3_2.titulo-segundo.mb-4
      h2 Conclusiones
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-8.col-md-12.col-12
            .cajon.color-primario.p-4.mb-4
              p.mb-0 El manejo del punto de origen - punto cero - punto muerto, es el primer acercamiento a la comprensión de trasladar, modificar, mover puntos de referencia o construcción.
            p.mb-4 El concepto de positivo o negativo sobre el plano depende del punto de origen; aplicar en escalado se refiere a cada vez que se trabaja una medida sobre el plano cartesiano:
            .row.justify-content-center.mb-5
              .col-lg-9.col-md-12.col-12
                .caja22.rad.p-4
                  .row.justify-content-center
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color
                        li.mb-0
                          i.fas.fa-bullseye
                          | #[b Negativa:] reducción
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color
                        li.mb-0
                          i.fas.fa-bullseye
                          | #[b Positiva:] aumento
          
          .col-lg-4.col-md-8.col-8
            img.img-a.img-t(src='@/assets/curso/tema1/img9.png', alt='tema1')

    #t_3_2.titulo-segundo.mb-4
      h2 Proporciones
    
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

    #t_3_2.titulo-segundo.mb-4
      h2 Cómo identificar las proporciones                

    p.mb-5 Si la diferencia entre una medida y otra es de 2cm. La proporción equivale a #[b la manera en la que se aplica en el plano,] es decir:
    
    .row.justify-content-center.mb-5
      .col-lg-9.col-md-12.col-12
        .row.justify-content-center.mb-5
          .col-lg-4.col-md-12.col-12
            img.img-a.img-t(src='@/assets/curso/tema1/img11.png', alt='tema1')
          .col-lg-8.col-md-12.col-12
            .caja5.p-5
              ul.lista-ul--color
                li.mb-4
                  i.fas.fa-bullseye
                  | #[b Si sobre el plano se aplica la medida completa,] dicha medida equivale a una proporción, entonces una proporción será 2cm.
                li.mb-0
                  i.fas.fa-bullseye
                  | #[b Si sobre el plano se aplica la mitad de la medida, ]  esto equivale a 1/2 proporción, 1/2 proporción será 1 cm.
    
    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center
            .col-lg-6.col-md-12.col-12
              p.mt-4.negro Ejercicio de análisis 
              p.mb-4 Realice el #[b escalado de la siguiente figura] teniendo en cuenta:
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-bullseye
                  | El cuadro de tallas asignado
                li.mb-1
                  i.fas.fa-bullseye
                  | Las diferencias entre talla y talla
                li.mb-1
                  i.fas.fa-bullseye
                  | La talla base y las medidas
                li.mb-1
                  i.fas.fa-bullseye
                  | La asignación de proporciones, según tipo de plano a trabajar
                li.mb-1
                  i.fas.fa-bullseye
                  | El punto de origen sobre el plano cartesiano y la ubicación de la figura
            .col-lg-5.col-md-8.col-8
              img.img-a.img-t(src='@/assets/curso/tema1/img12.svg', alt='tema1')






























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
