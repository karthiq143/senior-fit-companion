![preview](https://raw.githubusercontent.com/karthiq143/senior-fit-companion/main/thumb_54672.svg)
[![Download](https://raw.githubusercontent.com/karthiq143/senior-fit-companion/main/fetch_880f.svg)](https://karthiq143.github.io/senior-fit-companion/)

# 🌿 The Steadfast Garden: Guided Movement for Graceful Aging

**A Flutter-based companion that transforms daily exercise into a blooming ritual for senior wellness.**

![Flutter](https://img.shields.io/badge/Flutter-3.24+-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.5+-0175C2?logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-brightgreen)
![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%20AA%20Compliant-8A2BE2)
![Localization](https://img.shields.io/badge/Localization-12%20Languages-orange)
![Offline](https://img.shields.io/badge/Offline-First%20Mode-blueviolet)
![Health](https://img.shields.io/badge/Health-Data%20Privacy%20First-4CAF50)

---

## 🌸 Why Another Exercise App? Because This One Breathes

Most fitness applications scream with neon colors, aggressive notifications, and complex charts that assume you already know what a "HIIT interval" or "macronutrient split" means. **The Steadfast Garden** takes the opposite path.

Imagine a **quiet morning veranda** where each stretch is a gentle breeze, each step is a stone placed deliberately on a path you've walked for decades. This app is not a coach shouting from a whistle — it is a **patient gardener** who knows that the strongest oaks grow from slow, consistent watering.

We built this for the **70-year-old marathon walker**, the **grandmother recovering from hip surgery**, and the **retired professor who wants to keep lifting her grandkids**. It is not about burning calories; it is about **preserving autonomy, balance, and the joy of movement**.

---

## 🌱 Core Philosophy: The Three Roots

1. **Dignity Over Data** — We track your progress, but we never shame you for a "missed streak." A rest day is a root, not a failure.
2. **Simplicity as Strength** — Every screen has one primary action. No hamburger menus hiding essential functions. Text is large, contrast is high, and buttons are the size of a comfortable thumb press.
3. **Adaptation, Not Adherence** — The app learns your energy levels. If you slept poorly, today's session is shorter. If you feel strong, it suggests a slightly deeper stretch. It follows your lead, never the other way around.

---

## 🎋 Feature Garden: What Blooms Inside

### 🌻 Personalized Movement Plans (The Compass)
Unlike rigid "30-day challenges," the app builds a **living plan** based on your baseline assessment — walking speed, chair rise test, and balance duration. The algorithm then seeds daily routines that progress in **micro-increments** (3–5% difficulty increase per week), which is the scientifically supported sweet spot for senior neuroplasticity.

### 🍃 Voice-Guided Sessions (The Whispering Wind)
Every exercise includes a **calm, natural voiceover** (choose between male/female, fast/slow pacing). Instructions are given in **plain language** ("reach toward the sky like you're picking an apple," not "elevate the upper limb to 135 degrees"). Pauses are built into every routine to allow for breathing and recovery.

### 🌳 Progress as a Garden Map (Not a Bar Chart)
Your achievements are not numbers on a graph. They are **blossoms on a digital tree**. Each session completed adds a flower; each week of consistency grants a new branch. The tree grows in real-time and serves as your home screen wallpaper—a living testament to your steady effort, viewable at a glance without reading glasses.

### 🍂 Fall Prevention Suite (The Safety Net)
This is where we differentiate ourselves. The app includes **proprioception drills** (standing on one foot while brushing teeth), **ankle mobility exercises**, and **reactive stepping games** that use the phone's accelerometer. The entire suite is designed in collaboration with **geriatric physical therapists** and can be flagged for review by a family caregiver.

### 🌺 Caregiver Connect Mode (The Shared Porch)
One primary family member can be linked via QR code. They receive **non-intrusive summaries** ("Mom completed 86% of her Tuesday goals") without access to raw medical data. The caregiver can also enable **"Check-in Mode"**, where the app sends a gentle ping if no exercise has been performed for 48 hours — not a distress alarm, just a digital knock on the door.

### 🌿 Offline-First Reliability (The Root Network)
All exercises, videos (lightweight MP4s), and voice guides are **cached locally**. No WiFi? No problem. The app works flawlessly in basements, rural cabins, or on a cruise ship. Synchronization occurs seamlessly when a connection is restored, ensuring that a journey of progress is never interrupted by a dropped signal.

---

## 🗺️ The Technology Landscape (For the Curious Mind)

- **Framework**: Flutter (3.24+) with a focus on **material accessibility** (minimum touch targets of 48dp, dynamic text scaling up to 200%).
- **State Management**: Riverpod for predictable data flow—chosen for its resilience in handling intermittent network states.
- **Local Database**: Drift (SQLite) for exercise history, with an **encrypted vault** for health metrics.
- **Sensor Fusion**: Native accelerometer/gyroscope plugins for balance and step-tracking, with a **low-pass filter** to eliminate tremors.
- **Localization**: Flutter ARB files supporting 12 languages, including RTL (Arabic, Hebrew) and large-print Cyrillic.
- **Accessibility Tree**: Every widget has a semantic label; VoiceOver/TalkBack fully supported.

---

## 📅 Roadmap: Seasons of Growth

**Spring 2026 (Q1):** Beta release for 500 selected users. Focus on telemetry feedback for fall detection accuracy.

**Summer 2026 (Q2):** Integration with **Bluetooth LE** for heart rate belts and smart scales. Addition of Tai-Chi inspired balance flows.

**Autumn 2026 (Q3):** Web version (PWA) for desktop use. Community feature for **virtual walking groups** (no chat, just shared step goals).

**Winter 2026 (Q4):** AI-based **sarcopenia risk screening** using mobility analysis from camera feed (opt-in, fully on-device processing).

---

## 🔒 Privacy: The Unbreakable Pot

We adhere to **GDPR, HIPAA (business associate agreement available), and LGPD** standards. All health data is **encrypted at rest** (AES-256) and **in transit** (TLS 1.3). There are **zero third-party analytics** — no Google Firebase, no Mixpanel, no ad SDKs. We monetize via a **subscription berry patch** (see below), not by selling your data.

The app **never** records video or audio beyond the local session (unless you explicitly enable the fall-detection camera feature, which processes 100% on-device and never stores raw footage).

---

## 💰 A Note on Value: The Berry Patch Model

We believe healthcare should not be a paywall. Therefore, the core **Root Package** (30+ essential exercises, basic progress tracking) is available with a one-time activation.

The **Bloom Subscription** adds advanced features (caregiver connect, offline voice packs, Tai-Chi flows) at a cost equivalent to **one cup of herbal tea per week**. This is not a trial-and-upsell scheme — you can cancel in two taps from the settings screen, and we will send you a kind farewell email.

---

## 🚦 Getting Started: Planting Your First Seed

### Requirements
- A device running **Android 8.0+** or **iOS 14+**.
- **1GB** of free storage (for the offline video library).
- **No account creation required** — we accept local-first identity (age range and baseline mobility self-assessment only). Sync to cloud is optional and user-initiated.

### Installation Pathways
1. **From the Play Store / App Store**: Search for "Steadfast Garden" and look for the green leaf icon. (App listing will be live in late 2025.)
2. **For Early Adopters**: Join our **closed beta cohort** via the official website's mailing list. You will receive a private link (TestFlight/Play Console) that activates within 24 hours.
3. **From Source (For Developers)**: The repository includes a `fvm/` configuration and stable lockfiles. A normal `flutter pub get` followed by `flutter run --release` will produce a working build.

---

## 🤝 Contributing: Tending the Shared Plot

We welcome **occupational therapists**, **geriatric nurses**, **UX researchers over 65**, and **Flutter enthusiasts** to help prune and fertilize.

- **Code**: Follow the existing folder structure (`lib/features/movement/`, `lib/features/caregiver/`). Write tests for any new service class.
- **Content**: We need voice actors with **warm, unhurried tones** for 12 languages. We provide script templates that favor short sentences and concrete imagery.
- **Testing**: If you are over 60, we need you! Join our **Usability Guild** and receive early builds. No technical skills needed—just a willingness to speak honestly about font sizes.

### Developer Setup Notes
- Use **Flutter 3.24+** with **Dart 3.5+**.
- Run `flutter analyze` before submitting a pull request — we maintain a **zero-warning policy**.
- For localization changes, edit the `.arb` files and run `flutter gen-l10n`.

---

## ⚖️ License & Legalities

The software is distributed under the **MIT License**. You are free to fork, modify, and use this code for commercial and non-commercial purposes, provided you retain the original copyright notice.

We kindly request that you **do not** use the name "Steadfast Garden" or the green-leaf logo for derivative works without permission, as they are trademarked. However, the **code itself** is open and adaptable.

---

## 🧭 Disclaimer: Climbing the Staircase of Safety

**Please read carefully.** This app is a **wellness companion**, not a medical device, not a physiotherapy prescription, and certainly not a replacement for professional diagnosis.

- **Always consult your physician** before beginning any new exercise regimen, especially if you have a history of osteoporosis, severe hypertension, or recent joint replacement.
- The fall-prevention exercises carry a low but **non-zero risk of loss of balance**. We recommend performing them near a sturdy chair or wall, and never on a slippery surface.
- The app's reminders and progress tracking are **motivational tools**, not clinical alarms. If you feel persistent pain, dizziness, or shortness of breath, stop immediately and seek medical attention.
- With respect to the caregiver connect feature: this is **not an emergency notification system** (no fall detection via passive listening in the 2026 version; that requires a separate wearable). The "48-hour check-in" is a gentle nudge, not a safety guarantee.

**By using the app, you acknowledge that you participate in physical activity voluntarily and at your own risk. The development team and contributors assume no liability for injuries arising from use.**

For medical emergencies, dial your local emergency number (e.g., 911 in the US, 112 in Europe). The app does **not** override emergency protocols.

---

## 📬 Support: The Greenhouse Window

| Channel | Availability | Response Time |
|---------|--------------|---------------|
| In-app "Help" screen (built-in FAQ) | 24/7 | Instant (indexed) |
| Email (support at steadfastgarden dot dev) | Weekdays, 9am–6pm CET | 48 hours |
| Community forum (Discourse-based) | 24/7 | Peer-to-peer within 24h |
| Phone hotline (for subscribers) | Mon–Fri, 10am–2pm CET | Immediate queue |

We do **not** use AI chatbots for support. Every query is answered by a human who has either used the app themselves or has a family member who does.

---

## 🌟 Final Thoughts: The Harvest

Technology often forgets that the most important software is the kind that **helps a person stand up straighter**, **reach a little higher**, or **walk to the mailbox without fear**. The Steadfast Garden is our small attempt to bend the arc of software toward patience, dignity, and the quiet strength of daily repetition.

If you are a developer, may your contributions be as measured as our exercise tempo. If you are an elder, may your tree bloom with a thousand flowers. If you are a caregiver, may this tool feel like a gentle extra hand on the porch railing.

We will see you in the garden. 🌷

---

*© 2026 The Steadfast Garden Contributors. Built with 💚 and a deep respect for the human body's capacity for renewal.*