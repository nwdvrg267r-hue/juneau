# Publishing Your Travelogue on GitHub Pages

**Time needed: about 10 minutes · Cost: free**

---

## Step 1 — Create a free GitHub account

Go to [github.com](https://github.com) and sign up. Choose any username — it will appear in your blog's URL (e.g. `yourusername.github.io/adventures`).

---

## Step 2 — Create a new repository

1. Once logged in, click the **+** icon (top right) → **New repository**
2. Name it something like `adventures` or `travelogue`
3. Make sure it's set to **Public** (required for free GitHub Pages)
4. Click **Create repository**

---

## Step 3 — Upload your files

1. On your new repository page, click **uploading an existing file** (there's a link in the middle of the page)
2. Drag these three files into the upload area:
   - `index.md`
   - `_config.yml`
   - Any photos you want to host (optional — see "Adding Photos" below)
3. Click **Commit changes**

---

## Step 4 — Turn on GitHub Pages

1. In your repository, click **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under "Branch", select **main** and click **Save**
4. GitHub will show you your site's URL — something like `https://yourusername.github.io/adventures`

It takes about 2–5 minutes to go live. Refresh the page and the URL will appear as a clickable link when it's ready.

---

## Step 5 — Share it!

Copy the URL and send it to family and friends. That's your travelogue, live on the internet.

---

## Adding Your Own Photos

**Option A — Host photos elsewhere (easiest)**
Upload photos to Google Photos, iCloud, or Imgur and copy the direct image link. Paste it in `index.md` where you see `https://picsum.photos/...`.

**Option B — Host photos in GitHub (keeps everything together)**
1. In your repository, click **Add file → Upload files**
2. Upload your photos (e.g. `kyoto-2025.jpg`)
3. In `index.md`, replace the URL with just the filename: `![Caption](kyoto-2025.jpg)`

---

## Adding a New Trip

1. Open `index.md` on GitHub (click the file, then the pencil ✏️ icon to edit)
2. Find the template comment at the bottom of the "Trip Stories" section
3. Copy the template, fill in your trip details, and click **Commit changes**

Your site updates automatically within a minute or two.

---

## Changing the Theme

Open `_config.yml`, change `theme:` to any of these:
- `jekyll-theme-cayman` — clean green header (default)
- `jekyll-theme-minimal` — very simple, white
- `jekyll-theme-slate` — dark sidebar
- `jekyll-theme-midnight` — dark background

Preview all themes at [pages.github.com/themes](https://pages.github.com/themes/).

---

*Questions? GitHub has free step-by-step help at [docs.github.com/pages](https://docs.github.com/pages).*
