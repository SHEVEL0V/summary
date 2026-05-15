# Andriy Shevelov — CV / Résumé

> Personal résumé built as a static HTML/CSS page, styled for 2026 design trends.  
> **Live →** _open `index.html` in any browser or host on GitHub Pages / Netlify_

---

## 🖼 Preview

The résumé uses a two-column layout:

| Column                  | Content                                                              |
| ----------------------- | -------------------------------------------------------------------- |
| **Sidebar** (dark navy) | Photo · Contacts · Tech Skills (pill tags) · Soft Skills · Languages |
| **Main** (white)        | Hero header · Projects · Work Experience · Education                 |

---

## 🗂 Project Structure

```
summary/
├── index.html      # Markup — semantic HTML5
├── styles.css      # All styles — CSS custom properties, Grid, Flexbox
├── sprite.svg      # SVG icon sprite (tel, mail, GitHub, LinkedIn)
├── photo.jpg       # Profile photo
└── README.md       # This file
```

---

## ⚡ Tech & Design

| Topic      | Choice                                                                      |
| ---------- | --------------------------------------------------------------------------- |
| Font       | [Inter](https://fonts.google.com/specimen/Inter) — system-UI feel, ATS-safe |
| Layout     | CSS Grid (two-column) + Flexbox internals                                   |
| Colors     | Dark navy sidebar `#0f172a` + Indigo accent `#818cf8`                       |
| Reset      | [normalize.css 8](https://necolas.github.io/normalize.css/)                 |
| Icons      | Inline SVG sprite                                                           |
| Responsive | Single breakpoint `@media (max-width: 640px)` → stacked                     |
| Print      | `@media print` — removes shadows, fills page width                          |

---

## 🛠 Skills Showcased

**Frontend** — HTML5 · CSS3 · SASS · JavaScript · TypeScript · React 19 · Redux · Next.js · Material UI

**Backend** — Node.js · GraphQL · REST API · Prisma ORM · JWT

**Database** — MySQL · PostgreSQL · MongoDB

**Tools** — Git · Docker · Webpack · Parcel

---

## 📂 Projects Listed

| Project                    | Live                                                                             | Stack                                                       |
| -------------------------- | -------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Kanban Board**           | [kanban-cuec.onrender.com](https://kanban-cuec.onrender.com)                     | Next.js 16 · React 19 · Prisma · MySQL · MUI · JWT · Docker |
| **Online Store — GraphQL** | [shop-gql.vercel.app](https://shop-gql.vercel.app/)                              | Next.js · Redux · GraphQL · TypeScript                      |
| **Online Store — REST**    | [shop-rest-a51dd6.netlify.app](https://shop-rest-a51dd6.netlify.app)             | React · Redux · RTK Query · TypeScript                      |
| **Movies App**             | [movies-v3.vercel.app](https://movies-v3.vercel.app/)                            | React · TypeScript · React Query · TMDB API                 |
| **Server — GraphQL**       | [shopservergql.onrender.com](https://shopservergql.onrender.com)                 | Node.js · Apollo Server · MongoDB                           |
| **Server — REST**          | [shop-server-rest.onrender.com/docs](https://shop-server-rest.onrender.com/docs) | Node.js · Express · MongoDB · Swagger                       |

---

## 🚀 Running Locally

```bash
# Clone
git clone https://github.com/SHEVEL0V/summary.git
cd summary

# Open — no build step needed
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or use any static server:

```bash
npx serve .
# → http://localhost:3000
```

---

## 🌐 Deploy

### GitHub Pages

1. Push to `main`
2. **Settings → Pages → Source:** `main / (root)`
3. Live at `https://shevel0v.github.io/summary/`

### Netlify (drag & drop)

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `summary/` folder onto the page
3. Done — instant public URL

---

## 📬 Contact

|          |                                                                           |
| -------- | ------------------------------------------------------------------------- |
| Email    | [an.shevelov@gmail.com](mailto:an.shevelov@gmail.com)                     |
| GitHub   | [@SHEVEL0V](https://github.com/SHEVEL0V)                                  |
| LinkedIn | [Andriy Shevelov](https://www.linkedin.com/in/andriy-shevelov-5439b3244/) |

---

_Last updated: May 2026_
