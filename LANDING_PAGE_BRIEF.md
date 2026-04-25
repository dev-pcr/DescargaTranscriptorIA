# BRIEF PARA LANDING PAGE: TRANSCRIPTOR IA DESKTOP

Este documento contiene toda la información necesaria para que un diseñador o una IA construya una **Landing Page** para el software "Transcriptor IA". Incluye el discurso de venta (copy), las instrucciones de instalación y las especificaciones exactas del sistema de diseño a replicar.

---

## 1. ¿Qué es Transcriptor IA? (Copy y Funcionalidad)

**Título Principal:** Convierte tus clases y reuniones en apuntes académicos perfectos.
**Subtítulo:** Transcriptor IA escucha tus audios largos, los transcribe con precisión casi humana y utiliza Inteligencia Artificial avanzada para darles formato de estudio, resaltando lo más importante. ¡Todo desde tu escritorio y sin necesidad de internet!

**Características Principales:**
- 🎙️ **Transcripción de Alta Precisión:** Utiliza la tecnología Whisper de OpenAI para escuchar y transcribir con precisión, detectando pausas inteligentemente para no cortar frases.
- 🧠 **Apuntes Automáticos:** No te entrega un bloque de texto gigante. La IA (LLaMA 3.1) lee la transcripción y la formatea en párrafos, listas, detecta temas de examen y resalta palabras clave en negrita.
- ☁️ **Modo Dual (Cloud & Local):** 
  - *Groq Cloud*: Usa tu API Key gratuita para transcribir horas de audio en segundos.
  - *Modo Local*: Descarga los modelos a tu PC y transcribe audios de manera 100% privada, sin necesidad de conexión a internet.
- 📄 **Exportación Directa a Word:** Con un solo clic, descarga tus apuntes formateados en un documento `.docx` listo para imprimir o estudiar.
- 💻 **Software 100% Autónomo:** Olvídate de instalar Python, dependencias complejas o usar la terminal. Es una aplicación de escritorio nativa para Windows.

---

## 2. Instrucciones de Instalación (Guía para el usuario)

Para usar la aplicación desde el archivo ZIP, el proceso es sumamente sencillo. (Puedes incluir esto en una sección de "Cómo Empezar" o "Guía Rápida").

**Paso 1: Descargar y Descomprimir**
- Descarga el archivo `Transcriptor_IA_Desktop_Standalone.zip`.
- Haz clic derecho sobre el archivo descargado y selecciona **"Extraer todo..."** (Es crucial extraer los archivos, no abrirlos directamente desde el ZIP).

**Paso 2: Ejecutar el Programa**
- Entra a la carpeta extraída.
- Busca el archivo con el logo verde llamado **`Transcriptor IA.exe`** y hazle doble clic.

**Paso 3: Configuración Inicial (Solo la primera vez)**
- Al abrirlo por primera vez, verás una ventana de configuración (Setup).
- **(Opcional)** Ingresa una API Key gratuita de Groq si quieres transcripciones ultra rápidas y formateo inteligente.
- Selecciona el modelo local de Whisper que deseas descargar (Base, Small o Medium) para cuando no tengas internet.
- Haz clic en **"Iniciar Transcriptor"**. ¡Y listo! La aplicación se abrirá en tu pantalla.

---

## 3. Especificaciones del Sistema de Diseño (Design System)

Para que la Landing Page sea coherente con la aplicación, debe utilizar el mismo estilo **"Hacker / Matrix Profesional"**. Aquí están las especificaciones exactas (Tokens de CSS):

### 🎨 Paleta de Colores
La paleta se basa en un fondo oscuro muy profundo con acentos en verde brillante, simulando una terminal moderna pero limpia y profesional.

- **Fondo Principal (Background):** `#0a0a0a` (Casi negro puro)
- **Fondo Secundario / Paneles:** `#111111` (Gris extremadamente oscuro)
- **Bordes (Borders):** `#1a3d1a` o `rgba(85, 241, 152, 0.2)` (Verde oscuro translúcido)
- **Texto Principal (Texto Claro):** `#e0e0e0` (Gris muy claro, para legibilidad)
- **Texto Secundario (Mutado):** `#888888` o `#2a7a4a` (Para descripciones o placeholders)
- **Acento Primario (Verde Matrix):** `#55f198` (Verde terminal brillante, usado para iconos, botones principales y estados activos)
- **Acento Hover:** `#44c778` (Una variación ligeramente más oscura para efectos de hover en botones)

### 🔤 Tipografía
El diseño utiliza una combinación de fuentes serif elegantes para la lectura larga y fuentes monoespaciadas para la estética técnica.

- **Fuente para Títulos y UI General:** `Inter` o `Segoe UI` (sans-serif limpio y moderno).
- **Fuente para Textos de Lectura (Resultados):** `Inria Serif` (Aporta un tono académico e intelectual).
- **Fuente Técnica / Estética Matrix:** `Roboto Mono` o `Consolas` (Para contadores de tiempo, badges, estados del sistema y botones).

### 📐 Estructura y Estilos de Componentes (UI/UX)
- **Bordes:** Todos los contenedores, botones e inputs deben tener bordes rectos y afilados. **Cero curvas** (`border-radius: 0px`). Esto refuerza la estética de consola/terminal.
- **Botones:**
  - *Fondo:* Transparente o `#111111`.
  - *Borde:* `1px solid #1a3d1a`.
  - *Texto:* Color verde acento (`#55f198`).
  - *Hover:* El fondo cambia al verde acento (`#55f198`) y el texto cambia al color de fondo (`#0a0a0a`), creando un efecto de bloque sólido.
- **Iconografía:** Usa iconos minimalistas y geométricos (como los de *Lucide Icons*). Los iconos deben estar tintados con el verde acento (`#55f198`).
- **Scrollbars:** Diseñadas a medida. Fondo `#0a0a0a`, y la barra deslizante en color `#2a7a4a` (cuadrada, sin bordes redondeados).

### 💫 Micro-Animaciones
- **Transiciones:** Suaves y rápidas (`transition: all 0.2s ease`). Especialmente en los hovers de los botones y links.
- **Efectos Matrix:** Puedes incluir pequeñas animaciones de texto escribiéndose solo (typewriter effect) o contadores de números cambiando rápidamente para darle más dinamismo a la landing page.
