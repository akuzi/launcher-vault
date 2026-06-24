---
title: Profiles
tags: [concept, theme]
created: 2026-06-24
---

# Profiles

"Profiles" in the launcher world means two genuinely different things. Keep them separate when researching.

1. **Launcher profiles / modes** — switchable home-screen *configurations* the launcher itself manages (a "Work" layout vs a "Home" layout).
2. **OS-level profiles** — separate, system-managed *app spaces* (Android Work Profile, Private Space, multiple users) that the launcher merely *surfaces*.

---

## 1. Launcher profiles / modes (configurations)

A saved set of home-screen state — which apps, layout, wallpaper, widgets, icon pack, even grid — that you can swap between, usually triggered by **context**.

### Triggers
- **Manual** — a gesture or toggle to switch (e.g. "Focus" ⇄ "Default").
- **Time-based** — work hours vs evening.
- **Location-based** — at the office vs at home.
- **Event/context** — connected to car Bluetooth → a "Driving" profile with big, few icons; headphones → a "Media" profile.

### Why it matters (mental model)
This is a direct expression of the **friction / intentionality** axis ([[Launcher Mental Models]]): a stripped "Focus" profile (few apps, no color) for work hours, a richer one off-hours. It's [[Digital Wellbeing and Minimalism]] applied *temporally* rather than permanently — you get minimalism when it helps and access when you want it.

### Where you see it
- **[[Smart Launcher]]** — explicit support for multiple home configurations / modes.
- **[[Nova Launcher]]** — achieved via app-state backups and automation (e.g. Tasker switching layouts), rather than a first-class "profiles" button.
- **[[AIO Launcher]]** and scriptable launchers — different widget sets per context.
- **OEM**: some [[OEM Launchers]] ship a separate **car / driving mode** and a **kids mode**, which are profile-like.
- Automation tools (Tasker, KWGT/KLWP) are the classic way to bolt context-switching onto any launcher.

### Trade-offs
- Powerful for **separating contexts** (work vs personal headspace) without separate devices.
- High setup cost; discoverability of triggers is poor (cf. [[Gestures as Input]]).
- Easy to over-engineer and then never switch.

---

## 2. OS-level profiles (Android, surfaced by the launcher)

These are managed by **Android**, not the launcher. The launcher's job is to *display* them — usually as a separate tab or section in the app drawer with **badged icons**.

### Work Profile
- Created by an MDM / "Android Enterprise" setup; isolates **managed work apps and data** from personal apps.
- Work apps show a **briefcase badge**; live in a separate **Work tab** in the drawer.
- Can be **paused** (a toggle that silences all work apps after hours).
- The launcher must support rendering the work tab — most mainstream launchers do ([[Nova Launcher]], [[Lawnchair]], [[Pixel Launcher]], [[Microsoft Launcher]]); some minimalist ones handle it poorly or not at all.

### Private Space (Android 15+)
- A hidden, lockable space for sensitive personal apps (a consumer-facing sibling of the work profile).
- Apps inside are hidden from the main drawer/search until the space is unlocked.
- Launcher support varies and is newer — a real compatibility gotcha when evaluating launchers.

### Multiple users / Guest mode
- Full separate user accounts (separate apps, data, even launcher choice). Heavier than a work profile; each user is effectively a fresh device shell.

### Why it matters (mental model)
- **Privacy & separation**: relevant to [[Privacy and Launchers]] — a launcher that mishandles work/private profiles can leak app presence or fail to respect the lock.
- **Compatibility checklist item**: "does it render the Work tab? does it support Private Space?" is a real reason power users stay on or leave a launcher.
- **Minimalist tension**: drawer-less / text-only launchers ([[Olauncher]], [[KISS Launcher]]) can struggle to expose a second profile cleanly, since they have no conventional tabbed drawer.

---

## Don't confuse them
| | Launcher profiles (mode) | OS-level profiles |
|---|---|---|
| Managed by | The launcher | Android |
| Purpose | Switch *layout/context* | Isolate *apps & data* |
| Data isolation | None (cosmetic) | Real sandboxing |
| Example | "Work" home screen | Work Profile, Private Space |

## Related
- [[Launcher Mental Models]] (friction axis, switching cost)
- [[Digital Wellbeing and Minimalism]] (temporal minimalism via modes)
- [[Privacy and Launchers]] (handling of work / private spaces)
- [[Glossary]]
