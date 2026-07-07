# the crabgrass 🦀

This repository **is** the website at [kirtanahariharan.com](https://kirtanahariharan.com). Whatever is on the `main` branch is what the world sees — any change you save here goes live automatically within a minute or two. No build step, no deploy button.

## What's in here

| File | What it is |
|---|---|
| `index.html` | The entire page — text, links, styling, everything |
| `Vol 1 of The Crabgrass.pdf` etc. | The volumes, linked from the left side of the page |
| `crab_in_grass.png` | The crab |
| `CNAME` | Connects the site to kirtanahariharan.com — **don't edit or delete this** |

There are also a couple of PDFs (`Kirtana Hariharan- Poetry Portfolio.pdf`, `nonfiction_essays.pdf`) that aren't linked from the page but are still reachable by direct URL.

## How to make changes (all in the browser)

### Edit the text on the page
1. Open `index.html` in this repo and click the **pencil icon** (top right of the file view).
2. The human-readable parts are near the bottom, between `<body>` and `</body>`:
   - the volume links (the `<a href="...">` lines in the first `side-links` block)
   - the italic line under the crab (`and the sun bore its great grapefruit weight`)
   - the blurb and attribution on the right
3. Click **Commit changes** (the green button). That's it — reload the site in a minute.

### Add or replace a volume PDF
1. On the repo's main page, click **Add file → Upload files**, drag the PDF in, and commit. To replace an existing volume, upload a file with the **exact same name** and it overwrites the old one.
2. If it's a *new* volume, also edit `index.html` and add a line next to the other volumes:
   ```html
   <a href="Vol 4 of The Crabgrass.pdf" target="_blank">Volume 4: Whatever It Becomes</a>
   ```
   The `href` must match the uploaded filename exactly, spaces and all.

### Change the crab (or any image)
Upload the new image the same way, then update the `<img src="...">` line in `index.html` to point at it.

## If something breaks

Every version of every file is saved forever. Click **History** on any file, find the last good version, and it can be restored — nothing you do here is permanent-permanent. (Or just email Kaivu.)
