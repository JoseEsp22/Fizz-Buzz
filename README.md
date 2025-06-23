# 🧠 FizzBuzz en Consola del Navegador

Este es un pequeño programa del clásico juego **FizzBuzz**, implementado como una aplicación de consola para ejecutarse directamente en el navegador. El usuario introduce un número y el programa devuelve una lista del 1 al número ingresado, con sustituciones según las reglas del juego.

---

## 📋 Planificación

### 🎮 Interfaz

Este programa **no tiene una interfaz gráfica**. Toda la interacción se da a través de:

- Una **ventana emergente** (`prompt`) para introducir el número.
- La **consola del navegador** (`console.log`) para mostrar los resultados.

### 🔢 Entrada

- El usuario introduce un número entero positivo mediante una ventana emergente.

### 🎯 Salida

- Se genera una lista del 1 al número ingresado.
- Cada número es evaluado con las siguientes reglas:
  - Si es divisible por **3**, se muestra: `[ ] Fizz`
  - Si es divisible por **5**, se muestra: `[ ] Buzzy`
  - Si es divisible por **3 y 5**, se muestra: `[ ] FizzBuzz`
  - En cualquier otro caso, se muestra el número tal cual.

---

## 💻 Ejemplo de Salida

Si el usuario introduce el número `15`, la salida en la consola será:

1
2
[ ] Fizz
4
[ ] Buzzy
[ ] Fizz
7
8
[ ] Fizz
[ ] Buzzy
11
[ ] Fizz
13
14
[ ] FizzBuzz


---

## 🚀 Cómo Ejecutarlo

1. Abre tu navegador web.
2. Presiona `F12` o haz clic derecho y selecciona **"Inspeccionar"** para abrir las herramientas de desarrollo.
3. Dirígete a la pestaña **Consola**.
4. Pega el código del programa (ver archivo `fizzbuzz.js` o el código fuente).
5. Presiona **Enter** y sigue las instrucciones.

---

## ✅ Requisitos

- Un navegador moderno (Chrome, Firefox, Edge, etc.).
- Conocimiento básico para acceder a la consola del navegador.

---

## 📁 Estructura del Proyecto

fizzbuzz/
├── README.md
└── fizzbuzz.js


---

## 📄 Licencia

Este proyecto está disponible bajo la licencia MIT.
