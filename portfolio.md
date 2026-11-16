# Bitácora de Inteligencia Artificial

## Consulta 1
- **Fecha:** 11/11/2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Generar la estructura base semántica en HTML5 para mi portfolio.
- **Prompt completo:** "Necesito una estructura semántica para un portfolio con encabezado, navegación, presentación, sobre mí, proyectos, habilidades, contacto y pie de página. Usá solamente HTML5, sin CSS, JavaScript ni frameworks. Marcá con [COMPLETAR] la información que no conozcas y explicá la función de las etiquetas."
- **Parte utilizada:** Utilicé las etiquetas `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
- **Cambios realizados por mí:** Reemplacé las marcas `[COMPLETAR]` por mi información real, mis proyectos de la especialidad y agregué los atributos `id` requeridos para los enlaces internos.
- **¿Qué comprendí?** Comprendí cómo vincular enlaces navegables mediante `href="#id"` asegurando que coincidan de forma exacta con los `id` de las secciones.
- **¿Qué descarté y por qué?** Descarté código JavaScript e íconos externos para mantener la versión 0.1 simple y estática.

## Consulta 2
- **Fecha:** 11/11/2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Crear un archivo CSS básico utilizando variables de color y tarjetas para proyectos.
- **Prompt completo:** "Mi portfolio tiene estilo limpio y formal, usa colores azul marino y celeste y debe transmitir profesionalismo. Creá un CSS inicial con variables de color, tipografía legible, espaciados y tarjetas. Usá CSS puro, sin frameworks ni animaciones. Explicá cada bloque."
- **Parte utilizada:** La estructura de variables `:root` y los estilos de la clase `.tarjeta`.
- **Cambios realizados por mí:** Modifiqué el color secundario para ajustar el contraste de los enlaces y agregué el formato circular para la imagen de perfil.
- **¿Qué comprendí?** El funcionamiento del modelo de caja (`margin`, `padding`, `border`) y la utilidad de `:root` para centralizar la paleta de colores.
- **¿Qué descarté y por qué?** Descarté tipografías externas de Google Fonts para evitar depender de conexiones externas durante las pruebas.