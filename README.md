# Samuel_Garcia_Garcia_Codigo_TFG
Repositorio que contiene los códigos que se han diseñado para el trabajo de fin de grado de matemáticas de la Universidad de Zaragoza: Selección de características y modelos predictivos para el diagnóstico clínico mediante ultrasonido, Samuel García García, Junio 2025.

El archivo "Modelo Variables Electrodiagnósticas.R" contiene el código para el diseño y análisis del modelo de regresión logística mediante validación cruzada leave-one-out utilizando las cinco variables electrodiagnóstico.

El archivo "Modelos Lasso Variables US.R" contiene el código para la construcción de los tres modelos Lasso de ultrasonido cuantitativo (transversal, longitudinal y la combinación de ambos) mediante LOOCV y su respectivo análisis. Incluye también el diseño y análisis de los modelos de regresión logística clásicos, utilizando como predictores las variables que han sido seleccionadas por Lasso.

El archivo "Modelos Red Elástica Variables US.R" contiene el código que calcula el AUC de los diferentes modelos de red elástica (los tres anteriores con diferentes métodos de muestreo) utilizando LOOCV.
