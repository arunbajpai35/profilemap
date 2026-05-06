# profilemap

react + leaflet front-end that plots user profiles on a map. profile list, per-profile details page, and a small admin page for adding entries. read-only client — no auth, no backend.

**live**: https://arunbajpai35.github.io/profilemap

## stack

vite · react 18 · typescript · tailwind · react-router · leaflet (via react-leaflet)

## run

```bash
npm install
npm run dev    # http://localhost:5173
```

## deploy

deployed to github pages on every push to `main` via `.github/workflows/deploy.yml`. `dist/` is built and uploaded as a pages artifact.
