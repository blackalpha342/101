## ¿Qué es el DOM?

El DOM (Document Object Model) es una representación en forma de árbol de los elementos de una página web. Permite a los lenguajes de programación, como JavaScript, acceder y manipular la estructura, el contenido y el estilo de una página web de manera dinámica.

## Relación entre el DOM y JavaScript

JavaScript usa el DOM para interactuar con los elementos de una página web, permitiendo modificar su contenido, estructura y apariencia en tiempo real. Esto hace posible la creación de páginas dinámicas e interactivas.

## Método para seleccionar un elemento del DOM por su ID

El método más común es document.getElementById(). Se usa de la siguiente manera:

let elemento = document.getElementById("miElemento");


Esto almacena en la variable elemento la referencia al elemento con el ID miElemento.

## Método para cambiar el color de fondo de un elemento en el DOM

Se puede usar la propiedad style.backgroundColor. Ejemplo de implementación:

let elemento = document.getElementById("miElemento");
elemento.style.backgroundColor = "blue";


Esto cambiará el color de fondo del elemento con ID miElemento a azul.
