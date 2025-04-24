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

## Capítulo I: Introducción

### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup

#### 1.1.2. Perfiles de integrantes del equipo

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática

#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements

##### 1.2.2.2. Lean UX Assumptions

##### 1.2.2.3. Lean UX Hypothesis Statements

##### 1.2.2.4. Lean UX Canvas

### 1.3. Segmentos objetivo

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
