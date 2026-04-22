# 🧪 API Testing Project – JSONPlaceholder

---

## 🎯 Business Context

This project simulates the validation of a REST API used to manage posts in a social media-like application.

The goal of this testing effort is to ensure that the core services function correctly, maintaining data integrity, response consistency, and acceptable performance.

---

## ⚠️ Risk Areas Identified

During API analysis, the following risks were identified:

- Lack of strict response structure validation
- Potential inconsistencies in resource creation (POST)
- Missing contract validation on endpoints
- Variable performance under high response payloads

These risks could affect system reliability in a production environment.

---

## 🧪 QA Approach

The testing strategy focused on:

- REST endpoint validation (GET / POST)
- HTTP status code verification
- Response schema validation (basic structure)
- Data integrity testing
- Basic performance validation (response time)

---

## 📌 Test Scope

### In Scope
- GET /posts
- GET /posts/{id}
- POST /posts
- JSON response validation
- Required fields validation

### Out of Scope
- Authentication / Security testing
- Load testing
- Database integration
- CI/CD automation

---

## 📊 Outcome

The testing process validated the correct behavior of the main API endpoints, ensuring response consistency, data structure integrity, and expected system behavior.

----------------------------------------------------------------------------------------------------------------------------

# 🧪 Proyecto de Testing de APIs – JSONPlaceholder

---

## 🎯 Contexto de Negocio

Este proyecto simula la validación de una API REST utilizada para gestionar publicaciones dentro de una aplicación tipo red social.

El objetivo del testing es asegurar que los servicios principales funcionen correctamente, manteniendo la integridad de los datos, la consistencia de las respuestas y un rendimiento adecuado.

---

## ⚠️ Áreas de Riesgo Identificadas

Durante el análisis de la API se identificaron los siguientes riesgos:

- Respuestas sin validación estricta de estructura
- Posibles inconsistencias en la creación de recursos (POST)
- Falta de validaciones de contrato en los endpoints
- Rendimiento variable en respuestas de gran volumen

Estos riesgos pueden afectar la confiabilidad del sistema en un entorno productivo.

---

## 🧪 Enfoque de QA

La estrategia de testing se centró en:

- Validación de endpoints REST (GET / POST)
- Verificación de códigos de estado HTTP
- Validación de estructura de respuesta (schema básico)
- Pruebas de integridad de datos
- Validación de performance básica (response time)

---

## 📌 Alcance de las pruebas

### Dentro del alcance
- GET /posts
- GET /posts/{id}
- POST /posts
- Validación de respuestas JSON
- Validación de campos obligatorios

### Fuera del alcance
- Autenticación / Seguridad
- Pruebas de carga
- Integración con bases de datos reales
- Automatización CI/CD

---

## 📊 Resultado

El proceso de testing permitió validar el correcto funcionamiento de los principales endpoints, asegurando consistencia en las respuestas, estructura de datos y comportamiento esperado de la API.

---
