<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Infografía estática

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/infografia/infografia.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 La #[strong Infografía estática] se presentará como una sola pieza gráfica que se auto sustenta a partir de texto corto, no tiene botones de interaccion.

        p.mb-4 Se utilizará en el momento que se desee brindar una explicación concreta de un tema a partir de datos específicos y secuenciales, apoyados, cada uno, con una imagen. Por ejemplo: Resúmenes, caracterizaciones, estadísticas, procesos, tipificaciones, fases, conclusiones.

        p.mb-4 No deben ser secuencias muy extensas, deben contar con un objetivo definido y todo el contenido enfocado a este.


    .row
      .col-lg-12.order-2.order-lg-1
        TabsA.color-acento-botones
          .tarjeta.clr--gris.p-4(titulo="Requerimientos de información")
            ul.lista-ul.mb-4
              li
                i.fas.fa-angle-right.txt--green
                | Título corto  (máximo 10 palabras)
              li
                i.fas.fa-angle-right.txt--green
                | <b>Texto descriptivo:</b> &nbsp;colocar una breve descripción del tema que se aborda en la infografía. (párrafo corto 40 palabras aprox)
              li
                i.fas.fa-angle-right.txt--green
                | <b>Imagen de referencia:</b> &nbsp;Describir y/o colocar una imagen de referencia, de la infografía solicitada.
              li
                i.fas.fa-angle-right.txt--green
                | Incluir cualquier observación o solicitud específica frente al diseño gráfico de la infografía.

          .tarjeta.clr--gris.p-4(titulo="Recomendaciones del diseñador")
            p #[strong 1) Definir un tema.]
              ul.lista-ul.ps-4
                li
                  i.fas.fa-angle-right.txt--green
                  | Explicación de un concepto.
                li
                  i.fas.fa-angle-right.txt--green
                  | Explicación de una tecnología o proceso.
                li
                  i.fas.fa-angle-right.txt--green
                  | Representación de datos estadísticos, biográficos, geográficos, etc.
                li
                  i.fas.fa-angle-right.txt--green
                  | Resumen de un documento.

              .hr--line
              p.mb-0 #[strong 2) Elegir un título atractivo.]<br> Se debe captar la atención del lector por medio de títulos cortos y llamativos que representen correctamente el contenido abordado.
              .hr--line
              p.mb-0 #[strong 3) Utilizar oraciones cortas y objetivas.]
              .hr--line
              p.mb-0 #[strong 4) Utilizar términos simples y fáciles de entender.]
              .hr--line
              p.mb-0 #[strong 5) La información debe estar bien organizada y esquematizada.]
              .hr--line
              p.mb-0 #[strong 6) Se debe hacer mayor énfasis en el lenguaje esquemático y pictórico.]
              .hr--line
              p.mb-0 #[strong 7) Los gráficos, diagramas, iconos y demás elementos planteados deben ser claros y específicos.]

    separador

    #t_1_1
    .titulo-segundo.color-acento-contenido
      h2 Ejemplos de infografías estáticas

    .titulo-sexto.color-acento-contenido
      h5 Ejemplo #1
      span infografía como imagen dentro del contenido

    .row.justify-content-center.align-items-center.mb-5
      .col-10
        img(src="@/assets/curso/temas/infografia/info1.png")

    .titulo-sexto.color-acento-contenido
      h5 Ejemplo #2
      span infografía descargable en pdf, con un título y texto introductorio.

    .tarjeta.color-acento-botones.p-4.p-md-5
      .row.justify-content-around.align-items-center
        .col-8.col-sm-5.col-md-4.mb-4.mb-md-0
          img(src="@/assets/componentes/ej-01.png")

        .col-md.col-lg-6
          h3 Psicología de la moda: sexualidad, ropa mágica, ropa malévola y ropa neurótica.
          p.mb-4 La conexión entre el vestuario y la persona que lo porta es lo que llamamos proceso efectivo de comunicación de las marcas, direccionado desde la psicología de la moda, lo invitamos a profundizar en esta temática consultando el siguiente recurso infografico.

          a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/Infografia_Psicologia_de_moda.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

    .row.justify-content-end.mb-5.me-3
      .col-auto
        a.boton.color-acento-contenido.texto-blanco.b--rad(:href="obtenerLink('/downloads/Llamado_accion_infografias.txt')" target="_blank" type="application/pdf")
          span Ver código fuente

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
