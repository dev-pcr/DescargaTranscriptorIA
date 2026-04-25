# Anti-patrones a Evitar (Vercel Labs Standard)

## Errores Comunes de Diseño
- 🚩 **Desactivar Zoom**: Nunca usar `user-scalable=no` o `maximum-scale=1`.
- 🚩 **Bloquear Pegado**: Nunca prevenir el evento `onPaste`.
- 🚩 **Transiciones Genéricas**: Evitar `transition: all`.
- 🚩 **Falta de Foco**: Evitar `outline-none` sin reemplazo visual.
- 🚩 **Semántica Incorrecta**: No usar `<div>` o `<span>` con manejadores de clic si debería ser un `<button>` o `<a>`.

## Errores de Contenido
- 🚩 **Imágenes sin Dimensiones**: Provoca saltos en el diseño durante la carga.
- 🚩 **Formularios sin Etiquetas**: Problema crítico de accesibilidad.
- 🚩 **Iconos sin Label**: Los botones que solo contienen un icono necesitan un `aria-label`.
- 🚩 **Formatos Hardcoded**: Usar siempre las APIs nativas `Intl.*` para fechas, números y monedas.
