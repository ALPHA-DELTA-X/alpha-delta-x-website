# Alpha Delta X

**Think Alpha. Execute Delta.**

The official website of Alpha Delta X: a single-page site built with plain HTML, CSS and JavaScript, published with GitHub Pages.

---

## Overview

Alpha Delta X is built around a simple idea: meaningful decisions begin with rigorous thinking (**Alpha**) and move forward through purposeful execution (**Delta**).

The site has these sections:

| Section | Purpose |
|---|---|
| **Hero** | Logo, tagline and introduction |
| **Philosophy** | The Alpha (Think) and Delta (Execute) principles |
| **Process** | The four steps: Observe → Think → Execute → Refine |
| **Technology** | The core capabilities behind the approach |
| **Vision** | The long-term direction of Alpha Delta X |

---

## Repository structure

```
.
├── index.html                    # The complete website (HTML, CSS and JS in one file)
├── Alpha_Delta_X_Neon_Logo.png   # Logo, also used as the favicon and social preview image
└── README.md
```

The site has no build step and no dependencies to install. Fonts load from Google Fonts.

---

## Features

- **Animated background**: flowing lines and a drifting node network, drawn on a canvas
- **Scroll animations**: content fades in as you scroll
- **Interactive cards**: a soft light follows the cursor across the cards
- **Responsive layout**: works on desktop, tablet and phone, with a mobile menu
- **Accessible**: uses semantic HTML, ARIA labels on navigation, and turns off motion for visitors who have reduced motion enabled
- **Lightweight**: a single file with no frameworks or libraries

---

## Publishing with GitHub Pages

1. Push `index.html` and `Alpha_Delta_X_Neon_Logo.png` to the root of the repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two, the site is live at:

```
https://<your-username>.github.io/<repository-name>/
```

---

## Running locally

Open `index.html` directly in a browser, or start a simple local server:

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Customising

| What | Where in `index.html` |
|---|---|
| Colours | The CSS variables in `:root` (`--blue`, `--cyan`, `--teal`, `--bg`) |
| Text content | The `<main>` section, organised by section `id` |
| Logo | Replace `Alpha_Delta_X_Neon_Logo.png`, keeping the same file name |
| Page title and description | The `<title>` and `<meta>` tags in `<head>` |

> **Note:** GitHub Pages file names are case-sensitive. The logo must be named exactly `Alpha_Delta_X_Neon_Logo.png`, or the page will show a "Logo file not found" notice in its place.

---

## Disclaimer

Content on this site is for general informational purposes only.

---

© Alpha Delta X. All rights reserved.
