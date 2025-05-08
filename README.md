# Natalidad

# 🌍 Predicción Global de la Tasa de Fertilidad con Machine Learning

Este proyecto busca predecir la evolución de la **Tasa de Fertilidad Total (TFR)** por país hasta el año 2100, utilizando datos demográficos históricos y proyectados. El objetivo es identificar tendencias globales y posibles **riesgos de baja fertilidad** futura, comparando los resultados con las predicciones oficiales de la ONU.

---


## 🗃️ Base de datos
https://population.un.org/dataportal/home?df=cc69c83b-2408-47e8-b594-2000daae1fbd


---


## 📊 Descripción del proyecto

- Se utilizaron datos demográficos anuales desde 1950 hasta 2023, incluyendo población, esperanza de vida, tasa de natalidad, edad media de maternidad, entre otros indicadores.
- Se entrenó un modelo de regresión para cada país usando datos históricos.
- Se aplicaron predicciones oficiales de la ONU (variables proyectadas) como entrada al modelo para prever la fertilidad en el futuro.
- Se evaluaron los resultados comparando las predicciones del modelo con las proyecciones oficiales de la ONU.

---

## 🔧 Tecnologías utilizadas

- Python
- Pandas & NumPy
- Scikit-learn
- CatBoost
- Seaborn & Matplotlib
- Jupyter Notebook
- Flourish (para mapas interactivos)
