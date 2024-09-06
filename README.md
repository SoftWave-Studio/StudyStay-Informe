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

| Versión |   Fecha    |              Autor               | Descripción de modificación | 
|:-------:|:----------:|:--------------------------------:|:----------------------------| 
|   TB1   | 03/09/2024 | Todos los integrantes del equipo |                             |
|   TP1   |     -      | Todos los integrantes del equipo |                             |
|   TB2   |     -      | Todos los integrantes del equipo |                             |
|   TF1   |     -      | Todos los integrantes del equipo |                             |


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

- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)

    - [5.2.1. Sprint 1](#521-sprint-1)
        - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
        - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
        - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
        - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

    - [5.2.2. Sprint 2](#522-sprint-2)
        - [5.2.2.1. Sprint Planning 2.](#5221-sprint-planning-2)
        - [5.2.2.2. Sprint Backlog 2.](#5222-sprint-backlog-2)
        - [5.2.2.3. Development Evidence for Sprint Review.](#5223-development-evidence-for-sprint-review)
        - [5.2.2.4. Testing Suite Evidence for Sprint Review.](#5224-testing-suite-evidence-for-sprint-review)
        - [5.2.2.5. Execution Evidence for Sprint Review.](#5225-execution-evidence-for-sprint-review)
        - [5.2.2.6. Services Documentation Evidence for Sprint Review.](#5226-services-documentation-evidence-for-sprint-review)
        - [5.2.2.7. Software Deployment Evidence for Sprint Review.](#5227-software-deployment-evidence-for-sprint-review)
        - [5.2.2.8. Team Collaboration Insights during Sprint 2.](#5228-team-collaboration-insights-during-sprint-2)

    - [5.2.3. Sprint 3](#523-sprint-3)
        - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
        - [5.2.3.2. Sprint Backlog 3](#5232-sprint-backlog-3)
        - [5.2.3.3. Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
        - [5.2.3.4. Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
        - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
        - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
        - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
        - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)

    - [5.2.4. Sprint 4](#524-sprint-4)
        - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-3)
        - [5.2.4.2. Sprint Backlog 4](#5242-sprint-backlog-3)
        - [5.2.4.3. Development Evidence for Sprint Review](#5243-development-evidence-for-sprint-review)
        - [5.2.4.4. Testing Suite Evidence for Sprint Review](#5244-testing-suite-evidence-for-sprint-review)
        - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
        - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
        - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
        - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)

- [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
        - [Segmento 1: Estudiantes que buscan información sobre habitaciones](#segmento-1-estudiantes-que-buscan-información-sobre-habitaciones)
            - [Presentación del entrevistado](#presentación-del-entrevistado)
            - [Explicación de los alcances de la demostración](#explicación-de-los-alcances-de-la-demostración)
            - [Navegación a través de la aplicación web](#navegación-a-través-de-la-aplicación-web)
                - [User Flow: Reserva de habitación](#user-flow-reserva-de-habitación)
            - [Preguntas Principales](#preguntas-principales)
        - [Segmento 2: Arrendadores que buscan alquilar habitaciones](#segmento-2-arrendadores-que-buscan-alquilar-habitaciones)
            - [Presentación del entrevistado](#presentación-del-entrevistado-1)
            - [Explicación de los alcances de la demostración](#explicación-de-los-alcances-de-la-demostración-1)
            - [Navegación a través de la aplicación web](#navegación-a-través-de-la-aplicación-web-1)
                - [User Flow: Publicar habitación](#user-flow-publicar-habitación)
            - [Preguntas Principales](#preguntas-principales-1)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)

- [5.4. Video About-the-Product](#54-video-about-the-product)
- [5.5. Video About-the-Team](#55-video-about-the-team)
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

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
  </tr>
  <tr>
    <td><b>Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.</b></td>
    <td> 
Francisco Hurtado Palomino TB1: Me encargue de realizar el análisis de la competencia, entrevistas y necesidades de los usuarios, ademas de la correccion completa del informe con nuevos detalles.
                <br>
Luis Aejo Cardenas TB1: Me encargue del desarrolo de la App Web y APIResful, usando python, FastAPI, javascript, vue y html.
<br>
Tony Torres Cortez TB1: Me encargue realizar y resumir entrevista, ademas de redactar el capitulo V y la creacion del repositorio de acceptance tests.
<br>
Ariana Huapaya TB1: Me encargue realizar  Web Applications UX/UI Design., ademas del Software Object-Oriented Design y el Database Design. <br>
Fabio Horna  TB1:Realize los mock ups, y el detalle de la solucion, diseño e implementacion de nuestra landing page tratamndo de mantener y respetar lo establñecido por normnas y cirterios de creacion de software y pautas de diseño al usuario.
                <br>
   </td>

  </tr>
  <tr>
    <td><b>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</b></td>
    <td> 
Francisco Hurtado Palomino TB1: Utilice mi conocimiento en lenguaje .md para la creacion  del informe.
        <br>
Luis Aejo Cardenas TB1: Utilice Vercel para el deploy del FrontEnd, Clever Cloud para la base de datos y Render para el APIRestful
<br>
Tony Torres Cortez TB1: Utilice mi conocimiento para redacciones y rectificaciones en lenguaje html y .md.
        <br>
Ariana Huapaya Buitron TB1: He aplicado mis habilidades en el diseño de UX/UI, diseño orientado a objetos, y diseño de bases de datos en el sector de aplicaciones web educativas, ayudando a crear soluciones que mejoran la experiencia del usuario y optimizan la gestión de información en plataformas digitales. <br>
Fabio Horna  TB1: Utilice diferente herramientas para la implementacion de la aplciacion relacionando problemas con caracteristicas funcionales para luego implementarlas
   </td>
  </tr>
</table>

<br><br>
