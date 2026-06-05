# Ans Rehman — Portfolio Website

A single-file, fast-loading personal portfolio. No build step, no dependencies — just `index.html`.

## Add your photo

1. Put a square-ish headshot at **`assets/photo.jpg`** (create the `assets/` folder).
2. That's it — the site loads it automatically. Until then, an "AR" monogram shows in its place.
   - Recommended: ~800×950px, JPG or PNG (rename to `photo.jpg`). Keep it under ~300 KB for fast loading.

## Host it free on GitHub Pages

1. Create a new GitHub repository named **`<your-username>.github.io`** (use your actual GitHub username).
2. Upload `index.html` (and the `assets/` folder with your photo) to the repo — drag-and-drop on github.com works fine.
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. Wait ~1 minute. Your site is live at **`https://<your-username>.github.io`**.

To update later, just edit/replace the files in the repo — Pages redeploys automatically.

## Alternative free hosts (drag-and-drop, no Git)

- **Netlify Drop** — drag the project folder onto https://app.netlify.com/drop
- **Vercel** — import the repo at https://vercel.com/new
- **Cloudflare Pages** — connect the repo at https://pages.cloudflare.com

## Edit your content

Everything lives in `index.html`. Search for the text you want to change (name, links, publications, projects) and edit it directly. Key links already wired:

- Email: `ans.rehman.engineer@gmail.com`
- LinkedIn, Google Scholar, and all publication DOIs are set in the relevant sections.
