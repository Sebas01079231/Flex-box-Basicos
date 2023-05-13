# Flex-box-Basicos
Guia de flexbox CSS

flex-direction -> la direccion que quieres como se muestre el contenido

justify-content -> forma de ordernar el contenido horizontalmente (en direccion rows)
align items -> forma de ordenar el contenido verticalmente (en direccion rows)

gap -> separacion entre cajas en flexbox (como margin pero en flex)

flex-basis: calc() -> calcula el tamaño base

flex: 0 0 calc(); -> Esta propiedad a diferencia de flex-basis, toma 3 valores:
            
                flex: flex-grow flex-shrink flex-basis; 

                flex-grow (factor de crecimiento)
                La propiedad flex-grow de CSS especifica el factor de crecimiento de un elemento flexible (que tiene asignado display:flex), en su dirección principal. El factor de crecimiento especifica qué cantidad del espacio restante dentro del contenedor flexible, debería ocupar el item en cuestión.


                flex-shrink (factor de contraccion/disminucion)
                La propiedad CSS flex-shrink especifica el factor de contracción de un flex item. Los flex items se encogerán para llenar el contenedor de acuerdo a su número flex-shrink , cuando el tamaño por defecto de los flex items sea mayor al de su contenedor flex container.

                flex-basis (tamaño base)
                La propiedad de CSS flex-basis especifíca la base flexible, la cual es el tamaño inicial de un elemento flexible.

Order -> 
    La propiedad CSS order especifica el orden utilizado para disponer los elementos en su contenedor flexible. Los elementos estarán  dispuestos en orden ascendente (si es menor numero se mostrara primero) según el valor de order. Los elementos con el mismo valor de order se dispondrán en el orden en el cual aparecen en el código fuente.

flex-wrap -> La propiedad flex-wrap de CSS especifica si los elementos "hijos" son obligados a permanecer en una misma línea o pueden fluir en varias líneas.
    ejemplo: tenemos 3 contenedores, y queremos que los primeras 2 me abarquen el 50% y 50% , por default esto se veria raro ya que el tercer contenedor no se iria por debajo de estos, si no mas bien opcuparia un espacio en la misma fila, si queremos que la 3er caja se vaya para abajo necesitamos un flex-wrap: wrap, y esto es como decir: el contenedor 1 ocupa 50%, el 2do 50%, pon la otra caja en la siguiente linea

    %es MUY IMPORTANTE definir el flex-wrap, ya que si no se define no el contenido sobrante no se va por debajo (la siguiente linea), y esto es por que por defecto esto es flex-wrap: nowrap;

