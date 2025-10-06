<div align="center">

<img width="125" height="125" alt="image" src="https://github.com/user-attachments/assets/998a5621-906e-45a8-9368-0a74b48f0d6e" />

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2025-20

# Arquitecturas De Software Emergentes


NRC 14653

Profesor: Berrocal Navarro, Richard Leonardo 

***INFORME DE TRABAJO - TP***

**Startup: DevTergentes**

**Producto: SecurOn**

**Integrantes**
| Nombre completo | Código        |
|----------------------------------------------|---------------|
| Amaro Villanueva, Camila Elena               | U202114248    |
| Astuyauri Calderon, Jherson David            | U202218451    |
| Calderon Huaman, Jose Daniel Mario           | U202213076    |
| Antonio Fretel, Jeremi Jose                  | U202219022    |
| Quispesivana Torres, Claudio Sandro          | U202215099    |

</div>
<br><div align="center"><h3>Septiembre 2025</h3></div><br>

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 18/09/2025 | Todos los integrantes del equipo  | Se completó la primera entrega del TB1.  |

---

# Project Report Collaboration Insights

**TB1:** Se han desarrollado las actividades correspondientes para la entrega TB1 dentro de nuestra organización de Git Hub.

Link de Github: [https://github.com/DevTergentes](https://github.com/DevTergentes)

*Registro de commits*
<img width="1022" height="585" alt="image" src="https://github.com/user-attachments/assets/365d5b4b-fc4b-46a8-bd1e-dec62e80f457" />

---

# Contenido 
## Tabla de contenidos
# [Student Outcome](#student-outcome)
## [Capítulo I: Introducción](#capítulo-i-introducción)
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
## [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#234-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
## [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#411-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
 ## [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.X. Bounded Context: <Bounded Context Name>](#5x-bounded-context-bounded-context-name)
    - [5.X.1. Domain Layer](#5x1-domain-layer)
    - [5.X.2. Interface Layer](#5x2-interface-layer)
    - [5.X.3. Application Layer](#5x3-application-layer)
    - [5.X.4. Infrastructure Layer](#5x4-infrastructure-layer)
    - [5.X.6. Bounded Context Software Architecture Component Level Diagrams](#5x6-bounded-context-software-architecture-component-level-diagrams)
    - [5.X.7. Bounded Context Software Architecture Code Level Diagrams](#5x7-bounded-context-software-architecture-code-level-diagrams)
      - [5.X.7.1. Bounded Context Domain Layer Class Diagrams](#5x71-bounded-context-domain-layer-class-diagrams)
      - [5.X.7.2. Bounded Context Database Design Diagram](#5x72-bounded-context-database-design-diagram)
## [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.2. Labeling Systems](#622-labeling-systems)
    - [6.2.3. Searching Systems](#623-searching-systems)
    - [6.2.4. SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
    - [6.2.5. Navigation Systems](#625-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.2. Applications Mock-ups](#642-applications-mock-ups)
    - [6.4.3. Applications User Flow Diagrams](#643-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
     

## [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.


| Criterio específico | Acciones realizadas                                                                                                      | Conclusiones |
| - |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Ayude en la en la elaboración de epics junto con sus respectivas user y technical stories teniendo en cuenta las necesidades identificadas en nuestros segmentos objetivos y los posibles escenarios que podrían presentarse. Esto nos permitió anticipar cómo deberíamos actuar ante diferentes situaciones. Asimismo, brindé apoyo en la creación de los impact maps correspondientes a los dos segmentos objetivos definidos.<br><br>**Jherson David Astuyauri Calderon**<br>Apoyé activamente a la identificación de eventos de dominio para mejorar la experiencia de usuario durante las interacciones con funciones centrales de nuestro sistema *SecurOn*. Para ello, se realizó un proceso completo de event storming siguiendo un patrón de pasos preestablecidos que nos permitió visualizar la lógica correcta del sistema.<br><br>**Claudio Sandro Quispesivana Torres**<br>Participé en la elaboración de los segmentos objetivo, el análisis de competidores y la definición de estrategias frente a ellos, lo cual requirió coordinación constante con el equipo. Asimismo, realicé el diseño de entrevistas y el análisis de resultados, fomentando el intercambio de ideas y perspectivas para fortalecer la solución final.<br><br>**Jose Daniel Mario Calderon Huaman**<br>Desarrollé la parte de descripción del startup del equipo, así como nuestro solution profile frente a una necesidad identificada, los antecendes que surgieron previamente a esta problemática y las solución que nuestra solución ofrece.<br><br>**Jeremi Jose Antonio Fretel**<br>Contribuí de manera activa en el desarrollo de los arquetipos de usuarios y en la definición de sus necesidades principales, lo que permitió orientar mejor el diseño de soluciones dentro del proyecto. Además, colaboré en la preparación de los journey maps para visualizar las experiencias de los usuarios en diferentes etapas del proceso. Este trabajo facilitó la identificación de puntos críticos y oportunidades de mejora en el sistema propuesto, asegurando una propuesta de valor más ajustada a las expectativas reales. | **TB1:** Como equipo, trabajamos de manera colaborativa para cubrir todas las etapas clave del desarrollo inicial de SecurOn, desde la definición del problema y el análisis de mercado hasta la construcción de la solución tecnológica. Cada integrante asumió un rol fundamental en áreas como la elaboración de user stories, la identificación de eventos de dominio, el diseño de entrevistas, la creación de arquetipos, el mapeo de experiencias y el modelado de la arquitectura del sistema. Esta sinergia nos permitió integrar múltiples perspectivas y asegurar una base sólida, estratégica y centrada en el usuario para el desarrollo de nuestra solución. 
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Participé de manera activa en las reuniones de planificación del proyecto, así como en su desarrollo. Además, me encargué de organizar las tareas relacionadas con la elaboración de las user stories, basándome en la información recopilada por cada integrante del equipo a través de entrevistas realizadas a usuarios pertenecientes a los segmentos objetivo.<br><br>**Jherson David Astuyauri Calderon**<br>Organicé las diferentes reuniones utilizando la metodología daily scrum hasta la entrega, donde identificamos las partes faltantes de nuestro trabajo, priorizamos tareas pendientes y coordinamos responsabilidades para asegurar el avance constante del proyecto. Donde la comunicación efectiva fue clave dentro del equipo para resolver bloqueos de forma oportuna y mantener la misma alineación.<br><br>**Claudio Sandro Quispesivana Torres**<br>Contribuí activamente a la creación de un entorno colaborativo, establecimos metas claras desde las fases iniciales del proyecto y organicé tareas relacionadas con el diseño táctico del software, abarcando los distintos Bounded Contexts. Coordiné la elaboración de las distintas capas arquitectónicas y diagramas técnicos, asegurando una planificación eficiente y cumplimiento de los plazos.<br><br>**Jose Daniel Mario Calderon Huaman**<br>Desarrollé el Lean UX Process, una artefacto fundamental para identificar nuestras funciones claves, segmentos objetivos, identificación y establecimiento de nuestra solución frente a la problemática identificada brindando una gráfica ejemplar y amplia para implementar una solución completa.<br><br>**Jeremi Jose Antonio Fretel**<br>Apoyé en la validación de requerimientos técnicos y funcionales, asegurando que cada propuesta se ajustara a los objetivos del proyecto. También colaboré activamente en la elaboración de diagramas de flujo y en la definición de entidades clave del sistema. Durante el desarrollo, participé en sesiones de retroalimentación continua, lo que permitió realizar ajustes oportunos y mantener la calidad en cada entrega parcial.  | **TB1:** El equipo demostró una sólida capacidad para colaborar de forma inclusiva, planificando estratégicamente las tareas y cumpliendo los objetivos del proyecto. A través de reuniones constantes, el uso de metodologías ágiles y una distribución clara de responsabilidades, logramos mantener una comunicación efectiva, anticipar desafíos y avanzar de manera organizada. Esto nos permitió construir una base sólida para el desarrollo de SecurOn, alineando tanto los aspectos técnicos como los objetivos del negocio. |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup DevTergentes, conformado por estudiantes de la Universidad Peruana de Ciencias Aplicadas, nace con el propósito de aportar a la sociedad mediante soluciones tecnológicas que mejoren la seguridad en el transporte de productos peligrosos. Su misión es optimizar la calidad del servicio con eficiencia, seguridad y transparencia, mientras que su visión es liderar en el Perú el desarrollo de soluciones IoT aplicadas al transporte seguro de materiales reactivos.

La propuesta consiste en un sistema integral de monitoreo con IoT que controla tanto las condiciones de salud del conductor como parámetros críticos de la carga (velocidad, horas de manejo, fugas de gas, temperatura y presión). Ante cualquier anomalía, el sistema envía alertas y activa medidas preventivas para mitigar riesgos y garantizar la integridad del transporte.

### 1.1.2. Perfiles de integrantes del equipo

A continuación, presentaremos los perfiles de los integrantes del equipo encargado de desarrollar el proyecto. Cada uno de nuestros miembros aporta una combinación única de habilidades y perspectivas que son fundamentales para el éxito del proyecto.

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Amaro Villanueva, Camila Elena - u202114248**             |Mi nombre es Camila Elena Amaro Villanueva, cuento con conocimientos de desarrollo frontend y backend, además de lenguajes de programación como C++, Python y JavaScript. Además, entre mis habilidades, puedo resaltar la responsabilidad y creatividad que poseo para aportar en los trabajos en equipo. | <img src="https://i.imgur.com/2UzudVJ.jpeg" alt="Imagen de Camila Amaro" />|
| **Astuyauri Calderon, Jherson David - u202218451**          |Soy Jherson, estudiante de Ingeniería de Software en la UPC (8.º ciclo). Me apasiona la inteligencia artificial y su potencial para transformar el mundo mediante soluciones más inteligentes y humanas. Tengo adaptabilidad, soy una persona responsable y proactiva con muchas ganas de crecer profesionalmente. | <img src="https://jhersonss24-portafolio.netlify.app/assets/profile-front_1.jpg" alt="Imagen de Jherson" />|
| **Quispesivana Torres, Claudio Sandro - u202215099**     |Mi nombre es Claudio Sandro Quispesivana Torres, tengo 20 años y estoy cursando el octavo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://raw.githubusercontent.com/TechZo-1ASI0732-4453/Report/refs/heads/main/Resources/Chapter-I/Profiles/sandroquispesivana.png" alt="Imagen de Sandro Quispesivana"/> |
| **Calderon Huaman, Jose Daniel Mario - U202213076** |Soy estudiante de 8.º ciclo de Ingeniería de Software con experiencia en desarrollo full-stack. Me considero una persona responsable, organizada y comprometida. Valoro el trabajo en equipo y me esfuerzo por aportar soluciones eficientes y bien estructuradas. He trabajado con tecnologías como React, Tailwind, Express.js, JavaScript y TypeScript, aplicándolas en proyectos reales. También tengo conocimientos en C++, Python y Flutter. | <img src="https://github.com/user-attachments/assets/7a670c75-fa1d-45d8-847c-2e829189ce79" alt="Imagen de Jose Calderon" /> |
| **Antonio Fretel, Jeremi Jose - U202219022** |Soy estudiante de 8vo ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona disciplinada y comprometida con mis objetivos académicos. He trabajado con tecnologías como C++, Python, Java, HTML/CSS, React y SQL. He desarrollado proyectos académicos principalmente en React.| <img src="https://github.com/user-attachments/assets/90844ac8-41e9-4feb-b7b7-d254379758e2" alt="Imagen de Jeremi Antonio" /> |

## 1.2. Solution Profile

**Product name**


El nombre asignado a nuestra solución es SecurOn. Este nombre refleja el concepto de seguridad activa y permanente durante todo el proceso de transporte, garantizando que tanto la carga como el conductor estén protegidos en todo momento.


**Product Description**

SecurOn es una solución basada en IoT que transforma el transporte de materiales peligrosos mediante un sistema integral de monitoreo. A través de sensores inteligentes instalados en el vehículo y en el conductor, se supervisan parámetros críticos como fugas de gas, temperatura, presión y condiciones de salud del operador.
En caso de detectar una anomalía, el sistema envía notificaciones inmediatas y activa mecanismos de alerta para prevenir incidentes. De esta manera, se asegura la integridad de la carga, la seguridad del conductor y la tranquilidad de las empresas transportistas.


**Monetización**

El modelo de negocio de SecurOn se basa en un esquema de suscripción que cubre tanto el uso de los dispositivos IoT como el acceso a la plataforma de monitoreo y gestión.

### 1.2.1. Antecedentes y problemática

En la última década, el transporte de productos peligrosos —como gases inflamables, sustancias químicas e insumos industriales— se ha convertido en una actividad de alto riesgo. Numerosos incidentes han demostrado que una fuga, un derrame o una explosión pueden generar daños graves al personal, al medio ambiente y a las comunidades cercanas.

Uno de los principales problemas es la detección tardía de anomalías. La falta de un sistema de monitoreo en tiempo real impide identificar a tiempo variaciones de presión, temperatura o movimientos anormales del vehículo, lo que convierte pequeños problemas en emergencias críticas.

Otro reto es la fragmentación tecnológica. Muchas empresas aún dependen de controles manuales o de equipos obsoletos que no ofrecen una supervisión integral ni centralizada, lo cual genera vulnerabilidades operativas.

A ello se suman las exigencias regulatorias cada vez más estrictas. No cumplir con la normativa de transporte de materiales peligrosos implica sanciones legales, pérdidas económicas y un daño significativo a la reputación empresarial.

SecurOn surge como respuesta a esta problemática, ofreciendo una solución digital moderna, integral y confiable.

**Herramienta 5W y 2H**

**¿Qué? (What)**

El transporte de productos peligrosos como gases y químicos implica riesgos altos: fugas, explosiones y derrames. La falta de monitoreo en tiempo real impide detectar estas situaciones a tiempo.

**¿Cuándo? (When)**

Estos problemas ocurren de manera constante durante los trayectos, especialmente en viajes largos o condiciones adversas donde no se supervisan las variables críticas.

**¿Dónde? (Where)**

Los incidentes pueden presentarse en carreteras, vías férreas o puertos, afectando no solo al transporte sino también a las comunidades y el medio ambiente.

**¿Quién? (Who)**

Los principales afectados son los conductores, las empresas transportistas, las comunidades cercanas a las rutas y las entidades reguladoras que supervisan la seguridad.

**¿Por qué? (Why)**

La mayoría de empresas aún usan sistemas manuales o desactualizados, lo que genera brechas de seguridad y dificulta cumplir con normativas cada vez más estrictas.

**¿Cómo? (How)**

Los incidentes ocurren cuando fugas o anomalías no son detectadas a tiempo. Sin un monitoreo integral, pequeños problemas pueden escalar a emergencias graves.

**¿Cuánto? (How Much)**

En Latinoamérica se registran miles de incidentes anuales con gases y combustibles, ocasionando pérdidas económicas, sanciones legales y graves impactos ambientales.

**Conclusiones de las 5W + 2H**

Luego de analizar las 5W y 2H, se evidencia que la industria del transporte de productos peligrosos enfrenta desafíos críticos en la detección temprana de fugas y otros incidentes relacionados con la seguridad. La fragmentación y la falta de actualización de las tecnologías de monitoreo son factores clave que impiden una respuesta rápida y efectiva ante emergencias. Para mitigar estos riesgos, se requiere una solución integral que incluya la implementación de tecnologías de monitoreo continuo y en tiempo real, centralizando la supervisión y mejorando la capacidad de respuesta ante condiciones peligrosas. Esto no solo ayudaría a cumplir con las normativas cada vez más estrictas, sino que también protegería a los trabajadores, el medio ambiente y las comunidades circundantes.
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Los productos/servicios existentes no abordan adecuadamente el problema crítico de la detección temprana de fugas de gases combustibles (GNV) durante su transporte, lo que pone en riesgo tanto la seguridad de los conductores como la reputación de las empresas.

Nuestra solución abordará esta brecha proporcionando un sistema de monitoreo en tiempo real que, a través de sensores, detectará rápidamente cualquier anomalía durante el transporte antes de que afecte al conductor o al producto transportado y se convierta en una amenaza.

Nos enfocaremos inicialmente en empresas de transporte de gases combustibles que necesiten mejorar sus medidas de seguridad y reducir riesgos operativos.

Sabremos que hemos tenido éxito cuando observemos una reducción significativa en los incidentes relacionados con fugas de gas, junto con una mejora en la percepción de seguridad por parte de los conductores y las empresas involucradas.

#### 1.2.2.2. Lean UX Assumptions

*Bussiness Outcomes:*

- Incremento de la seguridad en el transporte de gases combustibles en un 30%. 

- Reducción del riesgo de explosiones en un 40%.

*Users:*

- **Conductores:** que transportan gases combustibles y necesitan protección frente a posibles fugas.
- **Empresas de transporte:** que desean asegurar la integridad de sus conductores y proteger su carga durante el transporte.

*User Outcomes & Benefits:*

- **Conductores:** Mayor seguridad durante el transporte de gases combustibles. Notificación temprana de posibles fugas, lo que permite tomar acciones inmediatas para evitar accidentes.
- **Empresas de transporte:** Monitoreo en tiempo real de las condiciones de seguridad de sus vehículos. Reducción de riesgos y responsabilidades asociadas a accidentes por fugas de gases.

*Features Assumptions:*

- **Monitoreo en tiempo real:** de las condiciones de seguridad mediante sensores en el vehículo (detección de fugas de gas, temperatura, presión, movimiento, etc.).
- **Alertas inmediatas:** al conductor y al centro de monitoreo en caso de detectar una fuga o condición peligrosa.
- **Registro histórico de datos:** para análisis y mejoras continuas en los protocolos de seguridad.
- **Integración con sistemas de gestión:** de la flota para una visión centralizada de la seguridad en el transporte.

*User Assumptions:*

- **¿Quién es el usuario?** Los usuarios de nuestra solución son conductores de vehículos que transportan gases combustibles y las empresas que gestionan estos transportes.
- **¿Dónde encaja nuestro producto en su trabajo o vida?** Nuestro producto es esencial en el día a día de los conductores, brindándoles una herramienta que les permite realizar su trabajo de manera más segura. Para las empresas, es una solución que mejora la seguridad y eficiencia operativa.
- **¿Qué problemas tiene nuestro producto? ¿Evitar?** Un posible desafío es que los conductores no confíen plenamente en el sistema o lo consideren complejo de usar. Para evitar esto, la interfaz debe ser sencilla y las alertas deben ser claras y precisas.
- **¿Cuándo y cómo es nuestro producto? ¿Usado?** Nuestra solución se utiliza durante todo el transporte de gases combustibles, monitoreando constantemente las condiciones de seguridad y emitiendo alertas en tiempo real.
- **¿Qué características son importantes?** Las características clave incluyen la detección precisa de fugas, la notificación instantánea al conductor, el registro de datos de seguridad y la capacidad de integración con sistemas de gestión de flotas.
- **¿Cómo debe verse nuestro producto y cómo comportarse?** La interfaz debe ser intuitiva y fácil de usar para los conductores. Las alertas deben ser visibles y comprensibles, y el sistema debe responder rápidamente a cualquier cambio en las condiciones de seguridad.

*Business Assumptions:*

- Creemos que nuestros clientes necesitan una mejor manera de asegurar la seguridad en el transporte de gases combustibles.
- Estas necesidades se pueden resolver con una solución IoT que permite el monitoreo en tiempo real y la detección temprana de fugas de gases.
- El valor principal que nuestro cliente quiere de nuestro servicio es la capacidad de prevenir accidentes graves mediante una detección temprana y notificación de fugas.
- El cliente también puede obtener beneficios adicionales como la reducción de costos asociados a accidentes y la mejora en la reputación de la empresa.
- Vamos a adquirir la mayoría de nuestros clientes mediante la promoción en ferias de seguridad, campañas en redes sociales, y recomendaciones de clientes actuales.
- Haremos dinero a través de la venta de dispositivos IoT y suscripciones al servicio de monitoreo.
- Nuestra competencia principal en el mercado serán otras soluciones de monitoreo de seguridad en el transporte de materiales peligrosos.
- Los venceremos debido a la simplicidad de uso de nuestra solución y a la precisión y rapidez en la detección de condiciones peligrosas.
- El mayor riesgo es que las empresas no adopten nuestra solución por considerarla innecesaria o por resistencia al cambio.
- Resolveremos esto a través de demostraciones de la efectividad del sistema y ofreciendo soporte continuo a nuestros clientes.


#### 1.2.2.3. Lean UX Hypothesis Statements

A continuación, se plantean las hipótesis que proponen una solución a la problemática dentro de las funcionalidades de la solución tecnológica. Cada una de estas hipótesis es específica y medible para sustentar el éxito de manera objetiva. Cabe resaltar que las métricas actuales son iguales a promedios generales de soluciones ya existentes.

### Hipótesis 1:
*Creemos que los conductores necesitan una solución que les alerte rápidamente sobre posibles fugas de gases combustibles (GNV).*
*Sabremos que hemos tenido éxito cuando nuestra solución IoT se convierta en una herramienta esencial para la seguridad diaria de los conductores.*

**Métricas:**
1. *Frecuencia de Uso Diario:* Porcentaje de conductores que utilizan el sistema de monitoreo IoT diariamente.
   - Métrica actual: 20%
   - Meta deseada: 60%

2. *Retención a Largo Plazo:* Porcentaje de conductores que siguen utilizando la solución después de 3 meses.
   - Métrica actual: 50%
   - Meta deseada: 70%

---

### Hipótesis 2:
*Creemos que las empresas de transporte necesitan monitorear en tiempo real las condiciones de seguridad de los vehículos que transportan gases combustibles.*
*Sabremos que hemos tenido éxito cuando las empresas adopten nuestra solución para todos sus vehículos de transporte de materiales peligrosos.*

**Métricas:**
1. *Implementación en la Flota:* Porcentaje de vehículos equipados con nuestro sistema IoT.
   - Métrica actual: 10%
   - Meta deseada: 80%

2. *Reducción de Incidentes:* Disminución del número de incidentes relacionados con fugas de gases en los vehículos que usan la solución.
   - Métrica actual: 2 incidentes mensuales
   - Meta deseada: 0 incidentes mensuales

---

### Hipótesis 3:
*Creemos que las empresas de transporte necesitan datos precisos para mejorar sus protocolos de seguridad.*
*Sabremos que hemos tenido éxito cuando las empresas utilicen los datos de nuestra solución para optimizar sus operaciones.*

**Métricas:**
1. *Uso de Datos para la Mejora Continua:* Número de empresas que reportan mejoras en sus protocolos de seguridad basadas en los datos recopilados por el sistema.
   - Métrica actual: 2 empresas
   - Meta deseada: 10 empresas

2. *Reducción en Costos de Seguro:* Porcentaje de reducción en los costos de seguro para las empresas que adoptan nuestra solución.
   - Métrica actual: 5% de reducción
   - Meta deseada: 20% de reducción

---

### Hipótesis 4:
*Creemos que las empresas de transporte deben evaluar constantemente la efectividad de los protocolos de seguridad implementados.*
*Sabremos que hemos tenido éxito cuando la calificación de seguridad de las empresas mejore significativamente gracias a nuestra solución.*

**Métricas:**
1. *Calificación de Seguridad:* Evaluación anual de seguridad por parte de las aseguradoras.
   - Métrica actual: 7/10
   - Meta deseada: 9/10

2. *Feedback de Conductores:* Porcentaje de conductores que reportan sentirse más seguros al utilizar el sistema.
   - Métrica actual: 60%
   - Meta deseada: 90%

---

### Hipótesis 5:
*Creemos que los sensores IoT mejorarán la seguridad en el transporte de gases combustibles.*
*Sabremos que hemos tenido éxito cuando los registros de alertas generadas por los sensores muestren una reducción en los riesgos de fugas.*

**Métricas:**
1. *Alertas por Fugas:* Número de alertas emitidas por fugas detectadas.
   - Métrica actual: 15 alertas mensuales
   - Meta deseada: 5 alertas mensuales

2. *Satisfacción del Cliente:* Estrellas promedio en una escala de 1 a 5 basada en la satisfacción con la solución IoT.
   - Métrica actual: 4.0 estrellas promedio
   - Meta deseada: 4.8 estrellas promedio


#### 1.2.2.4. Lean UX Canvas


![image](https://github.com/user-attachments/assets/ed8887b4-8e82-49c9-ad85-539f768bda72)



## 1.3. Segmentos objetivo

| Tipo de Usuario | Conductores que transportan gases combustibles | Empresas de transporte que operan con materiales peligrosos | 
| - | - | - |
| **Geográfico** | País: Perú <br> Zona de operación: Zonas urbanas y rurales, especialmente aquellas asociadas a rutas de transporte de gases inflamables. | País: Perú <br> Zona de operación: Regiones que abarcan trayectos donde se movilizan materiales peligrosos.|  
| **Psicográfico** | Clase Social: Media <br> Estilo de Vida: Conductores experimentados en el manejo de materiales peligrosos, enfocados en la seguridad y la reducción de riesgos durante sus actividades laborales. | Clase social: No es relevante dado que puede incluir pequeñas empresas de transporte o grandes corporaciones. <br> Estilo de vida: Empresas orientadas a garantizar la seguridad y la eficiencia en el transporte de materiales peligrosos, con interés en la innovación y mejora continua de sus protocolos. |  
| **Demográfico** | Edad: 25 a 55 años <br> Nivel de Ingreso: No determinante; enfocado en conductores profesionales con trayectoria en el manejo de vehículos pesados. | Edad: 30 a 60 años <br> Nivel de ingreso: No es un factor clave; dirigido a empresas que administran flotas dedicadas al transporte de materiales peligrosos. |

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 18%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th rowspan="2">¿Por qué llevar a cabo este análisis?</th>
<th colspan="5">Se hace este analisis para conocer las debilidades y fortalezas y compararlas con el producto solución propuesto</th>
</tr>
<tr class="odd">
<th colspan="5">Permite reconocer las ventajas competitivas y áreas de mejora de "SecurOn" frente a competidores clave, facilitando el diseño de estrategias eficaces para destacarse en el sector agrícola y atraer a agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th></th>
<th></th>
<th>SecurOn</th>
<th>Grupo Caresny</th>
<th>Dachser</th>
<th>Cargo & Transport</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil</th>
<th>Overview</th>
<th>Plataforma tecnológica integral con sensores IoT para alertar y monitorear condiciones críticas durante el transporte de materiales peligrosos.</th>
<th>Empresa tradicional del rubro logístico, enfocada en soluciones personalizadas.</th>
<th>Multinacional con cobertura global y servicios de transporte terrestre, marítimo y aéreo.</th>
<th>Especialista en carga pesada y bienes industriales, con enfoque en mercados en crecimiento.</th>
</tr>
<tr class="header">
<th>Ventaja competitiva</th>
<th>Seguridad en tiempo real con sensores que detectan fugas, temperatura, presión y movimiento</th>
<th>Amplia red de transporte y servicios integrados.</th>
<th>Gran infraestructura global y experiencia en logística compleja.</th>
<th>Capacidad para operar en entornos difíciles y con cargas especiales.</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil de Marketing</th>
<th>Mercado Objetivo</th>
<th>Empresas del sector químico, petrolero y otras que gestionan transporte de materiales peligrosos.</th>
<th>Negocios que buscan servicios logísticos a medida, principalmente retail y consumo masivo.</th>
<th>Empresas internacionales con operaciones logísticas complejas.</th>
<th>Industrias pesadas y proyectos de infraestructura en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Estrategias de marketing</th>
<th>Promoción de seguridad y cumplimiento normativo como elementos diferenciadores.</th>
<th>Contratos duraderos y atención personalizada.	</th>
<th>Uso de infraestructura avanzada y tecnología para la cadena de suministro.</th>
<th>Reputación de fiabilidad y capacidad para manejar operaciones complejas.</th>
</tr>
<tr class="odd">
<th rowspan="3">Perfil de Producto</th>
<th>Productos &amp; Servicios</th>
<th>Monitoreo IoT especializado en transporte seguro de productos peligrosos.	</th>
<th>Servicios de transporte terrestre, almacenamiento y logística.</th>
<th>Transporte multimodal y soluciones integradas de cadena de suministro.</th>
<th>Transporte de gran escala, logística para proyectos industriales.</th>
</tr>
<tr class="header">
<th>Precios y Costos</th>
<th>Modelo por suscripción ajustable según cantidad de sensores y funcionalidades.</th>
<th>Tarifas competitivas y adaptables al tipo de servicio.	</th>
<th>Costos variables según la complejidad y cobertura requerida.</th>
<th>Costos determinados por tipo de carga y nivel de dificultad.</th>
</tr>
<tr class="odd">
<th><p>Canales de distribución</p>
<p>(Web y/o Móvil)</p></th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
</tr>
<tr class="header">
<th rowspan="5">Análisis SWOT</th>
<th colspan="5">Realice esto para su startup y sus competidores. Sus
fortalezas deberían apoyar sus oportunidades y contribuir a lo que
ustedes definen como su posible ventaja competitiva.</th>
</tr>
<tr class="odd">
<th>Fortalezas</th>
<th>Alta innovación tecnológica, monitoreo en tiempo real, y plataforma digital robusta.</th>
<th>Red logística consolidada, relaciones sólidas con clientes.</th>
<th>Cobertura internacional, experiencia en logística avanzada.</th>
<th>Capacidad para manejar cargas especiales, presencia fuerte en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Debilidades</th>
<th>Alta dependencia tecnológica, posibles costos iniciales elevados.</th>
<th>Falta de innovación frente a competidores modernos.</th>
<th>Costos altos, fuerte presencia en mercados maduros más que emergentes.</th>
<th>Cobertura global limitada frente a otras multinacionales.</th>
</tr>
<tr class="odd">
<th>Oportunidades</th>
<th>Mayor demanda por soluciones seguras, posibilidad de expansión internacional.	</th>
<th>Potencial para adoptar nuevas tecnologías y expandirse.	</th>
<th>Crecimiento en mercados emergentes, enfoque sostenible.	</th>
<th>Posibilidad de ingresar a nuevos sectores y alianzas tecnológicas.</th>
</tr>
<tr class="header">
<th>Amenazas</th>
<th>Competencia con grandes corporaciones con más recursos, cambios en la regulación.	</th>
<th>Presión de empresas más tecnológicas y competitivas.	</th>
<th>Volatilidad económica global, competencia en mercados emergentes.	</th>
<th>Restricciones ambientales más estrictas, competencia en precios.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

| Estrategia/ Táctica                          | Medidas a tomar                                         |
|----------------------------------------------|---------------------------------------------------------|
| Diferenciación en implementación IoT | \- Destacar la ventaja de la implementación de sensores junto con una aplicación    |
|                                              | \- Resaltar el uso de sensores durante todo el transporte           |
|                                              | \- Alianzas con empresas de transporte |
| Enfoque en la seguridad                    | \- Priorizar la seguridad de los conductores         |
|                                              | \- Ofrecer a las empresas los detalles obtenidos por los sensores en tiempo real         |
| Publicidad mediante redes sociales         | \- Resaltar funcionalidades IoT            |
|                                              | \- Publicitar la solución IoT mediante Facebook, Instagram y Google Ads.           |

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas.

A continuación, se diseñaron entrevistas dirigidas a los dos segmentos objetivos definidos para el proyecto. Las preguntas fueron elaboradas con el fin de generar respuestas abiertas y detalladas por parte de los entrevistados, permitiendo así obtener información valiosa que nos ayude a comprender mejor sus necesidades. Cabe mencionar que las preguntas de introducción no están incluidas en esta lista; sin embargo, se realizarán al inicio de cada entrevista.

**Segmento objetivo: Transportistas**

El objetivo de las preguntas del segmento objetivo de los transportistas es identificar las necesidades, desafíos y preferencias de los transportistas en relación con la seguridad y el monitoreo de cargas peligrosas, con el propósito de diseñar una solución tecnológica que mejore su eficiencia y protección durante el transporte.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué sistemas de seguridad utilizas actualmente para evitar incidentes durante el transporte de gases inflamables?

- ¿Has vivido alguna situación relacionada con fugas de gas u otro tipo de incidente? En caso afirmativo, ¿cómo respondiste ante ello?

- ¿Qué dificultades o problemas encuentras con mayor frecuencia en tu labor como transportista?

- ¿Cuentas con alguna tecnología o dispositivo que te permita monitorear la seguridad de tu carga mientras estás en ruta? ¿Qué ventajas y desventajas has percibido?

- ¿Estarías dispuesto a incorporar una solución tecnológica que permita supervisar en tiempo real las condiciones del cargamento? ¿Cuál sería tu motivación?

- ¿Qué tipos de sensores consideras adecuados para el monitoreo de combustibles durante el transporte en vehículos?

- ¿Qué clase de notificaciones o alertas crees que serían más efectivas para prevenir posibles fugas de gases durante el traslado?

- ¿Cuál sería tu canal preferido para recibir este tipo de alertas (por ejemplo, app móvil, SMS, entre otros)?

- ¿Qué obstáculos crees que podrían dificultar la incorporación de nuevas tecnologías de monitoreo en tu trabajo diario?

- ¿Qué funcionalidades considerarías imprescindibles en una solución tecnológica emergente para adoptarla como parte de tu rutina?

- ¿Cuál es tu opinión sobre las tecnologías actuales que existen en el mercado enfocadas en la seguridad del transporte de materiales peligrosos?

- ¿Qué mejoras consideras necesarias en estas soluciones para que resulten más eficientes y útiles?

- ¿Tu vehículo cuenta con una pantalla que permita la interacción con algún sistema operativo?

- ¿Qué dispositivos usas con mayor frecuencia durante tus jornadas laborales?

**Segmento objetivo: Empresas de transporte de productos peligrosos**

El objetivo de las preguntas del segmento objetivo de las empresas de transporte de productos peligrosos es evaluar las estrategias de seguridad, tecnologías actuales y disposición de las empresas de transporte para adoptar soluciones IoT, con el fin de identificar oportunidades de mejora y diseñar una herramienta que optimice la gestión y seguridad de las operaciones logísticas.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué medidas de seguridad aplica tu empresa para proteger tanto al personal como a la carga durante el traslado de productos peligrosos?

- ¿Cómo se lleva a cabo la formación del personal en temas de prevención de incidentes y actuación ante emergencias?

- ¿Qué tecnologías o herramientas están actualmente en uso en tu empresa para supervisar la seguridad de las cargas peligrosas?

- ¿Qué tipos de sensores consideras más apropiados para el monitoreo de combustibles en vehículos?

- ¿Tu empresa estaría interesada en adoptar una solución IoT para supervisar en tiempo real la seguridad de los cargamentos? ¿Por qué razón?

- ¿Qué beneficios esperas lograr mediante la implementación de una tecnología IoT enfocada en la seguridad?

- ¿Qué inquietudes podrían surgir respecto a la adopción de esta solución en tu organización?

- ¿De qué forma prefieres que tu empresa reciba alertas sobre posibles riesgos durante el transporte?

- ¿Cómo impactarían estas notificaciones en las decisiones operativas de tu empresa?

- ¿Consideras que una solución de monitoreo basada en IoT podría convertirse en una ventaja competitiva? ¿De qué manera?

- ¿Qué características clave debería tener esta solución para destacar frente a otras propuestas tecnológicas del mercado?

### 2.2.2. Registro de entrevistas

**Segmento objetivo: Transportistas**

### Primera Entrevista

| Campo       | Detalle |
|-------------|---------|
| **Nombre**  | Carolina Torres Torres |
| **Edad**    | 27 |
| **Inicio**  | 0:00 |
| **Fin**     | 5:06 |
| **Duración**| 5:06 |
| **Link**    | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218451_upc_edu_pe/ERzZzWSCvfVKhMVEPHadV3EBtcJbmxtE9d_93Lfp8QX-DQ?e=06ngK3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Imagen**  | ![entrevista1t](https://i.imgur.com/0MFB9Rr.png) |
| **Resumen de la entrevista** | Carolina es una transportista de productos reactivos y actualmente cuenta con un sistema de GPS y un monitoreo de temperatura básico instalado en su vehículo. Su principal motivación para incorporar una solución tecnológica adicional es mejorar su seguridad, ya que esto le permitiría prevenir un mayor número de accidentes que podrían poner en riesgo su integridad y la de las personas a su alrededor. Además, menciona que esta solución también le brindaría mayor tranquilidad durante sus recorridos. Carolina prefiere que las notificaciones se emitan mediante alertas sonoras, ya que considera que así podrá estar más atenta mientras conduce. En cuanto a funcionalidades imprescindibles, destaca el monitoreo en tiempo real, las alertas automáticas y el acceso inmediato desde la central. |


### Segunda Entrevista

| Campo       | Detalle |
|-------------|---------|
| **Nombre**  | Maricielo Valdivia |
| **Edad**    | 25 |
| **Inicio**  | 5:06|
| **Fin**     | 9:13 |
| **Duración**| 4:07 |
| **Link**    | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218451_upc_edu_pe/ERzZzWSCvfVKhMVEPHadV3EBtcJbmxtE9d_93Lfp8QX-DQ?e=06ngK3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Imagen**  | ![entrevista_2](https://github.com/user-attachments/assets/4dc6f462-920d-4513-adcf-1dc2e1ca6348) |
| **Resumen de la entrevista** | Maricielo, de 25 años y residente en Callao, relató que tuvo una experiencia con una fuga menor de gas, frente a la cual actuó siguiendo los protocolos de seguridad. Entre sus principales dificultades menciona el tráfico, las largas jornadas y la falta de espacios seguros para detenerse. Actualmente, utiliza un sistema de GPS que le resulta útil para el control de rutas, aunque reconoce que no brinda información sobre el estado de la carga. Está dispuesta a incorporar una solución tecnológica de monitoreo en tiempo real, motivada por la seguridad y la prevención de accidentes, siempre que sea sencilla y práctica. Considera clave el uso de sensores de presión, temperatura y gases, y cree que las alertas más efectivas serían las sonoras inmediatas y las notificaciones en celular, preferentemente mediante una app móvil o mensajes de texto. Identifica como posibles obstáculos el costo, el mantenimiento y la capacitación. En su rutina laboral utiliza con mayor frecuencia el celular, el GPS y la radio de comunicación. |


**Segmento objetivo: Empresas de transporte de productos peligrosos**

### Primera Entrevista

| Campo       | Detalle |
|-------------|---------|
| **Nombre**  | Arnhol Castrejon |
| **Inicio**  | 0:00 |
| **Fin**     | 4:32 |
| **Duración**| 4:32 |
| **Link**    | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218451_upc_edu_pe/Ef69MXwMrZZGqLdEIjw5134BLTEMz3ZmWUUBnmpt836yhg?e=VCLD5t&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Imagen**  | <img width="1235" height="446" alt="image" src="https://github.com/user-attachments/assets/c26fb33c-a0e3-44a2-a9b1-d6c69c683ffc" /> |
| **Resumen de la entrevista** | Arnold Alfredo, de 26 años, es propietario de una empresa de transporte de gas en Villa El Salvador. Actualmente cuentan con medidas básicas de seguridad como revisión de unidades antes de los viajes, uso de extintores, chalecos y cascos, además de charlas internas de prevención. La empresa solo utiliza GPS para el seguimiento de vehículos, pero el entrevistado considera que sensores de fuga de gas y de temperatura serían los más adecuados para su rubro. Expresó interés en implementar soluciones IoT que permitan mejorar la seguridad en tiempo real, reaccionar más rápido ante emergencias y generar confianza en los clientes. Entre los beneficios esperados mencionó mayor control de la carga, reducción de riesgos y prevención de pérdidas, aunque también manifestó preocupaciones respecto al costo de implementación y la adaptación del personal. Finalmente, indicó que prefiere recibir alertas en el celular o mediante aplicaciones móviles, y considera que una solución IoT confiable, sencilla y de bajo costo le daría una ventaja competitiva en el sector. |


### Segunda Entrevista

| Campo       | Detalle |
|-------------|---------|
| **Nombre**  | Sebastian Lobato |
| **Edad**    | 20 |
| **Inicio**  | 4:32 |
| **Fin**     | 10:06 |
| **Duración**| 5:34 |
| **Link**    | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218451_upc_edu_pe/Ef69MXwMrZZGqLdEIjw5134BLTEMz3ZmWUUBnmpt836yhg?e=VCLD5t&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Imagen**  | <img width="1883" height="639" alt="image" src="https://github.com/user-attachments/assets/de90f951-f7e1-4297-8a5d-9b28f74b653d" /> |
| **Resumen de la entrevista** | Sebastian, de 20 años, explicó que actualmente en su empresa se aplican medidas de seguridad como el uso de válvulas de seguridad, extintores, rutas planificadas y revisiones periódicas de los vehículos, además de protocolos estrictos para prevenir incidentes. Relató que en una ocasión, ante una fuga, el equipo detuvo las operaciones de inmediato y notificó a la empresa y a personal especializado para resolver la situación, evidenciando el cumplimiento riguroso de los procedimientos establecidos. Entre las dificultades, mencionó la presión por cumplir con los tiempos de entrega, lo que en ocasiones puede entrar en tensión con las medidas de seguridad. Actualmente, cuentan únicamente con GPS para el seguimiento de las unidades, pero no con herramientas que informen sobre el estado del gas o de las condiciones internas. Por ello, considera necesario incorporar una solución tecnológica que incremente la seguridad, permita un mejor monitoreo y brinde mayor tranquilidad tanto a los trabajadores como a la empresa. |


### Tercera Entrevista

| Campo       | Detalle |
|-------------|---------|
| **Nombre**  | Diego Sebastian Valdivia Colque |
| **Edad**    | 21 |
| **Inicio**  | 10:06 |
| **Fin**     | 15:56 |
| **Duración**| 5:50 |
| **Link**    | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218451_upc_edu_pe/Ef69MXwMrZZGqLdEIjw5134BLTEMz3ZmWUUBnmpt836yhg?e=VCLD5t&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Imagen**  | ![entrevista_3](https://github.com/user-attachments/assets/8785f422-1467-4562-9a4d-8f26b943154a) |
| **Resumen de la entrevista** | Diego, de 21 años y residente en Bellavista, comentó que su empresa aplica el Reglamento Nacional de Transporte Terrestre de Materiales y Residuos Peligrosos, utilizando vehículos certificados, señalización adecuada, bitácoras de control, equipos de protección personal y kits de emergencia en cada unidad. La capacitación del personal se realiza mediante convenios con SENCICO, incluyendo simulacros de derrames, incendios y evacuación, así como charlas de primeros auxilios y manejo de sustancias químicas. Además, emplean tecnologías como GPS con geocercas, sensores de temperatura y presión, cámaras de cabina y sistemas de trazabilidad en tiempo real. Diego destacó que la implementación de soluciones IoT permitiría anticipar incidentes, optimizar operaciones y generar ventajas competitivas, aunque reconoció desafíos como el costo inicial, la capacitación del personal y la seguridad de los datos. |

### 2.2.3. Análisis de entrevistas

Las entrevistas realizadas tanto a conductores como a representantes de empresas que transportan productos peligrosos han permitido identificar patrones comunes que subrayan la necesidad de fortalecer la seguridad, incorporar monitoreo en tiempo real y adoptar nuevas tecnologías, especialmente aquellas basadas en IoT. A continuación, se detallan los principales hallazgos:

- Actualmente, muchas empresas dependen principalmente de la experiencia del conductor y de acciones reactivas como el uso de extintores o la comunicación básica para manejar emergencias. Esto evidencia una oportunidad para reforzar los protocolos de seguridad a través de capacitaciones más completas y el uso de herramientas tecnológicas que permitan anticiparse a posibles incidentes.

- El uso de dispositivos tecnológicos como sensores de gas, temperatura y presión aún es escaso, lo cual representa una limitación significativa. Tanto las empresas como los transportistas podrían beneficiarse ampliamente de implementar soluciones IoT que proporcionen monitoreo constante y en tiempo real del estado de la carga, aumentando así los niveles de seguridad.

- Existe un marcado interés en adoptar tecnologías IoT, ya que se perciben como medios eficaces para mejorar la seguridad, hacer más eficientes los procesos logísticos y cumplir con normativas vigentes. Esta disposición abre la puerta a la introducción de soluciones que cubran estas necesidades específicas.

- No obstante, pese al interés, existen ciertos obstáculos que dificultan su adopción. Entre ellos destacan los costos asociados a la inversión inicial y los posibles problemas de conectividad en zonas remotas. Por ello, es esencial que las empresas proveedoras de estas tecnologías garanticen soluciones confiables, accesibles y fáciles de operar.

- La necesidad de recibir alertas en tiempo real es una demanda clave. Cualquier sistema basado en IoT debe incluir notificaciones precisas y oportunas, que no interfieran con las actividades del conductor, pero que faciliten la toma de decisiones inmediatas en caso de riesgo.

- La integración de tecnologías emergentes representa una oportunidad para que las empresas de transporte se posicionen como referentes en seguridad dentro del sector. Aquellas que adopten estas innovaciones de forma anticipada no solo optimizarán sus procesos, sino que también podrán atraer más clientes al ofrecer servicios más seguros y confiables.

![image](https://github.com/user-attachments/assets/59ec18cf-bdea-47e8-8ca3-e3801edbbf28)

En resumen, los testimonios obtenidos reflejan una necesidad concreta de actualizar los sistemas de seguridad actuales y apostar por soluciones tecnológicas como el IoT. Aunque el interés es alto, es fundamental abordar las preocupaciones sobre costos y conectividad. Las empresas que logren implementar estas tecnologías de forma efectiva obtendrán una ventaja competitiva y podrán mejorar considerablemente la seguridad en sus operaciones.

## 2.3. Needfinding
En esta sección, se buscarán las necesidades implícitas y explícitas de las personas o segmentos para poder diseñar y adaptar el producto solución de manera apropiada.

### 2.3.1. User Personas

Se realiza las User Persona, personaje ficticio para reflejar al cliente ideal, estos user persona son creados en base a la investigación de capitulos previos para identificar a los diferentes tipos de clientes que podrían usar el producto solución. Se utilizó la herramienta UXPressia.

**Transportistas de combustibles peligrosos**

![361573775-97d571cf-7016-4d0d-9b38-ed6343c98e6f](https://github.com/user-attachments/assets/d045a6b1-433a-47e3-ab11-df173cd3438d)


**Empresas de transporte de productos peligrosos**

![Carlo Galavis](https://github.com/user-attachments/assets/fb10e06a-0889-4d9b-a8d0-d005574d1eb8)

### 2.3.2. User Task Matrix

A continuación, se muestra el User Task Matrix para los siguientes segmentos objetivo:


<table>
  <tr>
    <th></th>
    <td colspan="2">TRANSPORTISTAS</td>
    <td colspan="2">EMPRESAS</td>
  </tr>
  <tr>
    <td>TASK</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
  </tr>
  <tr>
    <td>Registrar los envíos de productos combustibles</td>
    <td>Low </td>
    <td>Low</td>
    <td>High</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Coordinar con los demás transportistas detalles acerca del cargamento</td>
    <td>Often</td>
    <td>High</td>
    <td>Rare</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>Trazar la ruta que se tiene que recorrer y sus peligros </td>
    <td>Always</td>
    <td>Medium</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Evaluar calidad de los vehiculos de transporte</td>
    <td>Always</td>
    <td>High</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Evaluar demanda y tendencias</td>
    <td>Often</td>
    <td>High</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Revisar el estado del cargamento</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Inspeccionar la condición del cargamento previo al transporte</td>
    <td>Often</td>
    <td>Low</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Monitorear la velocidad del transportista</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
</table>

**Tareas con Mayor Frecuencia e Importancia:**
- Frecuencia:

> Respecto al segmento objetivo de transportistas, las tareas que se realizan con mayor 
> frecuencia incluyen trazar la ruta que se tiene que recorrer y sus peligros, coordinar con los demás transportistas detalles acerca del cargamento, 
> y evaluar la calidad de los vehículos de transporte. Por otro lado, para el segmento de empresas de transporte de productos peligrosos, las tareas más
> frecuentes son evaluar la calidad de los vehículos de transporte, revisar el estado del cargamento, y trazar la ruta y sus peligros.

- Importancia:

> Para el segmento de empresas de transporte, las tareas más importantes incluyen registrar los 
> envíos de productos combustibles, evaluar la calidad de los vehículos de transporte, y monitorear la velocidad del transportista. 
> En el caso de los transportistas, las tareas de mayor relevancia son coordinar detalles acerca del cargamento, evaluar la 
> calidad de los vehículos de transporte, y trazar la ruta que se tiene que recorrer.

Principales Diferencias y Coincidencias:

Una de las principales diferencias entre los dos segmentos objetivo es que las empresas de transporte tienen una mayor responsabilidad en la supervisión y monitoreo del cargamento, como lo demuestra la alta importancia y frecuencia asignada a tareas como revisar el estado del cargamento y monitorear la velocidad del transportista. Por otro lado, los transportistas se centran más en la planificación de rutas y la coordinación con otros transportistas, lo que refleja su rol más operativo y menos gerencial.

Tanto los transportistas como las empresas coinciden en la alta importancia de la evaluación de la calidad de los vehículos de transporte y la necesidad de trazar rutas seguras y eficientes. Ambas audiencias reconocen la importancia crítica de estas tareas para garantizar la seguridad y la eficiencia en el transporte de productos peligrosos.

### 2.3.3. Journey Mapping

<img src="https://i.imgur.com/b1FuQz1.png" style="width:80%">
<img src="https://i.imgur.com/SEZ5r2H.png" style="width:80%">

### 2.3.4. Empathy Mapping

**Transportistas de combustibles peligrosos**

![Empathy map](https://github.com/user-attachments/assets/ed0e74aa-de6d-4e8f-9ca6-e235f146f6c7)

**Empresas de transporte de productos peligrosos**

![Empathy map (1)](https://github.com/user-attachments/assets/ef04d9c0-99cf-47e2-8c70-5f579319d6f7)

### 2.3.5. As-is Scenario Mapping

![image](https://github.com/user-attachments/assets/753224a7-ec79-412f-9fe9-7a5cf13b7c0b)
![image](https://github.com/user-attachments/assets/233c4c8e-0a59-472f-863e-d9023194cdc5)

## 2.4. Ubiquitous Language

Términos y Definiciones

**Dashboard (Panel de Control)**
Un panel de control es un componente de la interfaz de usuario que proporciona una visión general del estado del transporte, incluyendo datos en tiempo real de sensores de gas y temperatura. Permite a los operadores monitorear alertas de seguridad y la ubicación de la carga.

**Incident List (Listado de Incidentes)**
Una pantalla que presenta una lista de todos los incidentes reportados durante los servicios de transporte. Incluye detalles como niveles de gas peligrosos detectados, cambios de temperatura anormales y acciones correctivas tomadas.

**Incident Notification (Notificación de Incidentes)**
El proceso por el cual los transportistas y empresarios son informados de forma automática y en tiempo real sobre fugas de gas, temperaturas fuera del rango seguro u otros problemas detectados por los sensores IoT instalados en los vehículos de transporte.

**Monitoring Package (Monitoreo de Carga)**
Seguimiento en tiempo real del estado de la carga, utilizando sensores IoT para registrar niveles de gas, temperatura y otros parámetros críticos para evitar accidentes durante el transporte de productos peligrosos.

**Transport Service (Servicio de Transporte)**
El conjunto de operaciones logísticas, incluyendo el monitoreo en tiempo real y la detección temprana de riesgos, destinados a transportar bienes peligrosos como gasolina o gas desde un punto de origen hasta su destino final.

**Transporters (Transportistas)**
Personas o empresas responsables de supervisar los vehículos equipados con sensores IoT para garantizar un transporte seguro de productos peligrosos.

**Business Owner (Empresario)**
Persona o entidad encargada de gestionar la logística y la coordinación del transporte de bienes peligrosos, supervisando las métricas de seguridad proporcionadas por la solución IoT.

**Incident Report (Reporte de Incidente)**
Documento generado automáticamente que detalla un incidente detectado por los sensores IoT, como fugas de gas o incrementos bruscos de temperatura. Incluye la causa, impacto y medidas correctivas tomadas.

**Sensor Alerts (Alertas de Sensores)**
Notificaciones automáticas enviadas a través de la plataforma cuando los sensores IoT detectan condiciones peligrosas como niveles altos de gas o temperaturas fuera del rango seguro.

**Transporter Rating (Calificación de Transportistas)**
Evaluación de la calidad del servicio ofrecido por los transportistas basada en su capacidad de respuesta a alertas de seguridad y su cumplimiento con los estándares de manejo de bienes peligrosos.

**Transporter Registration (Registro de Transportistas)**
Proceso mediante el cual un transportista se registra en la plataforma para vincular su flota de vehículos con sensores IoT y ofrecer servicios de transporte seguro.

**Login (Iniciar Sesión)**
El proceso mediante el cual un usuario accede a su cuenta en la plataforma para monitorear, gestionar o responder a alertas relacionadas con el transporte de bienes peligrosos.

**Authentication Policy (Política de Autenticación)**
Conjunto de reglas que garantizan que solo usuarios autorizados, como transportistas y empresarios, puedan acceder a la plataforma y monitorear los datos IoT.

**Transport Route (Ruta de Transporte)**
El trayecto definido que debe seguir el transportista, monitoreado en tiempo real para garantizar el cumplimiento de condiciones seguras a lo largo del recorrido.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**To Be Scenario Mapping: Transportista**
<img width="1693" height="auto" alt="image" src="https://i.imgur.com/Suxeyok.png" />


**To Be Scenario Mapping: Empresas de transporte**
<img width="1693" height="652" alt="image" src="https://github.com/user-attachments/assets/14d02699-4d2d-45d1-949a-e3b9a303ac64" />



## 3.2. User Stories

| **Epic ID** | **Epic**                                             | **Descripción**                                                                           |
|-------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------|
| EP01        | Gestión de Transportistas y Documentación de Cumplimiento | Gestión y mantenimiento de perfiles de transportistas, verificación de permisos, y certificaciones. |
| EP02        | Gestión de Solicitudes de Transporte                 | Publicación y administración de solicitudes de transporte por parte de las empresas.       |
| EP03        | Seguimiento en Tiempo Real            | Monitoreo en tiempo real del transporte de productos peligrosos.|
| EP04        | Acciones de prevención            | Acciones a realizar como respuesta ante posibles incidentes que puedan ocurrir con la carga.|

---

| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** |
|---------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** 
| US01                | Monitoreo del Vehículo                             | Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.                                                         | **Escenario 1: Realizar monitoreo**. Dado que el transportista necesite asegurar el estado del vehículo, cuando inicie la función de monitoreo, entonces el sistema presentará un reporte con el estado del vehículo. **Escenario 2: Error en el monitoreo**. Dado que el sistema presenta un error durante la verificación del estado del vehículo, cuando el transportista intente iniciar la función de monitoreo, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo realizar el monitoreo y sugerir intentar nuevamente o contactar soporte. | EP03                          |
| US02                | Notificaciones de Mantenimiento Preventivo         | Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.                                                                  | **Escenario 1: Notificación de mantenimiento**. Dado que el vehículo se acerque a la fecha de mantenimiento, cuando el sistema detecte la proximidad de esta fecha, entonces se enviará una notificación al transportista. **Escenario 2: Error en la notificación**. Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el transportista revise el sistema, entonces este deberá mostrar un mensaje indicando que hubo un problema y permitir al transportista revisar manualmente las fechas de mantenimiento programadas.         | EP04                          |
| US03               | Reporte de Estado del Vehículo                     | Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.                                                                                    | **Escenario 1: Generar reporte**. Dado que el transportista complete la revisión del vehículo, cuando se complete la revisión, entonces el sistema permitirá generar un reporte que puede ser enviado al supervisor. **Escenario 2: Error al generar reporte**. Dado que el sistema falle en generar el reporte, cuando el transportista intente crear el reporte después de la revisión, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo generar el reporte y sugerir reintentar o guardar los datos manualmente. | EP03                          |
| US04                | Seguimiento en Tiempo Real de los Transportes Activos| Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.          | **Escenario 1: Seguimiento del Transporte en Tiempo Real**. Dado que hay un transporte activo en curso, cuando la empresa accede a la sección de seguimiento de transportes, entonces el sistema muestra la ubicación actual, la velocidad y el estado del transporte en tiempo real en un mapa. **Escenario 2: Error en el seguimiento en tiempo real**. Dado que el sistema falle en actualizar la ubicación del transporte, cuando la empresa intente realizar el seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje indicando que no se puede obtener la ubicación y permitir reintentar o contactar al transportista directamente. | EP03                          |
| US05                | Recibir Notificaciones de Incidentes en Tiempo Real | Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).                     | **Escenario 1: Recepción de Notificaciones de Incidentes**. Dado que un transporte está en curso, cuando ocurre un incidente o evento inesperado, entonces el sistema envía una notificación en tiempo real a la empresa con detalles del incidente y posibles acciones a tomar. **Escenario 2: Error al recibir notificación de incidente**. Dado que el sistema falle en enviar la notificación de incidente, cuando la empresa espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje indicando que no se pudo enviar la notificación y sugerir verificar el estado del transporte manualmente o contactar al transportista. | EP04                          |
| US06                | Registro de Transportista de Combustibles Peligrosos| Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.          | **Escenario 1: Validación del Registro de Transportista**. Dado que el transportista accede a la página de registro, cuando completa todos los campos requeridos y adjunta los documentos de certificación, entonces el sistema valida la información y confirma el registro si todos los datos son correctos. **Escenario 2: Error al registrar transportista**. Dado que el sistema falle en procesar el registro, cuando el transportista intente registrarse, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo completar el registro y sugerir reintentar o contactar soporte técnico.                   | EP01                          |
| US07                | Notificación de Nuevas Solicitudes de Transporte    | Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.                                                                                                           | **Escenario 1: Recepción de Notificación de Nueva Solicitud**. Dado que una empresa de transporte publica una nueva solicitud de transporte de combustibles, cuando el transportista tiene los permisos adecuados y disponibilidad, entonces el transportista recibe una notificación y puede optar por aceptar o rechazar la solicitud. **Escenario 2: Error al recibir notificación de nueva solicitud**. Dado que el sistema falle en enviar la notificación, cuando el transportista espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje de error y sugerir revisar manualmente las solicitudes publicadas o contactar a la empresa de transporte. | EP02                          |
| US08                | Actualización de Estado del Transporte              | Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).                                                                     | **Escenario 1: Actualización del Estado del Transporte en Curso**. Dado que el transportista ha aceptado un trabajo y está en ruta, cuando hay un cambio en el estado del transporte, entonces el transportista puede actualizar el estado y la empresa recibe una notificación con el estado actualizado. **Escenario 2: Error al actualizar estado del transporte**. Dado que el sistema falle en procesar la actualización del estado del transporte, cuando el transportista intente actualizar el estado, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo actualizar el estado y sugerir reintentar o contactar a la empresa directamente. | EP02                          |
| US09                | Publicación de Solicitudes de Transporte de Productos Peligrosos | Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.                              | **Escenario 1: Publicación de Solicitud de Transporte**. Dado que la empresa accede a la sección de solicitud de transporte, cuando completa el formulario de solicitud con toda la información requerida, entonces la solicitud se publica y los transportistas calificados reciben notificaciones. **Escenario 2: Error al publicar solicitud de transporte**. Dado que el sistema falle en procesar la solicitud de transporte, cuando la empresa intente publicar la solicitud, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo publicar la solicitud y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US10                | Visualización de Transportistas Disponibles         | Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.                   | **Escenario 1: Visualización de Transportistas Calificados**. Dado que la empresa ha publicado una solicitud de transporte, cuando hay transportistas calificados disponibles, entonces el sistema muestra una lista de transportistas con sus detalles de calificación, precio, y disponibilidad. **Escenario 2: Error al visualizar transportistas disponibles**. Dado que el sistema falle en cargar la lista de transportistas disponibles, cuando la empresa intente visualizar transportistas calificados, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar la lista y sugerir reintentar o contactar soporte técnico. | EP02                 |
| US11                | Landing Page responsive       | Como visitante, deseo visitar la landing page desde cualquier dispositivo.                                                      | **Escenario 01**: Dado que el visitante necesita una aplicación web o móvil para mejorar su servicio, cuando busque en el navegador "Monitorear productos peligrosos", entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web o móvil. **Escenario 02**: Dado que el visitante desea una aplicación web o móvil con características puntuales de seguridad de transporte de productos peligrosos, cuando navegue por la landing page y se encuentre en la sección de beneficios y funcionalidades, entonces visualizará la funcionalidad que se desea y se decide en usar la aplicación web o móvil.      | EP01                          |
| US12                | Visualización de características de la aplicación web o móvil en Landing Page | Como visitante, deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo.                                  | **Escenario 01**: Dado que el visitante accede a la landing page desde su celular, cuando visite la landing page desde el navegador de su celular, entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil. **Escenario 02**: Dado que el visitante recomienda la landing page mediante un dispositivo móvil, cuando el otro visitante recomendado acceda a la landing page desde otro dispositivo móvil con resolución diferente, entonces la landing page se mostrará completamente visible y ordenada dado que es responsive.            | EP01                          |
| US13                | Botón Call to Action       | Como visitante, deseo ir a la aplicación web o móvil desde un solo botón desde la landing page.                                    | **Escenario 01**: Dado que el visitante desea usar la aplicación web o móvil, cuando esté en la sección donde se encuentre el botón call to action y lo use, entonces será dirigido a la aplicación web o móvil. **Escenario 02**: Dado que el visitante quedó satisfecho con la información brindada en la landing page, cuando desee empezar a usar la aplicación web o móvil, entonces puede acceder a ella de forma rápida mediante el botón call to action            | EP01                          |
| **TS-01** | Implementación de Monitoreo del Vehículo           | Como desarrollador, quiero implementar la funcionalidad de monitoreo del vehículo para que los transportistas puedan verificar el estado del vehículo antes de iniciar un viaje. | **Background:** Implementar el endpoint `GET /api/vehicle-monitoring/{vehicleId}` para obtener el estado actual del vehículo.<br><br>**Scenario 01: Obtener estado del vehículo**<br>Dado que el transportista quiere verificar el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo existe en la base de datos, entonces el sistema devuelve un `response` con `status 200` y los detalles del estado del vehículo en el `Response Body`.<br><br>**Scenario 02: Error al obtener estado del vehículo**<br>Dado que el sistema falla en obtener el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo no existe o hay un problema en el sistema, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP03**                   |
| **TS-02** | Implementación de Notificaciones de Mantenimiento Preventivo | Como desarrollador, quiero implementar el sistema de notificaciones de mantenimiento preventivo para alertar a los transportistas cuando se acerque la fecha de mantenimiento del vehículo. | **Background:** Configurar un sistema de notificaciones automáticas que envíe alertas a través de `POST /api/notifications/maintenance`.<br><br>**Scenario 01: Envío de notificación de mantenimiento**<br>Dado que la fecha de mantenimiento del vehículo se acerca, cuando el sistema detecta que faltan X días para la fecha de mantenimiento, entonces se envía una notificación al transportista y se devuelve un `response` con `status 200` confirmando el envío exitoso.<br><br>**Scenario 02: Error en el envío de notificación de mantenimiento**<br>Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el sistema intenta enviar la notificación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-03** | Implementación de Verificación de Permisos de Transportistas | Como desarrollador, quiero implementar la funcionalidad para verificar los permisos y certificaciones de los transportistas, para que las empresas puedan tomar decisiones informadas al contratarlos. | **Background:** Crear un endpoint `GET /api/transporters/{transporterId}/certifications` que devuelva los permisos y certificaciones de un transportista específico.<br><br>**Scenario 01: Obtener permisos y certificaciones del transportista**<br>Dado que la empresa necesita verificar los permisos de un transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, y el transportista tiene permisos registrados, entonces el sistema devuelve un `response` con `status 200` y los detalles de las certificaciones en el `Response Body`.<br><br>**Scenario 02: Error al obtener permisos y certificaciones**<br>Dado que el sistema falla en obtener los permisos del transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP02**                   |
| **TS-04** | Implementación de Monitoreo en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad de monitoreo en tiempo real utilizando la Edge API, para que los dispositivos IoT puedan enviar datos de ubicación, velocidad, estado y horas de conducción directamente desde el transporte. | **Background:** Configurar un endpoint en la Edge API `POST /edge/vehicle-monitoring` que reciba datos en tiempo real desde dispositivos IoT instalados en los vehículos.<br><br>**Scenario 01: Recepción de datos en tiempo real**<br>Dado que el vehículo está en movimiento, cuando el dispositivo IoT envía datos de ubicación, velocidad, estado y horas de conducción al endpoint `/edge/vehicle-monitoring`, entonces la Edge API procesa y almacena los datos en la base de datos central, devolviendo un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de datos**<br>Dado que el sistema IoT falla en enviar los datos al Edge API, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/vehicle-monitoring` y ocurre un error de conexión o datos corruptos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-05** | Implementación de Notificaciones de Incidentes en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT envíen notificaciones de incidentes en tiempo real a través de la Edge API, para que la empresa pueda reaccionar rápidamente a situaciones críticas. | **Background:** Configurar un endpoint en la Edge API `POST /edge/incident-notifications` que reciba alertas de incidentes desde los sensores IoT del vehículo.<br><br>**Scenario 01: Recepción de notificación de incidente**<br>Dado que ocurre un incidente durante el transporte, cuando el dispositivo IoT detecta un evento crítico (accidente, desviación, etc.) y envía datos al endpoint `/edge/incident-notifications`, entonces la Edge API procesa la alerta, notifica a la empresa, y devuelve un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de notificación de incidente**<br>Dado que el sistema IoT falla en enviar la notificación de incidente, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/incident-notifications` y ocurre un error de comunicación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-06** | Implementación de Actualización de Estado del Vehículo desde Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT en el vehículo actualicen el estado del transporte en tiempo real a través de la Edge API, para que la empresa siempre tenga información precisa sobre el progreso del viaje. | **Background:** Configurar un endpoint en la Edge API `PUT /edge/vehicle-status/{vehicleId}` que permita a los dispositivos IoT actualizar el estado del vehículo (en camino, retraso, entregado, etc.).<br><br>**Scenario 01: Actualización de estado exitosa**<br>Dado que el vehículo cambia su estado (por ejemplo, llega al destino), cuando el dispositivo IoT envía una actualización de estado al endpoint `/edge/vehicle-status/{vehicleId}`, entonces la Edge API actualiza la información en el sistema central y devuelve un `response` con `status 200` para confirmar la actualización exitosa.<br><br>**Scenario 02: Error en la actualización del estado del vehículo**<br>Dado que el sistema IoT falla en actualizar el estado del vehículo, cuando el dispositivo IoT intenta enviar una actualización al endpoint `/edge/vehicle-status/{vehicleId}` y ocurre un error de transmisión o de datos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP02**                   |


## 3.3. Impact Mapping

**Transportistas de combustibles peligrosos**

![Impact map Transportista](https://i.imgur.com/isPyVui.png)

**Empresas de transporte de productos peligrosos**

![Impact map Empresa de tansportes](https://i.imgur.com/5o4y4SJ.png)



## 3.4. Product Backlog

A continuación, se mostrará la herramienta Product Backlog, lista de trabajo ordenado por la prioridad para el equipo de desarrollo de GreatMinds.

|**#Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :-: | :-: | :-: | :-: | :-: |
|01|US12|Visualización de características de la aplicación web o móvil web en Landing Page|Como visitante deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo|5|
|02|US11|Landing Page responsive| Como visitante deseo visitar la landing page desde cualquier dispositivo.|5|
|03|US13|Botón Call to Action|Como visitante deseo ir a la aplicación web o móvil web desde un solo botón desde la landing page |5|
|04|US09|Publicación de Solicitudes de Transporte de Productos Peligrosos|Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.|5|
|05|US07|Notificación de Nuevas Solicitudes de Transporte|Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.|8|
|06|US01|Monitoreo del Vehículo|Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.|8|
|08|US10|Visualización de Transportistas Disponibles|Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.|5|
|09|US08|Actualización de Estado del Transporte|Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).|8|
|10|US06|Registro de Transportista de Combustibles Peligrosos|Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, para poder ser considerado en futuros trabajos de transporte.|8|
|12|US05|Recibir Notificaciones de Incidentes en Tiempo Real|Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).|5|
|14|US04|Seguimiento en Tiempo Real de los Transportes Activos|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.|2|
|17|US03|Reporte de Estado de la carga|Como transportista, quiero generar y enviar un reporte sobre el estado de la carga, para mantener un registro actualizado.|3|
|18|US02|Notificaciones de Mantenimiento Preventivo|Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.|3|




# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design
### 4.1.1. Design Purpose.

El propósito del diseño estratégico de SecurOn es ofrecer una solución digital integral que aborde los riesgos asociados al transporte de materiales peligrosos, garantizando la seguridad de los conductores, la protección de las comunidades y el cumplimiento normativo de las empresas. El diseño busca responder directamente a la problemática identificada: la detección tardía de anomalías, la fragmentación tecnológica en los procesos de monitoreo y las crecientes exigencias regulatorias en el sector transporte.

Para cumplir con este propósito, se plantea una arquitectura orientada a la integración de sensores IoT y servicios en la nube, que permita monitorear en tiempo real variables críticas del transporte —como presión, temperatura, ubicación y estado del vehículo— y activar protocolos de prevención ante posibles incidentes. Esta estrategia tecnológica asegura una supervisión centralizada, resiliente y adaptable a distintos escenarios operativos.

La orientación al usuario es un eje fundamental. Para los transportistas, el diseño contempla funcionalidades de registro validado, inspección previa del vehículo, generación de reportes de estado y recepción de notificaciones de mantenimiento preventivo. Para las empresas de transporte, se priorizan herramientas de gestión de solicitudes, verificación de permisos de conductores, seguimiento en tiempo real de los viajes activos y alertas inmediatas en caso de incidentes. Así, el sistema no solo cubre las necesidades de operatividad y seguridad, sino que también contribuye a optimizar la eficiencia en la coordinación logística.

Asimismo, el enfoque estratégico del diseño posiciona a SecurOn como una ventaja competitiva frente a actores tradicionales del sector, al ofrecer un modelo escalable basado en servicios digitales modulares y un esquema de despliegue flexible mediante Edge API. Esta decisión facilita la incorporación de nuevas funcionalidades sin afectar la estabilidad del sistema, permitiendo a la solución evolucionar en paralelo con los cambios normativos y las demandas del mercado.

En suma, el propósito del diseño de SecurOn es consolidar una plataforma tecnológica que no solo garantice la continuidad y seguridad del transporte de productos peligrosos, sino que también potencie la confianza de las empresas en sus operaciones, minimice riesgos legales y reputacionales, y ofrezca a los transportistas una herramienta práctica, moderna y centrada en la prevención.

### 4.1.2. Attribute-Driven Design Inputs. 

### 4.1.2.1. Primary Functionality (Primary User Stories)

En esta sección se presentan las funcionalidades primarias que tienen un mayor impacto en las decisiones de diseño arquitectónico de **SecurOn**.  
Se seleccionaron únicamente aquellas *Epics* y *User Stories* que son críticas para garantizar el monitoreo en tiempo real mediante IoT y Edge API, la validación de transportistas y permisos, la publicación de solicitudes, así como el envío de notificaciones críticas en situaciones de riesgo.  
Estas funcionalidades representan los **drivers funcionales principales** que orientan la definición de la arquitectura del sistema.

| Epic / User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------------|--------|-------------|--------------------------|---------------------------|
| EP01 / US06 | Registro de Transportista de Combustibles Peligrosos | Como transportista, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte. | Validación de datos y documentos; error mostrado si la información no es procesada correctamente. | EP01 |
| EP02 / US09 | Publicación de Solicitudes de Transporte de Productos Peligrosos | Como empresa, quiero publicar solicitudes de transporte detallando tipo de producto, cantidad, origen, destino y requisitos, para gestionar la logística. | La solicitud se publica correctamente y transportistas calificados reciben notificaciones; se muestran errores si la publicación falla. | EP02 |
| EP03 / US04 | Seguimiento en Tiempo Real de los Transportes Activos | Como empresa, quiero realizar seguimiento en tiempo real de los transportes activos para garantizar seguridad y puntualidad. | El sistema muestra ubicación, velocidad y estado en tiempo real; si falla, se debe notificar error y opciones de contacto manual. | EP03 |
| EP03 / TS-04 | Implementación de Monitoreo en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar monitoreo en tiempo real mediante Edge API para recibir datos IoT (ubicación, velocidad, estado). | Recepción y procesamiento correcto de datos en tiempo real; manejo de errores de conexión o datos corruptos. | EP03 |
| EP04 / US05 | Notificaciones de Incidentes en Tiempo Real | Como empresa, quiero recibir notificaciones en tiempo real sobre incidentes (accidente, retraso, desviación) durante el transporte. | El sistema envía notificación en tiempo real con detalles; si falla, se muestra error y opciones alternativas de contacto. | EP04 |
| EP04 / TS-05 | Implementación de Notificaciones de Incidentes en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar envío de alertas de incidentes desde sensores IoT a la Edge API, para notificar a la empresa de forma inmediata. | Procesamiento correcto de notificaciones de incidente; manejo de fallas en la comunicación. | EP04 |

#### 4.1.2.2. Quality Attribute Scenarios

En esta sección se especifican los **atributos de calidad más relevantes** para el diseño de la solución **SecurOn**.  
Los escenarios planteados responden a necesidades críticas del sistema, como la **disponibilidad en tiempo real**, la **seguridad de la información sensible**, la **escalabilidad ante picos de demanda**, la **fiabilidad de las notificaciones de incidentes** y la **usabilidad para actores no técnicos**.  
Estos atributos se convierten en **drivers arquitectónicos clave**, orientando la selección de tecnologías, patrones y mecanismos de integración.

| Atributo | Fuente | Estímulo | Artefacto | Entorno | Respuesta | Medida |
|----------|--------|----------|-----------|---------|-----------|--------|
| Disponibilidad (High Availability) | Empresa usuaria | Un administrador intenta acceder al sistema durante un pico de solicitudes o en mantenimiento planificado | Plataforma SecurOn (Frontend + Mobile + Backend) | Horas pico, múltiples solicitudes concurrentes | El sistema garantiza acceso continuo mediante balanceo de carga y redundancia | 99.9% de uptime mensual |
| Seguridad (Security) | Actor malicioso externo | Intento de acceso no autorizado a datos de transportistas, rutas o solicitudes | API Gateway + Base de datos | Operación normal | El sistema rechaza el acceso y registra el intento en logs de auditoría | 100% de intentos bloqueados, detección en < 2 seg |
| Rendimiento / Escalabilidad (Performance / Scalability) | Empresas publicando solicitudes | Se registran más de 100 solicitudes simultáneamente | Servicio de publicación de solicitudes + base de datos | Pico de uso inesperado | El sistema procesa las solicitudes sin pérdida de datos ni caídas | Tiempo de respuesta < 2 seg por solicitud |
| Fiabilidad de Comunicación (Reliability) | Sensores IoT en transporte | Se produce un incidente (accidente, desviación) y se envía señal a la Edge API | Servicio de Monitoreo en Tiempo Real + Notificaciones | Transporte en curso bajo condiciones de riesgo | El sistema recibe y reenvía la alerta a la empresa de manera inmediata | Entrega de notificación en < 5 seg, tasa de entrega ≥ 99% |
| Usabilidad (Usability) | Transportista no técnico | Transportista intenta registrarse en la plataforma y subir sus permisos | Módulo de Registro de Transportistas | Operación normal | El sistema guía con formularios validados y mensajes claros de error | Registro completado en < 3 min con ≤ 1 intento fallido |

#### 4.1.2.3. Constraints

En esta sección se definen las **restricciones técnicas no negociables** que guían la implementación de la solución **SecurOn**.  
Estas restricciones provienen de las necesidades del negocio, la criticidad del dominio (transporte de productos peligrosos) y las condiciones técnicas establecidas por el cliente.  
Cada constraint se expresa como una *Technical Story* con sus respectivos criterios de aceptación.

| Technical Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|--------------------|--------|-------------|--------------------------|---------------------------|
| CON-001 | Arquitectura Monolítica Escalable | El sistema debe ser implementado como una aplicación monolítica centralizada para simplificar despliegue y mantenimiento inicial. | La solución debe desplegarse como un único artefacto y soportar crecimiento en funcionalidades sin comprometer estabilidad. | EP01, EP02 |
| CON-002 | Autenticación y Autorización Segura | El sistema debe validar credenciales de transportistas y empresas mediante autenticación segura y control de accesos. | Acceso a funcionalidades restringidas solo a usuarios autenticados; autorización basada en roles. | EP01 |
| CON-003 | Procesamiento en Tiempo Real vía Edge API | La plataforma debe recibir y procesar datos de sensores IoT a través de la Edge API con baja latencia. | El sistema procesa eventos en tiempo real con latencia máxima de 5 segundos en condiciones normales. | EP03, EP04 |
| CON-004 | Cifrado de Datos Sensibles | Toda la información sensible (permisos, certificaciones, solicitudes) debe estar cifrada en tránsito y en reposo. | Cifrado en tránsito con TLS 1.2+ y cifrado en reposo con AES-256. | EP01, EP02 |
| CON-005 | Alta Disponibilidad | La aplicación debe estar disponible para empresas y transportistas en todo momento, incluso en horarios de alta demanda. | Disponibilidad ≥ 99.5% mensual. | EP02, EP03 |
| CON-006 | Compatibilidad Multidispositivo | El sistema debe ser accesible desde navegadores en computadoras, tablets y dispositivos móviles. | La interfaz se adapta automáticamente a diferentes resoluciones y tamaños de pantalla. | EP01, EP02 |
| CON-007 | Cumplimiento Normativo | El sistema debe garantizar que las solicitudes de transporte y permisos de transportistas cumplan con la normativa vigente de transporte de sustancias peligrosas. | El sistema valida documentación obligatoria antes de publicar solicitudes o aceptar transportistas. | EP01, EP02 |

### 4.1.3. Architectural Drivers Backlog

El **Architectural Drivers Backlog** representa el conjunto de decisiones clave que guían el diseño de la solución.  
Este backlog fue construido a partir de la priorización de los **Functional Drivers**, los **Quality Attribute Drivers** y los **Constraints** identificados en el proceso de *Quality Attribute Workshop*.  
Los elementos se organizaron considerando dos dimensiones:  
- **Importancia para Stakeholders**: el grado de criticidad del driver para el negocio y los usuarios finales.  
- **Impacto en Architecture Technical Complexity**: el nivel de esfuerzo y complejidad técnica que implica implementarlo.  

A continuación, se presenta la primera versión del backlog:

| Driver ID | Título de Driver | Descripción | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
|-----------|-----------------|-------------|--------------------------------|---------------------------------------------|
| FD-01 | Seguimiento en Tiempo Real de Transportes | Permite a empresas y autoridades monitorear en tiempo real el transporte de productos peligrosos mediante IoT y Edge API. | High | High |
| FD-02 | Notificaciones de Incidentes Críticos | Envío de alertas en tiempo real a empresas y transportistas ante accidentes, desviaciones o retrasos. | High | High |
| FD-03 | Gestión de Solicitudes de Transporte | Publicación, administración y actualización del estado de solicitudes de transporte. | High | Medium |
| FD-04 | Gestión de Transportistas y Documentación | Registro, validación y control de permisos y certificaciones de transportistas. | High | Medium |
| QD-01 | Seguridad | Cifrado en tránsito y en reposo de datos sensibles; autenticación y autorización seguras. | High | High |
| QD-02 | Disponibilidad | El sistema debe garantizar ≥ 99.5% de disponibilidad mensual. | High | Medium |
| QD-03 | Rendimiento / Tiempo Real | Procesamiento de datos IoT con latencia máxima de 5 segundos. | High | High |
| QD-04 | Usabilidad | Interfaces simples y adaptables para usuarios no técnicos en dispositivos múltiples. | Medium | Medium |
| CD-01 | Arquitectura Monolítica Escalable | La solución debe desplegarse como aplicación monolítica centralizada. | Medium | Medium |
| CD-02 | Cumplimiento Normativo | Validación obligatoria de permisos y documentación en procesos críticos. | High | Medium |
| CD-03 | Compatibilidad Multidispositivo | Adaptación responsiva para navegadores en computadoras, tablets y móviles. | Medium | Low |

### 4.1.4. Architectural Design Decisions

En esta sección se resumen las decisiones de diseño arquitectónico alcanzadas durante el proceso de **Quality Attribute Workshop (QAW)**.  
Para cada iteración, se analizaron los **drivers de mayor impacto** en los stakeholders y la complejidad técnica, considerando tácticas y patrones de diseño alternativos.  
Las evaluaciones se documentan en la siguiente **Candidate Pattern Evaluation Matrix**, en la cual se incluyen los pros y contras de cada opción evaluada, y se justifican las decisiones finales.

| Driver ID | Título de Driver | Pattern 1 | Pro | Con | Pattern 2 | Pro | Con |
|-----------|-----------------|-----------|-----|-----|-----------|-----|-----|
| FD-01 | Seguimiento en Tiempo Real de Transportes | Event-Driven Architecture (EDA) | Alta capacidad de respuesta; integración natural con IoT y mensajería; escalabilidad. | Mayor complejidad técnica; requiere infraestructura de colas y brokers. | Request-Response tradicional (REST) | Simplicidad en diseño; fácil integración con servicios web. | No soporta grandes volúmenes en tiempo real; latencias elevadas. |
| FD-02 | Notificaciones de Incidentes Críticos | Publish/Subscribe Messaging | Alta desacoplación; entrega en tiempo real a múltiples suscriptores; tolerancia a fallos. | Requiere gestión de colas, configuración de tópicos y monitoreo. | Polling periódico | Implementación simple; no requiere infraestructura adicional. | Latencia alta; riesgo de pérdida de eventos críticos. |
| QD-01 | Seguridad | Security by Design + Cifrado AES-256 | Cumplimiento normativo; protección robusta de datos en reposo. | Requiere más recursos de cómputo; impacto en rendimiento. | Seguridad básica con HTTPS/TLS | Fácil implementación; estándar en frameworks. | No cubre datos en reposo ni auditoría detallada. |
| QD-02 | Disponibilidad | Load Balancing con Failover Activo-Pasivo | Alta disponibilidad; recuperación automática ante fallos. | Costo adicional de infraestructura. | Single Instance con Backups | Menor costo; simplicidad en despliegue. | Baja tolerancia a fallos; riesgo de indisponibilidad. |
| CD-01 | Arquitectura Monolítica Escalable | Monolithic Layered Architecture | Sencillo de implementar y mantener; menor complejidad inicial; coherencia de datos garantizada. | Menor flexibilidad para escalar partes específicas; riesgo de “monolith gigante”. | Modular Monolith (con paquetes y capas internas bien definidas) | Balance entre simplicidad y modularidad; facilita refactorización futura. | Requiere disciplina de desarrollo para mantener separación clara de capas. |

**Decisiones tomadas:**
- Para **seguimiento en tiempo real (FD-01)** y **notificaciones críticas (FD-02)** se adoptaron patrones basados en **eventos y mensajería (EDA + Pub/Sub)**, priorizando la **baja latencia y alta disponibilidad** frente a la simplicidad de REST o polling.  
- Para **seguridad (QD-01)** se eligió **cifrado robusto + auditoría**, aún con impacto en rendimiento, dado que los datos involucran **información sensible de transportistas y cargas peligrosas**.  
- Para **disponibilidad (QD-02)** se seleccionó un enfoque de **Load Balancing con Failover**, asegurando continuidad del servicio en picos o fallos de nodo.  
- En cuanto a **arquitectura (CD-01)**, se confirmó la elección de un **monolito modular**, dado que el alcance actual no justifica microservicios, pero sí requiere cierta modularidad para facilitar mantenibilidad y escalabilidad progresiva.

### 4.1.5. Quality Attribute Scenario Refinements

Al concluir el proceso de **Quality Attribute Workshop (QAW)**, se priorizaron los escenarios de atributos de calidad con mayor impacto para la solución **SecurOn**.  
La priorización se basó en dos dimensiones principales:  
- **Alineación con los objetivos de negocio**, principalmente garantizar la **seguridad en el transporte de materiales peligrosos** y la **continuidad de operación en tiempo real**.  
- **Factibilidad técnica** de implementación en el corto plazo, considerando restricciones de arquitectura monolítica y recursos disponibles.  

A continuación, se presentan los escenarios refinados en orden de prioridad:

---

| Scenario Refinement for Scenario 1 |
|-----------------------------------|
| **Scenario(s):** Protección de datos sensibles en tránsito y en reposo. |
| **Business Goals:** Garantizar cumplimiento normativo y confianza de empresas y transportistas al usar la plataforma. |
| **Relevant Quality Attributes:** Seguridad. |
| **Scenario Components - Stimulus:** Intento de acceso no autorizado a datos sensibles. |
| **Scenario Components - Stimulus Source:** Actor malicioso externo. |
| **Scenario Components - Environment:** Operación normal con usuarios activos. |
| **Scenario Components - Artifact (if Known):** API Gateway + Base de datos. |
| **Scenario Components - Response:** Bloqueo del acceso, registro en logs de auditoría, alerta al administrador. |
| **Scenario Components - Response Measure:** 100% de intentos bloqueados; detección < 2 segundos. |
| **Questions:** ¿Qué estándar de cifrado será obligatorio (AES-256, TLS 1.2+)? ¿Cómo se gestionarán las llaves de cifrado? |
| **Issues:** Posible impacto en el rendimiento por procesos de cifrado y validación. |

---

| Scenario Refinement for Scenario 2 |
|-----------------------------------|
| **Scenario(s):** Garantizar disponibilidad durante picos de carga. |
| **Business Goals:** Asegurar la continuidad del servicio en horarios críticos y evitar pérdidas operativas. |
| **Relevant Quality Attributes:** Disponibilidad. |
| **Scenario Components - Stimulus:** Acceso concurrente de múltiples empresas durante un pico de solicitudes. |
| **Scenario Components - Stimulus Source:** Usuarios finales (empresas). |
| **Scenario Components - Environment:** Horas pico de operación. |
| **Scenario Components - Artifact (if Known):** Plataforma SecurOn (frontend y backend). |
| **Scenario Components - Response:** Balanceo de carga y failover para mantener el servicio disponible. |
| **Scenario Components - Response Measure:** ≥ 99.5% uptime mensual. |
| **Questions:** ¿Se usará escalado vertical u horizontal en el monolito? |
| **Issues:** Limitaciones de escalabilidad en arquitecturas monolíticas. |

---

| Scenario Refinement for Scenario 3 |
|-----------------------------------|
| **Scenario(s):** Procesamiento de datos IoT en tiempo real. |
| **Business Goals:** Garantizar monitoreo de transportes peligrosos sin latencia significativa. |
| **Relevant Quality Attributes:** Rendimiento / Tiempo real. |
| **Scenario Components - Stimulus:** Datos de ubicación y estado enviados desde dispositivos IoT. |
| **Scenario Components - Stimulus Source:** Sensores instalados en el transporte. |
| **Scenario Components - Environment:** Transporte en curso. |
| **Scenario Components - Artifact (if Known):** Edge API + servicio de monitoreo en tiempo real. |
| **Scenario Components - Response:** Recepción, procesamiento y almacenamiento inmediato de los datos. |
| **Scenario Components - Response Measure:** Latencia máxima de 5 segundos por evento. |
| **Questions:** ¿Qué protocolo IoT será adoptado (MQTT, HTTP, WebSocket)? |
| **Issues:** Riesgo de pérdida de datos en conexiones inestables. |

---

| Scenario Refinement for Scenario 4 |
|-----------------------------------|
| **Scenario(s):** Recepción confiable de notificaciones críticas. |
| **Business Goals:** Permitir a empresas reaccionar de manera inmediata ante incidentes de transporte. |
| **Relevant Quality Attributes:** Fiabilidad de la comunicación. |
| **Scenario Components - Stimulus:** Ocurre un incidente (accidente, retraso o desviación). |
| **Scenario Components - Stimulus Source:** Sensor IoT del transporte. |
| **Scenario Components - Environment:** Transporte en curso bajo condiciones de riesgo. |
| **Scenario Components - Artifact (if Known):** Servicio de notificaciones + Edge API. |
| **Scenario Components - Response:** Entrega inmediata de notificación al sistema central y a la empresa usuaria. |
| **Scenario Components - Response Measure:** Entrega en < 5 segundos, tasa ≥ 99%. |
| **Questions:** ¿Cómo garantizar la entrega en áreas sin cobertura de red? |
| **Issues:** Dependencia de conectividad móvil para alertas críticas. |

---

| Scenario Refinement for Scenario 5 |
|-----------------------------------|
| **Scenario(s):** Registro intuitivo para transportistas no técnicos. |
| **Business Goals:** Favorecer la adopción de la plataforma por transportistas individuales. |
| **Relevant Quality Attributes:** Usabilidad. |
| **Scenario Components - Stimulus:** Transportista intenta registrarse y subir documentación. |
| **Scenario Components - Stimulus Source:** Usuario transportista sin experiencia técnica. |
| **Scenario Components - Environment:** Operación normal. |
| **Scenario Components - Artifact (if Known):** Módulo de Registro de Transportistas. |
| **Scenario Components - Response:** Registro completado de manera guiada con validaciones en formularios. |
| **Scenario Components - Response Measure:** Registro en < 3 minutos, ≤ 1 error por intento. |
| **Questions:** ¿Se incluirá validación automática de documentos o revisión manual? |
| **Issues:** Posible resistencia de usuarios poco familiarizados con plataformas digitales. |


## 4.2. Strategic-Level Domain-Driven Design
### 4.2.1. EventStorming
En el transcurso de la etapa de *Event Storming*, el grupo de trabajo ejecutó una actividad grupal donde se intercambiaron propuestas sobre funcionalidades y características que se pretendían integrar en el proyecto. 

Para llevar a cabo esta metodología se utilizó la herramienta *MIRO* como soporte visual y de organización. *Ver ANEXO A*

**Step 1: Unstructured exploration**

En esta etapa, se consiguieron identificar los eventos más importantes que representan las acciones fundamentales dentro de la solución tecnológica, obteniendo de esta manera los primeros esbozos de los *bounded context*.

![image](https://github.com/user-attachments/assets/20a8a668-6e4e-4d80-90fe-b87d6e609bff)

**Step 2: Timelines**

En esta fase, los eventos identificados se agruparon en conjuntos más reducidos, tomando en cuenta tanto las rutas ideales o exitosas *(happy paths)* como aquellas que representan fallos o situaciones no deseadas *(unhappy paths)*. Esta organización facilitó estructurar mejor la información y comprender las diferentes secuencias dentro del sistema de manera más clara.

![image](https://github.com/user-attachments/assets/3873cf40-8ccf-4aa3-a3a8-dd4e10f9014a)

**Step 3: Paint Points**

En este procedimiento se identificaron *paint points*, es decir, zonas problemáticas donde los usuarios podrían encontrarse con obstáculos al interactuar con nuestro sistema. Reconocerlos es fundamental para mejorar la experiencia de uso y optimizar el diseño de la aplicación.

![step3](https://github.com/user-attachments/assets/f84f6a50-bde3-46fe-8577-3a862380ec8c)


**Step 4: Pivotal Points**

A lo largo de esta etapa se reconocieron *pivotal points*, es decir, eventos fundamentales que representan instantes críticos en el flujo de la plataforma, con un impacto significativo en el comportamiento del sistema o la experiencia de usuario.

![image](https://github.com/user-attachments/assets/7d6160ab-2489-4c5e-9206-7b69ddd0b90b)

**Step 5: Commands**

En este procedimiento, a cada evento se le asignó un comando específico que lo desencadena y un actor responsable de ejecutarlo, lo que permitió entender mejor la interacción de los usuarios con el sistema.

![step5](https://github.com/user-attachments/assets/511ac749-892d-4f8e-9ab5-c175d36c27bc)

**Step 6: Policies**

En esta fase se establecieron las políticas relevantes para cada contexto del sistema, incluyendo reglas de negocio, validaciones y restricciones específicas. 

![step6](https://github.com/user-attachments/assets/cd03c448-e0cf-42f4-b22b-d49c73f8ec9a)

**Step 7: Read Models**

En esta etapa se diseñaron y desarrollaron los modelos de lectura correspondientes a cada contexto del sistema, garantizando que ofrecieran la información necesaria de forma clara, eficiente y alineada con las necesidades de usuario.

![step7](https://github.com/user-attachments/assets/c3698437-46d0-42c1-98f2-0a2feefa6a73)

**Step 8: External Systems**

Durante el desarrollo de este proceso se identificaron los sistemas externos con los que la plataforma debe interactuar y se definieron las interfaces necesarias para lograr una integración efectiva.

![step8](https://github.com/user-attachments/assets/43c6e6a4-103b-4425-94e1-60daccd9f8b6)


**Step 9: Aggregates**

En el desarrollo de esta fase se definieron los *aggregates* para cada contexto del sistema, con el propósito de representar adecuadamente las transacciones y operaciones que deben mantenerse coherentes.

![step9](https://github.com/user-attachments/assets/4129de72-61c2-4287-8e04-6e7a03dd6f7c)

**Step 10: Bounded Contexts**

Finalmente, gracias a la identificación y definición de cada uno de los elementos se pudo alcanzar la resolución de los *bounded contexts*, espacios centrales de funcionamiento diferentes, pero necesarios.

![bcts](https://github.com/user-attachments/assets/33a1784f-b1aa-4c31-b0b2-3d7891c702b8)


### 4.2.2. Candidate Context Discovery

Para priorizar el desarrollo del núcleo funcional del sistema se aplicó la técnica *start-with value*, con el propósito de tener una perspectiva más clara y enfocada del producto desde sus fundamentos.

- **Identificación de valores del negocio:** Se ejecutó un análisis de los principales valores que aporta la aplicación. Tales como mejorar la experiencia de nuestros usuarios durante la monitorización de cargas, el registro eficiente de incidentes ocurridos durante el transporte, la calificación a nuestros usuarios transportistas luego de cada viaje realizado y la optimización en la gestión de usuarios en SecurOn.
- **Identificación de funcionalidades clave:** Se definieron las funcionalidades fundamentales que sostienen el objetivo de nuestro sistema. Incluyendo la autenticación y registro de usuarios *(IAM)*, el monitoreo y notificación de incidentes *(MANAGEMENT)* y las operaciones de registro y reporte de incidentes *(RECORDS)*. Todas ellas alineadas directamente con el valor agregado del negocio.

**Candidate para Bounded Context: *IAM***

![iamBC](https://github.com/user-attachments/assets/60d88854-4c28-49c2-ab1c-b5df1bef1907)

**Candidate para Bounded Context: *MANAGEMENT***

![managementBC](https://github.com/user-attachments/assets/4f17b55d-9a8e-4d5e-8c82-2915430d7488)

**Candidate para Bounded Context: *RECORDS***

![recordsBC](https://github.com/user-attachments/assets/673b12d5-0db6-4d8a-8ef5-f9edd020ff22)

**Vista Completa**

![bcs](https://github.com/user-attachments/assets/9b91cbb8-8664-49b3-92bb-9342524bc4fb)


### 4.2.3. Domain Message Flows Modeling


**Iniciar sesión:** El flujo de autenticación comienza cuando el usuario ingresa sus credenciales, que luego el sistema valida. Si las credenciales son correctas, el usuario es redirigido al panel principal; de lo contrario, el flujo se detiene y muestra un mensaje de error.

![Diagrama de flujo de inicio de sesión](https://i.imgur.com/xMhtNnf.png)

**Visualización de historial de transportes:** Este flujo permite al usuario acceder a un historial de transportes que se carga dinámicamente desde la base de datos. El usuario puede usar filtros para refinar los resultados y hacer clic en cada registro para ver más detalles.

![Diagrama de flujo de visualización de historial de transportes](https://i.imgur.com/MdgpWkT.png)

**Monitoreo real de transporte:** El flujo de monitoreo en tiempo real utiliza un mapa interactivo que actualiza constantemente la ubicación de los vehículos a través de APIs de geolocalización en vivo. Además, el sistema envía notificaciones si ocurren eventos importantes, como desvíos o retrasos.

![Diagrama de flujo de monitoreo real de transporte](https://i.imgur.com/ZrJcw9H.png)

### 4.2.4. Bounded Context Canvases 

**Iniciar sesión:** El usuario accede al sistema ingresando sus credenciales en una interfaz sencilla que valida su autenticidad antes de redirigirlo al panel principal.

![Canvas de inicio de sesión](https://i.imgur.com/iagavZb.png)

**Visualización de historial de transportes:** El usuario puede ver una lista detallada de transportes anteriores, con opciones para filtrar y ver información específica de cada registro.

![Canvas de visualización de historial de transportes](https://i.imgur.com/kiryIY9.png)

**Monitoreo real de transporte:** El sistema muestra la ubicación y el estado de los vehículos en tiempo real en un mapa interactivo, lo que permite la supervisión y la respuesta inmediata ante cualquier eventualidad.

![Canvas de monitoreo real de transporte](https://i.imgur.com/vXip4Oq.png)

---

### 4.2.5. Context Mapping

Este diagrama ilustra la interacción entre los contextos delimitados **IAM**, **Records** y **Management** en **SecurOn**. **IAM** y **Management** se comunican a través de un **Shared Kernel**, compartiendo la lógica de autenticación y gestión de transporte. **Records** utiliza una **ACL** (Capa Anti-Corrupción) con **Management** e **IAM** para proteger la integridad de los datos y evitar contaminación. **IAM** actúa como **Supplier** para **Records**, proporcionando servicios de autenticación que **Records** consume para gestionar incidentes. Esto promueve una arquitectura modular y cohesiva en el sistema.

<img src="https://i.ibb.co/sp7H8nd7/contextmapping.png" alt="contextmapping" border="0">

### 4.3. Software Architecture

#### 4.3.1. Software Architecture System Landscape Diagram

El diagrama identifica a dos usuarios principales: el **Driver** (Conductor) y el **Manager** (Gerente), quienes interactúan directamente con el sistema **SecurOn** para gestionar el transporte y responder a posibles riesgos. Además, el sistema **SecurOn** utiliza un **Alert System**, un servicio de notificaciones, para enviar alertas y mantener a los usuarios informados sobre cualquier evento relevante durante el proceso de transporte.

<img src="https://github.com/user-attachments/assets/14a7f683-26a9-4b40-afeb-f2ceea60d94f" alt="landscapecontext" border="0">

#### 4.3.2. Software Architecture Context Level Diagrams

Este diagrama **contextualiza** cómo el sistema **SecurOn** se integra en su entorno y qué **actores externos** (personas o sistemas) interactúan con él. Destaca el flujo de información crucial, como el **monitoreo**, las **alertas** y la **gestión de incidentes** en situaciones de riesgo.

![image](https://github.com/user-attachments/assets/9e9d621e-da36-4ec8-a68b-368853473291)

---

#### 4.3.3. Software Architecture Container Level Diagrams

El diagrama muestra la **arquitectura de software a nivel de contenedores** del sistema de mitigación de riesgos. Incluye a los actores **Driver** y **Manager**, que interactúan con componentes como la **Mobile App**, **Landing Page**, **Web Application**, **Edge Application**, **IoT Embedded App**, **Alert System**, **Web API**, **Edge Database** y **Web Database**. Las conexiones indican los flujos de datos y notificaciones, como el **monitoreo**, las **alertas de incidentes** y las **consultas**. Integra aplicaciones móviles, web y de borde con bases de datos para gestionar información en tiempo real. Los **bounded context** incluidos son **IAM**, **Management** y **Records**.

![image](https://github.com/user-attachments/assets/ca75228c-708d-4ed8-8ca5-129b9ef4128a)

---

#### 4.3.4. Software Architecture Deployment Diagrams

El diagrama de despliegue detalla la **arquitectura de software** de **SecurOn** para la mitigación de riesgos de productos químicos reactivos. Muestra los contenedores y nodos de despliegue: **Landing Page** (HTML/CSS, Github Pages), **Web Application** (Angular/Springboot, Netlify), **Web API** y **Edge API Application** (Springboot, Azure), **Mobile App** (Flutter, dispositivos móviles), **IoT Embedded App** (Python, dispositivos IoT), **Web Database** (MySQL, Azure) y **Edge Database** (MySQL, Azure). Las conexiones representan los flujos de datos, incluyendo el **monitoreo**, la **transferencia de datos IoT** y las operaciones de **lectura y escritura en las bases de datos**.

<img src="https://github.com/user-attachments/assets/c2fac1fa-18fb-4547-ab6f-56cac609d78a" alt="deployment" border="0">
<br>

# Capítulo V: Tactical-Level Software Design

## 5.X. Bounded Context: <Bounded Context Name>
### 5.X.1. Domain Layer
### 5.X.2. Interface Layer
### 5.X.3. Application Layer
### 5.X.4. Infrastructure Layer
### 5.X.6. Bounded Context Software Architecture Component Level Diagrams
### 5.X.7. Bounded Context Software Architecture Code Level Diagrams
#### 5.X.7.1. Bounded Context Domain Layer Class Diagrams
#### 5.X.7.2. Bounded Context Database Design Diagram


# Capítulo VI: Solution UX Design
## 6.1. Style Guidelines
### 6.1.1. General Style Guidelines
### 6.1.2. Web, Mobile & Devices Style Guidelines

## 6.2. Information Architecture
### 6.2.2. Labeling Systems
### 6.2.3. Searching Systems
### 6.2.4. SEO Tags and Meta Tags
### 6.2.5. Navigation Systems

## 6.3. Landing Page UI Design
Durante la fase inicial del diseño de la interfaz de la página de inicio (landing page), un paso fundamental es la elaboración de un wireframe. Este funciona como un esquema preliminar que representa la disposición y organización de los elementos esenciales de la página. En este caso, se contemplan apartados como la barra de navegación en el área principal, el encabezado o Hero, la sección de servicios, la información corporativa, los testimonios, la opción de descarga y el pie de página.

### 6.3.1. Landing Page Wireframe

Hero:

![image](https://github.com/user-attachments/assets/8995e159-15f6-4bf4-9a9f-2cbe0e68860d)

Services:

![image](https://github.com/user-attachments/assets/c7ce2413-f6b9-4359-804d-d6f6d48ea7a9)

About us:

![image](https://github.com/user-attachments/assets/a2140cd0-fa6d-46d0-bd69-046f8b9668b4)

Testimonials:

![image](https://github.com/user-attachments/assets/9cc4d581-7022-4e76-8dfd-df58706562cc)

Download:

![image](https://github.com/user-attachments/assets/88aad065-1a17-4217-b814-b2ebb3b36da3)

Footer:

![image](https://github.com/user-attachments/assets/4c0265b9-db50-401e-97cf-a08bf8dd5114)

### 6.3.2. Landing Page Mock-up

Hero:

![image](https://github.com/user-attachments/assets/89f42efd-c555-426c-ab67-a89d68fd4d36)

Services:

![image](https://github.com/user-attachments/assets/1185c8ba-d63f-4267-a5ac-f3b655a710b7)

About us:

![image](https://github.com/user-attachments/assets/e7d26a9d-8e06-43af-999f-1381fc0ded28)

Testimonials:

![image](https://github.com/user-attachments/assets/16b6e8ac-4b0f-4f8d-bd81-f81e532be8d4)

Download:

![image](https://github.com/user-attachments/assets/6cbbe3c0-e59f-4e4e-b9fd-054db6526844)

Footer:

![image](https://github.com/user-attachments/assets/12ee1743-0d86-43fa-8d52-ba26b9a8f389)


## 6.4. Applications UX/UI Design
En este apartado se presentan las propuestas visuales y de interacción de nuestras aplicaciones web y móviles, tomando en cuenta la experiencia del usuario al interactuar con los productos.

### 6.4.1. Applications Wireframes
Aquí se muestran los wireframes desarrollados para la aplicación web y móvil Chemtack.

**Wireframes Web Application:**

![Wireframes Web App](https://i.imgur.com/CswDZjd.png)

**Wireframes Web Application Responsive:**
![Wireframes Web App Responsive](https://i.imgur.com/dV2z3Vz.png)

**Wireframes Mobile:**

![Wireframes Mobile App](https://github.com/user-attachments/assets/1d66d831-2319-4cc4-9eb5-27a1d815defa)

[Enlace para acceder al Figma.](https://www.figma.com/design/c7g8w481pDMJGjvVyiU6F1/Chemtrack?node-id=87-44&t=Nj0ZnQTSve38LPvz-1 "Enlace para acceder al Figma.")

### 6.4.2. Applications Wireflow Diagrams

En esta sección, se presentan los Wireflows, donde se mostrarán las rutas que los usuarios pueden tener al momento de usar la aplicación web y móvil. Para su realización se utilizó la herramienta LucidChart.

---

**Wireflow Diagrams Mobile Application:**
**User goal, usuario inicia sesion y se registra**

**Descripción:**
Al iniciar la aplicación, el usuario se encuentra en la página de opciones, donde puede iniciar sesión. Si el usuario no posee una cuenta puede registrar una nueva utilizando su correo electrónico.

![Wireflow Mobile Application 1](https://i.imgur.com/QvX5QtC.jpeg)

**User goal, usuario transportista acepta servicio e inicia recorrido**

**Descripción:**
Cuando el transportista haya aceptado el servicio y comience con la ruta presiona en la app la opción de iniciar recorrido, donde le figurará detalles acerca del recorrido y la carga a transportar y parámetros brindados por los sensores.

![Wireflow Mobile Application 2](https://i.imgur.com/FojRu3F.jpeg)

**User goal, usuario transportista reporta incidente**

**Descripción:**
El usuario puede reportar incidentes que hayan ocurrido durante el recorrido para que de ese modo el administrador permanezca atento de ello.

![Wireflow Mobile Application 3](https://i.imgur.com/GqzxViA.jpeg)

**User goal, usuario administrador añade nueva ruta a monitorear**

**Descripción:**
Desde la app el admnistrador tiene la opción de poder añadir nuevos servicios a monitorear para que así pueda ir monitoreando remotamente como se encuentran los parámetros de los sensores.

![Wireflow Mobile Application 4](https://i.imgur.com/rrNCCir.jpeg)

**User goal, usuario administrador visualiza reportes de incidentes**

**Descripción:**
El usuario administrador puede visualizar los reportes de incidentes brindados por los transportistas al igual de los parámetros de monitoreo que dejaron los sensores en dicho momento.
![Wireflow Mobile Application 5](https://i.imgur.com/HaLPhcx.jpeg)

[Enlace para acceder a LucidChart.](https://lucid.app/lucidchart/78d14ebd-5614-4c11-be07-705631141f25/edit?viewport_loc=-3238%2C-2725%2C14392%2C6984%2Cz.Le~yULM6Za&invitationId=inv_efb1a0e4-2462-43d2-805c-6c06dbb66383 "Enlace para acceder a LucidChart.")

### 6.4.2. Applications Mock-ups
En este apartado se presentan los mock-ups correspondientes a la aplicación web y móvil Chemtrack.

**Web Application Mock-up**

![Mock-up Web Application](https://i.imgur.com/yqDNN8S.png)

**Web Application Responsive Mock-up**
![Mock-up Web Application Responsive](https://i.imgur.com/etnXnd4.png)


**Mobile Application Mock-ups:**

![Mock-up Mobile Application](https://i.imgur.com/B0GUcoa.png)

[Enlace para acceder al Figma.](https://www.figma.com/design/c7g8w481pDMJGjvVyiU6F1/Chemtrack?node-id=87-45&t=Nj0ZnQTSve38LPvz-1 "Enlace para acceder al Figma."

### 6.4.3. Applications User Flow Diagrams
En esta sección, se presentan los User Flows, donde se mostrarán las Happy y Unhappy paths que los usuarios pueden tener al momento de usar la aplicación web y móvil. Para su realización se utilizó la herramienta LucidChart.
- Entonces podrá ingresar a la sección "Monitoring" para iniciar el recorrido
- Si selecciona una ruta, se le muestran los detalles del viaje y de la carga
- Si desea añadir una nueva ruta, se le muestra un formulario para completarla
- Al iniciar el recorrido, se muestran los datos de monitoreo en tiempo real
- Entonces puede seguir la ruta y finalizar la entrega desde la interfaz

![image](https://i.imgur.com/SsocVaB.jpeg)

**User goal, usuario transportista reporta incidente**

**Task Flow:**

- Si el transportista se encuentra realizando un recorrido
- Entonces puede acceder a la sección "Incidents" desde el menú
- Si decide registrar un nuevo incidente, se le muestra un formulario
- Al completar los campos requeridos, puede enviar el reporte
- Entonces el incidente queda registrado y visible para el administrador

![image](https://i.imgur.com/7bxJw1e.jpeg)

**User goal, usuario administrador añade nueva ruta a monitorear**

**Task Flow:**

- Si el administrador accede a la sección "Monitoring"
- Entonces puede seleccionar la opción para añadir una nueva ruta
- Si decide continuar, se le muestra un formulario para completar los datos
- Al guardar la información, la nueva ruta queda registrada
- Entonces podrá monitorear los parámetros de los sensores en esa ruta

![image](https://i.imgur.com/7BzRtg9.jpeg)

**User goal, usuario administrador visualiza reportes de incidentes**

**Task Flow:**

- Si el administrador accede a la sección "Incidents"
- Entonces se le muestra la lista de reportes enviados por los transportistas
- Si selecciona un reporte, se visualiza el detalle del incidente
- Entonces también se muestran los parámetros de monitoreo asociados al evento

![image](https://i.imgur.com/aFCOnRN.jpeg)



[Enlace para acceder a LucidChart](https://lucid.app/lucidchart/78d14ebd-5614-4c11-be07-705631141f25/edit?viewport_loc=-7647%2C-2992%2C14024%2C6805%2C0_0&invitationId=inv_efb1a0e4-2462-43d2-805c-6c06dbb66383 "Enlace para acceder a LucidChart"). 


## 6.5. Applications Prototyping

En este apartado se presenta el prototipo desarrollado en Figma, el cual refleja la aplicación de principios de arquitectura de la información, buscando que la experiencia sea lo más eficiente y clara posible.

Principio de elección:
Se procura que tanto la aplicación web como la móvil mantengan un número adecuado de secciones visibles en todo momento. Por ello, ambas incluyen una barra superior fija con cuatro secciones que permiten acceder rápidamente a las funcionalidades desde cualquier pantalla.

Principio de divulgación:
La información se organiza en bloques diferenciados, lo que facilita al usuario ubicar con mayor rapidez el contenido o función que necesita.

Video de presentación del prototipo:
**Prototipo Web Application**
Timing: 0:00
Duración: 03:31

![image](https://i.imgur.com/bMplMmA.png)

**Prototipo Mobile Application**
Timing: 03:32
Duración: 03:51

![image](https://i.imgur.com/H1gB1R8.png)

[Link al video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114248_upc_edu_pe/Eb7QckaAXOZHqCAdbBh9b1cB-LXKRizGLBlfKQjgbgPFjQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=60MG8p "Link al video").


## Conclusiones

El desarrollo de SecurOn representó un esfuerzo colaborativo integral que abarcó todas las etapas clave del proyecto, desde la definición del problema hasta el diseño arquitectónico. La integración efectiva de distintos roles y perspectivas dentro del equipo permitió enriquecer cada fase del proceso, asegurando que la solución fuera técnicámente sólida y centrada en el usuario. Gracias a una planificación estratégica, la adopción de metodologías ágiles y una comunicación constante, se logró mantener una organización clara que facilitó anticipar riesgos, adaptarse a cambios y cumplir consistentemente con los objetivos establecidos. Como resultado, se ha consolidado una base sólida que alinea los aspectos técnicos con las metas del negocio, sentando las bases para el crecimiento y la escalabilidad futura de SecurOn.

## Recomendaciones

Para garantizar el éxito continuo y la evolución de SecurOn, se recomienda priorizar el desarrollo iterativo basado en feedback real de usuarios en las próximas etapas. Además, es crucial consolidar un roadmap de producto que incorpore nuevas funcionalidades previamente identificadas, así como fortalecer continuamente los protocolos de seguridad y privacidad para cumplir con las regulaciones emergentes. Finalmente, se sugiere explorar oportunidades de integración con plataformas complementarias que puedan ampliar el alcance y valor de la solución.

# Bibliografía

Aguilar-Velázquez, J. A., & Salazar-González, M. (2018). Evaluación del riesgo en el transporte terrestre de sustancias peligrosas mediante sistemas de información geográfica. Revista Internacional de Contaminación Ambiental, 34(1), 131-141.

García, C. H., & Martínez, J. D. (2022). Aplicación de sensores IoT para detección temprana de fugas en unidades móviles de transporte de gas. Revista Electrónica de Ciencia y Tecnología, 19(1), 47-55.

López-Atamoros, L. G., Fernández-Villagómez, G., Cruz-Gómez, M. J., & Durán-de-Bazúa, C. (2010). Integración de una Base Nacional de Datos de Accidentes durante el Transporte de Gas LP (BNDAT@ GLP) 1998-2009: Sustento para un estudio de evaluación de riesgo. Tecnología, Ciencia, Educación, 25(2), 99-112.

Rivas-Tovar, L. A., & Vázquez-González, R. (2017). Desarrollo de un sistema de monitoreo para transporte de materiales peligrosos utilizando sensores y redes inalámbricas. Revista Iberoamericana de Automática e Informática Industrial RIAI, 14(3), 315-324.

Soto, J. A. S., González, D. L. E., Sánchez, J. F. I., Reyes, J. A., & Layva, J. M. E. (2023). DISEÑO DE DISPOSITIVO PARA PREVENIR ACCIDENTES CAUSADOS POR FUGAS DE GAS. Revista IPSUMTEC, 6(4), 11-14.


# Anexos

**Anexo A.** Event Storming desarrollado en la plataforma MIRO.

![eventStorming](https://github.com/user-attachments/assets/fe7db010-856e-4eee-8ef3-90a84ecb3327)


**Videos de exposición**

Video de exposición TB1: https://upcedupe-my.sharepoint.com/personal/u202114248_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202114248%5Fupc%5Fedu%5Fpe%2FDocuments%2FDevTergentes%2FTB1%2Fupc%2Dpre%2D202502%2D1asi0728%2D14653%2DDevTergentes%2Dexpo%2Dtb1%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Efc550a72%2D774b%2D4c15%2Dad9c%2Dd66fd808ffee



