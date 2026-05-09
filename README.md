# Manoj Ghawate — Portfolio

Static personal portfolio site. Plain HTML / CSS / JS — no build step.

## Files

- `index.html` — page content (edit copy here)
- `styles.css` — all styling
- `script.js`  — small JS for nav, mobile menu, scroll reveals
- `profile.jpg` — your headshot (you add this; see step 1 below)
- `Manoj_Ghawate_CV.pdf` — your resume (you add this; see step 1 below)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## 1. Add your assets

Copy these two files into this folder:

1. Save your headshot as **`profile.jpg`** (the photo you sent in our chat).
2. Save your resume as **`Manoj_Ghawate_CV.pdf`**.

If the photo is missing, the site automatically shows a styled "MG" monogram instead.

## 2. Preview locally

Just double-click `index.html` — it opens in your browser. That's it.

## 3. Deploy to GitHub Pages

See deployment steps in chat. Short version:

```powershell
cd "C:\Users\Manoj Ghawate\portfolio"
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/manojghawate7219/manojghawate7219.github.io.git
git push -u origin main
```

Repo name **must** be `manojghawate7219.github.io` (matches your username).
GitHub Pages will auto-publish at: `https://manojghawate7219.github.io/`

## 4. Editing later

- All text lives in `index.html` — search for the section heading and edit the copy.
- Colors live at the top of `styles.css` (the `:root` block).
- To add a new project, copy one of the four `<article class="project">` blocks and edit it.
