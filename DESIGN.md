---
name: Moyo
description: A dark, data-forward care console where one amber signal travels from the band through AI, nurse, doctor and insurer.
colors:
  ink-ground: "#070D10"
  ink-ground-2: "#0B1317"
  panel: "#0E181D"
  panel-raised: "#132028"
  hairline: "#1A2B32"
  hairline-strong: "#28414B"
  brand-mint: "#4EE1B5"
  brand-trace: "#3CC8A9"
  signal-amber: "#F5A524"
  signal-ink: "#1A1204"
  nurse-violet: "#A491FF"
  doctor-coral: "#FF7366"
  insurer-blue: "#56A8FF"
  fg: "#E8F0F2"
  muted: "#93A7AF"
  dim: "#5D717A"
typography:
  display:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(32px, 3.6vw, 46px)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.03em"
    fontVariation: "wdth 110"
  headline:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(28px, 2.7vw, 36px)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.03em"
    fontVariation: "wdth 110"
  title:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "0em"
    fontVariation: "wdth 100"
  body:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
  lede:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0em"
  label:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0.02em"
  label-key:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0.03em"
  reading-hero:
    fontFamily: "Inter (tabular numerals), ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "56px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "-0.06em"
  reading-kpi:
    fontFamily: "Inter (tabular numerals), ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "34px"
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "-0.04em"
  reading-metric:
    fontFamily: "Inter (tabular numerals), ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "22px"
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  reading-inline:
    fontFamily: "Inter (tabular numerals), ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: "-0.01em"
  timestamp:
    fontFamily: "Inter (tabular numerals), ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "-0.01em"
rounded:
  mark: "2px"
  redact: "3px"
  key: "4px"
  focus: "6px"
  control: "7px"
  field: "10px"
  panel: "12px"
  pill: "99px"
spacing:
  hairline: "1px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "22px"
  xl: "28px"
  gutter: "24px"
  section: "88px"
components:
  panel:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.fg}"
    rounded: "{rounded.panel}"
    padding: "20px 22px"
  stage-card:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.fg}"
    rounded: "{rounded.panel}"
    padding: "13px 14px 12px"
  kpi-tile:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.brand-mint}"
    typography: "{typography.reading-kpi}"
    padding: "18px 18px 16px"
  button-scenario:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.control}"
    padding: "7px 12px"
  button-scenario-hover:
    backgroundColor: "{colors.panel-raised}"
    textColor: "{colors.fg}"
  button-scenario-selected:
    backgroundColor: "{colors.signal-amber}"
    textColor: "{colors.signal-ink}"
  button-secondary:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.muted}"
    rounded: "{rounded.field}"
    padding: "0 12px"
    height: "40px"
  button-secondary-hover:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.fg}"
  cuff-prompt:
    backgroundColor: "rgba(245,165,36,.1)"
    textColor: "{colors.signal-amber}"
    rounded: "{rounded.field}"
    padding: "10px 12px"
  chip-state:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  chip-pill:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
    padding: "3px 9px"
  tag-provenance:
    backgroundColor: "transparent"
    textColor: "{colors.signal-amber}"
    rounded: "{rounded.pill}"
    padding: "2px 9px"
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.control}"
    padding: "6px 10px"
  nav-link-active:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.fg}"
  kbd-key:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.key}"
    padding: "3px 5px"
  toggle:
    backgroundColor: "{colors.hairline-strong}"
    rounded: "{rounded.pill}"
    width: "34px"
    height: "20px"
  toggle-on:
    backgroundColor: "{colors.insurer-blue}"
---

<!-- Recorded from the shipped index.html on 2026-11-15. Replaces the rejected "Clinic Book" paper system entirely. Provenance note: the independent finish reviewer's verdict pass was cut off by a rate limit; the last fix batch and the restyle that followed were scored by the build thread, not by the reviewer. -->

# Design System: Moyo

## Overview

**Creative North Star: "The Guardian's Console"**

Moyo is a dark operations console for care, not a marketing page and not a notebook. Everything sits on a deep blue-green ink ground; content lives in quietly raised panels drawn with hairline borders, a one-pixel lit top edge and a soft dropped shadow. The page is data-forward: every reading, price, count and timestamp is set in a monospaced face with tabular figures, so numbers line up like instrument readouts, while headings are set wide and heavy in Inter so the product has a voice of its own.

Colour is rationed by meaning. Mint is the brand: it marks sections, lights the KPIs, traces the heartbeat and stands for the AI. One warm amber, the guardian's lamp, belongs to the live signal alone: the pulse on the connector, the selected scenario, the cuff prompt, the scroll progress line, the Moyo column of the comparison. Each actor in the care chain owns one muted ink (AI mint, nurse violet, doctor coral, insurer blue) that colours only its stage mark, its state chip, its node on the track and its name in the log. Nothing glows, nothing is gradient-filled text, nothing is paper.

Density is presentation density: the whole first viewport fits 1280x720, panels are tight (13-22px padding) and type stays legible from the back of a room. Motion is the pipeline's own: the pulse travels, values rise into place, KPIs count up, bars grow, sections reveal on scroll, and every one of them has a complete resting state under reduced motion.

**Key Characteristics:**
- Deep blue-green ink ground with raised, hairline-bordered panels and a single faint mint wash top-right of the hero
- Brand mint for KPIs, section marks and the AI; amber reserved for the live signal; one muted ink per actor
- Inter, semibold and tight for headings; Inter (tabular numerals) with tabular numerals for every number and timestamp
- Hairline-grid tiles (1px gaps over the line colour) instead of nested boxes
- Panels with an inset top highlight and a soft, long dropped shadow; no glows, no gradient text
- Motion grammar of travel, rise, count and grow, all from a visible resting state

## Colors

A near-black blue-green ground with cool, desaturated greys for text and one saturated accent per meaning.

### Primary
- **Brand Mint** (`brand-mint`): the Moyo accent. Section marks (the 36x3px bar above every section heading), KPI figures, the "Demo data" live dot, the AI actor and the Moyo Plus card's border tint (`rgba(78,225,181,.45)`). Also the top of the hero's faint radial wash (`rgba(78,225,181,.09)`).
- **Trace Mint** (`brand-trace`): a slightly dimmer mint for drawn lines, the ECG stroke and its area fill (`rgba(60,200,169,.2)`), and the "Yes" tick icon. Use it where mint must sit on the panel at thin weights.

### Secondary
- **Signal Amber** (`signal-amber`): the guardian's lamp, used only for the live event. Track fill and pulse, selected scenario button, cuff prompt border and tint (`rgba(245,165,36,.1)`, hover `.16`), scroll progress line, the provenance tag, the Moyo column in the comparison (`color-mix(in oklab, signal 7%, panel)` with a 2px inset top rule), the "Partly" icon, the shield in the logo, text selection (`rgba(245,165,36,.35)`), the `accent-color` and the focus ring.
- **Signal Ink** (`signal-ink`): the only dark text in the system, used on amber fills (selected scenario, its kbd key at `rgba(26,18,4,.35)` border).

### Tertiary (actor inks)
- **Nurse Violet** (`nurse-violet`), **Doctor Coral** (`doctor-coral`), **Insurer Blue** (`insurer-blue`), and the AI's **Brand Mint**: each actor's single ink, applied through the `--c` custom property on its stage. It colours the 8px square mark beside the stage title, the 2px top rule (35% at rest, 100% when active or done), the track node, the active state chip and the actor name in the event log. Doctor Coral is also the flagged-reading colour on the member panel (with `#FFB0A8` for its caption), the "urgent" status dot and the irregular ECG trace. Insurer Blue is the checked state of the consent toggle and the end colour of the condition bars (`linear-gradient(90deg, brand-mint, insurer-blue)`). The member (Amani) uses Foreground as her ink.

### Neutral
- **Ink Ground** (`ink-ground`): page background and the fill of track nodes at rest; also the 2px ring around the pulse.
- **Ink Ground 2** (`ink-ground-2`): reserved deeper ground; declared but unused on the shipped surface.
- **Panel** (`panel`): base surface of every panel, tile, segmented control, top-bar hover and sticky table header.
- **Panel Raised** (`panel-raised`): top of the panel gradient, avatar fill, button hover, done-state chip and the empty bar track.
- **Hairline** (`hairline`): every border, divider, tile gap and the top-bar rule.
- **Hairline Strong** (`hairline-strong`): borders on chips, kbd keys, avatar and nodes; track rail; toggle off-state; the redaction block.
- **Foreground** (`fg`): primary text and the member's ink.
- **Muted** (`muted`): secondary text, labels, units, nav links at rest, table row heads; the ECG gridlines at `rgba(147,167,175,.12)`.
- **Dim** (`dim`): the "No" icon only; the quietest ink.

### Named Rules
**The Lamp Rule.** Amber marks the live signal and the presenter's controls, nothing else. It never colours a KPI, a heading, a bar or decoration. If amber appears, something is happening now or is about to be pressed.

**The One Ink Per Actor Rule.** Each actor has exactly one colour and it is applied through `--c`: mark, top rule, node, active chip, log name. Actor inks never fill a panel; the active stage only tints its border (`color-mix` 55% with hairline) and background (6% with panel).

**The Mint Is Brand Rule.** Mint carries the brand and the AI, and it is the only accent allowed on numbers at rest (the KPIs). Flagged readings turn coral; nothing else recolours a figure.

## Typography

**Display Font:** Inter, variable width and weight (with ui-sans-serif, system-ui fallback)
**Body Font:** Inter (same family, width 100%)
**Label/Mono Font:** Inter (tabular numerals) 400-600 (with ui-monospace, SF Mono, Menlo fallback)

**Character:** Headings are Inter set wide (font-stretch 110%, up to 112% in the logotype), heavy (700-800) and tight (-0.03em), which gives the console a broad, confident voice. Every figure and timestamp is Inter (tabular numerals) with tabular numerals and slightly tightened tracking, so values read as instrument output rather than prose.

### Hierarchy
- **Display** (700, `clamp(32px, 3.6vw, 46px)`, 1.1, -0.03em, width 110%): section headings ("What the insurer sees", "Plans"). Each carries a 36x3px mint mark above it.
- **Headline** (700, `clamp(28px, 2.7vw, 36px)`, 1.1, -0.03em, width 110%): the hero title. Smaller than Display on purpose; the hero's room goes to the live panels.
- **Title** (700, 15px, 1.1, 0em, width 100%): stage titles, panel h3s, the event log head (13px). Headings inside panels drop back to normal width and tracking. The plan name is the one larger title (20px, width 105%); the logotype is 19px/800/112%.
- **Lede** (400, 17px, 1.55, muted, max 58ch): section intro paragraph set beside the Display heading. The hero lede is 15px, max 62ch.
- **Body** (400, 15px, 1.5): stage values, log lines, list copy; 14px for table cells, bar rows, plan features and sub-captions; 13px for fine print, legend, footer and chip text.
- **Label** (500, 12px, 0.02em, muted): metric captions and KPI names, sentence case.
- **Label Key** (500, 12px, 0.03em, uppercase, muted): the key in a key/value pair inside a stage card. Uppercase is permitted only here, directly above the value it names.
- **Reading Hero** (Inter (tabular numerals) 500, 56px, 1, -0.06em): the live heart rate, with its unit in 15px Inter muted.
- **Reading KPI** (Inter (tabular numerals) 500, 34px, 1.2, -0.04em, mint): insurer KPI figures.
- **Reading Metric** (Inter (tabular numerals) 500, 22px, 1.25): the four member metrics; the plan price is 26px/-0.03em.
- **Reading Inline** (Inter (tabular numerals) 400, 15px): numeric values inside stage key/value pairs and the cost row of the comparison.
- **Timestamp** (Inter (tabular numerals) 400, 14px, muted): event-log times; kbd keys are 11px with a 4px-radius hairline-strong border.

### Named Rules
**The Mono Number Rule.** Any number a presenter might read aloud (a reading, a count, a price, a time) is set in Inter (tabular numerals) with `font-variant-numeric: tabular-nums`. Units and captions beside it return to Inter.

**The Wide Heading Rule.** Page- and section-level headings are width 110%, weight 700, tracking -0.03em. Headings inside a panel are width 100%, tracking 0, so panels never shout over the page.

## Layout

A single centred column, max-width 1280px, with 24px gutters (grown by the safe-area insets). The top bar is sticky (56px min height, blurred `rgba(10,17,20,.86)`) with a 2px amber progress line fixed above it.

The hero is the first viewport: a two-column stage grid (`minmax(0,330px) minmax(0,1fr)`, 16px gap) with the member panel left and the pipeline right. The pipeline is four equal stage columns (12px gap, min-height 240px) under a 2px track whose rail runs from 12.5% to 87.5% so each node centres on its column; the event log sits beneath. On viewports at least 1001px wide and at most 800px tall the stage grid is capped to `calc(100vh - 180px)` and the log takes the remaining height, so the whole demo stays inside 1280x720.

Sections below use a two-column head (heading left, lede right, aligned to the baseline, 48px column gap) with 88px of top padding and 28px before the content. Content grids are 16px-gapped: a five-up KPI strip, a 1.4fr/1fr insurer grid, a two-column why/questions grid and a two-column plan grid. Tile sets (metrics, KPIs) are hairline grids: a 1px gap over the hairline colour inside one bordered, rounded container.

Breakpoints, from the build: 1000px (stage grid stacks, track hides, stages go two-up), 980px (KPIs two-up with the last tile full width), 900px (insurer and why grids stack), 820px (section head stacks), 720px (plans stack, live chip hides), 600px (stages one-up, scenario buttons fill the width and drop their kbd hints, log collapses to two columns), 480px (bar label column narrows to 120px). The comparison table keeps a 1040px min-width inside a horizontally scrolling panel with a sticky first column.

Spacing rhythm: 1px hairline, 8, 12, 16, 22, 28 and 88px. Panel padding is 20x22px in sections, 18px on the member panel and 13x14px on stage cards.

## Elevation & Depth

Hybrid, and quiet. Depth comes first from tone: the ground is the darkest value, panels sit one step up with a vertical gradient from Panel Raised to Panel over the top 38%, and hover or done states step up again to Panel Raised. Every panel then carries a lit top edge and one soft, long shadow. The top bar floats with a backdrop blur. There are no glows: no coloured box-shadows anywhere, and the only luminous element is the faint mint radial wash behind the hero (`radial-gradient(1100px 560px at 85% -8%, rgba(78,225,181,.09), transparent 62%)`).

### Shadow Vocabulary
- **Panel lift** (`box-shadow: inset 0 1px 0 rgba(255,255,255,.035), 0 24px 48px -36px rgba(0,0,0,.8)`): every `.panel` and the comparison wrapper; the inset line is the lit edge, the outer shadow pools beneath.
- **Strip lift** (`box-shadow: 0 24px 48px -36px rgba(0,0,0,.8)`): the KPI strip, whose tiles are already separated by hairlines and need no inset edge.
- **Top rule** (`box-shadow: inset 0 2px 0 var(--signal)`): the Moyo column header in the comparison; a rule drawn as an inset shadow, not elevation.

### Named Rules
**The Lit-Edge Rule.** A raised surface shows a 1px highlight on its top edge and a shadow below. Depth is never conveyed by a coloured glow or a brighter border alone.

**The Resting State Rule.** Every animated element (track fill, pulse, rising values, counting KPIs, growing bars, scroll reveals) has a complete, legible state with motion disabled; reduced motion shows the finished state immediately and slows the ECG tick.

## Shapes

Softly rounded rectangles on a strict grid. Panels and tile containers use 12px; fields and controls (segmented control, reset button, metric grid, cuff prompt) use 10px; the buttons inside the segmented control and nav links use 7px; the focus ring 6px; kbd keys 4px; the redaction block 3px; the actor mark and section mark 2px. Chips, state badges, the live indicator, the toggle, bars and the provenance tag are full pills (99px). Nodes, the pulse, the avatar, status dots and the toggle knob are circles.

Borders are always 1px hairlines; the only 2px strokes are the active stage's top rule, the track, the progress line and the pulse's ground-coloured ring. The actor mark is an 8px square, the status dot an 8px circle, the live dot 7px. Icons are inline SVG at 14-16px (22-28px for the shield) drawn with 1.4-1.8px round-capped strokes.

## Components

### Buttons
Controls are quiet until pressed; the pressed scenario is the one amber fill on the page.
- **Shape:** 7px inside the segmented control, 10px for the standalone reset button; the control itself is a 10px panel with 3px inner padding and a hairline border.
- **Scenario (segmented):** transparent, muted 14px/500 text with a mono kbd hint, 7x12px padding. Hover: Panel Raised fill, foreground text. Selected (`aria-pressed="true"`): Signal Amber fill with Signal Ink text and kbd. Disabled siblings while a scenario runs: 45% opacity. Transitions 150ms.
- **Secondary (reset):** 40px tall, Panel fill, hairline border, muted text with a 15px stroke icon; hover lifts text to foreground and border to Hairline Strong.
- **Cuff prompt:** a full-width amber-bordered action (`rgba(245,165,36,.1)` fill, 10px radius, 10x12px padding) with an amber bold lead, muted explanation and a kbd "C"; hover deepens the tint to `.16`. It appears only while a scenario is paused.
- **Focus:** 2px Signal Amber outline, 2px offset, 6px radius, on every focusable element.

### Chips
- **State badge:** 11px/500, 2x8px padding, pill, Hairline Strong border, muted text. Active stage: border and text in the actor ink. Done stage: foreground text on Panel Raised.
- **Pill (plan, live):** 12px/500, 3x9px (4x10px with a 7px mint dot for the live indicator), pill, hairline border, muted text.
- **Provenance tag:** 12px/500 amber text on a 40% amber pill border, placed under a section heading to label illustrative data.
- **kbd:** Inter (tabular numerals) 11px, 3x5px, 4px radius, Hairline Strong border, muted.

### Cards / Containers
- **Corner Style:** 12px.
- **Background:** `linear-gradient(180deg, panel-raised, panel 38%)` with a 1px hairline border.
- **Shadow Strategy:** Panel lift (see Elevation).
- **Border:** hairline; Moyo Plus uses a 45% mint border; the active stage uses `color-mix(in oklab, actor 55%, hairline)`.
- **Internal Padding:** 20x22px (section panels), 18px (member panel), 13x14px (stage cards), 22px (plan cards).
- **Lists inside panels** separate items with hairline rules and 12px vertical padding, no bullets.

### Inputs / Fields
- **Consent toggle:** 34x20px pill, Hairline Strong track, 14px foreground knob at 3px inset; checked turns the track Insurer Blue and springs the knob 14px right (`cubic-bezier(.3,1.4,.5,1)` 200ms). Its label is 13px with a foreground bold line and a muted explanation; it sits at the bottom of the insurer stage above a hairline.
- **Focus:** the global amber ring.

### Navigation
- **Top bar:** sticky, blurred ink (`rgba(10,17,20,.86)`, `backdrop-filter: saturate(140%) blur(10px)`), hairline bottom rule, 56px min height. Logotype 19px/800 width 112% beside the amber-shield mark and a muted 13px tagline. Links 14px/500 muted with 6x10px padding and 7px radius; hover and the active section (observed by scroll position) show foreground text on a Panel fill. A 2px amber progress line tracks scroll at the very top. Under 720px the live chip hides and the nav wraps beneath the logotype.

### Live Pipeline (signature)
The track is a 2px Hairline Strong rail with four 10px nodes (ground fill, Hairline Strong ring) at 0/33/66/100%. As a scenario runs, an amber fill grows along the rail and a 14px amber pulse (2px ground ring) travels to the active node (`cubic-bezier(.16,1,.3,1)` 700ms); passed nodes fill with their actor ink. Below, each stage card shows its title with an 8px actor square, a state badge, a muted one-line role, and either an empty-state sentence or a key/value list (uppercase 12px keys, 15px values, numeric values in mono) whose rows rise into place 60ms apart. The insurer stage redacts member fields with a Hairline Strong block until consent is on. The track hides under 1000px; stages reflow two-up then one-up.

### Event Log (signature)
A panel with a 13px bold head and a muted hint on the right. Rows are a three-column grid (52px mono time, 92px actor name in its ink, text), 8x14px padding, hairline rules, newest first, rising in over 450ms. The list scrolls at 120px, or fills the remaining height under the 720px height cap.

### Live Vitals (signature)
The member panel stacks identity (34px avatar, name, plan pill), the 56px mono heart rate with a 15px unit, a 64px canvas ECG (Trace Mint 1.8px stroke over two 12% gridlines with a mint-to-transparent area fill, coral when irregular), a 2x2 hairline grid of 22px mono metrics with 12px captions (flagged metrics turn coral), and a status line led by an 8px dot (mint ok, amber watch, coral urgent).

### KPI Strip and Bars
Five hairline-separated tiles in one 12px container: 12px label, 34px mint mono figure that counts up over 1.1s when scrolled into view, 13px muted caption. Condition bars are 8px pills on a Panel Raised track filled with a mint-to-insurer-blue gradient that grows over 1s; label 170px left, mono count right.

## Do's and Don'ts

### Do:
- **Do** set every number and timestamp in Inter (tabular numerals) with tabular numerals, and return units and captions to Inter.
- **Do** colour an actor through `--c` only: mark, top rule, node, active chip and log name; tint its active stage with `color-mix` at 55% (border) and 6% (background).
- **Do** keep amber for the live signal and the presenter's controls: pulse, track fill, selected scenario, cuff prompt, progress line, provenance tag, focus ring.
- **Do** build tile sets as hairline grids (1px gap over the hairline colour inside one 12px bordered container) rather than nested bordered boxes.
- **Do** give every panel the lit edge and the long soft shadow (`inset 0 1px 0 rgba(255,255,255,.035), 0 24px 48px -36px rgba(0,0,0,.8)`).
- **Do** ship every animation with a complete resting state and honour `prefers-reduced-motion` by showing it immediately.
- **Do** keep the whole live demo inside 1280x720 using the height cap, and keep demo type at 14px or larger.
- **Do** draw icons as inline SVG strokes (1.4-1.8px, round caps) at 14-16px.

### Don't:
- **Don't** bring back paper, notebook, handwriting, stamp or ruled-line metaphors; the world is a console.
- **Don't** add glows: no coloured box-shadows, no blurred halos, no gradient-filled text. Gradients exist only as the panel's top tint, the hero wash and the condition bar fill.
- **Don't** use amber on KPIs, headings, bars or decoration, and don't use mint for the live pulse.
- **Don't** fill a stage or panel with an actor's ink; actor colours are marks and rules, never surfaces.
- **Don't** set uppercase text outside the key of a key/value pair; there are no kickers or eyebrows above headings, only the mint mark.
- **Don't** widen or tighten headings inside panels; width 110% and -0.03em belong to page and section headings only.
- **Don't** introduce a second body face or a system display face; Inter and Inter (tabular numerals) are the whole palette.
- **Don't** add a light theme; the system is dark only (`color-scheme: dark`).
