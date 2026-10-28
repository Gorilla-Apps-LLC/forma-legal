---
layout: page
title: Privacy Policy
permalink: /privacy/
---

# Forma — Privacy Policy

**Effective date:** October 22, 2026
**Last updated:** October 28, 2026

Forma ("Forma," "we," "us," or "our"), provided by Gorilla Apps LLC, is a personal workout and
nutrition tracking app. This policy explains what data Forma collects, how it is used and stored,
and the choices you have. It applies to the Forma iOS app, Android app, and web app (together, the
"Service").

We built Forma so your data is *yours*. We do not sell it, we do not show ads, and we do not embed
third-party analytics or tracking SDKs.

---

## The short version

| | |
|---|---|
| **What we collect** | What you enter or choose to sync: workouts, nutrition, body metrics, blood pressure, resting heart rate, lab results, progress photos, and your account email — plus first-party usage events (which features you use, not what you logged) kept in our own database. |
| **Why** | To provide the app's features to you — logging, trends, reminders, and optional AI insights. |
| **Who we share it with** | A small set of infrastructure providers that run the app (database/hosting, AI insights, food lookups, push delivery). Listed in full below. |
| **What we never do** | Sell your data. Show you ads. Use third-party advertising or analytics trackers. |
| **Your controls** | Export your data, delete your account and all its data from within the app, and turn notifications off at any time. |

This summary is for convenience; the full policy below governs.

---

## 1. Who we are

Forma is operated by Gorilla Apps LLC. For any privacy question or request, contact us at
**info@gorillaapps.ai**.

## 2. Information we collect

We collect the following categories of information. Almost all of it is information **you choose to
enter**. The only background collection is the optional Apple Health sync described in §2.3 — it
runs only after you have explicitly connected Apple Health, syncs only the data types listed there,
and can be turned off at any time on the Apple Health card in the app.

### 2.1 Account information
- **Email address**, used to create and sign in to your account. Forma uses passwordless sign-in
  (a one-time link or code sent to your email); we do not store a password for you.
- Optional profile settings you configure: a note to the coach (your goals statement); your daily
  calorie and macro targets, with the date you set them and whether they came from a program you
  picked (each change is kept as a dated history so you and the coach can tell which numbers were
  yours); your stated goal (cut, maintain, build, or recomp) as a dated history — you can withdraw
  it, which deletes that history; your training setup (equipment, days per week, session length,
  experience, and what you train for), stored only as fixed choices, never free text; water target,
  unit preferences, and timezone.

### 2.2 Health and fitness data you enter
This is the core of the app and consists of information you log yourself:
- **Workouts** — exercises, sets, reps, weights, session history, programs, and workout notes.
- **Nutrition** — logged meals and their calories/macros, and water intake.
- **Body metrics** — body weight, height, body-fat percentage, and body (tape) measurements. If
  you use the tape-based body-fat estimate, the protocol you choose for it (the formula is
  sex-specific) is stored with your settings; the estimate itself is computed on your device and
  only the result you choose to log is kept.
- **Vitals** — blood pressure readings and resting heart rate.
- **Lab results** — values you record from health panels.
- **Progress photos** — images you choose to upload to track visual change over time.

Some of this is **health-related data** and we treat it with corresponding care (see *How we protect
your data*).

### 2.3 Apple Health data (optional two-way sync)
If you choose to connect Apple Health (an explicit permission prompt controlled by iOS), Forma
syncs **two ways**:

- **Reads into Forma**: body weight, body-fat percentage, active and resting energy, steps,
  resting heart rate, blood pressure, dietary energy and macros, and workouts recorded by other
  apps or devices (for example a watch workout or an exercise-bike ride) — including the name of
  the app or device that recorded each workout and, for those workouts, the heart-rate samples and
  cycling power recorded during them, which Forma shows on the workout's detail. **Sleep** is read
  only if you separately turn on *Sleep in your weekly review*, and only as a weekly average — no
  nightly sleep data is stored.
- **Writes from Forma to Apple Health**: entries you logged in Forma yourself — weigh-ins,
  body-fat entries, meals, water, and blood pressure. Values Forma computes (such as the fat-loss
  projection or AI insights) are **never** written to Apple Health.

After your first sync, Forma re-syncs automatically when you open the app and — if the build
supports it and iOS allows — in the background while the app is closed, for the read types listed
above. Forma keeps a record of what it has written to Apple Health so the same entry is never
duplicated or re-imported. You can turn automatic sync off at any time on the Apple Health card in
the app, and you can revoke any permission in iOS Settings → Privacy → Health. On Android, there is
no Health Connect integration in this version.

### 2.4 Notifications data
If you enable reminders, we store a **push notification token** for your device and your reminder
preferences (including timezone) so we can deliver reminders at the right local time. Reminder
messages can include a brief summary figure you logged — for example, your protein total so far
today — so the reminder is useful at a glance.

### 2.5 Technical data
Forma stores a session token on your device to keep you signed in, and your theme preference. Our
infrastructure providers process standard technical data (such as IP address and request logs)
needed to operate and secure the Service. Forma does not collect your location or GPS coordinates
(we store only your timezone, to schedule reminders), does not use advertising identifiers, and does
not embed third-party analytics, advertising, or cross-app tracking SDKs.

## 3. How we use your information

We use your information only to provide and operate the Service:
- To store your logs and show them back to you as dashboards, history, and trends.
- To calculate derived figures (streaks, calorie-deficit math, trend lines).
- To look up foods and barcodes you search for.
- To generate the optional AI insights you request (see *AI features* below).
- To send the reminders you enable.
- To understand which features are used. Forma records **first-party usage events** — for example
  "meal logged" or "coach viewed," with the kind of action and a timestamp, never the content of
  what you logged — in our own database, to improve the app. No third-party analytics service
  receives them. They are deleted with your account.
- To secure the Service, prevent abuse, and comply with law.

We do **not** use your data to build advertising profiles, and we do **not** sell or rent it.

## 4. AI features (important disclosure)

Forma includes an optional AI "coach" that writes a weekly review of your trends, narrates the
workouts you save, and answers questions you ask. **The coach is off until you turn it on** — in the
app under *Account*, or from the *Coach tools* screen — and you can turn it off in the same places
at any time. While it is off, nothing is sent to Anthropic for coaching: no weekly review is
generated for you and your saved workouts are not narrated. The date you turned it on is recorded in
your account as your consent record.

When the coach is on:

- Each week, and whenever you ask for an analysis or type a question, we send a **28-day summary of
  your data** — computed as aggregates, not your raw entries — to our AI provider, **Anthropic** (the
  Claude API), to generate the text. The summary can include: your average and change in body
  weight; workout counts and per-lift top-set progression; average calories, protein, and water
  against your daily targets — only the targets you set yourself or kept from a program as yours,
  never the app's placeholder, and only the fields you set; planned-versus-logged meal adherence;
  the change between your last two tape checkpoints (never the measurements themselves); your
  stated goal and the date you stated it; and the note you wrote to the coach. If you
  have connected a health store, it can also include your **average resting heart rate**, **average
  blood pressure**, the count and minutes of outside workouts by type, your training-load ratios
  against your own norm, and — only if you also turned on sleep in your weekly review — your weekly
  sleep average.
- When you **save a workout**, the coach narrates it from a short list of findings the app already
  computed (for example "top set up from last session"), never from your raw sets.
- If you **ask the AI a question**, the text of your question is also sent to Anthropic, and the
  feature may run a web search to answer it.
- The AI-generated text is stored in your account alongside the data summary it was based on. You
  can delete any of it from the *Coach tools* screen; turning the coach off does not delete reviews
  already written.

Two other features use Anthropic and run only when you take the specific action, whether or not the
coach is on:

- If you **photograph a meal** to log it, the photo is sent to Anthropic only to identify the foods
  on the plate; it is not stored, and the nutrition numbers come from the food databases, not from
  the AI.
- If you use **Look it up** for a restaurant or branded item, the food name you typed is sent to
  Anthropic to find a page that publishes its nutrition facts; our servers then fetch that public
  page and read the figures from it. The page's address is recorded with the result.
- If you **bring in a routine you already have** (a photo of a page, a screenshot of another app,
  or text you paste), that photo or text is sent to Anthropic only to read the exercises, sets,
  reps, and loads out of it. The photo and the pasted text are not stored; what you confirm on the
  read-back screen is saved as your program, including the exercise names as you wrote them.

Anthropic processes this data as our service provider, on our instructions, to return the text.
Anthropic's handling of API data is governed by its own terms; see Anthropic's privacy policy. The
AI does not provide medical advice, and its output can be incomplete or wrong — see the Terms of
Service health disclaimer.

## 5. How we share your information

We share data only with the infrastructure providers ("service providers" / "sub-processors")
required to run Forma, each limited to what its function needs:

| Provider | Purpose | What it receives |
|---|---|---|
| **Supabase** (database, authentication, file storage; hosted on cloud infrastructure) | Stores your account and all your data, including progress photos | Your account email and all data you enter |
| **Anthropic** (Claude API) | Generates the optional AI insights you request; identifies foods in a meal photo; finds a nutrition page for a food you look up; reads a routine you bring in | The 28-day data summary described in §4, any question text you submit, a meal photo you choose to analyze (not stored), the food name you look up, or the routine photo or text you choose to bring in (not stored) |
| **USDA FoodData Central** and **Open Food Facts** | Food and barcode lookups | The search term or barcode you enter — **not** your identity or account data |
| **Apple Push Notification service, Google/Firebase Cloud Messaging, and Expo push service; Web Push (browsers)** | Delivering the reminders you enable | A device push token and the reminder message |
| **Apple App Store / Google Play** | App distribution and any future in-app purchases | Governed by Apple's and Google's own policies |

We may also disclose information if required by law, to protect our or others' rights and safety, or
in connection with a business transfer (in which case this policy continues to govern your data).

We do **not** share your data with advertisers, data brokers, or third-party analytics companies.

## 6. If you choose to share access

Where the Service offers it, you may invite another person to view your data on a read-only basis.
This happens only when you initiate it, you control who is invited, and you can revoke access. Anyone
you invite can see the data you grant them; only share with people you trust.

## 7. How we protect your data

- Your data is isolated per-account by database row-level security, so one account cannot read
  another's data.
- Progress photos are stored in a **private** storage bucket with no public/anonymous access path.
- Connections to the Service use encryption in transit (HTTPS/TLS).
- Secret keys (including the AI provider key) live only on the server and are never shipped in the
  app.

No method of transmission or storage is 100% secure, and we cannot guarantee absolute security.

## 8. Data retention

We keep your data for as long as your account exists so the Service can show you your history. When
you delete your account (see below), we delete your account record, your data, and your uploaded
photos. Backups and provider logs may persist for a limited period before being overwritten in the
ordinary course.

## 9. Your rights and choices

- **Access** — your data is visible to you in the app at any time.
- **Export** — in the **web app**, you can export your workout history, meals, body metrics, blood
  pressure, lab results, and Apple Health data as CSV files (each category exports separately;
  progress photos are not included). CSV export is not currently available in the mobile app.
- **Delete** — you can permanently delete your account and its associated data from within the app
  (Account → Delete account). This removes your database records, your stored photos, and your
  sign-in identity.
- **Notifications** — you can turn reminders off at any time in settings or in your device settings.
- **Correction** — you can edit or remove individual entries directly in the app.

Depending on where you live, you may have additional rights (such as under GDPR or the CCPA). To
exercise any right, contact **info@gorillaapps.ai**.

## 10. Children's privacy

Forma is not directed to children and is intended for users **16 and older**. We do not
knowingly collect data from children under that age. If you believe a child has provided us data,
contact us and we will delete it.

## 11. Where your data is processed

Forma's providers operate in the United States and may process and store data there. If you use
Forma from another country, you consent to processing in the United States and other locations where
our providers operate.

## 12. Changes to this policy

We may update this policy as the app evolves. We will change the "Last updated" date above and, for
material changes, provide a more prominent notice. Continued use after an update means you accept the
revised policy.

## 13. Contact

Questions or requests: **info@gorillaapps.ai**.
