# Operaciones Matemáticas y Manejo de Cadenas en JavaScript.

## Descripción del Proyecto:

### Objetivo
El objetivo de este proyecto es demostrar el uso de funciones matemáticas y el manejo de cadenas de texto en JavaScript. A través de este código, se pueden realizar diversas operaciones matemáticas, como cálculos de redondeo, generación de números aleatorios y operaciones trigonométricas, así como la manipulación de cadenas para formar un nombre completo.

### Estructura del Proyecto

1. **Importación de Constantes Matemáticas:**
   - Se declara la constante `PI`, que utiliza la propiedad `Math.PI` para obtener el valor de π (Pi), esencial en muchas operaciones matemáticas.

2. **Funciones Matemáticas:**
Aquí tienes una descripción de los diferentes tipos de métodos utilizados en el código, junto con ejemplos para cada uno:

### 1. **Métodos de Redondeo**

Estos métodos se utilizan para redondear números a enteros.

- **`Math.round()`**: Redondea un número al entero más cercano.
  ```javascript
  console.log(Math.round(9.85)); // Resultado: 10
  ```

- **`Math.floor()`**: Redondea un número hacia abajo al entero más cercano.
  ```javascript
  console.log(Math.floor(3.7)); // Resultado: 3
  ```

- **`Math.ceil()`**: Redondea un número hacia arriba al entero más cercano.
  ```javascript
  console.log(Math.ceil(3.1)); // Resultado: 4
  ```

### 2. **Métodos de Mínimo y Máximo**

Estos métodos se utilizan para encontrar el valor mínimo o máximo de un conjunto de números.

- **`Math.min()`**: Devuelve el número más pequeño de un conjunto de números.
  ```javascript
  console.log(Math.min(-5, 3, 20, 50, 5, 10, 0)); // Resultado: -5
  ```

- **`Math.max()`**: Devuelve el número más grande de un conjunto de números.
  ```javascript
  console.log(Math.max(-5, 3, 20, 50, 5, 10, 0)); // Resultado: 50
  ```

### 3. **Métodos Aleatorios**

Estos métodos se utilizan para generar números aleatorios.

- **`Math.random()`**: Genera un número pseudoaleatorio entre 0 (incluido) y 1 (excluido).
  ```javascript
  const radNUM = Math.random();
  console.log(radNUM); // Ejemplo de resultado: 0.123456789
  ```

- **Generar un número entero aleatorio entre un rango específico**:
  ```javascript
  const Num = Math.floor(Math.random() * 11); // Número entre 0 y 10
  console.log(Num); // Ejemplo de resultado: 7
  ```

### 4. **Métodos de Raíz y Potencia**

Estos métodos se utilizan para realizar cálculos de raíces cuadradas y potencias.

- **`Math.sqrt()`**: Devuelve la raíz cuadrada de un número.
  ```javascript
  console.log(Math.sqrt(100)); // Resultado: 10
  ```

- **`Math.pow()`**: Devuelve la base elevada a la potencia del exponente.
  ```javascript
  console.log(Math.pow(3, 2)); // Resultado: 9 (3 elevado a 2)
  ```

### 5. **Constantes Matemáticas**

Estas son constantes importantes en matemáticas.

- **`Math.PI`**: Representa el valor de π (pi), aproximadamente 3.14159.
  ```javascript
  console.log(Math.PI); // Resultado: 3.141592653589793
  ```

- **`Math.E`**: Representa la base de los logaritmos naturales, aproximadamente 2.71828.
  ```javascript
  console.log(Math.E); // Resultado: 2.718281828459045
  ```

### 6. **Logaritmos**

Estos métodos se utilizan para calcular logaritmos naturales.

- **`Math.log()`**: Devuelve el logaritmo natural de un número.
  ```javascript
  console.log(Math.log(2)); // Resultado: 0.6931471805599453
  ```

### 7. **Funciones Trigonométricas**

Estos métodos se utilizan para calcular valores trigonométricos.

- **`Math.sin()`**: Devuelve el seno de un ángulo (en radianes).
  ```javascript
  console.log(Math.sin(0)); // Resultado: 0
  ```

- **`Math.cos()`**: Devuelve el coseno de un ángulo (en radianes).
  ```javascript
  console.log(Math.cos(0)); // Resultado: 1
  ```

### Resumen

Cada uno de estos métodos forma parte del objeto `Math` en JavaScript y permite realizar una variedad de cálculos matemáticos de forma eficiente. Puedes combinar estos métodos para resolver problemas más complejos o para generar resultados específicos según tus necesidades. Si necesitas más ejemplos o detalles sobre algún método en particular, ¡házmelo saber!

3. **Manejo de Cadenas de Texto:**
   - Se declaran variables para el nombre, apellido y edad.
   - Se utiliza el operador `+` para concatenar estas variables y formar una cadena que contiene el nombre completo y la edad.
   - Se imprime el nombre completo y la edad en la consola.
