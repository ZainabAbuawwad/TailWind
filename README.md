# FixMyCar 🚗🔧

A mobile car repair service website — customers book a repair, we pick up their car, fix it, and deliver it back home.

## Tech Stack

- **Frontend:** HTML + [Tailwind CSS](https://tailwindcss.com/)

## Project Structure

```
my-website/
├── index.html            # Main landing page
├── input.css              # Tailwind source file (@import "tailwindcss")
├── dist/
│   └── output.css         # Compiled Tailwind CSS (generated, don't edit directly)
└── README.md
```

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS version, v22.x recommended) — needed to run the Tailwind CLI
- npm (comes with Node.js)

## Getting Started

### 1. Install Tailwind

From the project root:

```bash
npm install tailwindcss @tailwindcss/cli
```

### 2. Build Tailwind CSS (watch mode)

Run this in a terminal and leave it running while you work:

```bash
npx @tailwindcss/cli -i ./input.css -o ./dist/output.css --watch
```

This watches `input.css` and your HTML files, and regenerates `dist/output.css` automatically whenever you save changes.

### 3. Open the site

Open `index.html` directly in your browser, or use the **Live Server** VS Code extension for auto-reload on save.

## Roadmap / TODO

- [ ] Make layout fully mobile-responsive
- [ ] Add more pages (About, Services detail)
- [ ] Add real service photos instead of placeholder images
- [ ] Connect booking form to a backend (planned for later)
- [ ] Deploy the site (e.g. Vercel, Netlify)

## License

Private project — all rights reserved.
