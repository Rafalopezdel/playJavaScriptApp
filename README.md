# 🛠️ Portafolio de Aplicaciones JavaScript

Este repositorio contiene una colección de pequeñas aplicaciones desarrolladas con **HTML, CSS y JavaScript puro**, enfocadas en la práctica de lógica, manipulación del DOM, estructura de código, y experiencia de usuario sin utilizar frameworks o librerías externas.

---

## 📋 Contenido

1. [🐍 Juego Snake](#-juego-snake)
2. [🧮 Calculadora](#-calculadora)
3. [📝 Control de Tareas](#-control-de-tareas)
4. [⏱️ Cronómetro](#️-cronómetro)
5. [🔐 Cifrador César](#-cifrador-césar)
6. [🎯 Juego del Ahorcado](#-juego-del-ahorcado)

---

## 🐍 Juego Snake

Un juego clásico donde el jugador controla una serpiente que debe alimentarse sin chocar contra sí misma ni los bordes. Utiliza una cuadrícula dinámica creada con HTML y se actualiza en tiempo real mediante ciclos de animación. Incluye detección de colisiones, puntuación automática y reinicio del juego.

- Uso de estructuras bidimensionales para modelar el tablero y controlado por teclado
- Lógica de crecimiento y alimentos aleatorios
- Gestión de puntuación y Game Over

---

## 🧮 Calculadora

Aplicación de calculadora básica que permite realizar operaciones aritméticas simples: suma, resta, multiplicación y división. Estructurada con clases para separar la lógica de cálculo y la visualización.

- Arquitectura basada en POO con las clases `Calculadora` y `Display`
- Control de errores (evita múltiples puntos, validación de entrada)
- Limpieza individual o total del display

---

## 📝 Control de Tareas

To-do list funcional con fecha dinámica y organización de tareas por estado. Los usuarios pueden agregar tareas, marcarlas como completadas, y reordenarlas según su progreso.

- Fecha generada automáticamente usando `Date()`
- Adición de tareas desde formulario con validación
- Interacción mediante clics y orden por estado (pendiente/completado)

---

## ⏱️ Cronómetro

Aplicación de cronómetro funcional con botones de iniciar, pausar, reiniciar y resetear. Ideal para medir intervalos de tiempo de forma simple.

- Precisión con `setInterval`
- Control completo de flujo del cronómetro
- Visualización de tiempo en formato `mm:ss:ms`

---

## 🔐 Cifrador César

Herramienta para encriptar y desencriptar textos usando el cifrado César. Permite definir el número de desplazamientos y obtener resultados en tiempo real.

- Entrada de texto dinámico
- Ajuste personalizado del desplazamiento
- Compatible con mayúsculas, minúsculas y espacios

---

## 🎯 Juego del Ahorcado

Juego clásico del ahorcado con lógica personalizada. El usuario debe adivinar la palabra antes de agotar los intentos.

- Interfaz interactiva con teclado virtual o teclado físico
- Dibujo progresivo del ahorcado en función de los errores
- Palabras elegidas aleatoriamente desde una lista

---

## 🚀 Cómo usar

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/portafolio-js.git

2. Ejecuta el archivo index.html de la app.

✨ Autor
Desarrollado por [Rafael López Delgado]
📧 rafalopezdel@gmail.com