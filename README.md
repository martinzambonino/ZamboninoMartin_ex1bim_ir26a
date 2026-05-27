# Examen Primer Bimestre - Sistema de Recuperación de Información

## Descripción

Este repositorio contiene el notebook del examen de primer bimestre de Recuperación de Información.

El trabajo implementa un sistema de recuperación de información usando embeddings y similitud coseno sobre el dataset **Rotten Tomatoes Movies and Critic Reviews** de Kaggle.

El notebook incluye:

- carga del corpus;
- selección de campos textuales;
- preprocesamiento del texto;
- generación de embeddings;
- recuperación de documentos mediante similitud coseno;
- ejecución de las 8 consultas solicitadas;
- tablas Top-k por consulta;
- tabla resumen general;
- visualización de embeddings con PCA como mejora adicional.

## Dataset usado

El dataset se descarga directamente desde Kaggle usando `kagglehub`.

Dataset:

```python
stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset