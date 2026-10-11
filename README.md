# Cheryl 公 · personal link hub

A full-page personal site for **@ahkongbuys** (lifestyle and streams) and **ahkongcafe** (food and drinks). It replaces Linktree as the link you share.

- `index.html`: the whole site (HTML, CSS and a little JS in one file, no build step)
- `assets/avatar.jpg`: profile photo, taken from your Linktree picture

Open `index.html` in any browser to preview it.

---

## What to edit before you publish

All of these are marked with `EDIT ME` comments inside `index.html` (search for `EDIT ME`).

1. **Collab emails.** Set: Jade Blackz → `heyjadeblackz@gmail.com`, Ah Kong Cafe → `ahkongcafe@gmail.com` (already in the page).
2. **Bio.** The line under your name. Right now it uses your Linktree bio plus one extra line.
3. **Status line.** "On a little break for house reno. Catch me on socials!" in the hero, plus the "Streams are paused for the house reno" band. Change or delete both when streams are back.
4. **Share preview image.** Already set to `https://jadeblackz.github.io/assets/avatar.jpg`, so your photo shows when the link is shared on WhatsApp, X and similar apps.
5. **Photo (optional).** Replace `assets/avatar.jpg` with any square photo and keep the same file name.

All social links were taken from your old Linktrees, so none of them are guesses. The page no longer links to Linktree. There are no `#` placeholder links.

### Adding or removing a link
Copy one `<li>…</li>` line inside a section and change the `href`, the name, and the small `sub` text. The two letters in the `badge` are the little icon text.

### Sections and jump links
The page is one long full-width site: hero, About, Watch & follow, stream update band, Shop & support, Collabs and footer. The sticky menu and the phone bottom bar jump to each section. You can link straight to a part of the page:
- `…/#about`, `…/#watch`, `…/#support`, `…/#collab`
- `…/#streamer` (ahkongbuys socials), `…/#gaming` (JadeBlackz), `…/#cafe` (ahkongcafe)

---

## Publishing on GitHub Pages (free)

### Option A: user site (cleanest URL)
URL will be `https://jadeblackz.github.io/`

1. On GitHub, create a new **public** repo named exactly `jadeblackz.github.io` (your GitHub username).
2. Click **Add file → Upload files** and drag in `index.html` and the `assets` folder. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment" set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**. Save.
4. Wait 1–2 minutes, then open `https://jadeblackz.github.io/`.

### Option B: project site
URL will be `https://jadeblackz.github.io/REPO-NAME/` (for example `.../ahkong-hub/`)

1. Create a public repo with any name, e.g. `ahkong-hub`.
2. Upload `index.html` and `assets/` the same way.
3. In **Settings → Pages**, pick Branch **main**, folder **/ (root)**, then Save.
4. Open `https://jadeblackz.github.io/ahkong-hub/`.

To update the site later, edit `index.html` on GitHub (pencil icon) or upload a new copy. Pages republishes within a minute or two.

---

## Using a Bitly link

1. Copy your live Pages URL from step 4 above.
2. In Bitly, choose **Create new → Link**, paste the Pages URL, and set a custom back-half (e.g. `bit.ly/cherylkong`).
3. Put that Bitly link in your Instagram, TikTok, YouTube, Threads and other bios in place of Linktree.

Tip: you can make extra Bitly links for each section, e.g. `bit.ly/ahkongcafe-links` → `https://jadeblackz.github.io/#cafe`.

If you ever move the site, just edit where the Bitly link points. Your bios don't need to change.

---

## Affiliate note
The Support section includes Shopee and HYGR affiliate links. A short disclosure line sits under that section, and those links use `rel="sponsored"`. Keep the disclosure if you add more affiliate links.
