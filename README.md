# CutJournal AI - Marketing Site

Marketing and support site for [CutJournal AI](https://cutjournal.com), an iOS body composition tracking app with AI-powered body fat estimation from progress photos.

Built with [Hugo](https://gohugo.io/).

## Local Development

```bash
hugo server -D
```

The site will be available at `http://localhost:1313`.

## Build

```bash
hugo
```

Output is written to the `public/` directory.

## Deployment

The site is automatically deployed via GitHub Actions on push to `main`. See `.github/workflows/deploy.yml`.

## Project Structure

```
content/          # Markdown pages (support, privacy, terms)
layouts/          # Hugo templates and shortcodes
static/           # CSS, images, and other static assets
hugo.toml         # Site configuration
```
