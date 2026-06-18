# dotcom

The [samelawrence.com](https://samelawrence.com) website — an Astro blog deployed to GitHub Pages.

## Development

```bash
npm run dev      # start dev server at localhost:4321
npm run build    # production build → ./dist
npm run preview  # preview the build locally
```

## Writing

Add new posts as `.md` or `.mdx` files in `src/content/blog/`.

## Deployment

Pushes to `main` automatically deploy via GitHub Actions. Make sure the repo's Pages source is set to **GitHub Actions** in Settings → Pages.
