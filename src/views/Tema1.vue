<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Documentación de procesos de implantación

    .fullbg.bg--gray.p-4.mb-4
      .row.justify-content-center.align-items-center
        .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t1/t1_01.png", alt="alt")
        .col-lg-8(data-aos="fade-left")
          p Es fundamental porque permite realizar modificaciones necesarias al proyecto sin grandes complicaciones, debido a que en estos documentos se registra todo lo que ocurre en este proceso, desde las especificaciones hasta las actas de entrega, además de ser un instrumento para comunicar los detalles no tan obvios del sistema.
          .row
            .col-auto.d-none.d-lg-flex
              figure
                img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30.m-auto
            .col-lg
              p La documentación es el registro de todos los pasos necesarios “cómo” se realizan; el desarrollo de #[em software] es esencialmente un grupo de procesos interrelacionados, por lo cual es importante llevar una correcta documentación de los procesos en los formatos establecidos.
    
    p(data-aos="fade-left").mb-4 Este proceso de implantación es la última fase dentro de la aplicación de una metodología para implementar un proyecto que antes debió considerar una fase de prueba. Aunque todas las labores para llegar a este estado se han realizado arduamente, esta fase de implementación puede considerarse como la más compleja. 

    .row.justify-content-center.mb-4
      .col-lg-8
        .row(data-aos="fade-left")
          .col-auto.d-none.d-lg-flex
            figure
              img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30.m-auto
          .col-lg
            p Sin embargo, así como en los niveles de construcción y prueba, el grado de dificultad depende de las características tecnológicas utilizadas, en la fase de implementación se apunta hacia el uso de un producto realizado con estándares, con el fin de reducir significativamente los posibles riesgos, de manera que la aplicación se ejecute más fácilmente.    

        .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
          p.mb-0 En un proceso de implantación intervienen diferentes tipos de usuario, por lo que se requiere documentar este proceso por medio de manuales para cada proceso:

        .row.justify-content-center
          .col-lg-6.mb-4.mb-lg-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--01
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Usuarios que operan el sistema manual de usuario.
                  
          .col-lg-6.mb-4.mb-lg-0
            .crd.crd--avatarH.clr--02(data-aos="flip-left")
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_02.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Usuarios del nivel técnico manual técnico.

      .col-lg-4.d-none.d-lg-flex(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_02.png", alt="alt")

    .bloque-texto-a.bloque-texto-a.clr_01.p-4.p-md-5.mb-5(data-aos="zoom-in") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          figure
            img(src="@/assets/curso/temas/t1/t1_03.svg", alt="alt")
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p.mb-0 Así, los manuales de usuario y técnicos comprenden el sistema en conjunto, de manera que permiten establecer la capacitación y transferencia de conocimiento. Se recomienda que dicho proceso se lleve a cabo prestando la máxima atención a los detalles, además de determinar una táctica para la implantación manifestada en un plan completo de administración del proyecto, que fije las acciones requeridas, incluso para la verificación de la utilización de nuevas tecnologías.

    p(data-aos="fade-left").mb-5 A continuación se presentan los pasos de una estrategia de implantación unida a su correspondiente documentación:

    SlyderF.cstmSlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in")
      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="01")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_04.svg", alt="alt").img90.m-auto               
        p.text-center Conferir la responsabilidad de la implantación a un comité técnico y a uno administrativo que resulten apropiados.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="02")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_05.svg", alt="alt").img90.m-auto               
        p.text-center Recibir formalmente la versión definitiva del sistema, además de armar y desplegar el sistema según se requiera.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="03")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_06.svg", alt="alt").img90.m-auto               
        p.text-center Conducir las pruebas finales de todos los elementos de la versión definitiva e introducir los ajustes que resulten necesarios. Importante probar repetidamente cualquier cambio.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="04")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_07.svg", alt="alt").img90.m-auto               
        p.text-center Preparar la documentación necesaria, entre los que se mencionan los manuales técnicos, de usuario y de materiales de capacitación. También, reclutar o designar al personal que operará el sistema.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="05")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_08.svg", alt="alt").img90.m-auto               
        p.text-center Capacitar a los usuarios sobre el funcionamiento del nuevo sistema y de ser el caso, conducir campañas de información masiva.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="06")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_09.svg", alt="alt").img90.m-auto               
        p.text-center Generar respaldos de los programas e información del sistema según se requiera, además de controlar cualquier proceso de actualización, asegurándose de que se estén utilizando los equipos y programas apropiados.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="07")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_10.svg", alt="alt").img90.m-auto               
        p.text-center De ser necesario, asegurar que se encuentren disponibles los sistemas de respaldo. También es importante asegurar que se cuente con fuentes alternas de energía, si es el caso.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="08")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_11.svg", alt="alt").img90.m-auto               
        p.text-center Asegurar que se cuente con equipos técnicos y de mantenimiento durante la operación para garantizar el éxito en su operación y respaldar la información según se requiera.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="09")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_12.svg", alt="alt").img90.m-auto               
        p.text-center Evaluar la operación del sistema y tener reuniones informativas con los usuarios, además de preparar propuestas para mejorar o reutilizar el sistema.

      .crd.bg--white.brd--rad_02.shadow.p-4
        .numb_02(data-nb="10")
        figure.mb-4
          img(src="@/assets/curso/temas/t1/t1_13.svg", alt="alt").img90.m-auto               
        p.text-center Dar el mantenimiento al sistema según se requiera y aplicar cualquier mejora aprobada.

    .cajon.cjn--yellow.p-4.mb-5(data-aos="zoom-in")
      p.mb-0 Asimismo, es aconsejable enmarcar estos pasos dentro de los conceptos de impacto organizacional, infraestructura, adecuaciones y capacitación, vea en qué consiste cada uno:

    .row.justify-content-center.align-items-center
      .col-lg-7(data-aos="fade-right")
        LineaTiempoD.color-primario
          .row.justify-content-center.align-items-center(numero="1" titulo="Impacto organizacional")
            .col-12.mb-4
              p.mb-0 Se debe vencer la resistencia natural al cambio en las personas, por lo que se promueve:
            .row.justify-content-center.align-items-center
              .col-lg-6.col-8.order-2.order-lg-1
                figure
                  img(src="@/assets/curso/temas/t1/t1_15.svg", alt="alt")
              .col-lg-6.order-1.order-lg-2.mb-4.mb-lg-0
                ul.fa-ul.mb-0
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Gestión al cambio
                .hr_line  
                ul.fa-ul.mb-0
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Motivación
                .hr_line  
                ul.fa-ul.mb-0                   
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Comunicación

          .row.justify-content-center.align-items-center(numero="2" titulo="Infraestructura")
            .col-12.mb-4
              p.mb-0 Debe soportar la nueva implementación:
            .row.justify-content-center.align-items-center
              .col-lg-6.col-8.order-2.order-lg-1
                figure
                  img(src="@/assets/curso/temas/t1/t1_16.svg", alt="alt")

              .col-lg-6.order-1.order-lg-2.mb-4.mb-lg-0
                ul.fa-ul.mb-0
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Equipos, redes, servidor, aplicación, base de datos
                .hr_line  
                ul.fa-ul.mb-0
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Despliegue del #[em software]
                .hr_line  
                ul.fa-ul.mb-0                   
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Pruebas y #[em tuning]
                .hr_line  
                ul.fa-ul.mb-0                   
                  li
                    i.fa-li.fas.fa-check-circle.txt--orange02
                    | Perfiles de usuario

          .row.justify-content-center.align-items-center(numero="3" titulo="Adecuaciones")
            .col-12.mb-4
              p.mb-0 Garantiza el funcionamiento del proceso para la mitigación de riesgos y en caso de ser necesario se debe llevar a cabo una depuración de datos o una optimización de procesos. 

          .row.justify-content-center.align-items-center(numero="4" titulo="Capacitación")
            .col-12.mb-4
              p.mb-0 La capacitación a usuarios se guía preferiblemente por el uso de un prototipo, en el que los usuarios pueden ejecutar sus prácticas con total libertad y sin miedo a equivocarse.

      .col-lg-5.d-none.d-lg-flex(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_14.svg", alt="alt")

    separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Manuales técnicos

    .row.justify-content-center.mb-5
      .col-xl-3.col-md-6.col-8.mb-4.mb-xl-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_36.png", alt="alt")
      .col-xl-9(data-aos="fade-left")
        .row.mb-3
          .col-auto.d-none.d-lg-flex
            figure
              img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30.m-auto
          .col-lg
            p.mb-0 En una solución de #[em software] o de un sistema de información por procesamiento electrónico de datos, los manuales técnicos tienen el objetivo de mostrar, informar, esclarecer las estructuras que conforman la aplicación y cómo fue construida. Se dirige, especialmente, al personal técnico: desarrolladores de #[em software], técnicos en sistemas, ingenieros de infraestructura y redes, arquitectos de #[em software] e ingenieros de pruebas, entre otros, quienes manejan la aplicación o el componente formativo. 

        p.mb-4 Se recomienda que en su estructura se presenten los siguientes aspectos:

        .row.justify-content-center
          .col-xl-4.col-md-10.mb-4.mb-xl-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--01
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 El objetivo y alcance del sistema.

          .col-xl-4.col-md-10.mb-4.mb-xl-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--02
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_02.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Una descripción de la base de datos. 

          .col-xl-4.col-md-10.mb-4.mb-xl-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--01
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Un diseño de reportes y pantallas.

    .bloque-texto-a.bloque-texto-a.clr_02.p-4.p-md-5.mb-5(data-aos="zoom-in") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-8.order-2.order-lg-1
          .bloque-texto-a__texto.p-4
            p.mb-0 Basados en el ciclo de vida del desarrollo de #[em software] que normalmente se aplica en la elaboración de los sistemas de información por procesamiento electrónico de datos, es de vital importancia que la documentación técnica y de operaciones de una organización se registre en el manual técnico, el cual llevará una secuencia lógica de implementación para la instalación, configuración y despliegue. Este debe describir como mínimo los siguientes elementos:
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure
            img(src="@/assets/curso/temas/t1/t1_17.svg", alt="alt")

    .crd.bg_slider_01.brd--rad_02.px-4.py-2.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t1/t1_18.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="01")
              h4 Objetivos y alcances del sistema
              p Definir los objetivos del sistema y dividirlos tanto en generales como específicos, dependiendo de los componentes involucrados.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="02")
              h4 Diseño de reportes y pantallas
              p Utilizar ilustraciones estándar que faciliten el entendimiento del paso a paso de las actividades a realizar.
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t1/t1_19.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t1/t1_20.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ms-lg-5.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="03")
              h4 Prerequisitos
              p Dentro de los prerrequisitos de instalación del sistema se encuentran: sistema operativo de los servidores de aplicación y base de datos, marca y versión de la base de datos y de los servidores de aplicación, navegador, configuraciones de seguridad, contenedores, etc. 


        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="04")
              h4 #[em Frameworks] y estándares
              p Nombres y versiones de los #[em frameworks] y estándares bajo los cuales está construido el sistema. 
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t1/t1_21.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t1/t1_22.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ms-lg-5.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="06")
              h4 Diagramas
              ul.fa-ul.mb-0
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagramas de caso de uso del sistema.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagramas ER: modelo entidad relación del sistema.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagrama de servicios expuestos por el sistema.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagrama de despliegue del sistema. 
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagrama de las clases más relevantes del sistema.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Diagrama de servicios expuestos por el sistema.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="07")
              h4 Diccionario de datos
              p Diccionario de datos del sistema.
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t1/t1_23.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t1/t1_24.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ms-lg-5.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="08")
              h4 #[em Scripts]
              p #[em Scripts] de instalación del sistema.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="09")
              h4 Referencias
              p Referenciar la ubicación en la que se encuentra la especificación en alguna de las siguientes formas.
              ul.fa-ul.mb-0
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Casos de uso del sistema.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Historias de usuario.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Documento de requerimientos.
                li
                  i.fa-li.fas.fa-check-circle.txt--orange02
                  | Acumulado del producto (#[em product backlog] en la herramienta de Gestión de proyectos de desarrollo de #[em software]).

          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t1/t1_25.svg', alt='')

    .fullbg.bg--gray.p-4.mb-5
      .row.justify-content-center.align-items-center        
        .col-lg-8.mb-4.mb-lg-0        
          .row(data-aos="fade-left")
            .col-auto.d-none.d-lg-flex
              figure
                img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30.m-auto
            .col-lg
              p.mb-0 Al mismo tiempo es importante tener en cuenta que según el Ministerio TIC (2018), en este documento #[span.hglt_yellow queda plasmada toda la información del proyecto de #[em software], con una descripción bien detallada sobre las características técnicas y físicas de cada elemento; este manual va dirigido al administrador del sistema y a otros ingenieros para que puedan hacer un respectivo mantenimiento en caso de que sea necesario;] estos también contendrán la siguiente información:
          
        .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t1/t1_26.png", alt="alt")

    .row.justify-content-center(data-aos="zoom-in")
      .col-lg-10
        .cstm_Table 
          table
            thead.cell--blue
              tr.text-center
                th(colspan='2') Manuales de instalación
            tbody
              tr
                td Nombre del sistema
                td Nombre completo del sistema de información.
              tr.cell--gray  
                td Sigla
                td Sigla o nombre corto bajo el cual se conoce el sistema de información. Si aplica.
              tr
                td Descripción del sistema
                td Descripción funcional del sistema y los servicios que presta.
              tr.cell--gray  
                td Versión
                td Versión actual y en producción del sistema de información.
              tr
                td Categoría
                td Indique la categoría del sistema, de acuerdo con la clasificación del Marco de Referencia de Arquitectura Empresarial para la Gestión de TI en el Estado:<br><br>• Sistema misional<br>• Sistema de apoyo<br>• Portales digitales<br>• Sistema de direccionamiento estratégico
              tr.cell--gray  
                td Fabricante
                td Compañía que construyó el sistema de información o nombre del desarrollador.
              tr
                td Fecha de vencimiento del soporte
                td Indique la fecha hasta la cual se tiene el contrato de mantenimiento o soporte.
              tr.cell--gray  
                td Sistema operativo
                td Sistema(s) operativos(o) sobre los cuales funciona actualmente el sistema de información.
              tr
                td Lenguaje de programación
                td Lenguajes de programación y #[em frameworks] sobre los cuales fue construido el sistema de información. Ejemplos, Java 7, C#.Net framework 4.5, PHP 5.3, etc.
              tr.cell--gray  
                td Plataforma de base de datos
                td Ejemplo, Oracle, SQL server, Postgres, MySQL, entre otros.
              tr
                td Documentación técnica y funcional
                td Indique la ubicación (URL) de la documentación detallada técnica y funcional del sistema (arquitectura, manuales, diseños, etc.).
              tr.cell--gray  
                td Arquitectura tecnológica
                td Stand alone, Web, cliente servidor, App móvil, #[em software] as a service (nube), etc.

    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Manuales técnicos

    .bg_img_02.mb-5
      figure(data-aos="zoom-in")
        img(src="@/assets/curso/temas/t1/t1_27.png", alt="alt")
      .row.justify-content-center.top--negMargin(data-aos="fade").mb-5
        .col-lg-10
          .crd.bg--gray.shadow.brd--rad_01.p-4
            p.mb-0 Después de conocer las características del manual técnico revise en qué consiste el manual de usuario y qué aspectos se deben tener en cuenta en su elaboración. Para conocer esta información consulte el siguiente video:  

      figure.mb-5(data-aos="zoom-in")
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

      p(data-aos="fade-left").mb-5 Entonces, recuerde que de acuerdo con la guía de evidencias y la guía técnica del dominio de sistemas de información que propenden por lograr una implementación exitosa del lineamiento, el manual de usuario debe contener o hacer referencia a los siguientes temas: 

      .row.justify-content-center
        .col-lg-6.mb-4.mb-lg-0(data-aos="flip-left")
          .crd.crd--avatarH.clr--01
            .row
              .col-auto
                figure
                  img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
              .col
                h4 Objetivo del sistema de información desarrollado 
                ul.fa-ul
                  li
                    i.fas.fa-caret-right.txt--mint.me-2
                    | Índice del contenido 
                  li
                    i.fas.fa-caret-right.txt--mint.me-2
                    | Introducción
                  li
                    i.fas.fa-caret-right.txt--mint.me-2
                    | Alcance funcional y organizacional
                    
        .col-lg-6
          .crd.crd--avatarH.clr--02(data-aos="flip-left")
            .row
              .col-auto
                figure
                  img(src="@/assets/curso/recursos/avatar_02.svg", alt="alt").img75
              .col
                h4 Funciones y utilización del sistema 
                ul.fa-ul.mb-0
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Prerequisitos para el uso del sistema de información por parte del usuario final. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Configuración del sistema en el computador del usuario.
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Funcionalidad y servicios ofrecidos. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Paso a paso de cada opción del sistema. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Preguntas frecuentes. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Solución de problemas. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Datos de contacto. 
                  li
                    i.fas.fa-caret-right.txt--orange02.me-2
                    | Glosario.   

    separador

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Manuales de instalación

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_28.png", alt="alt")

      .col-lg-8(data-aos="fade-left")
        p Un manual de instalación de #[em software] corresponde a un documento técnico del paso a paso en orden secuencial y lógico, en donde se describe de manera detallada los componentes necesarios e instrucciones para instalar el #[em software]. 

        .row.mb-4
          .col-auto.d-none.d-lg-flex
            figure
              img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30
          .col-lg
            p.mb-0 Estas instrucciones normalmente deben ir acompañadas de material audiovisual de apoyo como imágenes, videos, gráficos, presentaciones, etc., que se toman preferiblemente de un proceso de instalación real que se ha ejecutado antes de acuerdo con los requisitos del sistema. 

        .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
          p.mb-0 Estas instrucciones con apoyo gráfico son una guía para realizar el correcto funcionamiento de una aplicación, especialmente para el personal técnico. Asimismo, es necesario considerar los siguientes elementos para la instalación:

    .row.justify-content-center.mb-5
      .col-lg-10
        .row.justify-content-center
          .col-lg-4.col-md-8.col-10.mb-4.mb-lg-0(data-aos="flip-left")
            .crd.bg--white.brd--rad_02.shadow.p-4
              .numb_02(data-nb="01")
              figure.mb-4
                img(src="@/assets/curso/temas/t1/t1_29.svg", alt="alt").img90.m-auto   
              h4.text-center.mb-4 Componentes            
              p.text-center Conjunto de elementos de #[em hardware], #[em software] e infraestructura de red requeridos por el sistema de información.

          .col-lg-4.col-md-8.col-10.mb-4.mb-lg-0(data-aos="flip-left")
            .crd.bg--white.brd--rad_02.shadow.p-4
              .numb_02(data-nb="02")
              figure.mb-4
                img(src="@/assets/curso/temas/t1/t1_30.svg", alt="alt").img90.m-auto   
              h4.text-center.mb-4 Pasos de instalación           
              p.text-center Se ordenan lógicamente para garantizar el funcionamiento del sistema, incluye comandos de ejecución, configuración y parametrización de datos.

          .col-lg-4.col-md-8.col-10(data-aos="flip-left")
            .crd.bg--white.brd--rad_02.shadow.p-4
              .numb_02(data-nb="03")
              figure.mb-4
                img(src="@/assets/curso/temas/t1/t1_31.svg", alt="alt").img90.m-auto   
              h4.text-center.mb-4 Rollback            
              p.text-center Definir el proceso de marcha atrás en la ejecución de alguno de los pasos, en caso de ser necesario.

    p(data-aos="fade-left").mb-4 Entonces, además de lo anterior ¿qué otros componentes se incluyen en el manual de instalación? 

    .row.mb-4(data-aos="fade-right")
      .col-auto
        .cstmH3
          h3.mb-0 Requisitos del sistema

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-5(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_32.png", alt="alt")
      .col-lg-7(data-aos="fade-left")
        p Se debe detallar qué tipo de #[em hardware] o #[em firmware] se necesita para instalar este #[em software], se especifica el sistema operativo Mac OS X o Windows 10 en el que puede funcionar. 
        p.mb-0 A continuación se presentan los requisitos mínimos para instalar el sistema operativo Windows 11 según Microsoft (2021):

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10 
        .cstm_Table       
          table
            thead.cell--blue
              tr.text-center
                th(colspan='2') Manuales de instalación
            tbody
              tr
                td Procesador
                td 1 giga Hertz (GHz) o más rápido con 2 o más núcleos en un procesador de 64 bits compatible o sistema en un chip (SoC).
              tr.cell--gray  
                td RAM
                td 4 gigabytes (GB).
              tr
                td Almacenamiento
                td Dispositivo de almacenamiento de 64 GB o más. Nota: para más información, consulte abajo en “Más información sobre los requisitos de espacio de almacenamiento para mantener Windows 11 actualizado”.
              tr.cell--gray  
                td #[em Firmware] del sistema
                td UEFI, compatible con arranque seguro. 
              tr
                td Tarjeta gráfica
                td Compatible con DirectX 12 o posterior con controlador WDDM 2.0.
              tr.cell--gray  
                td Pantalla
                td Pantalla de alta definición (720p) de más de 9” en diagonal, con canal de 8 bits por color.
              tr
                td Conexión a Internet y cuentas de Microsoft
                td Windows 11 Home requiere conexión a Internet y una cuenta de Microsoft.El cambio fuera de Windows 11 en modo S también requiere conexión a Internet.Para todas las ediciones de Windows 11 se requiere acceso a Internet para poder realizar actualizaciones, así como para descargar y aprovechar algunas de las características. Para algunas características se requiere una cuenta de Microsoft.
              tr.cell--gray  
                td TMP
                td Módulo de plataforma segura (TPM) versión 2.0.
              tr
                td Pantalla
                td Pantalla de alta definición (720p) de más de 9” en diagonal, con canal de 8 bits por color.
              tr.cell--gray  
                td(colspan="2") Windows 11 Home requiere conexión a Internet y una cuenta de Microsoft. Para todas las ediciones de Windows 11 se requiere acceso a Internet para poder realizar actualizaciones, así como para descargar y aprovechar algunas de las características. Para algunas características se requiere una cuenta de Microsoft.

    TabsC.color-acento-botones(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Descripción general de las características del sistema o del producto")
        .row.justify-content-center.align-items-center
          .col-xl-5.col-md-6.col-8.mb-4.mb-xl-0
            figure
              img(src="@/assets/curso/temas/t1/t1_33.svg", alt="alt")
          .col-xl-7
            h4 Descripción general de las características del sistema o del producto
            p Se describen las características básicas del #[em software] o del producto en cuestión, por lo general se usa una lista o una tabla. 
            p Ejemplo, en un #[em software] de telefonía IP (comunicación), se debe indicar cuántas líneas admite el #[em software], cuántos usuarios y contraseñas admite, el tipo de base de datos que necesita, cuántas zonas o particiones soporta, etc.

            .bg--gray.pt-4.p-5.mb-4   
              .quote           
                i.fas.fa-quote-left              
              p.ps-4.mb-2 Son importantes los datos de contacto del desarrollador o de la empresa que creó la solución informática o con el departamento de atención al cliente, dado el caso que se presente alguna duda relacionada con el producto, garantía, registro, etc.              
              p.text-end.mb-2 #[strong UGUR (2009)]    
              .quote.float-end
                i.fas.fa-quote-right 

            p.mb-0 También en este apartado se incluye cualquier exención de responsabilidad legal, divulgaciones, advertencias de agencias gubernamentales oficiales, información de registro, etc. 

      .py-3.py-md-4(titulo="Configuración mínima de inicio rápido")
        .row.justify-content-center.align-items-center
          .col-lg-5.col-8.mb-4.mb-lg-0
            figure
              img(src="@/assets/curso/temas/t1/t1_34.svg", alt="alt")
          .col-lg-7
            h4 Configuración mínima de inicio rápido
            p En algunos tipos de #[em software] se publica una guía de “inicio rápido” independiente, además se explica cómo identificar e interpretar cualquier sistema o códigos de #[em hardware] y números de serie que vienen con el producto. 

            p Así, se deben incluir gráficos del paso a paso de cómo instalar el #[em software] y mostrar las conexiones de cableado correctas, en caso de que se trate de alguna instalación física.

            p.mb-0 Si se realizan todas las sugerencias en este manual se fomentará la lealtad del cliente, ya que se generan altos niveles de satisfacción y se minimizan las llamadas al departamento de atención al cliente.   

      .py-3.py-md-4(titulo="Configuraciones de instalación")
        .row.justify-content-center.align-items-center
          .col-lg-5.col-8.mb-4.mb-lg-0
            figure
              img(src="@/assets/curso/temas/t1/t1_35.svg", alt="alt")
          .col-lg-7
            h4 Configuraciones de instalación
            p Es común que un #[em software] de aplicación tenga una instalación “típica” y una “excepcional” o una “diseñada por el cliente”. En ocasiones, esta instalación también se denomina “implementación” en la documentación del producto.
            p A continuación se invita a conocer los componentes mínimos que se incluirán en la estructura de un manual de instalación:

            .tarjeta.bg--cta.p-3
              .row.justify-content-around.align-items-center
                .col-auto
                  img(src="@/assets/curso/recursos/cta_01.svg").img45
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h5.text-white.mb-1 Formato de instalación
                      p.text-white.mb-0 Estimado aprendiz a continuación descargar el siguiente documento para su consulta.
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('/downloads/Formato_Instalacion.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download   



                                                           
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    modal1: false,
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
