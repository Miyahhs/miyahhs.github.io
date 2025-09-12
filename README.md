# Pink Profesh — a clean, cute Jekyll theme (for GitHub Pages)

A professional-but-cute Jekyll theme with a tasteful pink palette, sharp typography, and subtle motion.
Perfect for portfolios, blogs, resumes, or lightweight docs.

## Quick start (GitHub Pages)

1. **Download** this zip and extract it.
2. Create a new GitHub repository (or click "Use this template" after you push it once).
3. Push the files to your repo's default branch.
4. In your repo: **Settings → Pages → Build and deployment → Source: GitHub Actions** (recommended) or **Source: Deploy from a branch** (for classic).
5. Edit `_config.yml` with your site title, url, and social links.
6. Commit & push — your site will be live shortly 🎉

### Local development

```bash
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000
```

> If `bundle install` asks to install Xcode CLT on macOS, follow the prompt, then rerun.

## Customize

- Colors: `_sass/_variables.scss`
- Fonts: set in `_sass/_variables.scss` (`--font-sans`, `--font-mono`)
- Navbar/brand: `_includes/header.html`
- Hero section: `index.md` front matter and content
- Buttons/cards/badges: `_sass/_components.scss`
- Post listing: `_layouts/home.html`
- Post layout: `_layouts/post.html`

## Use as a remote theme (optional, advanced)

If you publish this as its own repo and want others to use it as a **remote_theme**, add this to their `_config.yml`:

```yml
remote_theme: your-username/pink-profesh-jekyll
plugins:
  - jekyll-remote-theme
```

And keep only the **`_layouts`**, **`_includes`**, **`assets`**, **`_sass`**, and a **`LICENSE`**/`README` in the theme repo.

## License

MIT — do anything, just keep the license file.
