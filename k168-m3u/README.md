# K-168 V1.0 M3U (GitHub Pages & Google Drive)

This repo is pre-structured so you can host your `.m3u` as a direct link in two easy ways: **GitHub Pages** or **Google Drive Direct Link**.

---

## Option A) Host on GitHub Pages (recommended)

### 1) Create a new public repo (one time)
- Repo name (suggested): `k168-m3u`
- Check "Public"

### 2) Upload the files (choose one method)

**Method 1 — Web upload (no terminal):**
- Drag the folder contents into the repo:
  - `playlist/K-168_V1.0.m3u`
  - `index.html`
  - `README.md`

**Method 2 — Terminal (git):**
```bash
git init
git branch -m main
git remote add origin https://github.com/<your-username>/k168-m3u.git
git add .
git commit -m "Add K-168 M3U and index"
git push -u origin main
```

### 3) Enable GitHub Pages
- Go to **Settings → Pages**
- **Source**: `Deploy from a branch`
- **Branch**: `main` / `/ (root)`
- Save. Wait ~1–2 minutes.
- Your site URL will be: `https://<your-username>.github.io/k168-m3u/`

### 4) Direct raw link to use in IPTV apps
Use the **raw** link to the file:
```
https://raw.githubusercontent.com/<your-username>/k168-m3u/main/playlist/K-168_V1.0.m3u
```
> Many IPTV players accept the GitHub **raw** URL directly.

Or via GitHub Pages (served by the site):
```
https://<your-username>.github.io/k168-m3u/playlist/K-168_V1.0.m3u
```

---

## Option B) Google Drive Direct Link

1) Upload `K-168_V1.0.m3u` to Google Drive and set **Anyone with the link → Viewer**.
2) Copy the file **ID** from the share URL. It looks like: `https://drive.google.com/file/d/FILE_ID/view?usp=sharing`
3) Construct the **direct** link:
```
https://drive.google.com/uc?export=download&id=FILE_ID
```
If your player has issues with `uc`, try this alternative:
```
https://drive.usercontent.google.com/download?id=FILE_ID
```

---

## One-liners (optional)

**Windows (PowerShell, with Git installed):**
```powershell
git init
git branch -m main
git remote add origin https://github.com/<your-username>/k168-m3u.git
git add .
git commit -m "Add K-168 M3U"
git push -u origin main
```

**macOS/Linux:**
```bash
git init && git branch -m main
git remote add origin https://github.com/<your-username>/k168-m3u.git
git add .
git commit -m "Add K-168 M3U"
git push -u origin main
```

---

## Test links (replace with your username later)

- Raw (GitHub): `https://raw.githubusercontent.com/<your-username>/k168-m3u/main/playlist/K-168_V1.0.m3u`
- Pages: `https://<your-username>.github.io/k168-m3u/playlist/K-168_V1.0.m3u`
```