1- start game: 
    Imprimir en pantalla los personajes y las preguntas y respuestas de 0.
    resetear las clues a 0.
    elegir aleatoriamente la solucion/personaje.
    Añadir un eventoclick a las preguntas
    Añador un eventoclick a los personajes

2- ClickPregunta: 
    cuando se haga click a una pregunta, si esa pregunta coincide con el personaje aleatorio, se deshabilitan los personajes que no cumplen con esa pregunta. Si no coincide con el aleatorio, se deshabilitan los persoanjes que sí lo cumplen. 
    Incrementa las pistas en 1.
    
3 - clickPersonaje:
    si es el personaje aleatorio, hacer un alert para felicitar al jugador por hagber ganado con ese numero de pistas usadas, si no es, un alert de que ha perdido :( y todo pierde capacidad de click y opacidad menos el personaje aleatorio y solo podría darle otra vez a START GAME. Solo tiene una oportunidad.




    /* ## Who is who

Dado el html ``exercise-2.html`` y el css ``exercise-2.css``, crea un archivo de javascript (recuerda que el javascript que
 proporcionamos nosotros es el que contiene la solución propuesta) para crear el famoso juego de Quien es quien!
 
 Para ello abre el fichero ``exercise-2.html`` en tu navegador y verás el resultado final de lo que queremos conseguir. Como ves, tenemos una serie de personas con diferentes caracteristicas fisicas y, debajo una serie de preguntas a
  realizar a nuestro programa. El cometido del programa que hagas será comparar la pregunta seleccionada que haga el
   usuario (botones) y deshabilitar personas en base a si concuerdan con las caracteristicas de la persona a adivinar
    que escogerá aleatoriamente el juego al iniciarse.
    
Deberás programar todas las condiciones partiendo de los **dos arrays que te dejamos al final del README**.
  
##Condiciones

1. Selecciona aleatoriamente una persona del array. Esta es la persona que deberá adivinar el usuario en base a las
 preguntas que haga al juego.  
2. Crea un tablero de juego en el que recorras todas las personas y pinta un ``<img>`` por cada una de ellas con
la imagen que cada persona tiene en la propiedad `.img` dentro
 del ``<div data-function="boardGame">`` 
3. Crea un tablero de preguntas con el array de ``questionsType`` que tendrás al final del README. Por cada uno de
 los objetos de este array deberás pintar un ``<h2>`` con el valor de la propiedad `.title` y tantos botones como
  strings tenga el array de la propiedad ``.questions``. Como consejo, podrás usar la propiedad `.key` para
   posteriormente comparar las respuestas con la persona seleccionada por el juego aleatoriamente.
4. Crea un evento ``click`` en los botones para comprobar si la persona seleccionada aleatoriamente por el juego
 coincide con la opción seleccionada por el usuario. Recorre el array de personas y deshabilita aquellas que no
  coincidan afirmativamente con la comparación. Ej: Si el usuario selecciona la opción ``Yes`` de la pregunta ``Glasses
tendremos que comprobar que el usuario seleccionado aleatoriamente por el juego tiene gafas...en caso de que las
 tenga. Deshabilitamos todos las personas que no tengan gafas y, en caso de que no la tenga, lo contrario. Para
  deshabilitar te recomendamos que añadas el estilo `pointers-events: 'none'` y `opacity: '0.2'`. Deshabilita también
   el botón al que el usuario ha hecho click con las mismas propiedades para que no pueda volver a
   darle. Finalmente, suma 1 al contador de pistas que estará en el `<span data-function="clueCount""`.
  5. Una vez hecho esto el usuario tendrá la capacidad de jugar hasta que decida que sabe quien es la persona
   seleccionada aleatoriamente por el juego. Para que el usuario seleccione la persona que cree que es, añade un
    evento `click` a las imagenes que comprueben si esa persona es realmente la persona que el juego ha seleccionado
    . Si es, crea una alerta felicitando al usuario por ganar con el numero de pistas usadas y si no...saca una
     alerta pero con un mensaje un poco menos optimo...you lose :(. Este evento sería lo ideal que lo hicieras
      al crear el tablero de juego con las personas...por optimizar jeje.
  6. Por último para nota, resetea el juego cuando el usuario elija una persona como respuesta. Para que pueda volver
   a jugar, basicamente :)
##Recursos
 */
