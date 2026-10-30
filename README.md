# antonstolz

Source for [antonstolz.de](https://antonstolz.de) — a minimal static site built with [Zola](https://www.getzola.org/).

Content lives in `content/`, the template in `templates/`, and the generated site in `docs/` (served by GitHub Pages).

## Local preview

```sh
zola serve
```

Serves the site at http://127.0.0.1:1111 with live reload.

## Build

```sh
zola build
```

Writes the generated site to `docs/`. Commit that folder to publish.
