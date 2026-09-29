# Shop Helper – Homepage

This repository hosts the public homepage for **Shop Helper**, a personal tool
for managing listings in the Etsy shop of Emin Yüksel, an individual seller
based in Ankara, Turkey. It uses only the official Etsy Open API v3.

The site is served with GitHub Pages at <https://phyxilo.github.io/ShopLister/>
and has three pages:

- `index.html` – what the app does and doesn't do, and how to get in touch
- `privacy.html` – privacy policy
- `callback.html` – the OAuth redirect page shown after Etsy authorization;
  it isn't linked from the navigation and is marked `noindex`

It is plain HTML and CSS (`style.css`), with no JavaScript, build step, or
external resources. Because the site is served from a subpath, all links are
relative (for example `privacy.html`, not `/privacy.html`).

The term 'Etsy' is a trademark of Etsy, Inc. This application uses the Etsy API
but is not endorsed or certified by Etsy, Inc.
