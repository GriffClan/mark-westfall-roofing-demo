# Mark Westfall Roofing — Website Redesign & Growth Pitch Package

This folder is a complete, zero-build static website ready for **Cloudflare Pages** or **GitHub Pages**.

## Files Included
- `index.html` — Lightweight (~30 KB) interactive presentation with all 3 Website Redesign Concepts + Tab 4 (SEO/AI Audit & ROI Calculator) + 24/7 AI Roof Assistant Drawer.
- `assets/hero-heritage-clay-tile.jpg` — Concept 1 Hero Image (San Pedro Spanish Clay Tile Roof).
- `assets/hero-modern-cool-shingle.jpg` — Concept 2 Hero Image (South Bay Cool Roof Shingles & Skylights).
- `assets/hero-commercial-silicone.jpg` — Concept 3 Hero Image (Commercial Silicone Cool-Roof Coating).
- `llms.txt` — AI Search / Answer Engine optimization file for ChatGPT, Claude, and Perplexity.
- `robots.txt` & `sitemap.xml` — Search engine & AI crawler directives.
- `_headers` — Cloudflare Pages performance & security headers.
- `.nojekyll` — Ensures GitHub Pages serves all files without Jekyll processing.

## Option A: Fastest Deploy on Cloudflare Pages (No GitHub Required — 30 Seconds)
1. Log in to your **Cloudflare Dashboard** → **Compute (Workers & Pages)** → **Pages**.
2. Click **Create** → **Pages** → **Upload assets** (Direct Upload).
3. Name your project (e.g., `mark-westfall-roofing`), drag and drop this entire folder (or the `.zip` file), and click **Deploy site**.
4. You will immediately get a free live link (`https://mark-westfall-roofing.pages.dev`) to send or show to Mark!

## Option B: Let Codex Push to GitHub & Deploy
Open Codex in this folder and paste:
> "Initialize a git repository in this folder, create a new public GitHub repository named `mark-westfall-roofing-demo`, push all files to the `main` branch, and enable GitHub Pages (or deploy it to my Cloudflare Pages account via `npx wrangler pages deploy . --project-name=mark-westfall-roofing`)."
