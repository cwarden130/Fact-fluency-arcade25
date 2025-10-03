
# Fact Fluency Arcade (Grade 3)

A lightweight React app for +, −, × fact fluency with an in‑browser teacher dashboard and exports.

## Quick start (local)

```bash
npm i
npm run dev
```

Open http://localhost:5173

## Deploy to GitHub Pages

1. **Create a new repo** on GitHub, e.g. `fact-fluency-arcade`.
2. **Upload this folder** (or push via git).
3. In your repo **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**.
4. Commit the provided workflow: `.github/workflows/deploy.yml`.
5. Wait for the workflow to finish; your site will be live at:
   - `https://YOUR_USER.github.io/REPO_NAME/` (project site)

### Vite base path

For project pages, Vite must know the base path. We inject it from the workflow using an env var `REPO_BASE=/{}REPO_NAME}/`. If you host at a custom domain or user site, it will default to `/`.

## Teacher PIN

Default PIN is **1234**. Change it in **Teacher → Settings**.

## Export/Backup

- **CSV**: per‑attempt data for spreadsheets.
- **JSON**: full backup/restore of class data.
