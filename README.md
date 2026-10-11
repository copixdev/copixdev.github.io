# Copix public site

Marketing site for **Copix Desktop** and **Copix CLI**.

**Live:** https://copixdev.github.io/

- No accounts, no Copix Web app  
- Desktop installers from [Releases](https://github.com/copixdev/copix-desktop/releases)  
- Standalone CLI via `curl | bash` (macOS/Linux) and `irm | iex` (Windows) from [copix-cli](https://github.com/copixdev/copix-cli)

Copix is **open source** under the [MIT License](https://github.com/copixdev/copix-desktop/blob/main/macOS/LICENSE.txt).

## Develop

```bash
./dev.sh
# or: cd app && npm run dev
```

## Build (GitHub Pages)

```bash
cd app
GITHUB_PAGES=true npm run build
```

The workflow in `.github/workflows/pages.yml` builds `app/` with `base: /` on push to `main` and deploys the `app/dist` output to GitHub Pages.
