# Reese Bowling — Portfolio Site

A custom-coded, framework-free static site (plain HTML/CSS/JS — no build step required).

## What's in here

```
index.html                     Homepage: hero, about, case studies grid, skills, beyond the desk, resume/contact
case-studies/*.html            5 expanded, anonymized case-study deep-dives
assets/css/style.css           All site styling
assets/js/main.js              Mobile nav toggle
assets/img/                    Drop photos here (headshot, ranch, camp, LLC logo)
assets/resume/                 Drop your resume PDF here (see README.txt inside)
```

## Status

All placeholders are filled in: email, LinkedIn, headshot, resume PDF, and all three Beyond the Desk photos/bios (A Bar A, Deerfoot Lodge, Bowling Capital Properties). This is publish-ready as of the last update.

## How to publish it (pick one)

### Option A — Netlify (recommended: free, custom domain, no git required)
1. Go to netlify.com → sign up free.
2. Drag-and-drop this whole folder onto the Netlify dashboard ("Deploy manually").
3. Netlify gives you a live URL immediately (e.g. `yourname.netlify.app`).
4. In Site settings → Domain management, add your custom domain once you've bought one.

### Option B — GitHub Pages (free, ties nicely to a developer-facing portfolio)
1. Create a new GitHub repo (e.g. `portfolio` or `yourname.github.io`).
2. Push this folder's contents to the repo's `main` branch.
3. In repo Settings → Pages, set source to `main` / root.
4. Site goes live at `https://<username>.github.io/<repo>` (or the root domain if the repo is named `<username>.github.io`).
5. Add a custom domain in the same Pages settings screen once purchased.

### Option C — Vercel (free, great if you want a github-connected auto-deploy workflow)
1. Push the folder to a GitHub repo.
2. Import the repo at vercel.com → deploy (no config needed, it's static HTML).

## Domain name suggestions

Verify availability on a registrar (Namecheap, Google Domains successor Squarespace Domains, Cloudflare Registrar) before building anything around a name:

- reesebowling.com
- reesebowling.dev
- reesebowlinganalytics.com
- bowlingcapitalproperties.com *(separate — for the LLC, if you ever want it to stand alone)*

`.com` reads most credibly on a resume; `.dev` is a nice signal for a technical/engineering-leaning audience if `.com` is taken.
