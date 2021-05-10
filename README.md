# Desafío 4: Clasificador de letras escritas a mano

Se les ha pedido implementar un módulo de un software que permita digitalizar documentos que son escaneados, para poder entregar opciones de accesibilidad.
Su tarea consiste en implementar un modelo de red neuronal que les permita reconocer una letra (A-Z) a partir de una imagen.

En este repositorio se encuentra un Dataset con imágenes en escala de grises que representan las letras del alfabeto en inglés (A-Z), junto con su etiqueta correspondiente. Para este trabajo se deberá:

- Leer el Dataset.
- Implementar (sin uso de librerías que lo hagan) y entrenar un perceptrón multicapa para la tarea de clasificación. Para esto se debe dividir los datos en entrenamiento y pruebas (70/30 sugerido).
- Con los datos de prueba, calcule la precisión (accuracy) de la predicción.


## Datos Adicionales

**Columna 0** : etiqueta de la imagen. 25 clases: una por cada letra del abecedario inglés (A-Z)


**"columna 1-784"**: Pixel n de la imagen, el valor es entre 0 y 1, siendo 0 completamente negro y 1 completamente blanco. Cada imagen es de 28x28, por lo que se tiene un vector de 784 pixeles.