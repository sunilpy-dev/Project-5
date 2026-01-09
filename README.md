# Twitter Clone — WebDay101 Project

![Project Screenshot](imagestw/images.png)

A responsive Twitter-like front-end built using modern web tooling. This project focuses on layout, Tailwind CSS styling, and a fast development experience using Vite.

## Highlights

- Clean, responsive UI inspired by Twitter
- Built with Tailwind CSS for rapid styling
- Fast dev server with Vite
- Small, easy-to-read codebase (HTML/CSS/JS)

## Demo / Screenshot

The project screenshot above is stored in the `imagestw` folder. Replace the image if you want a different preview.

## Features

- Responsive layout for desktop and mobile
- Reusable Tailwind utility classes
- Ready-to-run dev workflow

## Tech Stack

- HTML
- CSS
- Tailwind CSS (devDependency: 3.4.17)
- Vite (dependency: 6.0.7)

Versions are taken from `package.json` — run `npm install` to get the exact versions used here.

## Getting Started

1. Install dependencies

```bash
npm install
```

2. Start development server (hot reload)

```bash
npm run dev
```

3. Generate Tailwind output (the project already includes `css/output.css`)

```bash
npm run build
```

Notes:
- `npm run build` runs Tailwind in watch mode (see `package.json`). For production builds, adjust the Tailwind CLI flags as needed.

## Project Structure

- `index.html` — main page
- `main.js` — frontend JS entry (if used)
- `css/input.css` — Tailwind input
- `css/output.css` — compiled CSS (ignored by Git ideally)
- `imagestw/` — images and screenshots

## Repository hygiene

- `node_modules/` is now ignored via `.gitignore`. If you see large files in history that need purging, consider using the BFG Repo-Cleaner or `git filter-branch` (destructive).

## Contributing

Feel free to open issues or PRs to improve responsiveness, accessibility, or add components.

## License

Distributed under the ISC License. See `package.json` for details.

