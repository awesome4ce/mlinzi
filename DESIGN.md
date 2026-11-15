---
name: Mlinzi Care Book
description: The care chain written into the patient's own clinic book, every handoff a dated entry stamped by whoever acted.
colors:
  cover: "#1E5A44"
  cover-deep: "#174836"
  cover-ink: "#F1F7F3"
  cover-muted: "#BDD8CB"
  cover-rule: "rgba(241,247,243,.22)"
  page: "#FFFFFF"
  rule-blue: "#C6D7EF"
  margin-red: "#E05A4E"
  ink: "#17202A"
  muted: "#566371"
  line: "#D9E0E8"
  hand-blue: "#1D2F7A"
  carbon: "#2B3170"
  stamp-ai: "#16683F"
  stamp-member: "#1D2F7A"
  stamp-nurse: "#5B3AA6"
  stamp-doctor: "#C22F2B"
  stamp-insurer: "#1F57B8"
  watch-amber: "#8F5300"
  tab-yellow: "#F4C534"
  tab-salmon: "#F29A82"
  tab-sky: "#9FD0EC"
  marker: "#FCEB7A"
  ecg-grid: "#F2C2CB"
  ncr-nurse: "#FFF3BF"
  ncr-doctor: "#FDE1E4"
  ncr-insurer: "#E1ECFB"
typography:
  display:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(30px, 3.2vw, 42px)"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "0.02em"
  headline:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "25px"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "0.06em"
  title:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "21px"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "0.06em"
  hand:
    fontFamily: "Kalam, Comic Neue, Segoe Print, cursive"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: "40px"
  body:
    fontFamily: "Barlow, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.5
  figure:
    fontFamily: "Barlow, system-ui, sans-serif"
    fontSize: "25px"
    fontWeight: 600
    lineHeight: 1.2
    fontFeature: "tnum"
  label:
    fontFamily: "Barlow, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    letterSpacing: "0.06em"
  stamp:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "19px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.06em"
rounded:
  sheet: "2px"
  book: "3px"
  stamp: "5px"
  tab: "8px 8px 0 0"
spacing:
  gutter: "20px"
  grid-gap: "22px"
  rule: "40px"
  section: "72px"
  container: "1240px"
components:
  tab-index:
    backgroundColor: "{colors.tab-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tab}"
    padding: "8px 12px 14px"
    height: "60px"
  stamp-ai:
    textColor: "{colors.stamp-ai}"
    typography: "{typography.stamp}"
    rounded: "{rounded.stamp}"
    padding: "5px 10px 4px"
  stamp-nurse:
    textColor: "{colors.stamp-nurse}"
    typography: "{typography.stamp}"
    rounded: "{rounded.stamp}"
    padding: "5px 10px 4px"
  stamp-doctor:
    textColor: "{colors.stamp-doctor}"
    typography: "{typography.stamp}"
    rounded: "{rounded.stamp}"
    padding: "5px 10px 4px"
  stamp-insurer:
    textColor: "{colors.stamp-insurer}"
    typography: "{typography.stamp}"
    rounded: "{rounded.stamp}"
    padding: "5px 10px 4px"
  slip-nurse:
    backgroundColor: "{colors.ncr-nurse}"
    textColor: "{colors.ink}"
    padding: "24px 22px 18px"
  slip-doctor:
    backgroundColor: "{colors.ncr-doctor}"
    textColor: "{colors.ink}"
    padding: "24px 22px 18px"
  slip-insurer:
    backgroundColor: "{colors.ncr-insurer}"
    textColor: "{colors.ink}"
    padding: "24px 22px 18px"
  sheet:
    backgroundColor: "{colors.page}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "22px 26px 24px"
  nav-link:
    textColor: "{colors.cover-muted}"
    rounded: "{rounded.stamp}"
    padding: "7px 11px"
  nav-link-hover:
    textColor: "{colors.cover-ink}"
  button-link:
    textColor: "{colors.stamp-insurer}"
    padding: "4px 0"
  cuff-prompt:
    backgroundColor: "#FFF6CC"
    textColor: "{colors.ink}"
    rounded: "{rounded.stamp}"
    padding: "10px 14px"
---

# Design System: Mlinzi Care Book

## Overview

**Creative North Star: "The Clinic Book"**

Everything is paper set on an exercise-book cover. The page background is a deep cover green; on it sit white paper objects: one open book spread with a centre gutter, carbon-copy slips in NCR tints, and plain white sheets for tables and plans. Nothing floats, glows or sits on a card. Depth comes from the paper itself: the book's stacked page edges, its gutter shading, the tape on a glued-in strip.

Colour belongs to rubber-stamp ink. Each actor in the care chain owns one ink (Mlinzi AI green, member blue, nurse violet, doctor red, insurer blue), and that ink marks their stamp, their carbon copy's heading and rule, and nothing else. Clinicians and the member "write" in a legible hand; printed form labels are condensed caps; data is set in a plain workhorse sans with tabular figures. The system is single-theme and light only: the user asked for no dark mode.

Density is tuned for a classroom projector: body text is 17px, handwriting 19 to 22px, live figures 24 to 28px, and every screen reads as one paper object at a time.

**Key Characteristics:**
- Deep cover-green ground, white paper objects, no cards
- One stamp ink per actor, used for that actor only
- Three voices: condensed printed caps, a legible hand, a tabular sans for data
- Blue ruled lines and a red margin line as structure, not decoration
- Motion is writing and stamping, one orchestrated sequence at a time

## Colors

A printer's palette: one cover cloth, white stock with blue rules and a red margin, five stamp inks, and three carbonless-copy tints.

### Primary
- **Exercise-Book Cover Green** (cover): the page ground behind everything; also `accent-color` for native controls and the scrollbar track.
- **Deep Cover Green** (cover-deep): the sticky top bar and safe-area strip, one step darker than the ground.

### Secondary (stamp inks)
- **Mlinzi AI Green** (stamp-ai): AI stamps; the "ok" status line; positive cells in the comparison table.
- **Member Ink Blue** (stamp-member): the member's stamp and the dashed border of the home-cuff prompt.
- **Nurse Violet** (stamp-nurse): nurse stamps and the nurse's carbon copy.
- **Doctor Red** (stamp-doctor): doctor stamps, the doctor's referral, flagged readings, the "urgent" status and the irregular heart trace.
- **Insurer Blue** (stamp-insurer): insurer stamps, the insurer's copy, cohort bars, the contract-rule lead-in and the text-link button.
- **Watch Amber** (watch-amber): the "watch" status line and "partial" cells in the comparison table. It is a status ink, not an actor.

### Tertiary
- **Index Tab Yellow, Salmon, Sky** (tab-yellow, tab-salmon, tab-sky): the three scenario tabs on the book's fore-edge, one per scenario. Tab yellow is also the focus ring.
- **Highlighter** (marker): text selection, the "illustrative data" label, and the highlighted Mlinzi row in the comparison table.
- **NCR Yellow, Pink, Blue** (ncr-nurse, ncr-doctor, ncr-insurer): the three carbon-copy slip papers.
- **ECG Pink** (ecg-grid): the graph-paper grid of the heart-rate strip.

### Neutral
- **Page White** (page): book pages and sheets.
- **Rule Blue** (rule-blue): ruled lines under entries, fields and table rows.
- **Margin Red** (margin-red): the vertical margin line on the entries page and the day headings written against it.
- **Print Ink** (ink): printed text on paper and the heavy 2px rules under form heads.
- **Faded Print** (muted): form labels, captions, times, secondary text on paper.
- **Pencil Line** (line): column dividers and page-foot rules.
- **Hand Ink** (hand-blue): handwriting on the book's pages.
- **Carbon Blue** (carbon): handwriting on carbon copies, slightly softened with a 0.6px blur.
- **Cover Ink / Cover Muted / Cover Rule** (cover-ink, cover-muted, cover-rule): text and hairlines set directly on the green cover.

### Named Rules
**The One Ink Per Actor Rule.** An actor's stamp ink appears only where that actor acted or receives: their stamp, their copy's heading and rule. Never use a stamp ink as a general accent.

**The Paper Holds the Colour Rule.** Colour other than the cover green lives on paper (stamps, tabs, slips, highlighter). Text set on the cover is cover-ink or cover-muted only.

## Typography

**Display Font:** Barlow Condensed (with Arial Narrow)
**Body Font:** Barlow (with system-ui)
**Hand Font:** Kalam (with Comic Neue, Segoe Print)

**Character:** A printed clinic form filled in by hand. Condensed caps are the form's printing, Barlow is the clerk's typewriter for data, and Kalam is the nurse's pen, legible first and casual second.

### Hierarchy
- **Display** (700, clamp(30px, 3.2vw, 42px), uppercase, 0.02em): section heads on the cover. The page h1 uses the same voice at clamp(28px, 3vw, 40px).
- **Headline** (700, 23 to 25px, uppercase, 0.06em): printed form heads: the book's title, slip headings, plan names.
- **Title** (700, 21px, uppercase, 0.06 to 0.08em): sub-heads on paper ("Entries", sheet headings).
- **Hand** (400, 21px on a 40px line; 20px on slips, 22px in fields; 700 for emphasis): every handwritten entry, field value and carbon-copy value.
- **Body** (400, 17px, 1.5): running text; secondary text 14 to 16px in faded print.
- **Figure** (600, 24 to 28px, tabular numerals): live readings, heart rate, return figures, prices.
- **Label** (600, 12px, 0.06em, uppercase, Barlow not condensed): printed field labels, reading labels, table column heads (13px).
- **Stamp** (700 condensed caps, 19px verb over an 11px actor name at 0.1em): stamp impressions only.

### Named Rules
**The Who Wrote It Rule.** The typeface says who produced the text. A person's words are in the hand; the form's printing is condensed caps; machine data is Barlow with tabular figures. Do not set data in the hand or a person's note in the sans.

**The Ruled Hand Rule.** Handwriting in the book sits on the 40px rule: its line-height equals the rule gap so every line lands on a blue rule.

## Layout

One centred container, 1240px max, with a 20px gutter (honouring safe-area insets). The first viewport is the open book: a two-column spread whose height clamps between 500px and 660px (100vh minus 186px), left page for the member's form, right page for entries. Scenario tabs hang above the right page's top edge, starting 16px right of the gutter. The entries list scrolls inside the right page.

Below the book, sections sit on the cover with 72px of top space, each opened by a section head (display title left, a 60ch cover-muted sentence right, a cover-rule hairline under both). Paper objects below a head sit in grids with a 22px gap: three slips, a two-column return sheet (44px internal gap), a full-width comparison table that scrolls horizontally inside its sheet, two two-up sheet pairs.

Responsive behaviour: at 900px the spread collapses to one column (left page over right, divided by a dashed line, tabs become a static row above the book without subtitles, margin moves to 60px, readings go 2 by 2); slips stack at 980px; plans stack at 720px; the top nav tightens at 640px; cohort bars narrow at 480px.

**The Ruled Page Rule.** Entries ride a 40px rule gap (blue rule lines drawn by a repeating gradient that scrolls with the content). Day headings occupy exactly one rule.

## Elevation & Depth

Flat paper on a flat cover. The single elevated object is the book, and its depth is physical: a soft drop beneath it plus two solid page-edge layers that read as the stacked leaves of a closed-off book block, and a darkening gradient down the centre gutter. Slips and sheets carry no shadow at all. The slips' scalloped top edge (cover-coloured circles cut into the tint) reads as a torn carbon perforation.

### Shadow Vocabulary
- **Book block** (`box-shadow: 0 34px 60px -34px rgba(0,0,0,.6), 0 3px 0 #DDE3EA, 0 6px 0 #C8D1DB`): the open book only. The two solid 3px and 6px layers are its page edges, not a decorative offset shadow.
- **Gutter** (`linear-gradient(90deg, transparent, rgba(23,32,42,.07) 46%, rgba(23,32,42,.16) 50%, rgba(23,32,42,.07) 54%, transparent)`, 56px wide): the spread's centre fold.

### Named Rules
**The Only the Book Lifts Rule.** The book is the one object with depth. Every other paper object lies flat on the cover; do not add shadows to slips, sheets, tabs or buttons, and do not reuse the page-edge layers anywhere but a book.

## Shapes

Paper geometry: nearly square corners on paper (2px sheets, 3px book), 5px on stamps and the cuff prompt, rounded tops only on index tabs (8px 8px 0 0). Structure is drawn with rules, not boxes: 2px ink rules under form heads and slip heads (in the actor's ink on slips), 1px blue rules under fields and rows, dashed rules for tear-off notes on slips. Stamps are slightly rotated (-3 to -7deg, members' stamps tilt the other way) and run through a fractal-noise displacement filter with multiply blending so they read as ink. The heart-rate strip is glued in: rotated -0.6deg with two translucent tape pieces at its corners.

## Components

### Index tabs (scenario controls)
The primary action. Coloured paper tabs on the book's fore-edge, one colour per scenario, label in Barlow 600 16px with a 13px subtitle. Rest sits 6px down (tucked behind the page); hover lifts to 0; the pressed tab rises to -4px; while a scenario runs the others desaturate and disable. Transition 0.2s cubic-bezier(.2,.8,.2,1).

### Stamps
The signature mark. A bordered impression (2.5px border in the actor's ink, 5px radius) with a condensed verb over the actor's name, rotated, ink-filtered, multiplied onto the page at 0.92 opacity. They land with the press animation after their entry finishes writing.

### Entries
A handwritten line on the ruled page with its time printed in the left margin (600 15px faded print, tabular) and a stamp on the right. New entries write on left to right (clip-path reveal, 0.95s, cubic-bezier(.16,1,.3,1)); the stamp presses at 0.8s (0.32s, overshoot cubic-bezier(.3,1.5,.5,1)). Steps advance every 2.7s. Day headings are margin-red label caps.

### Carbon-copy slips
One slip per receiving actor in its NCR tint with a scalloped top edge; heading in the actor's ink over a 2px actor-ink rule; a label/hand definition list; a dashed-rule footnote saying what that actor sees. A refreshed slip re-writes its values with staggered 0.12s delays. The insurer's slip redacts with solid ink bars until the consent box is ticked.

### Sheets
Plain white paper on the cover for tables and lists: 2px radius, no shadow, ink 2px rule under any header. Tables use 1px blue row rules and tabular figures; the Mlinzi row is highlighted with a marker band (10% inset top and bottom).

### Form fields and readings
Printed label caps beside a handwritten value on a blue rule. Readings sit in a four-column strip under a 2px ink rule with pencil-line dividers; a flagged reading turns doctor red.

### Navigation
A sticky deep-green bar: the wordmark in condensed caps 27px with a cover-muted gloss, links in Barlow 500 15px cover-muted with 5px radius, hover to cover-ink on a 7% white wash.

### Buttons
Two kinds beyond the tabs. The cuff prompt: full-width, pale yellow, 2px dashed member-blue border, bold member-blue line over faded print; hover deepens the yellow. The text-link button: no box, insurer-blue 600 14px, underlined with a 3px offset.

### Consent checkbox
A 24px square ink-bordered box with a hand-ink tick that springs in (0.2s overshoot).

Focus everywhere is a 3px tab-yellow outline with 3px offset.

## Do's and Don'ts

### Do:
- **Do** give every new actor or role a single stamp ink and keep it to their stamp, copy and flagged values.
- **Do** put people's words in Kalam on a ruled line, printed labels in 12px label caps, and numbers in Barlow 600 with tabular figures.
- **Do** set new content as white paper on the cover green: a sheet (2px radius, no shadow) under a cover section head.
- **Do** show the illustrative-data label in the marker highlight wherever pilot figures appear.
- **Do** honour reduced motion: no write or press animations, instant scrolling, slower step cadence (1.4s).
- **Do** keep text at projector sizes: 17px body minimum on paper, 12px only for caps labels.

### Don't:
- **Don't** add a dark theme; the system is single-theme light by the user's decision.
- **Don't** use a stamp ink as a decorative accent or put two actors' inks on one object.
- **Don't** add shadows, cards or floating panels; only the book has depth.
- **Don't** put coloured text directly on the cover; colour lives on paper.
- **Don't** set data or UI copy in the handwriting face, or handwriting off its rule.

<!-- Known gaps shipped at the second finish review (open defects, not system rules; do not copy them into new surfaces):
1. During a run a stamp and the carbon copy it updates are never on screen together; the page scrolls to the copies only when the run ends.
2. The Jubilee return sheet leaves its lower-right quarter empty.
3. The "Doctor's referral" slip heading wraps to two lines.
4. About 140px of dead space under Status on the left page at 1280x720. -->
