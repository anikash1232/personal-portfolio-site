# Personal Portfolio Site

A personal portfolio built from scratch in HTML and CSS — no framework, no build step, no
dependencies.

## What it is

A single static page written directly in markup and stylesheets. Everything is hand-authored:
layout, typography, responsive behaviour and any visual effects, with no CSS framework
providing defaults.

```
index.html    structure and content
styles.css    all styling
```

## Running it

Open `index.html` in a browser. There is nothing to install and nothing to build.

```bash
python3 -m http.server 8000     # if you'd rather serve it
```

Writing a site this way means dealing with the cascade, specificity, the box model and
responsive layout directly rather than through a framework's abstractions.
