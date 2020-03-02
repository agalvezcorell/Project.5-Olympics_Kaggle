![Portada](https://github.com/agalvezcorell/Project.5-Olympics_Kaggle/blob/master/output/portada.jpg)
# Entrenando el mejor modelo de Machine Learning

Este proyecto consiste en participar en [esta competición de Kaggle](https://www.kaggle.com/c/diamonds-datamad0120) y entrenar el mejor modelo de machine learning para predecir con exactitud el precio de los diamantes.

### ¿Qué pasos he seguido?
En primer lugar he tenido que investigar sobre el precio de los diamantes y las variables que influyen en él para poder trabajar con en la limpieza de los datos con conocimiento.

En segundo lugar, he realizado una limpieza básica de los datos con pandas.

#### Modelos de Machine Learning
Para entrenar los modelos y sacar las predicciones he seguido básicamente dos caminos.

En primer lugar, entrené el modelo RandomForestRegressor y comprobé que aunque el r2 score era bastante alto (0,87), los datos no se ajustaban demasiado ya que mi puntuación en la competición no era muy alta.

Después, me he centrado en H2O y, en concreto, en estudiar su AutoModel, que lo que hace básicamente es entrenar 50 modelos y darte una tabla con el que más se ajusta a tus datos en función de la métrica que lo quieras ordenar.

Mi mejor puntuación la he conseguido entrenando todos los modelos durante 2h (entrenando más horas obtenía los mismos resultados) con el modelo XGBoost.
