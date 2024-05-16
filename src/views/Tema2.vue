<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Escalado en Optitex
    
    .row.justify-content-center.mb-5
      .col-lg-1.col-md-12.col-12
        img.img-a.img-t.d-none.d-lg-block(src='@/assets/curso/tema2/img1.svg', alt='tema1')
      .col-lg-11.col-md-12.col-12
        p.mb-4 A nivel general, el escalado digital o a través de un software de patronaje se trabaja de la misma manera o con el mismo análisis que se hace de forma manual, en esta ocasión únicamente se va a abordar la programación, herramientas y reconocimiento de la interfaz del programa Optitex para hacer cualquier tipo de escalado, de esta manera se tomará como referente la base de falda; sin embargo, estos mismos pasos y esta misma configuración aplica para cualquier tipo de base, prenda, trazo, molde o interpretación.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/watch?v=NdZGHw_-8bA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-10.col-md-12.col-12
        .fondo21.p-4.mb-2
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-12.col-12
              img.mx-1.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema2/img2.svg", alt="tema 2")
            .col-lg-9.col-md-12.col-12
              h4.mb-1.text-white Escalado en Optitex
              p.mb-2.text-white Revisa el documento que pueden resultar útil  para aprender más sobre el escalado en Optitex.
            .col-lg-2.col-md-12.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
                span Descargar
                i.fas.fa-file-download



</template>

<script>
export default {
  name: 'Tema2',
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
