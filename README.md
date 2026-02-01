# 🎂 Birthday Interactive Experience 🚀

<p align="center">
  <img src="https://img.shields.io/badge/HAPPY-BIRTHDAY-888888?style=for-the-badge" />
  <img src="https://img.shields.io/badge/VIEW-DEMO-2196F3?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CHECK-IT_OUT-FF5722?style=for-the-badge" />
</p>

---

## 📝 Descripción del Proyecto
Este proyecto es una **experiencia web personalizada** diseñada para celebrar un cumpleaños desde una perspectiva de programador. No es solo un mensaje estático; es una interfaz dinámica que combina recuerdos multimedia con un sistema de chat interactivo que emula una terminal de comandos. 

> "El 99.9% de las personas envían un mensaje de texto. Nosotros lo decimos con código." ✨

---

## 🛠️ Tecnologías Utilizadas
He utilizado un stack limpio y moderno para que la web sea rápida y visualmente impactante:

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## ⚙️ Instrucciones de Personalización

Para mantener el estilo profesional y dinámico, sigue estos pasos para editar el contenido:

### 🖼️ Cambiar Fotos y Videos
El sistema busca automáticamente los archivos en la estructura de carpetas `assets/`:
* **Fotos:** Guarda tus imágenes en `assets/img/`. Se recomienda usar nombres como `foto1.jpg`, `foto2.jpg`.
* **Video:** Sustituye el archivo `video.mp4` en la raíz de `assets/`.
* **Música:** Cambia el archivo en `assets/music/bg-audio.mp3`.

### 💬 Editar el Chat Interactivo
Para modificar lo que dice la terminal, abre el archivo `script.js` y localiza el bloque de mensajes:
```javascript
// Edita estos textos para personalizar el mensaje
const chatMessages = [
    "> Iniciando sistema...",
    "> Cargando recuerdos...",
    "> ¡Feliz Cumpleaños! 🎉"
];