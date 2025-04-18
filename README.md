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
