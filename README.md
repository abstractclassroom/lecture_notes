# Abstract Classroom Notes (Just the Docs)

This repo is configured to publish a documentation site with the **Just the Docs** Jekyll theme (dark mode).

## GitHub Pages setup

1. Repo → **Settings → Pages**
2. Source: `main`
3. Folder: `/docs`
4. (Optional) Check **Enforce HTTPS**

If you use a custom domain, keep the `docs/CNAME` file.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000
