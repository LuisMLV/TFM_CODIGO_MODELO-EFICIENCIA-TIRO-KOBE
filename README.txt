Este repositorio contiene el código desarrollado para el Trabajo Final de Máster "Modelo predictivo sobre la eficiencia de jugadores 
en base a datos de tiros a canasta de la Carrera de Kobe Bryant", del máster Big Data y Data Science de la Universidad Internacional de
Valencia (VIU).


Este trabajo final de máster toma los datos ofrecidos por la competición de Kaggle Kobe Bryant Shot Selection 
(https://www.kaggle.com/c/kobe-bryant-shot-selection/overview). Estos datos consisten en diferentes variables 
que describen los tiros a canasta realizados por Kobe Bryant a lo largo de su carrera en la NBA.



Contiene los siguientes archivos:

 - Archivos notebook .ipynb (ver en el orden aquí enunciado para una mejor comprensión del proceso):
   
   - KOBE_ANALISIS_EXPLORATORIO.ipynb: Análisis exploratorio de las distintas variables que describen los tiros a canasta de la carrera de
     Kobe Bryant.
   - POSICIONES_KOBE_loc_x-loc_y: Código que efectúa un análisis exploratorio de las variables loc_x y loc_y.
   - EXITO_POSICIONES_KOBE_loc_x-loc_y: Código que efectúa un análisis exoploratorio de las variables loc_x y loc_y respecto al éxito de
     tiro.
   - SELECCION_DE_CARACTERISTICAS_Y_DE_MODELO.ipynb: Código para la selección de características/variables y selección del modelo de
     Machine Learning para construir el modelo de predicción. 
   - BOXPLOTS_RESULTADO_DE_CROSS_VAL_SCORE_MODELOS.ipynb: Código que crea una visualización de boxplots que presenta los resultados de la
     validación cruzada (llevada a cabo en la selección del modelo) para cada modelo a comparar.
   - OPTIMIZACION_ENTRENAMIENTO_PREDICCION__DELMODELO.ipynb: Código que realiza una optimización de hiperparámetros en el modelo, entrena 
     el modelo y genera la predicción con los hiperparámetros seleccionados, y crea el un archivo .csv para enviar a la competición de
     Kaggle.

 - Archivos .csv:

   - data.csv: Dataset ofrecido por la competición de Kaggle. Contiene tanto el conjunto de entrenamiento como el conjunto de test. Usado
     en todos los notebooks excepto en KOBE_ANALISIS_EXPLORATORIO.ipynb.
   - kobe_train.csv: Dataset que contiene el conjunto de entrenamiento. Usado solo en KOBE_ANALISIS_EXPLORATORIO.ipynb.
   - resultados_cv: Dataset que contiene los resultados de la validación cruzada realizada en el notebook SELECCIÓN_DE_CARACTERÍSTICAS_Y_DE_MODELO.ipynb
     para cada modelo a comparar. Usado en BOXPLOTS_RESULTADO_DE_CROSS_VAL_SCORE_MODELOS.ipynb 
   
