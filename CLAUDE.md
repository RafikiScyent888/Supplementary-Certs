# Supplementary Certs — project context

Read this first in any session touching this repo. The global rules in
`/root/.claude/CLAUDE.md` apply here and win over anything below.

**What it is:** the standalone "Full Tile" page for the Command Center's
Supplementary Certs tile (`cyber-warrior-command-center-2.0`), built 16
October 2026 at the owner's request: "Add this to my cyber warrior command
center under the new tile called: Supplementary Certs ... Add this website at
the first one: https://rafikiscyent888.github.io/Physical-Security-and-Resiliency-
... The color of the new tile is Indigo." Same pattern as the other tile pages
(`Under-the-Hood-labs` is the closest): a royal blue page, one tile, its
links, the full footer.

**Decisions (owner, 16 October 2026):**
- Indigo `#4b0082`, picked from three previewed on the real hub (classic
  `#4b0082`, deep `#3730a3`, bright `#4338ca`). Light lettering (12.1:1).
- The hub tile sits last, after Face Off Games.
- The first link reads "Physical Security & Resiliency" (the owner's choice
  of the ampersand). The URL's trailing dash is the repo's own name.
- No one-line description under the link yet: the Physical Security site and
  its repo weren't reachable from the session that built this, so nothing was
  written about it that couldn't be checked. Add one once it can be read.

**Keep in step:** a link added here is added to the hub's tile in the same
sitting (and its `verify/page.mjs` lists), or the Full Tile button sends
students to a different list from the one they came from.

**Checks:** `node verify/page.mjs` (links, indigo tile with light lettering,
footer, AAA on painted pixels desk and phone at rest and hovered, no sideways
scroll); `--plant` runs ten planted mistakes, all caught. When a link is
added, add it to `EXPECT`.
