
# Análisis de falsificación de Productos - Mercado Libre

Este repositorio contiene el análisis de un conjunto de datos de publicaciones en Mercado Libre, enfocado en la detección de productos falsificados. Se exploran variables como precio, marca, categoría y score de riesgo, identificando patrones y oportunidades para mejorar los sistemas de moderación y prevención de fraude en la plataforma.

## Objetivo

Explorar un conjunto de datos con información de moderaciones de productos publicados en Mercado Libre, con el fin de:

- Entender las características asociadas a productos falsificados.
- Identificar patrones, tendencias y posibles mejoras para el sistema de detección.
- Proponer estrategias analíticas y operativas que potencien la moderación proactiva.

## Dataset

El dataset contiene más de 40.000 publicaciones, con atributos como:

- `titulo`, `marca`, `precio`, `categoria`
- Flags como `moderado`, `fake` (falsificado), `rollback`
- `score`: probabilidad estimada de falsificación

## Principales Insights

- Las falsificaciones se concentran en pocas marcas específicas.
- Los productos falsificados tienden a tener **precios más bajos**.
- Algunos casos de moderación fueron revertidos (rollback).
- Score y precio podrían ser buenas variables predictivas para modelos.

## Visualizaciones

- Incluidas en el Rmarkdown (Job_Mercado_Libre1.Rmd)

## Próximos pasos y recomendaciones, reflexiones finales
- Incluidos en el Análisisyrecomendaciones.pdf


## Estructura del repo

```
├── Job.Rmd         # Análisis exploratorio y visualizaciones, Modelo de regresión logística, Validación del modelo
├── Análisisyrecomendaciones.pdf
├── README.md

```

---
**Autor:** Pablo César Prada Luna  
**Fecha:** Abril 23, 2025
