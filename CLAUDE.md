# Debriefer.io Site — Claude Code Context

## What This Is
Public landing page for debriefer.io — an AI service that turns email archives into interactive project narratives.

## Key Rules
- **This repo is PUBLIC.** Zero real names, places, institutions, or healthcare terms anywhere.
- De-identified sample uses trucking/fleet logistics theme with animal characters
- Years shifted -3 from real dates
- Git history was scrubbed clean on Apr 13 — don't reference pre-scrub commits
- Planning docs are in meta-framework repo, NOT here

## Brand
- Mascot: Goose the Goose (emerald green SVG face)
- Colors: dark (#0a0f0d) + emerald green (#10b981). "debriefer" white, ".io" green
- Tagline: "The story is in your inbox. We bring it out."
- Price: $199/project

## Infrastructure
- Hosting: GitHub Pages with HTTPS enforced
- Domain: debriefer.io (Porkbun)
- Email: Brevo (free tier), form URL is sibforms.com hosted
- Pixel: Meta Pixel 1253681319867385 (shared with Counselors)
- ?qa URL parameter disables animations for coworker QA testing

## Files
- index.html — landing page with parallax email fragments
- sample.html — de-identified sample timeline with animal characters
- terms.html — terms of use
- ads/ — 3 ad creative HTML files
- logo.svg, favicon.svg — Goose
- welcome-email.html — Brevo email template source

## Animal Character Spec
See meta-framework/docs/animal-character-spec.md for canonical SVG proportions.
