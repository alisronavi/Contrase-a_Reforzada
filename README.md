# Contrasena_Reforzada
Proyecto de contraseña Reforzada

El proyecto de contraseña reforzada se desarrollo mediante las siguientes tareas:

https://trello.com/b/7J3niJpR/proyecto-contrase%C3%B1a-reforzada

El desarrollo del juego se baso en la creación de un generador de contraseñas.

Se importo la biblioteca de random para poder obtener sus funciones, entre ellas ".random_choice" para obtener un elemento aleatorio de una lista en este caso.

El diseño esta orientado a partir del uso de int, str, listas, funciones y bucles.

Las funciones que se utilizaron fueron:

.append para agregar los elementos
.join para juntar los resultados obtenidos

El diseño del generador inicio con esta secuencia:

1. Se importa random para obtener la funcion de .random_choice
2. Se define nuestra funcion que sera "contraseña_reforzada"
3. La contraseña sera un elemento vacio para que se agregue la informacion de la funcion despues de las siguientes operaciones
4. Declaramos las variables que queremos utilizar en la funcion, en este caso son limitadas por Mayusculas, minusculas, simbolos y numeros y las sumamos en una variable que se llame "elementos"
  4.1 La investigacion sugeria la utilizacion de ASCII pero no se importo la biblioteca por lo que cada elemento se transcribio.
5. Iniciamos un bucle para iterar en el rango de elementos que queremos
  5.1 para este rango agregamos un ".input" para quien este operando el generador.
    5.1.1 No alcanzamos a agregar limites para el bucle o restricciones de letras o decimales
6. Definimos una variable como "elemento_random" para la funcion ".random_choice" sobre la variable "elementos". Esta nos dara como resultado el elemento que se haya escogido aleatoriamente.
7. Despues utilizamos la funcion de append para agregar a la contraseña el "elemento_random" que se haya obtenido.
8. Cuando lleguemos al numero total del input que se haya ingresado de longitud, el bucle terminara y nos dara "return" la contraseña con la lista de todos los .append que hayamos hecho a traves de la funcion de .join.
9. Por ultimo, definimos que la funcion corra si la variable de contraseña es igual a la funcion.
10. Asi obtenemos nuestra contraseña basada en os diferentes elementos que definimos, escogidos aleatoriamente, combinados y con la impresion de "Tu contraseña reforzada es:"

Para utilizar el generador solo se requieren 3 pasos.

1. Abrir el generador: https://github.com/alisronavi/Contrase-a_Reforzada/blob/main/Contrase%C3%B1a_reforzada.ipynb
2. Correr el codigo
3. Ingresar el numero que nos piden para obtener nuestra contraseña

*La densidad del codigo puede sintetizarse importando mas librerias
*El input de la longitud puede limitarse aun mas para que no se ingrese información erronea ya que esta definido solo que sea int pero no para STR o FLOAT.


