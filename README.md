# Portafolio Web Personal en AWS

## Descripción del proyecto

Proyecto personal desarrollado en paralelo al programa **AWS Cloud 09 de Generation Chile (Administrador/a Jr. Cloud)**. El objetivo es diseñar, construir y desplegar un sitio web profesional que funcione como portafolio digital, mostrando mi experiencia, proyectos y evolución profesional mientras aplico de forma práctica los conocimientos adquiridos durante el bootcamp.

## Sobre mí

Soy **Diseñadora UX/UI en transición hacia Cloud Computing**, con interés en la creación de soluciones digitales centradas en las personas y respaldadas por infraestructura moderna en la nube.

Este proyecto integra ambas disciplinas:

* Diseño de experiencia de usuario (UX)
* Diseño de interfaces (UI)
* Arquitectura Cloud en AWS
* Desarrollo web
* Automatización y servicios serverless

Mi enfoque consiste en diseñar primero la experiencia mediante wireframes y flujos de usuario, para luego implementar soluciones técnicas escalables siguiendo buenas prácticas de la industria.

---

## Stack Tecnológico

### Frontend

* HTML5
* CSS3
* Diseño basado en wireframes propios

### Backend y lógica inicial

* Python

### Base de datos local

* PostgreSQL o MySQL

### Infraestructura Cloud

* Amazon S3 (hosting del sitio estático)
* Amazon CloudFront (CDN y distribución global)
* AWS Lambda (backend serverless)
* Amazon DynamoDB (base de datos NoSQL)

---

## Arquitectura del Proyecto

```text
Usuario
   │
   ▼
CloudFront
   │
   ▼
Amazon S3
   │
   └── Sitio web estático

Formulario de contacto
   │
   ▼
AWS Lambda
   │
   ▼
Amazon DynamoDB
```

---

## Fases del Proyecto

### Fase 1: Fundamentos (Linux y Git)

* Investigación y definición de requerimientos.
* Creación de wireframes y flujo de navegación.
* Desarrollo inicial en HTML y CSS.
* Control de versiones con Git.
* Publicación del repositorio en GitHub.

### Fase 2: Bases de Datos y Python

* Diseño del flujo del formulario de contacto.
* Implementación de la lógica en Python.
* Integración con una base de datos local.
* Pruebas funcionales y validación de datos.

### Fase 3: Servicios AWS

* Migración del sitio a Amazon S3.
* Configuración de distribución mediante CloudFront.
* Implementación de backend serverless con AWS Lambda.
* Persistencia de datos mediante DynamoDB.
* Optimización de costos utilizando el AWS Free Tier.

### Fase 4: Cierre y Consolidación

* Documentación completa de la arquitectura.
* Diagramas de infraestructura.
* Análisis de buenas prácticas basadas en el AWS Well-Architected Framework.
* Preparación para la certificación AWS Certified Cloud Practitioner.

---

## Decisiones de Diseño y Arquitectura

### Diseño centrado en el usuario

Antes de escribir código, se realiza un proceso de planificación mediante wireframes y flujos de usuario para garantizar una experiencia intuitiva y consistente.

### Optimización de costos

Todas las decisiones técnicas consideran las limitaciones del **AWS Free Tier**, permitiendo desarrollar experiencia práctica en la nube sin generar costos innecesarios.

### Buenas prácticas Cloud

La arquitectura se construye siguiendo como referencia los pilares del **AWS Well-Architected Framework**:

* Excelencia operacional
* Seguridad
* Fiabilidad
* Eficiencia de rendimiento
* Optimización de costos
* Sostenibilidad

---

## Estado Actual

**En desarrollo**
📅 Inicio del proyecto: **30 de julio de 2026**
🎯 Objetivo final: desplegar un portafolio profesional completamente funcional en AWS y consolidar conocimientos para el camino hacia la certificación **AWS Certified Cloud Practitioner**.

### Competencias demostradas

* UX Research y UX Design
* UI Design
* HTML y CSS
* Git y GitHub
* Linux
* Python
* Bases de datos relacionales
* AWS S3
* AWS CloudFront
* AWS Lambda
* AWS DynamoDB
* Arquitectura Cloud
* Serverless Computing
* Documentación técnica
