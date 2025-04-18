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

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding

#### 2.3.1. User Personas

#### 2.3.2. User Task Matrix

#### 2.3.3. User Journey Mapping

#### 2.3.4. Empathy Mapping

#### 2.3.5. As-is Scenario Mapping

### 2.4. Ubiquitous Language

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
