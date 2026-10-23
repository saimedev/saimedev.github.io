# Portfolio site (static)

Static HTML/CSS/JS conversion of the OVRO portfolio template that came in the zip.
Open `index.html` directly or serve the folder (e.g. `python3 -m http.server`).

Every `[Bracketed]` text is a placeholder: replace it in `index.html` with real info.
- Photo: replace `assets/img/placeholders/photo.svg` (or point the <img> to your photo, ~338x350).
- Projects: replace `assets/img/placeholders/project*.svg` with screenshots and set the links.
- CV: add `assets/cv.pdf` and set the "Download CV" link to `assets/cv.pdf` with `download`.
- Social icons: set the `href="#"` links in the profile card and the "Find Me Online" box.
- Contact form is not wired to a backend yet (shows an alert). Hook it to Formspree/Web3Forms with YOUR own key.
