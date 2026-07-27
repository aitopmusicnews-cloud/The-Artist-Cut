# The Artists Cut — Investor Static Site

A single-file static website for **The Artists Cut**, combining the company's existing distribution/education story with the two current product blueprints:

- **AI Music Video Studio** — AI video generation, audio analysis, timeline editing, media handling, and final rendering.
- **OG BEATZ Vault** — catalog operations, audio intelligence, CRM, promotional sharing, and studio workflow tools.
- **Next Gen Sounds** — experiential education and workforce-development mission already represented on the existing site.

## Site architecture

The public narrative follows one connected creator journey:

**Create → Analyze → Manage → Promote → Distribute → Educate**

This positions The Artists Cut as a broader creator-technology platform rather than a collection of unrelated apps.

## Run locally

No build step is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

You can also open `index.html` directly in a browser.

## Deploy

Because the site is plain HTML/CSS/JavaScript, it can be hosted on GitHub Pages, Netlify, Vercel, Cloudflare Pages, Render Static Sites, S3/CloudFront, or any standard web host.

## Before public launch

Replace the investor-contact placeholder near the bottom of `index.html` with the approved company email, pitch-deck URL, scheduling link, or contact form.

The investor page intentionally avoids inventing revenue, valuation, user-count, fundraising, or market-size figures.
