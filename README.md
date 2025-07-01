# 🌍 Dashboard del Mercado Global de Empleos en IA – 2025

Este proyecto es un dashboard interactivo desarrollado en **Power BI** que analiza más de 15,000 ofertas laborales en el sector de **Inteligencia Artificial (IA)** a nivel global. A través de visualizaciones dinámicas y KPIs, se identifican las **tendencias de salario**, **tipos de contratación**, **niveles de experiencia** y las **habilidades técnicas más requeridas** por las empresas en 2025.

---

## 🎯 Objetivo del Proyecto

Diseñar un tablero analítico que permita visualizar, de forma clara y dinámica, las características del mercado laboral en IA. Se busca responder preguntas como:

- ¿Cuáles son los niveles de experiencia mejor remunerados?
- ¿Qué tipo de contrato es más común en este sector?
- ¿Qué países lideran la oferta de empleo en IA?
- ¿Qué tecnologías y habilidades son más demandadas?

---

## 🧠 Proceso de Desarrollo

### 1. **Preparación y limpieza de datos**
- Fuente: Dataset extraído de [Kaggle – AI Job Market 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
- Eliminación de registros vacíos e inconsistentes.
- Transformación de columnas codificadas (`Experience_Level`, `Employment_Type`) a etiquetas legibles:
  - `EN` → Entry-level
  - `MI` → Mid-level
  - `SE` → Senior-level
  - `EX` → Executive-level
- División de las habilidades técnicas (skills) por fila para análisis de frecuencia.

### 2. **Modelado en Power BI**
- Relaciones simples con una única tabla de hechos (dataset principal).
- Uso de medidas DAX para calcular indicadores clave:
  - `Salario promedio`, `máximo`, `mínimo`
  - `Conteo de empleos por país`, `tipo de contrato` y `nivel de experiencia`
- Segmentadores (slicers) para filtrar por país, experiencia, tipo de contrato, etc.

### 3. **Visualizaciones**
- **Tarjetas KPI y Gráfico de Áreas**: salario promedio, máximo y mínimo.
- **Gráfico de barras horizontales**: top países por salario promedio.
- **Gráfico de columnas**: distribución de empleos por experiencia.
- **Gráfico de anillos**: porcentaje de tipos de contrato.
- **Gráfico de barras verticales**: habilidades más mencionadas.
- Diseño limpio, minimalista y de rápida interpretación.

---

## 📊 Principales Insights Descubiertos

- El salario promedio varía significativamente según el nivel de experiencia, destacando el rango Executive.
- La mayoría de ofertas son para trabajos **full-time** y **por contrato**, indicando una fuerte presencia global.
- Las **habilidades más demandadas** incluyen **Python**, **SQL**, **Kurbenetes**, y herramientas en la nube como **AWS**.
- Países como **Suiza**, **Dinamarca** y **Noruega** lideran la cantidad de ofertas con mejores sueldos.

---

## 📁 Archivos del proyecto

| Archivo | Descripción |
|--------|-------------|
| `dashboard-ai-job-market-2025.pbix` | Archivo principal del dashboard en Power BI |
| `dashboard-ai-job-market-2025-v2.pbix` | Archivo final del dashboard en Power BI |
| `ai_job_market_2025.csv` | Dataset base utilizado para el análisis |
| `Dashboard Principal.png` | Captura del primer dashboard |
| `Dashboard Final.png` | Captura del dashboard completo |
| `kpis.png` | Captura del dashboard completo |

---

## 🧰 Herramientas utilizadas

- Power BI Desktop  
- Power Query  
- Lenguaje DAX  
- Kaggle (fuente de datos)  
- Excel (para revisión previa de los datos)

---

## 👨‍💻 Autor

**Marcelo Payano Guzmán**  
Estudiante de Computación e Informática – Cibertec  
Practicante de Data Analyst | Apasionado por la visualización de datos y el análisis de información para la toma de decisiones.  
✉️ marcelitoguzman63@gmail.com



