# STAR Lab website

Source for **https://star-computing.github.io**, served by GitHub Pages
from the `main` branch. There is no build step: edit `index.html`, commit,
and push, and the site updates within a minute or two.

## Editing

Everything is in `index.html`, one commented block per section:

- **People:** copy a `<div class="person">` block. For a photo, add a square
  image under `assets/people/` and replace the initials `<div class="avatar">`
  with `<img class="avatar" src="assets/people/name.jpg" alt="">`.
- **Publications:** copy an `<li>`, newest first. Remove links you don't have.
- **News:** add an `<li>` at the top of the list.
- **Open source:** copy an `<a class="card link-card">` block.

Colors and layout are in `style.css`. The palette matches the STAR paper
template: midnight blue `#25356B`, cyan `#00A8C6`, ink `#222A3A`.

## Preview locally

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```
