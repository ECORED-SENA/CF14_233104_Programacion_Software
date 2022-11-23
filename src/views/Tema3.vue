<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Labores finales del proceso de implantación            

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t3/t3_01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las labores de pruebas, acta de entrega y mantenimiento de #[em software] son las que se realizan para garantizar la entrega del producto de #[em software] instalado y configurado de manera correcta.  En las actas se registran tanto la persona que entrega el producto como el cliente que lo recibe, además, se informa a los clientes sobre las políticas y mecanismo de implementación de labores de garantía y de mantenimiento de #[em software].

    separador

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Pruebas y actas de entrega

    .fullbg.bg--gray.p-4.mb-4
      .row.justify-content-center
        .col-xl-4.col-lg-6.col-8.mb-4.mb-xl-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t3/t3_02.svg", alt="alt")
        .col-xl-8(data-aos="fade-left")
          p Al momento de realizar la entrega de la solución informática esta debió ser probada de manera interna por los desarrolladores para examinar la correcta funcionalidad de todos sus procesos, permitiendo conocer la calidad del mismo, así como los posibles fallos que se puedan presentar a corto, medio o largo plazo, con el fin de lograr predecir su comportamiento durante la implantación, su grado de manejabilidad y lo amigable que pueda ser su interfaz gráfica.

          .row.justify-content-center
            .col-auto.d-none.d-lg-flex
              figure
                img(src="@/assets/curso/recursos/rectangle_00.svg", alt="alt").img30
            .col-lg
              p.mb-0 En el caso de los usuarios, las pruebas van dadas por las necesidades y el contexto que representa a cada uno de los clientes, en otras palabras, la misma prueba no puede servir para todos los escenarios, porque puede ser que una prueba para un #[em software] específico sea la adecuada, pero en otro puede llegar a ser perjudicial. En el caso puntual de los clientes se debe hacer una prueba de funcionamiento y rendimiento en el sitio, bajo las condiciones y entorno de la empresa, con las funciones y datos reales, esta prueba debe ser ejecutada y analizada por las dos partes, se puede hacer  en una sola jornada o si el cliente lo desea se puede hacer dos días o hasta en una semana, solo así, el cliente sentirá la seguridad de firmar el acta de entrega a satisfacción.

    .row.justify-content-center.align-items-center
      .col-lg-9.order-2.order-lg-1(data-aos="fade-left")
        p Las pruebas como las actas de entrega se presentan en los formatos establecidos por la organización para los cuales se realizan y se especifican el conjunto de pruebas realizadas, también se pueden referenciar a manera de anexo. En dichos documentos se debe establecer las firmas de los participantes tanto de los que entregan como de los que reciben, especificando fechas, estado y componentes entregados.
        .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
          p.mb-0 Estos documentos son muy importantes porque se constituyen en la evidencia de los compromisos adquiridos entre el cliente y el proveedor, que normalmente se expresan bajo un contrato. Apoyan la memoria histórica de lo realizado durante el proyecto sobre todo en la parte de pruebas, lo que es de especial atención cuando en una organización se presentan altos índices de rotación de personal. Se invita a conocer el siguiente ejemplo de acta de entrega:
      .col-lg-3.col-8.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t3/t3_03.svg", alt="alt")

    .tarjeta.bg--cta.p-3.mb-5(data-aos="zoom-in")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/recursos/cta_01.svg").img45
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white.mb-1 Acta de entrega
              p.text-white.mb-0 Estimado aprendiz a continuación descargar el siguiente documento para su consulta.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Acta_Entrega.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="right")
      h2 3.2 Mantenimiento de #[em software]

    .fullbg.bg--gray.p-4.mb-4
      .row.justify-content-center.align-items-center
        .col-xl-4.col-lg-5.col-8.mb-4.mb-xl-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t3/t3_04.svg", alt="alt")
        .col-xl-8
          p(data-aos="fade-left") El eje central de este apartado es indicar cómo se debe realizar el mantenimiento del #[em software] de forma adecuada, de tal manera que la calidad del aplicativo no se deteriore como resultado del uso, debe enfocarse en la siguiente pregunta: ¿cómo debe mantenerse el #[em software] para preservar su fiabilidad?

          .row.align-items-center.mb-4(data-aos="fade-left")
            .col-auto.d-none.d-lg-flex 
              figure
                img(src="@/assets/curso/recursos/rectangle_00.svg", alt="alt").img30
            .col-lg
              p.mb-0 Esta es la fase que se presenta dentro del ciclo de vida de desarrollo de #[em software] después de la fase de puesta en producción o implementación del producto, se caracteriza por:

          .row.justify-content-center
            .col-lg-4.col-10.mb-4.mb-lg-0(data-aos="flip-left")
              .crd.bg--white.brd--rad_02.shadow.p-4
                .numb_02(data-nb="01")
                figure.mb-4
                  img(src="@/assets/curso/temas/t3/t3_05.svg", alt="alt").img90.m-auto               
                p.text-center Permitir la posibilidad de agregar mejoras al proyecto entregado.

            .col-lg-4.col-10.mb-4.mb-lg-0(data-aos="flip-left")
              .crd.bg--white.brd--rad_02.shadow.p-4
                .numb_02(data-nb="02")
                figure.mb-4
                  img(src="@/assets/curso/temas/t3/t3_06.svg", alt="alt").img90.m-auto               
                p.text-center Optimizar el proyecto entregado, así como también la corrección de defectos.

            .col-lg-4.col-10.mb-4.mb-lg-0(data-aos="flip-left")
              .crd.bg--white.brd--rad_02.shadow.p-4
                .numb_02(data-nb="03")
                figure.mb-4
                  img(src="@/assets/curso/temas/t3/t3_07.svg", alt="alt").img90.m-auto               
                p.text-center En el momento de detectar los defectos deben ser ingresados en el sistema de rastreo de defectos. 

    .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
      p.mb-0 El mantenimiento de #[em software] se puede clasificar en los siguientes tipos, los cuales se diferencian por el porcentaje aproximado respecto del conjunto de mantenimiento:

    .row.justify-content-center.mb-4
      .col-lg-3.col-10.mb-4.mb-lg-0(data-aos="flip-left")
        .bg--blue.brd--rad_01
          .row
            .col-auto
              .bg--white02.p-2
                figure                
                  img(src="@/assets/curso/temas/t3/t3_08.svg", alt="alt").img45
            .col.hor--negMargin        
              p.ver-align.text-center.text-white.strong.mb-0 Mantenimiento evolutivo

      .col-lg-3.col-10.mb-4.mb-lg-0(data-aos="flip-left")
        .bg--mint.brd--rad_01
          .row
            .col-auto
              .bg--white02.p-2
                figure                
                  img(src="@/assets/curso/temas/t3/t3_08.svg", alt="alt").img45
            .col.hor--negMargin        
              p.ver-align.text-center.strong.mb-0 Mantenimiento adaptativo

      .col-lg-3.col-10.mb-4.mb-lg-0(data-aos="flip-left")
        .bg--blue.brd--rad_01
          .row
            .col-auto
              .bg--white02.p-2
                figure                
                  img(src="@/assets/curso/temas/t3/t3_08.svg", alt="alt").img45
            .col.hor--negMargin        
              p.ver-align.text-center.text-white.strong.mb-0 Mantenimiento correctivo

      .col-lg-3.col-10(data-aos="flip-left")
        .bg--mint.brd--rad_01
          .row
            .col-auto
              .bg--white02.p-2
                figure                
                  img(src="@/assets/curso/temas/t3/t3_08.svg", alt="alt").img45
            .col.hor--negMargin        
              p.ver-align.text-center.strong.mb-0 Mantenimiento preventivo 

    p(data-aos="fade-left") Recuerde que el mantenimiento de #[em software] es una de las actividades más comunes en la ingeniería de #[em software], que consiste en el proceso de mejora y optimización del #[em software] desplegado (revisión del programa y corrección de los defectos).   
              




    


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
