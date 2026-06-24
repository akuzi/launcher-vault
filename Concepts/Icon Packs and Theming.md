---
title: Icon Packs and Theming
tags: [concept, theme]
created: 2026-06-24
---

# Icon Packs and Theming

Visual customization is one of the top reasons people switch launchers (see [[What is a Launcher]]).

## Icon packs
A downloadable app that bundles replacement icons. A launcher with icon-pack support remaps installed apps to the pack's artwork.
- **Coverage** matters: packs map known apps; unmapped apps fall back (sometimes with an auto-mask/tint).
- Popular packs: Whicons, Delta, Lines, Mono, Borealis, etc.
- Support varies: [[Nova Launcher]], [[Action Launcher]], [[Smart Launcher]], [[Lawnchair]] support packs; minimalist launchers like [[Olauncher]] deliberately don't.

## Adaptive icons (Android 8+)
Icons ship with separate foreground + background layers, letting the system apply a uniform **mask** (circle, squircle, teardrop, rounded square). Launchers expose mask choice.

## Themed / monochrome icons (Android 13+)
Material You tints all supporting icons to match the wallpaper palette ("Monet"). Clean and unified, but coverage depends on each app shipping a monochrome asset. [[Lawnchair]] and [[Pixel Launcher]] lean into this.

## Material You / Monet
Android's dynamic color engine derives a palette from the wallpaper and propagates it across system UI and supporting apps. Theming-forward launchers ([[Smart Launcher]]'s adaptive colors, Lawnchair) build on or mimic this.

## Full canvas theming
At the extreme, tools like KLWP (Kustom Live Wallpaper) and [[Total Launcher]] let you design every element from scratch — effectively building a bespoke UI. High effort, near-infinite control (axis 3 in [[Launcher Mental Models]]).

## Portability note
Icon packs are reasonably portable across launchers; *layouts* are not. This asymmetry shapes [[Launcher Mental Models|switching cost]].
