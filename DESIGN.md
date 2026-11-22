---
name: Moyo
description: A dark, warm care console in one coral "heart" hue, where a single health event travels from the band through AI, nurse, doctor and insurer.
colors:
  ground: "#0B0A0A"
  ground-2: "#100F0E"
  panel: "#141312"
  panel-raised: "#1B1918"
  hairline: "rgba(255,245,240,.07)"
  hairline-strong: "rgba(255,245,240,.13)"
  fg: "#F5F2EF"
  muted: "#B8B2AC"
  dim: "#8E8882"
  brand-coral: "#FF5C4D"
  brand-peach: "#FF8A6B"
  brand-soft: "rgba(255,92,77,.12)"
  brand-line: "rgba(255,92,77,.42)"
  brand-ink: "#1A0806"
  warn-amber: "#F5B86A"
  urgent-pink: "#FF4D8D"
  urgent-soft: "rgba(255,77,141,.14)"
  urgent-line: "rgba(255,77,141,.5)"
  role-ai: "#FF5C4D"
  role-nurse: "#FF8A6B"
  role-doctor: "#FFB59A"
  role-insurer: "#F2DDD2"
typography:
  display:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(32px, 4vw, 52px)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.045em"
  headline:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(28px, 2.9vw, 40px)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.045em"
  subhead:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.025em"
  stat-name:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.015em"
  body:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
  lede:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0em"
  label:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0em"
  eyebrow:
    fontFamily: "IBM Plex Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0.04em"
  reading-hero:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "46px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "-0.06em"
  reading-kpi:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "44px"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-0.045em"
  reading-metric:
    fontFamily: "Hanken Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: "-0.03em"
  timestamp:
    fontFamily: "IBM Plex Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "12.5px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
rounded:
  redact: "4px"
  key: "5px"
  chip-step: "8px"
  logo: "9px"
  control: "10px"
  field: "14px"
  metric: "16px"
  panel: "18px"
  hr-card: "20px"
  screen: "38px"
  phone: "46px"
  pill: "99px"
spacing:
  hairline: "1px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "40px"
  column-gap: "72px"
  block-gap: "80px"
  gutter: "24px"
  section: "112px"
components:
  stage-card:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.fg}"
    rounded: "{rounded.panel}"
    padding: "14px 15px 13px"
  kpi:
    backgroundColor: "transparent"
    textColor: "{colors.fg}"
    typography: "{typography.stat-name}"
    padding: "18px 0 0"
  button-scenario:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.control}"
    padding: "8px 13px"
  button-scenario-selected:
    backgroundColor: "{colors.fg}"
    textColor: "#141010"
  button-secondary:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.muted}"
    rounded: "{rounded.field}"
    padding: "0 14px"
    height: "42px"
  cuff-prompt:
    backgroundColor: "{colors.brand-soft}"
    textColor: "{colors.fg}"
    rounded: "{rounded.metric}"
    padding: "10px 12px"
  chip-state:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
    padding: "3px 9px"
  chip-state-urgent:
    backgroundColor: "{colors.urgent-soft}"
    textColor: "{colors.urgent-pink}"
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
  nav-link-active:
    backgroundColor: "{colors.panel-raised}"
    textColor: "{colors.fg}"
  kbd-key:
    backgroundColor: "transparent"
    textColor: "{colors.dim}"
    rounded: "{rounded.key}"
    padding: "3px 5px"
  toggle:
    backgroundColor: "{colors.hairline-strong}"
    rounded: "{rounded.pill}"
    width: "36px"
    height: "22px"
  toggle-on:
    backgroundColor: "{colors.brand-coral}"
---

<!-- Recorded from the shipped index.html on 2026-11-22. Replaces the "Guardian's Console" system (blue-green ink, amber signal, five actor hues, Archivo + Azeret Mono) entirely. -->

# Design System: Moyo

## Overview

**Creative North Star: "One Heart, One Signal"**

Moyo means "heart" in Swahili, so the whole page is built from one warm coral hue on a warm near-black ground. Colour is never decoration: coral marks the brand and the live event, amber means "watch", hot pink means "urgent", and everything else is neutral. The page reads like a calm clinical console that lights up only where something is happening.

The demo is presented on a classroom projector, so legibility beats subtlety: no text below 4.5:1, no meaning carried by colour alone (stages are also numbered 01–04), and the statistic names on the insurer view are as prominent as the numbers.

Key characteristics:

- One brand hue (coral #FF5C4D) with a peach tint; roles are a tonal ramp of it, not separate hues
- Two semantic colours only: amber for watch, pink for urgent
- Hanken Grotesk for everything readable; IBM Plex Mono only for timestamps, keys and eyebrows
- Boxes only where a box means "a separate screen or view"; everything else is separated by spacing and hairlines

## Colors

### Primary

- **Brand Coral** (`brand-coral`, #FF5C4D): the logo tile, the heart-rate trace, the pipeline fill and nodes, the active stage, the first KPI's top rule, the Plus plan's top rule, flagged metrics, the toggle when on, check icons, eyebrow dots.
- **Brand Peach** (`brand-peach`, #FF8A6B): the lighter end of the brand. KPI figures, eyebrow text, the Moyo column header in the comparison, the end of the pipeline gradient.
- **Brand Soft / Line** (12% fill, 42% border): tints for the active stage, cuff prompt and flagged metrics.

### Semantic

- **Watch Amber** (`warn-amber`, #F5B86A): the status dot when a reading needs attention, and the "Partly" icon in the comparison. Nothing else.
- **Urgent Pink** (`urgent-pink`, #FF4D8D): only the urgent state. In the irregular-rhythm scenario it colours the AI and nurse stage chips, the active stage, the flagged HRV metric, the status dot and the heart-rate trace. Its hue is deliberately away from coral so an alarm never looks like branding.

### Roles

Roles are a ramp from coral toward off-white: AI #FF5C4D, nurse #FF8A6B, doctor #FFB59A, insurer #F2DDD2. They appear only as the small dot before each actor's name in the event log. Stages are told apart by their number chip (01–04), not by colour.

### Neutral

- **Ground** #0B0A0A, **Ground 2** #100F0E (phone screen), **Panel** #141312, **Panel Raised** #1B1918.
- **Hairline** 7% and **Hairline Strong** 13% warm white.
- **Foreground** #F5F2EF; **Muted** #B8B2AC for secondary text; **Dim** #8E8882 for captions, timestamps and table subtitles. Dim is the floor: it is at least 5:1 on every surface.

### Named Rules

- **The One Hue Rule.** A new accent needs a meaning. If it is not brand, watch or urgent, it is a neutral.
- **The Projector Floor.** No text below 4.5:1 on its surface. Dark ink (#1A0806) on coral fills, never white.

## Typography

**Interface:** Hanken Grotesk 400–700 (fallback ui-sans-serif, system-ui)
**Mono:** IBM Plex Mono 400–500, used only for timestamps, kbd keys, eyebrows and the log hint

Headings are semibold (600) and tight (−0.045em at display size). Every number uses Hanken Grotesk with `font-variant-numeric: tabular-nums` so live readings do not jitter.

### Hierarchy

- **Display** (600, clamp 32–52px): section headings.
- **Headline** (600, clamp 28–40px): the hero line.
- **Subhead** (600, 20px): column headings inside sections ("Conditions caught early", "Why it's hard to copy").
- **Stat name** (600, 18px, foreground): KPI names on the insurer view. They are as important as the figures.
- **Reading KPI** (500, 44px, peach): KPI figures.
- **Reading Hero** (500, 46px): the live heart rate.
- **Title** (600, 15px): stage names.
- **Body** 15px, **Lede** 17px muted, **Label** 12px muted.
- **Eyebrow** (Plex Mono 12px, uppercase, peach, with a coral dot): the small label above each section heading.

## Layout

- Max width 1280px, 24px gutters, sections 112px apart.
- The first viewport (hero, phone, four stages, event log) must fit 1280×720. Below 800px tall at desktop width, the grid is height-capped and the log absorbs the slack.
- Below the demo, content columns are separated by space (72px column gap, 80px between blocks), not by boxes.

### The Box Rule

A panel with a fill and border means "this is a separate screen or actor's view". Only these get one: the four stage cards, the event log, the phone and the tiles inside the phone. KPIs, the insurer columns, "Why it's hard to copy", "Questions we expect" and the plans are unboxed. KPIs and plans sit under a single top hairline (coral for the emphasised one); the comparison table has rules between rows but no outer frame; the insurer contract rule uses a 2px coral left rule.

## Elevation & Depth

Surfaces are flat with a 4% inner top highlight. The phone has a soft dark drop shadow. The current build also uses coral glows on the active stage, pipeline fill, pulse and logo tile, a coral gradient on "heartbeat", and a faint coral wash at the top of the page. Impeccable flags these, and the earlier brief banned them; they are candidates to remove.

## Shapes

Radii grow with the size of the thing: keys 5px, step chips 8px, controls 10px, fields 14px, phone tiles 16px, panels 18px, the heart-rate card 20px, the phone 46px. Chips, nav links and toggles are full pills.

## Components

- **Scenario switcher:** a segmented control. The selected scenario becomes a light pill (foreground fill, dark text); the others dim while it runs.
- **Stage card:** numbered chip, name, state chip, one-line role, then key/value details. Active: coral tint and border, coral chip. Done: white chip. Urgent: pink chip, pink state, pink tint.
- **Pipeline:** a hairline track joining the four stages; it fills coral and a pulse travels to each stage as it activates.
- **Event log:** mono timestamp, actor name with a role-ramp dot, message. The newest entry has a short coral wash.
- **Phone:** status bar, member header with heart logo, heart-rate card with live trace, four metric tiles, status line, cuff prompt (BP scenario only), tab bar.
- **KPI:** stat name (18px, foreground) above the figure (44px, peach) above a muted caption, all under a top hairline.
- **Comparison table:** sticky first column, tinted Moyo column with a coral top rule, row hover.
- **Plan:** name, price, one-line description, hairline, check list. Moyo Plus has a coral top rule and a "Family" badge.
- **Toggle:** 36×22 pill; coral when on.

## Motion

Scroll reveals (fade, rise, slight blur), counting KPIs, growing bars, a scroll progress line, and stage detail rows that rise in sequence. Everything has a visible resting state under `prefers-reduced-motion`.

## Do's and Don'ts

### Do

- Use coral for the brand and the live event, amber for watch, pink for urgent, and nothing else.
- Keep every text colour at or above Dim (#8E8882).
- Make the name of a statistic at least as prominent as its value.
- Separate content with space and hairlines unless it is genuinely a separate view.
- Set every number in tabular numerals.

### Don't

- Don't introduce a new hue per actor or per section.
- Don't put white text on coral.
- Don't box a group of items just to group them.
- Don't use Inter, Geist, Archivo or another default font; Hanken Grotesk and IBM Plex Mono are the whole set.
- Don't bring back paper, notebook, handwriting or stamp metaphors, or a light theme.
