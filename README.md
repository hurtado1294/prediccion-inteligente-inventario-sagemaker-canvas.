# prediccion-inteligente-inventario-sagemaker-canvas.
Proyecto de predicción inteligente de inventario utilizando AWS SageMaker Canvas, desarrollado para crear un modelo de aprendizaje automático sin código.
# Predicción Inteligente de Inventario con AWS SageMaker Canvas

## Descripción

Este proyecto utiliza **AWS SageMaker Canvas** para crear un modelo de aprendizaje automático que predice las necesidades de inventario de manera eficiente. El modelo se entrena sin necesidad de escribir código, aprovechando las herramientas visuales de SageMaker Canvas.

**Objetivo:** Desarrollar un modelo de pronóstico de inventario utilizando datos históricos, para predecir la cantidad de productos que se deben mantener en inventario.

---

## Paso 1: Selección y Carga del Conjunto de Datos

Se utilizó un conjunto de datos relacionado con los movimientos de inventario y las ventas pasadas de productos. Este conjunto de datos fue cargado en **SageMaker Canvas** para su posterior procesamiento y análisis.

---

## Paso 2: Construcción y Entrenamiento del Modelo

El modelo de pronóstico fue entrenado en SageMaker Canvas utilizando las características del conjunto de datos como variables de entrada (por ejemplo, producto, cantidad vendida, fecha) y la demanda futura de inventario como la variable de salida.

---

## Paso 3: Análisis de Métricas de Rendimiento

Las principales métricas utilizadas para evaluar el rendimiento del modelo incluyen:
- **MAPE (Error porcentual absoluto medio)**: Un valor bajo indica una mayor precisión en las predicciones.
- **RMSE (Error cuadrático medio)**: Mide la diferencia entre los valores predichos y los reales.
- **P50, P90**: Percentiles que indican escenarios de demanda media y alta, respectivamente.

---

## Paso 4: Realización de Predicciones

El modelo entrenado generó predicciones de inventario para varios periodos futuros, lo que permitió identificar las necesidades de reabastecimiento para optimizar los niveles de inventario.

---

## Paso 5: Conclusiones y Resultados

El modelo proporcionó predicciones de inventario precisas, lo que permitió a la empresa optimizar su cadena de suministro y reduc
