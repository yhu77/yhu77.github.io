# Field Notes

A minimal personal blog built with Astro and ready for GitHub Pages.

## Personalize it

Edit `src/data/site.ts` to change the title, author, description, and email. This project is configured for `https://yhu77.github.io`. If you later move it to another repository, update `site` and `base` in `astro.config.mjs`.

Posts live in `src/content/posts`. Duplicate one of the Markdown files, update the details between the `---` lines, and write below them.

## Preview locally

```bash
npm install
npm run dev
```

## Publish

Create a GitHub repository, push this project to its `main` branch, then open **Settings → Pages** and choose **GitHub Actions** as the source. Future pushes will publish automatically.
