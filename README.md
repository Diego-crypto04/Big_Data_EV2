# Evaluación 2 Big Data: Avistamientos OVNI
**Integrantes:**  
- Liliana Heracles  
- Lidia Nuñez  
- Diego Sanhueza

**Profesor:** Fernando Fuentes  
**Sección:** 002D  

## Tabla de Contenidos

- [Introducción](#introducción)
- [Objetivo del Proyecto](#objetivo-del-proyecto)
- [Metodología](#metodología)
- [Consultas SQL destacadas](#consultas-sql-destacadas)
- [Gráficos con Looker Studio](#gráficos-con-looker-studio)
- [Resultados e insights](#resultados-e-insights)
- [Conclusión](#conclusión)
- [Anexos](#anexos)

## Introducción
El presente informe tiene como objetivo presentar el desarrollo de un proceso completo de análisis de datos en un entorno Big Data, utilizando herramientas del ecosistema de Google Cloud. La actividad se enmarca en la Evaluación Parcial N°2 del curso Big Data (AVY1101), y consiste en la construcción de un flujo de trabajo que permita la ingesta, limpieza, transformación, análisis y visualización de grandes volúmenes de datos mediante procesos batch.

Para este propósito, se utilizó un archivo con registros históricos de avistamientos de objetos voladores no identificados (OVNIs), el cual fue cargado inicialmente en Cloud Storage como parte del diseño de un Data Lake. Posteriormente, el conjunto de datos fue procesado mediante Cloud Dataprep (Alteryxs), donde se llevaron a cabo tareas de limpieza y preparación de datos para asegurar su calidad. Una vez procesado, el archivo fue cargado en una tabla del servicio BigQuery, lo que permitió ejecutar diversas consultas SQL para obtener insights relevantes.

Finalmente, se construyeron visualizaciones interactivas en Looker Studio, enfocadas en responder preguntas de negocio relacionadas con la frecuencia, ubicación y características de los avistamientos registrados. Este informe documenta cada una de las etapas del proceso, incluyendo capturas, consultas y análisis obtenidos, evidenciando el desarrollo de competencias clave en el manejo de tecnologías de Big Data.

## Objetivo del Proyecto

El objetivo principal del proyecto es diseñar y ejecutar un proceso completo de análisis de datos en un entorno Big Data, utilizando herramientas de Google Cloud Platform, con el fin de gestionar, transformar y visualizar información proveniente de un conjunto de datos sobre avistamientos de OVNIs.

## Metodología
El taller es realizado en la plataforma `Google Skill Boost`, exactamente en el `Lab GSP823`, en el cual se accede con el usuario y contraseña. Esto lleva directo al launcher del taller a realizar, en él es necesario crear un bucket, de la siguiente forma:
```
Cloud Storage -> Buckets -> Create
   ```
En el cual se crea al bucket necesario para cargar el archivo Excel (.csv) para la extracción de datos, el bucket creado tiene como nombre, el apellido de todos los integrantes del grupo de la siguiente forma:


el conjunto de datos utilizados para este proyecto corresponde a un archivo denominado ufo_sighting.csv, el cual contiene registros históricos de avistamientos de objetos voladores no identificados (OVNIs). Este dataset incluye información relevante como fecha y hora del evento (Date_time), ubicación (city, state/province, country), características del objeto (UFO_shape), duración estimada del encuentro, descripción del suceso, y coordenadas geográficas (latitude y longitude), entre otros campos.



## Consultas SQL destacadas

...

## Gráficos con Looker Studio

...

## Resultados e insights

...

## Conclusión

...

## Anexos

...





[![.github/workflows/ci.yaml](https://github.com/pages-themes/minimal/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/minimal/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-minimal.svg)](https://badge.fury.io/rb/jekyll-theme-minimal)

*Minimal is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/minimal), or even [use it today](#usage).*

![Thumbnail of Minimal](thumbnail.png)

## Usage

To use the Minimal theme:
