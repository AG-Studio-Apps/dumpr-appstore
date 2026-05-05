---
layout: doc
title: "Getting started"
description: "Set up Dumpr in under a minute — grant permissions, choose your destinations, and make your first capture."
permalink: /onboarding/
---

# Getting started

<p class="doc-lead">From first launch to your first routed capture in under a minute.</p>

<div class="doc-toc">
  <strong>On this page</strong>
  <ul>
    <li><a href="#welcome">Welcome screen</a></li>
    <li><a href="#permissions">Permissions</a></li>
    <li><a href="#destinations">Default destinations</a></li>
    <li><a href="#first-capture">Your first capture</a></li>
    <li><a href="#review-sheet">The review sheet</a></li>
  </ul>
</div>

---

## Welcome {#welcome}

<div class="step-box">
  <span class="step-label">Step 1</span>
  <h3>Meet Dumpr</h3>
  <p>The opening screen shows the app name and tagline. Tap <strong>Continue</strong> to move to permissions.</p>
</div>

---

## Permissions {#permissions}

<div class="step-box">
  <span class="step-label">Step 2</span>
  <h3>A few permissions</h3>
  <p>Dumpr needs four permissions to do its job. Tap <strong>Continue</strong> and iOS will walk you through them — Microphone and Speech Recognition come first in a single combined dialog, then Calendar, then Reminders.</p>
</div>

| Permission | Why it's needed |
|---|---|
| **Microphone** | To record your voice during a capture session |
| **Speech Recognition** | To transcribe what you said on-device |
| **Calendar** | To create calendar events when you confirm them |
| **Reminders** | To create tasks in your Reminders lists |

Each iOS system dialog explains what the permission is for before you grant it. **You can deny any of them and still use the parts that don't need it** — for example, if you deny Calendar, tasks still route to Reminders. You can change any permission later in **Settings → Privacy & Security** on your iPhone.

---

## Default destinations {#destinations}

<div class="step-box">
  <span class="step-label">Step 3</span>
  <h3>Where should it go?</h3>
  <p>Tell Dumpr where to send items by default. You can change these at any time in Settings.</p>
</div>

### Tasks (no date)

By default, tasks without a specific date go to **Apple Reminders**, in a dedicated "Dumpr" list that is created automatically on first use (so your existing lists stay tidy). If you'd rather use **Things 3**, you can pick it here — just make sure you've installed it from the App Store first, otherwise routing will fail. You can change this any time in Settings.

### Calendar events

Calendar events always go to Apple Calendar. In this step you can choose which of your calendars to use — or leave it set to the system default.

### Reminders list

You can choose which Reminders list tasks land in, or leave the default "Dumpr (auto-create)" setting to have Dumpr manage its own list.

---

## Your first capture {#first-capture}

Once you've finished setup, the main screen is ready. To capture:

1. **Tap the record button** — or use the lock-screen widget, the home-screen widget, ask Siri ("Hey Siri, Dumpr"), or press the Action Button if you've assigned it.
2. **Speak freely.** Don't try to structure what you say. Ramble — Dumpr handles the sorting. Short pauses are fine; if you stay fully silent for several seconds, the recording wraps up on its own.
3. **Tap stop** when you're done. Dumpr processes your transcript immediately.

The hard cap on a single recording is 3 minutes. For longer dumps, stop and start a new recording — the inbox holds them all.

---

## The review sheet {#review-sheet}

After processing, the review sheet appears. **Nothing has been sent anywhere yet.**

The sheet shows every item Dumpr detected, each with:

- A **checkbox** — unchecked items are excluded when you confirm. Tap to toggle.
- **Editable text** — tap any row to edit the wording before it routes.
- A **category pill** (Task / Calendar / Note) — tap it to cycle through the three categories if Dumpr got one wrong.

Other things you can do on the review sheet:

- **Swipe left** on a row to delete it entirely.
- **Long-press** a row and choose "Split this item" if Dumpr glued two things together.
- **Tap "Save to Notes"** (in the Original transcript section) to send the full transcript to Apple Notes as well.
- **Tap the share icon** (top-left) to share the whole dump with someone else who has Dumpr.

When you're happy, tap **Add all** — only the checked items are routed to their destinations.

---

**That's it.** Head to the [User Manual]({{ '/manual/' | relative_url }}) for day-to-day tips and a full feature walkthrough.
