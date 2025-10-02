# Proyecto-de-aula-Aprendizaje-de-Maquinas-Aplicado
Repositorio de Entregas Proyecto Aprendizaje de Máquinas Aplicado

# 📊 TripAdvisor Hotel Reviews - Baseline Model

Este repositorio contiene el desarrollo de un **Proyecto** para la predicción de calificaciones (**Rating**) de reseñas de hoteles en **TripAdvisor** a partir del contenido textual de las opiniones. El trabajo hace parte de un proyecto académico en el marco de la Maestría en Ciencias de Datos y Analítica de la Universidad EAFIT.

---

## Descripción del proyecto
El objetivo principal es construir un modelo de **clasificación supervisada multiclase** que permita asignar una calificación (1 a 5 estrellas) a una reseña textual.
---

## Dataset
- **Fuente:** Dataset público *TripAdvisor Hotel Reviews* (Disponible en Kaggle o repositorios abiertos).
- **Variables principales:**
  - `Review`: Texto de la reseña del usuario.
  - `Rating`: Calificación numérica entre 1 y 5 estrellas (variable objetivo).
- **Características relevantes:**
  - Contiene mas de 20.000 observaciones.
  - Distribución desbalanceada hacia ratings altos (4 y 5 estrellas).
  - Gran variabilidad en la longitud de las reseñas.

---

## Análisis exploratorio (EDA)
- El dataset muestra **desbalance de clases**, con predominio de calificaciones positivas.
- La longitud de las reseñas es heterogénea: desde comentarios cortos hasta descripciones extensas.
- El análisis de palabras frecuentes reveló asociaciones claras con sentimientos positivos (“excellent”, “friendly”) y negativos (“dirty”, “poor”).

---
