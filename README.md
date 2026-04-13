

# 📊 Análisis de Violencia de Género en Colombia

## 🧾 Descripción

Este proyecto realiza un análisis exploratorio de datos sobre violencia de género en Colombia, integrando información de feminicidios, violencia intrafamiliar y delitos sexuales para identificar patrones temporales, geográficos y demográficos.

El objetivo principal es comprender cómo se distribuye la violencia de género y detectar tendencias que permitan apoyar la toma de decisiones basadas en datos.

---

## 🎯 Objetivos del Proyecto

* Analizar la distribución geográfica de la violencia de género
* Identificar municipios con mayor vulnerabilidad
* Evaluar tendencias temporales entre 2024 y 2025
* Comparar tipos de violencia reportados
* Identificar correlaciones entre variables
* Detectar patrones demográficos de riesgo

---

## 🗂️ Dataset

El análisis se realizó sobre una base consolidada con:

* 216,557 registros
* 37 variables
* Datos de violencia intrafamiliar
* Datos de feminicidios
* Datos de delitos sexuales

Archivo principal:

```
BD_CONSOLIDADA.xlsx
```

---

## 🔬 Metodología

El flujo de trabajo del análisis fue:

1. Integración de bases de datos
2. Limpieza y depuración de registros
3. Estandarización de variables
4. Análisis exploratorio de datos (EDA)
5. Visualización de resultados
6. Análisis de correlación estadística

---

## 📈 Análisis Realizados

* Distribución geográfica de violencia intrafamiliar
* Identificación de municipios vulnerables
* Comparación entre tipos de violencia
* Tendencia temporal de feminicidios
* Análisis de correlación de Pearson
* Análisis demográfico por edad
* Identificación de estacionalidad

---

## 🧠 Principales Hallazgos

* La violencia intrafamiliar es el tipo más frecuente
* Existe concentración en grandes ciudades
* Municipios rurales presentan posible subregistro
* Enero presenta mayor pico de feminicidios
* Mujeres entre 20 y 39 años tienen mayor riesgo
* Violencia intrafamiliar y delitos sexuales están altamente correlacionados

---

## 🛠️ Tecnologías Utilizadas

* R
* RMarkdown
* Excel
* HTML

### Librerías utilizadas

```r
library(readxl)
library(dplyr)
library(tidyr)
library(ggplot2)
library(scales)
library(kableExtra)
library(reshape2)
```

---

## 📁 Estructura del Proyecto

```
📦 proyecto-violencia-genero
 ┣ 📂 images
 ┣ 📂 rsconnect
 ┣ 📜 BD_CONSOLIDADA.xlsx
 ┣ 📜 Feminicidios.Rmd
 ┣ 📜 Feminicidios.html
 ┣ 📜 ProyectofinalF.Rproj
 ┣ 📜 logo-sena-blanco.png
 ┣ 📜 styles.css
 ┗ 📜 README.md
```

---

## 📊 Archivo Principal de Análisis

El análisis completo se encuentra en:

```
Feminicidios.Rmd
```

El reporte generado puede visualizarse en:

```
Feminicidios.html
```

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio
2. Abrir el archivo `.Rproj` en RStudio
3. Ejecutar el archivo `Feminicidios.Rmd`
4. Generar el reporte HTML

---

## 📌 Resultados

El proyecto permite:

* Identificar patrones de violencia de género
* Detectar zonas de mayor riesgo
* Analizar tendencias temporales
* Evaluar relaciones entre tipos de violencia
* Generar evidencia para toma de decisiones

---

## 👨‍💻 Autor

Proyecto desarrollado como análisis de datos utilizando R y técnicas de visualización estadística aplicado a problemáticas sociales.

---

## 📎 Notas

Este proyecto fue desarrollado con fines académicos y de análisis exploratorio de datos.


