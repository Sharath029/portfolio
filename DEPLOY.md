# Deploy to GitHub Pages

Follow these steps to publish your portfolio.

## 1. Create the GitHub repository

1. Go to [https://github.com/new](https://github.com/new)
2. **Repository name:** `portfolio`
3. **Visibility:** Public
4. Do **not** add a README, .gitignore, or license (they already exist locally)
5. Click **Create repository**

## 2. Push your code

From the project root:

```bash
git push -u origin main
```

If prompted, sign in with your GitHub account (HTTPS or SSH).

## 3. Enable GitHub Pages

1. On GitHub, open your repo **Sharath029/portfolio**
2. Go to **Settings** → **Pages**
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` → `/ (root)` → **Save**
4. Wait 1–2 minutes. Your site will be at:

**https://sharath029.github.io/portfolio/**

## 4. Add resume PDF (optional)

If `Sharath-cv.pdf` was not pushed (e.g. ignored), add it so the Download button works:

```bash
git add -f Sharath-cv.pdf
git commit -m "Add resume PDF"
git push
```

---

**Live URL for LinkedIn:** https://sharath029.github.io/portfolio/
