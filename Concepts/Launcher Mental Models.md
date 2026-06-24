---
title: Launcher Mental Models
tags: [concept, mental-model]
created: 2026-06-24
---

# Launcher Mental Models

The recurring frames researchers and power users use to reason about launchers. Most launchers can be located against each of these axes.

## 1. Retrieval model — how you find an app
The single most defining choice. Three dominant patterns:

- **Spatial memory** — apps live in fixed grid positions; you reach for them by location, like keys on a piano. (Stock grid, [[Nova Launcher]], [[Pixel Launcher]])
- **Search-first** — you type or speak; position is irrelevant. ([[KISS Launcher]], [[AIO Launcher]])
- **List / alphabetical** — a scrollable or scrubable list, often one-handed. ([[Niagara Launcher]], [[Olauncher]])

Trade-off: spatial is fast for a known small set but degrades as app count grows; search scales but adds a typing step; lists are predictable but require scanning.

## 2. Friction model — intentional vs frictionless
- **Frictionless / maximal access** — everything one tap away, lots of icons, widgets, glanceable data. Optimises for speed. ([[AIO Launcher]], info-dense setups)
- **Intentional friction** — deliberately hides apps, removes icons/color, forces a search or a deliberate gesture. Aims to break the unconscious "open Instagram" reflex. ([[Olauncher]], [[Before Launcher]], [[Niagara Launcher]])

This is the [[Digital Wellbeing and Minimalism]] axis. The bet: small friction interrupts dopamine loops.

## 3. Customization spectrum
A continuum from *touch nothing* to *design every pixel*:

`Stock-like` → `Themeable` → `Power-user` → `Build-from-scratch`

- Stock-like: [[Pixel Launcher]], [[Lawnchair]]
- Power-user: [[Nova Launcher]], [[Action Launcher]], [[Smart Launcher]]
- Build-from-scratch (canvas): [[Total Launcher]], KLWP-style setups

More control = more setup cost. Most users abandon deep customization within weeks; the launcher is most-used and most-rarely-reconfigured surface.

## 4. The launcher as a "shell" / replaceable OS layer
Android treats the home experience as a swappable shell. Mental model: the OS is a kernel + services; the launcher is the *window manager / desktop environment* equivalent (cf. GNOME vs KDE on Linux). This framing explains why launchers can be so different yet interchangeable, and why they have deep access (see [[Privacy and Launchers]]).

## 5. Glanceability — push vs pull of information
- **Pull**: you go look (open the app). Minimalist launchers.
- **Push / ambient**: information surfaces on the home screen without action — weather, next event, unread counts. ([[Microsoft Launcher]] feed, At a Glance, [[AIO Launcher]] widgets)

## 6. Monetization-shaped design
How a launcher earns shapes what it builds. See [[Monetization Models]]:
- One-time unlock → feature-complete, less ongoing pressure
- Subscription → recurring value, cloud/sync features, steady updates
- Free/OSS → community-driven, no upsell, slower or volunteer pace
- Ad/feed-supported → engagement incentives can conflict with minimalism

## 7. Lock-in & switching cost
Home-screen layout is muscle memory and manual setup. Backup/restore quality, layout import, and icon-pack portability determine how easily a user can leave. High switching cost is itself a moat (notably hurt users when [[Nova Launcher]]'s future became uncertain).
