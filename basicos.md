# Ejercicios básicos

¡Bienvenido a este repositorio de ejercicios básicos de JavaScript!

## Descripción

Esta colección de ejercicios está diseñada para personas que están dando sus primeros pasos en el mundo de la programación con JavaScript. Aquí encontrarás una serie de desafíos que te ayudarán a practicar y reforzar tus conocimientos en los fundamentos del lenguaje.
Requisitos Previos
Para sacar el máximo provecho de estos ejercicios, es recomendable que tengas conocimientos básicos de JavaScript, incluyendo:

- Tipos de datos y operadores
- Variables y constantes
- Estructuras de control (condicionales y bucles)
- Manipulación de strings
- Trabajo con arreglos
- Funciones
- Objetos literales

Si aún no estás familiarizado con estos conceptos, te sugerimos que primero revises algunos recursos introductorios. Puedes encontrar excelentes tutoriales y cursos gratuitos en plataformas como YouTube, FreeCodeCamp o MDN Web Docs.

## Ejercicios

### 1. Saludo personalizado
Crea una función que reciba un nombre como parámetro y devuelva un saludo personalizado.

```js
function saludar(nombre) {
  // Tu código aquí
}

console.log(saludar("Ana")); // Debería imprimir: "¡Hola, Ana!"
```

### 2. Suma de dos números
Implementa una función que reciba dos números como parámetros y devuelva su suma.

```js
function sumar(a, b) {
  // Tu código aquí
}

console.log(sumar(5, 3)); // Debería imprimir: 8
```

### 3. Resta de dos números

Crea una función que reciba dos números como parámetros y devuelva el resultado de restar el segundo del primero.

```js
function restar(a, b) {
  // Tu código aquí
}

console.log(restar(10, 4)); // Debería imprimir: 6
```

### 4. Multiplicación de dos números

Escribe una función que reciba dos números como parámetros y devuelva su producto.

```js
function multiplicar(a, b) {
  // Tu código aquí
}

console.log(multiplicar(6, 7)); // Debería imprimir: 42
```

### 5. División de dos números

Implementa una función que divida el primer número por el segundo. Recuerda manejar el caso de división por cero.

```js
function dividir(a, b) {
  // Tu código aquí
}

console.log(dividir(15, 3)); // Debería imprimir: 5
console.log(dividir(10, 5)); // Debería imprimir: 2
```

### 6. Calculadora simple
Implementa una función que reciba dos números y un operador (+, -, *, /) como parámetros y realice la operación correspondiente.

```js
function calcular(num1, num2, operador) {
  // Tu código aquí
}

console.log(calcular(5, 3, "+")); // Debería imprimir: 8
console.log(calcular(15, 3, "-")); // Debería imprimir: 12
console.log(calcular(5, 2, "*")); // Debería imprimir: 10
console.log(calcular(10, 5, "/")); // Debería imprimir: 2
```

### 7. Número par o impar
Escribe una función que determine si un número es par o impar.

```js
function esPar(numero) {
  // Tu código aquí
}

console.log(esPar(4)); // Debería imprimir: true
console.log(esPar(7)); // Debería imprimir: false
```

### 8. Comparar dos números
Escribe una función que compare dos números y devuelva un mensaje indicando cuál es mayor o si son iguales.

```js
function compararNumeros(a, b) {
  // Tu código aquí
}

console.log(compararNumeros(5, 3));  // Debería imprimir: "5 es mayor que 3"
console.log(compararNumeros(2, 2));  // Debería imprimir: "Los números son iguales"
console.log(compararNumeros(1, 10)); // Debería imprimir: "10 es mayor que 1"
```

### 9. Mayor de edad
Crea una función que determine si una persona es mayor de edad (18 años o más).

```js
function esMayorDeEdad(edad) {
  // Tu código aquí
}

console.log(esMayorDeEdad(20)); // Debería imprimir: true
console.log(esMayorDeEdad(16)); // Debería imprimir: false
```

### 10. Calificación
Escribe una función que convierta una calificación numérica a una letra según la siguiente escala:

90-100: 'A'
80-89: 'B'
70-79: 'C'
60-69: 'D'
0-59: 'F'

```js
function obtenerCalificacion(puntuacion) {
  // Tu código aquí
}

console.log(obtenerCalificacion(85)); // Debería imprimir: 'B'
console.log(obtenerCalificacion(92)); // Debería imprimir: 'A'
console.log(obtenerCalificacion(50)); // Debería imprimir: 'F'
```

### 11. Día de la semana
Implementa una función que reciba un número del 1 al 7 y devuelva el día de la semana correspondiente (1 es lunes, 7 es domingo). Si el número está fuera de este rango, debe devolver "Número inválido".

```js
function obtenerDiaSemana(numero) {
  // Tu código aquí
}

console.log(obtenerDiaSemana(1)); // Debería imprimir: "Lunes"
console.log(obtenerDiaSemana(5)); // Debería imprimir: "Viernes"
console.log(obtenerDiaSemana(8)); // Debería imprimir: "Número inválido"
```

### 12. Verificar contraseña
Crea una función que verifique si una contraseña cumple con los siguientes criterios:

Tiene al menos 8 caracteres
Contiene al menos una letra mayúscula
Contiene al menos un número

```js
function esContrasenaValida(contrasena) {
  // Tu código aquí
}

console.log(esContrasenaValida("Abc12345")); // Debería imprimir: true
console.log(esContrasenaValida("abcdefgh")); // Debería imprimir: false
console.log(esContrasenaValida("Ab1")); // Debería imprimir: false
```

### 13. Determinar el estado del agua
Implementa una función que determine el estado del agua (sólido, líquido o gaseoso) según su temperatura en grados Celsius.

```js
function estadoAgua(temperatura) {
  // Tu código aquí
}

console.log(estadoAgua(0));    // Debería imprimir: "sólido"
console.log(estadoAgua(25));   // Debería imprimir: "líquido"
console.log(estadoAgua(100));  // Debería imprimir: "gaseoso"
```

### 14. ¿Puedo montar en la montaña rusa?
Crea una función que determine si un niño puede montar en la montaña rusa basándose en su altura.

```js
function puedoMontarMontanaRusa(alturaCm) {
  // Tu código aquí
  // La altura mínima es 120 cm
}

console.log(puedoMontarMontanaRusa(130)); // Debería imprimir: "¡Sí, puedes montar!"
console.log(puedoMontarMontanaRusa(110)); // Debería imprimir: "Lo siento, aún no puedes montar."
```

### 15. Elegir el sabor de helado
Escribe una función que sugiera un sabor de helado según el color favorito.

```js
function saborHelado(colorFavorito) {
  // Tu código aquí
  // Opciones: rojo -> fresa, azul -> menta, amarillo -> limón, otro -> chocolate
}

console.log(saborHelado("rojo"));    // Debería imprimir: "Te recomiendo un helado de fresa"
console.log(saborHelado("verde"));   // Debería imprimir: "Te recomiendo un helado de chocolate"
```

### 16. Juego de piedra, papel o tijera
Escribe una función que determine el ganador en un juego de piedra, papel o tijera.

```js
function piedraPapelTijera(jugador1, jugador2) {
  // Tu código aquí
  // Recuerda: Piedra gana a Tijera, Tijera gana a Papel, Papel gana a Piedra
}

console.log(piedraPapelTijera("piedra", "tijera")); // Debería imprimir: "¡Gana Jugador 1!"
console.log(piedraPapelTijera("papel", "papel"));   // Debería imprimir: "¡Empate!"
```

### 17. El Clasificador de Películas
Vamos a crear un programa que clasifique películas según la edad recomendada.

```js
function clasificarPelicula(edad) {
  // Instrucciones:
  // 1. Si la edad es menor a 7, la película es "Apta para todos los públicos"
  // 2. Si la edad está entre 7 y 12, la película es "Recomendada para mayores de 7 años"
  // 3. Si la edad está entre 13 y 17, la película es "Recomendada para mayores de 13 años"
  // 4. Si la edad es 18 o mayor, la película es "Solo para adultos"
  // Usa 'if', 'else if' y 'else' para crear estas condiciones

  // Tu código aquí
}

console.log(clasificarPelicula(6));  // Debería imprimir: "Apta para todos los públicos"
console.log(clasificarPelicula(10)); // Debería imprimir: "Recomendada para mayores de 7 años"
console.log(clasificarPelicula(15)); // Debería imprimir: "Recomendada para mayores de 13 años"
console.log(clasificarPelicula(18)); // Debería imprimir: "Solo para adultos"
```

### 18. El Evaluador de Notas
Hagamos un programa que nos dé un mensaje según la nota obtenida en un examen.

```js
function evaluarNota(nota) {
  // Instrucciones:
  // 1. Si la nota es 10, el mensaje es "¡Excelente!"
  // 2. Si la nota está entre 8 y 9, el mensaje es "Muy bien"
  // 3. Si la nota está entre 6 y 7, el mensaje es "Bien, pero puedes mejorar"
  // 4. Si la nota está entre 5 y 6, el mensaje es "Aprobado por poco"
  // 5. Si la nota es menor que 5, el mensaje es "Necesitas estudiar más"
  // Usa 'if', 'else if' y 'else' para crear estas condiciones

  // Tu código aquí
}

console.log(evaluarNota(10)); // Debería imprimir: "¡Excelente!"
console.log(evaluarNota(8));  // Debería imprimir: "Muy bien"
console.log(evaluarNota(6));  // Debería imprimir: "Bien, pero puedes mejorar"
console.log(evaluarNota(5));  // Debería imprimir: "Aprobado por poco"
console.log(evaluarNota(4));  // Debería imprimir: "Necesitas estudiar más"
```

### 19. ¿Es mayor de 10?
Crea una función que determine si un número es mayor que 10.

```js
function esMayorDeDiez(numero) {
  // Tu código aquí
}

console.log(esMayorDeDiez(15)); // Debería imprimir: "Es mayor que 10"
console.log(esMayorDeDiez(8));  // Debería imprimir: "No es mayor que 10"
```

### 20. Clima frío o cálido
Escribe una función que determine si la temperatura es fría (menos de 15 grados) o cálida (15 o más grados).

```js
function clima(temperatura) {
  // Tu código aquí
}

console.log(clima(10)); // Debería imprimir: "Hace frío"
console.log(clima(20)); // Debería imprimir: "Hace calor"
```

### 21. Contar hasta 10
Escribe un bucle que cuente del 1 al 10 e imprima cada número.

```js
function contarHastaDiez() {
  // Tu código aquí
}
```

contarHastaDiez();
// Debería imprimir:
// 1
// 2
// 3
// ...
// 10

### 22. Suma de números
Crea una función que sume todos los números del 1 al 100 usando un bucle.

```js
function sumarHastaCien() {
  // Tu código aquí
}

console.log(sumarHastaCien()); // Debería imprimir: 5050
```

### 23. Tabla de multiplicar
Escribe una función que imprima la tabla de multiplicar del 5 (del 1 al 10).

```js
function tablaDelCinco() {
  // Tu código aquí
}

tablaDelCinco();
// Debería imprimir:
// 5 x 1 = 5
// 5 x 2 = 10
// ...
// 5 x 10 = 50
```

### 24. Contar pares
Crea una función que cuente e imprima los números pares del 1 al 20.

```js
function contarPares() {
  // Tu código aquí
}

contarPares();
// Debería imprimir:
// 2
// 4
// ...
// 20
```

### 25. Factorial
Implementa una función que calcule el factorial de un número usando un bucle.

```js
function calcularFactorial(numero) {
  // Tu código aquí
}

console.log(calcularFactorial(5)); // Debería imprimir: 120
```

### 26. Revertir una cadena
Escribe una función que invierta una cadena de texto usando un bucle.

```js
function revertirCadena(texto) {
  // Tu código aquí
}

console.log(revertirCadena("Hola")); // Debería imprimir: "aloH"
```

### 27. Contar vocales
Crea una función que cuente el número de vocales en una cadena de texto.

```js
function contarVocales(texto) {
  // Tu código aquí
}

console.log(contarVocales("Hola Mundo")); // Debería imprimir: 4
```

### 28. Imprimir patrón de asteriscos
Escribe una función que imprima un patrón de asteriscos en forma de triángulo.

```js
function imprimirTriangulo(altura) {
  // Tu código aquí
}

imprimirTriangulo(5);
// Debería imprimir:
// *
// **
// ***
// ****
// *****
```

### 29. Fibonacci
Implementa una función que genere los primeros n números de la secuencia de Fibonacci.

```js
function fibonacci(n) {
  // Tu código aquí
}

console.log(fibonacci(8)); // Debería imprimir: [0, 1, 1, 2, 3, 5, 8, 13]
```

### 30. Encontrar el número mayor
Escribe una función que encuentre el número más grande en un array usando un bucle.

```js
function encontrarMayor(numeros) {
  // Tu código aquí
}

console.log(encontrarMayor([3, 7, 2, 9, 1])); // Debería imprimir: 9
```

### 31. Sumar elementos de un array
Crea una función que sume todos los elementos de un array usando un bucle.

```js
function sumarArray(numeros) {
  // Tu código aquí
}

console.log(sumarArray([1, 2, 3, 4, 5])); // Debería imprimir: 15
```

### 32. Contar ocurrencias
Implementa una función que cuente cuántas veces aparece un elemento en un array.

```js
function contarOcurrencias(array, elemento) {
  // Tu código aquí
}

console.log(contarOcurrencias([1, 2, 3, 2, 4, 2, 5], 2)); // Debería imprimir: 3
```

### 33. Eliminar duplicados
Escribe una función que elimine los elementos duplicados de un array usando un bucle.

```js
function eliminarDuplicados(array) {
  // Tu código aquí
}

console.log(eliminarDuplicados([1, 2, 2, 3, 4, 4, 5])); // Debería imprimir: [1, 2, 3, 4, 5]
```

### 34. Multiplicar matrices
Crea una función que multiplique dos matrices usando bucles anidados.

```js
function multiplicarMatrices(matriz1, matriz2) {
  // Tu código aquí
}

const m1 = [[1, 2], [3, 4]];
const m2 = [[5, 6], [7, 8]];
console.log(multiplicarMatrices(m1, m2)); // Debería imprimir: [[19, 22], [43, 50]]
```

### 35. Validar palíndromo
Implementa una función que verifique si una palabra es un palíndromo usando un bucle.

```js
function esPalindromo(palabra) {
  // Tu código aquí
}

console.log(esPalindromo("radar")); // Debería imprimir: true
console.log(esPalindromo("hola"));  // Debería imprimir: false
```

### 36. Generar números primos
Escribe una función que genere los primeros n números primos usando bucles.

```js
function generarPrimos(n) {
  // Tu código aquí
}

console.log(generarPrimos(5)); // Debería imprimir: [2, 3, 5, 7, 11]
```

### 37. Ordenar array (Bubble Sort)
Implementa el algoritmo de ordenamiento de burbuja usando bucles.

```js
function bubbleSort(array) {
  // Tu código aquí
}

console.log(bubbleSort([64, 34, 25, 12, 22, 11, 90])); // Debería imprimir: [11, 12, 22, 25, 34, 64, 90]
```

### 38. Rotar array
Crea una función que rote los elementos de un array k posiciones a la derecha.

```js
function rotarArray(array, k) {
  // Tu código aquí
}

console.log(rotarArray([1, 2, 3, 4, 5], 2)); // Debería imprimir: [4, 5, 1, 2, 3]
```

### 39. Espiral de números
Implementa una función que genere una matriz en espiral de n x n.

```js
function generarEspiral(n) {
  // Tu código aquí
}

console.log(generarEspiral(3));
// Debería imprimir:
// [
//   [1, 2, 3],
//   [8, 9, 4],
//   [7, 6, 5]
// ]
```

### 40. Juego del ahorcado
Crea una versión simple del juego del ahorcado usando bucles.

```js
function jugarAhorcado(palabra) {
  // Tu código aquí
  // Usa bucles para implementar la lógica del juego
  // Pide al usuario que adivine letras hasta que complete la palabra o se quede sin intentos
}

jugarAhorcado("javascript");
// Este juego requerirá interacción con el usuario y múltiples bucles para manejar los intentos y actualizar el estado del juego
```