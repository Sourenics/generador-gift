# 🎁 Generador de preguntas Moodle

> ⚠️ **Vibe-coded project**
> Este proyecto ha sido desarrollado siguiendo la filosofía *vibe coding* (con la ayuda de IA). Es una herramienta experimental y práctica, creada para resolver una necesidad concreta y en constante desarrollo, por lo que está sujeta a continuas mejoras y ajustes. ¡Cualquier sugerencia o feedback es más que bienvenido!

[![Live Demo](https://img.shields.io/badge/Demo-Online-brightgreen?style=for-the-badge&logo=github)](https://sourenics.github.io/generador-gift/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](LICENSE)

---

## 🚀 Probar la Aplicación

No requiere registros, servidores ni configuraciones avanzadas. Puedes usar la herramienta directamente desde tu navegador:

👉 **[Acceder al Generador (Página Oficial)](https://sourenics.github.io/generador-gift/)**

También puedes descargar el archivo `index.html` del repositorio y abrirlo con doble clic: funciona sin conexión a internet.

---

## ✨ Características Principales

* 🔄 **Dos formatos de salida:** escribe las preguntas una sola vez y descárgalas en **GIFT** o en **XML de Moodle**. El selector de formato avisa de qué preguntas no admite cada uno en lugar de descartarlas en silencio.
* 📝 **10 tipos de pregunta:** opción múltiple (una o varias correctas), verdadero/falso, respuesta corta, emparejamiento, numérica, ensayo y —solo en XML— respuestas incrustadas (cloze), seleccionar palabras que faltan y arrastrar y soltar sobre texto.
* 👁️ **Vista previa en vivo:** el código se genera y se resalta por sintaxis mientras escribes, y un contador indica cuántas preguntas están listas para exportar.
* 💾 **Guardado automático en el navegador:** tu examen se conserva aunque cierres la pestaña.
* 📤 **Exportación directa:** descarga el archivo listo para importar, o cópialo al portapapeles.
* 🗂️ **Categoría y retroalimentación:** define la categoría del banco de preguntas y añade retroalimentación general por pregunta.
* ⚡ **100% Client-side (sin servidor):** funciona directamente en tu navegador. No requiere registro ni conexión a bases de datos.
* 🔒 **Privacidad garantizada:** las preguntas que escribes no salen de tu navegador ni se envían a ningún servidor externo.

---

## 🎓 Qué formato elegir

| Formato | Tipos que admite | Cuándo usarlo |
|---|---|---|
| **GIFT** | Los 7 clásicos | Archivos ligeros y legibles, fáciles de revisar o retocar en cualquier editor de texto. |
| **XML de Moodle** | Los 10, incluidos cloze, seleccionar palabras y arrastrar y soltar | Cuando necesites los tipos avanzados. Es el formato más completo de Moodle. |

Para importar en Moodle: **Banco de preguntas → Importar**, elige *formato GIFT* o *Formato XML de Moodle* según corresponda y sube el archivo.

El escapado de caracteres reservados (`\ # = ~ { } :`), los saltos de línea y los pesos de las respuestas se generan siguiendo el código fuente del propio importador de Moodle, de modo que el texto que escribes es exactamente el que aparece tras importar.

---

## 🛠️ Tecnologías Utilizadas

El proyecto está construido en código estándar para garantizar ligereza y ejecución instantánea sin frameworks ni dependencias complejas:

* **HTML5:** Estructura de la aplicación.
* **CSS3:** Estilos visuales y diseño adaptativo, con soporte para modo claro y oscuro.
* **JavaScript (Vanilla):** Modelo común de preguntas, exportadores de cada formato y validación en vivo.

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
