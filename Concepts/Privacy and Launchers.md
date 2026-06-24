---
title: Privacy and Launchers
tags: [concept, theme, privacy]
created: 2026-06-24
---

# Privacy and Launchers

A launcher is uniquely positioned to observe behaviour: it sees **every app you have, how often you open each, what you search, and (with permissions) your widgets' data**. This makes trust a real consideration.

## What a launcher can see
- Full list of installed apps (which itself is sensitive — reveals banking, health, dating, political, religious apps).
- App launch frequency and timing (usage patterns).
- Search queries typed into the launcher.
- Whatever permissions it requests: location (weather/At a Glance), contacts (search), notification access (badges, feeds), calendar.

## Risk vectors
- **Telemetry / analytics** in closed-source launchers — what's collected and sent.
- **Feeds and recommendations** that profile you to serve content/ads (more typical in [[OEM Launchers]] and vendor launchers).
- **Acquisition risk** — a trusted launcher changing hands can change its data practices. (The [[Nova Launcher]] / Branch acquisition raised exactly this concern, since Branch is an attribution/analytics company.)

## Why FOSS launchers appeal to privacy-conscious users
Open source means the data behaviour is **auditable**. No hidden telemetry; community scrutiny.
- [[KISS Launcher]] — local, no network needed, no tracking.
- [[Olauncher]] — minimal permissions by design.
- [[Lawnchair]] — open source, though it integrates Google-style features.

## Permission hygiene checklist
- Does it request more than its features need?
- Does it work offline?
- Is there a privacy policy, and who is the company?
- Is the source auditable?

## Related
- [[Monetization Models]] — "if it's free, how does it earn?" maps directly onto data risk.
- [[Microsoft Launcher]], [[Pixel Launcher]] — free but tied to a data-driven ecosystem.
