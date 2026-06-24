---
title: Widgets
tags: [concept, theme]
created: 2026-06-24
---

# Widgets

Widgets are **interactive or glanceable mini-apps embedded on the home screen** — a clock, weather, calendar, music controls, a to-do list. They are the launcher's main tool for the **push / ambient information** axis (axis 5 in [[Launcher Mental Models]]): information that surfaces *without* you opening an app.

## What they are (vs icons and shortcuts)
- **Icon** — launches an app. Static.
- **Shortcut** — jumps to a specific in-app action (e.g. "new message").
- **Widget** — *displays live content* and may be interactive in place (toggle, scrub, expand). It occupies grid cells rather than a single icon slot.

## The Android tech (brief)
- Built on the **App Widget framework** (`RemoteViews`) — apps publish widgets; the launcher hosts them.
- **Android 12 (Material You)** redesigned widgets: rounded corners, dynamic color, smoother resizing — a visible quality jump.
- **Jetpack Glance** lets developers build widgets with Compose, which improved the modern widget ecosystem.
- The launcher controls the **widget picker, placement, resizing**, and sometimes free/overlapping placement.

## Where the launcher's role shows
- **Resizing & grid fit** — how granularly a widget can be sized depends on the launcher's grid.
- **Free / overlapping placement** — most launchers snap widgets to the grid; canvas launchers like [[Total Launcher]] allow free, overlapping placement (see [[Icon Packs and Theming]]).
- **At a Glance / Smartspace** — Google's contextual widget (next event, weather, travel), native to [[Pixel Launcher]] and cloned by [[Lawnchair]] (see [[Glossary]]).
- **Text-widget dashboards** — [[AIO Launcher]] is built *entirely* from compact text widgets; the home screen is a stack of them.
- **Widget stacks / swipeable widgets** — some launchers and OEMs let widgets stack in one slot.

## Custom widget ecosystems (the theming engine)
Beyond app-provided widgets, a whole scene exists for **building your own**:
- **KWGT** (Kustom Widget Maker) — design bespoke widgets with layers, fonts, live data (battery, weather, calendar).
- **KLWP** (Kustom Live Wallpaper) — full home-screen canvases via the wallpaper layer.
- Zooper Widget — the influential, now-defunct predecessor.

These power the **setup-sharing viral loop** in [[Growth and Marketing Strategies]]: a shared "setup" is usually a launcher layout + a KWGT/KLWP preset. The beautiful widget *is* the advertisement (see [[Icon Packs and Theming]]).

## The minimalist tension
Widgets add information density — which is the opposite of [[Digital Wellbeing and Minimalism]]. Minimalist launchers ([[Olauncher]], [[Niagara Launcher]]) limit or omit traditional widgets, sometimes substituting a single calm element (clock/next event). Info-dense [[AIO Launcher]] sits at the far other end.

## Mental model fit
- **Glanceability (axis 5)** — widgets are the primary "push" mechanism; their density places a launcher on the minimal ↔ dashboard spectrum.
- **Customization (axis 3)** — widget freedom (resize, overlap, custom KWGT) is a power-user differentiator.

## Related
- [[Launcher Mental Models]] · [[Icon Packs and Theming]] · [[Digital Wellbeing and Minimalism]]
- [[AIO Launcher]] (text-widget dashboard) · [[Pixel Launcher]] / [[Lawnchair]] (At a Glance) · [[Total Launcher]] (free placement)
- [[Glossary]] (widget, At a Glance, Smartspace)
