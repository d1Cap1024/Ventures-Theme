# Ventures

A dark Obsidian theme that mirrors the [Armando Ventures](https://armandoventures.com) design language: deep purple-black backgrounds, matte gold accents, Playfair Display headlines, Inter for body text. Sharp 4px radii, no soft shadows, a hex/spiderweb watermark on empty panes, and a subtle gold glow anchored top-right of the workspace.

**Dark mode only.** If you toggle to light mode, the theme falls through to Obsidian defaults.

## Install

### Manual

1. Download or clone this repo.
2. Copy the folder into your vault: `<vault>/.obsidian/themes/Ventures/`
   - Only `manifest.json` and `theme.css` are required at runtime.
3. Open Obsidian → **Settings → Appearance → Themes** → select **Ventures**.

### Build from source

```sh
npm install
npm run build      # one-shot compile of src/theme.scss → theme.css
npm run watch      # rebuild on save
```

## Style Settings

Install the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin to expose these knobs under **Settings → Style Settings → Ventures**:

| Setting | Default | What it does |
|---|---|---|
| Accent intensity | Bold | Bold (`#C9A84C`) / Subtle (dimmer gold) / Punch (gold-light as primary) |
| Heading font | Playfair Display | Swap h1/h2 to Inter if you prefer sans |
| Hex watermark | On | The hexagon spiderweb mark on empty panes |
| Gold glow | On | Radial gold gradient anchored top-right of the workspace |
| Tag dot color | `#C9A84C` | The "principle marker" dot rendered before each tag |
| Compact density | Off | Tighter line-height and paddings (~15%) |

## What gets restyled

Backgrounds · text · headings (Playfair on h1/h2 with gold underline on h2) · links · tags (gold-dot principle markers, no pill) · callouts (purple surface, 3px gold rule) · code (JetBrains Mono, gold keywords) · tables · checklists · sidebars · ribbon · tabs (flat with gold underline on active) · status bar · file explorer (gold dot on active file) · graph view · empty-state hex watermark · workspace gold glow.

## Credits

Design language by [Armando Ventures](https://armandoventures.com). Theme implementation: same.

## License

MIT — see [LICENSE](./LICENSE).
