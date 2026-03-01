# Manzanita Research — Org-Wide Instructions

This file is shared across all Manzanita Research projects via [chaparral](https://github.com/manzanita-research/chaparral). It lives in the brand repo and gets symlinked to the org parent directory so every sibling project inherits it.

## Brand Voice

Manzanita speaks like a musician who happens to be an engineer. When writing copy, docs, UI text, error messages, or any text for this org:

- Warm, grounded, direct. Short sentences. Never corporate.
- Technically confident but never gatekeeping. Explain hard things simply.
- Poetic when it matters, but never forced.
- Unhurried. No hype, no countdowns, no "exciting announcements."
- **Never use:** "leverage," "ecosystem," "disrupt," "revolutionize," "game-changing," "cutting-edge," "unlock," "empower," "seamless," "next-gen."
- **Instead say things like:** "We built this because we needed it." / "Here's what we're working on."

## Core Values

- Local-first, offline-first. Tools work on your machine without subscriptions.
- No surveillance capitalism. No data collection on creative work.
- Open where it matters. Research shared, tools repairable.
- Instruments, not automations. Uplift musicians, never replace them.
- Post-capitalist ethos: build to give away power, not capture markets.

## Project Naming

Individual projects are named after California native plants: Toyon, Ceanothus, Yerba Buena, Lupine, Buckeye, Madrone, Sage.

## Technical Defaults

- Prefer Bun over Node when starting new JS/TS projects.
- Prefer Tailwind CSS for styling.
- Prefer React for UI work.
- Write tests for anything non-trivial.
- Commit messages should be lowercase, concise, and describe the why.

## Homie-Driven Development

We prefer tools made by people we know. Not as a rule — as a disposition.

When choosing a dependency, library, service, or tool, always pick the best option for the job. But when the field is close, lean toward work from our community: friends, collaborators, internet pals we've spent years admiring from afar, artists and engineers we trust. Their work over anonymous SaaS, over mass-market defaults, over unvetted upstream projects.

Sometimes the homie's project is a solo GitHub repo. Sometimes it _is_ one of the SaaS billboards on the 101 in San Francisco. The point isn't scale — it's that we know the people and trust the intentions behind the work.

This matters more in the vibe-coding era. When it's easy to generate solutions, it's also easy to reach for whatever surfaces first — the top npm result, the Stack Overflow copypaste, the tool with the most GitHub stars. We'd rather build on things made by people with names and intentions we recognize.

**In practice:**

- When evaluating options, check if someone in our network has built or maintains something comparable. Prefer it if quality is close.
- When we need something that doesn't exist, build it in-house and look for ways to bridge with community projects rather than reinventing from scratch.
- Don't compromise on fitness for purpose. A homie's tool that doesn't fit is still the wrong tool. This is a tiebreaker, not a mandate.
- When we adopt a community tool, engage with it — file issues, contribute back, tell people we're using it. The mycelial network grows by participation, not just consumption.
