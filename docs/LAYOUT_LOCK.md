# Layout lock (approved 2026-09-23)

Do not redesign without an explicit user request.

1. **Banner** — compact centered CSS `.broncos-banner` (DENVER BRONCOS / JUST THE FACTS + corner accents) above brand/nav. Not image-based; not 2× height.
2. **Standings** — full-width flush-left `.page-shell`; AFC West rail beside main (`clamp(15rem, 20vw, 19.5rem)`, ~1.05rem type). Keep flush to the left edge of the orange page.
3. **Chrome** — orange page `#fb4f14`, white tiles, navy header.

Content updates only on daily runs unless fixing a real bug.

4. **AFC West odds tile** — directly under the standings tile in `.afcwest-rail` (added 2026-09-24): `aside.afcwest-standings.afcwest-standings--odds`, same width/style as standings, 0.75rem gap; Team / Div / SB American odds (Broncos row `is-den`), muted source line.
5. **Body AFC West card removed** (2026-09-24) — the rail standings tile is the only standings display; its title and a small "Full NFL standings" source line both link to https://www.nfl.com/standings/division/2026/REG (new tab). Upcoming card now spans 2 columns so the grid has no empty cell.
6. **Official desk logo** (added 2026-10-01) — Official desk logo docs/broncos-desk-logo.png centered directly below .broncos-banner on every page; keep on regeneration. Markup (inside `header.site-header`, between `.broncos-banner` and `.header-bar`): `<img class="broncos-desk-logo" src="broncos-desk-logo.png" alt="Broncos Desk logo" width="112" height="112">`; styled by `.broncos-desk-logo` in styles.css (clamp 96–120px, centered). The index is hand-regenerated from the previous index each day, so carry this line forward. When a page is copied into docs/archive/, its relative asset paths need `../` (e.g. `../broncos-desk-logo.png`, `../styles.css`).
