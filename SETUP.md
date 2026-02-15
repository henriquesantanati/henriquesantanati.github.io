# GitHub Pages Setup Instructions

## Enable GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/ (root)`
4. Click **Save**

GitHub will automatically detect Jekyll and build your site. No GitHub Actions needed!

## Your site will be live at:
`https://henriquesantanati.github.io/`

## First Deployment

After enabling Pages:
1. Push your changes: `git add . && git commit -m "Initial Jekyll setup" && git push`
2. Wait 1-2 minutes for GitHub to build
3. Visit your site URL

## Optional: Custom Domain

To use a custom domain:
1. Add your domain in **Settings** → **Pages** → **Custom domain**
2. Create a `CNAME` file in your repo root with your domain
3. Configure DNS with your domain provider (add CNAME record pointing to `henriquesantanati.github.io`)

---

That's it! GitHub Pages handles everything automatically for Jekyll sites.
