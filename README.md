# doriengayrosenthall.com — Dark room

Static single-page site. No build step, no dependencies.

## Files

```
index.html                 the whole site (HTML + CSS + JS inline)
images/mosaic.jpg          hero — the mosaic itself. NOT included: keep the
                           file already in your repo, or replace it with a
                           higher-resolution export.
images/mosaic-framed.jpg   the framed work photographed on the wall (included)
```

The hero and the framed-work section both magnify on hover and read the real
pixels of these files, so resolution matters. 3000–4000 px on the long edge is
ideal; if a file goes over ~4 MB, save the JPEG at quality 80.

## Before publishing

1. **Artist paragraph** — in `index.html`, the `.about` section. Placeholder text is there now.
2. **Email address** — appears twice (the `mailto:` link and the contact line). Currently `studio@doriengayrosenthall.com`.
3. **Dimensions** — set as 120 × 180 cm, framed (portrait). Change if that is wrong.
4. **Portrait** (optional) — drop `images/portrait.jpg` in and swap the grey placeholder for an `<img>`.

## Publishing on GitHub Pages

Upload the contents of this folder to the root of the `main` branch, then
Settings → Pages → Source: `main` / `/ (root)`. The site appears at
`https://<user>.github.io/<repo>/`. For the custom domain, add a file named
`CNAME` containing `www.doriengayrosenthall.com` and point the DNS `CNAME`
record at `<user>.github.io`.

## Notes

The magnifier is mouse-only and switches off on touch devices. Layout collapses
to a single column below 860 px.
