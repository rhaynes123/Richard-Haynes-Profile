# Richard Haynes — Personal Site

A single-page static site. No build step, no dependencies.

## Before you deploy — fill these in

Open `index.html` and search for:
- `mailto:your.email@example.com` → your real email
- `href="#"` on the **LinkedIn** button → your real LinkedIn URL
- Double-check the `github.com/rhaynes123` links point where you want

## Deploy to Vercel (easiest: no CLI needed)

1. Push this folder to a GitHub repo (or a new one).
2. Go to https://vercel.com/new
3. Import the repo. Framework preset: **Other** (it's static — no build command, no output directory needed).
4. Click **Deploy**. Done — you'll get a `your-project.vercel.app` URL.

## Or deploy from the CLI

```bash
npm i -g vercel
cd site
vercel        # first deploy, follow prompts
vercel --prod # promote to production
```

## Custom domain

In the Vercel dashboard → your project → **Settings → Domains** → add your domain and follow the DNS instructions.
