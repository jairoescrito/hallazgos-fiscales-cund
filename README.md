# Hallazgos Fiscales - Gobernación de Cundinamarca

Pipeline de análisis de hallazgos fiscales de auditoría para la Gobernación de Cundinamarca.

## Objetivo

Procesar, clasificar y asociar hallazgos fiscales a puntos de riesgo fiscal según el 
Catálogo Indicativo DAFP (Anexo 3, Guía para la Gestión Integral de Riesgos v7).

## Visión a largo plazo

Desarrollar un modelo de aprendizaje automático para la clasificación automática 
de hallazgos por proceso SIGC y punto de riesgo fiscal.

## Estructura del proyecto
hallazgos-fiscales-cund/
├── data/
│   ├── raw/          # Datos originales (excluidos del repo)
│   ├── processed/    # CSVs procesados
│   └── catalogo/     # Referencias DAFP
├── notebooks/        # Análisis exploratorio y pipeline
├── src/              # Módulos reutilizables
├── models/           # Modelos ML (largo plazo)
└── outputs/          # Reportes y exportaciones

## Stack tecnológico

- Python (pandas, rapidfuzz, scikit-learn)
- Jupyter Notebooks
- Power BI

## Contexto institucional

Proyecto desarrollado en el marco del contrato de Gerencia Integral de Riesgos, 
Dirección de Cultura Organizacional y Mejora Continua - DAFPC.
