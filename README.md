# Supplementary Certs

Study resources for supplementary certifications, alongside the main
certification tracks of the Cyber Warrior Program.

**Live site:** https://rafikiscyent888.github.io/Supplementary-Certs/

This is the "Full Tile" page for the Supplementary Certs tile in the
[Cyber Warrior Command Center](https://rafikiscyent888.github.io/Cyber-Warrior-Command-Center-2.0/).

## What's here

| Resource | What it is | Link |
| --- | --- | --- |
| Physical Security & Resiliency | The PSRDM Study Hub: a study guide and interactive test bank for the VA Physical Security and Resiliency Design Manual | https://rafikiscyent888.github.io/Physical-Security-and-Resiliency-Design-/ |

Physical Security & Resiliency is the first, at the owner's word (16 October
2026). More are to come: a link added here goes on the Command Center's tile
in the same sitting, and the other way round, or the two lists drift apart.

## Colour

The tile is **indigo**, `#4b0082`, the owner's colour for this tile. Indigo is
outside the royal palette, so three indigos were shown as a preview on the
Command Center first (classic `#4b0082`, deep `#3730a3`, bright `#4338ca`), and
the owner picked the classic one: it is the most distinct from the Universal
tile's royal purple and from the page's royal blue. It is dark, so it carries
**light** lettering: white on it measures 12.1:1.

## Accessibility

Text meets **WCAG AAA** (7:1 for body text, 4.5:1 for large text), measured
on the painted pixels of the rendered page, not read from the stylesheet. Easier
reading is built in rather than switched on: a plain sans-serif, generous line
height, short lines, nothing justified. Links darken and gain an outline when
hovered or focused, so the state never depends on colour alone. Nothing
scrolls sideways on a phone.

## Checks

`node verify/page.mjs` drives the page in Chromium: the links, in order, to the
right sites, each in a new tab; the indigo tile with light lettering; the full
footer; AAA on painted pixels on a desk and a phone, at rest and with a link
hovered; no sideways scroll. `node verify/page.mjs --plant` plants eleven mistakes
and confirms every one is caught. Not needed to run the site.

## Hosting

Plain static HTML, no build step, no JavaScript. GitHub Pages serves `main`
from the repo root.

---

Cyber Warrior Program — built by an instructor, for students, to make
certification study more interactive. For educational purposes only. Not
affiliated with, endorsed by, or sponsored by CompTIA®. All trademarks belong
to their respective owners.
