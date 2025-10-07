
## **Universidad Peruana De Ciencias Aplicadas**  

 <p align="center"> <img src = "https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img> 
 </p>

 
### Facultad de Ingenieria  
### Carrera de Ingenieria de Software   
### Ciclo: 2025-02
### 7385 | Desarrollo de Aplicaciones Open Source 
### Profesor: Juan Antonio Flores Moroco

### **Informe de Trabajo Final**  
### Startup: SpeakingUp
### Producto: Quizbee  

### Integrantes:
- Vidal Malaga, Jareth Beycker  (u202316878)
- Geronimo Quispe ,Pablo Antonio(u202314304)
- Acosta Elera, Abraam Bernabe  (u202219199)
- Alejandro Franklin, Mendoza Vergara (u202312343)
---

### **Registro de Versiones del Informe**
| Versión | Fecha       | Autor             | Descripción de modificación            |
|---------|-------------|-------------------|----------------------------------------|
| 0.1     | 06/04/2025  | Todos los integrantes          | Desarrollo del capítulo 1 y 2             |
| 0.2     | 12/04/2025  | Todos los integrantes          | Desarrollo del capítulo 3                    |
| 0.3     | 18/04/2025  | Todos los integrantes                 | Desarrollo del capítulo 4 y sprint 1         |


---

### **Project Report Collaboration Insights**
En esta sección el equipo indica el URL del repositorio para el Project Report en la
organización de GitHub del equipo. Adicionalmente, para cada entrega explica cómo
se han desarrollado las actividades de elaboración del informe y se presenta
capturas en imagen de los analíticos de colaboración y commits en GitHub para el
repositorio del informe, realizados por los miembros del equipo. Todos los miembros
del equipo deben tener participación en la elaboración del informe. Esta sección
debe ir expandiéndose con descripciones y evidencias en cada entrega. Lo descrito y
evidenciado debe tener coherencia con el Registro de Versiones del Informe.

---

### **Contenido**

- [Capítulo I: Introducción](#capítulo-i-introducción)  
  - [1.1. Startup Profile](#11-startup-profile)  
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
  - [1.2. Solution Profile](#12-solution-profile)  
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)  
    - [1.2.2. Lean UX Process](#122-lean-ux-process)  
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)  
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)  
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)  

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  
  - [2.1. Competidores](#21-competidores)  
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)  
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
  - [2.2. Entrevistas](#22-entrevistas)  
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  
  - [2.3. Needfinding](#23-needfinding)  
    - [2.3.1. User Personas](#231-user-personas)  
    - [2.3.2. User Task Matrix](#232-user-task-matrix)  
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)  
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)  
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)  
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)  

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  
  - [3.1. User Stories](#31-user-stories)  
  - [3.2. Impact Mapping](#32-impact-mapping)  
  - [3.3. Product Backlog](#33-product-backlog)  

- [Capítulo IV: Product Design](#capítulo-iv-product-design)  
  - [4.1. Style Guidelines](#41-style-guidelines)  
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)  
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)  
  - [4.2. Information Architecture](#42-information-architecture)  
    - [4.2.1. Organization Systems](#421-organization-systems)  
    - [4.2.2. Labeling Systems](#422-labeling-systems)  
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
    - [4.2.4. Searching Systems](#424-searching-systems)  
    - [4.2.5. Navigation Systems](#425-navigation-systems)  
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)  
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)  
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)  
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)  
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)  
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)  
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)  
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)  
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
    - [4.7.1. Class Diagrams](#471-class-diagrams)  
  - [4.8. Database Design](#48-database-design)  
    - [4.8.1. Database Diagrams](#481-database-diagrams)  

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)  
  - [5.1. Software Configuration Management](#51-software-configuration-management)  
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
    - [5.1.2. Source Code Management](#512-source-code-management)  
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
    - [5.2.1. Sprint 1](#521-sprint-1)  
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)  
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-1)  
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

---

### **Student Outcome**

| Criterio específico                                                  | Acciones realizadas       | Conclusiones      | 
|----------------------------------------------------------------------|---------------------------|-------------------|
|Comunica oralmente con efectividad a diferentes rangos de audiencia   |<br>**Geronimo Quispe, Pablo Antonio**<br>**TB1:** Se centró en identificar un problema concreto que afecta a los usuarios y ofrecer una solución innovadora. En este caso, la descripción del problema, los usuarios potenciales y los objetivos del proyecto y Se encargó de desarrollar los antecedentes y problemáticas del trabajo para proporcionar una base sólida que facilite el análisis y la formulación de soluciones para la problemática junto al C4 model . <br>**Vidal Malaga, Jareth Beycker**<br>**TB1:**          | **TB1**: El trabajo realizado en TB1 contribuyó significativamente a la comprensión de la problemática, la formulación de soluciones innovadoras y la estructura de propuestas para resolver problemas específicos en el proyecto.        |
|Comunica por escrito con efectividad a diferentes rangos de audiencia |   |<br>**Geronimo Quispe, Pablo Antonio**<br>**TB1:** El proceso de definir una propuesta de valor refuerza la importancia del aprendizaje continuo en el análisis de problemas reales y en la creación de soluciones centradas en el usuario .      |    **TB1** El trabajo realizado en TB1 contribuyó significativamente a la comprensión de la problemática, la formulación de soluciones innovadoras y la estructura de propuestas para resolver problemas específicos en el proyecto.           |

---

# **Capítulo I: Introducción**
## 1.1. Startup Profile  

### 1.1.1. Descripción de la Startup  

**QuizzBee** es una startup innovadora que se enfoca en el desarrollo de soluciones empleando una arquitectura orientada a servicios, haciendo uso de tecnologías open-source. Mediante esta Startup buscamos  conectar a personas que dominan un idioma específico con aquellas que desean reforzar sus conocimientos, empleando herramientas dinámicas como **quizzes, retos interactivos y competencias gamificadas**.

**Misión:** Nuestra misión es brindar una plataforma  interactiva que promueva el aprendizaje colaborativo de idiomas, a través de dinámicas lúdicas que aumenten la motivación, refuercen la práctica constante y conecten a estudiantes con hablantes experimentados o nativos.  

**Visión:** Nuestra visión es consolidarnos como la plataforma líder en el aprendizaje práctico de idiomas a nivel global, ofreciendo experiencias interactivas que combinen diversión, gamificación y recompensas, transformando la manera en que las personas refuercen y compartan sus conocimientos.  

---
### 1.1.2. Perfiles de integrantes del equipo


| Foto                                                                                                                                                                 | Descripción |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| <img width="150" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/FotosNuestras/AlejandroMendoza.png" alt="Foto de Alejandro"> | Mi nombre es Alejandro Mendoza y soy estudiante de la carrera de Ingeniería de Software.Actualmente tengo experiencia en C++ y Python.Estoy interesado en seguir aprendiendo sobre diferentes lenguajes de programación y en la creación de distintas aplicaciones web y móviles,por lo que intento dar todo de mí para tener buenos resultados.|
| <img width="150" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/FotosNuestras/JarethVidal.jpg" alt="Foto de Jareth Vidal">   | Mi nombre es Jareth Vidal estoy estudiando la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo. Me gusta el deporte y mantenerme en constante aprendizaje. Tengo conocimientos en  C++, HTML, CSS y JavaScript y un poco de Python, así como habilidades para la adaptabilidad y la responsabilidad. |
| <img width="150" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/FotosNuestras/Pablo-photo.jpg" alt="Foto de Pablo">          |Mi nombre es Pablo,tengo 20 años y soy estudiante de Ingeniería de Software en la UPC, sede San Miguel. Soy una persona decidida, confiable, responsable y honesta con mi grupo de trabajo ,siendo lo más útil posible. Tengo conocimientos en C++,C# y php. Cada día trato de dar una mejor versión de mi y aprender de mis errores. |   

## 1.2.1. Antecedentes y Problemática (usando The 5W’s y 2H’s)  

### What (Qué)  
- **¿Cuál es el problema?** El aprendizaje de idiomas suele ser monótono, solitario y teórico. Muchos estudiantes carecen de espacios dinámicos para practicar con hablantes reales, lo que reduce la motivación y ralentiza su progreso.  
- **Relación con el usuario:** QuizzBee actúa como intermediario entre estudiantes y hablantes avanzados, brindando una solución práctica, motivadora y gamificada al proceso de aprendizaje.  

### When (Cuándo)  
- **¿Cuándo sucede el problema?** Cuando los estudiantes desean practicar fuera del aula y no encuentran opciones atractivas, o cuando hablantes avanzados buscan un espacio para compartir sus conocimientos.  
- **La tendencia hacia el aprendizaje online se aceleró notablemente en la última década** y, en particular, tras la pandemia de COVID-19, que demostró la efectividad y necesidad de las herramientas de conexión remota.
- **¿Cuándo utiliza el cliente el producto?** Durante su tiempo libre, sesiones de estudio, o en momentos en los que buscan practicar de forma breve y efectiva.  

### Where (Dónde)  
- **¿Dónde está el cliente cuando usa el producto?** En cualquier lugar con acceso a internet: hogar, transporte, oficina o universidad. Este fenómeno es global, pero es especialmente relevante en entornos digitales y conectados, donde las barreras geográficas se desdibujan.
El mercado objetivo es amplio, abarcando cualquier persona con acceso a internet y un smartphone o computador.  
- **¿Dónde surge el problema?** En entornos donde el aprendizaje es principalmente teórico y no hay suficientes oportunidades de práctica real.  

### Who (Quién)  
- **¿Quiénes están involucrados?**  
  - **Equipo:** encargados del desarrollo, soporte técnico y mejora continua de la plataforma.  
  - **Usuarios estudiantes:** quienes desean reforzar su aprendizaje.  
  - **Usuarios mentores:** quienes dominan un idioma y desean compartirlo.  
- **¿Quién lo utilizará?** Estudiantes, profesionales, viajeros, autodidactas y cualquier persona interesada en mejorar o practicar un idioma.  

### Why (Por qué)  
- La causa principal es la falta de plataformas que combinen **interactividad, gamificación y conexión entre hablantes**. Los métodos tradicionales resultan poco motivadores y no siempre fomentan la práctica constante.  
- **El aprendizaje tradicional suele ser lineal, puede resultar monótono y no simula las situaciones reales de comunicación**, donde se requiere agilidad, comprensión auditiva y capacidad de reacción.

### How (Cómo)  
- **Condiciones de uso:** Los usuarios acceden a QuizzBee para realizar prácticas rápidas, resolver retos, competir en quizzes y canjear recompensas.  
- **¿Cómo nos conocen?** A través de campañas digitales, redes sociales, instituciones educativas asociadas y recomendaciones de otros usuarios.  
- **¿Cómo prefieren acceder?** Mediante una app móvil y/o plataforma web intuitiva y atractiva.  

### How much (Cuánto)  
- Según el **EF English Proficiency Index 2023**, más del **70% de estudiantes de idiomas** en América Latina buscan plataformas adicionales para reforzar lo aprendido en clases.  
- El mercado global de aprendizaje digital de idiomas superará los **25 mil millones de dólares en 2025**, impulsado por soluciones interactivas y accesibles como QuizzBee.  
- **El mercado de e-learning de idiomas** tiene un valor de miles de millones de dólares y continúa en crecimiento, lo que indica un alto interés y disposición a pagar por soluciones efectivas y entretenidas.
---

## 1.2.2. Lean UX Process  

### 1.2.2.1. Lean UX Problem Statements  

**Problem Statement #1**  
Los estudiantes de idiomas carecen de plataformas dinámicas que combinen **práctica, interacción y motivación**. La mayoría de aplicaciones se enfocan en teoría y repeticiones, lo que reduce el interés y la constancia.  

**Pregunta clave:**  
¿Cómo podemos crear una experiencia gamificada que mantenga a los usuarios motivados a practicar de manera constante y divertida?  

**Problem Statement #2**  
Los hablantes avanzados o nativos que desean compartir sus conocimientos carecen de un espacio digital donde conectar con estudiantes de forma **estructurada, justa y motivadora**, sin depender de métodos informales como redes sociales o recomendaciones personales.  

**Pregunta clave:**  
¿Cómo podemos ofrecer un sistema que les permita obtener reconocimiento y recompensas por su participación, asegurando al mismo tiempo un aprendizaje real y efectivo para los estudiantes?  

---

### 1.2.2.2. Lean UX Assumptions  

#### Business Outcomes  
- Los usuarios necesitan una solución práctica, divertida y social que les permita **aprender y practicar idiomas** de manera interactiva.  
- La gamificación (quizzes, retos, vidas, puntos, recompensas) aumentará la motivación y el tiempo de uso.  
- Los niveles de suscripción crearán **nuevas fuentes de ingresos**:  
  - **Nivel Básico (gratuito):** acceso limitado con **vidas finitas**; cuando se acaban, el usuario debe esperar a que se recarguen.  
  - **Nivel Premium (pago):** acceso con **vidas ilimitadas**, quizzes exclusivos y recompensas adicionales.  

#### Usuarios principales  
- **Estudiantes de idiomas** (escolares, universitarios, profesionales).  
- **Autodidactas** que buscan practicar en su tiempo libre.  
- **Mentores o hablantes avanzados** que quieren compartir su conocimiento y recibir beneficios (puntos, reconocimiento, visibilidad).  

#### Competencia y Diferenciación  
- Aplicaciones como Duolingo o Quizlet también utilizan gamificación.  
- **Nuestra diferenciación**:  
  - Integración de retos y competencias entre usuarios.  
  - Recompensas canjeables en la tienda.  
  - Conexión directa con hablantes avanzados.  
  - Sistema de **vidas limitadas vs. vidas ilimitadas** para impulsar la motivación y la conversión a planes pagos.  

#### Riesgos  
- Que los usuarios del nivel básico se frustren con las vidas limitadas y abandonen la app en lugar de migrar al plan premium.  
- Que los mentores no encuentren suficiente incentivo para mantenerse activos.  

#### Mitigación  
- Ofrecer incentivos diarios (bonos de vidas, recompensas sorpresa).  
- Brindar pruebas gratuitas del plan premium.  
- Mantener el nivel básico suficientemente atractivo para enganchar, pero con límites que incentiven la conversión.  

---

### 1.2.2.3. Lean UX Hypothesis Statements  

- **Hipótesis 1:** Creemos que al ofrecer quizzes interactivos y gamificación con vidas limitadas, los usuarios practicarán con más constancia.  
  - **Éxito:** El 70% de los usuarios básicos regresa al menos 3 veces por semana.  

- **Hipótesis 2:** Creemos que al incluir un sistema de vidas limitadas en el plan básico y vidas ilimitadas en el plan premium, aumentaremos la conversión a suscripciones pagas.  
  - **Éxito:** Al menos el 25% de los usuarios activos gratuitos migra al plan premium en los primeros 3 meses.  

- **Hipótesis 3:** Creemos que los usuarios premium dedicarán más tiempo y generarán mayor engagement al no tener restricciones de vidas.  
  - **Éxito:** Los usuarios premium presentan un tiempo de uso 40% mayor que los gratuitos.  

- **Hipótesis 4:** Creemos que al ofrecer recompensas canjeables, los usuarios sentirán mayor motivación para seguir participando.  
  - **Éxito:** El 60% de los usuarios activos canjean recompensas al menos una vez al mes.  

- **Hipótesis 5:** Creemos que conectar estudiantes con hablantes avanzados mejorará la calidad de la práctica.  
  - **Éxito:** El 80% de los usuarios califican con 4 o 5 estrellas las interacciones con mentores.  

---
#### 1.2.2.4. Lean UX Canvas.
<p align="center"><img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-I/LeanUXCanva.jpg">
  
## 1.3. Segmentos objetivo.
Esta sección incluye la descripción de los segmentos asociados al dominio del problema, incluyendo características demográficas e información estadística de sustento.

A partir de la investigación realizada, se han identificado dos segmentos clave para el desarrollo de Pathly. Ambos representan actores principales en el proceso de orientación vocacional y han sido seleccionados debido a su influencia directa en la toma de decisiones académicas y su apertura al uso de herramientas digitales.


## Segmento objetivo #1. Personas que quisieran reforzar lo aprendido de algun idioma.

Usuarios que cuentan con conocimientos previos en un idioma (nivel básico o intermedio), pero sienten que olvidan lo aprendido si no lo practican constantemente. Buscan repasar de manera dinámica y entretenida a través de quizzes interactivos.  

**Objetivo principal:**  
Consolidar conocimientos ya adquiridos y ganar seguridad en el uso del idioma.  

**Aspectos Geográficos:**  
- Ciudades urbanas con acceso a internet y alta concentración de estudiantes.  
- Principalmente en países donde el inglés, francés u otros idiomas son demandados como segunda lengua.  

**Aspectos Demográficos:**  
- **Sexo:** Masculino y femenino
- **Edad:** 13 – 30 años (estudiantes de secundaria , universitarios y publico en general).  
- **Nivel socioeconómico:** Clase media y media-alta, con acceso a smartphones y conectividad.  

**Aspectos Psicográfica:**  
- **Estilo de vida:**Personas acostumbrados a usar apps educativas, redes sociales y plataformas digitales.  
- **Valores y creencias:** Valoran la mejora personal, el aprendizaje continuo y buscan mantener un hábito de estudio divertido.  


## Segmento objetivo #2. Personas que ya dominan algun idioma
Usuarios con nivel avanzado o fluido en el idioma, que desean perfeccionar sus habilidades, retarse con mayor dificultad y mantener un uso constante para no perder fluidez.  

**Aspectos Geográficos:**  
- Zona geográfica en la que viven: Urbana.
- Países con fuerte demanda de certificaciones internacionales de idiomas.  

**Aspectos Demográficos:**  
- **Sexo:**Masculino y femenino
- **Edad:** 20 – 40 años (universitarios avanzados y  profesionales).  
- **Nivel socioeconómico:** Clase media y media-alta, con disposición a pagar por planes premium.  

**Aspectos Psicográficos:**  
- **Estilo de vida:** Competitivos, motivados por la superación personal , profesional y buscan Recibir recompensas por lo que saben. 
- **Valores y creencias:** Ven el dominio del idioma como una herramienta clave para acceder a mejores oportunidades académicas y laborales.

---


# **Capítulo II: Requirements Elicitation & Analysis**
## 2.1. Competidores.
### 2.1.1. Competitive Analysis Landscape  

| Por qué llevar a cabo este análisis? | Este análisis es clave para entender el mercado de las plataformas digitales de aprendizaje de idiomas, identificar necesidades de los usuarios y cómo **QuizzBee** puede ofrecer soluciones innovadoras y efectivas para diferenciarse de sus competidores. |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| Características | Duolingo | Quizlet | Memrise | Busuu | **QuizzBee** |
|-----------------|----------|---------|---------|-------|-------------|
| **Perfil**      | Plataforma global para aprender idiomas de manera gamificada con ejercicios cortos y recompensas. | Aplicación centrada en el aprendizaje a través de flashcards y quizzes creados por la comunidad. | App que enseña idiomas con contenido audiovisual y repeticiones espaciadas. | Plataforma con cursos estructurados y tutorías de idioma con hablantes nativos. | Plataforma SaaS que conecta a *personas que quieren reforzar lo aprendido* con *personas que ya dominan el idioma* mediante quizzes, retos y speaking rooms; incorpora vidas, niveles y tienda de recompensas canjeables por certificados/exámenes. |
| **Ventaja competitiva**<br>¿Qué valor ofrece a los clientes? | Experiencia altamente gamificada con un sistema de niveles, vidas y recompensas. | Permite a los usuarios crear y compartir quizzes personalizados. | Uso de videos de hablantes nativos y repetición espaciada para mejorar la retención. | Interacción con hablantes nativos y cursos estructurados. | Combina contenido generado por usuarios avanzados + speaking rooms + sistema de puntos canjeables por certificados oficiales; incentiva creación de contenido y práctica real. |
| **Mercado objetivo** | Estudiantes y adultos que buscan aprender un idioma desde cero o reforzar conocimientos. | Estudiantes y profesores que buscan reforzar conocimientos a través de quizzes. | Personas interesadas en aprender vocabulario y frases con apoyo audiovisual. | Estudiantes y profesionales que desean mejorar competencias lingüísticas con apoyo humano. | Estudiantes, autodidactas, jóvenes profesionales y hablantes avanzados que desean crear contenido; instituciones educativas y academias de idiomas. |
| **Estrategias de marketing** | Marketing de contenido, gamificación extrema, publicidad en redes. | Uso en contextos académicos, alianzas con profesores y colegios. | Estrategia freemium y publicidad digital. | Suscripción premium y alianzas con instituciones educativas. | Alianzas con academias y universidades, campus ambassadors, marketing de contenido orientado a preparación de exámenes y creador de contenido (UGC), campañas en redes y eventos de speaking. |
| **Precios & Costos** | Modelo freemium con publicidad; versión premium: $7 – $15/mes. | Freemium, premium desde $3 – $7/mes. | Freemium, premium desde $5 – $10/mes. | Premium desde $7 – $15/mes con tutorías adicionales. | **Freemium** (vidas limitadas). Premium: vidas ilimitadas, speaking rooms y contenido exclusivo — propuesta orientativa $5–$12/mes; monetización adicional por canje de certificaciones y comisiones a creadores. |
| **Productos & Servicios** | Ejercicios de vocabulario, gramática, listening, sistema de vidas. | Flashcards, quizzes creados por usuarios. | Videos, vocabulario, repeticiones espaciadas. | Cursos estructurados, práctica con tutores. | Quizzes y retos gamificados, creador de quizzes, speaking rooms, sistema de puntos y tienda de recompensas (vouchers para exámenes/certificados), dashboards de progreso, panel para creadores. |
| **Canales de distribución**  | App móvil y plataforma web. | Web y app móvil. | App móvil y web. | App móvil y web. | App móvil y plataforma web; integraciones con academias, landing page institucional y marketplace de creadores. |
| **Fortalezas**               | Gran base de usuarios, gamificación. | Gran biblioteca generada por usuarios. | Material audiovisual auténtico. | Tutorías con hablantes nativos. | Diferenciación por **canje real de puntos por certificados**, enfoque en speaking y UGC, incentivos para creadores y doble segmento (aprendices + expertos). |
| **Debilidades**              | Poca práctica real de speaking. | Calidad variable del contenido UGC. | Aprendizaje no siempre estructurado. | Coste elevado para acceso completo. | Necesita alcanzar masa crítica de usuarios y cerrar alianzas con certificadores; inversión inicial en adquisición y verificación de creadores. |
| **Oportunidades**            | Expandir speaking rooms. | Integración en instituciones. | Incorporar certificaciones oficiales. | Expandir en mercados emergentes. | Alianzas con centros de examen, venta de vouchers, integración B2B con academias/universidades, nichos (preparación TOEFL/IELTS). |
| **Amenazas**                 | Competencia gratuita y copias de features. | Plataformas con gamificación más atractiva. | Apps más completas. | Alternativas económicas. | Competidores grandes podrían replicar el canje por certificados o speaking rooms; dependencia de acuerdos con certificadoras. |

---
### 2.1.2. Estrategias y Tácticas frente a Competidores  

Estas son las principales estrategias que aplicará **QuizzBee**:  

- **Conectar segmentos de usuarios**: personas que quieren reforzar lo aprendido con usuarios avanzados que ya dominan el idioma y pueden crear quizzes, retos y speaking rooms.  
- **Sistema de gamificación innovador**: uso de niveles, vidas limitadas en el plan básico y vidas ilimitadas en el plan premium para fomentar la suscripción.  
- **Recompensas reales**: sistema de puntos canjeables por beneficios tangibles como acceso a exámenes oficiales (TOEFL, IELTS) o certificados de participación.  
- **Contenido generado por usuarios avanzados**: los expertos en el idioma podrán crear quizzes y retos que enriquezcan la comunidad, motivando tanto a aprendices como a creadores.  
- **Alianzas con instituciones educativas**: integración de QuizzBee como herramienta complementaria en colegios, universidades y academias de idiomas.  
- **Foco en speaking rooms**: diferenciarse de competidores al potenciar el speaking colaborativo y en tiempo real entre estudiantes y usuarios avanzados.  
## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

## Segmento #1: Personas que quieren reforzar lo aprendido

### Preguntas principales
1. ¿Cómo te sientes normalmente cuando intentas practicar el idioma fuera de clases o cursos?  
2. ¿Qué sueles hacer para reforzar lo que aprendiste en clases (apps, libros, videos, conversaciones)?  
3. ¿Qué tan fácil o difícil es para ti mantener la constancia en la práctica del idioma?  
4. ¿Qué es lo que más te preocupa al momento de practicar solo? (ej. olvidar vocabulario, errores de gramática, pronunciación).  
5. ¿Qué valoras más en una herramienta para practicar idiomas (diversión, rapidez, feedback, variedad de temas)?  
6. ¿Con qué frecuencia dedicas tiempo a reforzar lo aprendido en un idioma?  
7. ¿Alguna vez has sentido que lo aprendido en cursos o clases se te olvida porque no lo practicas? ¿Cómo lo resolviste?  
8. ¿Qué importancia le das a contar con un sistema que te dé feedback inmediato sobre tus errores?  
9. ¿Te interesaría usar una plataforma de quizzes y retos para reforzar idiomas? ¿Por qué?  
10. ¿Qué funcionalidades crees que harían esa plataforma útil y atractiva para ti?
11. ¿Qué tipo de retos (escritura, audio, conversación, vocabulario rápido) te motivan más?


### Preguntas complementarias
- ¿Qué buscas normalmente en internet cuando quieres practicar un idioma por tu cuenta?  
- ¿Cuánto confías en apps de idiomas actuales para realmente reforzar lo aprendido?  
- ¿En qué momentos específicos del día o la semana crees que te sería más útil tener acceso a una práctica rápida?  
- ¿Te sentirías cómodo usando una plataforma con un plan gratuito (vidas limitadas) y un plan premium (vidas ilimitadas)?  

---

## Segmento #2: Personas que ya dominan el idioma

### Preguntas principales
1. ¿Qué tipo de actividades realizas actualmente para mantener tu dominio del idioma?  
2. ¿Qué tan seguido practicas o usas el idioma en tu día a día?  
3. ¿Cómo mantienes la motivación para seguir mejorando si ya tienes un buen nivel?  
4. ¿Qué impacto tendría para ti perder fluidez en el idioma?  
5. ¿Qué criterios tomas en cuenta al elegir una herramienta digital para seguir practicando?  
6. ¿Has tenido experiencias negativas con plataformas de idiomas? ¿Qué aprendiste de esas situaciones?  
7. ¿Qué tan importante es para ti contar con retos avanzados (ej. vocabulario técnico, situaciones profesionales)?  
8. ¿Te interesaría crear quizzes y retos personalizados para otros usuarios? ¿Qué beneficios esperarías recibir a cambio?  
9. ¿Qué tan útil te parecería poder participar en reuniones virtuales de speaking con otros usuarios avanzados?  
10. ¿Cómo valorarías una plataforma que te otorgue puntos por tu participación y te permita canjearlos por exámenes oficiales (ej. TOEFL, IELTS)?  

### Preguntas complementarias
- ¿Qué te motivaría más: competir en rankings globales o colaborar creando contenido para otros?  
- ¿Qué herramientas digitales usas actualmente para practicar speaking y mantener tu nivel de conversación?  
- ¿Qué tan dispuesto estarías a pagar por un plan premium que te ofrezca beneficios como reuniones ilimitadas, quizzes exclusivos y certificados?  
- ¿Te sentirías más motivado si tu progreso dentro de la plataforma pudiera convertirse en una certificación oficial reconocida?  
### 2.2.2. Registro de entrevistas.
#### Segmento 1:
<img width ="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/entrevista1.png">

- Entrevista N°1: Diego Avalos
- Sexo: Masculino
- Edad: 21 años

- Ubicación en la que vive: Independencia, Lima, Perú

#### Entrevista: ####


[link https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EbkmdeLghNhGjq4V5uYy5esBiOXestT9hokV-ZV7bz5WRg?e=UARbDo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EXHY9vTo3TVKnJV3A4e2Ha4B1NsXtcJY6HnYjbc_acjhbA?e=aUP9ck)


- Momento en el que inicia: 0:03

- Duración: 5:00

**Resumen:**
Diego Ávalos es un joven interesado en mejorar su nivel de inglés. En la entrevista, compartió su experiencia y hábitos al momento de practicar idiomas fuera del entorno académico. Señaló que suele recurrir a plataformas como Duolingo, aunque considera que su efectividad puede ser limitada, calificándolas alrededor de un 6 o 7 en una escala del 1 al 10.
Diego mencionó que valora herramientas que ofrezcan diversión, variedad temática y, sobre todo, feedback inmediato cuando comete errores. Considera que una plataforma que le diga al instante en qué falló y por qué, sería mucho más útil para su proceso de aprendizaje.
Una de sus mayores dificultades es mantener la constancia y, en ocasiones, olvida lo aprendido en clases por no practicarlo con frecuencia. Aun así, busca reforzar sus conocimientos viendo videos, escuchando música o interactuando con contenido en inglés.
Sobre la propuesta de Quizbee, le pareció interesante una aplicación tipo Duolingo pero con vidas ilimitadas, retos personalizados por usuarios avanzados (tipo C1) y recompensas por desempeño. Cree que esto haría la práctica más atractiva y motivadora. También valoró positivamente la posibilidad de tener un plan premium con beneficios extra.
Finalmente, considera que una plataforma ideal debería combinar el juego, el aprendizaje práctico y el acompañamiento mediante feedback claro. Recalcó que lo más importante para él es tener una herramienta interactiva, efectiva y entretenida que le ayude a consolidar lo aprendido y avanzar en su dominio del idioma.




<img width ="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/entrevista2.png">


- Entrevista N°2:PaolaGarcia 
- Sexo: Femenino
- Edad: 18 años

- Ubicación en la que vive: San Martin de Porres, Lima, Perú

#### Entrevista: ####
[link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EbkmdeLghNhGjq4V5uYy5esBiOXestT9hokV-ZV7bz5WRg?e=UARbDo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EZVBbO-nSShMkVtyZqXMGywB2bbQ-m2QPlZqqa_MLAmDRQ?e=aPpPBE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

- Momento en el que inicia: 0:02

- Duración: 5:58

**Resumen:**
Paola García, de 18 años, considera interesante la propuesta de Quizbee, una plataforma que permite a usuarios avanzados crear retos de idioma para que otros los resuelvan y ganen recompensas. Le gusta la idea de usar quizzes, obtener feedback inmediato, y contar con una tienda de premios que motive a practicar.
Suele usar Duolingo, pero lo califica con un 6 o 7 de 10, ya que no siempre refuerza bien lo aprendido. Le interesa una plataforma con vidas ilimitadas, tanto gratuita como con plan premium. También mencionó que a veces se le dificulta mantener la constancia y teme olvidar lo aprendido, por lo que valora herramientas prácticas y entretenidas.
Sugiere incluir un ranking entre usuarios y contenido variado. En general, ve a Facebee como una plataforma útil y motivadora para aprender idiomas de forma más dinámica.
Finalmente, mostró interés en el uso de plataformas como Quizbee, ya que considera que los quizzes y retos creados por otros usuarios pueden ser una forma dinámica de reforzar sus conocimientos.

#### Segmento 2:


<img width ="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/entrevista3.PNG">


- Entrevista N°1: Anyelo Alejos
- Sexo: Masculino
- Edad: 20 años

- Ubicación en la que vive: Independencia, Lima, Perú

#### Entrevista: ####
[link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EbkmdeLghNhGjq4V5uYy5esBiOXestT9hokV-ZV7bz5WRg?e=UARbDo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202314304_upc_edu_pe/EWKynO5MHTxHn0o0V0fRJdsBl5PyVsWey90-rqW_i3YSZA?e=eGyWfX&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


- Momento en el que inicia: 0:05

- Duración: 6:35

**Resumen:**
Anyelo alejos nos comparte su experiencia con el aprendizaje y mantenimiento de idiomas a través del proyecto Quizbee, una plataforma SaaS que busca reforzar idiomas mediante quizzes y retos creados por usuarios. Actualmente, Pedro realiza actividades frecuentes para mantener su dominio del idioma y utiliza diversas herramientas digitales, especialmente para practicar speaking.
Se mostró muy interesado en la idea de crear retos personalizados para otros usuarios, y valoró mucho la posibilidad de obtener puntos canjeables por exámenes oficiales, como el Cambridge, uno de los más solicitados. Para él, mantener un ranking y competir dentro de la plataforma sería una motivación adicional importante.
Pedro también destacó que es crucial que la plataforma incluya retos avanzados, vocabulario técnico y situaciones profesionales, para ajustarse a usuarios con nivel alto. Se mostró dispuesto a pagar por un plan premium que ofrezca beneficios exclusivos, como reuniones y quizzes limitados, y considera muy valioso que el progreso pueda convertirse en una certificación oficial reconocida. Finalmente Pedro ve a Quizbee como una plataforma que puede apoyar significativamente a usuarios avanzados a mantener y certificar su nivel de idioma mediante retos dinámicos y recompensas tangibles.



<img width ="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/entrevista4.PNG">


- Entrevista N°2: Liliana Quilcat
- Sexo: Femenino
- Edad: 38 años

- Ubicación en la que vive: Callao, Peru

#### Entrevista: ####
link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316878_upc_edu_pe/EZWkEJGZFOFDlQkg6khUE5UBJuBFZM_wwmNDtt7jmyMkrw?e=Uo4mVo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


- Momento en el que inicia: 0:02

- Duración: 4:46

**Resumen:**
Liliana Margarita Málaga Vidal mantiene su dominio del inglés mediante la lectura de artículos, viendo series y películas en el idioma, y trabajando con textos relacionados a su profesión. Utiliza el inglés entre dos y cuatro veces por semana en su entorno laboral, especialmente para interactuar con expertos internacionales. Su motivación para seguir mejorando proviene de su entorno profesional, ya que en su trabajo interactúa con personas que dominan el inglés, lo que le permite seguir aprendiendo y avanzando.

Liliana considera que la pérdida de fluidez en inglés sería una gran desventaja, especialmente en su entorno laboral donde la comunicación con expertos internacionales es clave. En cuanto a las herramientas digitales para aprender, prefiere aquellas que ofrecen contenidos avanzados y prácticos, y que permiten interacción en vivo, algo que le resultó difícil de encontrar al principio. Para ella, contar con retos avanzados en contextos profesionales es esencial para seguir progresando en el idioma.

Está interesada en crear quizzes y retos personalizados para ayudar a otros usuarios a mejorar su nivel de inglés, y valora la posibilidad de obtener algún tipo de reconocimiento o beneficio por sus contribuciones. Además, le parece muy valiosa la idea de participar en reuniones virtuales con otros usuarios avanzados, ya que estas experiencias simulan conversaciones reales y le ayudan a ganar confianza. Finalmente, le gustaría que una plataforma le otorgue puntos por su participación, que luego podría canjear por exámenes oficiales o certificaciones, lo que convertiría su práctica en un beneficio concreto.

<img width ="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/entrevista5.PNG">

- Entrevista N°3: Diego Vela
- Sexo: Masculino
- Edad: 40 años

- Ubicación en la que vive: San Miguel, Peru

#### Entrevista: ####
link: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316878_upc_edu_pe/EZWkEJGZFOFDlQkg6khUE5UBJuBFZM_wwmNDtt7jmyMkrw?e=Uo4mVo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316878_upc_edu_pe/EQs8KuoZROtNugXc4s3brQABOx9pbT8eBCT9qUDb6AHvGw?e=EhTAJR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


- Momento en el que inicia: 0:01

- Duración: 3:54

**Resumen:** La persona entrevistada, mantiene su dominio del idioma principalmente viendo series, escuchando música y leyendo artículos en inglés unas tres veces por semana. Su motivación está ligada a mejores oportunidades laborales y a no perder el esfuerzo que le costó alcanzar su nivel actual. Considera negativo perder fluidez, ya que afectaría su trabajo, y al elegir plataformas valora la facilidad de uso, la práctica real y los retos avanzados, sobre todo en vocabulario técnico y profesional. Ha tenido experiencias negativas con apps muy básicas y cree útil participar en reuniones virtuales de speaking, ya que en Lima no siempre hay espacios para practicar. Le interesa la idea de crear quizzes a cambio de beneficios y se motiva más con rankings globales. Aunque usa herramientas como YouTube y Tandem, pagaría un plan premium si el precio fuera accesible, y valora altamente que el progreso en la plataforma pueda convertirse en una certificación oficial reconocida.


### 2.2.3. Análisis de entrevistas.
## 2.3. Needfinding.
### 2.3.1. User Personas.
**User Persona 1:** Personas que quieren reforzar lo aprendido de algún idioma

<img src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/UserPersona_Segmento1.png" alt="User Persona 1" width="600"/>

**User Persona 2:** Personas que ya dominan algún idioma

<img src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/UserPersona_Segmento2.png" alt="User Persona 2" width="600"/>

### 2.3.2. User Task Matrix.
- **Primer Segmento:** Personas que quisieran reforzar lo aprendido de algún idioma


| Tarea del Usuario              | Frecuencia | Importancia |
|--------------------------------|-------------|-------------|
| Buscar quizzes por nivel        | Alta        | Alta        |
| Resolver quizzes                | Muy Alta    | Muy Alta    |
| Navegar entre preguntas         | Alta        | Alta        |
| Controlar el tiempo de práctica | Media       | Alta        |
| Confirmar finalización          | Media       | Media       |
| Revisar puntaje y resultados    | Muy Alta    | Muy Alta    |
| Revisar historial de quizzes    | Media       | Alta        |


- **Segundo Segmento:** Personas que ya dominan algún idioma 


| Tarea del Usuario               | Frecuencia | Importancia |
|---------------------------------|-------------|-------------|
| Crear nuevos quizzes             | Alta        | Muy Alta    |
| Editar quizzes existentes        | Media       | Alta        |
| Publicar quizzes creados         | Alta        | Muy Alta    |
| Revisar feedback recibido        | Media       | Alta        |
| Recibir notificación de feedback | Media       | Media       |
| Eliminar quizzes obsoletos       | Baja        | Media       |
| Revisar historial de quizzes     | Media       | Alta        |
| Moderar salas de speaking        | Media       | Alta        |



### 2.3.3. User Journey Mapping.

- Segmento 1: Personas que quisieran reforzar lo aprendido de algun idioma.
  
  <img width="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/JourneyMapping1.png" alt="Journey Mapping">


- Segmento 2: Personas que ya dominan algun idioma
  
<img width="555" height="300" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/JourneyMapping2.png" alt="Journey Mapping 2">

  
### 2.3.4. Empathy Mapping.
**User Persona 1:** Personas que quieren reforzar lo aprendido de algún idioma

<img src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/EmpathyMap1.png" alt="Empathy Map 1" width="600"/>

**User Persona 2:** Personas que ya dominan algún idioma

<img src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/EmpathyMap2.png" alt="Empathy Map 2" width="600"/>

## 2.4. Big Picture Event Storming.

<img src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-2/EventStorming.jpg" alt="EventStorming" width="600"/>

## 2.5. Ubiquitous Language.

| Término | Definición | Segmentos relacionados |
|---------|------------|------------------------|
| **Quiz (Cuestionario)** | Conjunto de preguntas diseñadas para reforzar o evaluar conocimientos de un idioma. | Novatos, Creadores |
| **Question (Pregunta)** | Elemento del quiz que plantea una consulta específica, generalmente con opciones. | Novatos, Creadores |
| **Answer (Respuesta)** | Opción seleccionada por el usuario frente a una pregunta, correcta o incorrecta. | Novatos |
| **Score (Puntaje)** | Resultado obtenido tras completar un quiz, calculado en base a respuestas correctas. | Novatos |
| **Feedback (Retroalimentación)** | Información que recibe el usuario sobre su desempeño, indicando aciertos, errores y sugerencias. | Novatos, Creadores |
| **Daily Quiz (Quiz Diario)** | Actividad breve publicada cada día para reforzar la práctica constante. | Novatos |
| **Progress (Progreso)** | Avance del usuario reflejado en historial, puntajes y métricas de aprendizaje. | Novatos |
| **Summary (Resumen)** | Pantalla final que muestra el puntaje total, respuestas correctas e incorrectas. | Novatos |
| **Ranking (Clasificación)** | Listado de usuarios ordenados por puntaje a nivel global, por país o por nivel. | Novatos |
| **Creator (Creador de Quizzes)** | Usuario avanzado que diseña y publica quizzes para los demás. | Creadores |
| **Speaking Session (Sesión de Speaking)** | Espacio en tiempo real donde los usuarios practican oralmente con otros. | Novatos, Creadores |
| **Role (Rol)** | Clasificación del usuario en la plataforma: Novato o Creador. | Novatos, Creadores |
| **History (Historial)** | Registro de quizzes resueltos y puntajes obtenidos a lo largo del tiempo. | Novatos |
| **Notification (Notificación)** | Mensaje enviado al usuario para avisar sobre feedback, logros o recordatorios. | Novatos, Creadores |
| **Premium (Suscripción Premium)** | Plan de pago que otorga beneficios adicionales como vidas ilimitadas y speaking sessions. | Novatos |
| **Life (Vida)** | Recurso limitado en modo gratuito que define cuántos quizzes se pueden resolver antes de esperar o pagar. | Novatos |
| **Feature Branch (Rama de Funcionalidad)** | Espacio de trabajo en el que se desarrolla una nueva característica antes de integrarla. | Creadores (equipo) |
| **Hotfix (Corrección Rápida)** | Cambio urgente en el sistema para resolver un error en producción. | Creadores (equipo) |


---

# **Capítulo III: Requirements Specification**
## 3.1. User Stories.

| User Story ID | Título | Description |Acceptance Criteria  | Epic Relacionado |
|---------------|--------|------|-----------------------------------|------------------|
| US01 | Registro de usuario | Como nuevo usuario, quiero registrarme en QuizzBee con mi correo y contraseña para poder acceder a la plataforma y crear mi perfil. | Given que un usuario desea acceder a QuizzBee, <br> When ingresa su correo y contraseña en el formulario de registro,<br> Then el sistema crea una nueva cuenta y permite que el usuario acceda a la plataforma de manera segura. | E01 |
| US02 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión con mis credenciales para acceder a mi cuenta y utilizar las funcionalidades de la plataforma. | Given que un usuario ya tiene una cuenta en QuizzBee <br> When ingresa su correo y contraseña en el formulario de inicio de sesión,<br>Then el sistema verifica sus credenciales y le permite acceder a la plataforma de manera segura. | E01 |
| US03 | Recuperación de contraseña | Como usuario que olvidó su contraseña, quiero poder recuperarla a través de mi correo electrónico para volver a acceder a mi cuenta sin perder mis datos. | Given que un usuario olvidó su contraseña, <br> When solicita recuperar su cuenta e ingresa su correo electrónico en la opción de "Olvidé mi contraseña", <br> Then el sistema envía un enlace de recuperación al correo proporcionado para que el usuario pueda restablecer su contraseña de manera segura. | E01 |
| US04 | Experiencia de autenticación guiada | Como usuario durante el proceso de registro, quiero recibir mensajes claros cuando cometa errores en los campos para poder corregirlos fácilmente. | Given que estoy en el proceso de registro,<br> When cometo un error en un campo,<br> Then el sistema me muestra mensajes claros para corregirlo. | E02 |
| US05 | Validación de correo | Como nuevo usuario, quiero validar mi correo electrónico después del registro para activar mi cuenta y acceder completamente a la plataforma. | Given que me registro por primera vez,<br> When recibo el correo de validación,<br> Then debo confirmar para activar mi cuenta. | E02 |
| US06 | Configuración de perfil | Como usuario autenticado, quiero poder configurar mi perfil personal para personalizar mi experiencia en la plataforma según mis preferencias y nivel. | Given que estoy autenticado,<br> When accedo a configuración,<br> Then puedo editar mi nombre, idioma y nivel de inglés. | E03 |
| US07 | Cambio de contraseña | Como usuario preocupado por la seguridad, quiero poder cambiar mi contraseña en cualquier momento para mantener mi cuenta protegida. | Given que deseo más seguridad,<br> When ingreso mi contraseña actual y la nueva,<br> Then el sistema actualiza mi clave exitosamente. | E03 |
| US08 | Eliminar cuenta | Como usuario que ya no desea usar la plataforma, quiero poder eliminar permanentemente mi cuenta para que mis datos sean borrados del sistema. | Given que quiero darme de baja,<br> When confirmo la eliminación de mi cuenta,<br> Then el sistema borra mis datos de forma irreversible. | E03 |
| US09 | Cerrar Sesion | Como usuario autenticado, quiero poder cerrar sesión de forma segura para proteger mi cuenta cuando termine de usar la plataforma. | Given que el usuario está autenticado en su cuenta,<br> When selecciona la opción "Cerrar sesión", <br> Then el sistema finaliza la sesión actual | E03 |
| US10 | Creación de quiz | Como creador de contenido, quiero poder crear quizzes con preguntas y respuestas personalizadas para compartir conocimiento con otros usuarios. | Given que soy creador,<br> When accedo a la sección "crear quiz" e ingreso preguntas,<br> Then el sistema guarda y publica el quiz. | E04 |
| US11 | Publicación de quiz | Como creador, quiero poder publicar mis quizzes terminados para que estén disponibles para otros usuarios en la plataforma. | Given que terminé de crear un quiz,<br> When lo marco como "publicar",<br> Then se vuelve visible para los demás usuarios. | E04 |
| US12 | Edición de quiz publicado | Como creador, quiero poder editar mis quizzes ya publicados para mejorarlos o corregir errores manteniendo un historial de cambios. | Given que soy creador,<br> When actualizo un quiz ya publicado,<br> Then los cambios se reflejan manteniendo historial. | E04 |
| US13 | Eliminación de quiz | Como creador, quiero poder eliminar mis quizzes cuando ya no los considere útiles o relevantes para mantener mi contenido actualizado. | Given que ya no quiero un quiz,<br> When lo elimino,<br> Then desaparece del listado público. | E04 |
| US14 | Búsqueda de quizzes por idioma | Como usuario, quiero poder filtrar quizzes por idioma específico para encontrar contenido en el idioma que deseo practicar. | Given que estoy en la sección de quizzes,<br> When filtro por idioma,<br> Then solo veo quizzes en ese idioma. | E05 |
| US15 | Búsqueda de quizzes por nivel | Como usuario, quiero poder filtrar quizzes por nivel de dificultad para encontrar contenido apropiado para mis habilidades actuales. | Given que estoy buscando prácticas,<br> When selecciono mi nivel A2,<br> Then se listan únicamente quizzes A2. | E05 |
| US16 | Búsqueda de quizzes por categoría | Como usuario, quiero poder filtrar quizzes por categoría temática para enfocarme en áreas específicas de estudio como vocabulario, gramática, etc. | Given que quiero reforzar vocabulario,<br> When filtro por categoría "vocabulary",<br> Then se muestran solo quizzes de vocabulario. | E05 |
| US17 | Resolver quiz | Como usuario, quiero poder resolver quizzes disponibles en la plataforma para practicar mis conocimientos y obtener retroalimentación inmediata. | Given que inicio un quiz,<br> When respondo todas las preguntas,<br> Then recibo mi puntaje inmediato. | E07 |
| US18 | Ver instrucciones | Como usuario, quiero ver instrucciones claras antes de comenzar un quiz para entender cómo funciona y qué se espera de mí. | Given que el usuario selecciona un quiz,<br> When se carga la pantalla inicial, <br> Then el sistema muestra una breve instrucción que explica cómo funcionará el quiz antes de comenzar. | E07 |
| US19 | Navegar entre preguntas | Como usuario resolviendo un quiz, quiero poder navegar entre preguntas para revisar y cambiar mis respuestas antes de finalizar. | Given que el usuario está resolviendo un quiz, <br> When decide retroceder o avanzar entre preguntas, <br> Then el sistema le permite revisar o cambiar sus respuestas antes de finalizar. | E07 |
| US20 | Temporizador en el Quiz | Como usuario, quiero ver un temporizador durante el quiz para controlar el tiempo que tardo en completarlo y mejorar mi velocidad de respuesta. | Given que el usuario está respondiendo un quiz, <br> When inicia la actividad, <br> Then el sistema muestra un temporizador visible que le permite controlar el tiempo que tarda en completarlo. | E07 |
| US21 | Preguntas sin responder | Como usuario, quiero que el sistema me indique qué preguntas dejé sin responder antes de finalizar el quiz para asegurarme de completarlo correctamente. | Given que el usuario está realizando un quiz, <br> When intenta finalizarlo sin responder todas las preguntas, <br> Then el sistema le indica cuáles quedaron sin responder | E07 |
| US22 | Mensaje de confirmacion al terminar el quiz | Como usuario, quiero recibir un mensaje de confirmación antes de finalizar el quiz para evitar enviarlo accidentalmente y poder revisar mis respuestas. | Given que el usuario está en la última pregunta del quiz, <br> When selecciona la opción "Finalizar quiz", <br> Then el sistema le solicita una confirmación antes de enviar sus respuestas para evitar finalizar por error. |E07 |
| US23 | Ranking global | Como usuario competitivo, quiero ver mi posición en el ranking global para compararme con todos los usuarios de la plataforma y motivarme a mejorar. | Given que ya he jugado varios quizzes,<br> When consulto el ranking global,<br> Then veo mi posición frente a otros usuarios. | E07 |
| US24 | Ranking por nivel | Como usuario, quiero ver el ranking filtrado por mi nivel de habilidad para compararme con usuarios de capacidades similares. | Given que compito con otros usuarios,<br> When accedo al ranking A2,<br> Then veo solo jugadores de mi nivel. | E07 |
| US25 | Ranking por país | Como usuario, quiero ver el ranking filtrado por país para compararme con jugadores de mi misma región y fomentar la competencia local. | Given que quiero compararme localmente,<br> When selecciono "Perú",<br> Then veo ranking con jugadores peruanos. |E07 |
| US26 | Historial de quizzes | Como usuario, quiero consultar mi historial de quizzes resueltos para revisar mi desempeño y progreso a lo largo del tiempo. | Given que he resuelto quizzes previamente,<br> When accedo a mi historial,<br> Then veo listado de quizzes con fecha y puntaje. |E08 |
| US27 | Historial de puntuaciones gráficas | Como usuario, quiero ver gráficos de mi progreso para visualizar fácilmente mi evolución y áreas de mejora en el tiempo. | Given que quiero revisar mi avance,<br> When abro mi historial,<br> Then se muestran gráficos de progreso en el tiempo. |E08 |
| US28 | Feedback de quiz | Como usuario, quiero poder calificar y comentar los quizzes que resuelvo para ayudar a otros usuarios y al creador a mejorar el contenido. | Given que resolví un quiz,<br> When lo califico con estrellas y comentarios,<br> Then el creador recibe mi feedback. |E06 |
| US29 | Resumen Final | Como usuario, quiero ver un resumen detallado al completar un quiz para revisar mi desempeño y aprender de mis errores. | Given que el usuario ha completado todas las preguntas de un quiz,<br> When llega al final del mismo,<br> Then el sistema muestra un resumen con su puntaje y las respuestas correctas e incorrectas. |E05 |
| US30 | Ver feedback recibido | Como creador de quizzes, quiero consultar todo el feedback recibido en mis quizzes para mejorar la calidad de mi contenido. | Given que soy creador,<br> When consulto el feedback de mis quizzes,<br> Then veo comentarios y calificaciones de usuarios. |E06 |
| US31 | Notificación de feedback nuevo | Como creador de quizzes, quiero recibir notificaciones cuando los usuarios dejen feedback para poder responder oportunamente. | Given que recibo feedback,<br> When un usuario deja un comentario,<br> Then me llega una notificación. |E06 |
| US32 | Compra de vidas extra | Como usuario del plan gratuito, quiero poder comprar vidas adicionales cuando se me agoten para continuar jugando sin esperar. | Given que estoy en plan gratuito y sin vidas,<br> When intento seguir jugando,<br> Then puedo comprar vidas adicionales con pago. |E09 |
| US33 | Suscripción premium | Como usuario, quiero poder suscribirme al plan premium para acceder a beneficios ilimitados y contenido exclusivo. | Given que quiero beneficios ilimitados,<br> When selecciono plan premium y realizo el pago,<br> Then mi cuenta pasa al estado premium. |E09 |
| US34 | Cancelación de suscripción | Como usuario premium, quiero poder cancelar mi suscripción cuando ya no desee continuar con los beneficios premium. | Given que no quiero seguir en premium,<br> When cancelo el plan,<br> Then mi cuenta vuelve al modo gratuito al final del ciclo. |E09 |
| US35 | Ver historial de pagos | Como usuario premium, quiero consultar mi historial de pagos y facturas para tener control de mis transacciones. | Given que soy usuario premium,<br> When consulto mi perfil,<br> Then veo un historial de mis pagos y facturas. |E09 |
| US36 | Participación en sala de speaking | Como usuario premium, quiero participar en salas de speaking para practicar inglés en tiempo real con otros usuarios. | Given que soy usuario premium,<br> When me uno a una sala de speaking,<br> Then puedo interactuar en tiempo real con otros. |E10 |
| US37 | Creación de sala de speaking | Como creador de contenido, quiero organizar salas de speaking para que los usuarios puedan practicar inglés en sesiones programadas. | Given que soy creador,<br> When organizo una sala de speaking,<br> Then los usuarios pueden unirse en la fecha y hora definidas. |E12 |
| US38 | Moderación de sala | Como creador de sala, quiero tener herramientas de moderación para gestionar la participación y mantener un ambiente de aprendizaje positivo. | Given que soy creador,<br> When gestiono mi sala,<br> Then puedo silenciar, expulsar o invitar usuarios. |E12 |
| US39 | Grabación de sesiones speaking | Como creador de sala, quiero poder grabar las sesiones de speaking para que los participantes puedan revisar el contenido posteriormente. | Given que estoy en una sala,<br> When activo la opción de grabar,<br> Then la reunión queda registrada para revisión. |E12 |
| US40 | Navegación en la landing page | Como visitante del sitio, quiero navegar fácilmente por la landing page para conocer los beneficios y características de la plataforma. | Given que soy visitante,<br> When accedo a la landing page,<br> Then puedo ver secciones de beneficios, testimonios y planes. |E13 |
| US41 | Testimonios en la landing page | Como visitante indeciso, quiero ver testimonios de usuarios reales para aumentar mi confianza en la plataforma antes de registrarme. | Given que soy visitante indeciso,<br> When veo testimonios reales,<br> Then aumento mi confianza en registrarme. |E13 |
| US42 | Responsive design | Como usuario móvil, quiero que todas las páginas se adapten correctamente a dispositivos móviles para tener una experiencia óptima desde cualquier dispositivo. | Given que ingreso desde un smartphone,<br> When navego en cualquier página,<br> Then el contenido debe ajustarse responsivamente. |E13 |
| TS01 | Backend API de login | Como desarrollador, quiero implementar una API de autenticación para permitir que los usuarios inicien sesión y reciban tokens de acceso. | Given que envío credenciales válidas,<br> When accedo al endpoint /login,<br> Then recibo token y confirmación. |E14 |
| TS02 | Backend API de quizzes | Como desarrollador, quiero implementar APIs para gestionar quizzes desde el backend y permitir operaciones CRUD. | Given que envío datos de un quiz nuevo,<br> When llamo al endpoint /quizzes,<br> Then se crea y devuelve el objeto quiz en JSON. |E14 |
| TS03 | Backend API de feedback | Como desarrollador, quiero implementar APIs para gestionar feedback de usuarios sobre quizzes completados. | Given que completo un quiz,<br> When llamo al endpoint /feedback,<br> Then se guarda el comentario vinculado al quiz y usuario. |E14 |
| TS04 | Seguridad de contraseñas | Como desarrollador, quiero implementar encriptación de contraseñas para garantizar la seguridad de las credenciales de usuario. | Given que registro un usuario,<br> When guardo la contraseña,<br> Then el sistema debe cifrarla antes de almacenarla. |E15 |
| TS05 | Validación JWT | Como desarrollador, quiero implementar validación de tokens JWT para proteger endpoints de la API. | Given que llamo a un endpoint protegido,<br> When incluyo un token válido,<br> Then el acceso es concedido.<br> But when el token es inválido,<br> Then recibo un error 401. |E15 |
| TS06 | Control de roles en API | Como desarrollador, quiero implementar control de acceso basado en roles para restringir operaciones según el tipo de usuario. | Given que soy admin,<br> When accedo a /admin/users,<br> Then puedo ver y gestionar usuarios.<br> But when soy estudiante,<br> Then recibo acceso denegado. |E15 |
| TS07 | Expiración de sesión | Como desarrollador, quiero implementar manejo de expiración de tokens para mantener la seguridad de las sesiones de usuario. | Given que mi token expira,<br> When intento acceder a la API,<br> Then recibo error 401 y debo iniciar sesión nuevamente. |E15 |
| TS08 | Conectar a Base de Datos |Como desarrollador, quiero configurar la conexión a la base de datos PostgreSQL para poder tener todos los datos de mi aplicacion. | Given que las credenciales de la base de datos son correctas <br>When se levanta el servidor <br>Then la conexión se establece sin errores.|E14 |


| Epic ID | Título                                     | Descripción breve                                              |
|--------|--------------------------------------------|----------------------------------------------------------------|
| E01    | Gestión de Acceso de Usuarios              | Como usuario, quiero registrarme <br> e iniciar sesión para acceder a la plataforma. |
| E02    | Experiencia de Usuario en Autenticación    | Como usuario, quiero tener una experiencia clara <br> y asistida durante los procesos de registro y autenticación. |
| E03    | Administración de roles y verificación     | Como administrador, quiero validar <br> y gestionar roles de usuario (creador, admin). |
| E04    | Creación y publicación de quizzes          | Como creador, quiero crear y publicar quizzes <br> para que otros usuarios los resuelvan. |
| E05    | Descubrimiento y búsqueda de quizzes       | Como usuario, quiero buscar quizzes <br> según mi nivel e idioma. |
| E06    | Retroalimentación y mejora de quizzes      | Como creador, quiero ver el feedback <br> y puntuación para mejorar mis quizzes. |
| E07    | Resolución de quizzes y puntuaciones       | Como usuario, quiero resolver quizzes <br> y obtener una puntuación para medir mi avance. |
| E08    | Historial y seguimiento del progreso       | Como usuario, quiero ver mis resultados <br> históricos para conocer mi progreso. |
| E09    | Gestión de Suscripciones y Pagos           | Como usuario, quiero suscribirme a un plan premium <br> para tener vidas ilimitadas. |
| E10    | Participación en salas de speaking         | Como usuario, quiero unirme a salas de práctica <br> de speaking en tiempo real. |
| E12    | Creación y moderación de salas             | Como creador, quiero organizar una sala <br> para practicar con usuarios. |
| E13    | Navegación en la Landing Page              | Como visitante, quiero navegar en una landing page <br> con información clara para decidir. |
| E14    |Gestión de Quizzes                          | Como developer, quiero exponer un endpoint <br>para crear, listar y obtener quizzes, para que los creadores publiquen y los usuarios accedan. |
| E15    |Seguridad y Autenticación                   |Como developer, quiero implementar JWT de autorización para proteger los recursos |

## 3.2. Impact Mapping.

<img width="700" height="500" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-3/Impact%20Mapping.png" alt="Impact Mapping">



## 3.3. Product Backlog.

| #Orden | User Story ID | Description |StoryPoint(1/3/5/8) |
|---------------|--------|------|------------------------------|
| 01 | US01 | Como nuevo usuario, quiero registrarme en QuizzBee con mi correo y contraseña para poder acceder a la plataforma y crear mi perfil. |3 |
| 02 | US02 | Como usuario registrado, quiero iniciar sesión con mis credenciales para acceder a mi cuenta y utilizar las funcionalidades de la plataforma. |2 |
| 03 | US03 | Como usuario que olvidó su contraseña, quiero poder recuperarla a través de mi correo electrónico para volver a acceder a mi cuenta sin perder mis datos. |3 |
| 04 | US04 | Como usuario durante el proceso de registro, quiero recibir mensajes claros cuando cometa errores en los campos para poder corregirlos fácilmente. | 2|
| 05 | US05 | Como nuevo usuario, quiero validar mi correo electrónico después del registro para activar mi cuenta y acceder completamente a la plataforma. | 3|
| 06 | US06 | Como usuario autenticado, quiero poder configurar mi perfil personal para personalizar mi experiencia en la plataforma según mis preferencias y nivel.	 | 3|
| 07 | US07 | Como usuario preocupado por la seguridad, quiero poder cambiar mi contraseña en cualquier momento para mantener mi cuenta protegida.	 | 2|
| 08 | US08 | Como usuario que ya no desea usar la plataforma, quiero poder eliminar permanentemente mi cuenta para que mis datos sean borrados del sistema.	 | 3|
| 09 | US09 | Como usuario autenticado, quiero poder cerrar sesión de forma segura para proteger mi cuenta cuando termine de usar la plataforma. |1 |
| 10 | US10 | Como creador de contenido, quiero poder crear quizzes con preguntas y respuestas personalizadas para compartir conocimiento con otros usuarios. | 5|
| 11 | US11 | Como creador, quiero poder publicar mis quizzes terminados para que estén disponibles para otros usuarios en la plataforma. | 2|
| 12 | US12 | Como creador, quiero poder editar mis quizzes ya publicados para mejorarlos o corregir errores manteniendo un historial de cambios. |3 |
| 13 | US13 | Como creador, quiero poder eliminar mis quizzes cuando ya no los considere útiles o relevantes para mantener mi contenido actualizado. |2 |
| 14 | US14 | Como usuario, quiero poder filtrar quizzes por idioma específico para encontrar contenido en el idioma que deseo practicar. | 2|
| 15 | US15 | Como usuario, quiero poder filtrar quizzes por nivel de dificultad para encontrar contenido apropiado para mis habilidades actuales. |2 |
| 16 | US16 | Como usuario, quiero poder filtrar quizzes por categoría temática para enfocarme en áreas específicas de estudio como vocabulario, gramática, etc. |2 |
| 17 | US17 | Como usuario, quiero poder resolver quizzes disponibles en la plataforma para practicar mis conocimientos y obtener retroalimentación inmediata. |6 |
| 18 | US18 | Como usuario, quiero ver instrucciones claras antes de comenzar un quiz para entender cómo funciona y qué se espera de mí. | 1|
| 19 | US19 | Como usuario resolviendo un quiz, quiero poder navegar entre preguntas para revisar y cambiar mis respuestas antes de finalizar. | 3|
| 20 | US20 | Como usuario, quiero ver un temporizador durante el quiz para controlar el tiempo que tardo en completarlo y mejorar mi velocidad de respuesta. | 3|
| 21 | US21 | Como usuario, quiero que el sistema me indique qué preguntas dejé sin responder antes de finalizar el quiz para asegurarme de completarlo correctamente. | 3|
| 22 | US22 | Como usuario, quiero recibir un mensaje de confirmación antes de finalizar el quiz para evitar enviarlo accidentalmente y poder revisar mis respuestas. | 2|
| 23 | US23 | Como usuario competitivo, quiero ver mi posición en el ranking global para compararme con todos los usuarios de la plataforma y motivarme a mejorar. | 5|
| 24 | US24 | Como usuario, quiero ver el ranking filtrado por mi nivel de habilidad para compararme con usuarios de capacidades similares. |5 |
| 25 | US25 | Como usuario, quiero ver el ranking filtrado por país para compararme con jugadores de mi misma región y fomentar la competencia local. |5 |
| 26 | US26 | Como usuario, quiero consultar mi historial de quizzes resueltos para revisar mi desempeño y progreso a lo largo del tiempo. | 3|
| 27 | US27 | Como usuario, quiero ver gráficos de mi progreso para visualizar fácilmente mi evolución y áreas de mejora en el tiempo. |5 |
| 28 | US28 | Como usuario, quiero poder calificar los quizzes con estrellas y comentarios para proporcionar feedback al creador. | 3|
| 29 | US29 | Como usuario, quiero ver un resumen completo al finalizar un quiz para conocer mi puntaje y revisar las respuestas correctas e incorrectas. |3 |
| 30 | US30 | Como creador, quiero consultar el feedback de mis quizzes para conocer la opinión y calificaciones de los usuarios. |3 |
| 31 | US31 | Como creador, quiero recibir notificaciones cuando los usuarios dejen comentarios para estar al tanto del feedback de mis quizzes. |5 |
| 32 | US32 | Como usuario en plan gratuito sin vidas, quiero poder comprar vidas adicionales para continuar jugando sin limitaciones. | 5|
| 33 | US33 | Como usuario, quiero suscribirme al plan premium para acceder a beneficios y características ilimitadas. |5 |
| 34 | US34 | Como usuario premium, quiero poder cancelar mi suscripción para que mi cuenta vuelva al modo gratuito al final del ciclo. |3 |
| 35 | US35 | Como usuario premium, quiero acceder a un historial de mis pagos y facturas para gestionar mi información financiera. | 3|
| 36 | US36 | Como usuario premium, quiero unirme a salas de speaking para interactuar en tiempo real con otros usuarios. |5 |
| 37 | US37 | Como creador, quiero organizar salas de speaking para que los usuarios puedan unirse en fechas y horas específicas. |5 |
| 38 | US38 | Como creador de salas, quiero gestionar mi sala de speaking para poder silenciar, expulsar o invitar usuarios según sea necesario. | 5|
| 39 | US39 | Como usuario en una sala de speaking, quiero poder grabar la reunión para tener acceso a ella posteriormente. | 8|
| 40 | US40 | Como visitante, quiero acceder a una landing page informativa para conocer los beneficios, testimonios y planes disponibles. | 1|
| 41 | US41 | Como visitante indeciso, quiero ver testimonios reales de usuarios para aumentar mi confianza antes de registrarme. | 1|
| 42 | US42 | Como usuario móvil, quiero que el contenido se ajuste responsivamente para tener una experiencia óptima en cualquier dispositivo. |3 |
| 43 | TS01 | Como desarrollador, quiero implementar autenticación por API para que los usuarios puedan iniciar sesión y recibir tokens de acceso. | 3|
| 44 | TS02 | Como desarrollador, quiero crear endpoints para la gestión de quizzes para permitir operaciones CRUD en formato JSON. |3 |
| 45 | TS03 | Como desarrollador, quiero implementar endpoints de feedback para guardar comentarios vinculados a quizzes y usuarios. |3 |
| 46 | TS04 | Como desarrollador, quiero implementar cifrado de contraseñas para garantizar la seguridad de las credenciales de usuario. |3 |
| 47 | TS05 | Como desarrollador, quiero implementar validación de tokens para controlar el acceso a endpoints protegidos y manejar tokens inválidos. |5 |
| 48 | TS06 | Como desarrollador, quiero implementar control de acceso basado en roles para diferenciar permisos entre administradores y usuarios regulares. |5 |
| 49 | TS07 | Como desarrollador, quiero manejar la expiración de tokens para mantener la seguridad y requerir re-autenticación cuando sea necesario. | 3|
| 50 | TS08 | Como desarrollador, quiero configurar la conexión a la base de datos PostgreSQL para poder tener todos los datos de mi aplicacion.  | 8|



---

# **Capítulo IV: Product Design**
## 4.1. Style Guidelines.
Se define las decisiones visuales y de comunicación aplicadas en QuizBee, incluyendo branding, tipografía, colores, espaciado y el tono de comunicación adoptado en la plataforma y el landing page.
### 4.1.1. General Style Guidelines.

- **Branding:** Nos enfocamos en comunicar frescura, confianza y dinamismo. La identidad visual intenta proyectar una perspectiva de aprendizaje colaborativo y lúdico,
  distanciándose de la rigurosidad académica y acercándose a una experiencia más moderna y atractiva.
  
- **Typography:** Se utilizó una tipografía moderna y altamente legible, pensada para mantener consistencia visual en cualquier dispositivo, ya sea escritorio o móvil. La elección de fuentes busca transmitir frescura y dinamismo en los títulos, a la vez que garantiza una lectura clara
  
  - **Titulos:** Se utiliza Poppins Bold con el propósito de otorgar fuerza, protagonismo y jerarquía a los encabezados más importantes. Esta fuente gráfica brinda modernidad y garantiza que los encabezados se destaquen inmediatamente.
    
  - **Parrafos:** Se emplea Roboto Regular, pues ofrece una lectura cómoda en bloques grandes y logra un aspecto limpio y profesional. Es perfecto para redactar párrafos y descripciones.
    
  - **Textos en Botones:** Se utiliza Poppins Semibold, lo que garantiza visibilidad y contraste, lo que a su vez proporciona claridad y favorece la interacción del usuario.
    
- **Colors:** La paleta de colores de QuizBee gira en torno al celeste, un tono que transmite frescura, claridad y confianza, alineándose con nuestra propuesta de ser una plataforma dinámica y accesible para el aprendizajey reforzarmiento del ingles. La elección de estos colores tiene como objetivo crear un entorno visual agradable que impulse al usuario a interactuar sin sentirse agobiado.
  
  - **Color principal:** Celeste claro (A5E8FF), que es el color mayoritario en el diseño y se emplea en componentes esenciales de la interfaz. Simboliza ligereza, apertura e innovación, rasgos que fortalecen la naturaleza de la aplicación.
    
  - **Color complementario:** Celeste más intenso (3ABEF9), aplicado en botones, llamados a la acción y elementos destacados. Su función es atraer la atención del usuario en los momentos clave, asegurando un contraste claro con el fondo y generando jerarquía visual.
    
  - **Fondo base:** Blanco humo (F5F9FC), empleado como fondo principal en el landing y las secciones informativas. Este tono neutro aporta claridad, sensación de amplitud y permite que los colores primarios y complementarios resalten de forma natural.
  
- **Spacing:** El espaciado es un elemento esencial en la identidad visual de QuizBee, debido a que garantiza que la interfaz no se vea sobrecargada y que navegar por ella sea fácil y claro. Se ha determinado un espaciamiento amplio entre secciones, lo que posibilita una jerarquía visual clara y ayuda al usuario a distinguir fácilmente la importancia de cada bloque de contenido.
  
- **Tono de comunicacion:** El tono que se estableció para QuizBee es entusiasta, casual y respetuoso, con el objetivo de crear un vínculo cercano con los usuarios sin disminuir la credibilidad ni la confianza. Se pretende proyectar una voz que estimule al usuario y lo acompañe en su proceso de aprendizaje, transmitiendo optimismo y manteniendo un comportamiento cordial en todo momento.
  
### 4.1.2. Web Style Guidelines.
En esta sección se definen los estándares visuales y de interacción para asegurar consistencia en todas las versiones de la plataforma (desktop, tablet y mobile).
- **Layout & Responsive:**
  - Estructura basada en un grid flexible de 12 columnas.

  - Breakpoints principales:

    - Mobile: ≤ 576px

    - Tablet: 577px – 992px

    - Desktop: ≥ 993px
      
  - Los elementos se adaptan manteniendo proporciones, espaciados y jerarquía visual en todas las resoluciones.

- **Navegación:**
  
  - Menú principal siempre visible en desktop y accesible mediante hamburger menu en mobile.

  - Botones de acción (CTA) como “Empezar ahora” permanecen visibles y accesibles en todas las resoluciones.
 
- **Botones e Interacciones:**
  
  - Botones primarios con fondo azul/celeste y texto blanco.

  - Hover: tono más oscuro para dar feedback.

  - Disabled: gris claro con texto desactivado.

  - Bordes redondeados para mantener el estilo amigable y moderno.

- **Espaciado:**

  - Márgenes y paddings adaptativos según resolución.

  - En mobile, se prioriza la verticalidad y el scroll fluido.

  - En desktop, se aprovecha mejor el espacio horizontal con columnas.
    
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
La información se organiza primordialmente de manera jerárquica, destacando los elementos más relevantes: el encabezado con la propuesta de valor, el llamado a la acción más importante y las secciones esenciales (Quiénes somos, Funcionalidades, Descarga, Contacto).

En ciertos apartados, se opta por una disposición secuencial, como en la descripción de las funcionalidades, donde se detallan paso a paso las ventajas y modos de uso (Retos diarios → Competencias gamificadas → Práctica con hablantes).

Para el contenido general, se utiliza un modelo de categorización por temas, organizando la información en bloques definidos: misión, visión, enfoque y comunidad; funcionalidades clave; opciones de descarga; y formulario de contacto.

En el formulario, la organización sigue una secuencia cronológica, comenzando con la solicitud de los datos básicos del usuario y luego confirmando que el equipo se pondrá en contacto.

Esta combinación de métodos de organización asegura que la experiencia sea clara, sencilla y fácil de navegar, sin importar el dispositivo que se utilice.

### 4.2.2. Labeling Systems.
El sistema de etiquetado  tiene como objetivo preservar la claridad y la sencillez, empleando vocabulario breve y explícito que transmita de manera instantánea la función de cada parte. Se evitan expresiones especializadas o poco claras que puedan causar malentendidos en los usuarios.

Las etiquetas principales definidas para el landing son:

- Inicio → acceso directo a la página principal y propuesta de valor.

- Quiénes somos → bloque informativo que presenta misión, visión, enfoque y comunidad.

- Funcionalidades → sección donde se explican los beneficios de la app (retos diarios, competencias, práctica con hablantes).

- Descargar → llamada a la acción con botones hacia App Store y Google Play.

- Contacto → formulario sencillo para que los usuarios puedan comunicarse.

Los botones de acción utilizan frases cortas en imperativo para incentivar la interacción, como “Empezar ahora”, “Descargar” o “Enviar”, manteniendo consistencia en el tono y evitando redundancias.

Este método de etiquetado permite que cada parte sea identificada al instante y que las conexiones entre el contenido y la acción sean evidentes para el usuario.

### 4.2.3. SEO Tags and Meta Tags
En esta sección se definen las etiquetas SEO y meta tags que se aplicarán en las principales páginas del sitio (Landing Page y Web Application), con el fin de optimizar la visibilidad en buscadores y garantizar una adecuada indexación.

- Landing Page :

  - Title: QuizBee 

  - Meta Description: Plataforma innovadora para aprender inglés mediante retos diarios, competencias gamificadas y práctica real con hablantes en videollamadas.

  - Meta Keywords: aprender inglés, retos diarios inglés, inglés gamificado, practicar inglés con hablantes, clases de inglés en videollamada

  - Meta Author: Equipo QuizBee

- Web Application :

  - Title: QuizBee App 

  - Meta Description: Participa en desafíos diarios, gana puntos en competencias gamificadas y mejora tu inglés con sesiones en vivo por videollamada.

  - Meta Keywords: retos de inglés, gamificación inglés, práctica en vivo inglés, inglés interactivo, mejorar inglés rápido

  - Meta Author: Equipo QuizBee

### 4.2.4. Searching Systems.
El sistema de búsqueda está diseñado para que los usuarios encuentren de manera rápida y clara los contenidos y recursos que necesitan dentro de la plataforma.

En la aplicación web, se ofrecerá una barra de búsqueda principal. Los usuarios podrán localizar retos específicos, lecciones temáticas, competencias gamificadas y videollamadas programadas.

Los resultados podrán refinarse mediante filtros como:

- Nivel de dificultad (básico, intermedio, avanzado).

- Tipo de actividad (reto escrito, reto hablado, competencia, práctica con experto).

- Duración estimada (corta, media, larga).

- Popularidad o relevancia (más usados, más recomendados).

Después de la búsqueda, los datos se presentarán en listas visuales con íconos representativos de cada tipo de recurso, junto a descripciones breves y botones de acción (ej. “Iniciar reto”).

De esta forma, el sistema de búsqueda no solo evita que los usuarios se pierdan entre la información, sino que los guía hacia las actividades que mejor se adaptan a sus metas de aprendizaje.

### 4.2.5. Navigation Systems.
En el Landing Page y la aplicación web se aplicará una navegación fluida y guiada por el scroll, donde el usuario recorre el contenido de forma secuencial y jerárquica, pasando de las secciones principales en un orden lógico: Inicio → Quiénes Somos → Funcionalidades → Contacto →Descarga.

En la Landing Page, los usuarios recorrerán el contenido de forma secuencial y jerárquica, con botones de llamada a la acción (CTAs) estratégicos como "Empiaza Ahora", que los llevan directamente al registro o inicio de sesion.

En la aplicación web, se implementará una navegación tipo tab bar (en móviles) y sidebar (en escritorio), permitiendo acceder fácilmente a las funciones principales: Retos diarios, Videollamadas, Competencias, Perfil y Configuración.

Además, se incluirán elementos de navegación contextual como breadcrumbs para ubicar al usuario dentro del sistema, y enlaces rápidos hacia secciones de soporte y comunidad. Esto garantiza que el recorrido sea fluido, motivador y que el usuario cumpla su meta: aprender y practicar inglés sin perderse en el camino.

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.

<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%201.png" alt="Frame 1">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%202.png" alt="Frame 2">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%203.png" alt="Frame 3">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%204.png" alt="Frame 4">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%205.png" alt="Frame 5">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%206.png" alt="Frame 6">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%207.png" alt="Frame 7">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Frame%208.png" alt="Frame 8">

### 4.3.2. Landing Page Mock-up.

<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding1.png" alt="Mockup Landing 1">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding2.png" alt="Mockup Landing 2">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding3.png" alt="Mockup Landing 3">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding4.png" alt="Mockup Landing 4">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding5.png" alt="Mockup Landing 5">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockupLanding6.png" alt="Mockup Landing 6">


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

- Descripcion: El wireframe de perfil presenta jerarquía clara con foto, nombre, e-mail y contrasena y sus opciones de edición. La estructura es simple, con tipografía base y espacios definidos que facilitan la lectura. Se asegura accesibilidad con botones de tamaño adecuado y un flujo lógico de información.
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireframeWebPerfil.png" alt="Wireframe Web Perfil">

- Descripcion: El wireframe de juegos organiza los quizzes en una grilla de dos columnas por múltiples filas, con tarjetas cuadrangulares fáciles de escanear. En la parte superior se ubican los filtros , asegurando jerarquía visual y navegación simple. Se prioriza la accesibilidad con botones amplios y disposición clara, aplicando arquitectura de información que guía al usuario de la búsqueda a la selección de forma intuitiva.
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebJuegos.png" alt="Wireframe Web Juegos">

- Descripcion: El wireframe del quiz presenta una  pantalla desplegable central donde se muestra la pregunta con un campo para ingresar la respuesta. En la parte superior se indican las vidas disponibles de forma clara, y en la parte inferior se ubica un botón destacado para enviar la respuesta. La disposición es simple y jerárquica, asegurando comprensión rápida, accesibilidad y una experiencia inclusiva que guía al usuario sin distracciones.

<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireframeWebQuiz.png" alt="Wireframe Web Quiz">

- Descripcion: El wireframe del resumen de quiz muestra una pantalla final donde se presenta el puntaje , seguido de un listado de respuestas correctas e incorrectas de forma clara y organizada. La jerarquía visual asegura que el usuario identifique primero su resultado general y luego pueda revisar el detalle de su desempeño. La estructura es simple, inclusiva y accesible, permitiendo comprender fácilmente el progreso alcanzado.
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebResumenQuizz.png" alt="Wireframe Web Resumen Quizz">

- Descripcion: El wireframe de salas de speaking muestra un listado simple con las salas disponibles
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebSpeaking.png" alt="Wireframe Web Speaking">

- Descripcion: 
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebCrear.png" alt="Wireframe Web Crear">

- Descripcion
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebMisCreaciones.png" alt="Wireframe Web Mis Creaciones">

- Descripcion
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireframeWebCompras.png" alt="Wireframe Web Compras">

- Descripcion
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/WireFrameWebHistorialPagos.png" alt="Wireframe Web Historial Pagos">


### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.

<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebPerfil.png" alt="MockUp Web Perfil">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebJuegos.png" alt="MockUp Web Juegos">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebQuiz.png" alt="MockUp Web Quiz">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpResumenQuiz.png" alt="MockUp Resumen Quiz">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebSpeaking.png" alt="MockUp Web Speaking">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebCrear.png" alt="MockUp Web Crear">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebMisCreaciones.png" alt="MockUp Web Mis Creaciones">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebCompras.png" alt="MockUp Web Compras">
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/MockUpWebHistorialPagos.png" alt="MockUp Web Historial Pagos">



### 4.4.3. Web Applications User Flow Diagrams.

- User Persona 1:
  
<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/UserFlow1.png" alt="User Flow 1">

- User Persona 2:

<img width="1000" height="600" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/UserFlow2.png" alt="User Flow 2">


## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.


### 4.6.2. Software Architecture Context Diagram

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/contextdiagram.png" alt="Context Diagram">


### 4.6.3. Software Architecture Container Diagrams

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/containerdiagram.png" alt="Container Diagram">


### 4.6.4. Software Architecture Components Diagrams

Authentication Bounded Context

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/authentificationbc.png" alt="Authentification BC">

Profile Bounded Context

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/profilebc.png" alt="Profile BC">

Quizz and Questions Bounded Context

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/quizzbc.png" alt="Quizz BC">

Speaking Room Bounded Context

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/speakingroom.png" alt="Speaking Room">

Attempt and Scoring Bounded Context

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/attempt.png" alt="Attempt">

Billing and Suscription Bounded Context 

<img width="auto" height="auto" src="https://raw.githubusercontent.com/Open-Source-7385/QuizBee-Report/main/assets/img/chapter-IV/Billing.png" alt="Billing">


## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams.

---

# **Capítulo V: Product Implementation, Validation & Deployment**
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

| Tipo de Actividad       | Herramienta / Producto | URL                                | Motivos de uso                                                                 |
|--------------------------|-------------------------|------------------------------------|--------------------------------------------------------------------------------|
| UX/UI Design             | Figma                  | https://www.figma.com/es-la        | Realizar los diseños de interfaz y de experiencia de usuario para nuestra solución. |
| Desarrollo de Software   | VS Code                | https://code.visualstudio.com      | Desarrollar la Landing Page de nuestra solución.                                |
| Documentación            | GitHub                 | https://github.com                 | Realizar la documentación de nuestra propuesta.                                 |
| Gestión de Requisitos    | Miro                    | https://miro.com/                | Para organizar, colaborar y realizar un seguimiento del trabajo de manera eficiente. |
| Reuniones                | Discord                | https://discord.com/               | Reuniones con el equipo.                                                        |


### 5.1.2. Source Code Management.
**Link Repositorio Report**

Link: https://github.com/Open-Source-7385/QuizBee-Report.git

**Link Repositorio Landing**

Link: https://github.com/Open-Source-7385/Landing.git


**Workflow – GitFlow**

Se implementará el modelo **GitFlow** para el manejo de ramas:

- **main**: rama principal, contiene solo versiones estables listas para producción.  
- **develop**: rama de integración, donde se juntan las nuevas funcionalidades antes de liberar una versión.  
- **feature/***: cada nueva funcionalidad tendrá su propio branch.  
  - Ejemplo: feature/login-auth  
- **release/***: rama usada para preparar una nueva versión antes de pasar a producción.  
  - Ejemplo: release/1.0.0
- **hotfix/***: ramas para corregir errores críticos en producción.  
  - Ejemplo: hotfix/fix-login-bug 


**Versionado**

Se aplicará **Semantic Versioning (SemVer 2.0.0):**

- **Formato**: MAJOR.MINOR.PATCH  
- **Ejemplo**: v1.2.3  

### Significado:  
- **MAJOR**: cambios incompatibles.  
- **MINOR**: nuevas funcionalidades sin romper compatibilidad.  
- **PATCH**: corrección de bugs.
  

**Commits**

Se utilizarán los estándares de **Conventional Commits**:

- **feat**: nueva funcionalidad.  
- **fix**: corrección de bug.  
- **docs**: cambios en documentación.  
- **style**: cambios de formato (no afectan código).  
- **refactor**: cambios internos sin alterar funcionalidad.  
- **test**: pruebas añadidas o corregidas.  
- **chore**: tareas de mantenimiento.  


### 5.1.3. Source Code Style Guide & Conventions.

Para asegurar la calidad, mantenibilidad y coherencia del código fuente en el proyecto, se adoptarán las siguientes guías de estilo y convenciones estándar para los lenguajes utilizados:

**JavaScript:**
- Se seguirá la guía de estilo de [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript), ampliamente reconocida en la industria.
- Nomenclatura camelCase para variables y funciones, PascalCase para clases y componentes.
- Uso de const y let en lugar de var.
- Indentación de 2 espacios.
- Comentarios claros y descriptivos.

**TypeScript:**
- Se adoptará la [Guía oficial de TypeScript](https://github.com/microsoft/TypeScript/wiki/Coding-guidelines) y las recomendaciones de [Airbnb TypeScript Style Guide](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-typescript).
- Tipado estricto y explícito en variables, funciones y clases.
- Uso de interfaces y types para definir contratos de datos.
- Nomenclatura camelCase para variables y funciones, PascalCase para tipos, interfaces y clases.

**Java:**
- Se seguirá la [Guía de Estilo de Google para Java](https://google.github.io/styleguide/javaguide.html).
- Nomenclatura camelCase para variables y métodos, PascalCase para clases.
- Indentación de 4 espacios.
- Uso de JavaDoc para documentación de clases y métodos públicos.

**Convenciones generales de coding:**
- Se utilizarán linters y formateadores automáticos (ESLint para JS/TS, Checkstyle para Java) para asegurar el cumplimiento de las guías.
- Se evitarán abreviaturas poco claras en nombres de variables y funciones.
- Se priorizará la legibilidad y la modularidad del código.
- Se fomentará el uso de patrones de diseño y buenas prácticas de programación orientada a objetos y funcional.

**HTML**
  - "p" Utiliza esta etiqueta para dividir el texto en párrafos.
  - "a" Permite crear enlaces hacia otras páginas web.
  - "ul" Crea una lista no ordenada (sin numeración).
  - "li" Define cada elemento dentro de una lista.
  - "meta" Se incluye en la sección de encabezado del HTML y no es visible en la página.
  - "h1" Indica el encabezado más importante del contenido.
  - "div" Agrupa diferentes secciones de contenido.
  
**CSS**
  - width: Define el ancho de un elemento.
  - height: Establece el alto de un elemento.
  - padding: Crea espacio interno entre el borde y el contenido.
  - font-family: Determina el tipo de fuente.
  - font-size: Ajusta el tamaño de la fuente.
  - font-weight: Controla el grosor o peso de la fuente.
  - font-style: Configura el estilo de la fuente (normal, cursiva, etc.).
  - text-align: Alinea el texto según lo especificado (izquierda, centro, derecha).
  - color: Aplica color al texto o al borde del elemento.
  - background-color: Define el color de fondo del elemento.


### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1

En esta sección, se documentará y explicará, en términos de producto y colaboración, el primer sprint de trabajo.

### 5.2.1.1. Sprint Planning 1.

| **Sprint #**                  | Sprint 1                                                                                                                                                                            |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                     |
| **Date**                       | 1 de septiembre del 2025                                                                                                                                                            |
| **Time**                       | 18:00 horas                                                                                                                                                                         |
| **Location**                   | Modalidad remota a través de la plataforma Discord                                                                                                                                  |
| **Prepared By**                | Todos los integrantes del equipo QuizBee                                                                                                                                            |
| **Attendees (to planning meeting)** | Todos los integrantes del equipo QuizBee                                                                                                                                            |
| **Sprint 0 Review Summary**    | Dado que es nuestro primer sprint de desarrollo, aún no se ha realizado un resumen del sprint anterior.                                                                             |
| **Sprint 0 Retrospective Summary** | No se identificaron mejoras ya que es el primer sprint.                                                                                                                             |
| **Sprint Goal & User Stories** | US01, US02, US03, US04, US05, US06, US07                                                                                                                                            |
| **Sprint 1 Goal**              | En este sprint, nuestro enfoque está en describir nuestra startup y en construir la estructura de la Landing Page, realizar las entrevisas, y tener definidos nuestros user stories |
| **Sprint 1 Velocity**          | 5                                                                                                                                                                                   |
| **Sum of Story Points**        | 5                                                                                                                                                                                   |


### 5.2.1.2. Aspect Leaders and Collaborators.

En este apartado se detallan los principales aspectos considerados en el Sprint 1 y la asignación de responsabilidades dentro del equipo. Para este primer sprint, se priorizó la definición y desarrollo de los siguientes aspectos clave:

- Elaboración y refinamiento de las User Stories fundamentales para la plataforma.
- Diseño y construcción de la estructura inicial de la Landing Page.
- Descripción y desarrollo de los primeros capítulos del informe, asegurando una base sólida para el proyecto.

Cada uno de estos aspectos fue liderado o apoyado por diferentes miembros del equipo, promoviendo la colaboración y el aprendizaje conjunto. La siguiente tabla muestra la distribución de roles y responsabilidades para cada aspecto relevante del Sprint:

| Team Member (Last Name, First Name) | Github Username | Elaboracion de User Stories Leader (L), Collaborator (C) | Desarrollo del landing page Leader (L), Collaborator (C) | Descripcion y desarrollo de los primeros capitulos Leader (L), Collaborator (C) |
| ----------------------------------- | --------------- | ------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------- |
|         | AlexBoo578         | (C)                                                     | (C)                                                            | (C)                                                |
| Vidal, Jareth              | Jareth341       | (L)                                                     | (C)                                                            | (C)                                                |
| Acosta, Abraam                 | abraam16        | (C)                                                     | (C)                                                            | (C)                                                |
| Geronimo, Pablo              | Phatogram       | (C)                                                     | (L)                                                            | (C)                                                |


### 5.2.1.3. Sprint Backlog 1.

El objetivo principal de este Sprint fue sentar las bases del proyecto, enfocándonos en la definición y desarrollo de los elementos esenciales para la primera entrega. Se priorizó la creación de la estructura de la landing page, la elaboración de las primeras user stories y la organización inicial del equipo. El Sprint Backlog refleja las tareas seleccionadas para alcanzar estos objetivos y asegurar un avance sólido y colaborativo desde el inicio del proyecto.


| Sprint # | Sprint 1 | | | |     | 
|----------|------|-|--|--|-----|
|          | **User Story** | |  | |     | 
| **Id**   | **Title** |  **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / In-Process / To-Review / Done)** |
| US01     | Navegación en la landing page  | Como visitante del sitio, quiero navegar fácilmente por la landing page para conocer los beneficios y características de la plataforma. |  |  |  |
|          | - Diseñar estructura de navegación principal | Definir el menú y enlaces principales de la landing page. | 2 | Jareth Vidal | Done |
|          | - Implementar navegación responsive | Asegurar que la navegación funcione en dispositivos móviles y escritorio. | 2 | Jareth Vidal | Done |
| US02     | Testimonios en la landing page  | Como visitante indeciso, quiero ver testimonios de usuarios reales para aumentar mi confianza en la plataforma antes de registrarme. |  |  |  |
|          | - Recopilar testimonios de usuarios | Buscar y seleccionar testimonios relevantes. | 1 | Pablo Geronimo | Done |
|          | - Maquetar sección de testimonios | Diseñar y programar la sección en la landing page. | 2 | Pablo Geronimo | Done |
| US03     | Funcionalidades en la landing page | Como visitante del sitio, quiero navegar fácilmente por la landing page para conocer las funcionalidades de la plataforma. |  |  |  |
|          | - Listar funcionalidades clave | Definir y redactar las funcionalidades principales. | 2 | Abraam Acosta | Done |
|          | - Implementar sección de funcionalidades | Maquetar y programar la sección en la landing page. | 3 | Abraam Acosta | Done |
| US04     | Planes Premiun en la landing page  | Como visitante, quiero ver los Planes Premiun que ofrecen en la plataforma. |  |  |  |
|          | - Definir contenido de planes premium | Redactar y estructurar la información de los planes. | 1 | Alex | Done |
|          | - Maquetar sección de planes premium | Programar la sección en la landing page. | 2 | Alex | Done |
| US05     | Formulario en la landing page  | Como visitante, quiero ver un formulario de contacto para poder resolver mis dudas. |  |  |  |
|          | - Diseñar formulario de contacto | Definir campos y estructura del formulario. | 2 | Abraam Acosta | Done |
|          | - Implementar validación de formulario | Programar validaciones básicas (requeridos, email, etc.). | 2 | Abraam Acosta | Done |
|          | - Integrar formulario en la landing page | Maquetar y ubicar el formulario en la página. | 2 | Abraam Acosta | Done |
| US06     | Redes en la landing page | Como visitante, quiero ver todas sus redes en el footer. |  |  |  |
|          | - Recopilar enlaces de redes sociales | Listar y verificar enlaces oficiales. | 1 | Jareth Vidal | Done |
|          | - Maquetar sección de redes en el footer | Programar los íconos y enlaces en el pie de página. | 3 | Jareth Vidal | Done |
| US07     | Servicios en la landing page | Como visitante, quiero ver los servicios que ofrecen en la plataforma. |  |  |  |
|          | - Definir lista de servicios | Redactar y organizar los servicios principales. | 1 | Pablo Geronimo | Done |
|          | - Implementar sección de servicios | Maquetar y programar la sección en la landing page. | 1 | Pablo Geronimo | Done |



### 5.2.1.4. Development Evidence for Sprint Review.

Durante este Sprint, el equipo logró avances significativos en la implementación del proyecto. Se completó la estructura y diseño de la landing page, integrando las secciones principales como navegación, testimonios, funcionalidades, planes premium, formulario de contacto, redes sociales y servicios. Además, se documentaron los commits y ramas utilizados, asegurando trazabilidad y colaboración efectiva entre los miembros del equipo. A continuación, se presenta la evidencia de los principales entregables y contribuciones realizadas durante el Sprint.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|--------------------|--------------------|
| QuizBee-Report | Chapter1 | a1b2c3d | docs:(chapter-I)"add format of team member profiles" | Added structured format for team member profiles including personal information, skills, and role descriptions for each team member in the startup profile section | 15/09/2024 |
| QuizBee-Report | Chapter1 | e4f5g6h | docs(chapter-1):"adding Competitive Analysis Landscape and Strategy and tactis front Rivals "" | Implemented comprehensive competitive analysis section with detailed competitor research, market positioning analysis, and strategic approaches to compete effectively in the market | 16/09/2024 |
| QuizBee-Report | Chapter1 | i7j8k9l | docs(chapter-1): add introduction structure for QuizzBee project and finalize Desing interview | Created complete introduction structure for QuizzBee project including startup description, solution profile, and finalized interview design questions for user research | 17/09/2024 |
| QuizBee-Report | Chapter2 | m0n1o2p | docs(chapter-II):"add summary of interview" | Added comprehensive summary of conducted interviews including key insights, user feedback analysis, and findings that will inform the product development process | 18/09/2024 |
| QuizBee-Report | Chapter2| q3r4s5t | fix(empathymapping): fix empathy map images | Fixed empathy mapping images by correcting display issues, updating broken links, and ensuring proper visualization of user personas and their emotional journey maps | 19/09/2024 |
| QuizBee-Report | Chapter2 | u6v7w8x | feat: Update the description on the Product Backlog. | Updated Product Backlog descriptions to align with user stories format, ensuring consistency between narrative descriptions and acceptance criteria across all user stories | 15/09/2024 |
| QuizBee-Report | Chapter3 | y9z0a1b | feat: restructure user stories format | Restructured user stories from Given-When-Then format to narrative format using "Como [rol], quiero [objetivo] para [beneficio]" structure for better clarity and consistency | 16/09/2024 |
| QuizBee-Report | Chapter3 | c2d3e4f | docs(chapter-III):"add epic with description and title" | Added comprehensive epic stories section with detailed descriptions and titles for each epic, establishing clear connections between user stories and business objectives | 17/09/2024 |
| QuizBee-Report | Chapter4 | g5h6i7j | Delete assets/img/chapter-IV/wireframe1.png | Removed outdated wireframe image file that was no longer needed and replaced with updated design mockups that better represent the current UI/UX design approach | 19/09/2024 |
| QuizBee-Report | Chapter5 | k8l9m0n | feat: update aspect leaders and collaborators | Updated aspect leaders and collaborators table with current team member assignments, defining clear roles and responsibilities for each sprint activity and deliverable | 20/09/2024 |

### 5.2.1.5. Execution Evidence for Sprint Review.

En este Sprint se logró desplegar la primera versión funcional de la landing page del proyecto, cumpliendo con los objetivos planteados en el backlog. El equipo trabajó de manera colaborativa para implementar y publicar las principales secciones, asegurando una experiencia de usuario coherente y alineada con los requerimientos iniciales. A continuación, se presenta la evidencia visual y el enlace de acceso a la landing page desplegada:

Enlace de la Landing Page: <br>
https://quizbeelandingpage.netlify.app/
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/landing.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/landing2.png">
### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Para esta entrega no se han empleado APIS, por lo cuál no se he requerido hacer una documentación sobre servicios implementados durante el Sprint


### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Durante este Sprint, el equipo realizó el despliegue exitoso de la landing page utilizando la plataforma Netlify. El objetivo fue asegurar que la solución estuviera disponible en línea para su revisión y validación, cumpliendo con los estándares de entrega continua y visibilidad del avance del proyecto.

**Pasos realizados durante el despliegue:**
1. Se creó una cuenta y espacio de trabajo en Netlify para el proyecto.
2. Se conectó el repositorio de la landing page alojado en GitHub con Netlify, permitiendo la integración continua.
3. Se configuró la rama principal del repositorio como fuente de despliegue automático.
4. Se ajustaron las opciones de build y publish para asegurar la correcta generación de archivos estáticos.
5. Se realizó el primer despliegue, verificando que la landing page estuviera accesible públicamente y funcionando correctamente.
6. Se validó el acceso desde diferentes dispositivos y navegadores para garantizar la experiencia de usuario.
7. Se documentó la URL de acceso y se compartió con el equipo para revisión y feedback.

###Design
Para realizar el diseño de los wireframes y mockups de la Landing Page para este Sprint,<br> se hizo uso de la plataforma Figma. Para utilizar la plataforma:

1.Se accede a través de la página oficial de Figma: https://www.figma.com/login
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/figma.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/figma2.png">

**Deployment Para la landing page, se utilizará Netlify para el despliegue de la página.**
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/deployment2.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/deployment4.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/deployment5.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/deployment.png">

Para nuestro proyecto se crearon 2 repositorios, el cuál fue:

Documentación|https://github.com/Open-Source-7385/QuizBee-Report :Este repositorio contiene el informe de nuestro proyecto. <br>
 Quizbee Landing Page | https://github.com/Open-Source-7385/Landing  :Este repositorio se usa para realizar el informe del proyecto de manera continua y subir la landing page.


### 5.2.1.8. Team Collaboration Insights during Sprint.

Durante este Sprint, las actividades de implementación se desarrollaron de manera colaborativa y organizada. El equipo utilizó herramientas como GitHub para la gestión de versiones y asignación de tareas, y Discord para la comunicación y coordinación diaria. Cada integrante asumió responsabilidades específicas según el backlog y los aspectos definidos en la planificación, participando activamente en el desarrollo, revisión de código y validación de entregables.

Se promovió la revisión cruzada de avances, el registro de commits detallados y la documentación de los cambios realizados. Las reuniones periódicas permitieron resolver dudas, ajustar prioridades y asegurar que todos los miembros estuvieran alineados con los objetivos del Sprint. Esta dinámica facilitó la integración continua y la entrega oportuna de los resultados esperados.

<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/collaboration.png">
<img width ="auto" height="auto" src="https://github.com/Open-Source-7385/QuizBee-Report/blob/main/assets/img/chapter-V/collaboration2.png">
---






