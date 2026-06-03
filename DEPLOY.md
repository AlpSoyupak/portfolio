# Deploy to Vercel (Free)

## What you need
- A free [GitHub](https://github.com) account
- A free [Vercel](https://vercel.com) account

---

## Step 1 — Create a GitHub repository

1. Go to https://github.com/new
2. Name it something like `portfolio` (can be private)
3. Click **Create repository**

## Step 2 — Upload your files

Upload both files to the repo root:
- `index.html`
- `vercel.json`

You can drag and drop them directly in the GitHub UI, or use git:

```bash
git init
git add index.html vercel.json
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

## Step 3 — Deploy on Vercel

1. Go to https://vercel.com and sign up / log in with GitHub
2. Click **Add New → Project**
3. Select your `portfolio` repository
4. Leave all settings as default — Vercel auto-detects static sites
5. Click **Deploy**

Your site will be live at:
`https://portfolio-YOUR_USERNAME.vercel.app`

## Step 4 — Custom domain (optional, still free)

In your Vercel project dashboard:
1. Go to **Settings → Domains**
2. Add your own domain (e.g. `alpsoyupak.dev`) if you have one
3. Or use the free `.vercel.app` subdomain — rename it to something like `alpsoyupak.vercel.app` in project settings

---

## Future updates

Any time you push changes to GitHub, Vercel redeploys automatically. Just edit `index.html` and push.

```bash
git add index.html
git commit -m "Update experience section"
git push
```
