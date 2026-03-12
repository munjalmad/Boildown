# Boildown 🔥

> Paste a meeting transcript. Get clean requirements. Build on them every session.

Built by a PM who was tired of spending 45 minutes after every meeting turning rambling transcripts into something actionable.

## What it does

Boildown takes your raw Webex (or any) meeting transcript, strips the jargon, filler, and "can everyone hear me" noise — and extracts a living requirements doc that gets smarter with every meeting.

- **Meeting 1** → requirements created
- **Meeting 2** → existing requirements updated, new ones added, resolved ones closed
- **Meeting 10** → one clean doc that reflects every decision ever made

No more 12 separate meeting summaries that nobody reads.

## Features

- Paste any transcript — Webex, Zoom, Otter.ai, rough notes — all work
- AI strips jargon and extracts plain-English requirements
- Tags each requirement as **New**, **Updated**, or **Resolved**
- Categorises by Feature, UX, Technical, Business, or Data
- Pulls out next steps with owner names
- Living doc — persists across sessions, builds on itself
- Mark requirements resolved or reopen them manually
- Export a clean markdown doc anytime
- Zero backend, zero installs — one HTML file

## How to use

1. Download `boildown.html`
2. Open it in Chrome
3. Paste your meeting transcript
4. Hit **Process Transcript**
5. Next meeting — paste again, it remembers everything

## Tech

- Vanilla HTML, CSS, JavaScript — no frameworks
- Claude API (Sonnet) for transcript intelligence
- localStorage for session persistence

## Why I built this

As a PM I run a lot of meetings. The real work isn't the meeting — it's the 45 minutes afterward turning notes into something a team can act on. Boildown cuts that to 30 seconds.

This is part of a broader experiment in vibe coding — building real PM tools using AI, without writing a single line of code by hand.

---

Built by [Madhur Munjal](https://ca.linkedin.com/in/madhurmunjal) · Principal PM · AI Product Builder · [Invoice Builder →](https://github.com/madhurmunjal/invoice-creator)
