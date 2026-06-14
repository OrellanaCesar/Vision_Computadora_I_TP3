# TP3: Template Matching - Visión por Computadora I

Este repositorio contiene la resolución del Trabajo Práctico Nº 3 de la materia **Visión por Computadora I** (Especialidad en Inteligencia Artificial, FIUBA).

## Integrantes
* Lucia T. Capon Paul
* Cesar Orellana
* Madrid, Martin
* Leandro Britez

## Descripción
El objetivo de este TP es aplicar técnicas de **Template Matching** para la detección automática de logotipos en imágenes. El Template Matching consiste en desplazar un patrón (template) sobre una imagen de búsqueda para calcular una métrica de similitud en cada posición, permitiendo identificar las regiones donde el objeto de interés coincide con el patrón proporcionado.

## Requisitos Previos
Para la gestión de dependencias y entornos, utilizamos **uv**, una herramienta extremadamente rápida para la gestión de proyectos de Python.

### Configuración del entorno

1. **Instalar `uv`**:
   Si aún no lo tienes, puedes instalarlo siguiendo las instrucciones oficiales en [astral.sh/uv](https://astral.sh/uv).

2. **Sincronizar el proyecto**:
   Dentro de la carpeta raíz del proyecto, ejecuta el siguiente comando para instalar las dependencias definidas en `pyproject.toml` (o `uv.lock`):

   ```bash
   uv sync