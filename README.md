# MIAD_ANS_TEAM22
 Repositorio academico: Proyecto Final Aprendizaje No Supervizado - Maestría en Inteligencia Analítica de Datos
 
 Resumen:
 Este repositorio contiene el desarrollo de un proyecto de segmentacion de inmuebles en Colombia, para el curso de Aprendizaje No Supervizado. Este proyecto busca responder a la siguiente pregunta: 
¿Es posible segmentar las propiedades presentes en los principales portales inmobiliarios de Colombia de tal manera que los datos ofrezcan puntos de partida de negociación y adquisición económica de los inmuebles, para que luego, la empresa Home Capital obtenga un margen alto de contribución?

Asi pues, este es un problema que se pretende abordar desde dos pasos, reducción de dimensionalidad, dada la magnitud de variables disponibles y la importancia que le da el negocio de considerarlas todas, y clusterizacion, cumpliendo con el objetivo de segmentar los inmuebles de tal manera que se puedan establecer precios teniendo en cuenta inmuebles con características similares. Para lo cual se sugiere abordar la tarea de reducción de dimensionalidad con un PCA y SVC, y la clusterizacion con un algoritmo basado en distancias, como es kmeans y un algoritmo basado en econometría espacial.

El repositorio se encuntra organizado en las siguientes carpetas:
   1. Data: Donde se almacenaran una muestra de las fuenets de infromacion disponible para la realizacion del proyecto. Informacion compartida por la empresa Home Capital bajo autorizacion con fines academicos.
   2. EDA: Analisis descriptivos de las fuentes de informacion. 
   3. DataPreparation: Preparacion de los datos, el cual consta de limpieza e imputacion de datos faltantes y valores atipicos, transfromacion de las variables, filtros, cruces de fuentes, alistamiento de base final para modelo de reduccion de dimensionalidad y segmentacion. 
   4. Training: Distintos algoritmos y modelos ajustados para la tarea de reduccion de dimensionalidad y segmentacion. Descriptivo de metricas de desempeño. 
   5. Model: Eleccion del mejor modelo de reduccion de dimensionalidad y segmentacion.
   6. Output: Salida de los modelos, perfilamiento de los segmentos, descriptivo de los resultados. 



