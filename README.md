# Bay Family Mediation — Website Guide

The live site is at **[bayfamilymediation.com.au](https://bayfamilymediation.com.au)**.
Changes saved here will appear on the live site automatically (usually within a minute).

---

## The Pages

Each page is a `.md` file — open it, edit the text, save.

- **[index.md](index.md)** — The home page. Edit the "hero" heading/text, and "service cards" in the top section of the file.
- **[about.md](about.md)** — The About page. Plain text with headings — edit freely.
- **[contact.md](contact.md)** — The Contact page. Update the email address if it changes.
- **[how-it-works.md](how-it-works.md)** — The How It Works page. Add, remove, or rewrite sections as needed.

---

## Header & Footer

The header (top bar with logo and nav) and footer (bottom bar) are shared across every page.
Edit them once and it updates everywhere.

- **[header.html](header.html)** — Change the logo, business name, or nav links here.
  - To add a new page to the nav, add a line like: `<li><a href="/your-page/">Page Name</a></li>`
- **[footer.html](footer.html)** — Update the copyright year here if needed.

---

## Colours

The site uses one main colour (teal) throughout — headings, the header bar, borders, and links.

- Open **[style.css](style.css)**
- Press **Ctrl+H** (Find & Replace)
- Replace `#2c5f7c` with your new colour (e.g. `#8b4513` for brown)
- Save — done, it changes everywhere at once

---

## Logo

The logo image is the file **[images/logo-whitebackground.png](images/logo-whitebackground.png)**.

- To swap the logo: replace that file with your new image, keeping the same filename
- To resize it: open [style.css](style.css), find `.site-logo`, and change the `height` value (e.g. `height: 90px`)

---

## Favicon

The favicon is the small icon that appears in the browser tab.

- The file is **[favicon.ico](favicon.ico)** in the root folder
- To change it: replace `favicon.ico` with a new image (a square image works best), keeping the same filename
