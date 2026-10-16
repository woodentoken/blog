# blog

Static blog built with [Hugo](https://gohugo.io), deployed to GitHub Pages.

- New post: `hugo new content posts/my-post.md` (then set `draft = false`)
- Preview: `hugo server -D`
- Deploy: push to `main` — `.github/workflows/hugo.yml` builds and publishes.

One-time setup: in the repo's **Settings → Pages**, set **Source** to **GitHub Actions**.
