## 1. Tipos de datos en JavaScript y sus diferencias

### **Tipos de datos primitivos**  
- **Number**: Representa números. Ejemplo: `let edad = 25;`
- **String**: Representa texto. Ejemplo: `let nombre = "Juan";`
- **Boolean**: Representa `true` o `false`. Ejemplo: `let esMayor = true;`
- **Undefined**: Variable declarada sin valor. Ejemplo: `let x;`
- **Null**: Ausencia de un valor. Ejemplo: `let y = null;`
- **Symbol**: Valores únicos e inmutables.
- **BigInt**: Para números grandes. Ejemplo: `let bigNumber = 12345678901234567890n;`

### **Tipos de datos complejos**  
- **Object**: Colección de pares clave-valor.  
  ```js
  let persona = { nombre: "Ana", edad: 30 };

let numeros = [1, 2, 3, 4, 5];

function saludar() { console.log("Hola!"); }

let edad = 18;

if (edad >= 18) {
  console.log("Eres mayor de edad.");
} else {
  console.log("Eres menor de edad.");
}

let temperatura = 25;

if (temperatura > 30) {
  console.log("Hace mucho calor.");
} else if (temperatura > 20) {
  console.log("El clima es agradable.");
} else {
  console.log("Hace frío.");
}

| Operador | Descripción | Ejemplo (`a = 10, b = 5`) |
|----------|------------|--------------------------|
| `+` | Suma | `a + b // 15` |
| `-` | Resta | `a - b // 5` |
| `*` | Multiplicación | `a * b // 50` |
| `/` | División | `a / b // 2` |
| `%` | Módulo | `a % b // 0` |
| `**` | Potencia | `a ** 2 // 100` |

| Operador | Descripción | Ejemplo (`a = 10, b = 5`) |
|----------|------------|--------------------------|
| `==` | Igualdad de valor | `a == "10" // true` |
| `===` | Igualdad estricta | `a === "10" // false` |
| `!=` | Diferente | `a != b // true` |
| `<, >, <=, >=` | Comparaciones | `a > b // true` |

| Operador | Descripción | Ejemplo |
|----------|------------|---------|
| `&&` | AND | `(a > 5 && b < 10) // true` |
| `||` | OR | `(a > 5 || b > 10) // true` |
| `!` | NOT | `!(a > b) // false` |



Declaración de variables en JavaScript
Método	Alcance	Puede reasignarse	Se recomienda usar
var	Función	Sí	No recomendado
let	Bloque	Sí	Cuando se necesita reasignar
const	Bloque	No	Para valores constantes

// var: alcance de función, puede reasignarse
var nombre = "Juan";
nombre = "Pedro"; // válido

// let: alcance de bloque, puede reasignarse
let edad = 25;
edad = 30; // válido

// const: alcance de bloque, NO puede reasignarse
const PI = 3.1416;
// PI = 3.14; // ❌ Error, no se puede reasignar
