# Whispering Pages

A React + Vite bookstore frontend.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown by Vite.

## Production build

```bash
npm run build
npm run preview
```

The project is a static frontend, so it can be deployed directly to GitHub Pages. The book catalog is loaded from Open Library in the browser.

## GitHub Pages

Push the project to a GitHub repository on the `main` branch. The included GitHub Actions workflow builds the project and publishes `dist` to GitHub Pages.

In the repository settings, open **Pages** and set the source to **GitHub Actions**.
