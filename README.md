# Editorial Portfolio Website

**A static portfolio export presenting services, project imagery, presentation decks, and before-and-after design work.**

[View the website](https://ahsaanstudio.vercel.app)

## What to look at

- Editorial page layout and typography.
- Project and comparison imagery stored in `assets/`.
- Presentation PDFs accompanying project examples.
- Service, FAQ, and contact sections.
- A self-contained static export with its supporting browser runtime.

This is a frontend presentation example. Portfolio text and any outcome claims need their own evidence; the site source alone does not establish client results.

## Preview locally

```bash
git clone https://github.com/ahsaan-10/High-fi-specs-site.git
cd High-fi-specs-site
python -m http.server 8080
```

Open `http://localhost:8080`. Serve the directory over HTTP so the supporting runtime can fetch resources as intended. No npm build step is included in this export.

## Repository map

```text
index.html   Exported page, content, and styling
support.js   Supporting browser runtime
assets/      Project images, portraits, favicons, and presentation PDFs
.nojekyll    Static hosting marker
```

## Hosting

Publish the repository root with a static host, or enable GitHub Pages from `main` and the root folder. The current demo is [Ahsaan Studio](https://ahsaanstudio.vercel.app). Its HTML response and matching page title were checked on 6 October 2026; browser interactions were not tested as part of this documentation update.

Before sharing a deployment, check contact and booking links, social-preview metadata, and assets on both mobile and desktop.
