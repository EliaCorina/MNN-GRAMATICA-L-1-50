# 🇯🇵 みんなの日本語 — App iOS/Android

App web progresiva (PWA) para estudiar la gramática completa de **Minna no Nihongo** L1–50.  
Funciona como una app nativa en iPhone con icono de la bandera japonesa 🇯🇵.

## 🆕 Novedades v2
- 🔊 **Audio japonés** — pronunciación nativa con Web Speech API (sin instalar nada)
- 🈺 **Furigana** — lectura en hiragana sobre cada kanji
- 🔤 **Romaji** — transcripción en alfabeto latino
- 📖 **Gramática COMPLETA** — todas las tablas, reglas y notas de cada lección
- 🃏 **Flashcards** con modo reverso (japonés→español y español→japonés)
- 📴 **100% offline** tras primera carga

## 📱 Instalar en iPhone (2 min)

1. Abre **Safari** en tu iPhone (no Chrome)
2. Ve a: `https://TU-USUARIO.github.io/nihongo-app/`
3. Pulsa el botón **Compartir** ↑ (cuadrado con flecha)
4. Selecciona **"Añadir a pantalla de inicio"**
5. La app aparece con la bandera 🇯🇵

## 🚀 Publicar en GitHub Pages

```bash
# 1. Crea un repositorio en github.com llamado "nihongo-app"
# 2. Sube todos los archivos (arrastra y suelta en GitHub)
# 3. Ve a Settings → Pages → Source: main → Save
# URL: https://TU-USUARIO.github.io/nihongo-app/
```

## ✨ Funcionalidades

| Feature | Descripción |
|---------|-------------|
| 🔊 Audio | Pronunciación japonesa con voz nativa del dispositivo |
| 🈺 Furigana | Lectura en hiragana sobre kanji |
| 🔤 Romaji | Transcripción latina completa |
| 📖 Gramática | Toda la gramática de L1–50 (274 ejemplos, 81 cajas, 21 tablas) |
| 🧠 Quiz | 20 preguntas, 4 opciones, puntuación |
| 🃏 Flashcards | Modo JP→ES y ES→JP con audio |
| ⭐ Favoritas | Marca lecciones para repaso rápido |
| ✅ Progreso | Se guarda en el dispositivo |
| 🔍 Búsqueda | Busca por japonés, español o romaji |
| 📴 Offline | Funciona sin internet una vez instalada |

## 📂 Estructura

```
nihongo-app/
├── index.html          ← App completa (self-contained)
├── lessons_data.json   ← 50 lecciones con todo el contenido
├── manifest.json       ← Config PWA para iOS/Android
├── sw.js               ← Service Worker (offline)
├── icons/              ← Bandera japonesa en todos los tamaños
└── README.md
```
