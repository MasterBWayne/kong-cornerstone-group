# Kong Cornerstone Group — Company Website

Static, single-page company website for Kong Cornerstone Group LLC.

## Stack
- Pure HTML/CSS — zero dependencies, zero build step
- Deployable to Vercel, Netlify, or any static host in under 2 minutes

## Deploy to Vercel (recommended)

### Option A — Vercel CLI
```bash
npm i -g vercel
cd /Users/jimmykong/Documents/GitHub/kong-cornerstone-group
vercel --prod
```
Follow the prompts. No framework preset needed — just static HTML.

### Option B — Vercel Dashboard (drag & drop)
1. Go to https://vercel.com/new
2. Drag the `kong-cornerstone-group` folder onto the page
3. Click Deploy

### Custom Domain
Once deployed, go to Settings → Domains in Vercel and add `kongcornerstonegroup.com`.

## Deploy to Netlify (alternative)
1. Go to https://app.netlify.com/drop
2. Drag the folder onto the page
3. Done — live in 30 seconds

## Files
- `index.html` — the entire site
- `vercel.json` — clean URLs config
