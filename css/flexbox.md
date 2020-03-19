# Flexbox

Flexbox es una propiedad de CSS la cual fue creada para ayudar a distribuir los espacios entre los elementos de una interfaz (contenedor) y mejorar los espacios de alineacion

Estos elementos los vamos a poder mover de dos maneras, horizontalmente y verticalmente.

## Requisitos

Para empezar a usar flexbox nesecitamos dos cosas, un contenedor con elementos los cuales deseamos mover, y una clase que le diga al contenedor que usaremos flexbox en el.
Estos elementos que vamos a mover dentro de nuestro contenedor no importa que sean elementos **en bloque** o elementos **en linea** ya que la funcion de `display:flex;` que veremos a continuacion cambiara la naturaleza de estos.

### Foto del HTML
### Foto del CSS

## Justify content

Justify content nos permitira mover nuestros elementos de manera horizontal atravez de todo nuestro contenedor de 5 maneras.

### flex-start:

Esta propiedad nos dejara todos nuestros elementos a la izquierda de nuestro contenedor.
 
### flex-end: 

Esta propiedad nos dejara todos nuestros elementos a la derecha de nuestro contenedor.

### center:

Esta propiedad nos dejara todos nuestros elementos en el centro de nuestro contenedor (hablando horizontalmente).

### space-around:

Esta propiedad nos dejara con espacios iguales a la derecha como a la izquierda de nuestros elementos.

### space-between:

Esta propiedad nos dejara con espacios iguales unicamente en el espacio que hay entre nuestros elementos

## Flex direction

Los **elementos** que tenemos **dentro** de nuestro **contenedor** por default tendran un valor de `display:inline;` y con flex direction podremos hacer varias cosas, una de ellas es cambiar esta propiedad que tengan nuestros elementos, y hacer que aparezcan en forma de bloque o en forma de en linea.
Otra de las cosas que podremos hacer con esta propiedad es voltear nuestros elementos al lado contrario, como si se tratara de un espejo.

### row: 

Este es el valor por default de nuestro flexbox, este hara que nuestros elementos sean de `display:inline;` y apareceran de manera natural a la izquierda de nuestro contenedor.

### row-reverse:

Esta propiedad dejara de la misma forma `display:inline;` a nuestros elementos, pero lo que hara es hacerles cambiar su posicion hasta la derecha pero en forma de espejo.
Supongamos que tenemos tres elementos, que al momento de iniciar flex estan acomodados como "1 2 3" a la izquierda de nuestro contenedor, bueno al aplicar esta propiedad los elementos se colocaran a la derecha de este con las posiciones de esta manera 
"3 2 1"

### column:

Esta propiedad nos cambiara nuestros elementos para que tengan `display:block;` todos nuestros elementos se acomodaran de manera decendente. pero ahora cambiaremos las propiedades `justify-content` y `align-items`.
### column-reverse: Elementos se colocan de abajo hacia arriba.

Esta propiedad es muy parecida a la anterior, pero aplica la misma propiedad de voltear nuestros elementos.

## Order

Esta propiedad se la podemos poner a cada elemento individual de nuestros contenedor que tiene flex.
Por defecto tiene un valor de 0, pero podemos agregarle un valor entero positivo o un valor entero negativo y esto lo movera respectivamente como el primer elemento de todos o el ultimo.

`order:1` o `order:-1`

## Align self

`align-self` es una propiedad identica a `align-items` en la que recibe los mismo valores que esta, pero esta la podremos aplicar a elementos individuales de nuestro contenedor.

