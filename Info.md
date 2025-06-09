PROPIEDADES


display: flex;
gap: px; #esto se hace para dar espacio entre si

* flex-direction:  define la dirección de los elementos en el contenedor

row: Elementos son colocados en la misma dirección del texto.
row-reverse: Elementos son colocados en la dirección opuesta al texto.
column: Elementos se colocan de arriba hacia abajo.
column-reverse: Elementos se colocan de abajo hacia arriba

    ejemplos: 
    Display: flex; 
    flex-direction: column #los pone en fila como una columna


* flex-wrap: controla si los elementos hijos deben mantenerse en una sola línea o pueden "envolverse" a otra línea cuando no hay suficiente espacio horizontal.

 nowrap: Cada elemento se ajusta en una sola línea.
 wrap: los elementos se envuelven alrededor de líneas adicionales.
 wrap-reverse: Los elementos se envuelven alrededor de líneas adicionales en reversa.
    
    ejemplos: 
    Display: flex; 
    flex-wrap: wrap;

* flex-flow es la union de dos valores; flex-direction y flex-wrap

flex-flow: column wrap; es igual a  (flex-direction: column;  + flex-wrap: wrap;)




* justify-content, la cual alinea elementos HORIZONTALMENTE y acepta los siguientes valores:

flex-start: Alinea elementos al lado izquierdo del contenedor.
flex-end: Alinea elementos al lado derecho del contenedor.
center: Alinea elementos en el centro del contenedor.
space-between: Muestra elementos con la misma distancia entre ellos.
space-around: Muestra elementos con la misma separación alrededor de ellos.

ejemplos: 
Display: flex; 
 justify-content: flex-end;
 justify-content: center;
 justify-content: space-around; 
 


* text-align: es una propiedad de CSS que controla la alineación horizontal del texto dentro de un elemento bloque (como un div, p, section, etc.).
left:	Alinea el texto a la izquierda (valor por defecto)
center:	Centra el texto en el contenedor
right:	Alinea el texto a la derecha
justify: Justifica el texto (como en periódicos o libros)

*align-items:  alinea elementos VERTICALMENTE
(align-self=  esta propiedad solo se usa para elementos individuales y acepta todos los valores de align-items )     
 flex-start: Alinea elementos a la parte superior del contenedor.
 flex-end: Alinea elementos a la parte inferior del contenedor.
 center: Alinea elementos en el centro (verticalmente hablando) del contenedor.
 baseline: Muestra elementos en la línea base del contenedor
 stretch: Elementos se estiran para ajustarse al contenedor.

    ejemplos: 
    display: flex: 
    align-items: flex-end

*  align-content: Solo funciona si hay más de una línea de elementos.  Complementa a align-items, que alinea los elementos individuales, mientras que align-content alinea las líneas completas.

flex-start: Las líneas se posicionan en la parte superior del contenedor.
flex-end: Las líneas se posicionan en la parte inferior del contenedor.
center: Las líneas se posicionan en el centro (verticalmente hablando) del contenedor.
space-between: Las líneas se muestran con la misma distancia entre ellas.
space-around: Las líneas se muestran con la misma separación alrededor de ellas.
stretch: Las líneas se estiran para ajustarse al contenedor.

    ejemplos: 
    display: flex: 
    ejemplos: 
    align-content: flex-start $ ajusta todas los elementos en la parte de arriba    



* Order : Por defecto, los elementos tienen un valor 0, pero nosotros podemos usar esta propiedad para establecerlo a un número entero positivo o negativo.
display: flex: 
order:1;

Union de ambas
#centra el elemento en toda la mitad
justify-content: center; #alinea centro horizontal
align-items: center; #alinea en centro en vertical




