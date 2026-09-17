# Just the Facts — Broncos

A tiny static site for daily Denver Broncos briefings.

## Enable GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Select **Branch: main** and **folder: /docs**, then click **Save**.
4. The site URL will be:

   <https://carrpete75-debug.github.io/PeteCarr-JustTheFacts-Broncos/>

## Cloudflare Pages alternative

Connect the repository to Cloudflare Pages with these settings:

- Framework: **None**
- Build command: leave empty
- Output directory: `docs`

## Daily update

1. Edit `docs/index.html` with the new briefing.
2. Copy the previous index content to `docs/archive/YYYY-MM-DD.html`.
3. Add a link for the new date on `docs/archive/index.html`.
4. Commit and push the changes.
