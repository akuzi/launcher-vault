---
title: What is a Launcher
tags: [concept]
created: 2026-06-24
---

# What is a Launcher

On Android, the **launcher** (a.k.a. *home app*) is the app that draws the home screen, the app drawer, and usually the dock and widgets. It is the first thing you see after unlocking and the surface you return to between tasks.

Crucially, the launcher is **a replaceable system component**. Android exposes a `HOME` intent category; any app that declares it can register as the default home app. The user picks one in Settings → Default apps. This is the core reason a launcher *ecosystem* exists on Android but barely does on iOS, where the home screen is fixed (iOS only began allowing limited customization — widgets, app library, focus modes — and still has no third-party launcher concept).

## What a launcher controls
- **App icons** and their layout (grid size, labels, icon size/shape)
- **App drawer** — the full list of installed apps (or its absence)
- **Widgets** placement and home-screen pages
- **Dock / hotseat** — the persistent row
- **Folders**
- **Gestures** — swipes, double-taps, etc. (varies by launcher)
- **Search** entry point
- **Wallpaper / theming hooks** (icon packs, adaptive color)

## What it does NOT control
- Notifications shade and quick settings (system UI)
- Lock screen (separate component, though some launchers add lock-screen-like layers)
- The recents/overview screen on most versions (tied to system, though some launchers integrate)
- System-level gestures (back/home/recents navigation)

## Why people change launchers
1. **Customization** the stock launcher won't allow ([[Nova Launcher]], [[Action Launcher]])
2. **Reducing friction / distraction** ([[Niagara Launcher]], [[Olauncher]])
3. **Productivity / search-first** ([[KISS Launcher]], [[AIO Launcher]])
4. **Aesthetics / theming** ([[Icon Packs and Theming]])
5. **Replacing a disliked OEM skin** (see [[OEM Launchers]])

See [[Launcher Mental Models]] for the conceptual frames and [[Launcher Taxonomy]] for categories.
