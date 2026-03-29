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
Ruido-Visualizacion/
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

- **Dataset 1 (23.18MB):** `01_Ruido diario_acumulado.csv` - 11 columnas
- **Dataset 2 (694.39kB):** `02_contaminacion-acustica.csv` - 13 columnas
- **Dataset 3 (4.65kB):** `03_DF3_4F_NoiseLimitdetails.csv` - 8 columnas
- **Dataset 4 (1.23MB):** `04-Metadata_Indicator_API_ESP_DS2_en_v2_17575.csv` - 4 columnas
- **Dataset 5 (4.66kB):** `05-estaciones-acusticas.csv` - 8 columnas
- **Dataset 6 (92.55MB):** `06-200085-1-censo-locales.csv` - 46 columnas
- **Dataset 6 (5.38MB):** `06-200085-6-censo-locales.csv` - 117 columnas
- **Dataset 7 (97.56kB):** `07-datos_calidad_vida_multi.csv` - 12 Dimensiones, 20 columnas cada una
- **Dataset 8 (50.83kB):** `08-48130_salud_mental.csv` - 6 columnas
- **Dataset 9 (451.29MB):** `09-31103_ADRH_distribucion_renta_hogares.csv` - 8 columnas


🔗 Acceso Kaggle (privado para el equipo docente):  
**URL:** [[https://www.kaggle.com/datasets/raquelahdo/ruido-datasets]]

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



