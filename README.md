# Sapientia
Sitio estático listo para GitHub Pages.

## Publicar
1. Sube `index.html`, `assets/` y `data/` a la raíz del repositorio.
2. Settings > Pages > Deploy from a branch > main / root.

## Analítica
En `index.html` busca `const GA_ID = ""` y pega tu ID de Google Analytics 4 (G-XXXXXXXXXX).

## Lotes de contenido
Los lotes están en `data/personajes.js`, `data/libros.js` y `data/frases.js` (listas `[texto, detalle]`). Funciona también abriendo `index.html` directamente. Los cursos, retos, posts y hábitos se pueden añadir en `data/` con la misma estructura. Claves: `frases` [texto, autor], `cursos` [título, categoría, descripción], `retos` [texto], `posts` [título, texto], `habitos` [pregunta, opciones, índice correcto].
