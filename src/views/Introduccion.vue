<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center 
      .col-lg-9.col-md-12.col-12
        .row.justify-content-center 
          .col-lg-4.col-md-8.col-8 
            img.mb-4(src='@/assets/curso/img1.png', alt='Proporción figura humana')
          .col-lg-8.col-md-12.col-12 
            .caja1.p-4 
              p.mb-4.negro ¡Bienvenidos!
              p.mb-4 En este componente se abordará 
                strong todas las bases de fundamentación para llevar a cabo todo tipo de escalado
                | , así mismo, se presenta las herramientas para trabajar los cuadros de tallas, atendiendo las diversas líneas femenina, masculina, adulto o  infantil, lo anterior permite atender la realización de trabajos personalizados o con requerimientos específicos, dependiendo siempre del tipo de cliente, marca o industria.



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
