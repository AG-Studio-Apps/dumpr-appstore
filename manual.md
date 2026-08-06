---
layout: doc
title: "User Manual"
description: "How to use Dumpr day-to-day — capturing, reviewing, editing, sharing, and managing settings."
permalink: /manual/
---

# User Manual

<p class="doc-lead">Everything you need to use Dumpr well, day to day.</p>

<div class="doc-toc">
  <strong>On this page</strong>
  <ul>
    <li><a href="#capture">Making a capture</a></li>
    <li><a href="#review">Reviewing your dump</a></li>
    <li><a href="#categories">Changing categories</a></li>
    <li><a href="#dates">Checking and fixing a date</a></li>
    <li><a href="#split">Splitting a row</a></li>
    <li><a href="#feedback">Telling us when we get it wrong</a></li>
    <li><a href="#sending">Sending to destinations</a></li>
    <li><a href="#sharing">Sharing with another Dumpr user</a></li>
    <li><a href="#inbox">The inbox</a></li>
    <li><a href="#settings">Settings</a></li>
  </ul>
</div>

---

## Making a capture {#capture}

A capture is a single continuous recording session. You can start one in several ways:

- **Tap the record button** on the Dumpr home screen.
- **Tap the widget** on your lock screen or home screen.
- **Ask Siri** — "Hey Siri, Dumpr" opens straight into recording.
- **Press the Action Button** (if you've set Dumpr as its action in iPhone Settings).

Once recording starts, speak naturally. Don't worry about structure — say everything in whatever order it comes to mind. Short pauses mid-sentence are fine; if you go fully silent for several seconds, Dumpr wraps the recording up automatically. The transcript updates live at the bottom of the screen so you can see what's been captured.

**Tap stop** when you're finished. Dumpr immediately runs the transcript through segmentation and classification, then presents the review sheet.

### Tips for better captures

- **Be specific about time** — "lunch with Ali at one tomorrow" is more useful than "lunch tomorrow". The cleaner the time reference, the better Dumpr's date extraction.
- **Vary your phrasing** — Dumpr handles "I need to call the dentist on Friday" and "dentist Friday" equally well; don't worry about saying things in a special way.
- **Long dumps are fine** — a three-minute recording is the hard limit. For a particularly long session, stop and continue in a fresh recording; both appear in the inbox.

---

## Reviewing your dump {#review}

The review sheet appears immediately after processing. **Nothing leaves Dumpr until you tap Add all.**

The header shows a count of how many items are checked out of the total — for example, "5 of 6 items". Each row shows:

- A **tick circle** on the left — filled green when included, empty circle when excluded.
- The **item text** — editable inline. On calendar rows this is the tidied event title, which is exactly what Calendar will receive.
- A **date chip** — calendar rows only. Shows the date and time about to be written. Tap it to change them.
- A **category pill** below the text — shows Task, Calendar, or Note.

At the bottom of the sheet, the **Original transcript** section shows everything you said verbatim, plus a **Save to Notes** button.

---

## Changing categories {#categories}

Tap the **category pill** on any row to cycle it through the three categories:

| Category | What it means | Where it goes |
|---|---|---|
| **Task** | Something to do; no specific time required | Reminders (or Things 3 if configured) |
| **Calendar** | Something with a date and/or time | Apple Calendar |
| **Note** | An observation, idea, or reflection | Saved to your Dumpr inbox; use **Save to Notes** to keep one in Apple Notes |

Dumpr's classification is accurate but not infallible — a quick tap to correct is always faster than fixing it after the fact.

---

## Checking and fixing a date {#dates}

Any row set to **Calendar** shows a small date chip beneath its text — this is exactly what will be written to your calendar, so there are no surprises after you confirm.

- **A date and time** ("Sat 8 Aug, 10:00") means a one-hour event at that time.
- **A date only** ("Sat 8 Aug") means an all-day event.
- **"Add a date" in orange** means Dumpr couldn't work out when you meant. Worth tapping — otherwise the event lands an hour from now.

**Tap the chip** to open a date picker. Set the date and time, or flip the **All-day** toggle, then tap Done. Your choice always wins over Dumpr's; nothing that arrives afterwards will overwrite it.

Relative phrases like "this Saturday", "next Wednesday" and "tomorrow" are resolved against today's date. Vaguer phrasing ("the second weekend of August", "sometime next month") is where the chip earns its keep — glance at it, and fix it there rather than in Calendar afterwards.

---

## Splitting a row {#split}

Sometimes two separate things end up as a single row — "Mum coming round at 8 and Tom coming round at 12" might arrive as one item. To split it:

1. **Long-press the row** to bring up the context menu.
2. Tap **Split this item**.
3. Dumpr re-runs segmentation on just that row and replaces it with the resulting sub-items.

If the split doesn't produce separate items (the segmenter still reads it as one), a message lets you know. In that case, **edit the text by hand first** — adding a period at the obvious break point and tapping Split again usually does the trick.

---

## Telling us when we get it wrong {#feedback}

Correct something on the review sheet — flip a category, edit a title, set a date by hand, deselect or delete an item — and a short prompt appears:

> **Oops! Did we get it wrong?** Share and we'll fix it.

It only shows up when you've actually changed something. Accept a dump as-is and you'll never see it.

Tapping it opens your Mail app with a report already written: the transcript, what Dumpr proposed, and what you changed it to, plus your app and iOS version. **You can read and edit every word before sending**, and nothing goes anywhere until you press send. If you'd rather not send part of it, delete that part — the report is still useful. If you have no mail account set up, the iOS share sheet appears instead so you can send it another way.

These reports are the main way Dumpr's sorting gets better, and the corrections are the useful part — they show us exactly where the model went wrong. Nothing is uploaded in the background, and dumps that someone else shared with you never offer the prompt.

---

## Sending to destinations {#sending}

When you're happy with the review, tap **Add all** in the top-right corner. Only rows with a filled tick circle are sent. Each item routes independently:

- **Tasks** go to Reminders (your configured default list, or a new "Dumpr" list if no default is set). Recurring tasks ("take vitamins every day") get a recurrence rule.
- **Calendar events** go to your configured default calendar. Day-only references create all-day events; time-bearing references create one-hour blocks. Recurring events ("every Monday at 9") get a recurrence rule.
- **Notes** — items classified as notes aren't sent to a third-party app automatically in the review sheet. To keep a note, use **Save to Notes** (see below) or change the category to Task before confirming.

### Saving the transcript to Notes

In the **Original transcript** section of the review sheet, tap **Save to Notes**. The iOS share sheet appears with the transcript pre-populated; choose Notes to create a new note. This sends the raw text — useful for free-form journaling or when you want the full context alongside the routed items.

---

## Sharing with another Dumpr user {#sharing}

You can share an entire dump — all its checked items — as a link that the recipient opens directly in their copy of Dumpr.

1. On the review sheet, tap the **share icon** (top-left, looks like a box with an arrow).
2. A tone picker appears: **cheeky** ("Eric just dumped on you 💩") or **serious** ("Tasks shared with you by Eric"). The name shown is whatever you've set in Settings → Sharing.
3. Confirm, and a standard iOS share sheet appears with a link ready to send — via Messages, Mail, AirDrop, WhatsApp, or any other app.

The recipient taps the link and it opens directly in their Dumpr review sheet, where they can route the items to their own destinations. If they don't have Dumpr, the link opens a web page explaining what it is and how to get the app.

**Privacy note:** the entire payload is encoded in the link itself. No data passes through any Dumpr server. The web page at that link is purely a fallback for people without the app.

---

## The inbox {#inbox}

The inbox is Dumpr's history of everything you've captured. Each entry shows:

- **Brain dumps** — a parent row showing the original transcript summary and how many items it contained. Tap it to see the transcript and all routed segments. Tap any segment to view or re-route it.
- **Sent dumps** — dumps you've shared with someone, flagged "Sent".
- **Received dumps** — dumps someone shared with you, flagged "From [name]".

**Filter chips** at the top let you scope the view to Sent or Received only.

Tapping a routed item opens it natively — a Calendar event opens in the full Calendar interface, a Reminder opens in a detail sheet — or you can jump straight to the system app.

To **re-route an item** from the inbox: open the parent dump, tap the segment you want to change, and update its category. The item will be re-sent to the new destination.

---

## Settings {#settings}

Open Settings by tapping the gear icon in Dumpr. The configurable options are:

### Default destinations

| Setting | What it does |
|---|---|
| **Tasks (no date)** | Where undated tasks go — Reminders, or Things 3 if installed. |
| **Tasks with a date** | Where dated tasks go — currently always Apple Calendar. |
| **Default calendar** | Which of your calendars receives new events. |
| **Default list** | Which Reminders list receives new tasks. |

### Sharing

- **Your name** — shown to people you share dumps with (e.g. "Eric just dumped on you"). Leave blank to share anonymously.

### Tips

- **Show feature tips** — discreet hints that appear below lists pointing out non-obvious features. They fade automatically as you use the features. Toggle off to suppress them entirely.

All settings take effect immediately. None require restarting the app.
