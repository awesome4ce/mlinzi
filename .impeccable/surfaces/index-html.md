---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface: Moyo demo (index.html)

Mode: Experience. The demo is the work; it is clicked through live on a classroom projector at Week 10.
Audience and job: GENE 225 panel must remember the handoff, one health event passing band, AI, nurse, doctor, insurer, each seeing their own slice. Must not feel too busy to present. Live scenarios (BP with cuff pause, rhythm, sleep/stress) are binding; structure is open.

## Direction contract

THESIS: Moyo as a live care pipeline: one signal visibly travels from the band through AI, nurse, doctor and insurer, and every stage's own view updates in the same screen. Refuses both the phone-mockup-beside-dashboard default and any paper metaphor.

OWN-WORLD: Dark, warm and data-forward, built from one coral "heart" hue (#FF5C4D, peach tint #FF8A6B) on a warm near-black ground. Amber means watch, pink (#FF4D8D) means urgent; everything else is neutral. Roles are a tonal ramp of the brand and stages are numbered 01-04. Hanken Grotesk for all text and tabular numbers, IBM Plex Mono only for timestamps, keys and eyebrows. Boxes only for genuinely separate views (stage cards, event log, phone); everything else is separated by spacing and hairlines. Text never below 4.5:1. See DESIGN.md.

STORY: The presenter presses 1, 2 or 3; the panel watches the pulse move stage to stage while each stage shows exactly what that actor sees, the insurer stage redacted unless Amani consents. Below: the insurer's pooled numbers, the competitive comparison, the moat, and the two plans.

FIRST VIEWPORT: Scenario switcher top right of the hero. Left: Amani's live vitals panel (large heart-rate number, live waveform, four metrics, status). Right: four stage columns joined by a connector the pulse travels along. Under them, a monospaced event log. All of it inside 1280x720.

FORM: seed: none (pinned). User's words for the world: "this is supposed to be a tech, not a fucking notebook entry app", "make things look sleak and mdoern", "its own identity but be data forward", theme "Dark". Confirmed answers pinning the first-surface experience: success is "the panel remembers the handoff, band → AI → nurse → doctor → insurer, each seeing their own slice"; "three live scenarios binding (rising BP with cuff pause, irregular rhythm, sleep/stress), each run must update every view"; feels wrong if "too busy to present".

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

Signature interaction: keyboard-driven presenting (1, 2, 3 run scenarios; R resets; C takes the cuff reading), with the coral pulse travelling the connector into each stage as it activates.
