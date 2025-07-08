# FDS2025-1-258
Trending YouTube Video Statistics
# 📊 Análisis de Videos en Tendencia — YouTube Canadá 🇨🇦

Repositorio oficial para el proyecto de la sección **FDS-2025-1-256** (o la que corresponda).

---

## 📌 Tabla de Contenidos

- [1. 🎯 Introducción](#1-🎯-introducción)
- [2. 👥 Integrantes del Grupo y Roles](#2-👥-integrantes-del-grupo-y-roles)
- [3. 🔍 Metodología CRISP-DM](#3-🔍-metodología-crisp-dm)
  - [3.1 Comprensión del Negocio](#31-comprensión-del-negocio)
  - [3.2 Objetivos del Proyecto](#32-objetivos-del-proyecto)
  - [3.3 Objetivos de Data Science](#33-objetivos-de-data-science)
- [4. 🗂️ Estructura del Repositorio](#4-🗂️-estructura-del-repositorio)
- [5. 📄 Descripción del Dataset](#5-📄-descripción-del-dataset)
- [6. ✅ Conclusiones](#6-✅-conclusiones)
- [7. 📜 Licencia](#7-📜-licencia)

---

## 1. 🎯 Introducción

En la actualidad, el análisis de datos desempeña un papel fundamental en la toma de decisiones estratégicas en múltiples industrias.  
Plataformas digitales como **YouTube** generan volúmenes masivos de datos diariamente, los cuales contienen información valiosa sobre las preferencias, intereses y comportamientos de los usuarios.

En este contexto, este proyecto aplica la **metodología CRISP-DM** para analizar los datos de videos en tendencia en **Canadá**, con el fin de responder a los requerimientos de información de una consultoría internacional con sede en Lima, Perú.

---

## 2. 👥 Integrantes del Grupo y Roles

| Nombre     | Rol                   | Funciones principales                                                   |
|------------|-----------------------|-------------------------------------------------------------------------|
| Marcelo    | Business Project Sponsor | Definición de objetivos, alineación con metas de negocio, validación de entregables y conclusiones. |
| Valentina  | Data Scientist        | Modelado de datos, selección de variables, entrenamiento de modelos y evaluación de métricas. |
| Leicy      | Data Engineer         | Limpieza, procesamiento, transformación y validación de datos.          |
| Anabella   | Data Analyst          | Análisis exploratorio, visualizaciones significativas e insights clave. |

---

## 3. 🔍 Metodología CRISP-DM

### 3.1 Comprensión del Negocio

Definir los objetivos del proyecto desde la perspectiva de negocio para entender los factores que influyen en la popularidad de videos en **YouTube Canadá**.

---

### 3.2 Objetivos del Proyecto

- Identificar categorías y características más asociadas al éxito de un video.
- Detectar patrones en la interacción del público (likes, dislikes, comentarios) en los videos más vistos.
- Estimar o predecir el número de likes usando variables relacionadas.
- Extraer insights accionables para creadores, agencias de marketing y anunciantes.

---

### 3.3 Objetivos de Data Science

- Aplicar árbol de decisión de regresión para predecir el número de **likes**.
- Usar variables independientes como **views**, **comment_count** y **channel_title**.
- Limpiar y pre-procesar datos, analizar correlaciones y variables predictivas.
- Evaluar desempeño con **MAE**, **RMSE** y **R²**.
- Responder a los requerimientos de la consultoría internacional.

---
## 📄 Descripción del Dataset

Puedes ver la descripción detallada del conjunto de datos en este [PDF](.upc-2025-01-258-4-tf.pdf).
## 📌 I. Conclusiones

- ✅ El proyecto permitió comprender cómo los datos generados por **YouTube en Canadá** pueden ser analizados para identificar **patrones de popularidad, interacción y comportamiento del público** en videos en tendencia.

- 🎭 Se evidenció que categorías como **“Entertainment”**, **“Music”** y **“Comedy”** concentran gran parte del contenido viral, y que variables como **vistas, comentarios y canal de publicación** influyen directamente en la cantidad de *likes* que recibe un video.

- 🌳 Se aplicó un **modelo de árbol de regresión** para predecir el número de *me gusta*, utilizando como variables predictoras: **vistas escaladas, comentarios escalados y codificación del canal**.  
  El modelo mostró buen desempeño, con una precisión (**R²**) cercana a 1 y errores aceptables, considerando los valores extremos de *likes* que pueden superar las 100,000 interacciones.

- 🔍 A través del análisis, se confirmó una **relación positiva** entre vistas, comentarios y *likes*, indicando que cuanto mayor es la interacción del público, mayor es la probabilidad de éxito del video.  
  Esta información puede ser valiosa para **marcas, creadores de contenido y agencias** que deseen optimizar su estrategia en plataformas digitales.

- 🤝 Como equipo, se reforzó la importancia de **iterar entre fases del proceso CRISP-DM**.  
  Las decisiones de limpiar, transformar y escalar los datos fueron claves para mejorar el rendimiento del modelo.  
  Se concluye que un enfoque **colaborativo y metodológico en Data Science** puede generar conocimiento útil para la toma de decisiones basadas en datos reales.



## 4. 🗂️ Estructura del Repositorio
```plaintext
📁 data/
   ├── data_inicial.csv               # Datos sin procesar
   └── final_limpio_dataset.csv       # Datos finales limpios/preparados
   └── json_inicial.json              #Json de las categorias

📁 code/
   └── upc_2025_01_258_4_tf.ipynb       # codigo


📄 README.md                    # Este archivo


