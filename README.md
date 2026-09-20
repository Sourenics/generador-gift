# 🎁 Generador GIFT

> ⚠️ **Vibe-coded project**
> Este proyecto ha sido desarrollado siguiendo la filosofía *vibe coding* (con la ayuda de IA). Es una herramienta experimental y práctica, creada para resolver una necesidad concreta y en constante desarrollo, por lo que está sujeta a continuas mejoras y ajustes. ¡Cualquier sugerencia o feedback es más que bienvenido!

[![Live Demo](https://img.shields.io/badge/Demo-Online-brightgreen?style=for-the-badge&logo=github)](https://sourenics.github.io/generador-gift/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](LICENSE)

---

## 🚀 Probar la Aplicación

No requiere registros, servidores ni configuraciones avanzadas. Puedes usar la herramienta directamente desde tu navegador:

👉 **[Acceder a Generador GIFT (Página Oficial)](https://sourenics.github.io/generador-gift/)**

También puedes descargar el archivo `.html` del repositorio y abrirlo con doble clic: funciona sin conexión a internet.

---

## ✨ Características Principales

* 📝 **7 tipos de pregunta:** opción múltiple (una o varias respuestas correctas), verdadero/falso, respuesta corta, emparejamiento, numérica (con margen de error o rango) y ensayo de respuesta abierta.
* 👁️ **Vista previa en vivo:** el código GIFT se genera y se resalta por sintaxis (verde para lo correcto, rojo para lo incorrecto) a medida que escribes.
* 💾 **Guardado automático en el navegador:** tu examen se conserva aunque cierres la pestaña; no se pierde el progreso entre sesiones.
* 📤 **Exportación directa:** descarga el archivo listo para importar en el banco de preguntas de Moodle, o cópialo al portapapeles.
* 🗂️ **Categoría y retroalimentación:** define la categoría de Moodle y añade retroalimentación general por pregunta.
* ⚡ **100% Client-side (sin servidor):** funciona directamente en tu navegador. No requiere registro ni conexión a bases de datos.
* 🔒 **Privacidad garantizada:** las preguntas que escribes no salen de tu navegador ni se envían a ningún servidor externo.

---

## 🎓 Sobre el formato GIFT

[GIFT](https://docs.moodle.org/en/GIFT_format) (*General Import Format Template*) es el formato de texto que usa Moodle para importar preguntas de forma masiva al banco de preguntas. Esta herramienta traduce lo que escribes en el formulario a la sintaxis GIFT correcta, para que no tengas que aprenderla ni escribirla a mano.

Para importar el archivo generado en Moodle: **Banco de preguntas → Importar → selecciona "formato GIFT"** en el desplegable de formato.

---

## 🛠️ Tecnologías Utilizadas

El proyecto está construido en código estándar para garantizar ligereza y ejecución instantánea sin frameworks ni dependencias complejas:

* **HTML5:** Estructura de la aplicación.
* **CSS3:** Estilos visuales y diseño adaptativo, con soporte para modo claro y oscuro.
* **JavaScript (Vanilla):** Lógica interactiva, generación del código GIFT y validación de preguntas.

---

## 🤝 Cómo Contribuir

¡Las ideas y contribuciones son bien recibidas! Al ser una herramienta *vibe-coded* y en constante evolución:

1. Haz un **Fork** del repositorio.
2. Crea una rama para tu mejora (`git checkout -b feature/nueva-mejora`).
3. Haz **Commit** de tus cambios (`git commit -m 'Añade nueva mejora'`).
4. Haz **Push** a la rama (`git push origin feature/nueva-mejora`).
5. Abre un **Pull Request**.

Si encuentras algún fallo o tienes una sugerencia, también puedes abrir una [Issue](https://github.com/Sourenics/generador-gift/issues).

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **GNU General Public License v3.0 (GPLv3)**. Consulta el archivo [`LICENSE`](LICENSE) para obtener más detalles.

---

<p align="center">Desarrollado con ❤️ para la comunidad educativa por <a href="https://github.com/Sourenics">Sourenics</a></p>

---
