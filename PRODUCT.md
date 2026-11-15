# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

The primary audience is the GENE 225 teaching team and class panel at Stanford (Fall 2026), who grade the project at the Week 10 presentations alongside a written paper. They need to grasp the business model and believe the product is real within a few minutes.

The product it depicts serves affluent Kenyans, starting in Nairobi, who pay for proactive health oversight. Secondary users inside the product are Mlinzi's licensed Kenyan nurses (working a flag queue on shift), partner-hospital doctors (receiving escalations), and private insurers such as Jubilee Health (viewing pooled cohort data and opted-in members).

## Product Purpose

Mlinzi (Swahili for "guardian") is a startup concept: a proprietary health wearable plus a remote care service. The band measures; an AI flags anomalies around the clock; a licensed Kenyan nurse calls the member; a doctor at a partner hospital in Nairobi handles escalation.

The website is a clickable product demo, not a marketing site. Success means the panel watches one scenario play out and understands, without extra explanation, who sees what at each step: member, nurse, doctor, insurer.

## Positioning

Other wearables give people numbers. Mlinzi gives them a Kenyan nurse and doctor who act on those numbers; the band is the entry ticket to the care team. Owning the device keeps the data rights (no HealthKit sharing limits), and insurers' group-risk models trained on Mlinzi data create switching costs.

## Operating Context

- Presented live at Week 10: one presenter clicks through on a projector while talking, so the demo must read from the back of a room and run on cue.
- Deployed at https://mlinzi-seven.vercel.app from the `awesome4ce/mlinzi` repo; Ethan Seung and Steven Diaz both edit it.
- Submitted alongside a written paper that reuses the competitive analysis.

## Capabilities and Constraints

- Single static `index.html` (HTML, CSS, vanilla JS), no build step, deployed by Vercel on push to `main`.
- Live scenarios are binding: rising blood pressure, irregular heart rhythm, and poor sleep/stress. Running one updates the member app, the care team console, and the insurer view together. The BP scenario pauses for a home-cuff confirmation before the nurse acts.
- Blood pressure from the band is a trend only; clinical decisions use the home BP cuff in the kit and a doctor. The band makes no diagnostic claims.
- Insurers see group-level, de-identified data. Members may opt in to individual sharing, used only for care pre-approval and discounts, never to raise an individual's premium or deny cover (Kenya Data Protection Act 2019 treats health data as sensitive).
- Pricing (illustrative): Guardian KES 3,900/month (band, cuff, AI, nurse calls); Guardian Plus KES 9,500/month (adds doctor escalation, quarterly check-up, two family members). Insurer discount up to 15% with record sharing.
- Expansion path: Kenya first, then other African markets, then a cheaper middle-class tier as data lowers costs.
- Not binding: the current four-tab structure, the shield logo, and the current visual style.

## Brand Commitments

- Name: Mlinzi, meaning "guardian" in Swahili.

## Evidence on Hand

- No real users, pilot data, testimonials, partners, or clinical results exist. All people, readings, and pilot figures are fictional and must stay labelled as illustrative.
- Jubilee Health, Britam, Apple Watch, Oura, Whoop, Xiaomi, Huawei, Discovery Vitality, and Withings are real companies named only for comparison or as hypothetical partners; do not imply endorsement or partnership.
- Competitor details in the comparison table must be checked before the paper is published.
- Validation in the paper relies on comparables (Discovery Vitality, Oura/Whoop, concierge medicine) plus a designed 6-month pilot of about 100 users with one partner hospital.

## Product Principles

1. Show the care, not the gadget. Human follow-up is the product; sensor numbers are supporting evidence.
2. Every flag has an owner. Each scenario step names who acts (AI, member, nurse, doctor, insurer) and what they see.
3. Privacy is visible. Where insurer data appears, the limit on its use appears next to it.
4. Never overclaim. Illustrative data is labelled, and the band never diagnoses.
5. Legible at a distance. Anything shown during the live demo must read on a classroom projector.
