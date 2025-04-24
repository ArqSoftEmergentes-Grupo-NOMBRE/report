# Informe de Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**  
**Ingenieria de Software**  
**Ciclo 08**

**Código del curso: 1ASI0728**  
**Curso: Arquitecturas De Software Emergentes**  
**NRC: 4281**

**Profesor: Rojas Malasquez, Royer Edelwer**

**Startup: a**

**Producto: a**

### Relación de integrantes:

|      Apellidos y Nombres       |   Código   |
|:------------------------------:|:----------:|
| Castilla Pachas, César Antonio | u202218735 |
| Cortés Casas, Joaquin Marcelo  | u202114545 |
|   Diaz Silva, Fernando Josué   | u202112722 |
| Jorge Arévalo, Ramón Alejandro | u20221D126 |

**Abril, 2025**

---

## Registro de Versiones del Informe

| **Versión** | **Fecha**  |           **Autor**            | **Descripción de Modificación**                                 |
|-------------|------------|--------------------------------|-----------------------------------------------------------------|
| 1.0         | 15/04/2025 | Cortés Casas, Joaquín Marcelo  | Creación del informe. Adición de carátula y tabla de contenidos |
| ...         | ...        | ...                            | ...                                                             |

---

## Project Report Collaboration Insights
### URL del repositorio en la organización GitHub
[Enlace al repositorio del informe en GitHub](https://github.com/SolucionesIoT-Grupo-IoTInnovators/report/tree/develop)

### Actividades de elaboración del informe
#### TB1:

**Descripción de las actividades realizadas:**
- **Castilla Pachas, César Antonio:** a
- **Cortés Casas, Joaquin Marcelo:** a
- **Diaz Silva, Fernando Josué:** a
- **Jorge Arévalo, Ramón Alejandro:** a

**Evidencia de colaboración y commits en GitHub del reporte:**

![Captura de analíticos de colaboración de GitHub - 1]()
![Captura de commits de GitHub - 1]()

---

## Contenido

**Tabla de contenidos**

- [Student Outcome](#student-outcome)

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
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
    - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
        - [4.1.1. Design Purpose](#411-design-purpose)
        - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
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

- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

- [Bibliografia](#bibliografia)

- [Anexos](#anexos)

---

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias. 

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| **Criterio específico**                                                                                                                                                               | **Acciones realizadas**                                                                                                                                                                            | **Conclusiones** |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.    | Castilla Pachas, César Antonio<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Cortés Casas, Joaquin Marcelo<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Diaz Silva, Fernando Josué<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Jorge Arévalo, Ramón Alejandro<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/> | Lorem ipsum dolor sit amet.               |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Castilla Pachas, César Antonio<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Cortés Casas, Joaquin Marcelo<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Diaz Silva, Fernando Josué<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>Jorge Arévalo, Ramón Alejandro<br/>TB1<br/>Lorem ipsum dolor sit amet.<br/>TP1<br/>Lorem ipsum dolor sit amet.<br/>TB2<br/>Lorem ipsum dolor sit amet.<br/>TF1<br/>Lorem ipsum dolor sit amet.<br/><br/>                                                                                                                                                                                                   | Lorem ipsum dolor sit amet.               |

---


# Capítulo I: Introducción

## 1.1. Startup Profile


### 1.1.1. Descripción de la Startup

**SmartWebContracts** es una startup universitaria formada por estudiantes de tecnología con interés en aplicar **contratos inteligentes en entornos reales** para resolver problemas de confianza y transparencia en el desarrollo de sitios web. Nuestra propuesta central gira en torno a la creación de una **plataforma descentralizada** que permite automatizar acuerdos entre desarrolladores web y sus clientes mediante **blockchain**, garantizando así el cumplimiento del servicio, la seguridad del pago, y la generación de un comprobante digital como evidencia de ejecución.

####  Misión:
Desarrollar soluciones tecnológicas basadas en blockchain que automaticen los acuerdos de servicios digitales, promoviendo la **transparencia, confianza y equidad** en la contratación de profesionales independientes del desarrollo web.

####  Visión:
Ser reconocidos como una **startup innovadora** en el desarrollo de herramientas digitales seguras para freelancers, fomentando el uso de tecnologías descentralizadas como blockchain en Latinoamérica y más allá.


### 1.1.2. Perfiles de integrantes del equipo

| Foto | Nombre completo          | Código | Carrera | Resumen |
|------|--------------------------|--------|---------|---------|
|  *(colocar foto aquí)* | **Name**                 | Código | Carrera | Resumen |
|  *(colocar foto aquí)* | **Name**  | Código | Carrera | Resumen |
|  *(colocar foto aquí)* | **Name** | Código | Carrera | Resumen |
|  *(colocar foto aquí)* | **Name**  | Código | Carrera | Resumen |
|  *(colocar foto aquí)* | **Name**  | Código | Carrera | Resumen |

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y Problemática

#### Enunciado del Problema
Existe una **falta de confianza en la contratación de servicios de desarrollo web**, donde los clientes temen no recibir el servicio prometido, y los desarrolladores temen no ser remunerados. Esto genera fricciones, sobrecostos, y pérdida de oportunidades para ambos.


| Clave | Pregunta | Respuesta                                                                                                 |
|-------|----------|-----------------------------------------------------------------------------------------------------------|
| **Who** | ¿Quiénes están involucrados? | Desarrolladores web y Profesionales que buscan crear un portafolio digital.                               |
| **What** | ¿Qué ocurre? | Se generan riesgos de fraude, falta de pago o incumplimiento en acuerdos de servicios web.                |
| **Where** | ¿Dónde ocurre? | En entornos digitales, principalmente redes sociales, plataformas independientes o acuerdos directos.     |
| **When** | ¿Cuándo ocurre? | Al contratar desarrolladores web por fuera de plataformas intermediarias.                                   |
| **Why** | ¿Por qué es un problema? | Porque no hay garantías legales ni mecanismos automáticos de verificación.                                |
| **How** | ¿Cómo se presenta? | A través de entregas fallidas, impagos o disputas entre las partes.                                       |
| **How Much** | ¿Qué tanto afecta? | Impacta directamente en la reputación de los desarrolladores y en la pérdida económica para ambas partes. |



---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
**Problem Statement 1**  
Se ha identificado que los desarrolladores web enfrentan desafíos importantes para garantizar el pago de sus servicios una vez entregado el producto final. La ausencia de mecanismos automatizados de verificación y pago genera desconfianza, especialmente cuando se trabaja fuera de plataformas intermediarias. Esto provoca frustración, riesgo de impago y limita el crecimiento de los profesionales independientes. Por lo tanto, se reconoce la necesidad de desarrollar un sistema descentralizado que asegure el cumplimiento del contrato y la liberación del pago únicamente cuando el cliente confirme que el servicio fue entregado correctamente o cuando el sistema lo valide automáticamente.

**¿Cómo podemos garantizar que los desarrolladores reciban el pago justo y oportuno por sus servicios sin depender de intermediarios, utilizando tecnologías descentralizadas?**

---

**Problem Statement 2**  
Por otro lado, se observa que muchos clientes que contratan servicios de desarrollo de páginas web no tienen la certeza de que recibirán un producto funcional o conforme a lo pactado. Las contrataciones informales y la falta de evidencia sobre el cumplimiento generan desconfianza, pérdida de tiempo y dinero. Además, no existe un mecanismo claro para verificar el estado de entrega ni para contar con una prueba digital de que el servicio se ha realizado. Por ello, se plantea la necesidad de contar con un sistema que permita validar de forma automatizada el estado del servicio y que brinde al cliente una prueba irrefutable de que se cumplió lo acordado, reduciendo así el riesgo percibido y fomentando relaciones comerciales más seguras.

**¿Cómo podemos ofrecer a los clientes una forma confiable y automatizada de validar la entrega de servicios web freelance y respaldar su cumplimiento mediante evidencia digital?**


---

#### 1.2.2.2. Lean UX Assumptions

#### • Business Assumptions

**Necesidad del mercado:**  
Creemos que tanto los desarrolladores web como sus clientes enfrentan desafíos al momento de contratar y entregar servicios digitales de forma segura y transparente. Los desarrolladores buscan garantías de pago tras la entrega, mientras que los clientes desean recibir productos funcionales antes de liberar el dinero. Actualmente, la informalidad de estos acuerdos, sumada a la falta de evidencia de cumplimiento, genera desconfianza en ambas partes.

**Solución integral:**  
Suponemos que el problema de la falta de garantías en servicios freelance puede ser mitigado mediante una **plataforma basada en contratos inteligentes en Ethereum**, que actúe como intermediario automático e imparcial. Esta plataforma validará el cumplimiento del servicio y ejecutará el pago automáticamente cuando se cumplan las condiciones predefinidas. Adicionalmente, generará un **comprobante digital** como prueba de cumplimiento.

**Clientes iniciales:**  
Nuestros clientes estarán divididos en dos segmentos:

- **Desarrolladores Web:** Profesionales que ofrecen servicios de desarrollo de landing pages o portafolios web y desean un sistema justo, transparente y automático para asegurar el pago.
- **Profesionales que buscan crear un portafolio digital** Personas que necesitan un sitio web funcional y desean tener garantía de cumplimiento antes de pagar, sin depender de plataformas intermediarias costosas.

**Propuesta de valor:**  
El valor principal de SmartWebContracts radica en brindar una solución descentralizada y segura para contratar servicios de desarrollo. Los contratos inteligentes garantizan transparencia y cumplimiento, mientras que la generación de comprobantes digitales permite certificar el trabajo realizado. Los beneficios clave incluyen:

- Protección automática para ambas partes durante la contratación.
- Reducción de conflictos y riesgo de fraude.
- Pago justo, liberado solo tras validación de cumplimiento.
- Evidencia digital verificable como respaldo profesional.

**Estrategia de adquisición:**  
Captaremos usuarios a través de comunidades de freelancers, grupos de desarrolladores, plataformas educativas, foros de criptomonedas y redes sociales. Se realizarán campañas piloto y demos con estudiantes y profesionales del desarrollo web. Además, se impulsará la adopción del sistema mediante **tutoriales sobre contratos inteligentes y wallets** para facilitar el onboarding.

**Principales riesgos:**
- Baja adopción por desconocimiento del uso de wallets o blockchain.
- Fallos en la validación automática del cumplimiento del servicio.
- Rechazo por parte de usuarios tradicionales no familiarizados con Web3.

**Mitigación de riesgos:**  
Se mitigarán mediante educación en el uso de wallets y contratos inteligentes, diseño de interfaz amigable y desarrollo incremental de validaciones automatizadas. Se incluirán también mecanismos de reclamo o evaluación secundaria por parte del cliente en los primeros lanzamientos.


#### •  User Assumptions

**¿Quién es el usuario?**
- **Desarrolladores web:** Jóvenes estudiantes, egresados o profesionales que ofrecen servicios de diseño web y buscan una forma segura y profesional de ser contratados y cobrar por sus servicios.
- **Profesionales que buscan crear un portafolio digital:** Personas que requieren una presencia digital rápida y profesional, como landing pages o portafolios.

**¿Dónde encaja nuestro producto?**
- En la rutina profesional: como una herramienta que les asegura el pago de su trabajo al entregar el servicio según lo pactado.
- En el proceso de contratación de clientes: como una garantía de que recibirán el producto antes de liberar el dinero.

**Problemas identificados y soluciones propuestas:**
- **Riesgo de impago al desarrollador web:**
    - *Solución:* contrato inteligente que bloquea el pago y lo libera solo si el servicio es entregado correctamente.
- **Dudas del cliente sobre la entrega del servicio:**
    - *Solución:* validación automática del servicio y generación de comprobante digital en blockchain.

**¿Cuándo y cómo se usa nuestro producto?**
- **Desarrollador web:** activan un contrato inteligente al iniciar el proyecto, configuran las condiciones, y al concluir, validan la entrega para liberar el pago.
- **Clientes:** depositan el pago en un contrato inteligente, reciben notificación cuando el servicio ha sido validado, y obtienen el acceso final + ticket digital del cumplimiento.

**Características importantes:**
- Contrato inteligente con condiciones personalizadas.
- Validación automática (por sistema o cliente).
- Liberación de pago vía blockchain (Ethereum, Trust Wallet).
- Comprobante digital de cumplimiento.
- Interfaz web accesible, clara y segura.

**Aspecto y comportamiento del producto:**
- **UI:** diseño moderno y minimalista compatible con navegadores y dispositivos móviles.
- **UX:** intuitiva, con guía paso a paso para contratación, seguimiento y validación.
- **Disponibilidad:** 24/7, sin necesidad de intervención de terceros.

**Features principales:**
- Registro y autenticación de clientes y desarrolladores web.
- Creación de contratos inteligentes personalizados.
- Integración con wallets Web3 (ej. Trust Wallet).
- Validación automatizada de cumplimiento.
- Emisión de ticket digital con hash en blockchain.
- Historial de contratos y reputación de desarrolladores web.
---



#### 1.2.2.3. Lean UX Hypothesis Statements

En relación con los segmentos objetivos definidos en SmartWebContracts, se presentan las siguientes hipótesis:

#### • Hipótesis para Desarrolladores Web:

Creemos que, al brindar a los desarrolladores una plataforma respaldada por contratos inteligentes que garantice el pago automático una vez validado el cumplimiento del servicio, se incrementará su seguridad, motivación y profesionalismo al momento de aceptar proyectos freelance.

Sabremos que hemos tenido éxito cuando al menos el 80% de los desarrolladores manifiesten sentirse más seguros al usar el sistema y se observe una tasa de finalización de proyectos superior al 90%, verificado mediante análisis de uso y encuestas post-proyecto.

#### • Hipótesis para Profesionales que buscan crear un portafolio digital:

Creemos que, al ofrecer a los profesionales una solución automatizada para contratar desarrolladores con validación de entrega y generación de comprobante digital, se incrementará la confianza y disminuirá la incertidumbre al momento de solicitar un servicio a uno o a un grupo de desarrolladores web.

Sabremos que hemos tenido éxito cuando más del 50% de los clientes contraten nuevamente a través de la plataforma y menos del 5% presenten reclamos o insatisfacción en la entrega, medido por métricas del sistema y encuestas de satisfacción.

#### • Hipótesis de Integración Tecnológica (Blockchain + Validación):

Creemos que, al integrar tecnología blockchain (Ethereum) con wallets Web3 y validaciones automáticas de cumplimiento, se logrará un proceso fluido y descentralizado que reduzca la necesidad de intervención humana o plataformas intermediarias.

Sabremos que hemos tenido éxito cuando el 95% de los contratos ejecutados se completen sin intervención manual, y al menos el 85% de los usuarios puedan utilizar correctamente el sistema desde su primera experiencia, verificado mediante pruebas piloto y métricas de adopción.

#### • Hipótesis de Viralidad y Reputación Profesional:

Creemos que una experiencia positiva al usar la plataforma, sumada a la generación de comprobantes digitales verificables en blockchain, incentivará tanto a desarrolladores como a profesionales a compartir y recomendar el sistema.

Sabremos que hemos tenido éxito cuando al menos el 30% de los nuevos usuarios provengan de referencias directas y más del 70% de los comprobantes digitales sean utilizados como evidencia profesional, medido por el sistema de tracking del ticket digital y portafolios públicos.

#### 1.2.2.4. Lean UX Canvas

| **Business Problem** | **Solutions** | **Business Outcomes** |
|----------------------|---------------|------------------------|
| • Alta desconfianza entre clientes y desarrolladores web debido a contratos informales y falta de garantías. <br> • Riesgo de impago para el desarrollador web una vez entregado el servicio. <br> • Imposibilidad del cliente de verificar si el servicio entregado cumple con lo pactado. | • Plataforma web con contratos inteligentes que gestionan el acuerdo y pago entre las partes. <br> • Validación automática del cumplimiento del servicio antes de liberar el pago. <br> • Generación de un comprobante digital en blockchain como evidencia del servicio completado. <br> • Integración con wallets como Trust Wallet para transferencias seguras en Ethereum. | • Aumento en la confianza y transparencia en los procesos de contratación freelance. <br> • Reducción de disputas entre cliente y desarrollador. <br> • Pagos automatizados y seguros sin necesidad de intermediarios. <br> • Fortalecimiento de la reputación profesional mediante tickets digitales verificables. |

| **Users** | **User Outcomes & Benefits** |
|-----------|------------------------------|
| • Desarrolladores web que ofrecen servicios de creación de landing pages o portafolios. <br> • Profesionales que requieren una presencia digital rápida y profesional, como landing pages o portafolios. | • Mayor seguridad y confianza en el proceso de contratación. <br> • Reducción del riesgo de estafa o incumplimiento. <br> • Evidencia digital del trabajo realizado (comprobante). <br> • Interacción fluida mediante una interfaz web simple, accesible y descentralizada. |

| **Hypotheses** | **What's the most important thing we need to learn first?** | **What's the least amount of work we need to do to learn the next most important thing?** |
|----------------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| • Creemos que ofrecer un sistema descentralizado de contratación mediante contratos inteligentes permitirá reducir el riesgo de fraude y aumentar la confianza. <br> • Creemos que automatizar el proceso de validación del cumplimiento antes del pago mejorará la experiencia tanto para el cliente como para el desarrollador web. | • Validar si los desarrolladores conocen o están dispuestos a aprender sobre el uso de wallets Web3 y contratos inteligentes. <br> • Entender qué tipo de evidencia consideran válida los clientes para aceptar un servicio como "cumplido". | • Realizar encuestas rápidas a desarrolladores web sobre medios de pago actuales y problemas al cobrar. <br> • Entrevistar a clientes que hayan contratado desarrolladores web y recopilar casos donde hubo disputas o incumplimientos. |

---


## 1.3. Segmentos Objetivo

Hemos sido diseñado para atender a dos segmentos objetivos bien definidos, ambos con necesidades concretas y complementarias dentro del proceso de contratación de servicios digitales. A continuación, se describe de manera detallada el perfil de cada uno:

### Segmento 1: Profesionales que buscan crear un portafolio digital

Este segmento está conformado por profesionales independientes, egresados, emprendedores y trabajadores creativos que necesitan construir su presencia digital para proyectar su identidad profesional, ya sea a través de un portafolio web, una landing page o una página personal. Muchos de ellos no cuentan con conocimientos técnicos en desarrollo web, por lo que recurren a desarrolladores web que les ayuden a materializar su imagen profesional en línea.

Su principal motivación es contar con una página funcional, visualmente atractiva y alineada a su propósito personal o laboral. Sin embargo, al tratarse de contrataciones informales o directas, estos profesionales enfrentan inseguridad respecto al cumplimiento del servicio, ya que no siempre hay un mecanismo que garantice la entrega del producto o que actúe como respaldo en caso de incumplimiento. Es por ello que buscan una alternativa más confiable y segura que les permita contratar sin temor a ser estafados y con evidencia de que el producto ha sido entregado correctamente.

### Segmento 2: Desarrolladores web

Este segmento incluye a estudiantes, egresados y profesionales técnicos dedicados al desarrollo web, especialmente aquellos que ofrecen servicios como la creación de landing pages y portafolios. Muchos de ellos utilizan redes sociales, comunidades en línea o referencias personales para conseguir clientes, pero enfrentan constantes dificultades para garantizar el pago justo por sus servicios.

Los desarrolladores de este segmento valoran herramientas que les permitan formalizar el acuerdo con el cliente sin necesidad de recurrir a plataformas costosas que cobran altas comisiones. Les interesa trabajar en entornos confiables que aseguren la recepción del pago únicamente después de haber cumplido con lo pactado. Asimismo, les resulta valioso contar con un comprobante digital que respalde su trabajo y que pueda ser usado como parte de su reputación profesional.



---

## Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

A continuación se presentan tres competidores relevantes que ofrecen soluciones similares o complementarias al modelo de SmartWebContracts:

| *Nombre del Competidor* | *Descripción*                                                                                                         | *Enlace*                                |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| *Upwork*                | Plataforma global para contratar freelancers, que actúa como intermediario en pagos y entregas.                         | [https://www.upwork.com](https://www.upwork.com) |
| *Braintrust*            | Red descentralizada para conectar freelancers con empresas mediante tecnología blockchain, sin comisiones.             | [https://www.usebraintrust.com](https://www.usebraintrust.com) |
| *LaborX*             | Plataforma freelance basada en blockchain que conecta a freelancers con clientes mediante contratos inteligentes y pagos en criptomonedas.              | [https://laborx.com](https://laborx.com) |

#### 2.1.1. Análisis competitivo

<table border="1" cellspacing="0" cellpadding="6">

<!-- Título -->
<tr>
  <th colspan="6" align="left">Competitive Analysis Landscape</th>
</tr>

<!-- Propósito del análisis -->
<tr>
  <td rowspan="2"><strong>¿Por qué llevar a cabo este análisis?</strong></td>
  <td colspan="5">Para comprender cómo se posiciona SmartWebContracts frente a sus principales competidores, identificando fortalezas, debilidades, oportunidades y amenazas que guíen su estrategia de crecimiento.</td>
</tr>
<tr></tr>

<!-- Cabecera de competidores -->
<tr>
  <td colspan="2"><strong>Competidores</strong></td>
  <td><img src="https://i.imgur.com/B8L5Fyd.png" width="80"><br><strong>SmartWebContracts</strong></td>
  <td><img src="https://play-lh.googleusercontent.com/PgAl0V1pWvER7X9ViFrBaT9Pxye4pRH5Nr9JlD5RbKjNX0bcMRp007dQhd17b0Y28Rwv" width="80"><br><strong>Upwork</strong></td>
  <td><img src="https://cdn-1.webcatalog.io/catalog/braintrust/braintrust-icon-filled-256.png?v=1714773455724" width="80"><br><strong>Braintrust</strong></td>
  <td><img src="https://media.licdn.com/dms/image/v2/C510BAQFtd5XIGbRKNA/company-logo_200_200/company-logo_200_200/0/1630628219536/laborxnews_logo?e=2147483647&v=beta&t=rUd2fHDRcAVvXU4XgVSAUOsnb6pLzH5iJ-5Bhmv_NMM" width="80"><br><strong>LaborX</strong></td>
</tr>

<!-- Overview -->
<tr>
  <td rowspan="1"><strong>Perfil</strong></td>
  <td>Overview</td>
  <td>Plataforma Web3 universitaria que automatiza acuerdos entre desarrolladores web y clientes mediante contratos inteligentes en blockchain.</td>
  <td>Marketplace freelance global con comisiones por intermediación y reputación consolidada.</td>
  <td>Plataforma descentralizada de trabajo freelance con gobernanza comunitaria y sin comisiones.</td>
  <td>Plataforma de contratación freelance basada en blockchain que permite acuerdos mediante contratos inteligentes y pagos en cripto.</td>
</tr>

<!-- Perfil de Marketing -->
<tr>
  <td rowspan="3"><strong>Perfil de Marketing</strong></td>
  <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
  <td>Contratos inteligentes automáticos, validación en blockchain y comprobante digital como evidencia de cumplimiento.</td>
  <td>Acceso a clientes internacionales, protección de pagos y reputación digital.</td>
  <td>Modelo sin comisiones, autogestión vía DAO y enfoque transparente.</td>
  <td>Pagos en cripto, sin intermediarios, libertad contractual entre partes.</td>
</tr>
<tr>
  <td>Mercado objetivo</td>
  <td>Freelancers web y profesionales que buscan presencia digital funcional y segura.</td>
  <td>Freelancers de diversas áreas y empresas globales.</td>
  <td>Empresas tecnológicas medianas y grandes que contratan talento remoto Web3.</td>
  <td>Freelancers y clientes familiarizados con el ecosistema cripto y descentralizado.</td>
</tr>
<tr>
  <td>Estrategias de marketing</td>
  <td>Workshops, contenido educativo sobre Web3, alianzas en universidades y comunidades tech.</td>
  <td>Publicidad pagada, posicionamiento en motores de búsqueda y reviews.</td>
  <td>Promoción comunitaria mediante DAO y presencia en eventos cripto.</td>
  <td>Alianzas con ecosistemas blockchain, recompensas por reputación y visibilidad Web3.</td>
</tr>

<!-- Perfil de Producto -->
<tr>
  <td rowspan="3"><strong>Perfil de Producto</strong></td>
  <td>Productos & Servicios</td>
  <td>Creación de contratos inteligentes personalizados, validación automatizada, emisión de comprobante digital.</td>
  <td>Contratación freelance, resolución de disputas y gestión de proyectos.</td>
  <td>Conexión descentralizada, reputación comunitaria, gobernanza abierta.</td>
  <td>Mercado freelance Web3 con contratos inteligentes preconfigurados y pagos automatizados.</td>
</tr>
<tr>
  <td>Precios & Costos</td>
  <td>Comisión baja por contrato validado, sin intermediarios.</td>
  <td>Comisión entre 5% y 20% por proyecto gestionado.</td>
  <td>Sin comisiones, modelo basado en token.</td>
  <td>Pagos en cripto, sin comisiones por intermediación.</td>
</tr>
<tr>
  <td>Canales de distribución (Web y/o Móvil)</td>
  <td>Web app con integración a Metamask, Trust Wallet y otras wallets Web3.</td>
  <td>Web + App móvil, con sistema de notificaciones y mensajería.</td>
  <td>Plataforma Web3 conectada a DAO y wallets.</td>
  <td>Plataforma Web3 accesible desde navegador y mobile-friendly.</td>
</tr>

<!-- Análisis SWOT -->
<tr>
  <td rowspan="5"><strong>Análisis SWOT</strong></td>
  <td colspan="5">Fortalezas, debilidades, oportunidades y amenazas de la startup y sus competidores principales.</td>
</tr>
<tr>
  <td>Fortalezas</td>
  <td>Descentralización, seguridad, automatización, validez en blockchain, foco educativo.</td>
  <td>Escalabilidad, reputación consolidada, herramientas robustas.</td>
  <td>Modelo sin fees, participación comunitaria, escalabilidad DAO.</td>
  <td>Libertad para establecer condiciones entre partes, visibilidad cripto, foco Web3.</td>
</tr>
<tr>
  <td>Debilidades</td>
  <td>Curva de aprendizaje blockchain, baja adopción inicial, barrera tecnológica.</td>
  <td>Comisiones altas, modelo centralizado, dependencia de la plataforma.</td>
  <td>Complejidad para usuarios nuevos, limitada difusión LATAM.</td>
  <td>Baja adopción general fuera de la comunidad cripto.</td>
</tr>
<tr>
  <td>Oportunidades</td>
  <td>Educación Web3, expansión en LATAM, alianzas académicas.</td>
  <td>Verticalización en nichos freelance.</td>
  <td>Expansión hacia modelos de talento corporativo descentralizado.</td>
  <td>Crecimiento del uso de criptomonedas y plataformas autónomas.</td>
</tr>
<tr>
  <td>Amenazas</td>
  <td>Desinformación tecnológica, resistencia a blockchain, regulación.</td>
  <td>Competencia descentralizada emergente.</td>
  <td>Regulación cripto, saturación de plataformas.</td>
  <td>Volatilidad cripto, posibles bloqueos regulatorios en ciertos países.</td>
</tr>

</table>

#### 2.1.2. Estrategias y tácticas frente a competidores
Nuestras estrategias y tácticas frente a la competencia se enfocan en diferenciar nuestra propuesta mediante el uso de tecnología blockchain y en brindar una experiencia accesible, segura y descentralizada.

- Para hacer frente a plataformas consolidadas como Upwork, nos enfocaremos en ofrecer contratos inteligentes automatizados que aseguren cumplimiento y confianza sin necesidad de intermediarios.
- Aprovecharemos la baja presencia de soluciones Web3 en Latinoamérica ofreciendo una plataforma localizada, con enfoque educativo y pensada para el contexto de freelancers emergentes.
- Frente a las fortalezas de los competidores, nuestra táctica será ofrecer una propuesta más transparente, sin comisiones ocultas, con validación automática y soporte para comprobantes digitales.
- Para abordar debilidades del mercado, nos posicionaremos como una alternativa moderna, descentralizada y especialmente útil para quienes inician su carrera freelance.
- Ante amenazas como la falta de adopción Web3 o cambios regulatorios, implementaremos estrategias de formación continua, acompañamiento al usuario y escalabilidad con tecnologías de bajo costo como soluciones L2 o blockchains más eficientes.

Estas estrategias permitirán que SmartWebContracts se consolide como una opción innovadora y confiable en la contratación de servicios freelance en entornos digitales.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

Con el objetivo de comprender a profundidad las necesidades, expectativas, motivaciones y frustraciones de nuestros usuarios potenciales, se diseñaron entrevistas cualitativas semiestructuradas para los dos segmentos objetivo de SmartWebContracts:

---

### Segmento 1: Desarrolladores Web 

*Objetivo de la entrevista:*  
Entender cómo gestionan sus servicios, cómo cobran, qué problemas enfrentan al cerrar acuerdos, y su familiaridad con herramientas Web3.

*Datos demográficos y de contexto a recolectar:*  
- Edad  
- Nivel de estudios  
- Ciudad de residencia  
- Años de experiencia como desarrollador  
- Canales que usan para conseguir clientes  
- Herramientas digitales que utilizan  
- Conocimiento o uso previo de wallets y blockchain  

*Preguntas principales:*  
1. ¿Cuánto tiempo llevas trabajando como desarrollador web?  
2. ¿Cómo sueles conseguir a tus clientes?  
3. ¿Cómo estableces acuerdos de pago? ¿Has tenido problemas para cobrar?  
4. ¿Con qué frecuencia enfrentas retrasos o impagos?  
5. ¿Conoces o has usado alguna vez tecnología blockchain o contratos inteligentes?  
6. ¿Qué tan dispuesto estarías a utilizar una herramienta que automatice estos acuerdos?

*Preguntas complementarias:*  
- ¿Qué importancia le das a tener respaldo o evidencia de cumplimiento de tu trabajo?  
- ¿Qué te generaría más confianza al iniciar un nuevo proyecto con un cliente?  
- ¿Qué canales digitales usas más: WhatsApp, Discord, Telegram, otros?

---

###  Segmento 2: Profesionales que buscan portafolio digital

*Objetivo de la entrevista:*  
Identificar las motivaciones y miedos al contratar servicios de desarrollo web, su experiencia previa, y expectativas de seguridad y cumplimiento.

*Datos demográficos y de contexto a recolectar:*  
- Edad  
- Profesión actual  
- Objetivo del sitio web (marca personal, negocio, CV, etc.)  
- Nivel de conocimiento tecnológico  
- Medios por los que busca desarrolladores  
- Canales de pago preferidos  
- Nivel de confianza al contratar por redes

*Preguntas principales:*  
1. ¿Has contratado alguna vez a un desarrollador web? ¿Cómo fue la experiencia?  
2. ¿Cuál es tu mayor temor al contratar servicios freelance por internet?  
3. ¿Qué tipo de garantías o pruebas necesitas antes de pagar por un servicio digital?  
4. ¿Te sentirías más seguro si el pago solo se libera cuando el servicio se cumple correctamente?  
5. ¿Te resulta familiar el concepto de blockchain o contratos inteligentes?

*Preguntas complementarias:*  
- ¿Qué dispositivos usas normalmente para gestionar tus contrataciones digitales?  
- ¿A qué medios recurres para buscar desarrolladores (grupos, plataformas, contactos)?  
- ¿Qué elementos te harían sentir más seguridad al contratar digitalmente?

---

Este diseño permitirá obtener tanto información *cuantitativa básica* (demográfica y de hábitos), como *cualitativa clave* (objetivos, frustraciones, necesidades), la cual será útil para construir los *arquetipos de usuario* y tomar decisiones sobre el diseño del producto.

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding

Usaremos las herramientas de User Persona, User Task Matrix, User Journey Mapping, Empathy Mapping y As-is Scenario Mapping para tener una visión general de las experiencias de nuestros usuarios.

#### 2.3.1. User Personas

##### User Persona Desarrollador Freelance

![User Persona Freelance](assets/img/chapter-2/user-persona-developer.png)

##### User Persona Profesional

![User Persona Dueño](assets/img/chapter-2/user-persona-owner.png)

#### 2.3.2. User Task Matrix

A continuación mostramos la User Task Matrix, en la que podremos observar las tareas más importantes que realizan los segmentos objetivos en sus jornadas normales.

| Task                                       | Desarrollador Freelance (Frecuencia/Importancia) | Profesionales que desea un portafolio digital (Frecuencia/Importancia) |
|--------------------------------------------|-----------------------------------------------|----------------------------------------|
| Búsqueda de nuevos proyectos               | Alta/Alta                                    | Baja/Baja                             |
| Negociación con clientes                   | Alta/Alta                                    | Media/Media                           |
| Gestión de proyectos                       | Alta/Alta                                    | Media/Alta                            |
| Creación de landing pages                  | Alta/Alta                                    | Media/Alta                            |
| Comunicación con clientes                  | Alta/Alta                                    | Media/Media                           |
| Aprendizaje y mejora de habilidades        | Alta/Alta                                    | Baja/Baja                             |
| Desarrollo de aplicaciones web             | Alta/Alta                                    | Baja/Media                            |
| Gestión de pagos y presupuestos            | Media/Media                                  | Alta/Alta                             |
| Planificación de tareas y plazos           | Alta/Alta                                    | Media/Alta                            |
| Evaluación de la satisfacción del cliente  | Media/Media                                  | Alta/Alta                             |
| Mejora de portafolio                       | Alta/Alta                                    | Alta/Alta                             |
| Investigación de nuevas tecnologías        | Alta/Alta                                    | Baja/Baja                             |
| Supervisión de la calidad del trabajo      | Alta/Alta                                    | Baja/Baja                             |
| Asesoría técnica a clientes                | Media/Alta                                   | Baja/Baja                             |
| Implementación de sistemas de gestión      | Baja/Baja                                    | Alta/Alta                             |

#### 2.3.3. User Journey Mapping

En esta sección se exponen los Journey Mappings, explicando las etapas principales del proceso de los segmentos objetivo:

##### User Journey Mapping Desarrollador Freelance

![User Journey Mapping Freelance](assets/img/chapter-2/user-journey-mapping-developer.png)

##### User Journey Mapping Profesional

![User Journey Mapping Dueño](assets/img/chapter-2/user-journey-mapping-owner.png)

#### 2.3.4. Empathy Mapping

En esta sección se exponen los Empathy Mappings, en los cuales intentamos comprender la situación. los problemas, las necesidades y los retos que enfrenta cada segmento objetivo:

##### Empathy Mapping Desarrollador Freelance

![Empathy Mapping Freelance](assets/img/chapter-2/empathy-mapping-developer.png)

##### Empathy Mapping Profesional

![Empathy Mapping Dueño](assets/img/chapter-2/empathy-mapping-owner.png)

#### 2.3.5. As-is Scenario Mapping  
*Segmento: Desarrollador Web *

Durante la investigación, se realizó un ejercicio de As-is Scenario Mapping para entender el flujo actual de trabajo del usuario objetivo, sus acciones, pensamientos y emociones en cada fase del proceso. Se utilizó una matriz con cuatro filas: Phases, Doing, Thinking y Feeling, y se identificaron áreas positivas , negativas  y desconocidas.

---
![user persona de propietario de estacionamiento](assets/img/chapter-2/WebDevs-Scenario%20mapping.png)

###  Positive points:
- *Desarrollo del proyecto*: El usuario suele estar motivado durante esta etapa, ya que disfruta aplicar sus conocimientos y ver avances tangibles.
- *Entrega final*: Confía en su trabajo y siente que el producto tiene valor para el cliente.

###  Negative points:
- *Contacto y acuerdo informal*: No existen mecanismos formales de validación ni registro del acuerdo.
- *Cobro del servicio*: El pago depende de la confianza, y muchos freelancers reportan impagos o demoras frecuentes.
- *Falta de garantía*: No hay forma automática de asegurar el cumplimiento del cliente o proteger al desarrollador.

###  Blank points:
- “¿Será un cliente serio?” → Es necesario investigar qué elementos generan confianza inicial en un posible cliente.
- “¿Le gustará el diseño?” → Se requiere entender cómo el freelancer mide la aceptación del cliente y cómo reacciona a cambios no pactados.
- “¿Me pagará a tiempo?” → Hay que explorar las formas de pago actuales y los problemas más comunes que enfrentan.

---

Este mapeo revela puntos críticos en el flujo actual del desarrollador freelance, que SmartWebContracts busca transformar mediante automatización, evidencia digital y contratos inteligentes.


*Segmento: Profesional que busca un portafolio digital*

Se mapeó el proceso típico de un usuario que necesita contratar un desarrollador freelance para crear su sitio web o portafolio digital. El análisis incluyó fases clave del proceso, sus acciones, pensamientos y emociones, junto con áreas positivas , negativas  y desconocidas .

---

![user persona de propietario de estacionamiento](assets/img/chapter-2/Clientes_ScenarioMapping.png)


###  Positive points:
- *Entrega del sitio web*: El cliente se siente satisfecho al ver una entrega concreta, especialmente si visualmente cumple con lo que esperaba.

###  Negative points:
- *Búsqueda y contacto inicial*: El proceso es informal y no brinda seguridad. La mayoría lo hace por redes sin referencias verificables.
- *Definición y pago*: No existe garantía ni contrato. Hay riesgo de perder el dinero o de no recibir lo que esperaba.
- *Post-pago*: No hay evidencia de cumplimiento. Si hay problemas, el cliente no tiene cómo reclamar formalmente.

###  Blank points:
- “¿Estará entendiendo bien lo que necesito?” → Es clave saber cómo validan el entendimiento del servicio antes de contratar.
- “¿Y si tengo que reclamar algo después del pago?” → Se debe explorar qué nivel de respaldo busca el cliente tras realizar el pago.
- “No tengo cómo comprobar que me entregará algo útil.” → Necesitamos entender qué criterios usa para confiar en un proveedor digital.

---

Este mapeo evidencia las principales tensiones y vacíos que experimentan los usuarios al contratar desarrolladores informales. SmartWebContracts propone resolver estas fricciones ofreciendo *respaldo digital, validación automática y garantías integradas* mediante tecnología blockchain

#### 2.4. Ubiquitous Language

A continuación, se presenta un glosario con los términos clave que forman parte del lenguaje ubicuo del dominio de SmartWebContracts. Este lenguaje común es utilizado por todos los miembros del equipo, stakeholders y usuarios, con el objetivo de evitar ambigüedades y alinear la comunicación alrededor del problema y la solución propuesta.

| Término (Inglés)            | Término (Español)               | Definición                                                                                   |
|-----------------------------|----------------------------------|----------------------------------------------------------------------------------------------|
| Smart Contract              | Contrato inteligente            | Acuerdo digital autoejecutable entre dos partes que se activa cuando se cumplen ciertas condiciones. Se utiliza para automatizar el cumplimiento de servicios freelance. |
| Freelancer                  | Trabajador independiente         | Profesional que ofrece servicios por proyecto, sin relación de dependencia con una empresa.  |
| Digital Portfolio           | Portafolio digital              | Sitio web que muestra el trabajo, habilidades y experiencia de un profesional de manera visual y estructurada. |
| Service Agreement           | Acuerdo de servicio             | Compromiso pactado entre el cliente y el desarrollador sobre el alcance, tiempos y condiciones del trabajo. |
| Evidence of Delivery        | Evidencia de entrega            | Prueba digital verificable de que el servicio fue realizado conforme a lo pactado. Puede incluir enlaces, hashes en blockchain o tickets de cumplimiento. |
| Dispute Resolution          | Resolución de disputas          | Mecanismo mediante el cual se gestionan desacuerdos entre cliente y desarrollador sobre el cumplimiento del servicio. |
| Verified Payment Release    | Liberación de pago verificada   | Proceso automático que transfiere el dinero al desarrollador solo cuando se valida que el servicio fue entregado correctamente. |
| Web3 Onboarding             | Incorporación a Web3            | Proceso educativo y de soporte para que los usuarios aprendan a utilizar wallets y tecnologías descentralizadas. |
| Digital Trust               | Confianza digital               | Percepción de seguridad, transparencia y cumplimiento que un usuario tiene al contratar o vender un servicio por medios digitales. |
| Reputation System           | Sistema de reputación           | Mecanismo que permite evaluar y mostrar el historial de cumplimiento y calidad de los usuarios dentro de la plataforma. |

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

### 3.2. User Stories

### 3.3. Impact Mapping

### 3.4. Product Backlog

## Capítulo IV: Strategic-Level Software Design

### 4.1. Strategic-Level Attribute-Driven Design

#### 4.1.1. Design Purpose

#### 4.1.2. Attribute-Driven Design Inputs

##### 4.1.2.1. Primary Functionality (Primary User Stories)

##### 4.1.2.2. Quality attribute Scenarios

##### 4.1.2.3. Constraints

#### 4.1.3. Architectural Drivers Backlog

#### 4.1.4. Architectural Design Decisions

#### 4.1.5. Quality Attribute Scenario Refinements

### 4.2. Strategic-Level Domain-Driven Design

#### 4.2.1. EventStorming

#### 4.2.2. Candidate Context Discovery

#### 4.2.3. Domain Message Flows Modeling

#### 4.2.4. Bounded Context Canvases

#### 4.2.5. Context Mapping

### 4.3. Software Architecture

#### 4.3.1. Software Architecture System Landscape Diagram

#### 4.3.2. Software Architecture Context Level Diagrams

#### 4.3.3. Software Architecture Container Level Diagrams

#### 4.3.4. Software Architecture Deployment Diagrams

---

## Conclusiones
### Conclusiones y recomendaciones

## Bibliografia

## Anexos
