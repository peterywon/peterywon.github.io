# How to put this site online (no git needed)

You have 3 files in this folder:
- `index.html` — the website itself (edit this to update content)
- `Peter_Won_CV.pdf` — linked from the "CV (PDF)" button
- `profile.jpg` — (you add this) a square headshot, e.g. 600×600 px. Optional; without it the page just shows a grey circle.

## Step 1 — Create the GitHub repository
1. Go to https://github.com/new (sign in first).
2. **Repository name**: type your username followed by `.github.io` exactly.
   Example: if your GitHub username is `peterwon`, name it `peterwon.github.io`.
3. Set it to **Public**. Do NOT add a README. Click **Create repository**.

## Step 2 — Upload the files
1. On the new empty repo page, click **"uploading an existing file"** (a link in the middle of the page).
2. Drag `index.html`, `Peter_Won_CV.pdf`, and `profile.jpg` (if you have one) into the box.
3. Click **Commit changes** (green button at the bottom).

## Step 3 — Turn on GitHub Pages
1. In the repo, go to **Settings** → **Pages** (left sidebar).
2. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
3. Wait ~1 minute. The page will show your live URL: `https://YOURUSERNAME.github.io/`

That's it — your site is live.

## Updating later
- Edit `index.html` here on your computer, then in the repo on GitHub click the file → pencil icon → paste new content → Commit. Or just re-upload via "Add file → Upload files" (it overwrites).
- New CV? Replace `Peter_Won_CV.pdf` (same filename) and re-upload.

## Custom domain (optional, like andy-li.site)
Buy a domain (~$12/yr at Namecheap/Cloudflare), then in repo Settings → Pages → "Custom domain" enter it, and add the DNS records GitHub tells you to. Free HTTPS is automatic.

## Want the fuller "academicpages" template instead?
Go to https://github.com/academicpages/academicpages.github.io → click **"Use this template"** → name the new repo `YOURUSERNAME.github.io`. It has separate pages for publications, talks, teaching, CV, and a blog, but you edit it in Markdown/YAML and it's many files. The single `index.html` you have now is the low-maintenance option; switch later if you outgrow it.
