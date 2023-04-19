<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-tasks" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .row.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/Seleccion_Multiple.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Actividad didáctica 1
        p.mb-4 Cras tempus tortor et nisi tincidunt feugiat. Integer lacus ante, venenatis nec fringilla quis, dapibus ut dui. Fusce imperdiet velit a leo sagittis, id scelerisque massa placerat. Duis at dui sed enim euismod pulvinar quis ac ante. Phasellus condimentum sapien nisi, ac facilisis purus tristique ac. Quisque magna est, luctus vitae elit ut, convallis venenatis justo. Nunc pretium elit a nisi tempus sagittis.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Descripción de la actividad didáctica.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
    .row.justify-content-end.mb-5.me-3
      .col-auto
        a.boton.color-acento-contenido.texto-blanco.b--rad(:href="obtenerLink('/downloads/Actividades.txt')" target="_blank" type="application/pdf")
          span Ver código fuente
      .col-auto
        a.boton.color-acento-contenido.texto-blanco.b--rad(:href="obtenerLink('/downloads/Iconos_actividades.zip')" target="_blank" type="application/pdf")
          span Descargar iconografía de las actividades

    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/Arrastrar_Soltar.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Actividad didáctica 2
        p.mb-4 Cras tempus tortor et nisi tincidunt feugiat. Integer lacus ante, venenatis nec fringilla quis, dapibus ut dui. Fusce imperdiet velit a leo sagittis, id scelerisque massa placerat. Duis at dui sed enim euismod pulvinar quis ac ante. Phasellus condimentum sapien nisi, ac facilisis purus tristique ac. Quisque magna est, luctus vitae elit ut, convallis venenatis justo. Nunc pretium elit a nisi tempus sagittis.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Descripción de la actividad didáctica.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/Completar.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Actividad didáctica 3
        p.mb-4 Cras tempus tortor et nisi tincidunt feugiat. Integer lacus ante, venenatis nec fringilla quis, dapibus ut dui. Fusce imperdiet velit a leo sagittis, id scelerisque massa placerat. Duis at dui sed enim euismod pulvinar quis ac ante. Phasellus condimentum sapien nisi, ac facilisis purus tristique ac. Quisque magna est, luctus vitae elit ut, convallis venenatis justo. Nunc pretium elit a nisi tempus sagittis.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Descripción de la actividad didáctica.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/Crucigrama.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Actividad didáctica 4
        p.mb-4 Cras tempus tortor et nisi tincidunt feugiat. Integer lacus ante, venenatis nec fringilla quis, dapibus ut dui. Fusce imperdiet velit a leo sagittis, id scelerisque massa placerat. Duis at dui sed enim euismod pulvinar quis ac ante. Phasellus condimentum sapien nisi, ac facilisis purus tristique ac. Quisque magna est, luctus vitae elit ut, convallis venenatis justo. Nunc pretium elit a nisi tempus sagittis.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Descripción de la actividad didáctica.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/Falso_Verdadero.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Actividad didáctica 5
        p.mb-4 Cras tempus tortor et nisi tincidunt feugiat. Integer lacus ante, venenatis nec fringilla quis, dapibus ut dui. Fusce imperdiet velit a leo sagittis, id scelerisque massa placerat. Duis at dui sed enim euismod pulvinar quis ac ante. Phasellus condimentum sapien nisi, ac facilisis purus tristique ac. Quisque magna est, luctus vitae elit ut, convallis venenatis justo. Nunc pretium elit a nisi tempus sagittis.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Descripción de la actividad didáctica.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
</template>

<script>
export default {
  name: 'Actividad',
}
</script>

<style lang="sass"></style>
