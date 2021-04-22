
## Scrolling-Effects

Creación de un Script que otorgara el funcionamiento de desplazamiento
dentro de una misma seccion de la página web.

## Creado con la tecnologia

Este ejemplo ha sido creado con HTML, CSS y Javascript

## Explicacion

 - Obtener la clase "Menu" con el atributo [href^="#"] de tal forma que solo ubicara a todos los que tengan el "#"
 - Creacion de un forEach para indentificar los click, posteriormente se crea una nueva funcion "scrollingToClick"
 - En la funcion se crea un "event.preventDefault()" con el fin de evitar que se muestre el "#" en la URL al estar cambiando de opciones
 - Usamos "event.target" para revisar al elemento clikeado y posteriormente obtener el "href"
 - Se usa el "offsetTop" para revisar la distancia del elemento actual
 - Por ultimo se crea el "window.scroll" para dar el efecto de desplazamiento y utilizar el "offsetTop"

