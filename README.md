# HADI DESIGNER INDONESIA PORTFOLIO

Static single-page portfolio (HTML/CSS/JS, no build step).

## Edit content
Open `index.html` and edit the `CFG` object in the `<script>` block: bio, WhatsApp/Instagram links, and the titles/categories of each artwork. Artwork lives in `images/portfolio/` (keys in `CFG` match file names).

## Deploy to Vercel
1. Push this folder to a new GitHub repo named `hadi-designer-indonesia-portfolio`.
2. In Vercel: Add New > Project > import the repo.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Root Directory: `./`.
4. Deploy. No environment variables needed.

## Push to GitHub
```
git init && git add . && git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/hadi-designer-indonesia-portfolio.git
git push -u origin main
```
