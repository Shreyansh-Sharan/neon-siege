# NEON SIEGE · Arena Shooter

A top-down cyberpunk arena shooter: six heroes with their own blasters and supers, 3v3 Team Takedown and Core Control on three neon maps, and a solo Grid Royale against sixteen bots on a shrinking grid with loot crates. Coins, gear merging, palettes and daily jobs are saved in your browser.

Built with Three.js · Deterministic sim · Twin-stick. Part of [Shreyansh Sharan's portfolio](https://shreyansh-sharan.github.io/shreyanshsharan-portfolio/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- `W` `A` `S` `D` move · mouse aims · `LMB` fire (or auto-fire)
- `E` or `RMB` power · `Q` super · `Space` dash

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.

## Credits

Asset sources and licences: [CREDITS.md](CREDITS.md).
