# 🎨 Layunta Studio

**Suite de diseño gráfico vectorial profesional en un único archivo HTML.**
Sin instalación, sin dependencias, sin servidor: abre `index.html` y a diseñar.

> **Autor:** Miguel Ángel Layunta López
> **Versión:** 4.0 · Paquetes A + B + C
> **Licencia:** MIT

---

## ✨ Características

### A · Precisión interactiva
- Transformaciones exactas con tiradores en el lienzo: mover, escalar, rotar y voltear.
- Panel numérico con unidades (px, mm, cm, pt, in) y escala proporcional.
- Edición de nodos Bézier: anclas, manejadores, insertar, eliminar, suavizar, esquina, partir, unir y simplificar.
- Operaciones booleanas reales (unir, restar, intersecar, excluir, dividir, contorno).
- Pincel con presión real de lápiz óptico y simulación con ratón.
- Alinear y distribuir respecto a mesa de trabajo, objeto clave o selección.
- Historial por comandos con parches diferenciales (deshacer/rehacer).

### B · Flujo de trabajo
- Paleta de comandos (`Ctrl+K`) con búsqueda difusa.
- Espacios de trabajo predefinidos y personalizables.
- Grabador de acciones → macros reutilizables.
- Procesado por lotes con variaciones y hoja de contactos SVG.
- Fusión de datos desde CSV (tarjetas, etiquetas, fichas).
- Guías inteligentes, reglas y guías arrastrables.
- Autoguardado y versiones con nombre.
- Presets de herramienta y atajos personalizables.

### C · Ecosistema
- Colaboración en tiempo real con CRDT (LWW por campo) sobre `BroadcastChannel`.
- Comentarios anclados al lienzo con hilos y resolución.
- Formato propio `.MAL` con esquema versionado y migraciones automáticas.
- Importadores: SVG (Bézier), PDF (flujo de contenido), PSD (capas + compuesto), PNG/JPG.
- Gestor de plugins con API pública.
- Compartir con permisos y modo revisión.
- Gestión del color: CMYK, RGB, Lab, Pantone, perfiles ICC, aviso de fuera de gama y ΔE.

---

## 🚀 Uso rápido

1. Descarga el repositorio o clónalo.
2. Abre `index.html` en Chrome, Edge, Firefox o Safari.
3. Ya está. No hace falta instalar nada.

---

## 📲 Instalar como aplicación (PWA)

Con la página abierta:

- **Chrome / Edge (escritorio):** icono de instalar en la barra de direcciones.
- **Android:** menú ⋮ → *Añadir a pantalla de inicio*.
- **iPhone / iPad:** Compartir → *Añadir a pantalla de inicio*.

Una vez instalada funciona **sin conexión**.

---

## 🌐 Publicar en GitHub Pages

1. Crea un repositorio **público** llamado `layunta-studio`.
2. Sube todos los archivos (arrástralos a la web de GitHub; respeta la carpeta `icons`).
3. Ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**.
5. Branch: **main** · carpeta: **/ (root)** → **Save**.
6. Espera 1–2 minutos. Tu app estará en:

