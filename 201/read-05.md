# Read 05: Estructura de control y Datos en JavaScript 

### 1. ¿Cuáles son los diferentes tipos de estructuras condicionales en JavaScript y en qué situaciones deberías usar cada una?

If: Si la condición es verdadera, se ejecutará el codigo.
Else: Si la condición es falsa, se ejecutará el codigo b. 
Else if: Se utiliza cuando una nueva condición se va a probar, si la primera condición es falsa else if.
switch: Se  usa para especificar varios bloques alternativos que se van a ejecutar. 
Se usan en condiciones secuenciales.

### 2. En el contexto de arreglos en JavaScript, ¿cuál es la diferencia entre los métodos push(), unshift() y splice(), y cuándo usarías cada uno?

- Push(): Añadimos un elemento al final de un array 
- unshift(): Añadimos un elemento al principio de un array 
- splice(): Podemos elimar y guardarlo en un nuevo array.

### 3. ¿Qué diferencias existen entre los bucles for, while y do...while? Proporciona un ejemplo práctico de uso para cada uno.

For y do...while se ejecutan hasta que una condición especificada se evalue como false, a comparación de while que se ejecuta siempre y cuando la condición especificada sea true.
 
 - for: for(let i = 2; i <= 5; i++){
  }
  - while: let i = 1; 
    while (i <= 5) {
    }

- do while: let entrada 
        do {
            entrada = prompt("Bienvenido (escribe "salir" para terminar):")
        } while (entrada !== "salir");

### 4. ¿Cómo se puede recorrer un arreglo en JavaScript utilizando diferentes tipos de bucles y cuál consideras más eficiente según el caso de uso?

- Si no sabes cuantas iteraciones necesitas, usaria while.
- En el caso de ejecutar un código antes de verificar la condición, se utilizaria do..while.

