# 📸 PhonixCam

> Una solución moderna de transmisión y seguridad de video en tiempo real, impulsada por IA y optimizada para la web.

[![Website](https://shields.io)](https://phonixcam.lrcompany.site/)

**PhonixCam** es una plataforma web desarrollada por **lrcompany**(mi persona) que transforma dispositivos móviles en herramientas inteligentes de seguridad y captura de video. Al integrar capacidades de inteligencia artificial, procesamiento multimedia y geolocalización, permite transmisiones estables y seguras directamente en la nube.

🔗 **Despliegue oficial:** [https://phonixcam.lrcompany.site/](https://phonixcam.lrcompany.site/)

---

## ✨ Características Principales

*   **Transmisión en Tiempo Real:** Flujos de video y audio en directo de alta calidad y baja latencia.
*   **Diseño Responsivo:** Interfaz moderna e intuitiva adaptada para dispositivos móviles y de escritorio.
*   **Seleccion de calidad:** Tiene varias opciones para grabar ya sea 180p o 2160p(4k)
*   **Cumplimiento de Privacidad:** Control absoluto sobre los datos compartidos, respetando las normativas de protección vigentes.

## 🛠️ Stack Tecnológico

El proyecto es una aplicación web pura (Client-Side) que se ejecuta directamente en el navegador sin dependencias de servidor:

*   **Frontend:** HTML5, CSS3 y JavaScript Moderno (Vanilla JS).
*   **Captura de Pantalla:** [Screen Capture API](https://mozilla.org) (`getDisplayMedia`) para la captura nativa del sistema operativo.
*   **Procesamiento y Codificación:** [MediaStream Recording API](https://mozilla.org) (`MediaRecorder`) con el códec de video **VP8** (`video/webm;codecs=vp8`).
*   **Almacenamiento:** Generación local de archivos binarios (`Blob`) descargables instantáneamente.

##  📄 Licencia

Este proyecto está bajo la Licencia **MIT**

---

Desarrollado con ❤️ por lrcompanyVE(https://github.com)
