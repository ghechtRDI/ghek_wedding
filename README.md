# Galen & Emma's Wedding Site

Static site for our wedding — June 12, 2027 at Granite Point Lodge, Resurrection Bay, Alaska.

Plain HTML + CSS, no build step.

## Structure

```
index.html        # all page content
css/styles.css    # styles (palette lives in :root at the top)
images/           # photos
.nojekyll         # tells GitHub Pages to serve files as-is
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploying to GitHub Pages

1. Push to `main`.
2. In the repo on GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main`, folder `/ (root)`
3. The site will be live at `https://<user>.github.io/ghek_wedding/` within a minute or two.

## TODO

Search `index.html` for `TBD` to find placeholders (ceremony time, boat details, lodging, registry).
