# 🚀 SpaceX Falcon 9 Rocket Launch – Predicción de Aterrizaje de la Etapa 1

Este proyecto es un **Capstone** desarrollado como parte final del **Certificado Profesional en Ciencia de Datos de IBM**

---

## 💡 Contexto y motivación

SpaceX anuncia en su página web que un lanzamiento del cohete **Falcon 9** cuesta **62 millones de dólares**.  
- El Falcon 9 está compuesto por tres partes: **Primera Etapa**, **Segunda Etapa** y **Carena de carga (Fairings)**.  

Otros proveedores llegan a cobrar más de **165 millones de dólares** por cada lanzamiento.  
- Gran parte del ahorro de SpaceX se debe a que **reutiliza la primera etapa**.  

Sin embargo:
- A veces la primera etapa no aterriza.
- A veces se destruye durante el aterrizaje.
- Otras veces SpaceX decide sacrificarla según los parámetros de la misión (carga útil, órbita, cliente).

**Si podemos predecir si la primera etapa aterrizará, podemos estimar el costo real de un lanzamiento.**

---

## 📜 Contexto del proyecto

En este proyecto asumo el rol de un científico de datos que trabaja para una *startup* que busca competir con SpaceX.  
El objetivo es **predecir si la primera etapa del Falcon 9 aterrizará con éxito** para que la empresa pueda realizar ofertas más informadas en licitaciones de lanzamiento.

Este proyecto sigue el ciclo completo de la metodología de la Ciencia de Datos:
1. **Recolección de datos** desde la API REST de SpaceX y otras fuentes.
2. **Manejo y limpieza de datos**.
3. **Análisis exploratorio y visualización**.
4. **Desarrollo y evaluación de modelos de machine learning**.
5. **Comunicación de resultados**.

---

## 🔍 Metodología

1. **Recolección de datos**  
   Obtención de información de lanzamientos históricos mediante la **API REST de SpaceX** y web scraping para complementar datos.

2. **Procesamiento de datos**  
   Limpieza, tratamiento de valores nulos, codificación de variables categóricas y creación de nuevas características.

3. **Exploración de datos (EDA)**  
   Análisis visual y estadístico de variables como tipo de órbita, sitio de lanzamiento, masa de carga útil y tasas de aterrizaje.

4. **Modelado**  
   Entrenamiento y comparación de distintos modelos de clasificación:
   - Regresión Logística
   - Support Vector Machines (SVM)
   - Árboles de Decisión
   - K-Nearest Neighbors (KNN)
5. **Optimización**  
   Búsqueda de hiperparámetros para maximizar métricas de rendimiento.

6. **Evaluación**  
   Uso de métricas como *accuracy*, F1-score, matriz de confusión y curva ROC-AUC.

---
