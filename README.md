# doriengayrosenthall.com — Dark room

Static single-page site. No build step, no dependencies.

## Files

```
index.html          the whole site (HTML + CSS + JS inline)
images/mosaic.jpg   the artwork — YOU MUST ADD THIS (see below)
```

## Do this first

`images/mosaic.jpg` is **not included** — I could not download it from the live site. Save the mosaic out of your originals and drop it in at that exact path, or the hero and the detail crops render blank.

## Before publishing

1. **Add `images/mosaic.jpg`** with the largest version of the mosaic you have. The magnifier and the three detail crops read the real pixels, so resolution matters: 4000 px on the long edge or more is ideal. If the file goes over ~4 MB, save a JPEG at quality 80.
2. **Artist paragraph** — `index.html`, the `.about` section. Placeholder text is there now.
3. **Title, year, medium** — hero caption. Set to *One Vision, 5,000 Stories*, 2025, 180 × 120 cm; change if wrong.
4. **Email address** — appears twice (`mailto:` link and the contact line). Currently `studio@doriengayrosenthall.com`.
5. **Portrait** (optional) — drop `images/portrait.jpg` in and swap the grey placeholder for an `<img>`.

## Publishing on GitHub Pages

Create a repository, upload the contents of this folder to the root of the `main` branch, then Settings → Pages → Source: `main` / `/ (root)`. The site appears at `https://<user>.github.io/<repo>/`. To use the custom domain, add a file named `CNAME` containing `www.doriengayrosenthall.com` and point the DNS `CNAME` record at `<user>.github.io`.

## Notes

The magnifier is mouse-only and switches off on touch devices, where the three detail crops carry the same idea. Layout collapses to a single column below 860 px.
