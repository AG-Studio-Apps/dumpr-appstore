---
layout: doc
title: "Privacy Policy"
description: "Dumpr is 100% on-device. No audio, transcripts, or captures ever leave your phone. No account, no analytics, no Dumpr server."
permalink: /privacy/
---

# Privacy Policy

<p class="doc-lead">Short version: everything Dumpr does stays on your iPhone. There is no Dumpr server, no account, and no analytics.</p>

<div class="notice-pill">
  Last updated: 5 May 2026 &mdash; contact: <a href="mailto:james@agnticstudio.com">james@agnticstudio.com</a>
</div>

<div class="doc-toc">
  <strong>On this page</strong>
  <ul>
    <li><a href="#what-dumpr-does">What Dumpr does with your data</a></li>
    <li><a href="#audio">Audio</a></li>
    <li><a href="#transcripts">Transcripts</a></li>
    <li><a href="#classification">Classification and segmentation</a></li>
    <li><a href="#routing">Routing to system apps</a></li>
    <li><a href="#sharing">Sharing a dump</a></li>
    <li><a href="#permissions">Permissions</a></li>
    <li><a href="#third-parties">Third-party SDKs</a></li>
    <li><a href="#children">Children</a></li>
    <li><a href="#changes">Changes to this policy</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div>

---

## What Dumpr does with your data {#what-dumpr-does}

Dumpr is a voice-capture and routing tool. It processes audio you record and routes the results to Apple's system apps on your device. The entire pipeline — recording, transcription, classification, and routing — runs on your iPhone. Nothing is sent to a Dumpr server, because there is no Dumpr server.

---

## Audio {#audio}

Audio is recorded **only while you hold a capture session open** and the microphone indicator is shown. Audio buffers are passed directly to Apple's on-device speech recognition framework and are never written to your device's storage. Audio is never transmitted to any server — by Dumpr or anyone else.

When you end a recording session, the audio is discarded. The only thing kept is the text transcript.

---

## Transcripts {#transcripts}

Transcripts of what you said are stored locally on your device in a private database. They are:

- **Never uploaded** to any server.
- **Never synced** via iCloud, Dropbox, or any cloud service. (If you use Apple's Encrypted iCloud Backup, your device's local data — including Dumpr's database — may be included in that backup under your own Apple ID. That is your backup, not ours.)
- **Never analysed** remotely.

You can delete individual dumps or clear the entire history from within the app at any time.

---

## Classification and segmentation {#classification}

After a recording, Dumpr splits your transcript into items and classifies each as a task, calendar event, or note. This runs entirely on-device using one of two approaches depending on your iPhone:

- **On Apple Intelligence-capable devices** (iPhone 15 Pro, iPhone 15 Pro Max, and all iPhone 16 / iPhone 17 models, with Apple Intelligence enabled): Dumpr uses Apple's on-device Foundation Models framework. The transcript is processed by a model that runs on the device's Neural Engine and never leaves the device.
- **On other supported devices**: Dumpr uses a text classifier that ships inside the app itself and runs locally with no network access.

In both cases, your transcript never leaves your phone during classification.

---

## Routing to system apps {#routing}

When you confirm items in the review sheet, Dumpr writes them to:

- **Apple Reminders** — via Apple's EventKit framework, locally.
- **Apple Calendar** — via Apple's EventKit framework, locally.
- **Things 3** — if you've chosen it, via Things 3's URL scheme, locally.
- **Apple Notes** — via the iOS share sheet, when you tap "Save to Notes".

Dumpr does not transmit anything to any server at this stage. Whether those destination apps subsequently sync their data (for example, Reminders syncing via iCloud) is governed by your own settings for those apps.

---

## Sharing a dump {#sharing}

When you choose to share a dump with someone, Dumpr encodes the items into a URL of the form `https://dumpr.agnticstudio.com/dump?...` and presents it via the iOS share sheet. You choose how to send it — Messages, Mail, AirDrop, WhatsApp, etc.

**The entire payload is encoded in the URL itself** (specifically in the URL's query parameters). The domain `dumpr.agnticstudio.com` hosts a static web page only. It does not receive requests carrying your data, does not have a database, and does not log or store anything about the link or its contents. The only thing Dumpr operates at that domain is a static fallback page for recipients who don't have the app installed.

The chosen sharing channel (Messages, Mail, etc.) has its own privacy policy, which is independent of Dumpr.

---

## Permissions {#permissions}

Dumpr requests the following permissions from iOS:

| Permission | Why |
|---|---|
| **Microphone** | To record audio during a capture session |
| **Speech Recognition** | To transcribe your recording on-device |
| **Calendar** | To create calendar events you've confirmed |
| **Reminders** | To create tasks you've confirmed |

Each permission is requested in context with an explanation. You can grant or revoke any permission independently in **Settings → Privacy & Security** on your iPhone. Revoking a permission only breaks the specific feature it supports.

---

## Third-party SDKs {#third-parties}

Dumpr contains **no third-party SDKs**, advertising identifiers, analytics frameworks, or telemetry libraries. There is no crash reporter, no A/B testing service, no session replay tool, and no advertising network. The only frameworks used are Apple's own system frameworks.

---

## Children {#children}

Dumpr does not knowingly collect any information from anyone. Because it collects no personal data at all, there are no special provisions regarding children's data — but Dumpr is designed as a productivity tool for adults and is not directed at children.

---

## Changes to this policy {#changes}

If this policy changes materially, the updated version will be posted here with a revised "Last updated" date. Continued use of the app after a policy update constitutes acceptance of the revised terms.

---

## Contact {#contact}

Questions about privacy? Email [james@agnticstudio.com](mailto:james@agnticstudio.com).
