
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

| Integrante                         | Descripción del Perfil                                                                                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
| Adrián Enrique Jesús Palma Obispo | Curso la carrera de Ingeniería de Software de 5to Ciclo. Experiencia trabajando en equipo, aportando en diversas áreas y ayudando en tecnologías. Capacidad para aprender rápido. Curioso y puntual. |
| Erick Joaquin Palomino Santa Cruz | Curso el quinto ciclo de la carrera de Ingeneria de Software. Me gusta aprender cosas nuevas y trabajar grupalmente para lograr una meta. |
| Joaquín Alonso Carbajal Pozzo     | Actualmente curso la carrera de Ingeniería de Software. Me gusta aprender sobre nuevas tecnologías y ponerlas en práctica lo antes posible. |
|                                   |                                                                                                                  |
|                                   |                                                                                                                  |



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
- 2.2. Análisis competitivo.
- 2.3. Estrategias y tácticas frente a competidores.
- 2.4. Entrevistas.
  - 2.4.1. Diseño de entrevistas.
  - 2.4.2. Registro de entrevistas.
  - 2.4.3. Análisis de entrevistas.
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
- 2.7. User Task Matrix.
- 2.8. User Journey Mapping.
- 2.9. Empathy Mapping.
- 2.10. As-is Scenario Mapping.
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
- 3.2. User Stories.
- 3.3. Impact Mapping.
- 3.4. Product Backlog.

### 4. Capítulo IV: Product Design

- 4.1. Style Guidelines.
  - 4.1.1. General Style Guidelines.
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
  - 4.4.2. Web Applications Wireflow Diagrams.
  - 4.4.3. Web Applications Mock-ups.
  - 4.4.4. Web Applications User Flow Diagrams.
  - 4.4.5. Web Applications Prototyping.
- 4.5. Domain-Driven Software Architecture.
  - 4.5.1. Software Architecture Context Diagram.
  - 4.5.2. Software Architecture Container Diagrams.
  - 4.5.3. Software Architecture Components Diagrams.
- 4.6. Software Object-Oriented Design.
  - 4.6.1. Class Diagrams.
  - 4.6.2. Class Dictionary.
- 4.7. Database Design.
  - 4.7.1. Database Diagram.

### 5. Capítulo V: Product Implementation, Validation & Deployment

- 5.1. Software Configuration Management.
  - 5.1.1. Software Development Environment Configuration.
  - 5.1.2. Source Code Management.
  - 5.1.3. Source Code Style Guide & Conventions.
  - 5.1.4. Software Deployment Configuration.
- 5.2. Landing Page, Services & Applications Implementation.
  - 5.2.1. Sprint n
    - 5.2.1.1. Sprint Planning.
    - 5.2.1.2. Sprint Backlog.
    - 5.2.1.3. Development Evidence for Sprint Review.
    - 5.2.1.4. Testing Suite Evidence for Sprint Review.
    - 5.2.1.5. Execution Evidence for Sprint Review.
    - 5.2.1.6. Services Documentation Evidence for Sprint Review.
    - 5.2.1.7. Software Deployment Evidence for Sprint Review.
    - 5.2.1.8. Team Collaboration Insights during Sprint.
- 5.3. Validation Interviews.
  - 5.3.1. Diseño de Entrevistas.
  - 5.3.2. Registro de Entrevistas.
  - 5.3.3. Evaluaciones según heurísticas.
  - 5.3.4. Video About-the-Product.

## Conclusiones

- Conclusiones y recomendaciones.
- Video About-the-Team.

## Bibliografía 
## Anexos
