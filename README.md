# Detección de Fraudes en Tarjetas de Crédito: Utilizando Algoritmos de Clasificación.

En este proyecto de detección de fraudes en tarjetas de crédito, se llevó a cabo un análisis detallado utilizando diversas técnicas de aprendizaje automático y optimización de hiperparámetros para identificar transacciones fraudulentas.

## Recopilación y Preparación de Datos:
Se obtuvieron los datos históricos de transacciones de tarjetas de crédito a través de Kaggle (https://www.kaggle.com/datasets/whenamancodes/fraud-detection/data). Se realizó un proceso exhaustivo de limpieza de datos para identificar valores atípicos y asegurar la coherencia de la información.

## Análisis Exploratorio con Visualizaciones:
Se llevó a cabo un análisis exploratorio utilizando visualizaciones para comprender la distribución de las transacciones, identificar patrones temporales y explorar la relación entre las características y la variable objetivo (fraude o no fraude).

## Selección de Características:
Se realizaron análisis de correlación para identificar las características más relevantes en la detección de fraudes. Se seleccionaron aquellas con mayor correlación positiva y negativa con la variable objetivo para utilizarlas en los modelos de aprendizaje automático.

## Preparación de los Datos para Modelos de Clasificación:
Se dividió el conjunto de datos en conjuntos de entrenamiento y prueba, y se aplicaron técnicas de balanceo de clases, como ADASYN, para abordar el desbalance de las clases. Además, se escaló las características para garantizar que todas tuvieran el mismo peso en los modelos.

## Implementación de Modelos de Aprendizaje Automático:
Se implementaron varios modelos de aprendizaje automático, incluyendo Random Forest, XGBoost, CatBoost y LightGBM, para predecir transacciones fraudulentas. Se evaluaron utilizando la métrica Área Bajo la Curva de Precisión-Recall (AUPRC).

## Optimización de Hiperparámetros:
Se utilizó la optimización de hiperparámetros mediante BayesianOptimization para ajustar los parámetros de los modelos y mejorar su desempeño. Se exploraron diferentes espacios de búsqueda para cada hiperparámetro y se seleccionaron los mejores valores.

## Evaluación y Comparación de Modelos:
Se realizaron evaluaciones de desempeño para cada modelo utilizando AUPRC y se compararon sus resultados. Se seleccionó el modelo LightGBM con optimización bayesiana como el de mejor desempeño.

## Predicción de Probabilidades:
Para predecir la probabilidad de fraude, se utilizó el método .predict_proba, que proporciona la probabilidad de que una transacción sea fraudulenta.

## Conclusión y Resultados:
Se concluyó que el modelo LightGBM optimizado con optimización bayesiana logró el mejor desempeño en la detección de fraudes en tarjetas de crédito, con un AUPRC de 0.7917. Este proyecto proporciona una base sólida para la detección eficaz de fraudes en transacciones financieras, lo que puede ser crucial para la seguridad y la prevención de pérdidas económicas.

Este proyecto representa un paso significativo en la detección de fraudes en transacciones financieras, utilizando técnicas avanzadas de aprendizaje automático y optimización de hiperparámetros para mejorar la precisión y eficacia en la identificación de transacciones fraudulentas.
