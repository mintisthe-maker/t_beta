# Torrentath Campaign Console — Tester Brief

**Build v283 · 2026-08-17** · read the **Beta Term** beside this first.

You run games. You have not run *this*. This brief exists so the first hour is
about the tool and not about guessing.

---

## What it is, in one paragraph

A **DM console** for a homebrew 5E-compatible campaign — the continent of Arret,
the twin cities, the Dragonspine sled race — plus a **second screen for the
players**. The console is what you drive. The player screen shows only what you
push to it: a map, a handout, a name card, an initiative order, a safety signal.
Everything is one folder of files on your own machine. There is no account, no
server, and nothing leaves your computer.

## Setting it up — five minutes, and two rules that catch everyone

1. Unzip the folder somewhere it can stay. Keep it intact; the HTML files find
   the images beside them.
2. Open **`campaign_console.html`** — that is yours.
3. Open **`player_display.html`** — that is theirs. Put it on the second monitor,
   the TV, or a shared browser tab.

**Rule one: the same browser, on the same machine.** The two screens talk over
the browser's BroadcastChannel. Chrome and Chrome, or Firefox and Firefox — not
one of each, and not across two computers.

**Rule two: your campaign lives in that browser's storage.** Not in the files.
Not in the cloud. **A private/incognito window keeps nothing**, and clearing site
data for the file clears your campaign. This is by design — but people lose a
session to it before they believe it, so: *believe it*.

The console's left-hand nav ends with the build line. **`Build v283`.**

## What we most want you to hammer

- **The nine battle maps and the Battle Board.** Drag tokens, size them
  (Medium → Gargantuan), fly them, drop them in water, run initiative, push the
  board to the players. Try to make the movement range disagree with the ground.
- **The "Dog" Sled Race.** The cockpit, the annual return, the broadcast.
- **The four Fighting Pits** and the ranked ladder.
- **The Atlas** — 139 locations, 114 of which link to a page of their own.
- **The epilogue and the vignettes.**
- **Two screens, live, for a whole session.** The single most valuable thing you
  can do is run one real game end to end and tell us where you reached for
  something that was not there.

## What is known-rough

- **25 Atlas cards deliberately reach no page**, and a few carry a **Detail**
  heading over almost nothing. Known; ranked; not worth a report unless the
  emptiness actively misleads you.
- **Some prose is thinner than the rest.** Chapters vary in polish.
- **A stale display tab shows an old build.** The player screen prints its own
  build at the foot of its idle screen. If it disagrees with the console, reload
  it — and tell us, because that should be hard to do by accident.

## When something is wrong

The console says it on every page, at the foot of the nav:

> **Found a problem? Quote the build line above and send it wherever you got
> this build. What to include: ⓘ About.**

Which means **the Discord**. Four things make a report usable, and one of them
does almost all the work:

| | |
|---|---|
| **The build stamp** | `Build v283`. Foot of the nav; foot of the player screen while idle. **A report without this usually cannot be acted on at all.** |
| **Your browser** | And whether it was a private window. |
| **One screen or two** | A fault on the player screen can look like nothing at all on the console. |
| **What you were doing** | Not a diagnosis — just what you pressed. |

**Screenshots are wanted.** Send them in the Discord; just do not post them
publicly (see the Beta Term).

**And a disagreement is a report.** If something works exactly as built and you
think it is the wrong call, say so. That is not a bug report failing — that is
the more useful kind.

## One thing you will meet on your second build

From v275 every saved thing carries a version stamp, and **a build refuses to
load a save it does not recognise instead of half-loading it.** When you open the
*next* build, pieces of your campaign may come up empty and the nav will read
**↺ Resets · N quarantined**.

**Nothing has been deleted.** The Resets page names every refused piece and
offers **Adopt at current shape** for each. Opening the older build also gives it
back. If you meet this and it feels wrong, that is exactly the sort of thing this
beta is for — tell us what it did.

---

*Thank you. Genuinely — five people running this properly will find more in a
month than every automated gate in the project has found in a year, and the
gates have found a lot.*
