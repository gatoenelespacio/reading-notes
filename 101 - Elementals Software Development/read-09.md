
## Respuesta de la lectura09

### ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

1. Booleno. Solo tiene los valores de "true" o "false"
2. null. Palabra clave que denota un valo nulo.
3. undefined. Propiedad de alto valor cuyo valor no está definido
4. number. Representa los números enteros como números de punto flotante.
5. bigint. Permite trabajar con números enteros.
6. string. Una secuencia de carácteres. Se define entre comillas simples y dobles.

### ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?

- Código: 
  if (condición) {
    // Código a ejecutar si la condición es verdadera
} else {
    // Código a ejecutar si la condición es falsa
}

- If: Si la condición es positiva, se ejecuta el código que esta en llaves.
- else: Se ejecuta si la condición del "if" es negativa.
  
### ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

- Operador aritmético: Utilizado para realizar operaciones.
- Operadores de comparación: Su mismo nombre lo define, compará valores y nos da un resultado booleno.
- Operadores lógico: Utilizados para combinar valores boolenos.
- Operadores de asignación: Asignan valores a las variables(=,+=,-=,etc)
- Operadores de decremento y incremento: Utilizado para aumentar o disminuir el valor de una variable. 
- Operadores de tipo: Comprueban el tipo de una variable {typeof}
- Operadores ternarios: Forma para realizar una evaluación condicional(condición ? expr1 : expr2)

## Operadores aritméticos 

1. Suma: "let suma = 5 + 3; // 8"
2. Resta: "let resta = 10 - 4; // 6"
3. Multiplicación: "let multiplicacion = 6 * 7; // 42"
4. División: "let division = 20 / 5; // 4"
5. Modulo (%): "let modulo = 10 % 3; // 1"
6. Exponenciación (**): "let potencia = 2 ** 3; // 8"

### Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

1. Declaracion de variables.-

- Var: "var nombre = "Juan";" 
- Let: "let edad = 30;"
- const: "const pi = 3.14;"

2. Diferencia entre var, let y const.- 

- Var: Su alcance de función o global, permite la re-asignación
- let: Solo son accesibles dentro del bloque "{}", tambien permite la re-asignación.
- const: No permite la re-asignacion, pero si la modificación de objetos y tambien son accesibles dentro de su bloque "{}"