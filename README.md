# Forecasting Económico del Sector Turístico Canario mediante Técnicas de Machine Learning

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un sistema de forecasting económico aplicado al sector turístico de Canarias mediante técnicas de Machine Learning. A partir de un dataset proporcionado por el Instituto Canario de Estadística (ISTAC), se analizarán las actividades realizadas por los turistas, los territorios visitados y los tipos de alojamiento utilizados con el fin de predecir tendencias futuras en la demanda turística. El análisis abarcará la serie temporal de 2018 a 2024, lo que permitirá estudiar la evolución del turismo antes, durante y después de la pandemia.

El resultado esperado es la construcción de modelos predictivos que permitan estimar la participación turística futura y extraer conclusiones relevantes que puedan ser aplicadas a la planificación económica y estratégica del sector.

---

## 🎯 Objetivo General
Desarrollar un modelo de forecasting económico basado en Machine Learning para predecir la evolución turística en Canarias y apoyar la toma de decisiones en el ámbito de la planificación y gestión turística.

---

## 🎯 Objetivos Específicos

- **Analizar el dataset del ISTAC** para comprender la distribución de turistas según territorio, actividad y tipo de estancia.
- **Explorar la evolución temporal del turismo (2018–2024)** y detectar patrones significativos.
- **Preparar y transformar los datos** mediante técnicas de limpieza, codificación y normalización.
- **Seleccionar y aplicar modelos de Machine Learning** adecuados para forecasting, tales como regresión, modelos basados en árboles o métodos de series temporales.
- **Evaluar el rendimiento de los modelos** utilizando métricas como MAE, RMSE y R².
- **Generar predicciones** sobre la actividad turística futura y analizar su impacto económico.
- **Interpretar los resultados** para obtener insights que puedan ser útiles en la planificación turística regional.

---

## 📊 Descripción del Dataset

El dataset está compuesto por **2400 registros** y **10 columnas**, integrando datos de:

### 🗺️ Territorio
Incluye Canarias, sus principales islas (Gran Canaria, Tenerife, Lanzarote, Fuerteventura, La Palma) y sus municipios turísticos.

### 🏖️ Actividad
Contempla actividades turísticas tales como:
- Playa  
- Piscina / instalaciones hoteleras  
- Paseo o callejeo  
- Excursiones  
- Ocio nocturno  
- Actividades deportivas y de naturaleza  
- Gastronomía y actividades culturales  

### 🏨 Tipo de estancia
- Hotel  
- Apartamento/villa  
- Vivienda privada  
- Otros  
- Total  

### 📆 Variables temporales
Columnas correspondientes a los años 2018–2024 con el número de turistas que realizaron cada actividad.

Estos datos permitirán estudiar patrones temporales y generar modelos predictivos fiables.

---

## 🛠️ Metodología Propuesta

1. **Análisis exploratorio de datos (EDA)**  
   - Distribución por territorios, actividades y tipos de estancia  
   - Evolución anual  
   - Visualización de tendencias  
    
2. **Preparación del dataset**  
   - Limpieza de valores  
   - Codificación de variables categóricas  
   - Normalización de variables numéricas  
    
3. **Modelado predictivo**  
   - Selección de modelos de Machine Learning  
   - Entrenamiento y validación  
   - Comparación de métricas  
    
4. **Generación de predicciones**  
   - Forecasting a nivel territorial y por actividad  
   - Estimación de variaciones futuras  
    
5. **Interpretación y conclusiones económicas**

---

## 🧰 Tecnologías que se utilizarán

- Python  
- Pandas  
- NumPy  
- Matplotlib y Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## 🚀 Resultados Esperados

- Un modelo de forecasting capaz de predecir el comportamiento turístico futuro.  
- Identificación de patrones clave en el comportamiento de los turistas.  
- Conclusiones útiles para la planificación turística y económica.  
- Visualizaciones que faciliten la interpretación de tendencias.  

---

## 🗂️ Estructura del Proyecto

```
ML_project/
│── app_streamlit/
│── data/
│── docs/
│── img/
│── Models/
│── Notebook/
│── Readme/
│── src/
│── Proyecto_ML.ipynb
│── README.md
```
