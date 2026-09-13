# Shiv Kumar | Lead Engineer – GenAI & Agentic AI

Personal portfolio / academic site for **Shiv Kumar, Lead Engineer (GenAI / Agentic AI)**.
Built with [Hugo](https://gohugo.io/) + [Wowchemy v5](https://wowchemy.com/). Content is sourced from the resume (`static/uploads/resume.pdf`).

Live URL (GitHub Pages project site): `https://ms-kumar.github.io/shivkumar-portfolio/`

## ⚠️ Hugo version is pinned — read this first

This repo uses **Wowchemy v5.7.1 (Oct 2022)** which **does not build on modern Hugo**.
It fails on Hugo ≥ 0.144 with:

```
template: _shortcodes/table.html:29: function "getCSV" not defined
```

You **must** use **Hugo Extended 0.100.2** (matches `netlify.toml`):

- Local macOS (ARM64):
  ```bash
  curl -L https://github.com/gohugoio/hugo/releases/download/v0.100.2/hugo_extended_0.100.2_macOS-ARM64.tar.gz -o /tmp/hugo.tar.gz
  mkdir -p /tmp/hugo100 && tar xzf /tmp/hugo.tar.gz -C /tmp/hugo100
  /tmp/hugo100/hugo version  # hugo v0.100.2+extended
  ```
- Or with Homebrew (installs latest — only for reference, will NOT build this site):
  ```bash
  brew install hugo  # v0.166+ — expected to fail, see note above
  ```

CI (`.github/workflows/hugo.yaml`) and Netlify (`netlify.toml`) are both pinned to `0.100.2` extended. Do not upgrade Hugo without migrating off Wowchemy v5.

## Run locally

Requires Go 1.18+ (for Hugo Modules).

```bash
# 1. Use Hugo 0.100.2 extended (see above)
/tmp/hugo100/hugo server -D
# open http://localhost:1313/

# 2. Production build (same as CI)
/tmp/hugo100/hugo --gc --minify
# output in ./public/
```

First build downloads Wowchemy modules (~15s). If modules fail, run:

```bash
/tmp/hugo100/hugo mod tidy
/tmp/hugo100/hugo mod graph
```

## Deploy

### GitHub Pages (recommended)

1. Push to `main` (or `site1`).
2. GitHub Action `Deploy Hugo to Pages` builds with Hugo 0.100.2 extended and deploys `./public`.
3. In repo Settings → Pages → Source, select **GitHub Actions**.
4. Site appears at `https://ms-kumar.github.io/shivkumar-portfolio/`.

The workflow passes `--baseURL ${{ steps.pages.outputs.base_url }}/` so it works for both user and project pages without editing `config/_default/config.yaml`.

### Netlify (alternative, already configured)

`netlify.toml` pins `HUGO_VERSION = "0.100.2"`. Just connect the repo; build command is `hugo --gc --minify -b $URL`.

## Update content from resume

- Author profile: `content/authors/admin/_index.md`
- Experience: `content/home/experience.md`
- Skills: `content/home/competitions.md` (titled "Technical Skills")
- Projects: `content/home/misc.md` (titled "Projects")
- Awards: `content/home/awards.md`
- Publications: `content/publication/<slug>/index.md` + `cite.bib` (featured=true shows on homepage)
- CV PDF: replace `static/uploads/resume.pdf` (linked from author social + top nav `CV`)
- Site title / URL: `config/_default/config.yaml` (`title`, `baseURL`)
- Nav: `config/_default/menus.yaml`
- SEO / footer: `config/_default/params.yaml`

## Repo layout

```
config/_default/   # config.yaml (title, baseURL), menus, params, languages
content/authors/admin/  # profile + avatar.png
content/home/      # homepage widgets: about, experience, publications, awards, skills, projects
content/publication/  # 2x IEEE ICRAIS 2023 papers
static/uploads/resume.pdf  # CV
.github/workflows/hugo.yaml  # Pages deploy (Hugo 0.100.2 extended)
netlify.toml       # Netlify deploy (Hugo 0.100.2)
```

## License

MIT — see `LICENSE.md`. Wowchemy theme code retains its original license.
