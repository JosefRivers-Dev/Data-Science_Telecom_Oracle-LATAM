# Proyecto de Análisis de Datos en Telecomunicaciones

## 📌 Descripción del Proyecto
Este proyecto consiste en un análisis de datos de clientes de telecomunicaciones utilizando un cuaderno Jupyter (`Data-Science_Telecom.ipynb`). El objetivo es extraer, transformar y analizar datos para identificar patrones relacionados con la cancelación de servicios (Churn) y otros factores relevantes en la industria de telecomunicaciones.

## 📌 Estructura del Proyecto
El cuaderno está organizado en tres secciones principales:

### 1. Extracción
- **Fuentes de datos**: 
  - Datos en formato JSON (`TelecomX_Data.json`).
  - Diccionario de datos en formato Markdown (`TelecomX_diccionario.md`).
- **Procesamiento inicial**: 
  - Creación de una tabla con el diccionario de datos para comprender las columnas del dataset.

### 2. Transformación
- **Creación del DataFrame**:
  - Normalización de columnas y modificación de nombres para facilitar el análisis.
  - Cambio de nombres de columnas al español para mejor comprensión.
- **Estandarización de datos**:
  - Modificación de tipos de datos (ejemplo: conversión de `Consumo_Total` a numérico).
  - Limpieza y estandarización de valores (ejemplo: reemplazo de "No internet service" por "No" en columnas de servicios).
  - Eliminación de datos no útiles y corrección de valores atípicos.

### 3. Carga y Análisis
- **Preparación del ambiente**:
  - Importación de bibliotecas como `pandas`, `matplotlib`, y `seaborn`.
- **Visualización de datos**:
  - Gráficos para comparar servicios activos vs. cancelados.
  - Análisis de la relación entre servicios contratados y la cancelación.
- **Agrupación de datos**:
  - Segmentación por estado del servicio (`Activo` o `Cancelado`).

## 📌 Columnas Principales
El dataset contiene las siguientes columnas (traducidas al español):
- `ID_Cliente`: Identificador único del cliente.
- `Cancelacion_Servicio`: Indica si el cliente canceló el servicio (`Yes`/`No`).
- `Género`: Género del cliente (`Male`/`Female`).
- `Edad_Avanzada`: Indica si el cliente es mayor de 65 años (`Yes`/`No`).
- `Servicios contratados`: Servicio telefónico, internet, TV, streaming, etc.
- `Antigüedad_Meses`: Meses de contrato del cliente.
- `Consumo_Mensual` y `Consumo_Total`: Gastos del cliente.

## 📌 Resultados Clave
- **Estandarización exitosa**: Los datos fueron limpiados y transformados para facilitar el análisis.
- **Visualizaciones**: Se generaron gráficos para entender la distribución de servicios y su relación con la cancelación.
- **Segmentación**: Los clientes se agruparon según su estado (`Activo` o `Cancelado`) para identificar patrones.

## 📌 Conclusiones
Este proyecto proporciona una base sólida para analizar el comportamiento de los clientes en el sector telecomunicaciones, con énfasis en la retención y cancelación de servicios. Los pasos seguidos pueden replicarse para otros conjuntos de datos similares.

## 📌 Instrucciones para Ejecutar el Proyecto
1. **Requisitos**:
   - Python 3.x.
   - Bibliotecas: `pandas`, `matplotlib`, `seaborn`.
2. **Ejecución**:
   - Abrir el cuaderno Jupyter (`Data-Science_Telecom.ipynb`).
   - Ejecutar las celdas en orden para reproducir el análisis.