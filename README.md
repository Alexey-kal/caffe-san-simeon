# Caffè San Simeon — Website

Static website for **Caffè San Simeon**, 39 Rue Dante, Montreal QC H2S 3B3.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main site (deploy this) |
| `logo.png` | Brand logo (transparent shield) |
| `hero_bg.mp4` | Hero background video |
| `coffee2.mp4` | Hero coffee video |
| `vercel.json` | Vercel cache headers |

## Deploy to GitHub + Vercel

### 1. Create a new GitHub repo

```bash
cd "caffe simon"
git init
git add index.html logo.png hero_bg.mp4 coffee2.mp4 vercel.json .gitignore README.md
git commit -m "Add Caffè San Simeon website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/caffe-san-simeon.git
git push -u origin main
```

### 2. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) → **Add New Project**
2. Import your GitHub repo
3. Framework Preset: **Other** (static — no build step)
4. Root Directory: `/` (repo root)
5. Click **Deploy**

Live in ~30 seconds. Vercel auto-deploys on every push to `main`.

## Contact

(514) 272-7386

*Built by Viral Lead Studio*
