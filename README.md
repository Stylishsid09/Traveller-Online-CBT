# Infinite World Explorer

A small 3D procedural exploration game built with Three.js and plain JavaScript.

## Run locally

Because `main.js` is an ES module, serve the folder through a local web server.

With Python:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `main.js`, and this README.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`.
6. Save and wait for GitHub Pages to publish.

No build step or backend is required. Three.js is loaded from jsDelivr.

## Controls

- **WASD / Arrow keys** — move
- **Mouse** — look around
- **Shift** — sprint
- **Esc** — release mouse
