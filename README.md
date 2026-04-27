# 🎵 Multi-Playlist Pro

Una aplicación web ligera y privada para gestionar listas de reproducción híbridas. Combina música de plataformas de streaming con archivos almacenados en la nube y archivos locales, todo en una única interfaz.

## 🚀 Características

- **Soporte Multi-Plataforma:** Reproduce enlaces de YouTube, Spotify y SoundCloud.
- **Integración con la Nube:** Soporte optimizado para streaming directo desde **Dropbox**.
- **Almacenamiento Local:** Permite cargar archivos MP3/WAV directamente en el navegador usando `IndexedDB` (los archivos permanecen guardados incluso al cerrar la pestaña).
- **Privacidad Total:** La aplicación no tiene servidor; todos tus datos y archivos se guardan localmente en tu dispositivo.
- **Portabilidad:** Sistema de Importación/Exportación mediante archivos JSON para mover tus listas entre dispositivos.
- **Interfaz Adaptable:** Diseño oscuro (Dark Mode) optimizado para escritorio y dispositivos móviles.

## 🛠️ Instrucciones de Uso

### 1. Añadir Contenido
- **Enlaces Web:** Escribe el nombre de la canción, pega el link y pulsa "Añadir Link".
- **Archivos Locales:** Usa el botón 📁 para seleccionar un archivo de tu dispositivo. Se guardará de forma permanente en la base de datos del navegador.

### 2. Configuración de la Nube
Para que los archivos de **Dropbox** funcionen:
1. Sube el archivo a tu cuenta.
2. Configura el archivo como **"Público"** o **"Cualquier persona con el enlace"**.
3. Copia el enlace y pégalo en la aplicación.

### 3. Copias de Seguridad
- Usa el botón **Exportar JSON** periódicamente.
- Este archivo contiene los nombres y enlaces de tu lista. 
- *Nota: El JSON no contiene los archivos físicos cargados mediante el botón local, solo sus referencias.*

## 📂 Estructura del Proyecto

- `index.html`: Contiene toda la lógica (HTML5, CSS3 y JavaScript Vanilla). No requiere dependencias externas ni frameworks.

## 🔧 Instalación

1. Clona este repositorio o descarga el archivo `index.html`.
2. Sube el archivo a **GitHub Pages** para tener tu propia URL privada.
3. ¡Disfruta de tu música!

---
*Desarrollado como una herramienta de productividad musical sencilla y eficiente.*
