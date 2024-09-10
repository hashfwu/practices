 
# OneHotEncoder
Codifique las características categóricas como una matriz numérica one-hot.

La entrada de este transformador debe ser una matriz de números enteros o cadenas que denoten los valores que toman las características categóricas (discretas). Las características se codifican utilizando un esquema de codificación one-hot (también conocido como "one-of-K" o "dummy"). Esto crea una columna binaria para cada categoría y devuelve una matriz dispersa o una matriz densa (según el sparse_outputparámetro).