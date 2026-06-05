<p align="center">
  <img src="assets/hero.png" width="860" alt="TFM2 Forge — champion creator for Teamfight Manager 2">
</p>

<h1 align="center">TFM2 Forge</h1>

<p align="center">
  <b>A visual champion creator for Teamfight Manager&nbsp;2.</b><br>
  Design a champion's stats, abilities, art, effects and sounds in a friendly desktop app —<br>
  TFM2 Forge writes a complete, valid mod straight into your game's <code>mods/</code> folder. <b>No JSON, no coding.</b>
</p>

<p align="center"><i>Created by <b>Zietes</b>. Fan-made; not affiliated with TeamSamoyed.</i></p>

---

## ⬇️ Download

➡️ **[Download the latest release](https://github.com/Zietes/tfm2-forge/releases/latest)**

| File | What it is |
|------|------------|
| **`TFM2Forge-Setup.exe`** | Installer — **recommended** (per-user, no admin; adds a Start-menu shortcut) |
| `TFM2Forge-Alpha.zip` | Portable — extract & run, nothing to install |

**Requirements:** Windows 10/11 and Teamfight Manager&nbsp;2 (Steam). Everything else is bundled — no Python or browser needed.

> ⚠️ This is an **unsigned Alpha** build, so Windows SmartScreen may warn you — click **More info → Run anyway**. You can verify any download against the `SHA256SUMS.txt` included with each release.

---

## ✨ What you can do

### 🎨 Design a champion — no coding
Set a name, category, role tags and stats; start fresh or clone a base champion as a template. Everything updates live, and a built-in validator keeps your champion correct before it ever reaches the game.

### ⚔️ Build abilities from recipes — with a live preview
Pick from **36 ready-made recipes** (skillshots, dashes, AoE, hooks, shields, damage-over-time…) and tune the numbers — or drop into the advanced **Flow** node editor for full control. The **Ability Preview** draws range, area and timing **to scale** and animates the cast, so you can *see* exactly what your ability does.

<p align="center">
  <img src="assets/ability-builder.png" width="780" alt="Recipe-based ability builder with a live, to-scale preview"><br>
  <img src="assets/ability-preview.gif" width="320" alt="Animated, to-scale ability preview">
</p>

### 🖼️ Reuse your game's own art
Browse and reuse all **60 base champion sprites** and **hundreds of ability icons** straight from your own install — or upload custom sprites, projectiles, effects (`.aseprite` / PNG) and sounds. Nothing from the game is bundled or redistributed; it's read from *your* copy.

<p align="center">
  <img src="assets/art-pickers.png" width="780" alt="Base champion sprite picker and ability icon picker">
</p>

### 📊 Instant balance feedback
See DPS, burst, sustained damage and effective HP at any level — and how your champion ranks against the 60 base champions — so you can balance as you build.

<p align="center">
  <img src="assets/balance.png" width="300" alt="Balance & Feedback panel">
</p>

…plus **multi-champion mods**, passives, per-ability character animations, cast/impact VFX & SFX, undo/redo with draft auto-save, and one-click save straight into `mods/`.

---

## 🚀 How to use it

1. **Start** a champion — new, clone a base champion, or open one of your mods.
2. **Build** it — identity, sprite, stats and up to four abilities (guided recipes or the **Flow** editor), plus icons, projectiles, effects and sounds.
3. **Watch the right-hand rail** — the **Ability Preview**, **Balance & Feedback** and live **Validation** all update as you go.
4. **Save to mods/** — then in Teamfight Manager&nbsp;2, enable the mod and **restart the game** to see your champion in the draft.

Click **? Help** in the app any time for the in-app guide.

---

## 🔄 Updates

TFM2 Forge checks here for new releases on launch. When one is available a banner appears — click **Update now** and it downloads and installs the update for you, then reopens. You can turn the check off in **? Help**.

---

## 🛠️ Troubleshooting

- **Champion doesn't appear in-game** — read the title-screen *diagnostics popup*; it names the file that failed. Make sure the mod is enabled and that you restarted the game.
- **"Game not found"** — point the tool at your `Teamfight Manager2` folder when prompted (the one containing `bundle.game_data`).
- **Always back up** your `mods/` folder before big changes.

---

## 🔒 Privacy

TFM2 Forge runs entirely on your machine (a local server bound to `127.0.0.1`). It reads art and data from **your own** game install and **does not** download or redistribute any game assets. The only network request it makes is the version check described above.

---

<sub>© 2026 Zietes. All rights reserved — see <a href="LICENSE.txt">LICENSE.txt</a>. This is a proprietary tool distributed as compiled releases; the source is not published. Teamfight Manager&nbsp;2 and all related assets are trademarks / copyrights of TeamSamoyed.</sub>
