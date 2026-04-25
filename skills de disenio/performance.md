# Guía de Performance y UX (Vercel Labs Standard)

## Animación y Movimiento
- **Respeto al Usuario**: Honrar siempre `prefers-reduced-motion`. Proporcionar variantes estáticas o desactivar animaciones.
- **Eficiencia**: Animar solo `transform` y `opacity` para aprovechar la aceleración por hardware.
- **Propiedades**: No usar nunca `transition: all`. Listar las propiedades explícitamente.

## Tipografía y Contenido
- **Símbolos**: Usar `…` en lugar de `...` y comillas curvas cuando sea posible.
- **Balance**: Usar `text-wrap: balance` o `text-pretty` en encabezados para evitar "viudas".
- **Carga**: Los estados de carga deben terminar con `…` (ej. "Cargando…").

## Imágenes y Assets
- **Dimensiones**: Especificar siempre `width` y `height` para prevenir saltos de diseño (CLS).
- **Carga Diferida**: Usar `loading="lazy"` para imágenes debajo del pliegue.
- **Prioridad**: Usar `fetchpriority="high"` para imágenes críticas en el hero.

## Interacción Táctil
- **Delay**: Usar `touch-action: manipulation` para prevenir el retraso del doble toque en móviles.
- **Áreas de Toque**: Asegurar que los botones y enlaces tengan un tamaño adecuado para ser pulsados fácilmente.
