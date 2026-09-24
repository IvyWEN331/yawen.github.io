# Ya Wen — Academic Website

A personalised academic website based on the **HugoBlox Kit / Academic CV** template.

## Before publishing

Replace these placeholders:

- `IvyWEN331` in `config/_default/hugo.yaml` and `data/authors/me.yaml`
- `YOUR-EMAIL@example.com`
- LinkedIn / Google Scholar / ORCID URLs
- `static/uploads/Ya_Wen_CV.pdf` with your current CV
- `assets/media/authors/me.png` with your portrait (keep the same filename)

## Publish with GitHub Pages

1. Create a public GitHub repository. For a main personal site, name it `IvyWEN331.github.io`.
2. Upload the **contents** of this folder to the repository root.
3. In GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Push to `main`. The included workflow will build and deploy the site.

## Local editing

Requirements: Hugo Extended 0.162.0+, Node.js, and pnpm.

```bash
pnpm install
hugo server --disableFastRender
```

Then open the local address shown by Hugo.

## Main content locations

- Homepage: `content/_index.md`
- Personal profile: `data/authors/me.yaml`
- Projects: `content/projects/`
- Publications: `content/publications/`
- Navigation: `config/_default/menus.yaml`
- Theme and site settings: `config/_default/params.yaml`
