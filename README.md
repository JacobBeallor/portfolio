# Portfolio

A personal portfolio site built with [Astro](https://astro.build).

## Quickstart

**Prerequisites:** Node.js 18+

```sh
# 1. Clone the repo
git clone https://github.com/jbeallor/portfolio.git
cd portfolio

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
```

The site will be available at `http://localhost:4321`.

## Project Structure

```
/
├── public/             # Static assets (favicon, images, etc.)
├── src/
│   ├── assets/         # Processed assets (images, SVGs)
│   ├── components/     # Reusable Astro components
│   ├── layouts/        # Page layout templates
│   └── pages/          # File-based routes (each file = a page)
├── astro.config.mjs
└── package.json
```

## Commands

All commands are run from the root of the project:

| Command             | Action                                      |
| :------------------ | :------------------------------------------ |
| `npm install`       | Install dependencies                        |
| `npm run dev`       | Start dev server at `localhost:4321`        |
| `npm run build`     | Build production site to `./dist/`          |
| `npm run preview`   | Preview the production build locally        |
| `npm run astro ...` | Run Astro CLI commands (e.g. `astro check`) |

## Deployment

Build the site and deploy the `./dist/` folder to any static host (Netlify, Vercel, GitHub Pages, etc.):

```sh
npm run build
```

## Resources

- [Astro Documentation](https://docs.astro.build)
- [Astro Discord](https://astro.build/chat)
