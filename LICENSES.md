# Torrentath — Campaign Console · 5E Compatible
# The per-image provenance record

**Build v283 · 2026-08-17 · 36 images**

This file exists because the licence to this product's art is real and the product
said so nowhere. It carries one row per image in `images/`, and it ships with the
product rather than being available on request.

**Format and pixel size on every row are measured off the file's own bytes** — they
are not read off the filename. Two of the 36 files still carry metadata of their
own; the rest were re-saved at some point and lost theirs, which is precisely why a
written record is needed. Where a file's own metadata says something, its row says
what the metadata says.

**The CLASS heading each section below is the one column here that is not measured.**
It is assigned from a file's own metadata where the file has any, and from the picture
otherwise — so two of these rows are evidenced by the file itself and the other
thirty-four are the author's own reading of a picture. All thirty-four were reviewed,
row by row and picture by picture, at v281.

## The two statements that govern all of it

**A licence to generate is not a copyright in the output.** The US Copyright Office
holds that purely AI-generated images are not protected by copyright. The licence
proves the right to make and to sell these images; it does not make the images
themselves protectable, and a buyer's reuse of *them* cannot be restrained.

**What is protectable is everything around them, and that is most of this product** —
the code, the prose, the world, the rules apparatus, the encounter design, the
arrangement, the hand-drawn maps and every plate this project draws itself.

---

### Generated · licensed AI image generator — 15

Produced with a commercially licensed AI image generator under a paid tier that grants commercial use. Receipts are held by the author and are produced on request; the receipt identifiers themselves are not published here.

| file | format | pixels | notes |
|---|---|---|---|
| `001.jpg` | JPEG | 1036×1036 | — |
| `Aedlab.jpg` | JPEG | 1428×784 | — |
| `BhindarulMap.png` | PNG | 1024×1024 | — |
| `BhindarulMap_player.png` | PNG | 1024×1024 | — |
| `Chanfirch.jpg` | JPEG | 1428×784 | — |
| `Knobdimmon.jpg` | JPEG | 1428×784 | — |
| `Oospufmorn.jpg` | JPEG | 1428×784 | — |
| `RV_deck_bottom.png` | PNG | 565×227 | — |
| `RV_deck_crowsnest.png` | PNG | 565×227 | — |
| `RV_deck_helm.png` | PNG | 565×227 | — |
| `RV_deck_sweeps.png` | PNG | 565×227 | — |
| `RV_deck_topdeck.png` | PNG | 565×227 | — |
| `TC_battle_map.png` | PNG | 1024×1024 | photoshop:Credit "Made with Google AI"; IPTC DigitalSourceType trainedAlgorithmicMedia; generator generation id (held, not printed — Q3) |
| `Vum.jpg` | JPEG | 1428×784 | — |
| `sacredTree.jpg` | JPEG | 1428×784 | — |

### Composite · author's drawing, generated frame — 4

The author's own drawing — a graph-paper floor plan or a hand-drawn map — set inside a generated decorative frame, and on two of them this project's own key markers typeset over the drawing. Every half is covered: the drawing and the markers are the author's own work, the frame by the licence above.

| file | format | pixels | notes |
|---|---|---|---|
| `Arret_map.jpg` | JPEG | 1092×1092 | — |
| `TwinsMap.jpg` | JPEG | 1036×1036 | — |
| `player_manor.jpg` | JPEG | 1260×840 | v265 — the bottom-left roundel replaced with a mirrored copy of this frame’s own bottom-right roundel (BL-039 visual check) |
| `player_manor_levels.jpg` | JPEG | 1344×896 | v265 — the same roundel, in the same frame at a second size (BL-039 visual check) |

### Authored · this project's own render — 16

Drawn or typeset by this project. The author's own work, in full.

| file | format | pixels | notes |
|---|---|---|---|
| `Arret_legend.jpg` | JPEG | 1372×896 | — |
| `bhindarul_map_key.png` | PNG | 1024×700 | — |
| `bhindarul_sign_legend.png` | PNG | 1400×1750 | — |
| `map_63_lower_dm.jpg` | JPEG | 1008×1204 | — |
| `map_63_lower_player.jpg` | JPEG | 1008×1204 | — |
| `map_63_upper_dm.jpg` | JPEG | 1008×1204 | — |
| `map_63_upper_player.jpg` | JPEG | 1008×1204 | — |
| `map_64_platform_dm.jpg` | JPEG | 1008×1204 | — |
| `map_64_platform_player.jpg` | JPEG | 1008×1204 | — |
| `maze_aria.jpg` | JPEG | 1008×1064 | — |
| `twin_cities_legend.jpg` | JPEG | 1036×1176 | — |
| `underbelly_legend.jpg` | JPEG | 1316×924 | — |
| `underbelly_ru_ailmen.jpg` | JPEG | 1092×1120 | — |
| `underbelly_ru_ailmen_player.jpg` | JPEG | 1092×1120 | — |
| `underbelly_yuvl_ilmern.jpg` | JPEG | 1288×952 | — |
| `underbelly_yuvl_ilmern_player.jpg` | JPEG | 1288×952 | — |

### Photograph · author's hand-drawn map — 1

A photograph of the author's own hand-drawn pencil map. The camera's EXIF is still in the file and is the evidence for this row.

| file | format | pixels | notes |
|---|---|---|---|
| `world_map.jpg` | JPEG | 868×645 | camera EXIF (samsung); camera EXIF (Galaxy) |

---

## Three things this record does not measure

Recorded plainly rather than guessed, because a record that invents a field is worse
than a record that admits one is missing.

1. **The generator's name, per file.** One file — `TC_battle_map.png` — carries its
   maker's own credit and the IPTC marker for algorithmically generated media. That
   name is *not* extended by inference to the other generated files.
2. **The licence tier, per file.** Held with the receipts.
3. **The purchase date, per file.** Held with the receipts.

## A note on the file extensions

**Every file in this package is named for the format its own bytes hold, and the
seal asserts it.** Until v268 that was not true of 23 of the 36: they were named
`.png` and held JPEG bytes, the residue of a re-save nobody re-measured. Nothing
was broken — browsers sniff the bytes and have never read the name — but a
marketplace validator or an asset pipeline that trusts extensions may reject the
upload, and a buyer who opens `images/` in a tool that does trust them gets an
error on two thirds of the art. The 23 were renamed at v268 and every reference
moved with them, in the world data and in the app.

The column above stayed measured through all of it, and that is the row that
found this. **A record that reports the truth beside a name that does not is a
record doing the job of a gate**, so the assertion moved to where it belongs: no
package seals with a file whose extension disagrees with its first eight bytes.

---

*Compatible with fifth edition. This product is not affiliated with, endorsed,
sponsored or approved by any game publisher.*
