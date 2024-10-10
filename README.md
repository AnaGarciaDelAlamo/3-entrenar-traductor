# 3-entrenar-traductor

### Mi repositorio: https://github.com/AnaGarciaDelAlamo/3-entrenar-traductor.git


En esta sección se entrena el modelo de traducción secuencia a secuencia usando el conjunto de datos previamente limpiado y dividido. 
Se entrenan los tokenizadores de alemán e inglés para convertir las palabras en secuencias numéricas. Se calcula el tamaño del vocabulario y la longitud máxima de la frase para ambos idiomas.
Se define el modelo de red neuronal secuencial con una capa de Embedding para representar las secuencias de palabras, capas LSTM para procesar las secuencias de entrada y generar las secuencias de salida y el modelo se compila usando el optimizador Adam. Por último se entrena durante 30 épocas con un tamaño de 64.
