# Proyecto: Juego del Dinosaurio (Estilo Chrome Dino)

Este proyecto es una recreación del clásico juego del dinosaurio sin conexión de Google Chrome. Está desarrollado utilizando únicamente HTML, CSS y JavaScript, sin frameworks externos.

---

## Descripción General

El jugador controla un dinosaurio que debe saltar para esquivar cactus. El juego aumenta su velocidad a medida que el jugador anota más puntos, simulando un ciclo de día y noche.

---

## Estructura de Archivos

```
dino-juego/
├── index.html       # Página principal con el juego
├── img/
│   ├── dino.png     # Sprite del dinosaurio
│   ├── suelo.png    # Imagen del suelo
│   ├── cactus1.png  # Imagen de cactus individual
│   ├── cactus2.png  # Imagen de cactus doble
│   └── nube.png     # Imagen de la nube
```

---

## Funcionamiento

- El dinosaurio salta con la tecla espacio.
- Si colisiona con un obstáculo, el juego termina y se muestra el mensaje "Game Over".
- La velocidad del juego aumenta según el puntaje.
- El fondo cambia dependiendo de la cantidad de puntos (día, tarde, noche).

---

## Características Técnicas

- El juego usa `requestAnimationFrame` para una animación fluida.
- Usa `getBoundingClientRect()` para detección de colisiones.
- Los obstáculos y las nubes se generan y eliminan dinámicamente.
- El puntaje se muestra en la esquina superior del contenedor.

---

## Cómo Ejecutarlo

1. Asegúrese de tener todos los archivos en la misma carpeta, incluyendo la carpeta `img`.
2. Abra el archivo `index.html` en cualquier navegador moderno.
3. Presione la barra espaciadora para comenzar a jugar.

---

## Mejoras Sugeridas

- Añadir un sistema de puntaje alto (high score).
- Incluir efectos de sonido y música.
- Añadir un botón de reinicio visible en pantalla.
- Compatibilidad para dispositivos móviles (toques en pantalla).

---

## Créditos

Desarrollado como práctica de animación, manipulación del DOM y lógica de juegos con JavaScript puro.
