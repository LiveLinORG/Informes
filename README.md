
# Contenido

## Tabla de contenidos
  - [1. Student Outcome Capítulo I: Introducción](#1-student-outcome-cap%C3%ADtulo-i-introducci%C3%B3n)
  - [2. Capítulo II: Requirements Elicitation & Analysis](#2-cap%C3%ADtulo-ii-requirements-elicitation--analysis)
  - [3. Capítulo III: Requirements Specification](#3-cap%C3%ADtulo-iii-requirements-specification)
  - [4. Capítulo IV: Product Design](#4-cap%C3%ADtulo-iv-product-design)
  - [5. Capítulo V: Product Implementation, Validation & Deployment](#5-cap%C3%ADtulo-v-product-implementation-validation--deployment)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliograf%C3%ADa)
- [Anexos](#anexos)

### 1. Student Outcome Capítulo I: Introducción

- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup
    - LiveLin Es una Startup orientada a la creación de aplicaciones web innovadoras enfocadas en solucionar problemas específicos pero comunes en la sociedad, somos un grupo de estudiantes de la Universidad De Ciencias Aplicadas (UPC) la mayoría cursamos el Quinto Ciclo de la carrera de Ingeniería de Software. Procuramos un ambiente sano y divertido para propiciar las ideas innovadoras tal y como el lema de nuestra alma máter. 
  - 1.1.2. Perfiles de integrantes del equipo

| Integrante                        | Descripción del Perfil                                                                                           |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
| Adrián Enrique Jesús Palma Obispo | Curso la carrera de Ingeniería de Software de 5to Ciclo. Experiencia trabajando en equipo, aportando en diversas áreas y ayudando en tecnologías. Capacidad para aprender rápido. Curioso y puntual. |
| Erick Joaquin Palomino Santa Cruz | Curso el quinto ciclo de la carrera de Ingeneria de Software. Me gusta aprender cosas nuevas y trabajar grupalmente para lograr una meta. |
| Joaquín Alonso Carbajal Pozzo     | Actualmente curso la carrera de Ingeniería de Software. Me gusta aprender sobre nuevas tecnologías y ponerlas en práctica lo antes posible. |
| Piero Alonso Martinez Villanueva  | Me encuentro cursando el sexto ciclo de la carrera de Ingeniería de Software. Poseo experiencia en trabajo en equipo, aportando ideas innovadoras y soluciones eficaces. Me gusta aprender sobre nuevas tecnologías. Soy paciente y perseverante. |
| Renzo Cesar Silva Morales         | En la actualidad me encuentro en el 5to Ciclo de la carrera de Ingeniería de Software. Me gusta mantenerme actualizado sobre el mundo de la tecnología. |



- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática

    #### ¿Cuál es el problema?
    El problema que pudimos identificar es que no todos los alumnos tiene la misma visibilidad desde todas los asientos del aula. Por lo que en ocasiones puede traerles porblemas para prestar atención o para entender de forma efectiva la clase. Además, este problema se ve intencificado en aquellos casos en el que el profesor no tiene un buen volumen de voz, viéndose perjudicados aquellos alumnos que se encuentran en los últimos asientos del aula.
    
    #### ¿Cuándo sucede el problema?
    Este problema toma lugar durante el dictado de clases presenciales. Es debido al tamaño del aula que no todos los alumnos tienen la misma visibilidad al momento de atender a sus clases.
    
    #### ¿Dónde sucede el problema?
    Como se mencionó con anterioridad, el problema ocurre dentro de las aulas de todas las instituciones educativas. Problema que se ve repotenciado en las aulas con mayor capacidad, puesto que el tamaño de la misma obliga a los alumnos a sentarse a una mayor distancia de la pizarra.
    
    #### ¿A quién se le presenta el problema? ¿Cuál es tu público objetivo?
    Dicho problema se le presenta a todos aquellos alumnos que tienen que llevar clases de forma presencial. Por lo que, nuestro público objetivo son estos mismo alumnos, además de los profesores y las mismas instituciones educativas. Los dos últimos también son considerados como público objetivo ya que se ven involucrados en el problema. Los profesores buscan que todos sus alumnos puedan entender de forma rápida y sencilla las clases que dictan, así como las instituciones buscan tener un mayor atractivo para aquellos futuros estudiantes.
    
    #### ¿Por qué sucede el problema? ¿Qué situación ocasiona el problema?
    La situación que ocasiona este problema es la dificultad de tener una única pantalla o pizarra donde se debe mostrar el contenido para toda la clase, por lo que termina habiendo problemas desde algunas perspectivas dentro del aula.
    
    #### ¿Cómo sucede el problema? ¿Cuáles son las precondiciones para que se presente el problema?
    Este problema sucede de forma involuntaria, se debe principalmente al diseño clásico de las aulas. Por lo mismo, es común ver este mismo problema replicado en una gran cantidad de instituciones educativas, véase universidades, colegios o institutos, a lo largo de nuestro país.
    Acerca de esto, Mónica Maldonado, Vícotor Sotomayor y Jorge Villagrasa, de la Universitat Politècnica de València mencionan que:
  
    > "El fenómeno de que los buenos estudiantes se encontrasen en las primeras filas, ocurría tanto si los propios estudiantes escogían sus asientos, como si, por el contrario, se les asignaba su localización de manera totalmente aleatoria" Maldonado et al. (2020).

    Lo que demuestra la relación directa de la ubicación del alumno y la calidad de aprendizaje que este mismo recibe, siendo distinto para cada alumno dentro del aula.
    
    #### ¿Cuánto impacto genera este problema? Representar datos estadísticos del segmento que tiene el problema.
    Dentro del mismo estudio mencionado anteriormente, se logró determinar que:
    
    > "Las notas son mucho más elevadas cuanto más hacia delante se sitúa el estudiante (con una diferencia de 2.4 puntos en actitud y 1.3 puntos en el examen final comparando la primera fila y la última)" Maldonado et al. (2020).

    Dicho que denota la disminución en las calificaciones tanto de actutud como de exámenes en aquellos alumnos que se encuentran más alejados de la pizarra.
    
  - 1.2.2. Lean UX Process.
    - 1.2.2.1. Lean UX Problem Statements.
      Nuestra solución de negocio surge a partir de una problemática que afecta a una gran cantidad de estudiantes, que es,la distancia que tienen dichos alumnos con respecto a la pizarra o al docente.
 
      Es esencial abordar este problema debido a que una de las principales causas de la disminución en el desempeño de los estudiantes, repercutiendo directamente en sus calificaciones finales. El desafío que buscamos enfrentar es poder aumentar la visibilidad de los alumnos, así como mejorar la comunicación entre estos y el profesor, proporcionando una herramienta útil tanto para el profesorado como para las diversas instituciones educativas.
      
    - 1.2.2.2. Lean UX Assumptions.
  
      **Bussines Outcomes:**
        * 1
    
      **Features:**
        * Inicio de sesión simple: NoteLive es una aplicación web accesible directamente desde un navegador, lo que elimina la necesidad de instalación de software adicional. Los usuarios pueden acceder fácilmente a la plataforma mediante un código único proporcionado por el profesor.
        * Interacción en Tiempo Real: Una vez que los alumnos ingresan al código de la sesión, pueden ver la presentación del profesor en tiempo real en sus dispositivos móviles. Esto les permite seguir el ritmo de la clase desde cualquier lugar en el aula.
        * Envío de Preguntas Anónimas: Los alumnos tienen la capacidad de enviar preguntas de forma anónima a través de la aplicación. Estas preguntas se vinculan automáticamente con la diapositiva relevante, lo que permite una referencia precisa durante la discusión posterior.
        * Destaque de Preguntas Relevantes: Para fomentar la participación y priorizar las preguntas más importantes, NoteLive incluye una función de "me gusta". Los alumnos pueden otorgar likes a las preguntas que consideren más relevantes, lo que las resalta en la pantalla para una fácil identificación por parte del profesor.
        * Integración con Presentaciones: Los profesores pueden vincular sus presentaciones de diapositivas a la plataforma, lo que permite una visualización sincronizada para todos los alumnos. Esto garantiza que todos los participantes estén en la misma página y facilita la discusión en tiempo real.
        * Exportación de Registro de Preguntas: Al finalizar la sesión, los alumnos tienen la opción de exportar un archivo detallado que contiene un registro de todas las preguntas formuladas durante la clase. Este archivo proporciona una valiosa herramienta de revisión para repasar el material discutido y las preguntas planteadas.
    
      **User Outcomes:**
        * 1
  
    - 1.2.2.3. Lean UX Hypothesis Statements.
    - 1.2.2.4. Lean UX Canvas.
- 1.3. Segmentos objetivo.
  
1. **Estudiantes Universitarios**:
   - Buscan herramientas que faciliten la interacción en el aula durante clases presenciales.
   - Valorizan la posibilidad de acceder a la plataforma sin necesidad de instalar software adicional.
   - Necesitan una forma de hacer preguntas de manera anónima para aclarar dudas sin temor a ser juzgados.
   - Quieren una plataforma que les permita seguir la presentación del profesor desde sus dispositivos móviles.
   
2. **Profesores y Educadores**:
   - Buscan una herramienta que facilite la interacción y participación de los alumnos durante las clases.
   - Valorizan la capacidad de integrar la plataforma con sus presentaciones de diapositivas.
   - Necesitan una forma de priorizar y responder a las preguntas más relevantes de los estudiantes.
   - Quieren una plataforma que les permita gestionar múltiples sesiones de manera eficiente.
   
3. **Instituciones Educativas y Empresas de Capacitación**:
   - Buscan una solución que facilite la interacción entre profesores y alumnos durante sesiones presenciales.
   - Valorizan la posibilidad de personalizar la plataforma según sus necesidades, incluyendo la opción de contar con cuentas premium para un mayor número de usuarios.
   - Necesitan una herramienta que garantice la seguridad y privacidad de los datos de los usuarios.
   - Quieren una plataforma que facilite la recopilación y revisión de preguntas formuladas durante las sesiones de clase.


### 2. Capítulo II: Requirements Elicitation & Analysis

- 2.1. Competidores.
   En el mercado de aplicaciones para la interacción en tiempo real durante sesiones de enseñanza, existen varios productos que compiten ofreciendo soluciones similares para profesores y alumnos. A continuación, se mencionan algunos de los competidores clave identificados:

	 **Zoom for Education:** Zoom for Education es una plataforma de videoconferencia popular, diseñada específicamente para entornos educativos. Ofrece herramientas como salas de reuniones virtuales, compartición de pantalla, pizarra virtual y chats en vivo. Además, cuenta con características de seguridad, como control de sala de espera y autenticación de usuarios, para proteger la privacidad de los estudiantes.

	 **Google Classroom:** Google Classroom es una plataforma de gestión del aprendizaje que permite a los profesores crear clases virtuales, asignar tareas, evaluar el trabajo de los alumnos y facilitar la comunicación entre estudiantes y profesores. La integración con otras herramientas de Google, como Google Drive y Google Meet, proporciona una experiencia educativa integrada y colaborativa. Google Classroom también ofrece funciones de seguimiento del progreso del alumno y retroalimentación personalizada.

	**Microsoft Teams for Education:** Microsoft Teams es una plataforma de colaboración que ofrece herramientas para la comunicación en tiempo real, la colaboración en documentos y la organización de equipos. La versión para educación de Microsoft Teams incluye características específicas para la enseñanza, como asignaciones integradas, cuadernos de clase de OneNote y la capacidad de realizar reuniones virtuales con estudiantes y profesores. Microsoft Teams for Education también ofrece integración con otras herramientas de Microsoft, como Office 365 y SharePoint.

	Estos competidores, al igual que NoteLive, se centran en ofrecer soluciones completas para la interacción en tiempo real durante clases, proporcionando una diversidad de herramientas y recursos para facilitar la comunicación, colaboración y aprendizaje entre profesores y alumnos. Cada plataforma presenta características únicas y ventajas competitivas, por lo que es esencial que los usuarios analicen sus necesidades y preferencias individuales al seleccionar la aplicación que más se ajuste a sus requerimientos.
- 2.2. Análisis competitivo.

  **Perfil de la Startup**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Origen           | Lima, Perú                            | San Jose, California, EE. UU.                         | Mountain View, California, EE. UU.                    | Redmond, Washington, EE. UU.                           |
| Descripción General | LiveLin es una Startup peruana que se especializa en ofrecer una plataforma de videoconferencia diseñada específicamente para entornos educativos. Su enfoque se centra en proporcionar herramientas intuitivas y eficientes para la interacción en tiempo real entre profesores y alumnos, facilitando la enseñanza remota y la colaboración en proyectos educativos. | Zoom es una reconocida empresa estadounidense que ofrece una plataforma de videoconferencia utilizada ampliamente en diversos ámbitos, incluida la educación. Su servicio se destaca por su facilidad de uso, calidad de audio y video, así como por sus funciones de colaboración en tiempo real. | Google Classroom es una plataforma educativa desarrollada por Google que permite a los profesores crear y administrar cursos en línea, así como asignar tareas y comunicarse con los estudiantes. Está integrada con otras herramientas de Google, como Google Drive y Google Docs, para facilitar el flujo de trabajo en el entorno educativo. | Microsoft Teams es una aplicación de colaboración en equipo desarrollada por Microsoft que ofrece funciones de chat, videoconferencia, intercambio de archivos y colaboración en tiempo real. Aunque su enfoque principal está en entornos empresariales, también se utiliza en instituciones educativas para facilitar la comunicación y la colaboración entre profesores y estudiantes. |
| Ventaja competitiva ¿Qué valor ofrece a los clientes? | LiveLin ofrece una solución integral para la enseñanza remota, con herramientas específicas para la interacción en tiempo real en entornos educativos. Su enfoque en la educación y su conjunto de características diseñadas para facilitar la enseñanza hacen que sea una opción atractiva para instituciones educativas y profesionales de la educación. | Zoom destaca por su facilidad de uso y calidad de audio y video, lo que lo convierte en una opción popular para la enseñanza remota y la colaboración en línea. Además, ofrece una amplia gama de funciones, como salas de reuniones virtuales, compartición de pantalla y grabación de sesiones, que añaden valor a la experiencia del usuario. | Google Classroom se beneficia de su integración con otras herramientas de Google, lo que facilita el flujo de trabajo para profesores y estudiantes que ya utilizan productos de Google en su vida diaria. Además, su enfoque en la simplicidad y la facilidad de uso lo hace atractivo para instituciones educativas de todos los niveles. | Microsoft Teams ofrece una plataforma completa de colaboración en equipo que incluye funciones de chat, videoconferencia y colaboración en tiempo real. Su integración con otras aplicaciones de Microsoft, como Office 365, proporciona una experiencia fluida para profesores y estudiantes que utilizan el ecosistema de Microsoft en sus actividades educativas. |

**Perfil de Marketing**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Mercado Objetivo | LiveLin está dirigido principalmente a instituciones educativas, profesores y estudiantes que buscan una solución integral para la enseñanza remota y la colaboración en proyectos educativos. | Zoom se dirige a una amplia variedad de usuarios, incluidos profesionales de negocios, equipos de trabajo remotos y educadores que necesitan herramientas de videoconferencia de alta calidad. | Google Classroom está orientado a profesores y estudiantes que desean gestionar cursos en línea, asignar tareas y colaborar en proyectos educativos utilizando las herramientas de Google. | Microsoft Teams se enfoca en entornos empresariales y educativos, ofreciendo una plataforma completa de colaboración en equipo que satisface las necesidades de comunicación y colaboración de profesores, estudiantes y equipos de trabajo. |
| Estrategias de Marketing | - Campañas de marketing dirigidas a instituciones educativas y profesionales de la educación. - Promoción en redes sociales y blogs educativos. - Colaboración con asociaciones educativas y organizaciones sin fines de lucro. | - Publicidad en línea y campañas de marketing dirigidas a profesionales y educadores. - Participación en conferencias y eventos de la industria. - Programas de afiliados y referencias para ampliar la base de usuarios. | - Integración con otras herramientas de Google para promover la adopción entre los usuarios existentes de Google. - Marketing de contenidos y tutoriales en línea para profesores y estudiantes. - Colaboración con instituciones educativas para la implementación y formación en Google Classroom. | - Promoción a través de la suite de productos de Microsoft, como Office 365 y Azure. - Eventos y conferencias educativas patrocinadas por Microsoft. - Colaboración con distribuidores y partners para la implementación y formación en Microsoft Teams. |

**Perfil del Producto**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Características y servicios | - Herramientas de videoconferencia diseñadas específicamente para entornos educativos. - Funciones de interacción en tiempo real entre profesores y estudiantes, como chat en vivo, compartición de pantalla y pizarra virtual. - Integración con plataformas de gestión de aprendizaje (LMS) para facilitar la administración de cursos y asignaciones. | - Videoconferencia de alta calidad con capacidad para hasta 1000 participantes en una sola reunión. - Funciones de colaboración en tiempo real, como compartición de pantalla, chat en vivo y grabación de sesiones. - Integración con aplicaciones de terceros y herramientas de productividad. | - Plataforma de gestión de cursos en línea que permite a los profesores crear y administrar clases virtuales, asignar tareas y evaluar el progreso de los estudiantes. - Integración con otras herramientas de Google, como Google Drive y Google Docs, para facilitar el flujo de trabajo. - Aplicación móvil para acceder a Google Classroom desde dispositivos móviles. | - Plataforma de colaboración en equipo que incluye funciones de chat, videoconferencia, intercambio de archivos y colaboración en tiempo real. - Integración con otras aplicaciones de Microsoft, como Office 365 y SharePoint. - Seguridad avanzada y cumplimiento de normativas para proteger los datos de los usuarios. |

**Análisis SWOT**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Fortalezas       | - Enfoque específico en el sector educativo. - Herramientas diseñadas para la enseñanza remota y la colaboración en proyectos educativos. - Integración con plataformas de gestión de aprendizaje (LMS) para una experiencia de usuario completa. | - Facilidad de uso y calidad de audio y video. - Capacidad para albergar grandes reuniones con hasta 1000 participantes. - Amplia gama de funciones de colaboración en tiempo real. | - Integración con otras herramientas de Google para un flujo de trabajo sin interrupciones. - Aplicación móvil para acceder a Google Classroom desde dispositivos móviles. - Popularidad y reconocimiento de la marca Google. | - Plataforma completa de colaboración en equipo con funciones de chat, videoconferencia y colaboración en tiempo real. - Integración con otras aplicaciones de Microsoft para una experiencia integrada. - Seguridad avanzada y cumplimiento de normativas para proteger los datos de los usuarios. |
| Debilidades      | - Poco reconocimiento de marca en comparación con competidores establecidos como Zoom y Google Classroom. - Limitaciones en la capacidad de participantes en las reuniones en comparación con Zoom. - Menor variedad de funciones en comparación con Microsoft Teams. | - Vulnerabilidades de seguridad y privacidad, como incidentes de "zoombombing". - Dependencia excesiva de la conexión a Internet para un rendimiento óptimo. - Falta de integración con otras herramientas educativas y plataformas de gestión de aprendizaje. | - Dependencia de la conectividad a Internet para el acceso y la funcionalidad. - Limitaciones en la capacidad de personalización y configuración en comparación con plataformas más avanzadas como Microsoft Teams. - Competencia directa con otras herramientas de productividad de Google, como Google Meet. | - Menor flexibilidad en la personalización y configuración en comparación con herramientas más avanzadas como Zoom y Microsoft Teams. - Menor integración con otras herramientas de productividad no relacionadas con Microsoft en comparación con Google Classroom. - Dependencia de la suscripción a Microsoft Office 365 para acceder a todas las funciones. |
| Oportunidades    | - Expansión del mercado educativo global con el aumento de la enseñanza remota y el aprendizaje en línea. - Colaboraciones estratégicas con instituciones educativas y organizaciones sin fines de lucro para promover la adopción de LiveLin. - Desarrollo y mejora continua de nuevas características y herramientas específicas para las necesidades educativas. | - Diversificación de servicios para abordar otras necesidades de comunicación y colaboración en línea, como reuniones virtuales sociales y eventos en línea. - Expansión internacional a nuevos mercados emergentes con una demanda creciente de herramientas de videoconferencia. - Integración con plataformas de gestión de aprendizaje (LMS) y sistemas de información educativa para una experiencia educativa más completa. | - Desarrollo de nuevas características y herramientas basadas en la retroalimentación de usuarios y educadores. - Expansión a mercados emergentes y regionales con una demanda creciente de soluciones educativas en línea. - Colaboración con desarrolladores de aplicaciones educativas y herramientas de aprendizaje para integraciones y asociaciones estratégicas. | - Expansión a nuevos sectores y mercados, como el sector empresarial y gubernamental, para su uso en la colaboración en equipo y la comunicación interna. - Integración con otras herramientas de productividad y sistemas empresariales para una experiencia de usuario más integrada. - Desarrollo de soluciones específicas para industrias verticales, como la atención médica y el sector público, para abordar necesidades específicas de colaboración y comunicación. |
| Amenazas         | - Competencia intensa de empresas establecidas en el mercado de videoconferencias, como Zoom y Google Meet. - Riesgos de seguridad y privacidad asociados con el almacenamiento y procesamiento de datos sensibles de estudiantes y profesores. - Cambios en las regulaciones y políticas gubernamentales que puedan afectar la operación y la expansión internacional de LiveLin. | - Competencia de otras plataformas de videoconferencia y colaboración en línea con una mayor cuota de mercado y reconocimiento de marca. - Amenazas de seguridad cibernética y violaciones de datos que pueden socavar la confianza del usuario en la plataforma. - Cambios en las preferencias y necesidades del usuario que pueden afectar la demanda de servicios de videoconferencia en línea. | - Competencia directa de otras plataformas educativas en línea, como Microsoft Teams y Canvas, que ofrecen funcionalidades similares y están integradas con otros servicios de productividad. - Cambios en las políticas y regulaciones gubernamentales que pueden afectar la recopilación y el procesamiento de datos de estudiantes y educadores en línea. - Dependencia de la infraestructura de Internet y la conectividad para el acceso y la funcionalidad de Google Classroom. | - Competencia de otras plataformas de colaboración en equipo y comunicación empresarial, como Slack y Cisco Webex Teams. - Amenazas de seguridad y riesgos de privacidad asociados con la comunicación y colaboración en línea en entornos empresariales y gubernamentales. - Cambios en las necesidades y preferencias del usuario que pueden afectar la demanda de herramientas de colaboración en equipo y comunicación interna. |
- 2.2. Análisis competitivo.
- 2.3. Estrategias y tácticas frente a competidores.
  ## Estrategias:

| Estrategia                           | Descripción                                                                                                                         |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Diferenciación del Producto          | Enfocarse en las características únicas de NoteLive para diferenciarse de otras plataformas en el mercado.                        |
| Enfoque en la Experiencia del Usuario| Priorizar la facilidad de uso y la experiencia del usuario para garantizar una experiencia satisfactoria durante las sesiones.       |
| Integración con Herramientas de Presentación | Mejorar la integración con herramientas de presentación populares para facilitar su adopción por parte de los usuarios.         |

## Tácticas:

| Táctica                                          | Descripción                                                                                                                            |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Ofrecer un Plan Gratuito Atractivo               | Mantener un plan gratuito con funcionalidades básicas para atraer a usuarios potenciales y darles la oportunidad de experimentar.     |
| Desarrollar y Promover Funcionalidades Exclusivas| Crear funcionalidades exclusivas para planes de pago y promover activamente estas características para captar usuarios dispuestos a pagar.|
| Crear Alianzas Estratégicas con Instituciones Educativas | Establecer alianzas con instituciones educativas para promover el uso de NoteLive en entornos académicos.                      |
| Realizar Campañas de Marketing Dirigidas        | Llevar a cabo campañas de marketing dirigidas a profesores y administradores educativos para destacar los beneficios de NoteLive.   |
| Mantenerse al Tanto de las Tendencias del Mercado| Permanecer atento a las tendencias del mercado y adaptar la plataforma para satisfacer las necesidades cambiantes de los usuarios.   |

- 2.4. Entrevistas.
  - 2.4.1. Diseño de entrevistas.
  
    ***Preguntas para Segmento 1: Estudiantes Universitarios***

    En relación al grupo de estudiantes universitarios a los que apuntamos:

	1. ¿Qué herramientas consideras más útiles para mejorar la interacción en el aula durante clases presenciales?
	2. ¿Prefieres plataformas que no requieran instalación de software adicional o estás dispuesto/a a hacerlo si ofrece más funcionalidades?
	3. ¿Qué características valoras más al hacer preguntas durante las clases, como la opción de anonimato o la facilidad de uso?
	4. ¿Qué aspectos te resultan más importantes al seguir la presentación del profesor desde dispositivos móviles?
	5. ¿Cómo crees que una plataforma podría ayudarte a mejorar tu experiencia de aprendizaje en el aula?
	6. ¿Qué funciones adicionales te gustaría que una plataforma ofreciera para facilitar la colaboración y el trabajo en equipo?
	7. ¿Cuál es tu opinión sobre la seguridad y privacidad de tus datos al utilizar plataformas en línea para la educación?
	8. ¿Has tenido alguna experiencia previa con plataformas similares? ¿Qué aspectos positivos y negativos destacarías?
	9. ¿Qué tan importante es para ti que una plataforma sea fácil de usar y tenga una interfaz intuitiva?
	10. ¿Qué crees que hace que una plataforma sea exitosa en el ámbito educativo?

    ***Preguntas para Segmento 2: Profesores y Educadores***

    Estas son algunas preguntas diseñadas para comprender mejor su perspectiva y experiencia en el ámbito educativo. 	 
    Agradecemos su tiempo y sus respuestas, ya que contribuirán al desarrollo de nuestro proyecto.

	1. ¿Qué características consideras más importantes al seleccionar una plataforma para utilizar en tus clases?
	2. ¿Cómo integrarías una plataforma en tus presentaciones de diapositivas o clases?
	3. ¿Qué herramientas te gustaría tener para priorizar y responder preguntas de los estudiantes durante las clases?
	4. ¿Cómo gestionas actualmente múltiples sesiones o cursos en línea?
	5. ¿Qué aspectos de una plataforma te facilitarían más tu trabajo como educador?
	6. ¿Qué desafíos enfrentas al interactuar con tus alumnos de manera remota o en línea?
	7. ¿Qué funciones adicionales te gustaría que una plataforma ofreciera para mejorar la participación y el compromiso de los estudiantes?
	8. ¿Cómo evalúas la efectividad de una plataforma en el proceso de enseñanza y aprendizaje?
	9. ¿Qué importancia le das a la personalización y adaptación de una plataforma a tus necesidades específicas como educador?
	10. ¿Qué consejos darías a otros educadores al seleccionar una plataforma para utilizar en sus clases?
  
  - 2.4.2. Registro de entrevistas.
    - Estudiantes:
      	- Entrevista #1:
      	  ![Imagen](https://github.com/LiveLinORG/Informes/blob/main/images/entrevista_lucia_usuario.jpg)
      	  Entrevistado: Maria Lucia Paez Cairo<br>
      	  Entrevistador: Erick Joaquin Palomino Santa Cruz<br>
	  Duración: 08:15<br>
   	  Link: https://youtu.be/iZBerMLXzHU?si=GmDG8FpFuHDhCL4- <br>
      	  Resumen: La entrevistada discute la importancia de la seguridad y privacidad de los datos en plataformas en línea, especialmente en entornos 	educativos e institucionales. Se mencionan experiencias con plataformas similares a LiveLin, como Canvas Student y Google Classroom, destacando la accesibilidad pero también las limitaciones en opciones. Se subraya la importancia de una interfaz intuitiva y fácil de usar para incentivar la participación de los estudiantes, especialmente aquellos menos familiarizados con la tecnología. Finalmente, se sugiere que el éxito de una plataforma educativa radica en una interfaz visualmente atractiva, adaptada a la preferencia de los estudiantes contemporáneos por las imágenes y los colores sobre el texto.
      	  
      	  
    - Profesores y Educadores:
    	- Entrevista #1:
          ![Imagen](https://github.com/LiveLinORG/Informes/blob/main/images/Entrevista_Piero.png)
          Entrevistado: Valeria Perez Yucra<br>
          Entrevistador: Piero Alonso Martinez Villanueva<br>
  	  Duración: 15:43<br>
          Link: https://youtu.be/eT3FQE8czCA <br>
          Resumen: La señora Valeria nos cuenta como ha sido su experiencia usando plataformas para el dictado de clases en línea, nos comenta que es importante que NoteLive contenga funcionalidades esenciales para el proceso de enseñanza y aprendizaje en cada uno de los niveles de enseñanza existentes en nuestro País.
           
  - 2.4.3. Análisis de entrevistas.
   - Usuarios y Estudiantes:
     - Entrevista #1: Maria Lucia Paez Cairo
       
       En la entrevista, se abordaron varios temas relacionados con la seguridad y privacidad de los datos en plataformas en línea, particularmente en contextos educativos e institucionales. El entrevistado expresó su preocupación por la delicadeza de la información compartida en estos entornos, dado que muchas veces se utilizan correos electrónicos o identificaciones asociadas con el ámbito educativo o laboral. Se destacó la necesidad de que las plataformas respeten y protejan la privacidad de los usuarios, dado que no son programas de uso libre, sino que implican información sensible.
	Luego, se exploraron experiencias previas con plataformas similares a LiveLin, como Canvas Student y Google Classroom. El entrevistado describió estas plataformas como accesibles pero con opciones limitadas, lo que sugiere la necesidad de explorar y aprovechar al máximo las características disponibles. Se resaltó la importancia de una interfaz intuitiva y fácil de usar para facilitar la participación de los estudiantes, especialmente aquellos que pueden tener menos familiaridad con la tecnología.
	Además, se discutió la importancia de que una plataforma educativa sea visualmente atractiva y estimulante para los estudiantes, dado que la generación actual ha crecido rodeada de tecnología y tiende a valorar más las imágenes y los colores que el texto puro. Se sugirió que una interfaz atractiva podría aumentar el compromiso de los estudiantes con la plataforma y, por ende, con su educación.
       
   - Profesores y Educadores:
     - Entrevista #1: Valeria Perez Yucra<br>
       Después de la entrevista, se descubrió que la profesora necesitaba varias funciones importantes de NoteLive. La maestra enfatizó la importancia de que la plataforma sea adaptable a varios niveles de enseñanza. Sugirió que la interfaz debe ser divertida y amigable para los estudiantes de niveles inferiores. Mientras tanto, para niveles superiores, como escuela secundaria, universidad o instituto, la interfaz debería ser más seria y los colores deberían ser más neutros.
Para aumentar la versatilidad, la profesora también mencionó la necesidad de incluir herramientas como una pizarra digital y la capacidad de incorporar material multimedia, ya sea desde YouTube u otro contenido propio, en las presentaciones. Además, sugirió que la aplicación debe permitir al maestro silenciar tanto el chat de voz como el texto de los estudiantes, así como proporcionar un glosario o un buscador para ayudar a los estudiantes a resolver sus dudas.
La posibilidad de que los estudiantes tengan su propia pizarra o anotador para tomar apuntes y comparar sus respuestas con el instructor, así como la inclusión de encuestas que evalúen la comprensión de los estudiantes de la clase dictada, son otras características significativas. Por último, el educador enfatizó la importancia de que NoteLive se diferencie de la competencia al ofrecer opciones de personalización que se adapten a las necesidades únicas de cada educador en la plataforma.

- 2.5. Needfinding.
  
	#### Problemas Identificados:

	1. **Dificultad para la Interacción en el Aula**:
   	- Los estudiantes encuentran desafiante participar activamente en las clases presenciales debido a barreras de comunicación o miedo al juicio de sus pares.

	2. **Limitaciones en la Participación de los Alumnos**:
   	- Algunos alumnos pueden sentirse reacios a hacer preguntas o expresar dudas en público durante las clases, lo que puede afectar su comprensión del material.

	3. **Falta de Sincronización en la Presentación de Diapositivas**:
   	- La falta de sincronización entre la presentación del profesor y los dispositivos de los alumnos puede dificultar seguir el ritmo de la clase y afectar la comprensión del contenido.

	4. **Desafíos en la Priorización de Preguntas Relevantes**:
  	- Los profesores pueden enfrentar dificultades para identificar y responder a las preguntas más importantes de los alumnos debido a la falta de un sistema de priorización claro.

	5. **Necesidad de Recursos de Revisión y Repaso**:
   	- Los estudiantes pueden carecer de herramientas efectivas para revisar y repasar el material discutido en clase, lo que puede afectar su rendimiento académico.

	#### Soluciones Propuestas:

	1. **Facilitar la Interacción en el Aula**:
   	- Proporcionar una plataforma que permita a los estudiantes participar activamente en la clase desde sus dispositivos móviles, eliminando barreras de comunicación.

	2. **Fomentar la Participación de los Alumnos**:
   	- Permitir a los estudiantes hacer preguntas de forma anónima para fomentar un entorno de aprendizaje inclusivo y sin miedo al juicio.

	3. **Sincronización en Tiempo Real**:
	- Garantizar que la presentación del profesor esté sincronizada con los dispositivos de los estudiantes para facilitar el seguimiento del contenido de la clase.

	4. **Priorización de Preguntas Relevantes**:
 	- Implementar un sistema de votación o "me gusta" para que los estudiantes puedan destacar las preguntas más importantes, ayudando así a los profesores a priorizarlas y responderlas de manera efectiva.

	5. **Recursos de Revisión y Repaso**:
  	- Permitir a los estudiantes exportar un registro detallado de preguntas formuladas durante la clase para facilitar la revisión y repaso del material discutido.
- 2.6. User Personas.
  
  ![Imagen](https://github.com/LiveLinORG/Informes/assets/48342953/c5f4b861-215c-480e-8532-369df812c498)
  
  ![Imagen](https://github.com/LiveLinORG/Informes/assets/48342953/5ce0cbdb-a647-4e53-a2af-8f44ac0764db)

- 2.7. User Task Matrix.
  	### Segmento Usuario

	| Actividades                                                 | Frecuencia    | Importancia |
	|-------------------------------------------------------------|---------------|-------------|
	| Participar en sesiones de consulta y capacitación           | A veces       | Media       |
	| Compartir experiencias y consejos en la comunidad en línea  | A veces       | Baja        |

	### Segmento Profesores

	| Actividades                                                 | Frecuencia    | Importancia |
	|-------------------------------------------------------------|---------------|-------------|
	| Integrar dispositivos ergonómicos en la rutina de trabajo  | A veces       | Alta        |
	| Seguir programas de ejercicios personalizados              | Regularmente | Alta        |
	| Utilizar herramientas de seguimiento y análisis del progreso | Regularmente | Media       |

- 2.8. User Journey Mapping.
  	### Segmento Usuario
  	![Imagen de WhatsApp 2024-04-07 a las 11 57 14_a45ffd10](https://github.com/LiveLinORG/Informes/assets/127764958/182e700e-f8d6-4815-8666-9334c00311df)

   	### Segmento Profesores
  	![Imagen de WhatsApp 2024-04-07 a las 12 03 35_b2fe94d1](https://github.com/LiveLinORG/Informes/assets/127764958/dca32f7c-d024-458e-bc06-1bd41ad27856)
  
- 2.9. Empathy Mapping.

  	### Segmento Usuario
  	![Imagen de WhatsApp 2024-04-07 a las 12 38 55_be20d5df](https://github.com/LiveLinORG/Informes/assets/127764958/38614ef5-91fe-460e-a522-829c97ad40f0)

 	### Segmento Profesores
 	![Imagen de WhatsApp 2024-04-07 a las 12 39 00_21f743ad](https://github.com/LiveLinORG/Informes/assets/127764958/de44a14d-5c4b-48d7-8411-006509a3731a)
  
- 2.10. As-is Scenario Mapping.

  	### Segmento Usuario
  	![Imagen de WhatsApp 2024-04-07 a las 15 53 32_056f73da](https://github.com/LiveLinORG/Informes/assets/127764958/9376f9dd-8727-4b2a-aad2-61d05ce7d2ac)

  	### Segmento Profesores
  	![Imagen de WhatsApp 2024-04-07 a las 15 53 39_da7b6c83](https://github.com/LiveLinORG/Informes/assets/127764958/ddf95e71-596c-49ee-9915-681fbdc2d086)
  
- 2.11. Ubiquitous Language.
  ## Términos y Conceptos

1. **Sesión Presencial**:
   - Definición: Una reunión física entre profesores y alumnos donde se utiliza NoteLive para facilitar la interacción en tiempo real.
   - Ejemplo de Uso: "Hoy tendremos una sesión presencial de matemáticas utilizando NoteLive."

2. **Inicio de Sesión Simple**:
   - Definición: Proceso de acceso a la plataforma NoteLive sin requerir instalación de software adicional.
   - Ejemplo de Uso: "Gracias a la función de inicio de sesión simple, los usuarios pueden acceder a NoteLive con solo ingresar un código proporcionado por el profesor."

3. **Interacción en Tiempo Real**:
   - Definición: La capacidad de los alumnos para seguir la presentación del profesor en tiempo real desde sus dispositivos móviles durante una sesión presencial.
   - Ejemplo de Uso: "La interacción en tiempo real de NoteLive permite a los estudiantes seguir el ritmo de la clase desde cualquier lugar en el aula."

4. **Preguntas Anónimas**:
   - Definición: La capacidad de los alumnos para enviar preguntas de forma anónima a través de la aplicación.
   - Ejemplo de Uso: "Con la función de preguntas anónimas, los estudiantes pueden aclarar sus dudas sin temor a ser juzgados."

5. **Destaque de Preguntas Relevantes**:
   - Definición: La función que permite a los alumnos destacar preguntas importantes mediante la opción de "me gusta".
   - Ejemplo de Uso: "Los profesores pueden identificar las preguntas más relevantes gracias al destaque de preguntas implementado en NoteLive."

6. **Integración con Presentaciones**:
   - Definición: La capacidad de los profesores para vincular sus presentaciones de diapositivas a NoteLive para una visualización sincronizada.
   - Ejemplo de Uso: "La integración con presentaciones de NoteLive garantiza que todos los participantes estén en la misma página durante la clase."

7. **Exportación de Registro de Preguntas**:
   - Definición: La opción para que los alumnos exporten un archivo detallado que contiene un registro de todas las preguntas formuladas durante la sesión.
   - Ejemplo de Uso: "Al finalizar la sesión, los alumnos pueden exportar el registro de preguntas para su revisión y repaso posterior."

## Planes de Suscripción

- **Plan Gratuito**:
  - Límite de personas en la sesión: 30
  - Límite de tiempo: 40 min
  - Límite de diapositivas: 100
  - Sin opción de preguntas destacadas
  - Solo puede crear una sesión a la vez

- **Plan Premium**:
  - 1 cuenta premium
  - Límite de personas en la sesión: 100
  - Tiempo ilimitado
  - Diapositivas: 500
  - Preguntas destacadas con CSS
  - Múltiples sesiones

- **Plan Empresarial**:
  - Hasta 1000 cuentas
  - Límite de personas en la sesión: 200
  - Todas las ventajas del plan premium

### 3. Capítulo III: Requirements Specification

- 3.1. To-Be Scenario Mapping.
  	### Segmento Usuario
	![Imagen de WhatsApp 2024-04-11 a las 19 52 59_86f66898](https://github.com/LiveLinORG/Informes/assets/127764958/a86bbe94-34c6-4d08-b5a6-d9771b46fa2b)

	### Segmento Profesores
	![Imagen de WhatsApp 2024-04-11 a las 19 53 23_5bcc7c9a](https://github.com/LiveLinORG/Informes/assets/127764958/7770ae00-f7af-4526-9251-a4be563642d0)


- 3.2. User Stories.
  
  	| ID   | Título                                 | Descripción                                                                                                                                                       | Estado     | Relacionado con la Epic #Número |
	|------|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|---------------------------------|
	| US001| Diseño de Interfaz y Navegación       | Crear una interfaz de usuario intuitiva y fácil de navegar, que incluya un menú de navegación con enlaces a las diferentes secciones del sitio web.                 | Completado | Epic #1 - Diseño y Usabilidad   |
	| US002| Sección de Descripción de NoteLive     | Incluir una descripción detallada de las características y beneficios clave de la aplicación NoteLive.                                                           | Completado | Epic #2 - Funcionalidades Clave |
	| US003| Planes y Precios                       | Detallar los planes de suscripción disponibles, incluyendo sus características y limitaciones.                                                                   | Completado | Epic #3 - Modelo de Negocio     |
	| US004| Testimonios de Usuarios                | Agregar una sección con testimonios de usuarios que destaquen la utilidad y el impacto positivo de NoteLive.                                                     | Completado | Epic #2 - Funcionalidades Clave |
	| US005| Recursos Educativos                    | Incluir una sección con artículos y guías sobre cómo sacar el máximo provecho a las funcionalidades de NoteLive.                                                 | Completado | Epic #4 - Recursos de Soporte   |
	| US006| Soporte y Contacto                     | Proporcionar información de contacto para soporte técnico y atención al cliente, incluyendo un correo electrónico y un formulario de contacto.                    | Completado | Epic #4 - Recursos de Soporte   |
	| US007| Integraciones y Compatibilidad         | Mencionar las principales plataformas de presentación y sistemas de gestión del aprendizaje (LMS) con los que NoteLive es compatible.                           | Completado | Epic #2 - Funcionalidades Clave |
	| US008| Actualizaciones y Novedades            | Agregar una sección para mantener a los usuarios informados sobre las últimas actualizaciones y próximos desarrollos de NoteLive.                                | Completado | Epic #5 - Comunicación y Transparencia |
	| US009| Sección de Inicio (Landing)           | Crear una sección de inicio atractiva, que incluya un título, subtítulo y algunas imágenes representativas de NoteLive.                                          | Completado | Epic #1 - Diseño y Usabilidad   |
	| US010| Exportación de Registro de Preguntas   | Agregar la funcionalidad de exportar un archivo con el registro de preguntas formuladas durante una sesión.                                                       | Completado | Epic #2 - Funcionalidades Clave |
	| US011| Notificaciones en Tiempo Real         | Implementar un sistema de notificaciones en tiempo real para alertar a los usuarios sobre nuevas preguntas, respuestas o interacciones relevantes.               | En Progreso| Epic #2 - Funcionalidades Clave |
	| US012| Modo de Presentación para Profesores  | Desarrollar una vista específica para profesores que les permita controlar y hacer énfasis en las diferentes secciones de la presentación.                       | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US013| Herramientas de Anotación              | Integrar herramientas de anotación y marcado durante la presentación que puedan ser visibles para todos los participantes.                                       | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US014| Encuestas y Evaluaciones               | Habilitar la creación de encuestas y evaluaciones en tiempo real durante las sesiones.                                                                             | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US015| Estadísticas de Participación         | Generar informes y métricas sobre la participación de los estudiantes durante las sesiones.                                                                       | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US016| Reconocimiento de Patrones             | Implementar un sistema de reconocimiento de patrones en las preguntas de los estudiantes para identificar áreas de dificultad.                                    | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US017| Modo de Vista Móvil                   | Optimizar la experiencia de usuario para dispositivos móviles, facilitando la interacción y visualización en pantallas pequeñas.                                | En Progreso| Epic #1 - Diseño y Usabilidad   |
	| US018| Autenticación con Redes Sociales      | Permitir a los usuarios iniciar sesión en NoteLive a través de sus cuentas de redes sociales.                                                                     | Por Hacer  | Epic #1 - Diseño y Usabilidad   |
	| US019| Personalización de Temas               | Ofrecer a los usuarios la posibilidad de personalizar la apariencia visual de la aplicación mediante temas y estilos personalizados.                             | Por Hacer  | Epic #1 - Diseño y Usabilidad   |
	| US020| Modo de Presentación Privado          | Habilitar un modo de presentación privado que permita a los profesores compartir contenido confidencial con un grupo seleccionado de estudiantes.                  | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US021| Historial de Sesiones                 | Implementar un historial de sesiones que permita a los usuarios volver a acceder a presentaciones y preguntas anteriores.                                         | En Progreso| Epic #2 - Funcionalidades Clave |
	| US022| Suscripción Automática a Sesiones     | Permitir que los estudiantes se suscriban automáticamente a las sesiones de sus profesores mediante un código único.                                             | Por Hacer  | Epic #1 - Diseño y Usabilidad   |
	| US023| Horario de Sesiones                   | Integrar un calendario y horario de sesiones que facilite la planificación y organización de las clases.                                                          | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US024| Emojis y Reacciones                   | Implementar la posibilidad de que los estudiantes puedan reaccionar a las preguntas y contenido con emojis.                                                       | En Progreso| Epic #2 - Funcionalidades Clave |
	| US025| Asistencia Virtual                    | Desarrollar una asistente virtual que pueda responder a preguntas comunes de los usuarios y guiarlos en el uso de la plataforma.                                  | Por Hacer  | Epic #4 - Recursos de Soporte   |
	| US026| Traducción Multilingüe                | Permitir la traducción automática de contenido y comunicación entre participantes de diferentes idiomas.                                                           | Por Hacer  | Epic #1 - Diseño y Usabilidad   |
	| US027| Registro de Actividad                 | Crear un registro detallado de la actividad de cada usuario durante las sesiones, incluyendo preguntas, respuestas y participación.                               | En Progreso| Epic #2 - Funcionalidades Clave |
	| US028| Notificaciones Push                   | Implementar notificaciones push en dispositivos móviles para mantener a los usuarios informados sobre nuevas sesiones, preguntas y actualizaciones.                | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US029| Integración con LMS                   | Desarrollar integraciones fluidas con los principales sistemas de gestión del aprendizaje (LMS) utilizados en el ámbito educativo.                                | Por Hacer  | Epic #2 - Funcionalidades Clave |
	| US030| Análisis de Sesiones                  | Proporcionar informes y análisis avanzados sobre el desempeño y la participación en las sesiones, con gráficos y métricas detalladas.                             | Por Hacer  | Epic #2 - Funcionalidades Clave |

- 3.3. Impact Mapping.
- 3.4. Product Backlog.
  
	|Historia De Usuario|Descripción|
	|:----|:----|
	|Inicio de Sesión Simple|Como usuario, quiero poder iniciar sesión de manera sencilla en NoteLive a través de un código único proporcionado por el profesor para acceder a la sesión.|
	|Interacción en Tiempo Real|Como alumno, deseo ver la presentación del profesor en tiempo real en mi dispositivo móvil mientras estoy en clase para poder seguir el ritmo de la lección desde cualquier lugar en el aula.|
	|Envío de Preguntas Anónimas|Como alumno, quiero tener la capacidad de enviar preguntas de forma anónima a través de la aplicación para poder participar en la discusión sin revelar mi identidad.|
	|Destaque de Preguntas Relevantes|Como alumno, me gustaría poder destacar las preguntas que considere más relevantes utilizando la función de "me gusta" para que el profesor pueda identificarlas fácilmente y abordarlas durante la clase.|
	|Integración con Presentaciones|Como profesor, quiero poder vincular mis presentaciones de diapositivas a NoteLive para que todos los alumnos puedan verlas sincronizadamente y facilitar la discusión en tiempo real durante la clase.|
	|Exportación de Registro de Preguntas|Como alumno, quiero tener la opción de exportar un archivo detallado que contenga un registro de todas las preguntas formuladas durante la clase para poder revisarlas posteriormente y repasar el material discutido.|
	|Navegación a la Página de Inicio|Como usuario, deseo poder navegar fácilmente a la página de inicio de NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para acceder a información general sobre la aplicación.|
	|Navegación a la Sección de Información|Como usuario, quiero poder acceder a la sección que explica qué es NoteLive haciendo clic en el enlace respectivo en la barra de navegación para obtener más detalles sobre su funcionamiento.|
	|Navegación a la Sección de Usos|Como usuario, deseo poder explorar los diferentes usos de NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para comprender cómo puede beneficiarme en mi contexto educativo.|
	|Navegación a la Galería|Como usuario, me gustaría poder ver una galería de imágenes relacionadas con NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para visualizar ejemplos de su aplicación en situaciones reales.|
	|Navegación al Registro|Como usuario, quiero poder acceder a la página de registro de NoteLive haciendo clic en el enlace respectivo en la barra de navegación para crear una cuenta y comenzar a utilizar la plataforma.|
	|Participación en Sesión Anónima|Como alumno, deseo poder participar en una sesión de NoteLive de manera anónima ingresando un código único proporcionado por el profesor para mantener mi privacidad durante la interacción en clase.|
	|Acceso a Presentaciones Sincronizadas|Como alumno, quiero poder acceder a las presentaciones de diapositivas sincronizadas con la clase a través de NoteLive para asegurarme de que todos los participantes estén en la misma página y no perderme ningún contenido importante.|
	|Recepción de Notificaciones|Como usuario, me gustaría recibir notificaciones de nuevas actualizaciones o anuncios importantes relacionados con NoteLive para mantenerme informado sobre cualquier cambio en la plataforma.|
	|Personalización de Perfil|Como usuario, quiero poder personalizar mi perfil en NoteLive agregando una foto y ajustando mi configuración para adaptar la experiencia de uso a mis preferencias individuales.|
	|Acceso a la Galería de Recursos|Como usuario, deseo poder acceder a una galería de recursos educativos dentro de NoteLive para encontrar material adicional que complemente mi aprendizaje durante la clase.|
	|Función de Traducción Integrada|Como usuario, me gustaría tener la opción de utilizar una función de traducción integrada en NoteLive para traducir contenido en tiempo real a mi idioma preferido y facilitar la comprensión de la lección.|
	|Compartir Enlaces de Sesión|Como profesor, quiero poder compartir enlaces de sesión personalizados con mis alumnos a través de NoteLive para facilitar su acceso a la plataforma y comenzar la clase sin problemas.|
	|Control de Acceso a la Sesión|Como profesor, deseo tener la capacidad de controlar el acceso a la sesión de NoteLive mediante la generación y asignación de códigos únicos para garantizar la seguridad y la integridad de la clase.|
	|Marcar Diapositivas Importantes|Como profesor, me gustaría poder marcar diapositivas importantes durante la presentación en NoteLive para resaltarlas y asegurarme de que los alumnos presten atención a los conceptos clave.|
	|Evaluación de Participación|Como profesor, deseo tener la capacidad de evaluar la participación de los alumnos durante la clase en NoteLive mediante la revisión de las preguntas enviadas y los comentarios realizados para medir su compromiso con el material.|
	|Asistencia Automatizada|Como profesor, quiero que NoteLive registre automáticamente la asistencia de los alumnos cuando accedan a la sesión para facilitar el seguimiento de su participación y puntualidad.|
	|Acceso a Recursos Compartidos|Como alumno, me gustaría poder acceder a recursos compartidos por el profesor durante la clase a través de NoteLive para revisar el material posteriormente y reforzar mi aprendizaje.|
	|Soporte para Diferentes Dispositivos|Como usuario, deseo que NoteLive sea compatible con una variedad de dispositivos y sistemas operativos para poder acceder a la plataforma desde cualquier dispositivo que tenga disponible.|
	|Personalización de Temas|Como usuario, me gustaría poder personalizar el tema visual de NoteLive eligiendo entre diferentes opciones de color y diseño para adaptarlo a mis preferencias estéticas y mejorar la experiencia de uso.|
	|Compartir Recursos con Otros Usuarios|Como profesor, quiero poder compartir recursos educativos con otros usuarios de NoteLive para promover la colaboración y el intercambio de conocimientos entre la comunidad de usuarios.|
	|Informes de Desempeño del Alumno|Como profesor, deseo tener acceso a informes de desempeño individual de los alumnos en NoteLive para evaluar su progreso y ofrecer retroalimentación personalizada sobre su rendimiento académico.|
	|Integración con Plataformas de Aprendizaje|Como usuario, me gustaría que NoteLive se integre con otras plataformas de aprendizaje en línea para facilitar la gestión de contenido y la comunicación con mis profesores y compañeros de clase.|
	|Sincronización de Notas y Comentarios|Como usuario, quiero que mis notas y comentarios realizados en NoteLive se sincronicen automáticamente en todos mis dispositivos para poder acceder a ellos desde cualquier lugar y en cualquier momento.|
	|Protección de Datos Personales|Como usuario, deseo que NoteLive garantice la protección de mis datos personales y la privacidad de mis interacciones en la plataforma mediante medidas de seguridad robustas y cumplimiento de regulaciones de privacidad.|
- Product Backlog de Landing Page:
	| User Story                           | Descripción                                                                                                          |
	|--------------------------------------|----------------------------------------------------------------------------------------------------------------------|
	| Optimización de Responsividad        | Asegurarse de que el sitio web sea completamente responsive en diferentes dispositivos y tamaños de pantalla.      |
	| Mejoras de Accesibilidad             | Garantizar que el sitio web sea accesible para usuarios con discapacidades, incluyendo la navegación por teclado y el uso de lectores de pantalla. |
	| Validación de HTML y CSS             | Validar el código HTML y CSS para asegurar que cumple con los estándares y no contiene errores.                     |
	| Optimización de Carga                | Optimizar el tiempo de carga del sitio web para mejorar la experiencia del usuario.                                |
	| Añadir Interactividad                | Implementar interactividad en elementos como botones y enlaces para mejorar la usabilidad.                          |
	| Mejoras de SEO                       | Optimizar el sitio web para mejorar su visibilidad en los motores de búsqueda.                                        |
	| Refactorización de Clases y Selectores | Revisar y refactorizar las clases y selectores en el CSS para mejorar la legibilidad y mantenibilidad del código.  |
	| Pruebas de Cross-Browser             | Realizar pruebas exhaustivas en diferentes navegadores para asegurar la compatibilidad y el rendimiento del sitio web.|
	| Documentación                        | Documentar el código HTML y CSS para facilitar el mantenimiento futuro y la colaboración entre desarrolladores.     |
	| Implementación de Funcionalidades Faltantes | Completar la implementación de características como el inicio de sesión, el registro de usuarios, y otras funciones necesarias para el funcionamiento completo del sitio web. |
	| Seguridad                            | Implementar medidas de seguridad apropiadas para proteger el sitio web contra vulnerabilidades y ataques maliciosos.|
	| Actualización de Contenido           | Actualizar el contenido del sitio web según sea necesario para mantenerlo relevante y preciso.                       |
	| Gestión de Errores y Excepciones     | Implementar manejo de errores y excepciones para proporcionar una experiencia de usuario robusta y sin problemas.     |
	| Integración de Diseño de Interfaces | Integrar el diseño de interfaces gráficas proporcionado por el equipo de diseño para asegurar coherencia visual en todo el sitio web. |
	| Cabecera (Header)                    | La estructura de la cabecera está definida con secciones como el logo y los elementos de navegación.                  |
	| Diseño Responsivo                    | El diseño del sitio web utiliza técnicas CSS Grid y Flexbox para garantizar una visualización adecuada en diferentes dispositivos y tamaños de pantalla. |
	| Estilos de Navegación                | Se han aplicado estilos CSS para los elementos de navegación, incluyendo efectos de hover y sombras.                 |
	| Contenedor Principal                 | El contenedor principal del sitio web se ha definido con una estructura de grid y secciones para organizar el contenido. |
	| Sección de Aterrizaje (Landing)      | Se ha creado una sección de aterrizaje con un título, subtítulo, imágenes y un botón de inicio.                     |
	| Estilos de Botón                     | Los botones tienen estilos CSS aplicados, incluyendo colores, sombras y efectos de hover.                           |
	| Tarjetas de Notas (Note Live Cards)  | Se han definido tarjetas para mostrar información sobre las características de NoteLive, con diferentes estilos según el tamaño de la tarjeta. |
	| Sección de Características Adicionales | Se ha creado una sección para mostrar las características de los diferentes planes de NoteLive, con estilos y colores específicos para cada plan. |
	| Estilos de Testimonios de Usuarios   | Los testimonios de usuarios tienen estilos aplicados, incluyendo colores de fondo, tipografía y efectos de hover. |
	| Sección de Recursos Educativos       | Se ha añadido una sección para mostrar recursos educativos relacionados con NoteLive.                                |
	| Sección de Soporte y Contacto        | Se ha creado una sección para proporcionar información de contacto y soporte, con estilos aplicados para resaltar la información. |
	| Sección de Integraciones y Compatibilidad | Se ha añadido una sección para destacar las integraciones y compatibilidad de NoteLive con otras plataformas.        |
	| Sección de Actualizaciones y Novedades | Se ha incluido una sección para informar a los usuarios sobre las últimas actualizaciones y noticias relacionadas con NoteLive. |
	| Estilos del Footer                   | El footer tiene estilos aplicados para el color de fondo, el color del texto y el espaciado interno.                |
	| Consulta de Medios (Media Queries)   | Se han implementado consultas de medios para ajustar el diseño y los estilos en diferentes tamaños de pantalla.     |

  

### 4. Capítulo IV: Product Design

- 4.1. Style Guidelines.
  - 4.1.1. General Style Guidelines.
    
	Nuestra aplicación tiene como objetivo mejorar la experiencia virtual para enriquecer el aprendizaje. Por ello, nuestra compañía ha decidido elegir un conjunto de colores discretos que resalten el contenido importante para el usuario.

	**Tipografía**
	**Tipo de letra:**

	Se ha elegido la tipografía Roboto, con variaciones en el tamaño de letra dependiendo del lugar en el que se encuentre, como puede ser título o subtítulo.

	**Color de letra:**

	Los tres colores que se utilizarán son el blanco, negro y anaranjado. La elección del color dependerá del fondo, habiendo una relación inversa entre la tonalidad del fondo y el color de la letra. No obstante, en ocasiones especiales se utilizarán otros colores para resaltar información importante. Aquí algunos ejemplos del color de la letra:

  - 4.1.2. Web Style Guidelines.
- 4.2. Information Architecture.
  - 4.2.1. Organization Systems.
  - 4.2.2. Labeling Systems.
  - 4.2.3. SEO Tags and Meta Tags.
  - 4.2.4. Searching Systems.
  - 4.2.5. Navigation Systems.
- 4.3. Landing Page UI Design.
  - 4.3.1. Landing Page Wireframe.
  - 4.3.2. Landing Page Mock-up.
- 4.4. Web Applications UX/UI Design.
  - 4.4.1. Web Applications Wireframes.
    
    Wireframe principal, donde se decidirá si se creará una sesión o se unirá a una ya existente.
    <p align="center"><img src="images/wireframeMain.jpg" alt="Wireframe Principal" width="80%"></p>
    
    Wireframe de unión, donde se introduce el pin de la sesión y el nombre del participante.
    <p align="center"><img src="images/wireframeJoin.jpg" alt="Wireframe de Unión" width="80%"></p>
    
    Wireframe de creación, donde se presenta el pin de la sesión, se ve la cantidad de participantes, sus nombre y se sube el doumento a visualizar.
    <p align="center"><img src="images/wireframeCreate.jpg" alt="Wireframe de Creación" width="80%"></p>
    
    Wireframe de uso, donde se vizualizará el documento subido, se podrá realizar preguntas y hacer comentarios en tiempo real.
    <p align="center"><img src="images/wireframeUse.jpg" alt="Wireframe de Uso" width="80%"></p>
    
  - 4.4.2. Web Applications Wireflow Diagrams.
    
    El usuario busca crear una sesión, por lo que presiona el botón de creación de sesión. Luego de compartir el pin de la sesión con sus alumnos y subir la presentación de la clase, presionará el botón de inicio. Luego podrá hacer uso de la herramienta.
    <p align="center"><img src="images/wireflowCrear.png" alt="Wireframe de Creación" width="80%"></p>
    
    El usuario busca unirse a una sesión existente, por lo que presiona el botón de unirse. Luego de ingresar el pin que le fue compartido e ingresar un nombre, podrá presionar le botón de ingresar. Luego podrá hacer uso de la herramienta.
    <p align="center"><img src="images/wireflowUnirse.png" alt="Wireframe de Unión" width="80%"></p>
    
  - 4.4.3. Web Applications Mock-ups.
    
    Mock-Up De la página principal
    <p align="center"><img src="images/mock-upMain.jpg" alt="Mock-Up Principal" width="80%"></p>
    
    Mock-Up de la página de unión
    <p align="center"><img src="images/mock-upJoin.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin1.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin2.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin3.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin4.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin5.jpg" alt="Mock-Up Unión" width="80%"></p>
    <p align="center"><img src="images/mock-upJoin6.jpg" alt="Mock-Up Unión" width="80%"></p>
    
    Mock-Up de la página de creación
    <p align="center"><img src="images/mock-upCreate.jpg" alt="Mock-Up Creación" width="80%"></p>
    <p align="center"><img src="images/mock-upCreate1.jpg" alt="Mock-Up Creación" width="80%"></p>
    <p align="center"><img src="images/mock-upCreate2.jpg" alt="Mock-Up Creación" width="80%"></p>
    <p align="center"><img src="images/mock-upCreate3.jpg" alt="Mock-Up Creación" width="80%"></p>
    
    Mock-Up de la página de uso
    <p align="center"><img src="images/mock-upUse.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse1.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse2.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.1.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.2.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.3.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.1.2.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.2.3.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.1.3.jpg" alt="Mock-Up Uso" width="80%"></p>
    <p align="center"><img src="images/mock-upUse3.4.jpg" alt="Mock-Up Uso" width="80%"></p>

    
  - 4.4.4. Web Applications User Flow Diagrams.
 
    User Flow de la creación de una sesión. Cuando el usuario haya apretado el botón de creación, y luego de subir el archivo a compartir. Este podrá iniciar la sesión cuando todos los participantes se hayan unido. 
    <p align="center"><img src="images/webappUserflowCreate.png" alt="Mock-Up UserFlow Creación" width="80%"></p>
    
    User Flow de unión a una sesión existente. Cuando el usuario haya apretado el botón de unirse, luego de haber ingresado un pin válido y un nombre. Este podrá unirse a la sesión tras presionar el botón de entrar.
    <p align="center"><img src="images/webappUserflowJoin.png" alt="Mock-Up UserFlow Unión" width="80%"></p>
    
    User Flow de comentar. Cuando un usuario ingrese un texto en la sección de comentarios, éste podra enviar un comentario en la caja del chat despúes de presionar el botón de envío.
    <p align="center"><img src="images/webappUserflowComment.png" alt="Mock-Up UserFlow Comentario" width="80%"></p>
    
    User Flow de preguntar. Cuando un usuario ingrese una pregunta en la sección de preguntas, éste podrá enviar su duda después de presionar el botón de envío.
    <p align="center"><img src="images/webappUserflowAsk.png" alt="Mock-Up UserFlow Pregunta" width="80%"></p>
    
    User Flow de me gusta. Cuando un usuario quiera ponerle "Me gusta" a una pregunta existente, este deberá apretar el pulgar arriba que se encuentra en las esquinas de todos los comentarios.
    <p align="center"><img src="images/webappUserflowLike.png" alt="Mock-Up UserFlow Me Gusta" width="80%"></p>
    
  - 4.4.5. Web Applications Prototyping.
- 4.5. Domain-Driven Software Architecture.
  - 4.5.1. Software Architecture Context Diagram.
  <p align="center"><img src="images/Context.png" alt="Diagrama de contexto" width="80%"></p>
  - 4.5.2. Software Architecture Container Diagrams.
  <p align="center"><img src="images/Container.png" alt="Diagrama de contendores" width="80%"></p>
  - 4.5.3. Software Architecture Components Diagrams.
  <p align="center"><img src="images/Components.png" alt="Diagrama de componentes" width="80%"></p>
- 4.6. Software Object-Oriented Design.
  - 4.6.1. Class Diagrams. <br>
    A continuación, se presenta el diagrama de clases de NoteLive elaborado en StarUML:
    ![image](https://github.com/LiveLinORG/Informes/blob/main/images/NoteLive-ClassDiagram.jpg)
    
  - 4.6.2. Class Dictionary. <br>
  
    - User:
    
	| Atributo     | Tipo de Dato | Descripción                                     |
	|--------------|---------------|-------------------------------------------------|
	| id           | int           | Identificador único del usuario.               |
	| username     | string        | Nombre de usuario.                              |
	| password     | string        | Contraseña del usuario.                         |
	| firstname    | string        | Nombre del usuario.                             |
	| lastname     | string        | Apellido del usuario.                           |
	| phonenumber  | string        | Número de teléfono del usuario.                 |
	| email        | string        | Correo electrónico del usuario.                |
	| usertype     | string        | Tipo de usuario (profesor/alumno).              |
	| membership   | Membership    | Tipo de membresía del usuario.                  |
	
	| Método                                 | Descripción                                           |
	|----------------------------------------|-------------------------------------------------------|
	| changeName(firstname, lastname)       | Cambia el nombre completo del usuario.               |
	| changeUsername(username)              | Cambia el nombre de usuario.                          |
	| changePassword(password)              | Cambia la contraseña del usuario.                     |
	| changePhonenumber(phonenumber)        | Cambia el número de teléfono del usuario.             |
	| changeEmail(email)                    | Cambia el correo electrónico del usuario.             |
	| putchaseMembership(membership)        | Adquiere una membresía para el usuario.               |


    - Membership:
    
	| Atributo    | Tipo de Dato | Descripción                                         |
	|-------------|---------------|-----------------------------------------------------|
	| id          | int           | Identificador único de la membresía.                |
	| activate    | bool          | Indica si la membresía está activa o no.           |
	| membertype  | string        | Tipo de membresía (premium, estándar, etc.).        |
	
	| Método                             | Descripción                                        |
	|------------------------------------|----------------------------------------------------|
	| activateMembership(activate)       | Activa o desactiva la membresía.                   |


    - ChatBox:
      
	| Atributo    | Tipo de Dato | Descripción                                          |
	|-------------|---------------|------------------------------------------------------|
	| id          | int           | Identificador único del chat.                        |
	| content     | string        | Contenido del chat.                                  |
	| bold        | bool          | Indica si el texto es en negrita.                    |
	| italic      | bool          | Indica si el texto es en cursiva.                    |
	| underline   | bool          | Indica si el texto está subrayado.                   |
	
	| Método                             | Descripción                                         |
	|------------------------------------|-----------------------------------------------------|
	| send(content)                     | Envía un mensaje en el chat.                        |
	| edit(content)                     | Edita un mensaje previamente enviado en el chat.    |
	| delete(content)                   | Elimina un mensaje del chat.                        |


    - Whiteboard:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| id          | int           | Identificador único del pizarrón.         |
	| tools       | Tool          | Herramientas disponibles en el pizarrón. |
	
	| Método                             | Descripción                                |
	|------------------------------------|--------------------------------------------|
	| draw(tools)                        | Dibuja utilizando las herramientas.        |
	| delete(tool)                       | Elimina una herramienta del pizarrón.     |


    - Tool:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| id          | int           | Identificador único de la herramienta.    |
	| texts       | Text          | Textos disponibles.                        |
	| rectangles  | Rectangle     | Rectángulos disponibles.                   |
	| lines       | Line          | Líneas disponibles.                        |
	
	| Método                             | Descripción                                |
	|------------------------------------|--------------------------------------------|
	| chooseTool()                       | Selecciona una herramienta.                |


    - Text:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| content     | string        | Contenido del texto.                       |
	| position    | point         | Posición del texto en el pizarrón.        |
	| color       | string        | Color del texto.                           |
	| fontSize    | int           | Tamaño de fuente del texto.                |
	| fontFamily  | string        | Fuente del texto.                          |


    - Rectangle:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| position    | point         | Posición del rectángulo en el pizarrón.   |
	| color       | string        | Color del rectángulo.                      |
	| size        | Size          | Tamaño del rectángulo.                     |
	| filled      | bool          | Indica si el rectángulo está relleno.      |

    - Line:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| start       | point         | Punto de inicio de la línea.               |
	| end         | point         | Punto final de la línea.                   |
	| color       | string        | Color de la línea.                         |
	| thickness   | int           | Grosor de la línea.                        |


    - Presentation:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| id          | int           | Identificador único de la presentación.   |
	| title       | string        | Título de la presentación.                 |
	| description | string        | Descripción de la presentación.            |
	| resources   | Resource      | Recursos asociados a la presentación.     |
	
	| Método                             | Descripción                                       |
	|------------------------------------|---------------------------------------------------|
	| selectResource(resources)          | Selecciona un recurso para la presentación.       |


    - Resource:
      
	| Atributo    | Tipo de Dato | Descripción                                |
	|-------------|---------------|--------------------------------------------|
	| id          | int           | Identificador único del recurso.           |
	| type        | ResourceType  | Tipo de recurso.                           |
	| url         | string        | URL del recurso.                           |


    - Session:
      
	| Atributo     | Tipo de Dato | Descripción                                         |
	|--------------|---------------|-----------------------------------------------------|
	| id           | int           | Identificador único de la sesión.                   |
	| teachers     | User          | Usuarios que son profesores en la sesión.            |
	| students     | User          | Usuarios que son alumnos en la sesión.              |
	| chatbox      | ChatBox       | Chat utilizado en la sesión.                         |
	| whiteboards  | Whiteboard    | Pizarrones utilizados en la sesión.                  |
	| presentations| Presentation  | Presentaciones utilizadas en la sesión.              |
	| startTime    | DateTime      | Hora de inicio de la sesión.                         |
	| endTime      | DateTime      | Hora de finalización de la sesión.                   |
	| maxAttendees | int           | Máximo número de asistentes permitidos en la sesión. |
	
	| Método                                 | Descripción                                               |
	|----------------------------------------|-----------------------------------------------------------|
	| presentBoard(whiteboards, presentations) | Presenta los pizarrones y presentaciones durante la sesión.  |
	| recordSession(startTime, endTime)     | Registra la sesión con su hora de inicio y finalización.   |


   - NoteLive:
     
	| Atributo   | Tipo de Dato | Descripción                                   |
	|------------|---------------|-----------------------------------------------|
	| users      | User          | Usuarios de la aplicación.                    |
	| sessions   | Session       | Sesiones disponibles en la aplicación.        |
	|
	| Método                             | Descripción                                       |
	|------------------------------------|---------------------------------------------------|
	| joinSession(users, sessions)       | Une a los usuarios a las sesiones disponibles.   |

    
- 4.7. Database Design.
  - 4.7.1. Database Diagram. <br>
    EL diagrama de la base de datos fue realizada en Vertabelo. A continuación, se adjunta la imagen:
    ![image](https://github.com/LiveLinORG/Informes/blob/main/images/NoteLive-Database-2024-04-12_20-00.png)
    Link: https://my.vertabelo.com/doc/Ep8TNV6YE7JK7SxGi013UZiFbiPT5WFw

### 5. Capítulo V: Product Implementation, Validation & Deployment

- 5.1. Software Configuration Management.
  - 5.1.1. Software Development Environment Configuration.
     - **Requirements Management**
      1. **Miro:** Plataforma en línea que permite la colaboración en tiempo real a través de pizarras digitales. Ofrece herramientas para la creación de diagramas, mapas mentales, diagramas de flujo, y más. En este caso, utilizamos Miro para la elaboración de As-Is y To-Be Scenarios Mapping.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/c6a157d4-5891-4df6-9a52-4155c04d3c37)
      2. **UXPressia:** Herramienta especializada en la creación de mapas de impacto de experiencia de usuario (UX). En este caso, utilizamos UXPressia para la elaboración del Impact Mapping para cada segmento objetivo.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/8337a3ad-5689-4f7c-9a67-1b7f6df8d95b)
      3. **Figma:** Herramienta de diseño de interfaces de usuario (UI) y prototipado colaborativo basada en la nube. En este caso, utilizamos Figma para la elaboración del prototipo de la aplicación.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/c4a55064-caee-464b-bdd8-908578c23e5f)
      4. **PivotalTracker**: Herramienta de gestión de proyectos basada en tableros. En este caso, utilizamos PivotalTracker para visualizar y actualizar el estado de las tareas e historias de usuario pertenecientes al sprint a desarrollar.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/0b140fca-5e55-4f15-ab6a-3b0a2aff2291)
    - **Software Development**
      1. **Visual Studio Code:** Editor de código fuente desarrollado por Microsoft que ofrece una amplia gama de funcionalidades para programadores. En este caso, utilizamos Visual Studio Code como nuestro entorno de desarrollo integrado principal para escribir, editar y depurar el código HTML y CSS de nuestro proyecto.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/4e2f9613-5067-4294-89e2-e3426ca7605a)
      2. **HTML:** HTML (Hypertext Markup Language) es el lenguaje estándar utilizado para crear y diseñar páginas web. En este caso, utilizamos el lenguaje HTML para la creación y presentación de nuestra página web.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/d4a632ca-5dc9-4c77-b51a-3d1839e5476b)
      3. **CSS:** CSS (Cascading Style Sheets) es un lenguaje de diseño utilizado para estilizar la presentación de documentos HTML.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/2ff3321a-5c8f-4dc9-804e-cd6fa4027417)
      4. **GitHub:** Plataforma de desarrollo colaborativo basada en la nube que utiliza el sistema de control de versiones Git. Permite a los desarrolladores alojar, revisar y colaborar en proyectos de software. En este caso, utilizamos GitHub como un repositorio remoto para almacenar y gestionar el código fuente de nuestro proyecto.
      ![image](https://github.com/TripTeamOrganization/Informes/assets/164519824/80bc9459-2cdd-40de-851b-d23d9eb62d4b)
  
  - 5.1.2. Source Code Management.
     Para todo el ciclo de vida de nuestro proyecto, utilizaremos el sistema de control de versiones Git donde la evidencia será visualizada y registrada en la plataforma de GitHub de nuestra organización. Se podrá visualizar todos los cambios y modificaciones hechos por cada uno de los miembros del grupo.
    GitHub URL: [Repositorio](https://github.com/LiveLinORG)
  - 5.1.3. Source Code Style Guide & Conventions.
    - **HTML:** Para el lenguaje HTML, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”:
      1. Usar nombres de elementos en minúsculas
      2. Cerrar todos los elementos HTML
      3. Usar nombres de atributos en minúsculas
      4. Usar atributos en imágenes
      5. Evitar líneas de código largas
      6. Usar sintaxis simple para los enlaces para las hojas de estilo y para cargar script externos
    - **CSS:** Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente, sostenible y ordenado:
      1. Utilizar minúsculas y guiones para los nombres de propiedades
      2. Utilizar un espacio después de los dos puntos y un punto y coma para separar pares propiedad-valor.
      3. Agrupar reglas CSS relacionadas y separarlas con una línea en blanco.
      4. Utilizar nombres de clases que sean descriptivos y reflejen el propósito del elemento.
      5. Separar los nombres de las clases y ID con un guión
    - **Gherkin:** Es un lenguaje de dominio específico diseñado para escribir especificaciones legibles por humanos que describen el comportamiento del software en un formato estructurado y comprensible. En busca de una buena práctica, se utilizarán saltos de línea para mejorar el orden de los escenarios y poder diferenciarlos de forma más óptima. Además, se escribirán los escenarios bajo el formato “Given”, “When”, “Then”, “And” para definir claramente el contexto, la acción y el resultado esperado.
  
  - 5.1.4. Software Deployment Configuration.
	- **Landing Page Deployment**
	  Para desplegar nuestro landing page, utilizamos GitHub. Para esto es necesario contar con una cuenta personal, una organización y un repositorio al cual cargar los documentos. En este repositorio, se puede observar lo siguiente:
	    - Una carpeta “html” con el archivo “index.html” el cual contiene nuestra landing page.
	    - Una carpeta “css” la cual contiene nuestra hoja de estilos “style.css”
	    - Una carpeta “images” la cual contiene las imágenes utilizadas en el landing page
	    - Una carpeta “js” la cual contiene nuestros scripts en un archivo “index.js”
	  Además, para el despliegue utilizando GitHub, también implementamos Node.js para el deployment mediante puertos abiertos TCP.
- 5.2. Landing Page, Services & Applications Implementation.
  - 5.2.1. Sprint n
    - 5.2.1.1. Sprint Planning.
      
| **Sprint #** | **Sprint 1** |
| :- | :- |
| **Sprint Planning Background** | |
| Date | 25/03/2024 |
| Time | 8:00 PM - 11:00 PM |
| Location | Discord |
| **Prepared By** | Adrián Enrique Jesús Palma Obispo  |
| Attendees | - Adrián Enrique Jesús Palma Obispo<br>- Erick Joaquín Palomino Santa Cruz<br>- Joaquín Alonso Carbajal Pozzo<br>- Piero Alonso Martínez Villanueva<br>- Renzo César Silva Morales |
| **Sprint 0 Review Summary** | Diseño y desarrollo del Landing Page |
| **Sprint 0 Retrospective Summary** | Completar los diseños y estandarizar el lenguaje usado en el desarrollo y presentación del landing page |
| **Sprint Goal & User Stories** | |
| **Sprint 1 Goal** | Elaborar, diseñar y desplegar una Landing Page atractiva e informativa para la aplicación TripMate |
| **Sprint 1 Velocity** | 15 |
| **Sum of Story Points** | 15 |
       
   - 5.2.1.2. Sprint Backlog.
     
|**Sprint #**|**Sprint 1**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story|Work-Item / Task|||||||
|Id|Title|Id|Title|Description|Estimation (Hours)|Assigned To|Status (To-do / In-Process / To-Review / Done)|
|US04|Añadir Interactividad|W-04|Añadir Interactividad|Implementar interactividad en elementos como botones y enlaces para mejorar la usabilidad.|8 hours|[Por Asignar]|To-do|
|US09|Implementación de Funcionalidades Faltantes|W-09|Implementación de Funcionalidades Faltantes|Completar la implementación de características como el inicio de sesión, el registro de usuarios, y otras funciones necesarias para el funcionamiento completo del sitio web.|14 hours|[Por Asignar]|To-do|
|US11|Actualización de Contenido|W-11|Actualización de Contenido|Actualizar el contenido del sitio web según sea necesario para mantenerlo relevante y preciso.|6 hours|[Por Asignar]|To-do|
|US12|Gestión de Errores y Excepciones|W-12|Gestión de Errores y Excepciones|Implementar manejo de errores y excepciones para proporcionar una experiencia de usuario robusta y sin problemas.|8 hours|[Por Asignar]|To-do|
|US13|Integración de Diseño de Interfaces|W-13|Integración de Diseño de Interfaces|Integrar el diseño de interfaces gráficas proporcionado por el equipo de diseño para asegurar coherencia visual en todo el sitio web.|10 hours|[Por Asignar]|To-do|
|US14|Cabecera (Header)|W-14|Cabecera (Header)|La estructura de la cabecera está definida con secciones como el logo y los elementos de navegación.|4 hours|[Por Asignar]|To-do|
|US15|Diseño Responsivo|W-15|Diseño Responsivo|El diseño del sitio web utiliza técnicas CSS Grid y Flexbox para garantizar una visualización adecuada en diferentes dispositivos y tamaños de pantalla.|8 hours|[Por Asignar]|To-do|
|US16|Estilos de Navegación|W-16|Estilos de Navegación|Se han aplicado estilos CSS para los elementos de navegación, incluyendo efectos de hover y sombras.|6 hours|[Por Asignar]|To-do|
|US17|Contenedor Principal|W-17|Contenedor Principal|El contenedor principal del sitio web se ha definido con una estructura de grid y secciones para organizar el contenido.|6 hours|[Por Asignar]|To-do|
|US18|Sección de Aterrizaje (Landing)|W-18|Sección de Aterrizaje (Landing)|Se ha creado una sección de aterrizaje con un título, subtítulo, imágenes y un botón de inicio.|8 hours|[Por Asignar]|To-do|
|US19|Estilos de Botón|W-19|Estilos de Botón|Los botones tienen estilos CSS aplicados, incluyendo colores, sombras y efectos de hover.|4 hours|[Por Asignar]|To-do|
|US20|Tarjetas de Notas (Note Live Cards)|W-20|Tarjetas de Notas (Note Live Cards)|Se han definido tarjetas de notas para mostrar información relevante de manera visualmente atractiva.|8 hours|[Por Asignar]|To-do|

---
- 5.2.1.3. Development Evidence for Sprint Review.
  
|Repository|Branch|Commit ID|Commit Message|Commit Message <br> Body|Commited On (Date)|  
|----------|------|---------|--------------|-------------------|------------------|
|ErickPalomino1923/LiveLinORG<br>/FrontEnd|Main|f2dd6d8731| | | |
|ErickPalomino1923/LiveLinORG<br>/FrontEnd|Main|674d37b56c| | | |
|APOGamer/LiveLinORG<br>/FrontEnd|Main|47bef22291| | | |
|APOGamer/LiveLinORG<br>/FrontEnd|Main|2a836c499e| | | |
|JCarbajal22/LiveLinORG<br>/FrontEnd|Main|d867e4d88f| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Main|b3aabb1055| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|4524d2e6bd| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|df60b4b190| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|6948049460| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|cffd774c83| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|2518c2a9dd| | | |
|Pmv612/LiveLinORG<br>/FrontEnd|Testimonios|6347a2351d| | | |
|ErickPalomino1923/LiveLinORG<br>/FrontEnd|Main|a770865894| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Main|3da62d2b18| | | |
|APOGamer/LiveLinORG<br>/FrontEnd|Main|2a64d8a75b| | | |
|APOGamer/LiveLinORG<br>/FrontEnd|Main|70d9639e89| | | |
|APOGamer/LiveLinORG<br>/FrontEnd|Main|515d752402| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Responsive|b30b72bb20| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Responsive|491f06fad2| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Main|491f06fad2| | | |
|Rrenzosilva/LiveLinORG<br>/FrontEnd|Main|6359222392| | | |
|ErickPalomino1923/LiveLinORG<br>/FrontEnd|Main|878f958fea| | | |
|ErickPalomino1923/LiveLinORG<br>/FrontEnd|Main|d600d2754e| | | |

- 5.2.1.4. Testing Suite Evidence for Sprint Review.
 ```gherkin
  Feature: US04: Añadir Interactividad
  Como usuario del sitio web
  Quiero interactuar con elementos como botones y enlaces
  Para mejorar mi experiencia de usuario

  Scenario: Interacción con botones
    Given Estoy en una página del sitio web que contiene botones interactivos
    When Hago clic en un botón
    Then Debería ver una acción o cambio en la página

  Scenario: Navegación a través de enlaces
    Given Estoy en una página del sitio web que contiene enlaces
    When Hago clic en un enlace
    Then Debería ser dirigido a la página correspondiente
   
Feature: US09: Implementación de Funcionalidades Faltantes
  Como desarrollador del sitio web
  Quiero completar la implementación de características necesarias
  Para garantizar el funcionamiento completo del sitio web

  Scenario: Implementación del inicio de sesión
    Given Estoy en la etapa final de desarrollo del inicio de sesión
    When Pruebo el inicio de sesión con credenciales válidas
    Then Debería poder acceder al área de usuario

  Scenario: Registro de nuevos usuarios
    Given Estoy en la etapa final de desarrollo del registro de usuarios
    When Completo el formulario de registro con información válida
    Then Debería recibir una confirmación de registro exitoso

Feature: US11: Actualización de Contenido
  Como editor del sitio web
  Quiero actualizar el contenido del sitio según sea necesario
  Para mantenerlo relevante y preciso

  Scenario: Actualización de información de contacto
    Given Estoy revisando la página de contacto del sitio web
    When Actualizo la dirección y los números de contacto
    Then Debería reflejarse la nueva información en la página

  Scenario: Agregar nuevas publicaciones al blog
    Given Estoy en el panel de administración del blog
    When Escribo y publico una nueva entrada en el blog
    Then Debería aparecer la nueva publicación en la página principal del blog

Feature: US12: Gestión de Errores y Excepciones
  Como desarrollador del sitio web
  Quiero implementar manejo de errores y excepciones
  Para proporcionar una experiencia de usuario robusta y sin problemas

  Scenario: Manejo de errores de formulario
    Given Estoy probando un formulario en el sitio web
    When Envío el formulario con información incompleta
    Then Debería recibir un mensaje de error indicando los campos obligatorios

  Scenario: Excepción en el servidor
    Given Estoy probando una función que interactúa con la base de datos
    When La base de datos no responde
    Then Debería recibir un mensaje de error amigable para el usuario

Feature: US13: Integración de Diseño de Interfaces
  Como desarrollador del sitio web
  Quiero integrar el diseño de interfaces proporcionado por el equipo de diseño
  Para asegurar coherencia visual en todo el sitio web

  Scenario: Integración del nuevo diseño de la página de inicio
    Given Tengo acceso al diseño actualizado de la página de inicio
    When Implemento el diseño utilizando HTML y CSS
    Then Debería ver la nueva página de inicio con el diseño actualizado

  Scenario: Ajuste de estilos en la página de contacto
    Given Tengo acceso al diseño actualizado de la página de contacto
    When Ajusto los estilos CSS para que coincidan con el nuevo diseño
    Then Debería ver la página de contacto con la misma apariencia que el diseño proporcionado

Feature: US14: Cabecera (Header)
  Como usuario del sitio web
  Quiero que la cabecera esté bien definida con secciones como el logo y los elementos de navegación
  Para una navegación intuitiva y clara

  Scenario: Verificación de elementos en la cabecera
    Given Estoy en la página principal del sitio web
    When Miro la cabecera de la página
    Then Debería ver el logo de la empresa y los elementos de navegación

Feature: US15: Diseño Responsivo
  Como usuario del sitio web
  Quiero que el diseño se adapte correctamente a diferentes dispositivos y tamaños de pantalla
  Para una experiencia de usuario consistente en todos los dispositivos

  Scenario: Verificación del diseño en dispositivos móviles
    Given Estoy en la página principal del sitio web desde un dispositivo móvil
    When Navego por el sitio web
    Then Debería ver que el diseño se adapta adecuadamente a la pantalla del dispositivo

  Scenario: Verificación del diseño en tabletas
    Given Estoy en la página principal del sitio web desde una tableta
    When Navego por el sitio web
    Then Debería ver que el diseño se adapta adecuadamente al tamaño de la pantalla de la tableta

Feature: US16: Estilos de Navegación
  Como usuario del sitio web
  Quiero que los elementos de navegación tengan estilos aplicados, incluyendo efectos de hover y sombras
  Para una experiencia visual atractiva y una navegación intuitiva

  Scenario: Estilos de enlaces
    Given Estoy en una página del sitio web que contiene enlaces
    When Paso el cursor sobre un enlace
    Then Debería ver un cambio en el estilo del enlace, como un cambio de color o una sombra

  Scenario: Estilos de menú desplegable
    Given Estoy en una página del sitio web que contiene un menú desplegable
    When Paso el cursor sobre el menú desplegable
    Then Debería ver una animación suave y atractiva al desplegar el menú

Feature: US17: Contenedor Principal
  Como usuario del sitio web
  Quiero que el contenido principal esté bien organizado con una estructura clara y fácil de entender
  Para una experiencia de navegación intuitiva

  Scenario: Verificación de la estructura del contenedor principal
    Given Estoy en una página del sitio web
    When Miro la estructura del contenedor principal
    Then Debería ver secciones claramente definidas con contenido relevante en cada una

Feature: US18: Sección de Aterrizaje (Landing)
  Como usuario del sitio web
  Quiero que la sección de aterrizaje tenga un diseño atractivo con un título, subtítulo, imágenes y un botón de inicio
  Para una primera impresión positiva y una navegación fácil

  Scenario: Verificación de elementos en la sección de aterrizaje
    Given Estoy en la página de inicio del sitio web
    When Miro la sección de aterrizaje
    Then Debería ver un título llamativo, un subtítulo descriptivo, imágenes atractivas y un botón de inicio visible

Feature: US19: Estilos de Botón
  Como usuario del sitio web
  Quiero que los botones tengan estilos CSS aplicados, incluyendo colores, sombras y efectos de hover
  Para una experiencia visual atractiva y una clara indicación de las acciones disponibles

  Scenario: Estilo de botón primario
    Given Estoy en una página del sitio web que contiene un botón principal
    When Paso el cursor sobre el botón
    Then Debería ver un cambio en el estilo del botón, como un efecto de sombra o un cambio de color

Feature: US20: Tarjetas de Notas (Note Live Cards)
  Como usuario del sitio web
  Quiero que se muestren tarjetas de notas con información relevante de manera visualmente atractiva
  Para una fácil visualización de la información importante

  Scenario: Verificación de tarjetas de notas en la página principal
    Given Estoy en la página principal del sitio web
    When Miro las tarjetas de notas en la página
    Then Debería ver información relevante presentada de forma visualmente atractiva en cada tarjeta
```

- 5.2.1.5. Execution Evidence for Sprint Review.

Durante este sprint, se completaron las siguientes tareas:

1. **Mejoras de Accesibilidad:**
   - Se aseguró que el sitio web sea accesible para usuarios con discapacidades, incluyendo la navegación por teclado y el uso de lectores de pantalla.

2. **Validación de HTML y CSS:**
   - Se validó el código HTML y CSS para asegurar que cumpla con los estándares y no contenga errores.

3. **Optimización de Carga:**
   - Se optimizó el tiempo de carga del sitio web para mejorar la experiencia del usuario.

4. **Añadir Interactividad:**
   - Se implementó interactividad en elementos como botones y enlaces para mejorar la usabilidad.

5. **Mejoras de SEO:**
   - Se optimizó el sitio web para mejorar su visibilidad en los motores de búsqueda.

6. **Refactorización de Clases y Selectores:**
   - Se revisaron y refactorizaron las clases y selectores en el CSS para mejorar la legibilidad y mantenibilidad del código.

7. **Pruebas de Cross-Browser:**
   - Se realizaron pruebas exhaustivas en diferentes navegadores para asegurar la compatibilidad y el rendimiento del sitio web.

8. **Documentación:**
   - Se documentó el código HTML y CSS para facilitar el mantenimiento futuro y la colaboración entre desarrolladores.

9. **Implementación de Funcionalidades Faltantes:**
   - Se completó la implementación de características como el inicio de sesión, el registro de usuarios, y otras funciones necesarias para el funcionamiento completo del sitio web.

10. **Seguridad:**
    - Se implementaron medidas de seguridad apropiadas para proteger el sitio web contra vulnerabilidades y ataques maliciosos.

11. **Actualización de Contenido:**
    - Se actualizó el contenido del sitio web según sea necesario para mantenerlo relevante y preciso.

12. **Gestión de Errores y Excepciones:**
    - Se implementó manejo de errores y excepciones para proporcionar una experiencia de usuario robusta y sin problemas.

13. **Integración de Diseño de Interfaces:**
    - Se integró el diseño de interfaces gráficas proporcionado por el equipo de diseño para asegurar coherencia visual en todo el sitio web.

14. **Cabecera (Header):**
    - Se definió la estructura de la cabecera con secciones como el logo y los elementos de navegación.

15. **Diseño Responsivo:**
    - Se utilizó técnicas CSS Grid y Flexbox para garantizar una visualización adecuada en diferentes dispositivos y tamaños de pantalla.

16. **Estilos de Navegación:**
    - Se aplicaron estilos CSS para los elementos de navegación, incluyendo efectos de hover y sombras.

17. **Contenedor Principal:**
    - Se definió el contenedor principal del sitio web con una estructura de grid y secciones para organizar el contenido.

18. **Sección de Aterrizaje (Landing):**
    - Se creó una sección de aterrizaje con un título, subtítulo, imágenes y un botón de inicio.

19. **Estilos de Botón:**
    - Se aplicaron estilos CSS a los botones, incluyendo colores, sombras y efectos de hover.

20. **Tarjetas de Notas (Note Live Cards):**
    - Se definieron tarjetas de notas para mostrar información relevante de manera visualmente atractiva.


- 5.2.1.6. Services Documentation Evidence for Sprint Review.
  Durante este sprint, se documentaron los servicios proporcionados por el sistema. La documentación de los servicios incluye detalles sobre la API, los puntos finales, los métodos admitidos, los parámetros requeridos y las respuestas esperadas. A continuación se presenta un resumen de la documentación de los servicios:
  1. **API de Usuarios:**
   - Endpoint: `/api/users`
   - Métodos admitidos: GET, POST, PUT, DELETE
   - Parámetros requeridos: Ninguno para GET, datos del usuario para POST y PUT, ID de usuario para DELETE
   - Respuestas esperadas: Datos de usuario para GET, mensaje de confirmación para POST y PUT, mensaje de éxito para DELETE

2. **API de Productos:**
   - Endpoint: `/api/products`
   - Métodos admitidos: GET, POST, PUT, DELETE
   - Parámetros requeridos: Ninguno para GET, datos del producto para POST y PUT, ID de producto para DELETE
   - Respuestas esperadas: Datos del producto para GET, mensaje de confirmación para POST y PUT, mensaje de éxito para DELETE

3. **API de Pedidos:**
   - Endpoint: `/api/orders`
   - Métodos admitidos: GET, POST
   - Parámetros requeridos: Ninguno para GET, datos del pedido para POST
   - Respuestas esperadas: Datos del pedido para GET, mensaje de confirmación para POST

- 5.2.1.7. Software Deployment Evidence for Sprint Review.
  Durante este sprint, se desplegó la versión actualizada del software en el entorno de producción. El proceso de implementación incluyó las siguientes etapas:
  
  1. **Pruebas de Integración:**
   - Se realizaron pruebas exhaustivas en el entorno de desarrollo para garantizar que todas las funcionalidades estén correctamente integradas.

2. **Pruebas de Usuario Final:**
   - Se llevó a cabo una fase de pruebas beta con usuarios finales para recopilar comentarios y detectar posibles problemas de usabilidad.

3. **Despliegue en Producción:**
   - Se desplegó la versión final en el entorno de producción después de que se completaran con éxito las pruebas de integración y usuario final.

4. **Monitorización Post-Despliegue:**
   - Se estableció un sistema de monitorización continua para supervisar el rendimiento y la estabilidad del sistema después del despliegue en producción.

- 5.2.1.8. Team Collaboration Insights during Sprint.    
    Durante este sprint, se observaron varios aspectos destacados en cuanto a la colaboración del equipo:
1. **Reuniones Diarias Efectivas:**
   - Se llevaron a cabo reuniones diarias donde todos los miembros del equipo compartieron actualizaciones sobre el progreso de las tareas asignadas y discutieron posibles obstáculos.

2. **Comunicación Transparente:**
   - Se fomentó una comunicación abierta y transparente entre los miembros del equipo, lo que permitió resolver rápidamente cualquier problema que surgiera durante el sprint.

3. **Colaboración en la Resolución de Problemas:**
   - Los miembros del equipo colaboraron estrechamente para resolver problemas técnicos y tomar decisiones importantes relacionadas con el desarrollo del proyecto.

4. **Apoyo Mutuo:**
   - Se brindó apoyo mutuo entre los miembros del equipo, lo que ayudó a mantener un ambiente de trabajo positivo y productivo durante todo el sprint.

- 5.3. Validation Interviews.
- 5.3.1. Diseño de Entrevistas.
- 5.3.2. Registro de Entrevistas.
- 5.3.3. Evaluaciones según heurísticas.
- 5.3.4. Video About-the-Product.

## Conclusiones

- Conclusiones y recomendaciones.
  ### Conclusiones:

- Durante el sprint, se lograron avances significativos en el desarrollo del proyecto, cumpliendo con la mayoría de los objetivos establecidos.
  
- La colaboración efectiva entre los miembros del equipo fue un factor clave para el éxito del sprint, permitiendo resolver desafíos de manera oportuna y eficiente.
  
- La implementación de prácticas ágiles demostró ser beneficiosa para la gestión del proyecto, facilitando la adaptación a cambios y mejorando la productividad del equipo.

### Recomendaciones:

- Continuar fomentando la comunicación abierta y transparente entre los miembros del equipo, así como la colaboración activa en la resolución de problemas.
  
- Realizar una revisión retrospectiva al finalizar cada sprint para identificar áreas de mejora y ajustar las estrategias de trabajo según sea necesario.
  
- Explorar herramientas y técnicas adicionales para mejorar la eficiencia y la calidad del desarrollo, como la automatización de pruebas y la implementación continua.

---

- Video About-the-Team.

## Bibliografía 
## Anexos
