# renewandgreen.in

Static website for https://www.renewandgreen.in, served by GitHub Pages.

- Plain HTML, no build step. Each page is a `.html` file at the repo root and is served
  without the extension (`privacy-policy.html` is `/privacy-policy`).
- Shared styles: `assets/style.css`. Images: `assets/img/`.
- Header, nav and footer are repeated in each page, so change them in every file.
- Links between pages are relative (`data`, not `/data`) so the site also works at the
  preview address https://ibneyveli-bit.github.io/renewandgreen/.
- Keep `/privacy-policy`: the BESS app's App Store listing points to it.
- Add new pages to `sitemap.xml`.
