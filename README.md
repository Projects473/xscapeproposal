# Xcape Website Proposal

Website proposal for **Xcape Excursions & Taxi Services**, Grenada, with four live demo websites.

## What's here

| Path | What it is |
|---|---|
| `index.html` | The proposal page, with all four demos, the logo and the agreement PDF built in, so it also works as a single file |
| `Xcape-Proposal-Acceptance.pdf` | Fillable acceptance agreement: care plan choice, signatures and deposit |
| `demos/xcape-website.html` | Demo 1 · Xcape Classic (bright travel magazine) |
| `demos/xcape-solaris.html` | Demo 2 · Xcape Solaris (airy resort booking) |
| `demos/xcape-travelik.html` | Demo 3 · Xcape Travelik (dark adventure) |
| `demos/xcape-restin.html` | Demo 4 · Xcape Restin (warm hospitality) |
| `assets/xcape-logo.jpg` | Xcape logo |

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `xcape-proposal`).
2. Upload every file and folder in this package, keeping the folder structure, including the hidden `.nojekyll` file.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute the proposal is live at `https://<your-username>.github.io/xcape-proposal/`.

Or from a terminal:

```bash
cd xcape-proposal-site
git init && git add . && git commit -m "Xcape website proposal and demos"
git branch -M main
git remote add origin https://github.com/<your-username>/xcape-proposal.git
git push -u origin main
```

## Notes

- All fees are in Eastern Caribbean dollars (XCD). Claude AI token costs are billed separately by Anthropic in USD.
- Demo photos are placeholders from Wikimedia Commons (credits in each demo's footer). Prices, reviews and bookings in the demos are examples; no payments are taken.
- The demos' AI Companion runs in guided demo mode on GitHub Pages. In production it connects to Claude through a small server-side API.
- If the repository is public, anyone with the link can see the proposal and pricing. Use a private repository (GitHub Pages on private repos needs a paid plan) or share the link only with Xcape.
