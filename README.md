# Predicción de Diabetes

## 📌 Descripción

Se probaron múltiples algoritmos como Logistic Regression, Random Forest, Gradient Boosting, entre otros. Luego de un análisis exploratorio de datos (EDA) y un adecuado preprocesamiento, se seleccionó el modelo con mejor rendimiento basado en métricas clave.

Posteriormente, se entrenaron tres modelos de conjunto (ensemble) y se evaluó su rendimiento utilizando un conjunto de validación. Los métodos de votación suave y dura ofrecieron los mejores resultados para este problema específico.

⚠️ Los resultados pueden variar dependiendo del preprocesamiento, la selección de modelos base y la configuración de los hiperparámetros.

## 🛠 Tecnologías Utilizadas

- **Python**
- **Pandas y NumPy**
- **Scikit-Learn, PyCaret**
- **Matplotlib y Seaborn**
- **Jupyter Notebook**

## 📊 Resultados

### Métricas de Rendimiento

- **Accuracy: 93.23%
- **Precisión: 92.31%
- **Recall: 88.24%
- **F1-score: 90.23%

### Matriz de Confusión

TP (Verdaderos Positivos): 51
TN (Verdaderos Negativos): 113
FP (Falsos Positivos): 11
FN (Falsos Negativos): 17

## 📈 Evaluación del Modelo

Se utilizó un enfoque basado en aprendizaje automático con PyCaret. Se probaron múltiples algoritmos (Logistic Regression, Random Forest, Gradient Boosting, etc.) y se seleccionó el modelo con el mejor rendimiento basado en métricas clave.

Tras el análisis de datos de dependencia (EDA) y el preprocesamiento, se ejecutaron tres modelos de conjunto y se verificó su rendimiento con el conjunto de datos de validación. El conjunto con votación suave y dura ofreció el mejor resultado para resolver este problema, pero los resultados pueden variar según el preprocesamiento, la selección de los modelos base y la configuración de los hiperparámetros.

## 🏁 Conclusión

El modelo tiene un alto nivel de precisión, lo que permite minimizar diagnósticos erróneos de diabetes en pacientes sanos. Sin embargo, el recall está por debajo del 95%, lo que indica que aún hay margen de mejora para captar más casos reales de diabetes.
