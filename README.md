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
│  └─ processed/    # (vacío en GitHub) Datos procesados alojados en Kaggle
├─ notebooks/        # Jupyter notebooks - para limpieza y procesdado de datos
├─ src/              # Ubicación de scripts (vacío)
├─ visualizations/
│  └─ resultado.html           # (Vacío) Export opcional para revisión rápida - Fase final del trabajo
├─ docs/
│  └─ memoria.pdf              # (Vacío) Entrega final (cuando aplique)
├─ requirements.txt
├─ README.md
└─ .gitignore          # (Vacío) Se incluirá cuando aplique


## Datos Originales
Origen de cada dataset, links y tamaño.
Los datos originales se alojan en Kaggle:
🔗 Acceso Kaggle (público):  
**URL:** [[https://www.kaggle.com/datasets/raquelahdo/ruido-datasets]]

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



> Si necesita acceso, por favor indique su usuario de Kaggle para añadirle como “Collaborator”.

## Datos Procesados
Origen de cada dataset procesado, link y tamaño
Los datos procesados se alojan en Kaggle:
🔗 Acceso Kaggle (público):  
**URL:** [[https://www.kaggle.com/datasets/raquelahdo/ruido-datasets-procesados]]

- df_01_Ruido_diario_acumulado_processed.csv (47.2 MB) - 17 columnas
- df_01_daily_plot.csv (2.87 MB) - 3 columnas
- df_01_daily_processed.csv (548.02 kB) - 3 columnas
- df_02_contaminacion_acustica_processed.csv (964.29 kB) - 17 columnas
- df_02_estacion_processed.csv (936 B) - 2 columnas
- df_03_noise_limit_processed.csv (6.08 kB) - 10 columnas
- df_05_estaciones-acusticas_processed.csv (4.64 kB) - 11 columnas
- df_06_locales_terrazas_processed.csv (33.54 MB) - 27 columnas
- df_07_Madrid-calidad-vida_processed.csv (3.33 kB) - 19 columnas
- df_07_calidad-vida_processed.csv (6.13 kB) - 18 columnas
- df_07_evolucion-calidad-vida_processed.csv (2.77 kB) - 18 columnas
- df_07_evolucion-long-calidad-vida_processed.csv (8.09 kB) - 4 columnas
- df_07_final-calidad-vida_processed.csv (17.08 kB) - 7 columnas
- df_09_distribucion-renta_processed.csv (488.52 MB) - 10 columnas
- df_09_reduced_distribucion-renta_processed.csv (186.82 kB) - 5 columnas




### Descarga local (opciones)
- **Manual:** Descargar desde la URL de Kaggle y colocar los archivos en `data/raw/`.
- **Automática:** (opcional) mediante `kaggle` CLI si está disponible en el entorno:
  ```bash
  kaggle datasets download -d USUARIO/NOMBRE-DEL-DATASET -p data/raw --unzip

  
## Instrucciones para ejecutar
1. Crear entorno instalando Anaconda
3. Ejecutar notebooks

## Preparación de datos
Abra y ejecute notebooks/
- Limpieza 01_Ruido_diario_acumulado.ipynb
- Limpieza 02_Contaminacion_acustica.ipynb
- Limpieza 03-Noise-limit.ipynb
- Limpieza 05-estaciones-acusticas.ipynb
- Limpieza 06-censo-locales.ipynb
- Limpieza 07-calidad-vida.ipynb
- Limpieza 08-salud-mental.ipynb
- Limpieza 09-ADRH-distribucion renta.ipynb

## Visualización
Fase de entrega final del proyecto

## Autoría
Alumno: Raquel Abreu
Programa: UNED – Visualización y Análisis de Datos



