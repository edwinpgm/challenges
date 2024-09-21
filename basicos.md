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

### 8. Contar vocales
Crea una función que cuente el número de vocales en una cadena de texto.

```js
function contarVocales(texto) {
  // Tu código aquí
}

console.log(contarVocales("Hola Mundo")); // Debería imprimir: 4
console.log(contarVocales("Ana")); // Debería imprimir: 2
console.log(contarVocales("Salvador")); // Debería imprimir: 3
console.log(contarVocales("Josh")); // Debería imprimir: 1
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