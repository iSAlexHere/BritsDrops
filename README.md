<p align="center">
  <img src="https://img.shields.io/badge/RUST-PVE-cd412b?style=for-the-badge&logo=rust&logoColor=white" alt="Rust PVE"/>
  <img src="https://img.shields.io/badge/BRITS%20WORLD-Loot%20Table-c9a44a?style=for-the-badge" alt="Brits World"/>
  <img src="https://img.shields.io/badge/status-live-7fb840?style=for-the-badge" alt="Live"/>
</p>

<h1 align="center">🔥 BRITS WORLD PVE — Loot Table</h1>

<p align="center">
  <strong>Complete interactive reference for all custom item drop locations on the Brits World PVE server.</strong><br>
  <em>Find where every weapon, armor set, and tool drops — filter by location, difficulty, crate type, and more.</em>
</p>

<p align="center">
  <a href="https://isalexhere.github.io/brits-world-loot-table/">🌐 Live Site</a>
</p>

---

## 📦 What's Inside

A single-page web app that lets you browse **all custom loot drops** on the Brits World PVE Rust server, including:

- **37 custom items** across 8 categories — Weapons, Guns, Special Weapons, Armor Sets (Leviathan, Impact, Dragon Thorns), Tools, and Special items
- **13 drop locations** — Deep Sea, Drone Boss, Dome Event, Water Treatment, Sat Dish, Harbor, Airfield Event, Dungeons, Heli's, Raids, Brads, Supply Drop, and Special sources
- **14 difficulty tiers** — from Easy to Legendary, with color-coded badges

## ⚡ Features

- **Multi-dimensional filtering** — filter by category, location, difficulty, Deep Sea crate source, and Supply Drop availability simultaneously
- **Real-time search** — instant name-based item search
- **Detailed drop view** — click any item to see every location and difficulty where it drops
- **Sorting** — sort by name (A→Z / Z→A) or by number of drop sources
- **Active filter tags** — see and remove active filters at a glance
- **Stats overview** — live count of filtered items, total drops, and category breakdown
- **Rust-themed UI** — designed to match the in-game Rust interface aesthetic (dark charcoal, golden accents, circular icons)
- **Fully responsive** — works on desktop, tablet, and mobile
- **Zero dependencies** — single HTML file, no frameworks, no build step

## 🚀 Deploy

This is a **single `index.html` file** — no build process, no dependencies.

### GitHub Pages
1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your site will be live at `https://your-username.github.io/brits-world-loot-table/`

### Manual
Just open `index.html` in any browser. That's it.

## 🗂️ Item Categories

| Category | Items | Description |
|----------|-------|-------------|
| 🗡️ Weapons | 2 | Brit's custom melee weapons |
| 🔫 Guns | 5 | Custom firearms (Python, Eoka variants, etc.) |
| ⚔️ Special Weapons | 7 | Rare & powerful weapons (Golden AK, AshMaker, BoomStick...) |
| ⭐ Special | 1 | Unique utility items (Helping Hands) |
| 🐉 Dragon Thorns Set | 6 | Full Dragon Thorns armor set |
| 💎 Impact Set | 7 | Full Impact armor set |
| 🌊 Leviathan Set | 7 | Full Leviathan armor set (Deep Sea exclusive) |
| 🛠️ Tools | 3 | Special harvesting tools |

## 🎨 Design

The UI is designed to match the **Rust in-game interface** aesthetic:

- Dark charcoal backgrounds (`#181a1b` / `#222425`)
- Golden amber accent color (`#c9a44a`) for borders, highlights, and headings
- Circular icons with golden borders (matching the Rust quest/reward UI)
- Monospace labels (`Share Tech Mono`) for a military/industrial feel
- Custom SVG icons for every drop location

## 📝 Updating Loot Data

All item data lives in the `ITEMS` array inside `index.html`. To add or modify items:

```javascript
{
  name: "Item Name",
  category: "Category",
  sources: {
    "Location": "Difficulty1 | Difficulty2",
    "Supply Drop": "✓"  // if applicable
  }
}
```

## 📄 License

This project is provided for the **Brits World PVE** community. Feel free to fork and adapt for your own Rust server.

---

<p align="center">
  <sub>Made with ❤️ for the Brits World PVE community</sub>
</p>
