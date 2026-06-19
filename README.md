# poleselalex.github.io

My personal site, served with GitHub Pages at
[poleselalex.github.io](https://poleselalex.github.io).

Plain static HTML and CSS, no build step and no dependencies.

## Structure

```
index.html       home page
style.css         shared styles
projects/         one HTML page per project
images/           images and assets
```

## Adding a project

1. Copy a `<a class="work-item project">…</a>` card in `index.html` and update
   the link, image, title and description.
2. Copy a file in `projects/` (e.g. `projects/new.html`) and edit its content.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server
```
