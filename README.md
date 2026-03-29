# Ruido-Visualizacion
Practica informática de la asignatura Visualización y Análisis de Datos

Este repositorio contiene el código, notebooks y documentación del proyecto de Visualización y Análisis de Datos (UNED).  
La visualización principal se desarrolla en Python con Altair y se entrega en formato notebook/HTML.  
Debido al tamaño de los datos de origen, los **datasets grandes** se alojan en **Kaggle**.

## Objetivo
- Diseñar una visualización clara y reproducible aplicando buenas prácticas de diseño.
- Implementar el flujo de preparación de datos (limpieza, transformación, verificación).
- Entregar una visualización ejecutable por terceros (equipo docente).

# Objetivo de la visualización
Descripción del objetivo global y los secundarios.

## Estructura del repositorio
Breve explicación de las carpetas.
proyecto-visualizacion/
├─ data/
│  ├─ raw/          # (vacío en GitHub) Datos originales alojados en Kaggle
│  ├─ interim/      # Transformaciones intermedias (si <50MB)
│  └─ processed/    # Datos finales listos para la visualización (si <50MB)
├─ notebooks/
│  ├─ 01_exploracion.ipynb
│  └─ 02_visualizacion_altair.ipynb
├─ src/
│  ├─ cleaning.py
│  ├─ load_data.py
│  └─ utils.py
├─ visualizations/
│  └─ resultado.html           # Export opcional para revisión rápida
├─ docs/
│  └─ memoria.pdf              # Entrega final (cuando aplique)
├─ requirements.txt
├─ README.md
└─ .gitignore


## Datos
Origen de cada dataset, links y tamaño.
Los datos originales se alojan en Kaggle:

- **Dataset 1 (200MB):** `data01_raw.csv`  
- **Dataset 2 (200MB):** `data02_raw.csv`

🔗 Acceso Kaggle (privado para el equipo docente):  
**URL:** [[https://www.kaggle.com/datasets/raquelahdo/ruido-dat]](https://www.kaggle.com/datasets/raquelahdo/ruido-dat)

> Si necesita acceso, por favor indique su usuario de Kaggle para añadirle como “Collaborator”.

### Descarga local (opciones)
- **Manual:** Descargar desde la URL de Kaggle y colocar los archivos en `data/raw/`.
- **Automática:** (opcional) mediante `kaggle` CLI si está disponible en el entorno:
  ```bash
  kaggle datasets download -d USUARIO/NOMBRE-DEL-DATASET -p data/raw --unzip

  
## Instrucciones para ejecutar
1. Crear entorno
2. Instalar requirements.txt
3. Ejecutar notebook

## Visualización
Abra y ejecute notebooks/02_visualizacion_altair.ipynb
Enlace a la versión HTML visualizations/resultado.html


## Autoría
Alumno: Raquel Abreu
Programa: UNED – Visualización y Análisis de Datos



