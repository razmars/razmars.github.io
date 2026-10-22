# razmars.github.io

Personal website: https://razmars.github.io

Static HTML and CSS, served by GitHub Pages. No build step or JavaScript is required.

To preview locally, run `python3 -m http.server 8000` in this directory and open
`http://localhost:8000`.

- Edit biography, news, publications, and links in `index.html`.
- Edit layout and colors in `style.css`.
- The portrait is stored in `profile.jpeg`. Its framing is controlled by
  `.portrait` and `.portrait img` in `style.css`; the original image is unchanged.
- Keep `.nojekyll` so GitHub Pages serves these files directly.

Social icons are from Font Awesome Free 6.7.2 by Fonticons, Inc., licensed
under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
The original attribution is preserved in each inline SVG. See
[Font Awesome licensing](https://fontawesome.com/license/free).

The X icon is disabled until a profile URL is supplied. Replace its button with
an anchor using the same `social-link` class and the verified profile URL.
