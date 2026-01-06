# Design That Interrupts – Landing Page Experimental

Proyecto de landing page desarrollado como parte de mi **portafolio comercial**, enfocado en diseño web moderno, animación avanzada y narrativa visual orientada a conversión y branding.

El objetivo fue demostrar capacidad para crear **experiencias web de alto impacto**, similares a las que se ven en plataformas como *Landing Love* o *Awwwards*.

---

## 🎯 Objetivo del proyecto

- Mostrar dominio de animaciones web modernas
- Crear una primera impresión fuerte en pocos segundos
- Usar el video y el movimiento como parte del mensaje, no como decoración
- Demostrar criterio visual y control técnico sin frameworks pesados

Este proyecto no es una plantilla genérica, es una **pieza de demostración**.

---

## 🧠 Concepto creativo

La landing está construida alrededor de una idea clara:

> Si no captas la atención rápido, el usuario se va.

Por eso:
- El sitio inicia con una **intro en video fullscreen**
- El contenido aparece con animaciones progresivas al hacer scroll
- El diseño prioriza contraste, tipografía fuerte y ritmo visual

---

## 🎬 Intro en video

- El video se reproduce automáticamente al cargar la página
- Su duración visible está **limitada a 3 segundos mediante JavaScript**
- No depende de la duración real del archivo
- La salida del intro es animada con GSAP

Esto demuestra control sobre:
- Timing
- Performance
- Experiencia de usuario

---

## 🎞️ Animaciones y experiencia

Se implementaron animaciones usando **GSAP y ScrollTrigger** para:

- Entradas suaves de texto e imágenes
- Parallax en videos de fondo
- Transiciones entre secciones
- Transiciones de navegación entre páginas

Todas las animaciones están pensadas para **acompañar el contenido**, no distraer.

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **GSAP 3**
- **GSAP ScrollTrigger**
- Video MP4 optimizado para web

No se usaron frameworks para demostrar control directo del código.

---

## 📂 Estructura del proyecto

```txt
/
├── index.html
├── intro.mp4
├── video/
│   ├── hero.mp4
│   └── manifiesto.mp4
├── img/
│   └── visual.png
├── assets/
│   └── img/grain.png
└── README.md
