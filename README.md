# Holland Wave Golf Outing 2026 — Landing Page

Single-page landing site for the 2026 Holland Wave golf fundraiser. Designed to convert visitors into signups by presenting the pitch clearly, then pushing them to the official registration page at `https://www.hollandwave.com/pigeon-creek-golf-outing-2026`.

## Files

- `index.html` — the entire site in one file
- `wave_lockup.png` — the Wave logo
- `README.md` — this file

That's it. No build step, no dependencies, no framework. Works on any static host.

## How to change the destination link later

All "Register" and "Sponsor" buttons point to:

    https://www.hollandwave.com/pigeon-creek-golf-outing-2026

If that URL changes, open `index.html`, search for that URL, and replace all 4 occurrences.

## Free hosting options (ranked)

### Option 1 — GitHub Pages (RECOMMENDED)
Permanent, free forever, tied to your GitHub account (not this platform).

1. Go to github.com and sign up for a free account (2 min).
2. Create a new repo named `hollandwave-golf`. Set it to Public.
3. On the repo page click "uploading an existing file". Drag `index.html` and `wave_lockup.png` in. Click Commit changes.
4. Go to Settings → Pages. Under "Source", pick "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. Wait ~1 min. Your site will be live at `https://YOURUSERNAME.github.io/hollandwave-golf/`.

### Option 2 — Netlify Drop (fastest, but requires free account)
1. Go to app.netlify.com/drop.
2. Sign up with email or Google (free).
3. Drag the whole `hollandwave_landing` folder onto the drop zone.
4. Site is live in ~10 seconds at a URL like `https://elegant-fudge-abc123.netlify.app`. You can rename the subdomain in settings.

### Option 3 — Cloudflare Pages (fast, requires free Cloudflare account)
1. Sign up at cloudflare.com (free).
2. Go to Pages → Create → Upload assets.
3. Drag the folder in, name the project `hollandwave-golf`.
4. Live at `https://hollandwave-golf.pages.dev`.

## Pointing hollandwave.com at this landing page (optional)
Any of the above hosts let you attach a custom domain. Since your main site is at hollandwave.com, you'd use a subdomain like `golf.hollandwave.com`. Ask your web person to add a CNAME record pointing to your Pages/Netlify/Cloudflare URL.

## Preview it locally
Open `index.html` in any browser. That's it.
