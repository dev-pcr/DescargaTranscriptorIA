# Guía de Accesibilidad (Vercel Labs Standard)

## Principios Fundamentales
- **Semántica**: Usar siempre etiquetas HTML semánticas (`<nav>`, `<main>`, `<header>`, `<footer>`) antes de recurrir a ARIA.
- **Imágenes**: Todas las imágenes deben tener un atributo `alt`. Las decorativas deben tener `alt=""`.
- **Iconos**: Los iconos decorativos deben tener `aria-hidden="true"`.
- **Navegación**: Los enlaces deben usar `<a>` con `href`, no manejadores `onClick` en otros elementos.

## Estados de Foco
- **Visibilidad**: Nunca usar `outline: none` sin proporcionar un reemplazo visual.
- **Interacción**: Preferir `:focus-visible` sobre `:focus` para evitar anillos de foco al hacer clic.
- **Consistencia**: Asegurar que los elementos interactivos tengan un anillo de foco claro (`focus-visible:ring-*`).

## Formularios
- **Etiquetas**: Cada entrada debe tener una etiqueta asociada.
- **Autocomplete**: Usar atributos de autocompletado significativos.
- **Errores**: Mostrar errores en línea junto a los campos y enfocar el primer error al enviar.
