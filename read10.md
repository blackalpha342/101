
¿Qué es “Control Flow” (Control de Flujo)?
Control Flow (Control de Flujo) en JavaScript
El Control de Flujo en JavaScript se refiere al orden en que se ejecutan las instrucciones en un programa. Normalmente, el código se ejecuta de arriba hacia abajo, pero con estructuras como condicionales (if, switch) y bucles (for, while, do...while), podemos alterar este flujo y hacer que el programa tome decisiones o repita acciones basadas en ciertas condiciones.

¿Qué es una “function” (Función) de JavaScript?
Funciones en JavaScript
Una función en JavaScript es un bloque de código reutilizable que ejecuta una tarea específica. Nos ayuda a escribir código más organizado y modular.
Ejemplo:
function saludar(nombre) {
    return `Hola, ${nombre}!`;
}

console.log(saludar("Juan")); // Output: Hola, Juan!

¿Cuántas veces se ejecutará un bucle “while”?
Un bucle while se ejecutará mientras la condición especificada sea verdadera. Si la condición nunca cambia a false, el bucle puede ser infinito.
Ejemplo:
let contador = 0;

while (contador < 5) {
    console.log(`Iteración número: ${contador}`);
    contador++; // Incrementamos para evitar un bucle infinito
}


¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?
Para agregar un elemento al final de un array en JavaScript, usamos el método .push().
Ejemplo:
let listaDeCompras = ["Pan", "Leche"];
listaDeCompras.push("Huevos");

console.log(listaDeCompras); // ["Pan", "Leche", "Huevos"]
