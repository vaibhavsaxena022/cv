# Vaibhav Saxena — Resume Website

A single self-contained page. No build step, no dependencies — the fonts are embedded
and all CSS/JS is inline. Just two files:

```
index.html              ← the website (open it to preview)
Vaibhav_Saxena_SDE.pdf  ← linked by the "Download résumé" buttons
```

To preview locally: double-click `index.html` (opens in your browser).

---

## Deploy (do this from your personal laptop)

Pick ONE. All are free. Keep both files together in the same folder.

### Option A — Netlify Drop (easiest, no account/git needed)
1. Go to https://app.netlify.com/drop
2. Drag this whole `resume-website` folder onto the page.
3. You get a live URL instantly (e.g. `something.netlify.app`). Done.
   - To rename it: Site settings → Change site name.

### Option B — GitHub Pages
1. Create a public repo, e.g. `vaibhavsaxena022.github.io` (this exact name = served at the root).
2. Upload `index.html` and `Vaibhav_Saxena_SDE.pdf` to it.
3. Repo → Settings → Pages → Source: `main` branch, `/root` → Save.
4. Live at `https://vaibhavsaxena022.github.io` in a minute or two.

### Option C — Vercel
1. Install the CLI: `npm i -g vercel`
2. From inside this folder, run: `vercel` (follow prompts; accept defaults).
3. Live URL printed in the terminal.

---

## Add the link to your resume / profiles
Once live, drop the URL into:
- The resume PDF (next to your email/GitHub) — tell me and I'll add it.
- LinkedIn "Website" field, Wellfound, GitHub bio.

## Custom domain (optional)
All three hosts let you attach a domain like `vaibhavsaxena.dev` (~₹800–1500/yr).
Buy from Namecheap/Cloudflare, then point it in the host's domain settings.

## Updating content later
Everything lives in `index.html`. Re-open this project in Claude Code and ask for changes —
or edit the text directly (it's plain HTML). After editing, re-deploy the same way.
