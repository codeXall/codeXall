<div align="center">

![codeXall — independent app company](./assets/codexall-hero-light.png)

# codeXall

### Everyday apps. Made to matter.

An independent UK app company creating, launching and growing its own mobile-first products.

[Website](https://codexall.com) · [Email](mailto:hello@codexall.com)

</div>

---

## About

This repository contains the public company website for **CODEXALL LTD**.

codeXall is an app-first product studio. We identify useful everyday needs, turn them into focused mobile experiences and continue improving each product after release. Our products are conceived, designed, engineered and operated under one roof.

## The website

The site is intentionally small and fast:

- Fully static HTML, CSS and JavaScript
- No framework, build step or runtime dependency
- Responsive across mobile and desktop
- Keyboard-friendly navigation and reduced-motion support
- No forms, analytics scripts or tracking cookies

Everything served to visitors lives inside [`dist/`](./dist).

```text
dist/
├── assets/
│   └── codexall-hero-light.png
├── index.html
├── robots.txt
├── script.js
├── sitemap.xml
└── styles.css
```

## Run locally

From the project directory:

```bash
python3 -m http.server 4173 --directory dist
```

Then open [http://localhost:4173](http://localhost:4173).

## Deploy

The `dist/` directory is the complete deployable website. It can be uploaded to any static hosting provider without a compilation step.

The production domain is intended to be **[codexall.com](https://codexall.com)**. Serve the directory over HTTPS and keep the existing file paths intact.

## Company

**CODEXALL LTD**  
Registered in England and Wales  
[hello@codexall.com](mailto:hello@codexall.com)

## Copyright

© 2026 CODEXALL LTD. All rights reserved.

The source code, visual assets and brand materials in this repository are proprietary unless a separate licence states otherwise.
