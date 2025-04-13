# 🎯 Adivina el Número – Juego en Python

Este repositorio contiene la práctica final del módulo **Programación Python** del Máster en Big Data.  
El objetivo del proyecto es desarrollar un juego interactivo que permita adivinar un número, aplicando los conocimientos adquiridos en clase: estructuras de control, funciones, validación de entradas, manipulación de archivos, etc.

---

## 🕹️ Descripción del juego

Al ejecutar el programa, el usuario podrá elegir entre varias opciones de juego:

### Menú principal

1. **Partida modo solitario**  
   El ordenador genera aleatoriamente un número entre 1 y 1000. El jugador debe adivinarlo.

2. **Partida 2 jugadores**  
   Un jugador ingresa el número a adivinar y otro intenta descubrirlo.

3. **Estadísticas**  
   Muestra el historial de partidas (ganadas/perdidas, jugador, dificultad) almacenadas en un archivo Excel.

4. **Salir**

---

## 🧠 Dificultades disponibles

Cada modo de juego permite elegir un nivel de dificultad, que define el número máximo de intentos:

- **Fácil**: 20 intentos  
- **Medio**: 12 intentos  
- **Difícil**: 5 intentos

---

## 📦 Estructura del repositorio

- `adivina_numero.ipynb`: Desarrollo del juego y lógica principal en Jupyter Notebook.
- `utils.py`: Funciones auxiliares para validación, generación de número, manejo de intentos, etc.
- `estadisticas.xlsx`: Registro de resultados por jugador, con nombre, resultado y dificultad.

---

## 🧪 Tecnologías y librerías utilizadas

- Python 3.x  
- Jupyter Notebook  
- Pandas (para leer/escribir Excel)  
- `random`, `openpyxl`, `os` (librerías estándar)

---

## 🚀 Cómo ejecutarlo

1. Copia el repositorio:
   ```bash
   git clone https://github.com/fabiogutierrezm/adivina-el-numero.git
   cd adivina-el-numero
