# Tarea Integradora: Análisis Predictivo y de Segmentación para Decisiones de Inversión

## 🎯 Objetivo General

Asesorar a un inversionista que busca maximizar sus oportunidades en el mercado inmobiliario o de distribución de combustibles, utilizando herramientas de aprendizaje automático supervisado y no supervisado.

## 📊 Conjuntos de Datos Disponibles
 1.	Precios de propiedades residenciales extraídos de Zillow (variables disponibles: precio, ubicación, número de habitaciones, baños, superficie, año de construcción, etc.)
 2.	Precios diarios de gasolina en estaciones de servicio de México (variables: estación, ubicación, tipo de combustible, entre otras)

Los estudiantes elegirán uno de los conjuntos de datos y aplicarán una de las dos técnicas analizadas en clase: regresión o clustering. Los datos que puedes usar están disponibles en: https://drive.google.com/drive/folders/1tRHUCpZlN7jL2QUYOQm1xLnvw6TFLFw4?usp=sharing 

Estas son las dos opciones que puedes seguir:

## OPCIÓN 1: 📈 REGRESIÓN MÚLTIPLE O RESTRINGIDA

### 🎯 Objetivo Específico

Estimar el valor futuro o adecuado de un activo (propiedad o combustible) en distintas ubicaciones, y asesorar sobre dónde realizar una inversión rentable.

### 💼 Contexto

Un inversionista desea comprar propiedades para revenderlas tras mejoras o adquirir una estación de servicio en una zona con potencial de alza en precios.

### 🧠 Actividades Sugeridas
• Definir la variable objetivo (precio actual o futuro).
• Seleccionar variables predictoras relevantes (e.g., ubicación, características físicas, histórico de precios).
• Aplicar regresión múltiple o restringida (ej. Lasso/Ridge) para predecir precios.
• Evaluar métricas de desempeño (R², MAE, RMSE).
• Justificar, en un informe, en qué ciudad o región se debería invertir con base en los resultados del modelo.

## OPCIÓN 2: 🔍 CLUSTERING DE SERIES DE TIEMPO

### 🎯 Objetivo Específico

Identificar zonas geográficas que presentan comportamientos similares de precios a lo largo del tiempo, para localizar patrones de alta o baja rentabilidad.

### 💼 Contexto

El inversionista busca zonas con baja volatilidad de precios o con tendencias ascendentes sostenidas para minimizar riesgos y maximizar márgenes.

### 🧠 Actividades Sugeridas
• Preprocesar los datos de series de tiempo (normalización, interpolación si es necesario).
• Aplicar técnicas de clustering como K-Means, DBSCAN o clustering jerárquico sobre las series de tiempo (con DTW o autocorrelaciones).
• Visualizar los grupos formados y relacionarlos con ubicaciones geográficas.
• Interpretar y recomendar zonas geográficas adecuadas para invertir con base en la estabilidad, tendencia o similitud con otras zonas exitosas.

## 📝 Entregables
1.	Informe técnico (máx. 6 páginas):
• Planteamiento del problema.
• Descripción del conjunto de datos y variables elegidas.
• Metodología aplicada (justificación del modelo).
• Resultados visuales y métricas.
• Recomendaciones de inversión.
2.	Código reproducible en Jupyter Notebook o script en Python/R.
3. Mapa o visualización geográfica (opcional pero recomendado).

## ✅ Criterios de Evaluación
• Claridad y lógica del enfoque analítico.
• Correcta aplicación del modelo de ML.
• Interpretación orientada a la toma de decisiones.
• Calidad de visualizaciones y presentación de resultados.
• Coherencia de recomendaciones con base en la evidencia.

