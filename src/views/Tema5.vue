<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Identificación de los recipientes, puntos de generación de residuos y ECOMAPA

    
    figure.mb-4(data-aos="fade")
      img(src='@/assets/curso/temas/tema7/img.png', alt='')

    p.mb-5(data-aos="fade") Se debe establecer la composición, cantidad, características y calidad de los residuos especiales, peligrosos y no peligrosos que se generan en la organización, por medio de una caracterización y aforo de acuerdo con alguna de las metodologías existentes para este fin.   

    

    h3.subt.text-white.mb-4(data-aos="fade") Tipo de residuos para la separación en la fuente

    p.mb-4 Mediante la siguiente tabla, se tendrá noción de los residuos que comúnmente se generan y se orienta sobre qué se puede hacer con ellos.

    //.row.justify-content-center
      .col-lg-8
        .titulo-sexto.color-secundario.mb-4(data-aos="fade")
          p.mb-0 #[b Tabla 1] Tipos de residuos
        .tabla-a.tema7.mb-5(data-aos="fade-down") 
          table
            caption.bg-gray.mt-2 
              p.mb-0 Nota. Gestión Ambiental Residuos sólidos Guía para la separación en la fuente.  ICONTEC (2009).
            thead
              tr.bg-blue2
                th Sector
                th Tipo de residuo
                th Color
            tbody.bg-white    
              tr
                td(rowspan="3") Doméstico
                td Aprovechables
                td Blanco
              tr 
                td No aprovechables
                td Negro
              tr
                td Orgánicos biodegradables
                td Verde
              tr
                td(rowspan="7") Industrial, comercial institucional y de servicios
                td Cartón y papel
                td Gris
              tr
                td Plásticos
                td Azul 
              tr
                td Vidrio
                td Blanco
              tr
                td Orgánicos
                td Crema
              tr
                td Residuos Metálicos
                td Café oscuro
              tr
                td Madera
                td Naranja
              tr
                td Ordinarios
                td Verde
              tr
                td(colspan="3") Nota1: Se recomienda que cada generador establezca un código de colores particular para aquellos residuos no incluidos en la tabla.
                  p.mb-0 Nota2: Se recomienda consultar la legislación local vigente para verificar si existe algún código de colores establecido por la autoridad competente.
                  p.mb-0 Nota3: Para residuos peligrosos se establecerá el código de colores e iconos en la guía para residuos peligrosos.
                  p.mb-0 Nota4: Los colores establecidos en la tabla obedecen a la normativa aplicable. 


    p.mb-4(data-aos="fade") Para dar respuesta a la pirámide de jerarquización de la gestión de residuos, es importante identificar en el diagnóstico, qué prácticas y actividades aportan a la prevención y minimización de residuos en la organización, se debe tener en cuenta la siguiente información:

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-down")
      .col-md-3.mb-4
        .bg-green4.tarjeta.p-4.h-366.d-flex.align-items-center
          .row.justify-content-center
            .col-md-5
              img(src='@/assets/curso/temas/tema7/tarj-ico1.svg' alt='')
            p.text-center La adopción de buenas prácticas, la optimización de los procesos, el cambio a tecnologías limpias, la sustitución de materias primas y la modificación de productos.     
      .col-md-3.mb-4
        .bg-green4.tarjeta.p-4.h-366.d-flex.align-items-center
          .row.justify-content-center
            .col-md-5
              img(src='@/assets/curso/temas/tema7/tarj-ico2.svg' alt='')
            p.text-center La reutilización de elementos que se generan en los procesos de la organización.
      .col-md-3.mb-4
        .bg-green4.tarjeta.p-4.h-366.d-flex.align-items-center
          .row.justify-content-center
            .col-md-5
              img(src='@/assets/curso/temas/tema7/tarj-ico3.svg' alt='')
            p.text-center Igualmente, el reciclaje de materiales, aprovechamiento de subproductos utilizándolos como materias primas dentro del mismo proceso productivo o dentro de otro.
      .col-md-3.mb-4
        .bg-green4.tarjeta.p-4.h-366.d-flex.align-items-center
          .row.justify-content-center
            .col-md-5
              img(src='@/assets/curso/temas/tema7/tarj-ico4.svg' alt='')
            p.text-center La utilización de una menor cantidad de empaques, solicitando al proveedor la entrega de productos sin envolturas innecesarias, el empleo de elementos que sean susceptibles de aprovechamiento para reemplazar el uso de aquellos que no lo son.


    p.mb-4(data-aos="fade") Se debe determinar si en la organización se realiza separación en la fuente, si es así, tener en cuenta aspectos como: 

    .row.justify-content-center.align-items-center.mb-4
      .col-md-2.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema7/ico-7-3.svg', alt='')
      .col-md-10.mb-4(data-aos="fade-left")
        ul.lista-ul--color.color-primario.fa-ul
          li 
            i.fas.fa-check
            | Tipo de residuos que se separan.
          li 
            i.fas.fa-check
            | Existencia y cantidad de recipientes adecuados (capacidad, código de colores, entre otros).
          li 
            i.fas.fa-check
            | Ubicación estratégica dentro de la organización y distribución por zonas. 
          li 
            i.fas.fa-check
            | Calidad de la separación.

    .row.fondo-blue.align-items-center.py-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .col-md-12
            h3.subt.text-white.mb-4(data-aos="fade") Identificación de recipientes

          .row.align-items-center  
            .col-md-6.mb-4(data-aos="fade-right")
              p La separación en la fuente es la base fundamental de la adecuada gestión de residuos y consiste en la separación inicial de manera selectiva de los residuos procedentes de cada uno de los centros generadores de la organización, iniciándose una cadena de actividades y procesos cuya efectividad depende de la adecuada clasificación de los residuos.  
              p.bg-green5.p-4 El diagnóstico permite definir el tipo y cantidad de recipientes que se requieren para la adecuada separación de los residuos en todas las áreas de la organización. Los recipientes utilizados preferiblemente deben cumplir con el color correspondiente a la clase de residuos que se va a depositar en ellos y que se denomina Código de Colores. Además, deben ser visibles y estar ubicados estratégicamente en las instalaciones de la organización; en caso de que los recipientes que posee la organización no cumplan con el Código de Colores pueden pintarse, emplear cintas adhesivas visibles o utilizar el fondo del rótulo para establecer el color correspondiente al tipo de residuo mientras realiza la correspondiente compra del recipiente. 
            .col-md-6.mb-4(data-aos="fade-left")
              figure
                img(src='@/assets/curso/temas/tema7/img2.png', alt='')

          .row.align-items-center  
            .col-md-5.mb-4(data-aos="fade-right")
              figure
                img(src='@/assets/curso/temas/tema7/img3.png', alt='')
            .col-md-7.mb-4(data-aos="fade-left")
              p Para cumplir con el Código de Colores no se requiere de bolsas del mismo color del recipiente, estas pueden ser reemplazadas por bolsas transparentes o de color, teniendo cuidado en el momento de recolección selectiva de cada residuo. 
              p A partir del 1 de enero de 2021, los municipios y distritos deberán implementar el código de colores para la presentación de los residuos sólidos en bolsas u otros recipientes, en el marco de los programas de aprovechamiento de residuos del servicio público de aseo, de acuerdo con lo establecido en los Planes de Gestión Integral de Residuos Sólidos (PGIRS).
              
          .col-md-10.mb-4
            .titulo-sexto.color-secundario.mb-4(data-aos="fade")
              p.mb-0 #[b Figura 4.] Código de colores obligatorio a partir del año 2021 para entregar al servicio público de aseo en todo el territorio nacional
            figure(data-aos="fade-down")
              img(src='@/assets/curso/temas/tema7/figura6.png', alt='Código de colores obligatorio a partir del año 2021 para entregar al servicio público de aseo en todo el territorio nacional')
              figcaption.bg-white
                p.mb-0 Nota. Gobierno unifica el código de colores para la separación de residuos en la fuente a nivel nacional. Ministerio de Ambiente (2020).  

          p(data-aos="fade") Esta norma es obligatoria a nivel nacional para los residuos que se entreguen al servicio de aseo, este código de colores deberá ser adoptado por los municipios o distritos que adelanten programas de aprovechamiento conforme a sus Planes de Gestión Integral de Residuos Sólidos (PGIRS) y permitirá simplificar la separación en la fuente en los hogares, preparando al país para el desarrollo e implementación de nuevos esquemas de aprovechamiento, en dónde se unifiquen los esfuerzos entre todos los actores de la cadena.

    
    h4.t-green.mb-4(data-aos="fade") Código de colores propuesto por la GTC 24

    p.mb-5(data-aos="fade") Para las entidades de salud si es obligatorio el código de colores que delegue el Manual para la Gestión Integral de Residuos Generados en la Atención en Salud y otras actividades, y se dictan otras disposiciones:

    .titulo-sexto.color-secundario.mb-4(data-aos="fade")
      p.mb-0 #[b Figura 5.] Código de colores propuesto por la GTC 24
    
    figure(data-aos="fade-down").mb-5
      img(src='@/assets/curso/temas/tema7/figura7.png', alt='Código de colores propuesto por la GTC 24')


    .row.fondo-green.align-items-center.py-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center
          
          .col-md-12
            p.mb-4(data-aos="fade") Los tipos y capacidades de los recipientes, dependen de las características y tipos de residuos, el tipo y frecuencia del sistema de recolección y del espacio disponible para ellos.

          .row.align-items-center  
            .col-md-4.mb-4(data-aos="fade-right")
              figure
                img(src='@/assets/curso/temas/tema7/img4.png', alt='')
            .col-md-8.mb-4(data-aos="fade-left")
              p.mb-4 Frecuentemente se emplean bolsas, contenedores, canecas, cajas, entre otros. Sin embargo, según la norma GTC 24- Gestión Ambiental Residuos sólidos Guía para la separación en la fuente del 2009, se debe tener en cuenta lo siguiente, para su selección:
              ul.lista-ul--color.fa-ul
                li.mb-4
                  i.fas.fa-check
                  | A nivel doméstico se espera que los recipientes sean de material impermeable, liviano y resistente, de fácil cargue, de tal forma que facilite su transporte y se reduzca el impacto sobre el ambiente y la salud humana.
                li.mb-4 
                  i.fas.fa-check
                  | Los recipientes de carácter retornable deberían permitir su fácil limpieza.
                li.mb-4 
                  i.fas.fa-check
                  | Los recipientes que se empleen para presentar los residuos para recolección deberían evitar el contacto de los residuos con el entorno y con las personas encargadas de dicha recolección.
                li.mb-4 
                  i.fas.fa-check
                  | Los recipientes tanto desechables como retornables deberían: proporcionar seguridad e higiene, permitir el aislamiento de los residuos con el entorno, tener una capacidad y volumen proporcional al peso, volumen y características de los residuos contenidos, ser de material resistente, preferiblemente reciclable, reutilizable o ambos y facilitar su cierre o amarre.
                li.mb-4 
                  i.fas.fa-check
                  | En instalaciones multiusuario, comerciales e industriales pueden emplearse grandes contenedores de acopio.


          p.mb-4(data-aos="fade") Los recipientes para residuos infecciosos deben ser del tipo tapa y pedal y se identifican sus canecas con el logo de infeccioso, ver figura, si es químico algunas veces colocan el logo de una calavera y dicen el tipo de químico que se envasa. 

          .col-md-6
            .titulo-sexto.color-secundario.mb-4(data-aos="fade")
              p.mb-0 #[b Figura 6.] Recipiente para residuos infecciosos
            figure(data-aos="fade-down")
              img(src='@/assets/curso/temas/tema7/figura8.png', alt='Recipiente para residuos infecciosos')

          p Los recipientes para residuos peligrosos obligatoriamente deben tener tapa, con buen ajuste, bordes redondeados y boca ancha para facilitar su vaciado. Construidos en forma tal que, estando cerrados o tapados, no permitan la entrada de agua, insectos o roedores, ni el escape de líquidos por sus paredes o por el fondo.
          p Los residuos reciclables usan el logo de reciclaje en los recipientes y para ordinarios usan algunas veces el logo circular, pero no es necesario el logo en ordinarios (Alcaldía Santiago de Cali,  2015).


    h3.t-green.mb-4(data-aos="fade") Bolsas

    .row.justify-content-center.align-items-center.mb-4
      .col-md-8.mb-4(data-aos="fade-right")
        p La resistencia de las bolsas debe soportar la tensión ejercida por los residuos contenidos y por su manipulación. El material plástico de las bolsas para residuos infecciosos, debe ser polietileno de alta densidad, o el material que se determine necesario para la desactivación o el tratamiento de estos residuos, la resistencia de cada una de las bolsas no debe ser inferior a 20 kg.
        p Los colores de bolsas seguirán el código establecido por la organización y/o entidad territorial, serán de alta densidad y calibre mínimo de 1.4 para bolsas pequeñas y de 1.6 milésimas de pulgada para bolsas grandes, suficiente para evitar el derrame durante el almacenamiento en el lugar de generación, recolección, movimiento interno, almacenamiento central y disposición final de los residuos que contengan. (Universidad Industrial de Santander, 2013)
      .col-md-4.mb-4(data-aos="fade-left")
        figure(data-aos="fade-down")
          img(src='@/assets/curso/temas/tema7/figura9.png', alt='Bolsas rojas')


    .row.fondo-blue.align-items-center.py-5.pb-4.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .col-md-12
            h3.t-green.mb-4(data-aos="fade") Recipientes para residuos Cortopunzantes
          
          .row.justify-content-center.align-items-center
            .col-md-7.mb-4(data-aos="fade-right")
              p Los recipientes para residuos cortopunzantes son desechables y deben tener las siguientes características:
              ul.lista-ul--color.ps-2.fa-ul
                li
                  i.fas.fa-check
                  | Rígidos, en polipropileno de alta densidad u otro polímero que no contenga P.V.C. 
                li
                  i.fas.fa-check
                  | Resistentes a ruptura y perforación por elementos cortopunzantes.
                li
                  i.fas.fa-check
                  | Con tapa ajustable o de rosca, de boca angosta, de tal forma que al cerrarse quede completamente hermético. Rotulados de acuerdo con la clase de residuo.
                li
                  i.fas.fa-check
                  | Livianos y de capacidad no mayor a 2 litros.
                li
                  i.fas.fa-check
                  | Ser resistentes, desechables y de paredes gruesa.
            .col-md-5.mb-4(data-aos="fade-left")
              .titulo-sexto.color-secundario(data-aos="fade")
                p.mb-0 #[b Figura 7.] Recipiente rígido para corto punzantes
              figure(data-aos="fade-down")
                img(src='@/assets/curso/temas/tema7/figura10.png', alt='Recipiente rígido para corto punzantes')


    
    h3.subt.text-white.mb-4(data-aos="fade") Rotulación

    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.mb-4(data-aos="fade-right")
        figure(data-aos="fade-down")
          img(src='@/assets/curso/temas/tema7/figura11.png', alt='Rotulación')
      .col-md-9.mb-4(data-aos="fade-left")
        p Los recipientes deben ir rotulados con el nombre del generador, departamento, área o servicio al que pertenecen, el nombre del residuo que contienen, fecha de recolección y el símbolo de peligrosidad si es residuo peligroso.
        p Para la rotulación de los residuos peligrosos se realiza acorde a la normativa ICONTEC (2005) Norma técnica colombiana NTC1692 Transporte de mercancías peligrosas definiciones, clasificación, marcado, etiquetado y rotulado y el decreto 1609 de 2002 "Por el cual se reglamenta el manejo y transporte terrestre automotor de mercancías peligrosas por carretera".
        p.bg-green.p-4 El etiquetado tiene como objetivo principal identificar el residuo peligroso y reconocer la naturaleza del peligro que representa, alertando a las personas involucradas en el transporte o manejo sobre las medidas de precaución y prohibiciones. La etiqueta que se utilizara para la identificación de los residuos puede ser de diferentes estilos. (Universidad de Cádiz, 2016)


    h3.subt.text-white.mb-4(data-aos="fade") Norma NFPA 
      em (National Fire Protection Association)
    p.mb-4(data-aos="fade") En residuos peligrosos pueden usarse diferentes tipos de pictogramas como el del rombo NFPA, ver figura.
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-4
        figure
          img.px-md-3(src='@/assets/curso/temas/tema7/figura12.png', alt='NFPA')


    h3.subt.text-white.mb-4(data-aos="fade") Sistema Globalmente Armonizado de clasificación y etiquetado de productos - SGA
    p.mb-4(data-aos="fade") Pictogramas como los del sistema globalmente armonizado.
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-4
        figure
          img(src='@/assets/curso/temas/tema7/figura13.png', alt='SGA')       

    .row.fondo-gray.align-items-center.py-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center(data-aos="fade-down")

          h4.text-center.mb-4 Pictogramas
          .row.text-center
            .col-md-4
              .bg-1.py-3.px-2.h-71.d-flex.align-items-center.justify-content-center
                h5.text-white.mb-0 Rojo: representa los peligros físicos.
            .col-md-4
              .bg-2.py-3.px-2.h-71.d-flex.align-items-center.justify-content-center
                h5.text-white.mb-0 Verde: representa los peligros para la salud.
            .col-md-4
              .bg-3.py-3.px-2.h-71.d-flex.align-items-center.justify-content-center
                h5.text-white.mb-0 Azul: representa los peligros para el medio ambiente.
    
 

    h3.subt.text-white.mb-4(data-aos="fade") Norma técnica NTC Colombiana 1692.
    p.mb-4(data-aos="fade") A continuación, se encuentran los pictogramas más usados de acuerdo con la norma NTC1692. 

    .row.justify-content-center.mb-5
      .col-md-9(data-aos="fade-down")
        .tabla-a.tema5
          table
            thead
              tr.bg-green3.text-center
                th CLASE
                th ROTULO/ ETIQUETA
                th DIVISIÓN
            tbody.bg-gray
              tr   
                td.fw-bold 1. EXPLOSIVO
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img.png', alt='EXPLOSIVO' style="width:90px;")
                td  
                  ol.lista-ol.fa-ul
                    li
                      span 1.1
                      | Sustancia y Objetos que presentan un riesgo de Explosión en masa.
                    li
                      span 1.2
                      | Sustancias y objetos que presentan un riesgo de proyección sin riesgo de explosión en masa
                    li
                      span 1.3
                      | Sustancias y objetos que presenta un riesgo de incendio y un riesgo menor de explosión u un riesgo menor de proyección, o ambos, pero no un grado de Explosión en masa.
                    li
                      span 1.4
                      | Sustancias y objetos que presentan un riesgo apreciable.
                    li
                      span 1.5
                      | Sustancias muy insensibles; que presentan un riesgo de explosión en masa.
                    li
                      span 1.6
                      | Objetos sumamente insensibles que no presentan riesgo de explosión en masa.
              tr   
                td.fw-bold 2. GASES
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img2.png', alt='GASES' style="width:90px;")
                td  
                  ol.lista-ol.fa-ul
                    li
                      span 2.1
                      | Gases inflamables.
                    li
                      span 2.2
                      | Gases no inflamables, no tóxicos.
                    li
                      span 2.3
                      | Gases tóxicos.
              tr   
                td.fw-bold 3 LÍQUIDOS INFLAMABLES Y LÍQUIDOS COMBUSTIBLE
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img3.png', alt='ÍQUIDOS INFLAMABLES Y LÍQUIDOS COMBUSTIBLE' style="width:90px;")
                td  
              tr   
                td.fw-bold 4 SÓLIDOS INFLAMABLES
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img4.png', alt='SÓLIDOS INFLAMABLES' style="width:90px;")
                td  
                  ol.lista-ol.fa-ul
                    li
                      span 4.1
                      | Sólido Inflamable, sustancias con reacción espontánea y sólidos explosivos insensibilizados.
                    li
                      span 4.2
                      | Sustancias que pueden experimentar combustión espontánea.
                    li
                      span 4.3
                      | Sustancias que, en contacto con el agua, desprenden gases inflamables.
              tr   
                td.fw-bold 2. OXIDANTES Y PERÓXIDOS ORGÁNICOS
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img5.png', alt='OXIDANTES Y PERÓXIDOS ORGÁNICOS' style="width:90px;")
                td  
                  ol.lista-ol.fa-ul
                    li
                      span 5.1
                      | Sustancias comburentes.
                    li
                      span 5.2
                      | Peróxidos orgánico.
              tr   
                td.fw-bold SUSTANCIA TOXICAS
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img6.png', alt='SUSTANCIA TOXICAS' style="width:90px;")
                td  
                  ol.lista-ol.fa-ul
                    li
                      span 6.1
                      | Sustancias Tóxicas
                    li
                      span 6.2
                      | Sustancia infecciosa
              tr 
                td.fw-bold 4. SUSTANCIAS RADIACTIVAS
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img7.png', alt='SUSTANCIAS RADIACTIVAS' style="width:90px;")
                td  
              tr 
                td.fw-bold 5. SUSTANCIAS CORROSIVAS
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img8.png', alt='SUSTANCIAS CORROSIVAS' style="width:90px;")
                td 
              tr    
                td.fw-bold 6. SUSTANCIAS PELIGROSAS MISCELÁNEAS
                td 
                  img.m-auto(src='@/assets/curso/temas/tema5/tabla-img9.png', alt='SUSTANCIAS PELIGROSAS MISCELÁNEAS' style="width:90px;")
                td 

    
    
    p.mb-4(data-aos="fade") Para los residuos no peligrosos su rotulación es colocar el nombre del residuo, quien lo genera , fecha de recolección y el logo de reciclaje si es para reciclar y si es ordinario o común no se requiere de logo solo de la identificación del residuo, algunas veces en los rótulos se coloca el peso o volumen del residuo si este no está en el rotulo debe estar en los registros de gestión de residuos sea en el registro de recolección o de almacenamiento de residuos o de entrega de residuos para así llevar los indicadores de gestión de generación de residuos.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10
        .titulo-sexto.color-secundario
          p.mb-0 #[b Figura 8.] Rotulado de la universidad los andes ejemplo de residuos peligrosos
        figure
          img(src='@/assets/curso/temas/tema7/figura17.svg', alt='Rotulado de la universidad los andes ejemplo de residuos peligrosos')
          figcaption.bg-gray
            p.mb-0 Nota. Tomado de Procedimiento para la gestión y disposición de residuos sólidos y peligrosos (2012).


    
    h4.subt.text-white.mb-4(data-aos="fade") Puntos de generación de residuos y ECOMAPA

    p.mb-5(data-aos="fade") Para identificar los residuos es importante recorrer la organización y detectar los puntos de generación de residuos, hacerse las preguntas que tipo de residuos se detecta en cada una de las etapas de producción y/o procesos en la organización, la mayoría de las veces se identifica por medio de la detección de los puntos ecológicos, pero también de las áreas en donde se generen residuos. Para esto es importante realizar una caracterización cualitativa por tanto se deberá definir por áreas el tipo de residuo que se genera. Para realizar esta identificación se puede facilitar por medio de un eco balance de proceso.


    h4.subt.text-white.mb-4(data-aos="fade") ECOMAPA
    p(data-aos="fade") Por medio de un ECOMAPA, se realiza la Identificación de aspectos ambientales que se generan en la organización entre estos se puede identificar la generación de los residuos por medio de pictogramas en el plano, mediante el empleo de un ecomapa como herramienta de diagnóstico.
    p.mb-4(data-aos="fade") Posteriormente se realizará una caracterización cuantitativa que se explica en el posterior tema para realizar metodología de cuantificación de estos.



    



</template>

<script>
export default {
  name: 'Tema5',
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
