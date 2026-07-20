# Personal Academic Homepage

A clean, single-page academic homepage template (adapted from
[Jon Barron's website](https://github.com/jonbarron/jonbarron_website)).
Plain HTML + CSS, no build step — just edit and push.

## Quick start

1. **Rename the repo** to `<your-username>.github.io` and enable GitHub Pages
   (Settings → Pages → Deploy from branch `master`/`main`). Your site will be
   live at `https://<your-username>.github.io`.
2. **Edit `index.html`** — replace every `Your Name`, `#` link, and placeholder
   sentence. Look for `TODO` and `EXAMPLE` comments.
3. **Add your assets** in `images/` and `data/`:
   - `images/profile.jpg` — your photo (replace the placeholder)
   - `images/paper1_before.jpg` / `paper1_after.jpg` — cross-fade thumbnail pair
   - `images/paper2.jpg` — a static thumbnail
   - `data/CV.pdf`, `data/bio.txt` — your CV and bio

## Adding a publication

Copy one `<tr>...</tr>` block inside the publications table in `index.html`.
Three patterns are included:

- **Example 1** — image "before/after" cross-fade on hover (highlighted row).
- **Example 2** — plain static thumbnail.
- **Example 3** — video thumbnail that plays on hover (commented out; add an
  `.mp4` and an `.jpg` poster to use it).

Each hover block needs a **unique id prefix** (the examples use `paper1`,
`paper3`) used consistently in the `<tr>` handlers, the `id=`, and the two
JavaScript functions.

## Custom domain (optional)

Add a `CNAME` file containing your domain (e.g. `yourname.com`) and configure
DNS per GitHub's docs.
