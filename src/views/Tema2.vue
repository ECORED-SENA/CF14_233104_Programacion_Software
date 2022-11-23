<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Capacitación de usuarios

    .fullbg.bg--gray.p-4.mb-4  
      .row.justify-content-center.align-items-center
        .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t2/t2_01.png", alt="alt")
        .col-lg-8(data-aos="fade-left")
          .quote           
            i.fas.fa-quote-left              
          p.ps-4.mb-2 #[strong la transferencia de conocimientos que se realiza durante todo el proceso de implementación de un sistema. Dicha transferencia de conocimiento debe realizarse a los integrantes del equipo de implementación, entendiendo como tal al conjunto de los usuarios del sistema y los consultores externos, relacionados con el proceso de implementación.]              
          p.text-end #[strong Aisemberg (2021)]    
          .quote.float-end
            i.fas.fa-quote-right

    p(data-aos="fade-left") La capacitación se realiza mediante la recopilación de la mayor cantidad de información posible del sistema de información, primordialmente, se acude a los manuales técnicos y de usuario disponibles, por lo cual es muy importante estudiar las tecnologías involucradas descritas, según sea el caso y complementar con experiencias propias. 

    p(data-aos="fade-left").mb-5 Por lo general existen dos tipos de usuario a quienes van dirigidas las capacitaciones:

    .row.justify-content-center.mb-5
      .col-lg-6.mb-4.mb-lg-0(data-aos="flip-left")
        .crd.crd--avatarH.clr--01
          .row
            .col-auto
              figure
                img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
            .col
              p.v-align.mb-0 Usuarios operativos para los cuales se brinda el conocimiento de las funcionalidades de acuerdo con el área de negocio y las necesidades del cliente. 
              
      .col-lg-6.mb-4.mb-lg-0
        .crd.crd--avatarH.clr--02(data-aos="flip-left")
          .row
            .col-auto
              figure
                img(src="@/assets/curso/recursos/avatar_02.svg", alt="alt").img75
            .col
              p.v-align.mb-0 Usuarios de orden consultor a quienes normalmente se les proporcionará el conocimiento de los procesos administrativos, de operación de las distintas áreas e incluso de nivel técnico para soportar.

    .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
      p.mb-0 Para llevar a cabo una buena capacitación Aisemberg (2021) hace las siguientes recomendaciones: 
    
    .row.justify-content-center.align-items-center
      .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t2/t2_02.png", alt="alt")
      .col-lg-8(data-aos="fade-right")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Líder de proyecto")
            .col-12
              p.mb-0 Asignar un líder de proyecto (interno o externo) con experiencia en la ejecución de sistemas de gestión, que analice previamente y con detalle el proyecto que deberá tener incluido el plan de capacitación y sus plazos de realización.

          .row(numero="2" titulo="Personal especializado")
            .col-12
              p.mb-0 Solicitar personal especializado para realizar un estudio de las capacidades y aptitudes del personal de la organización.

          .row(numero="3" titulo="Director de proyecto")
            .col-12
              p.mb-0 Nombrar un director de proyecto para asegurar el acompañamiento de la dirección, socializar con el equipo de trabajo la visión y los objetivos del negocio y definir los aspectos clave en los procesos de negocio de las distintas áreas involucradas.

    separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Técnicas

    .bloque-texto-g.cstm_right.p-3.p-sm-4.p-md-5.mb-4(data-aos="zoom-in")    
      .bloque-texto-g__texto.p-4
        p.mb-0 Una de las grandes tareas a cargo de los departamentos de recursos humanos es realizar un seguimiento para conocer cuáles son las necesidades de capacitación dentro de una empresa o de un área de trabajo determinada, una buena organización debe ser capaz de determinar cuáles son las necesidades de capacitación de los colaboradores, para lograr diseñar los planes y programas que las satisfagan, contemplando los aspectos materiales y humanos necesarios. #[strong Eslabón (2019).]
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t2/t2_03.png')})`}"
      )
          
    p(data-aos="fade-left") De acuerdo con este concepto, es momento de preguntar ¿cómo se puede llevar a cabo una estrategia acertada de capacitación? 

    p(data-aos="fade-left").mb-4 Para ello, se requiere detectar las necesidades de capacitación, pero ¿a qué hace referencia este concepto?

    .fullbg.bg--gray.p-4.mb-4  
      .row.justify-content-center.align-items-center
        .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t2/t2_04.png", alt="alt")
        .col-lg-8(data-aos="fade-left")
          .quote           
            i.fas.fa-quote-left              
          p.ps-4.mb-2 #[strong Sostiene que es el proceso orientado a la estructuración y desarrollo de planes o programas para el establecimiento y fortalecimiento de conocimientos o habilidades en los colaboradores de una organización, con la finalidad de aportar en el logro de los objetivos corporativos.]              
          p.text-end #[strong Eslabón (2019)]    
          .quote.float-end
            i.fas.fa-quote-right

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-left")
        .row.mb-4
          .col-auto.d-none.d-lg-flex
            figure
              img(src="@/assets/curso/recursos/rectangle_00.svg/", alt="alt").img30.m-auto
          .col-lg
            p.mb-0 Cuando se precisan estas necesidades de capacitación es posible ejecutar satisfactoriamente las tareas y responsabilidades que le corresponde a cada uno de los empleados dentro de la organización, así como las limitaciones de la misma organización que pueden afectar el desempeño.
        .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
          p.mb-0 Existen dos tipos de necesidades de capacitación:

        .row.justify-content-center
          .col-lg-6.mb-4.mb-lg-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--01
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_01.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Necesidades manifiestas 
                  
          .col-lg-6.mb-4.mb-lg-0(data-aos="flip-left")
            .crd.crd--avatarH.clr--02
              .row
                .col-auto
                  figure
                    img(src="@/assets/curso/recursos/avatar_02.svg", alt="alt").img75
                .col
                  p.v-align.mb-0 Necesidades encubiertas

      .col-lg-4.col-8(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t2/t2_05.svg", alt="alt")

    .row.mb-4(data-aos="fade-right")
      .col-auto
        .cstmH3
          h3.mb-0 Tipos de capacitación

    p(data-aos="fade-left").mb-4 Las labores de capacitación se clasifican en los siguientes tipos:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t2/t2_06.png", alt="alt")
      .col-lg-8(data-aos="fade-right")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Aprendizaje pasivo")
            .col-12
              p.mb-0 El participante es un receptor pasivo de lo que imparte el instructor, ya sea en forma directa o indirecta.

          .row(numero="2" titulo="Aprendizaje activo")
            .col-12
              p.mb-0 Exige que el participante piense y actúe para descubrir el conocimiento. El papel del instructor y los medios didácticos consisten solamente en facilitar, guiar y estimular el aprendizaje.

          .row(numero="3" titulo="Capacitación grupal")
            .col-12
              p.mb-0 Se proporciona a un grupo de participantes y la enseñanza se imparte en forma colectiva.

          .row(numero="4" titulo="Capacitación individual")
            .col-12
              p.mb-0 Se adapta a las características individuales de cada participante, considerando sus potencialidades y limitaciones.

    p.mb-5 Se recomienda analizar muy bien las necesidades y contar con la asesoría de un asesor experto, además, revisar antecedentes o experiencias anteriores para seleccionar el tipo de aprendizaje idóneo en cada caso. 

    .row.mb-4(data-aos="fade-right")
      .col-auto
        .cstmH3
          h3.mb-0 Técnicas de capacitación

    p(data-aos="fade-left").mb-4 Después de clasificar e identificar la capacitación requerida es muy importante, desde el punto de vista metodológico, seleccionar la forma de presentarla, para lo cual se relacionan las siguientes técnicas que corresponden a mecanismos reconocidos y muy utilizados en diferentes organizaciones:

    .crd.bg_slider_01.brd--rad_02.px-4.py-2.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="01")
              h4 Capacitación organizacional
              p.mb-0 Programa formativo que se realiza mediante seminarios o talleres, con el objetivo de transmitir conocimientos útiles a todo el equipo humano. Importante contar con una plataforma para medir la eficacia de la formación y el progreso de los empleados, sus necesidades y puntos fuertes.              
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_07.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_08.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="02")
              h4 Comunicación asertiva
              p Se aplica en casos de dificultad comunicativa entre líderes y colaboradores. Es común encontrar falla en las tareas por falta de comprensión de las reglas o por falta de comunicación entre el equipo.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="03")
              h4 Formación en liderazgo
              p.mb-0 Identificar perfiles clave que sean líderes de un equipo, para guiar un proyecto, además de mediar, motivar y tomar decisiones complejas. Su objetivo se orienta a la gestión de personas, el manejo de conflictos, la administración de metas y el pensamiento crítico.              
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_09.svg', alt='')        

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_10.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="04")
              h4 #[em Coaching] corporativo
              p Se busca el desarrollo individual y colectivo en la organización, con el foco en un equipo asertivo, de alto desempeño y comprometido en la mejora de resultados. Se pretende que los colaboradores se sientan parte de la empresa para  alcanzar los resultados esperados.

    separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Plan de capacitación

    .fullbg.bg--gray.p-4.mb-4  
      .row.justify-content-center.align-items-center
        .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/temas/t2/t2_11.png", alt="alt")
        .col-lg-8(data-aos="fade-left")
          .quote           
            i.fas.fa-quote-left              
          p.ps-4.mb-2 #[strong Un plan o programa de capacitación se conforma de un conjunto de pasos para el entrenamiento del equipo de trabajo, en el que mediante actividades guiadas se presenta información tanto teórica como práctica sobre algún tema. En este plan de capacitación se identificarán las debilidades del equipo para dirigir las actividades que suplan tales dificultades en un tiempo determinado. Por ello, en la planeación se debe incluir la cantidad de horas a invertir y el personal necesario involucrado tanto de aprendices como de formadores.]             
          p.text-end #[strong (Da Silva, 2022).]    
          .quote.float-end
            i.fas.fa-quote-right

    p(data-aos="fade-left").mb-4 Se invita a revisar un ejemplo de los pasos que se deben incluir en el documento de estructura de un plan de capacitación.

    .row.justify-content-center
      .col-lg-10
        PasosA.color-acento-botones.mb-5(tipo="n")
          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
              h4 Necesidades
              p.mb-0 ¿Qué conocimientos, habilidades y actitudes deben ser fortalecidas?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_29.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0.txt--left(data-aos="fade-left")
              h4 Agente de capacitación
              p.mb-0 ¿La capacitación será desarrollada por un agente interno (del mismo equipo de trabajo) o por un agente externo (proveedor)?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_30.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
              h4 Objetivos
              p.mb-0 ¿Para qué capacitar?, ¿qué se desea lograr con la capacitación?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_31.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0.txt--left(data-aos="fade-left")
              h4 Objetivos
              p.mb-0 ¿Para qué capacitar?, ¿qué se desea lograr con la capacitación?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_32.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
              h4 Formato
              p.mb-0 ¿Cómo se realizará?, ¿presencial, en línea o semipresencial?,¿se cuenta con espacios físicos, con la infraestructura tecnológica o ambas?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_33.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0.txt--left(data-aos="fade-left")
              h4 Contenido
              p.mb-0 ¿Qué deben aprender los participantes para obtener los conocimientos, habilidades y actitudes que se quieren desarrollar o fortalecer?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_34.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
              h4 Tipo, modalidad y nivel
              p.mb-0 Tipo: inductivo, preventivo, desarrollo de carrera. Modalidad: formación, actualización especialización o perfeccionamiento.
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_35.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0.txt--left(data-aos="fade-left")
              h4 Impacto
              p.mb-0 ¿Qué beneficios habrá para la empresa o institución?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_36.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
              h4 Metodología de desarrollo
              p.mb-0 ¿Cómo y con qué se llevará a cabo la formación y el proceso de enseñanza y aprendizaje?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_37.svg", alt="alt")

          .row.justify-content-center.align-items-center
            .col-lg-6.mb-4.mb-lg-0.txt--left(data-aos="fade-left")
              h4 Inversión
              p.mb-0 ¿El costo de lo que se desea implementar se ajusta al presupuesto original? ¿El costo por un agente de capacitación externo es viable para el presupuesto de la empresa o institución?
            .col-lg-6(data-aos="zoom-in")
              figure
                img(src="@/assets/curso/temas/t2/t2_38.svg", alt="alt")

    .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
      p.mb-0 De acuerdo con #[em.strong Edgepoint learning (2020)], hay que establecer plazos y métodos de implementación, estos deben ser claros y realistas para no jugar con el tiempo de los usuarios, ni la productividad de la empresa. A continuación algunos tips de aporte en este ítem. Para lograr un buen plan de capacitación su documento debe contener la siguiente estructura:

    .tarjeta.bg--cta.p-3.mb-5(data-aos="zoom-in")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/recursos/cta_01.svg").img45
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white.mb-1 Estructura de un plan de capacitación
              p.text-white.mb-0 Estimado aprendiz a continuación descargar el siguiente documento para su consulta.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Estructura_Plan_Capacitacion.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Videotutoriales

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.order-2.order-lg-1(data-aos="fade-left")
        p.mb-4 Un videotutorial corresponde a la unión de un video de imágenes con el instructivo en una serie de pasos que se quieren ilustrar para llevar a cabo el aprendizaje en un tema en específico, está orientado a estimular la cultura del autoaprendizaje en un aprendiz y normalmente su construcción suele ser de videos cortos con un máximo de 10 minutos, diseñados de manera atractiva para llamar la atención y retener a los usuarios.
        .row
          .col-auto.d-none.d-lg-flex
            figure
              img(src="@/assets/curso/recursos/rectangle_01.svg/", alt="alt").img90.m-auto
          .col-lg
            p.mb-0 #[strong Para realizar un videotutorial es necesario realizar un análisis sobre los siguientes aspectos:]
      .col-lg-4.col-8.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t2/t2_12.svg", alt="alt")

    .row.justify-content-center.mb-4
      .col-lg-4.col-8.order-2.order-lg-1(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t2/t2_13.png", alt="alt")
      .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
        ul.fa-ul
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | Identificar el aprendizaje que se quiere impartir.
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | ¿A quién va dirigido?
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | El tema a investigar.
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | La definición de objetivos.
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | Redactar un guion con estructura narrativa: inicio, nudo y desenlace.
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | Seleccionar las herramientas tecnológicas de acuerdo con la complejidad de elaboración del video.
          .hr_line
          li
            i.fa-li.fas.fa-check-circle.txt--mint
            | Finalmente, lograr una fácil puesta en marcha y facilidades de publicación del video en medios de uso masivo.  

    p(data-aos="fade-left").mb-4 Vea algunas buenas prácticas que Mejía (2019) considera conveniente para realizar un videotutorial exitoso:

    .crd.bg_slider_01.brd--rad_02.px-4.py-2.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="01")
              h4 Contenidos útiles
              p.mb-0 Elija contenidos útiles y de valor para su público. Investiga cuáles son las dudas más frecuentes entre su audiencia y ofrézcales la respuesta a sus preguntas con un video.              
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_14.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_15.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="02")
              h4 Crear un guión
              p Cree un guion sobre la narración que va a ir teniendo en el transcurso del material audiovisual y ensáyelo para evitar equivocaciones al hacer la grabación y realizar múltiples ediciones.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="03")
              h4 Extensión
              p.mb-0 Los videos largos aburren, por lo que su material debe no tener una duración mayor a 10 minutos. Si cree que su video no se podrá desarrollar en ese periodo de tiempo, puede manejarlo por partes o capítulos.            
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_16.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_17.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="04")
              h4 Música
              p No utilice música de fondo, porque puede distraer al usuario. Al único sonido que se le debe prestar total atención es a su voz.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="05")
              h4 Lenguaje
              p.mb-0 Utilice un lenguaje claro y sencillo. Las personas que ven su videotutorial posiblemente no tienen un conocimiento avanzado previo y se les dificulte entender algunos conceptos del procedimiento que está explicando.            
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_18.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_19.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="06")
              h4 Redes sociales
              p Compártalo en todas las redes sociales. Este es uno de los recursos al que más provecho le puede sacar. Además de publicarlo en su blog, puede publicarlo en YouTube, Twitter y Facebook y observar la respuesta que generan.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="07")
              h4 Planeación
              p.mb-0 Solo si es un experto en el tema puede  improvisar. Un videotutorial siempre debe estar planificado, desde las capturas de pantalla que mostrará hasta el guion que seguirá. Si considera que sabe desarrollar muy bien el tema sin titubear, ¡adelante! Puede crear su video sin planificación.            
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_20.svg', alt='')

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-4.col-8.order-2.order-lg-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/temas/t2/t2_21.svg', alt='')
          .col-lg-7.order-1.order-lg-2.ps-5.ps-lg-2.position-relative
            .cont.ps-4
              .numb(data-number="08")
              h4 Presentación
              p Cuide la presentación de su video. No solo es la narración del procedimiento lo que debe cuidar, también debe tener en orden sus imágenes o las capturas de pantalla que va presentando en el transcurso.

        .row.justify-content-center.align-items-center.pt-5
          .col-lg-7.mb-4.mb-lg-0.ps-5.ps-lg-2.position-relative
            .cont
              .numb(data-number="09")
              h4 Iluminiación
              p.mb-0 Verifique la iluminación de su entorno. En caso de que sus videotutoriales no sean grabaciones de pantallas y tenga que grabar los pasos de algún procedimiento, consiga un espacio para grabar con la iluminación correcta.           
          .col-lg-4.col-8
            figure
              img(src='@/assets/curso/temas/t2/t2_22.svg', alt='')

    .cajon.cjn--yellow.p-4.mb-4(data-aos="zoom-in")
      p.mb-0 Una vez se tiene conocimiento sobre cómo realizar un videotutorial es importante identificar en dónde se puede realizar.  Por costos en licencias, facilidad de uso en diferentes plataformas de sistemas operativos, cantidad de formatos manejados para exportar un video y una comunidad grande de usuarios que comparten para edición de sus archivos de videos, los mejores programas para hacer estos videos son:

    SlyderF.cstmSlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in")
      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_23.png", alt="alt").img90.m-auto               
        p.text-center OBS Studio 

      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_24.png", alt="alt").img90.m-auto               
        p.text-center Wondershare Filmora 

      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_25.png", alt="alt").img90.m-auto               
        p.text-center Jing 

      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_26.png", alt="alt").img90.m-auto               
        p.text-center Shotcut

      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_27.png", alt="alt").img90.m-auto               
        p.text-center ApowerREC   

      .crd--gray00.brd--rad_02.shadow.p-4        
        figure.mb-4
          img(src="@/assets/curso/temas/t2/t2_28.png", alt="alt").img90.m-auto               
        p.text-center Camptasia         




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
