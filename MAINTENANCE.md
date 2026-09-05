# Website maintenance

The live site is a dependency-free static page served by GitHub Pages from the repository root.

## Main files

- `index.html`: content, metadata, and page structure
- `styles.css`: visual system and responsive layout
- `assets/portfolio/batu-ozturkler.jpg`: profile photo
- `assets/portfolio/og.png`: social sharing image
- `Batu_Ozturkler_Resume.pdf`: primary résumé download

Legacy résumé paths are kept in sync so previously shared links continue to work.

## Preview locally

From the repository root, run:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Publish

Commit and push changes to `master`. GitHub Pages serves the updated files automatically.
