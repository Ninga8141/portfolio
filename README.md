# Ninga Portfolio (GitHub Pages Ready)

This is a ready-to-deploy personal portfolio website built from your resume.

## Files
- `index.html` — your site.
- `profile.jpg` — placeholder profile photo (replace with your real photo).
- Resumeddps.pdf — your resume (linked to the Download button). 

## How to go live on GitHub Pages
1. Create a GitHub account (if needed): https://github.com
2. Create a new **public** repository named **yourusername.github.io** (replace `yourusername` with your GitHub username).
3. Upload these files (`index.html`, `profile.jpg`, Resumeddps.pdf).
   - Click **Add file → Upload files** → Commit changes.
4. Open **Settings → Pages** for the repo.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**, and choose branch **main** and folder **/** (root). Save.
6. Visit `https://yourusername.github.io` after a minute and your site should be live.

## Customize
- Replace `profile.jpg` with your own image file of the same name for instant update.
- In `index.html`, update your GitHub link (`https://github.com/yourusername`).
- Edit text in each section as you like.
- To add more projects: duplicate the `<div class="card">` inside the Projects section.

## Update your site
Any time you edit files in the repo and commit, the site updates automatically.

## Netlify (optional alternative)
- Go to https://app.netlify.com/drop and **drag & drop** the folder. You’ll get a `your-site.netlify.app` link immediately.

## Troubleshooting
- If the site 404s: double-check the repo is named exactly `yourusername.github.io` (public).
- If the resume button doesn’t download: ensure the file name is exactly `Resumeddps.pdf` in the repo root.
- If the photo doesn’t change: hard refresh the page (CTRL+Shift+R) after replacing `profile.jpg`.
