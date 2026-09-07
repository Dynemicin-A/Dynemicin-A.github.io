# Xuanhao Zhang

Personal academic homepage: https://dynemicin-a.github.io/

A responsive static page about diffusion models, audio generation, and 3D molecular generation. It contains a short biography, research preprints, research experience, selected awards, and contact links. The CV is hosted separately at https://dynemicin-a.github.io/Xuanhao-Zhang-CV/Xuanhao_Zhang_CV.pdf.

## Preview

Run `python3 -m http.server 8765` from this directory and open http://localhost:8765. The site uses plain HTML, CSS, and a small optional script for the footer year; no dependencies or build step are required.

## Content

Edit `index.html` for the biography, research entries, and links. Keep paper titles and author order aligned with the linked arXiv records, label unaccepted work as preprints, and update the footer date after content edits. Styling and responsive layouts are in `styles.css`.

The September 2026 revision uses the supplied CV and these primary research records:

- https://arxiv.org/abs/2605.04547
- https://arxiv.org/abs/2509.22728

Layout and information organization were informed by the academic homepages of [Jon Barron](https://jonbarron.info/), [Yang Song](https://yang-song.net/), and [Haian Jin](https://haian-jin.github.io/). This site's implementation is original; their source code and assets are not copied.

## Deployment

GitHub Pages publishes the repository root from the `main` branch. Before pushing, check local assets and section links, run `node --check script.js`, and review the diff. After pushing, verify the Pages build and the live page.
