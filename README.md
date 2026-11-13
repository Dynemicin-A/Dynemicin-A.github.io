# Xuanhao Zhang

Personal academic homepage: https://dynemicin-a.github.io/

A responsive academic homepage focused on recursive self-improvement (RSI) and automated research. Current research presents three ongoing questions: meta-level adaptation, open-ended skill discovery, and measuring recursive progress. Earlier diffusion-model preprints remain separate from the ongoing agenda. Selected experience covers the ByteDance AutoResearch project collaboration and the Shanghai Institute of Materia Medica internship.

## Preview

Run `python3 -m http.server 8765` from this directory and open http://localhost:8765. The site uses plain HTML, CSS, and a small optional script for the footer year; no dependencies or build step are required.

## Content

Edit `index.html` for the biography, research entries, and links. Keep paper titles and author order aligned with the arXiv records, label unaccepted work as preprints, and keep ongoing research framed as research questions rather than demonstrated results. Update the footer and stylesheet version after content edits. Styling and responsive layouts are in `styles.css`.

The November 13, 2026 revision aligns the RSI agenda and collaboration description with the current two-page English CV. The public CV is hosted separately at https://dynemicin-a.github.io/Xuanhao-Zhang-CV/Xuanhao_Zhang_CV.pdf. The intermediary platform is not listed, and the collaboration is not presented as employment.

Primary research records:

- https://arxiv.org/abs/2605.04547
- https://arxiv.org/abs/2509.22728

Layout and information organization were originally informed by the academic homepages of [Jon Barron](https://jonbarron.info/), [Yang Song](https://yang-song.net/), and [Haian Jin](https://haian-jin.github.io/). This site's implementation is original; their source code and assets are not copied.

## Deployment

GitHub Pages publishes the repository root from the `main` branch. Before pushing, check local assets and section links, run `node --check script.js`, and review desktop/mobile presentation and the diff. After pushing, verify the Pages build and the live page. The existing public CV repository should contain the approved current PDF, served as `application/pdf`.
