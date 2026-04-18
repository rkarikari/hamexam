# 📡 HamExam — Amateur Radio License Study App

**HamExam** is a fully self-contained Android study app for the FCC Amateur Radio License examinations. All three licence tiers — Technician, General, and Amateur Extra — are bundled in the app. No internet connection is required to study or take practice exams.

> Built by **RadioSport · 9G5AR**

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Study Modes](#study-modes)
- [Practice Exam](#practice-exam)
- [AI Tutor](#ai-tutor)
- [Progress & Statistics](#progress--statistics)
- [Certificates](#certificates)
- [Cloud Sync](#cloud-sync)
- [Privacy](#privacy)
- [Requirements](#requirements)

---

## Features

| Feature | Details |
|---|---|
| 📶 **Offline-first** | All question pools embedded — study anywhere, no SIM required |
| 🎓 **All three licence classes** | Technician · General · Amateur Extra |
| 📖 **Study by topic** | Browse questions grouped by subject area |
| 📝 **Full mock exams** | Timed, randomised, pass/fail scored |
| 🤖 **AI Tutor** | Ask questions, get explanations, use quick-prompt shortcuts |
| 📊 **Progress tracking** | Per-class progress bars, accuracy, streaks, and study time |
| 🏆 **Certificates** | Pass certificate with unique Session ID |
| ☁️ **Cloud sync** | Optional cross-device session backup |
| 💾 **Local persistence** | All progress auto-saved on-device |

---

## Installation

1. On your Android device go to **Settings → Apps → Special app access → Install unknown apps** and allow your file manager or browser.
2. Transfer `HamExam.apk` to the device and tap it to install.
3. Tap **Open** when installation completes.

> **Upgrading?** If you have an older version installed, uninstall it first before installing the newer version.

---

## Getting Started

When you open HamExam you land on the **Home Screen**:

```
┌─────────────────────────────────┐
│  AMATEUR RADIO LICENSE SYSTEM   │
│  FCC Question Pool · 2022–2026  │
│ ─────────────────────────────── │
│  📡 TECHNICIAN   ████░░░░  40%  │
│  🌐 GENERAL      ██░░░░░░  20%  │
│  🛰️  AMATEUR EXTRA░░░░░░░░   0%  │
│ ─────────────────────────────── │
│  YOUR STATISTICS                │
│  0 answered · 0 correct · —%    │
│ ─────────────────────────────── │
│  RETRIEVE CERTIFICATE           │
└─────────────────────────────────┘
```

Tap any licence card to begin studying for that class.

---

## Study Modes

After selecting a licence class you choose how to study:

### 📚 By Topic

Questions are grouped by subject area (e.g. *Regulations*, *Operating Procedures*, *Antennas*, *Propagation*). Tap any topic button to drill just those questions. Your progress bar fills as you answer correctly.

### 🔀 Full Question Pool

Cycles through all questions for the selected licence in a randomised order. Ideal for broad review sessions.

---

## Practice Exam

Tap **TAKE EXAM** from the mode screen to start a full simulated FCC examination.

| Licence | Questions | Pass mark | Time limit |
|---|---|---|---|
| Technician | 35 | 26 / 35 (74%) | 35 min |
| General | 35 | 26 / 35 (74%) | 35 min |
| Amateur Extra | 50 | 37 / 50 (74%) | 50 min |

**During the exam:**

- A live countdown timer is shown in the banner at the top of the screen.
- The AI Tutor is locked — this mirrors real exam conditions.
- Tap **SUBMIT** when finished (or let the timer expire).

**After the exam:**

- Your score and pass/fail result are displayed immediately.
- A breakdown by topic shows where you lost marks.
- On a **pass**, a certificate is generated with a unique Session ID.

---

## AI Tutor

The AI Tutor is available during study (not during timed exams). Tap the **🤖 EXPLAIN WITH AI** button on any question to open it.

### Quick prompts

Pre-built shortcut buttons let you ask common questions instantly, for example:
- *Ohm's Law*
- *Explain this question*
- *Give me a hint*

You can also type any question in your own words.

### Choosing an AI provider

| Provider | Cost | Setup |
|---|---|---|
| **Pollinations** (default) | Free | None — works immediately |
| **Gemini** | Free tier available | Requires a Google AI API key |

#### Setting up Gemini

1. Visit [aistudio.google.com](https://aistudio.google.com) and sign in with your Google account to generate a free API key.
2. In the AI panel, switch the provider to **Gemini**.
3. Paste your key into the field that appears.

Your key is stored only on your device and is sent exclusively to Google's servers.

---

## Progress & Statistics

The Home Screen **YOUR STATISTICS** section tracks your cumulative performance across all sessions:

| Stat | Description |
|---|---|
| Questions Answered | Total questions attempted across all modes |
| Correct Answers | Total correct responses |
| Accuracy | Overall percentage correct |
| Practice Exams | Number of full mock exams completed |
| Best Streak | Longest consecutive correct answer run |
| Study Time | Total time spent in the app |

Per-licence **progress bars** on each licence card show how much of that class's question pool you have covered correctly.

The 🔥 **streak counter** in the top bar tracks your current consecutive correct answer run in real time.

All statistics are saved automatically and persist between sessions.

---

## Certificates

When you pass a practice exam, HamExam generates a pass certificate containing:

- A unique **Session ID** in the format `RS-2025-XXXX`
- A short **Unlock Code** (e.g. `ABC-1234`)

**Keep these safe** — you will need them to retrieve your certificate later.

### Retrieving a past certificate

On the Home Screen, scroll down to **RETRIEVE CERTIFICATE**, enter your Session ID and Unlock Code, then tap retrieve.

---

## Cloud Sync

Cloud sync is **optional**. When enabled, your exam sessions are backed up online so you can access them across multiple devices.

To set it up, open the cloud/settings panel in the app and follow the on-screen instructions.

> Cloud sync requires an internet connection. All exam content still works fully offline without it.

---

## Privacy

HamExam contains no advertising, analytics, or tracking of any kind. The full question pool is stored inside the app itself.

When connected to the internet, the app contacts only the services needed for optional features — the AI Tutor and cloud sync. Your data is never sold or shared.

---

## Requirements

- **Android 7.0** or later
- ~5 MB free storage
- Internet connection: optional (only needed for AI Tutor and cloud sync)

---

## Licence

© R.N.K · 9G5AR · RadioSport. All rights reserved.

FCC question pool data is public domain (US Government). App code and design are proprietary.

---

*73 de 9G5AR — good luck on your exam!* 📻
