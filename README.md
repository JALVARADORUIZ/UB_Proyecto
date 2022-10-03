# UB_Proyecto

RESUMEN EJECUTIVO



El objetivo del presente trabajo es desarrollar un modelo de aprendizaje automático que pueda predecir, a partir de una imágen de su etiqueta, el precio de un producto vitivinícola.


Desde hace ya algunos años, el mercado vitivinícola sufre una gran expansión. Año a año, nuevos actores de distinta envergadura intentan introducirse en el mercado convirtiéndose en un entorno muy competitivo. Ante esta situación, estos nuevos jugadores se encuentran frente a un difícil desafío: deben ofrecer una propuesta innovadora en cuanto a su estrategia de mercadeo, a la vez que reducir riesgos de posibles pérdidas. 


Es de esta problemática que surge la solución de este trabajo, contando con una extensiva base de datos de vinos, sus características principales y sus imágenes, buscaremos encontrar un algoritmo que prediga de la manera más eficiente, con la etiqueta del producto, su precio/valor.  


Se utilizaron dos abordajes distintos (predicción de categoría de precio y predicción de precio) ocupando dos algoritmos distintos para, al final del proceso, poder comparar los resultados. De esta manera, usaremos dos modelos de clasificación (un SVM y una Red Neuronal Convolucional) para predecir la categoría de precio (bajo, medio, alto) y  dos modelos de regresión para intentar predecir la variable de precio en dólares. Nos apalancamos, para el tratamiento de las imágenes en los algoritmos que involucren máquinas vectoriales, en un modelo pre-entrenado para el preprocesado de las imágenes y en análisis de componentes principales para reducir la dimensionalidad de las mismas y eficientizar el tiempo de computación. 
