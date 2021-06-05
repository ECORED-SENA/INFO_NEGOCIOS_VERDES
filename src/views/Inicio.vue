<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Negocios Verdes
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Negocios Verdes 
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 621102 
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en semanas: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto Virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Requisito de ingreso: 
                .banner-principal__datos__item__texto
                  ul.lista-ul
                    li
                      i.lista-ul__vineta
                      p Nivel académico adecuado para caracterizar al aspirante de acuerdo con el perfil de egreso: media académica, grado 11
                    li
                      i.lista-ul__vineta
                      p Requiere certificación académica.
                    li
                      i.lista-ul__vineta
                      p No requiere formación para el trabajo y desarrollo humano.
                    li
                      i.lista-ul__vineta
                      p No requiere experiencia laboral. 
                    li
                      i.lista-ul__vineta
                      p Edad mínima definida en la ley: 16 años.
                    li
                      i.lista-ul__vineta
                      p Requisitos adicionales:
                      ul.lista-ul
                        li
                          i.lista-ul__vineta
                          p Presentar resultado de la prueba o examen de estado de la educación media. 
                        li
                          i.lista-ul__vineta
                          p Título de bachiller o su equivalente validación aprobada por la entidad competente
                    li
                      i.lista-ul__vineta
                      p El aspirante debe tener interés relacionado con el emprendimiento; Preferencia por el trabajo en equipo, liderazgo y comunicación asertiva, vocación de servicio; Preferencia por trabajos que exigen el cumplimiento de normas, procedimientos, estándares, protocolos; Interés en la formación técnica aplicada a la industria; Gusto por actividades laborales de incentivar el desarrollo sostenible, disposición para comercializar productos con enfoque ambiental; Disposición para respetar jerarquías y acatar órdenes; Preferencia por el trabajo operativo, interés por la investigación de productos y servicios verdes, motivación para la organización de actividades ambientales.

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/vQevR3qzy14" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Las estrategias del Biocomercio se han desarrollado desde hace 17 años a partir de los acuerdos de la Conferencia Mundial de Desarrollo Sostenible (Sudáfrica, 2002) y Conferencia de las Naciones Unidas sobre comercio y desarrollo (Biotrade). Su propósito es definir cómo se deben transformar los procesos productivos para asegurar el desarrollo sostenible a partir de un conjunto de principios y criterios que responden y apoyan los objetivos de los convenios de diversidad biológica internacional, abordando una gran variedad de problemáticas relevantes como: la erradicación de la pobreza, el desarrollo social y económico, la protección del medio ambiente, el calentamiento global, los objetivos de desarrollo del milenio, entre muchos otros.
      br
      br
      |Colombia, no es ajena a estos procesos, es por esto que el SENA cumpliendo la función que le compete al estado de formar al sector productivo, desarrolló el programa Negocios Verdes, con el fin de desarrollar negocios innovadores y competitivos, basados en el aprovechamiento sostenible de la biodiversidad nativa, a través de lineamientos claros que promuevan principios de biocomercio (Minambiente, 2014).
      br
      br
      |El SENA ofrece este programa con todos los elementos de formación profesional, sociales, tecnológicos y culturales, metodologías de aprendizaje innovadoras, acceso a tecnologías de última generación, estructurado sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidarios y emprendedores, con manejo de conceptos y normativa ambiental, investigación de mercados y unidades productivas reales, cadena de suministro, estrategias de mercadeo, desarrollo de productos y servicios y, la negociación de los mismos, que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias, cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo del país.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Los negocios verdes, están comprendidos por actividades económicas, en las que se ofertan bienes o servicios, que originan impacto ambiental positivo y subvencionan a su conservación, como capital natural, que soporta el desarrollo de los territorios (Ministerio de medio ambiente y desarrollo sostenible, 2014)”.
      br
      br
      |Colombia, el segundo país más biodiverso y una de las doce naciones más megadiversas de la tierra (Colciencias , 2019) tiene una ventaja comparativa para desarrollar negocios internacionales a partir de esta riqueza, que suscite el bienestar y desarrollo, coadyuve con la subsistencia de la biodiversidad (UNCTAD, 2010), a la vez que pueda ser generador de ingresos a la población con pobreza monetaria (para el año 2018 fue del 27% y la pobreza extrema fue de 7,2% en el total nacional (DANE, 2018)), tal como ha quedado demostrado con los 1.414 negocios verdes, confirmados por el Ministerio de Ambiente y desarrollo sostenible, que aportan a la empleabilidad en el país, con una cifra de ocupación de más de 20.000 personas en el año 2019 (Minambiente, 2019).
      br
      br
      |El SENA, atendiendo a su rol, como uno de los actores sectoriales en generación de conocimiento, innovación y valor agregado del PRNB (Programa nacional de biocomercio sostenible) en articulación con las agendas de competitividad, productividad e innovación (Mincit), presenta la Tecnología en Negocios verdes, dando alcance al objetivo general del Programa Nacional de Biocomercio Sostenible, consistente en desarrollar negocios innovadores y competitivos, basados en el aprovechamiento sostenible de la biodiversidad nativa, a través de lineamientos claros que promuevan principios de biocomercio (Minambiente, 2014)

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 3. Competencias<br> a desarrollar

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | Estructurar sistema de gestión ambiental según procedimiento
      li
        i.lista-ul__vineta
        | Categorizar negocios sostenibles según criterios verdes normativa.
      li
        i.lista-ul__vineta
        | Formular el plan según objetivos y metodologías.
      li
        i.lista-ul__vineta
        | Planear la integración de las cadenas de suministro según mejores prácticas y modelos de gestión.
      li
        i.lista-ul__vineta
        | Negociar productos o servicios de acuerdo con objetivos estratégicos.
      li
        i.lista-ul__vineta
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li
        i.lista-ul__vineta
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos productivo y social.
      li
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente. 
      li
        i.lista-ul__vineta
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
      li
        i.lista-ul__vineta
        | Orientar investigación formativa según referentes técnicos.
      li
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li
        i.lista-ul__vineta
        | Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social. 
      li
        i.lista-ul__vineta
        | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de referencia para las lenguas.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 4. Perfil<br> de ingreso
    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | Nivel académico adecuado para caracterizar al aspirante de acuerdo con el perfil de egreso: media académica, grado 11
      li
        i.lista-ul__vineta
        | Requiere certificación académica.
      li
        i.lista-ul__vineta
        | No requiere formación para el trabajo y desarrollo humano.
      li
        i.lista-ul__vineta
        | No requiere experiencia laboral. 
      li
        i.lista-ul__vineta
        | Edad mínima definida en la ley: 16 años.
      li
        i.lista-ul__vineta
        | Requisitos adicionales:
        ul.lista-ul
          li
            i.lista-ul__vineta
            | Presentar resultado de la prueba o examen de estado de la educación media. 
          li
            i.lista-ul__vineta
            | Título de bachiller o su equivalente validación aprobada por la entidad competente
      li
        i.lista-ul__vineta
        p El aspirante debe tener interés relacionado con el emprendimiento; Preferencia por el trabajo en equipo, liderazgo y comunicación asertiva, vocación de servicio; Preferencia por trabajos que exigen el cumplimiento de normas, procedimientos, estándares, protocolos; Interés en la formación técnica aplicada a la industria; Gusto por actividades laborales de incentivar el desarrollo sostenible, disposición para comercializar productos con enfoque ambiental; Disposición para respetar jerarquías y acatar órdenes; Preferencia por el trabajo operativo, interés por la investigación de productos y servicios verdes, motivación para la organización de actividades ambientales.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 5. Perfil<br>de egreso
    p El egresado del programa Tecnología en negocios verdes es un talento humano formado integralmente bajo el enfoque por competencias con capacidad de determinar las oportunidades de mercado, recopilar información para realizar análisis de tendencias del mercado verde y negociar productos con criterios de sostenibilidad (económica, social, ambiental); con un alto sentido de responsabilidad social-empresarial potenciando la calidad del talento humano, el trabajo en equipo y liderazgo. Podrá desempeñarse en empresas comercialización de bienes y servicios de la biodiversidad, en cargos de coordinador de mercadeo o supervisor de ventas.
      br
      br
      |Los principales productos del trabajo del egresado son:

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | Informe de caracterización del entorno ambiental del negocio.
      li
        i.lista-ul__vineta
        | Categorización del negocio verde de acuerdo al marco referencial.
      li
        i.lista-ul__vineta
        | Propuesta de condiciones y características de la cadena de suministro.
      li
        i.lista-ul__vineta
        | Plan de comercialización de productos verdes.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 6. Estrategia<br>metodológica
    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | El instructor - Tutor
      li
        i.lista-ul__vineta
        | El entorno
      li
        i.lista-ul__vineta
        | las TIC
      li
        i.lista-ul__vineta
        | El trabajo colaborativo

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 Créditos

    Creditos

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({}),
}
</script>

<style lang="sass"></style>
