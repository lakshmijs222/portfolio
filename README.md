# Portfolio — Lakshmi Garikapati

Personal portfolio site. Plain HTML/CSS/JS — no build step.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `portfolio` or `<your-username>.github.io`).
2. Push the files in this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from branch → main / root → Save**.
4. Visit `https://<your-username>.github.io/<repo-name>/`.

## Edit

- **Personal info, projects:** `index.html`
- **Colors, layout:** `styles.css`

### Update project links

In `index.html`, replace each `href="#"` with the actual GitHub repo URL or live demo.

### Update contact email

Search for `your.email@example.com` in `index.html` and replace.
