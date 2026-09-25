# Layout lock (approved 2026-09-23)

Do not redesign without an explicit user request.

1. **Banner** — compact centered CSS `.broncos-banner` (DENVER BRONCOS / JUST THE FACTS + corner accents) above brand/nav. Not image-based; not 2× height.
2. **Standings** — full-width flush-left `.page-shell`; AFC West rail beside main (`clamp(15rem, 20vw, 19.5rem)`, ~1.05rem type). Keep flush to the left edge of the orange page.
3. **Chrome** — orange page `#fb4f14`, white tiles, navy header.

Content updates only on daily runs unless fixing a real bug.

4. **AFC West odds tile** — directly under the standings tile in `.afcwest-rail` (added 2026-09-24): `aside.afcwest-standings.afcwest-standings--odds`, same width/style as standings, 0.75rem gap; Team / Div / SB American odds (Broncos row `is-den`), muted source line.
