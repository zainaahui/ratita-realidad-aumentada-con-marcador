[readme.md](https://github.com/user-attachments/files/34756712/readme.md)
# Realidad Aumentada con AR.js

Este proyecto es una aplicación web de Realidad Aumentada (RA) que permite visualizar contenido interactivo en 3D utilizando la cámara de tu dispositivo y un marcador impreso.

## ¿Cómo funciona?

1. **Detección de Patrones:** La aplicación utiliza la librería AR.js para acceder a la cámara del navegador web.
2. **Reconocimiento del Marcador:** Analiza en tiempo real los fotogramas de la cámara en busca del patrón geométrico específico del marcador.
3. **Renderizado 3D:** Una vez que la cámara detecta y ubica el marcador, posiciona y proyecta el objeto virtual tridimensional encima de este, ajustándose dinámicamente según la perspectiva y el movimiento.

## Requisitos Previos

Para que la experiencia funcione correctamente, es **indispensable** contar con el marcador físico:

1. **Descarga el marcador:** Asegúrate de descargar la imagen oficial del marcador (compatible con blanco y negro) desde el repositorio o enlace provisto.
2. **Impresión:** Imprime el marcador en una hoja de papel (preferiblemente en papel mate para evitar reflejos de luz que puedan dificultar la lectura de la cámara).
3. **Dispositivo:** Abre la aplicación en un navegador web compatible con acceso a la cámara (como Google Chrome o Safari en tu smartphone, tablet o computadora con webcam).
