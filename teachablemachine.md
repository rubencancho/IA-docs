# Introducción al problema

Vamos a entrenar un modelo de Teachable Machine para que sea capaz de identificar a que contenedor tenemos que tirar un residuo.

## Iteración 1

1. Elección de clases y datos de entrenamiento

vamos a añadir 3 clases:
  * Contenedor amarillo
  * Contenedor verde
  * Contener azul

2. Entrenamiento del modelo

3. Evaluación del modelo y conclusiones

### Test 1

Probamos con una botella de plástico y nos da una clasificación de contenedor erronea (verde):

![](https://github.com/rubencancho/IA-docs/blob/main/imagenes_doc/test1.png)

Debemos reentrenar el modelo para que aprenda mejor la diferencia entre los materiales, y no se centre en las formas.

### Test 2

Probamos con un rollo de papel y nos da una clasificación de contenedor erronea (amarillo):

![](https://github.com/rubencancho/IA-docs/blob/main/imagenes_doc/test2.png)

### Conjunto de entrenamiento 1

| Imagen          | Categoría real | Categoría del modelo | Porcentaje | Comentario |
|-----------------|----------------|----------------------|------------|------------|
| aluminio.jpg    | Amarillo       | Amarillo             | 80,00 %    |            |
| brote_spray.jpg | Amarillo       | Amarillo             | 94,00 %    |            |
| brik.jpg        | Amarillo       | Amarillo             | 98,00 %    |            |


## Iteración 2

Mejora de los datos de entrenamiento (opción 1)
Mejora de los parámetros de entremiento (opcion 2)
Evaluación del modelo y conclusiones
