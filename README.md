# blog

## Publicar (gratis, GitHub Pages)

1. Crea una cuenta en https://github.com y un repositorio **público** llamado `TUUSUARIO.github.io`.
2. **Add file → Upload files**: sube todo el contenido de esta carpeta → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
4. En 1–2 min estará en `https://TUUSUARIO.github.io`.

## Escribir un post

Crea `_posts/AAAA-MM-DD-titulo.md`:

```markdown
---
layout: post
title: "mi post"
---

Texto en Markdown.
```

## Multimedia

- Imagen: súbela a `assets/` y escribe `![descripción](/assets/foto.jpg)`
- Audio y video: súbelos a https://archive.org y usa la dirección de descarga del archivo:
  - `{% include audio.html src="https://archive.org/download/IDENTIFICADOR/archivo.mp3" %}`
  - `{% include video.html src="https://archive.org/download/IDENTIFICADOR/archivo.mp4" %}`

Límite de GitHub: 25 MB por archivo al subir desde la web (por eso audio y video van en archive.org).
