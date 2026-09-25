# Fred Kakungulu — Portfolio

Personal site for Fred Kakungulu, a statistician and data-systems developer in Kampala, Uganda. The site is static HTML, CSS, and JavaScript. There is no build step and no dependencies.

## Pages

- [index.html](index.html) — home
- [about.html](about.html) — background, roles, and skills
- [projects.html](projects.html) — systems built, including the MUSSA voting case study
- [contact.html](contact.html) — email, GitHub, and CV download

Styles are in [css/style.css](css/style.css). Navigation, the footer year, stat counters, and the copy-email button are in [js/main.js](js/main.js).

## View it locally

Open `index.html` in a browser, or from this folder run:

```bash
python -m http.server
```

Then visit `http://127.0.0.1:8000`.

## Personal files

These are not in the repo yet. Drop them in `assets/`:

- `Fred-Kakungulu-CV.pdf` — linked from the Download CV button on the contact page
- `photo.jpg` — optional headshot. In [about.html](about.html), replace the initials block with:

```html
<div class="avatar"><img src="assets/photo.jpg" alt="Fred Kakungulu"></div>
```

[assets/README.txt](assets/README.txt) repeats those two drop instructions next to the folder.
