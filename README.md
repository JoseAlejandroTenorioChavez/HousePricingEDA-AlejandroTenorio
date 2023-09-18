# Análisis de Datos de Casas

## 1. Análisis exploratorio de datos (EDA)

Este es el primer paso en el análisis de datos. Aquí, vamos a entender las características principales del conjunto de datos, la relación entre las diferentes variables, identificar posibles valores atípicos, entender la distribución de los datos, etc. Esto se hace utilizando estadísticas descriptivas y visualizaciones gráficas.

## 2. Limpieza de datos

En este paso, vamos a tratar los valores perdidos o nulos en el conjunto de datos. También vamos a eliminar o corregir los valores atípicos si es necesario.

## 3. Transformación de variables categóricas

Muchos modelos de aprendizaje automático requieren que todas las variables sean numéricas. Por lo tanto, vamos a convertir las variables categóricas en numéricas. Esto se puede hacer utilizando varias técnicas como la codificación one-hot y MultiColumnLabelEncoder.

### Codificación One-Hot

Esta técnica convierte cada valor único de una característica categórica en una nueva característica binaria (0 o 1). Es útil cuando no hay un orden o jerarquía en las categorías. Sin embargo, puede aumentar significativamente la dimensionalidad del conjunto de datos si una característica tiene muchas categorías únicas.

### MultiColumnLabelEncoder

Esta técnica asigna un número entero único a cada categoría de una característica. Es útil cuando hay un orden en las categorías (por ejemplo, "bajo", "medio", "alto"). A diferencia de la codificación one-hot, no aumenta la dimensionalidad del conjunto de datos.

## 4. Correlación y selección de características

Finalmente, vamos a calcular la correlación entre las diferentes características y la variable objetivo. Esto nos ayudará a entender qué características son las más importantes para predecir la variable objetivo.

La conversión de características categóricas a numéricas es un paso crucial porque permite que los algoritmos de aprendizaje automático procesen los datos correctamente. Algunos algoritmos pueden manejar características categóricas directamente. Para otros algoritmos, todas las características deben ser numéricas. Al convertir las características categóricas en numéricas, nos aseguramos de que nuestro conjunto de datos pueda ser utilizado por una amplia gama de algoritmos de aprendizaje automático.
