# ÌLÉ ÀṢẸ́ IFÁ AWOPEJU – Versión LITE

Sitio web sagrado inspirado en la tradición Ìṣẹ̀ṣẹ̀ nigeriana, con menú de Òrìṣà, textos tradicionales, animaciones y sistema de audio por sección.  
**Esta es la versión LITE**, optimizada para funcionar en GitHub Pages sin los problemas de archivos de audio demasiado pesados.

## 📂 Estructura del proyecto

- `index.html` — Página principal con menú superior sticky, secciones de Òrìṣà y formulario de contacto.
- `styles.css` — Estilos en blanco + dorado, auras de color por Òrìṣà, animaciones y diseño responsive.
- `script.js` — Motor de audio por sección (fade in/out), solo reproduce pistas que existan y sean ligeras.
- `assets/icons/favicon.svg` — Favicon espiritual (Òpón Ifá minimal en dorado).
- `assets/audio/` — Carpeta para colocar tus pistas de audio (.mp3) que no superen **10–15 MB**.
- `assets/audio/playlist.json` — Lista que define qué pista suena en cada Òrìṣà (puedes usar URLs externas).
- `README.md` — Esta guía.

## 🚀 Cómo usar

1. **Descomprime** este proyecto en tu PC.
2. **Coloca** tus pistas de audio ligeras (< 10–15 MB) en `assets/audio/`.
3. **Edita** `assets/audio/playlist.json` para definir qué pista corresponde a cada Òrìṣà.
4. **Abre** `index.html` en tu navegador para probar localmente.

## 🌐 Cómo publicar en GitHub Pages

1. Crea un nuevo repositorio en [GitHub](https://github.com).
2. Sube **todos los archivos** de este proyecto (incluyendo carpetas).
3. Ve a **Settings → Pages**.
4. En **Source**, elige `main` y `/ (root)` y pulsa **Save**.
5. Tu web estará disponible en: `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`.

## 🎵 Notas sobre el audio

- GitHub Pages **no acepta archivos individuales de más de ~25 MB**.
- Si una pista es muy larga:
  - **Opción A:** Comprímela a 128 kbps para reducir tamaño.
  - **Opción B:** Usa un servidor externo o un servicio como Dropbox, Google Drive o un CDN y pega la URL en `playlist.json`.
- El sistema de audio **no se rompe** si faltan pistas: simplemente habrá silencio en esa sección.

## 🛠️ Personalización

- Cambia colores y estilos en `styles.css`.
- Reemplaza el favicon en `assets/icons/favicon.svg`.
- Agrega imágenes de fondo en `assets/images/` y modifícalas en el CSS.

## 📜 Créditos

Desarrollado con respeto absoluto a la tradición Ìṣẹ̀ṣẹ̀, integrando versos, oraciones y símbolos espirituales yorùbá.

**Aṣẹ o!**
