# Torrentath — Campaign Console · 5E Compatible

A Dungeon Master's console for the Torrentath campaign and the adjoining
*"Dog" Sled Race* one-shot, with a second screen for the players.

**Build v283 · 2026-08-17**

---

## Open `campaign_console.html` first. That is the whole tool.

`player_display.html` is the **second screen** — the one the players see. Open it
on a second monitor, a TV, or a shared browser tab, and leave it there. It shows
what you push to it and nothing else.

If you only ever open one file, open the console.

---

## What it needs

* **A modern browser.** Chrome, Edge, Firefox or Safari, kept reasonably current.
* **Nothing else.** No install, no account, no server, no internet connection.
  Open the file from your own disk and it runs.
* **Two screens, ideally** — one for you, one for the table. One screen works;
  you just alt-tab.
* **Keep the folder together.** Both screens read `images/` from beside them — move an
  HTML file on its own and the maps go missing. The console does **not** read
  `world_data_console.json`: it carries its own copy of the campaign inside it, and the
  file beside it is that copy, readable and editable, for when you want to see it.

## How the two screens talk

The console and the display talk over the browser's **BroadcastChannel**, so a
push reaches the second screen instantly — as long as **both files are open in
the same browser, on the same machine**. Everything you change is saved in that
browser's **localStorage**, which means your campaign state lives on the machine
you play on: it survives closing the tab, it is never uploaded anywhere, and it
does not follow you to a different computer or a private window.

> Clearing your browser's site data for this file clears your campaign state.
> The console's **↺ Resets** page is the safe way to clear things deliberately.

## What is in the box

| file | what it is |
|---|---|
| `campaign_console.html` | **The DM console. Open this one.** |
| `player_display.html` | The players' second screen. |
| `world_data_console.json` | The campaign: chapters, NPCs, stat blocks, the race. |
| `images/` | 36 maps, plates and legends. |
| `LICENSE.md` | Attribution, art provenance, and what you may do with this. |
| `LICENSES.md` | The per-image provenance record — one row per image. |
| `README.md` | This file. |

## Where the version is

Bottom of the console's left-hand nav, on every page: **Build v283**. The
players' screen carries the same line at the foot of its idle screen while it is
idle.

**Found a problem?** Quote the build line and send it wherever you got this
build. The console's **ⓘ About & Licence** page lists what else a report needs;
the build line is the part it cannot do without.

## What you may do with it

Use it at your table, privately and on stream, for as many games as you like.
**Edit it** — it is a DM tool, and a DM tool a DM may not change is a DM tool that
will be changed anyway. Do not redistribute or resell it, modified or unmodified.
The full statement, and the licences this product owes, are in `LICENSE.md`.

---

*Compatible with fifth edition. This product is not affiliated with, endorsed,
sponsored or approved by any game publisher.*
