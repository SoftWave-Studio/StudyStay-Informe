# StudyStay-Informe


# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 7mo Ciclo</strong><br>
    <strong>Diseño de Experimentos de Ingenieria de Software - WX72</strong><br>
    <strong>Profesor: JULIO MANUEL NORIEGA MELENDEZ</strong><br>
    <br>INFORME DE TRABAJO FINAL - TF1
</p>

<p align="center">
    <strong>Startup: SoftWave Studio</strong><br>
    <strong>Producto: StudiStay</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Fabio Horna Silva</td>
            <td>U202020229</td>
        </tr>
        <tr>
            <td>Luis Alejo Cardenas</td>
            <td>U202122519</td>
        </tr>
        <tr>
            <td>Francisco Hurtado Palomino</td>
            <td>U202117498</td>
        </tr>
        <tr>
            <td>Ariana Huapaya Buitron</td>
            <td>U201819645</td>
        </tr>
        <tr>
            <td>Tony Do Santos Torres Cortez</td>
            <td>U201917662</td>
        </tr>
    </table>
</div>
<br>

# Registro de Versiones del Informe

| Versión |   Fecha    |              Autor               | Descripción de modificación                                                                                          | 
|:-------:|:----------:|:--------------------------------:|:---------------------------------------------------------------------------------------------------------------------| 
|   TB1   | 03/09/2024 | Todos los integrantes del equipo | Se presento una primera version de nuestra web aplication, agregando todo el estudio de segmento objetivo.           |
|   TP1   | 22/09/2024 | Todos los integrantes del equipo | Se realizaron las correciones marcadas en la entrega anterior, ademas se añadiero nuevos capitulos en esta entrega.  |
|   TB2   | 30/10/2024 | Todos los integrantes del equipo | Se realizaron las correciones marcadas en la entrega anterior, se añadio el contenido correspondiente a esta entrega |
|   TF1   |     -      | Todos los integrantes del equipo |                                                                                                                      |


<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)

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
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management.]()
  - [5.1.1. Software Development Environment Configuration.]()
  - [5.1.2. Source Code Management.]()
  - [5.1.3. Source Code Style Guide & Conventions.]()
  - [5.1.4. Software Deployment Configuration.]()
- [5.2. Product Implementation & Deployment.]()
  - [5.2.1. Sprint Backlogs.]()
  - [5.2.2. Implemented Landing Page Evidence]()
  - [5.2.3. Implemented Frontend-Web Application Evidence]()
  - [5.2.4. Implemented Native-Mobile Application Evidence]()
  - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence]()
  - [5.2.6. RESTful API documentation]()
  - [5.2.7. Team Collaboration Insights]()
  - [5.3. Video About-the-Product.]()
  
### [Capítulo VI: Product Verification & Validation]()
- [6.1. Testing Suites & Validation]()
  - [6.1.1. Core Entities Unit Tests.]()
  - [6.1.2. Core Integration Tests.]()
  - [6.1.3. Core Behavior-Driven Development]()
  - [6.1.4. Core System Tests.]()
### [Capítulo VII: DevOps Practices]()
- [7.1. Continuous Integration]()
  - [7.1.1. Tools and Practices.]()
  - [7.1.2. Build & Test Suite Pipeline Components.]()
- [7.2. Continuous Delivery]()
  - [7.2.1. Tools and Practices.]()
  - [7.2.2. Stages Deployment Pipeline Components.]()
- [7.3. Continuous deployment]()
  - [7.3.1. Tools and Practices.]()
  - [7.3.2. Production Deployment Pipeline Components.]()


- [Avance de Conclusiones, Bibliografía y Anexos.]()

- [Conclusiones](#conclusiones-1)
- [Bibliografía](#bibliografía-1)
- [Anexos](#anexos-1)

### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<br><br>
# Project Report Collaboration Insights
## Student Outcome

Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| **Criterio específico**                                                                                                                              | **Acciones realizadas**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | <br>Francisco Hurtado Palomino TB1: Me encargue de realizar el análisis de la competencia, entrevistas y necesidades de los usuarios, ademas de la correccion completa del informe con nuevos detalles.<br>                <br>Luis Aejo Cardenas TB1: Me encargue del desarrolo de la App Web y APIResful, usando python, FastAPI, javascript, vue y html.<br><br>Tony Torres Cortez TB1: Me encargue realizar y resumir entrevista, ademas de redactar el capitulo V y la creacion del repositorio de acceptance tests.<br><br>Ariana Huapaya TB1: Me encargue realizar  Web Applications UX/UI Design., ademas del Software Object-Oriented Design y el Database Design. <br>Fabio Horna  TB1:Realize los mock ups, y el detalle de la solucion, diseño e implementacion de nuestra landing page tratamndo de mantener y respetar lo establñecido por normnas y cirterios de creacion de software y pautas de diseño al usuario.<br>  <br> Fabio Horna  TP:Colaboré de manera eficaz en el equipo, participando en el desarrollo de la landing page en HTML e integrando las pruebas de Core Systems Test, Core Entities Unit Tests, y Behavior-Driven Development (BDD). Mi contribución mejoró la comunicación y coordinación del equipo, lo que resultó en una entrega eficiente y alineada con los objetivos del proyecto  <br>  <br> Luis Aejo Cardenas TP: Mejoré los diferentes apartados de la página web, actualicé los endpoints para que se pudiera comunicar con el Api. También, modifiqué las tablas de nuestra base de datos para nuevos campos antes no previstos. <br> <br> Tony Torres Cortez TP: Para esta entrega, colabore junto con mi equipo de manera conjunto para realizar los cambios y actualizaciones respecto  las implementaciones mencionadas en entregas anteriores.  <br> <br> Ariana Huapaya TP: En esta entrega colabore con los integrantes realizando las correcciones presentadas en la entrega anterior, ademas se realizaron las pruebas automatizadas.   <br> <br> Francisco Hurtado TP: Para esta entrega colabore con el equipo para realizar los cambios necesarios pedidos en la entrega anterior, ademas de agregar las secciones de Continous monitoring and delivering <br> <br> Luis Aejo Cardenas TB2: Me encargué de añadir una ventana emergenta de reseña para la aplicación web, mientras que en el API implemente los endpoints para proceder con las reserva, al igual que la creacion de esta tabla en la base de datos ya existenete. </br> </br> Tony Torres Cortez TB2 : Colabore de manera eficaz con el equipo para el anisis de las diferentes funciones , identificando posibles mejoras y refinamientos futuros que puedan necesitar. </br> </br> Fabio Horna TB2 : Logre establecer un diseño eficaz de experimentos coordinancod con el equipo para mejorar la eficiencia del analisis de sobre manera, de esta forma identificando posibles escenarios, mejoras y diseños que se puedan implementar para una eficaz prueba de nuestros artefactos. </br> </br> Ariana Huapaya Buitron TB2 : Me encargue de establecer los datos analiticos, asi como los kpis, y metricas de seleccion con el equipo para mejorar la eficiencia del proyecto, asi pues, hice un tracking plan tanto en web como en dipositivo movil sobre nuestro proyecto para experimentar su funcionabilidad. </br> </br> Francisco Hurtado Palomino TB2 : Para esta entrega me dedique a la documentacion del monitoreo de la API de MySQL que se creo para esta web application. |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.                                                             | <br>Francisco Hurtado Palomino TB1: Utilice mi conocimiento en lenguaje .md para la creacion  del informe.<br>        <br>Luis Aejo Cardenas TB1: Utilice Vercel para el deploy del FrontEnd, Clever Cloud para la base de datos y Render para el APIRestful<br><br>Tony Torres Cortez TB1: Utilice mi conocimiento para redacciones y rectificaciones en lenguaje html y .md.<br>        <br>Ariana Huapaya Buitron TB1: He aplicado mis habilidades en el diseño de UX/UI, diseño orientado a objetos, y diseño de bases de datos en el sector de aplicaciones web educativas, ayudando a crear soluciones que mejoran la experiencia del usuario y optimizan la gestión de información en plataformas digitales. <br> <br>Fabio Horna  TB1: Utilice diferente herramientas para la implementacion de la aplciacion relacionando problemas con caracteristicas funcionales para luego implementarlas<br> <br> Fabio Horna TP: Apliqué mis conocimientos de desarrollo web y pruebas de software dentro de un sector empresarial específico, desarrollando una landing page funcional y realizando pruebas que aseguraron que la solución cumpliera con las necesidades del dominio. Ajusté el producto a los requisitos del negocio, garantizando su relevancia y efectividad para los usuarios finales.  <br> <br> Luis Alejo Cardenas TP: Utilicé mis conocimientos en VUE y javascript para crear una pantalla emergente para publicar un post en el FrontEnd y registrarlo en nuestra base de datos. <br> <br> Tony Torres Cortez TP: Aplique mis conocimientos de tests de paginas web, utilizando la herramienta Selenium para detallar el paso a paso y el buen funcionamiento implementado en nuestro proyecto.   <br> <br> Ariana Huapaya Buitron TP: Aplique mis conocimientos en la documentacion para arreglar los errores de la entrega pasada, ademas se utilizaron los conocimientos aprendidos en clases para automatizacion de pruebas <br> <br> Francisco Hurtado TP: Para esta entrega utilice mis conocimientos en vue.js para apoyar en el front end y las correciones necesarias, ademas adquiri nuevos conconimientos para la automaticacion de tareas. <br> <br> Luis Aejo Cardenas TB2: Utilizando mis conocimientos de programación pude mejorar el frontend, al igual que rediseñar algunas tablas en el backend y desplegar nuestro API en otro servicio para lograr una mejor comunicacion entre toda la aplicacion web. </br> </br> Tony Torres Cortez TB2 :  Utilice mis conocimientos en experimentación identificando y resaltando los diferentes ajustes propuestos e implementaciones solicitas con respecto a la entrega previa  </br> </br> Fabio Horna TB2 :   COmo programador utilice mis conocimientos en al teoria lpara plantar eficazmente hipotesis y experimentos acompañadas de pruebas que sirvan para mejroar el uso de nuestra plataforma eficazmente </br> </br> Ariana Huapaya Buitron TB2 :  Como programar utilice mis conocimientos en teoricos para calcular la escalas de nuestras decisiones, y diseñar experimentos, acompañados de pruebas que contribuyan a mejorar el uso de nuestra plataforma de manera efectiva. </br> </br> Francisco Hurtado Palomino TB2 :  Utilice mi conocimiento obtenido a lo largo del curso para monitorear y experimentar con el funcionamiento de la app.                                                                                                                                                                       |
