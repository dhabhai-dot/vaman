# Jodhpur Misthan Bhandar

Frontend-only online ordering experience for Jodhpur Misthan Bhandar.

## Run the website

Install the project dependencies once:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Then open the local address printed by Vite (normally `http://localhost:5173`) in your browser.

Do not open `index.html` by double-clicking it. This is a React application and must be served by Vite; opening the HTML file directly results in a blank page because the browser cannot load `/src/main.jsx` from a file URL.

## Useful commands

```bash
npm run build   # Create a production build in dist/
npm run preview # Preview the production build
npm run format  # Keep source files human-readable
```

## Project files

- `src/main.jsx` — React UI, page components, mock data, and local cart/order state
- `src/style.css` — responsive visual design system and page styles
- `index.html` — application shell

The current project is frontend-only and stores mock cart/order data in browser local storage.