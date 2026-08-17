# Trabajo Práctico N.º 3 — Taller de Programación

**Maestría en Economía Aplicada — Universidad de Buenos Aires**

## Grupo 2

* Andrea Chasi
* Santiago Soler
* Pablo Ortiz

## Clasificación de la informalidad laboral en Argentina

El TP3 utiliza los microdatos de la Encuesta Permanente de Hogares (EPH) correspondientes al cuarto trimestre de 2024 y 2025 para analizar y predecir la informalidad laboral mediante modelos de clasificación.

Para el Grupo 2 se utiliza la definición **Upper-tier informal wage employees**, construida a partir de la condición de asalariado, ausencia de descuento jubilatorio y tamaño del establecimiento.

## Estrategia del análisis

El trabajo utiliza:

* **EPH 2024** como muestra de entrenamiento.
* **EPH 2025** como muestra de testeo fuera de muestra.
* Una segunda especificación basada en los individuos observados en ambos períodos, incorporando su condición de informalidad en 2024, siguiendo la extensión propuesta a partir de Maurizio y Monsalvo (2021).

Se presentan:

* Balance entre las muestras 2024 y 2025.
* Dos modelos de regresión logística.
* Coeficientes, errores estándar y odds ratios.
* Probabilidades predichas.
* Matrices de confusión.
* Métricas de desempeño.
* Curvas ROC.
* Comparación de los modelos desde una perspectiva de política pública.

## Archivos principales

**Informe final**

`TP3_Programacion_Grupo2.pdf`

Contiene la metodología, principales resultados, interpretación económica, evaluación predictiva, conclusiones y apéndices.

**Notebook reproducible**

`TP3_Programacion_Grupo2.ipynb`

Contiene la construcción de las bases, procesamiento de datos, estimaciones, tablas, métricas y gráficos utilizados en el informe.

## Resultado principal

La incorporación del estatus de informalidad observado en 2024 mejora el desempeño predictivo para 2025. El segundo modelo presenta mejores resultados en **recall, F1-score y AUC**, lo que resulta particularmente relevante cuando el objetivo es identificar trabajadores informales y reducir falsos negativos en la focalización de políticas de formalización laboral.

## Reproducibilidad

El código y los resultados utilizados en el informe se encuentran disponibles en esta carpeta para permitir la trazabilidad entre los datos procesados, las estimaciones realizadas y los resultados reportados en el documento final.

