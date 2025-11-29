# Santa Maria Blumen - Website

Official website for **Santa Maria Blumen** (Atelier Blooming), a premium florist in Frankfurt am Main, Germany.

**Live Site:** [https://santa-maria-blumen.com](https://santa-maria-blumen.com)

---

## Project Structure

```
santa-maria-blumen/
├── dist/                    # Production website (deployed)
│   ├── index.html           # Main page
│   ├── impressum.html       # Legal notice
│   ├── agb.html             # Terms & conditions
│   ├── datenschutz.html     # Privacy policy
│   └── assets/              # Images, CSS, JS
├── src/                     # Source files
│   ├── css/style.css        # Main stylesheet
│   └── js/main.js           # Main JavaScript
├── public/                  # Static assets
└── .github/workflows/       # GitHub Actions (auto-deploy)
```

---

## Deployment

### Automatic (GitHub Pages)

Every push to `main` automatically deploys to GitHub Pages.

- **URL:** https://santa-maria-blumen.com
- **Workflow:** `.github/workflows/deploy.yml`
- **Source:** `dist/` folder is deployed directly

---

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## Tech Stack

- **Build:** Vite 5.x
- **Styling:** Vanilla CSS with CSS variables
- **JavaScript:** Vanilla JS (ES6 modules)
- **Fonts:** Google Fonts (Playfair Display, Lato)
- **Hosting:** GitHub Pages

---

## Contact

**Santa Maria Blumen**
Frankfurt am Main, Germany
[https://santa-maria-blumen.com](https://santa-maria-blumen.com)
