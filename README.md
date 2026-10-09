# whitneyzhang.com

Whitney Zhang's personal academic website, migrated from WordPress to Astro.

## Local development

Requires Node.js 22.12 or newer.

```sh
npm install
npm run dev
```

## Editing research

All papers shown on the homepage and the Research page live in
`src/content/research.md`. Edit that file to add, remove, or reorder papers;
both pages update automatically.

## Deployment

Pushes to `main` or `master` deploy automatically through GitHub Pages. In the repository settings, choose **GitHub Actions** as the Pages source and set `whitneyzhang.com` as the custom domain.
