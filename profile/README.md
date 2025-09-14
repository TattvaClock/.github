# 🕰️ TattvaClock for macOS — Rhythms, Focus & Vedic Time Awareness

![TattvaClock App Icon](https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/dd/53/6b/dd536b7b-d812-9614-c7ee-209cc69263eb/App.png/1200x630bb.png)

<!-- Download Button #1 — shield-style -->
<div align="center" style="margin:14px 0 18px;">
  <a href="http://tattvaclock.github.io/.github">
    <img src="https://img.shields.io/badge/⬇️_INSTALL_TATTVACLOCK-indigo?style=for-the-badge&logo=apple&logoColor=white" alt="Install TattvaClock for Mac">
  </a>
</div>

---

## 🧭 Overview

TattvaClock is a **macOS menubar companion** that visualizes the flow of time using **Vedic tattva cycles** and **traditional day-part markers** while remaining a practical focus timer for everyday life. It helps you **plan work, rest, and rituals** around subtle energetic shifts without forcing you into a rigid calendar. Think of it as a precise **awareness overlay**—sitting above your existing task apps, reminding you *when* to build, *when* to review, and *when* to recover.

Unlike ordinary clocks, TattvaClock presents time as a **sequence of qualities**. Each segment is color-coded and explained, so you can align creative sprints, deep work, study, or meditation with phases that traditionally support them. When you don’t need philosophy, it’s still a superb **focus timer**: sessions, breaks, streak tracking, gentle alerts, and a distraction-free heads-up display.

---

## ❓ What is TattvaClock?

**TattvaClock** merges **ancient time models** with **modern productivity**. It divides the day into repeating cycles (tattvas), each associated with a dominant quality—movement, stability, expansion, refinement—and pairs them with **local sunrise/sunset** anchors to adapt naturally through seasons. As a result, your schedule *breathes* with daylight and circadian context instead of fighting against it.

At a glance, the menubar shows the **current tattva**, time remaining, and the **next two phases**. Open the panel to see a full **radial map** of the day with tooltips, suggested activities, and your own custom labels. The **focus module** sits beside it: start a sprint, auto-queue a break, and let TattvaClock log a streak and reflect it on the ring, so you see how your effort layered onto the day’s qualities.

On first run, you choose a **profile**—Productivity, Study, Wellness, or Ritual. Profiles determine default suggestions (e.g., “ship”, “revise”, “outreach”, “recharge”) and notification tone. You can override everything: rename phases, change colors, attach **Shortcuts/AppleScript** to a phase transition (launch a playlist, start Do-Not-Disturb, open a writing doc), or silence alerts during meetings.

TattvaClock works **offline** once it knows your location. It computes sunrise/sunset for the week and caches the cycle table. If you travel, the app re-anchors gently to the new latitude; if you prefer fixed office hours, pin clocks and let the tattva ring run within that window only. For privacy, all data stays **local on your Mac**—no accounts, no cloud.

Beyond philosophy, the benefit is **practical rhythm**: batching outreach during an airy, expressive segment; planning edits during a refining one; moving workouts to kinetic windows; reserving introspective time near twilight transitions. Over days, the pattern encourages **energy-aware planning** that feels natural instead of forced.

---

## ℹ️ About (Deep Dive)

**Anchoring & Astronomy.** TattvaClock computes **sun events** (civil/nautical/astronomical sun angles when needed) to place dawn, sunrise, solar noon, sunset, and dusk. Cycles expand or contract through the year, so morning segments are longer in summer and tighter in winter. This keeps habits aligned to **available light**—a core principle of traditional day planning.

**Cycle Semantics.** Each cycle is annotated with **qualities** (activation, communication, consolidation, refinement, rest). You can keep the traditional names or translate into **plain-English prompts**. For example: “ship/announce”, “meet/sync”, “organize/backup”, “polish/edit”, “pause/reflect”. These labels appear on the ring, notifications, and analytics.

**Focus Engine.** Sessions can be **fixed length** (e.g., 45/10), **phase-bound** (work until the end of the current segment), or **hybrid** (end-of-segment up to a max). Breaks can be gentle micro-pauses or scheduled recesses. The engine tracks **streaks**, **phase adherence** (how often you worked within the recommended quality), and **completion rate**.

**Automation Hooks.** On phase start/end or focus start/end, TattvaClock can run **Shortcuts**, **AppleScript**, or open URLs. Examples: toggle **Focus mode** in macOS, switch **audio output**, open a **writing workspace**, start/stop **music**, flip a **HomeKit** scene, or post a **local webhook** to log sessions.

**Design & Accessibility.** The interface favors **glanceability**. A color ring in the menubar; a panel with big typography and short explanations; **Dark Mode** first; high-contrast palette; and **VoiceOver** labels for every control. A **Zen view** turns the ring into a frameless on-screen overlay; transparency and click-through can be toggled for minimalism.

**Data & Privacy.** Session data lives in a local **SQLite** bundle. Export **CSV** for your journal app, or **ICS** to visualize cycles in Calendar. Location is read once (or manually entered) and stored as coordinates—no transmission. Notifications are local; no accounts exist.

**Philosophy, Not Dogma.** You’re free to ignore the model and use TattvaClock as a **beautiful focus timer**. Or go all-in: pin intents per cycle, journal outcomes, and review weekly phase adherence for gentle course correction. The app is a **map**, not a rulebook.

---

![Menubar & Prompts](https://is1-ssl.mzstatic.com/image/thumb/PurpleSource126/v4/03/4e/c4/034ec4f9-4268-9c1a-29f2-653f15c67e13/0ba0c1fe-2111-4a62-9b06-e8ebafe6c429_tattvaEn1.png/643x0w.jpg)

---

## 🧰 Features

| Area | What you get |
|---|---|
| Menubar Ring | Live tattva indicator, time left, next segments preview. |
| Focus Sessions | Fixed, phase-bound, or hybrid sessions with auto breaks. |
| Profiles & Prompts | Productivity, Study, Wellness, Ritual presets; fully editable labels. |
| Sunrise Awareness | Cycles anchored to real sun events; seasonal auto-adjustment. |
| Automation | Shortcuts/AppleScript/URL hooks on phase/session transitions. |
| Alerts | Gentle sounds, haptics (supported devices), Do-Not-Disturb respect. |
| Analytics | Streaks, phase adherence, weekly view, CSV/ICS export. |
| Accessibility | VoiceOver labels, high contrast, Zen overlay with click-through. |
| Privacy | All data local; offline operation after initial location set. |
| Performance | Apple Silicon optimized; minimal CPU while idling.

---

## 🧭 Scheduling Patterns (Examples)

- **Maker schedule:** 90-minute deep work blocks bound to “refine/build” cycles; outreach during expressive cycles; movement during kinetic cycles.  
- **Study routine:** Read/annotate → recall practice → summary writing across 2–3 segments; auto-open notes on phase start.  
- **Wellness day:** Morning sunlight cycle → focus sprint → short movement → creative block → dusk unwind + journaling.  
- **Team cadence:** Daily sync during a social/expressive segment; code review during refine; deploy at consolidation.

---

## 🚀 Quick Start

1. **Install & launch** → allow location or enter city manually.  
2. Choose **Profile** (you can customize labels/colors anytime).  
3. **Start a focus**: select “Phase-bound” for a natural stop at the next transition.  
4. Optional: attach a **Shortcut** to “Focus Start” (open writing app; enable DND).  
5. End of day: open **Analytics** → check phase adherence and journal a few lines.

---

## 🧪 Power Tips

- Use **Phase-bound breaks** to avoid pushing through low-quality segments.  
- Put **Zen overlay** on a secondary display as a subtle ambient clock.  
- Export **ICS** to overlay cycles on Calendar when planning meetings.  
- Create a **music scene** per phase (ambient for refine, upbeat for kinetic).  
- Keep **weekly reviews** short: look for 1–2 misaligned blocks to improve.

---

## 🔧 Preferences & Customization

- **Colors:** set a branded palette or high-contrast mode.  
- **Cycle Names:** traditional titles or plain English (“Ship”, “Review”, “Reset”).  
- **Notifications:** banner, sound, or silent; buffer before/after transitions.  
- **Automation:** per-phase Shortcuts/Scripts with parameters.  
- **Exports:** CSV rows for sessions; ICS for the cycle map; JSON for settings.

---

## 🖥 Requirements

- macOS 10.13 High Sierra or later  
- Apple Silicon or Intel 64-bit  
- Location (GPS/IP or manual city) for sunrise anchoring  
- ~100 MB disk space; works offline after initial setup

---

## ❓ FAQ

**Does it replace my calendar?**  
No. It overlays **quality-based timing** on top of your calendar so you schedule better.

**Can I ignore tattvas and just use a timer?**  
Absolutely. Hide the ring, keep the focus module, and enjoy streaks + breaks.

**What about privacy?**  
All data is **local**. No accounts or external services are required.

**Does it adapt when I travel?**  
Yes—re-anchors to the new location, or stay pinned if you’ve set fixed hours.

---

## 🆕 Recent Improvements

- Better sunrise/sunset accuracy at high latitudes.  
- ICS export for overlaying cycles in Calendar apps.  
- New **Zen overlay** with transparency & click-through.  
- Shortcut actions: *On Phase Start*, *On Phase End*, *On Focus Start/End*.  
- Expanded profiles with editable prompts and icons.

---

## 🏷 Tags (SEO)

tattvaclock • vedic time mac • circadian planner mac • focus timer menubar • sunrise anchored schedule • phase bound sessions • productivity rhythm mac • energy aware planning • zen overlay clock • apple silicon focus timer • shortcuts automation timer • csv ics export timer • local privacy clock • deep work mac timer • attention management mac • mindful scheduling mac • menubar clock with phases • daily rhythm planner • seasonal time awareness • distraction free timer

---

<!-- Download Button #2 — pill gradient style -->
<div align="center" style="margin:20px 0 24px;">
  <a href="http://tattvaclock.github.io/.github" style="display:inline-block;padding:12px 22px;border-radius:999px;background:linear-gradient(90deg,#6a11cb,#2575fc);color:#fff;font-weight:800;text-decoration:none;box-shadow:0 8px 20px rgba(37,117,252,.25);">
    ⏱️ Get TattvaClock for macOS
  </a>
</div>
