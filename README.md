# Resume — landing page

A tiny, self-contained website (no build step, no dependencies) for GitHub Pages:

- `index.html` — one-screen landing page with an animated stack of CV templates.
- `privacy.html` — Privacy Policy.
- `terms.html` — Terms of Use.
- `styles.css` — shared styles (brand palette: blush + ink `#111827`).

## Publish on GitHub Pages
1. Commit this `docs/` folder and push to GitHub.
2. Repo → **Settings → Pages**.
3. **Source**: *Deploy from a branch* → Branch: `main` → Folder: **`/docs`** → Save.
4. Your site goes live at `https://<username>.github.io/<repo>/` in a minute.

## Customise
- **Name/wordmark**: search for `Resume` in `index.html` (and the header of each page) and replace.
- **Contact email**: replace `hello@example.com` everywhere.
- **App Store link**: the hero button `href="#"` in `index.html` — point it to your App Store URL once live.
- **Colors**: the `:root` variables at the top of `styles.css`.
- **Real template screenshots** (optional): the CV cards are lightweight CSS mockups. To show real app screenshots instead, drop PNGs in `docs/` and swap the `.cv` blocks for `<img>` tags.
