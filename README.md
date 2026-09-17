---
title: "About"
permalink: "/about/"
layout: page
---

# Florez-Garcia Lab — editar mi página

Todo se actualiza desde este repositorio de GitHub. No necesitas Pages CMS ni otra cuenta.

## Publicaciones

### [✏️ EDITAR MIS PUBLICACIONES](https://github.com/victorflorez/victorflorez.github.io/edit/master/PUBLICACIONES.md)

1. Pulsa el enlace anterior. Verás tu lista de referencias como texto, sin el código de la página.
2. Debajo de `## 2026` (o el año correspondiente), pega la nueva referencia y deja una línea vacía antes y después. Puedes copiar una referencia existente como ejemplo. No escribas el número: se calcula automáticamente.
3. Pulsa **Commit changes…**, escribe «Añadir publicación» y confirma con **Commit changes**. Eso guarda y publica los cambios.
4. Espera a que termine la actualización y [consulta tu página de publicaciones](https://victorflorez.github.io/publications/).

La pestaña **Preview** muestra el texto con su formato antes de guardar. Para crear otro año, escribe un encabezado como `## 2027` encima del año anterior. Conserva los años del más reciente al más antiguo.

Para enlazar un artículo, copia el formato de los demás: `[Leer artículo](https://doi.org/DOI-DEL-ARTICULO)`.

## Otros cambios

- [Ver o editar biografía y ruta del CV](https://github.com/victorflorez/victorflorez.github.io/blob/master/_data/profile.json). Estos campos aún usan formato JSON; no son un formulario visual.
- [Ver el PDF actual](https://github.com/victorflorez/victorflorez.github.io/blob/master/victor.pdf). Para sustituirlo manteniendo los enlaces, sube el nuevo PDF al repositorio con el mismo nombre `victor.pdf`.
- [Ver si terminó la publicación](https://github.com/victorflorez/victorflorez.github.io/actions).

El archivo que contiene las referencias es **PUBLICACIONES.md**, visible en la carpeta principal. `publications.html` solo controla cómo se muestran. Los cambios guardados en `master` actualizan la web pública.

---

## Documentación original del tema

## Installation

Just fork this [repository](https://github.com/niklasbuschmann/contrast) and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.

## Features

 - supports dark mode on macOS Mojave
 - optional sidebar
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
