# App Store Connect — everything to paste

Generated 2026-07-16 for Cause & Cure v1.0 (build 1), Dataset.json v38.
Character counts are checked against Apple's limits — don't pad them.

---

## 1. Name (30 char limit)

```
Cause & Cure
```
*12 chars.* **Reserving this is the definitive availability check — do it FIRST,
before any other work here.** The 2026-07-15 sweep found "MedRef" taken by a
near-clone ("MedRef Pro") and nearly every single-word medical term gone; "Cause &
Cure" showed no conflict, but only App Store Connect can confirm it.

## 2. Subtitle (30 char limit)

```
Disease, medication & organism
```
*30 chars exactly — at the cap. Do not add anything.*

## 3. Promotional text (170 char limit — editable without a new build)

```
Look up a disease and see its treatments, or a drug and see what it treats — both directions, offline. A study reference for rotations. Not for patient care.
```
*155 chars.*

## 4. Description (4000 char limit)

```
Cause & Cure is a bidirectional clinical study reference. Start from a disease and see how it's treated. Start from a drug and see what it treats. Start from an organism and see what it causes and what covers it. Every link works in both directions, so you can follow your thinking instead of the app's.

Built for the way rotations actually work: you hear a drug name on rounds and need to know what it's for, or you see a presentation and need to know what's likely and what to reach for.

WHAT'S INSIDE
• Diseases with specialty, management overview, and tagged treatment options
• Medications with class, mechanism, indications, dosing, half-life, metabolism, excretion, monitoring, max dose, renal/hepatic adjustment, and pregnancy/lactation notes
• Organisms with type, morphology, features, and source — plus how each presents as a syndrome, and which drugs cover it
• A drug interaction reference, organised by severity

THERAPY TAGS
Treatments are tagged first-line, alternative, second-line, prophylaxis, adjunct, symptomatic, or avoid — with a "use when" note explaining the context. Rename and recolour the tags to match how you think.

HOSPITAL-SPECIFIC PLANS
Formularies differ between sites. Tag a treatment to a hospital and it appears alongside the general standard, so you can carry one reference across rotations without losing what's specific to where you are.

DAILY QUIZ
Ten questions a day, generated from the reference itself — first-line therapy, what a drug treats, which organism causes a syndrome, coverage, mechanisms, half-lives. Miss one and it comes back tomorrow; get it right and it spaces out. Nearly 1,800 questions.

MARK WHAT YOU TRUST
Flag an entry as verified, or as needing correction with a note on what's wrong. Your review status is personal to you, and a data update will never overwrite something you've verified.

SEARCH
One search field covers diseases, medications, and organisms at once.

PRIVATE AND OFFLINE
No account. No analytics. No tracking. No servers. Everything you add stays on your device. The full reference ships inside the app and works with no connection.

IMPORTANT — PLEASE READ
Cause & Cure is a study and reference tool for medical education. It is not medical advice and not a substitute for professional clinical judgement. It must not be used to diagnose, treat, or make decisions for real patients.

Drug doses and treatment information are study drafts curated from third-party references and may be incomplete, out of date, or incorrect. Always verify against an authoritative source and current guidelines before any clinical use.

The interaction reference is a study aid only — not a real-world interaction checker. It shows only what is in its own catalogue, and an empty result never means a combination is safe.

Do not enter patient-identifiable information into the app.
```
*~2,700 chars — inside the limit with room to spare.*

## 5. Keywords (100 char limit, comma-separated, NO spaces after commas)

```
pharmacology,antibiotics,microbiology,drug,dosing,clinical,rotations,USMLE,medical,student,reference
```
*100 chars exactly.* Don't repeat words already in the name or subtitle — Apple
indexes those separately, so "cause", "cure", "disease", "medication" and "organism"
would be wasted characters here.

## 6. Category

- **Primary: Medical**
- **Secondary: Education**

Medical is the honest primary — the content is clinical. Education as secondary
reflects the study framing.

## 7. Age rating — answer the questionnaire like this

The one that matters:

- **Medical/Treatment Information** → **Frequent/Intense**

That yields **17+**. Do not soften it to Infrequent/Mild to chase a lower rating: the
app is wall-to-wall drug dosing and treatment information, and a rating that
understates it is both a review risk and dishonest. Everything else in the
questionnaire (violence, sexual content, gambling, horror, profanity, contests, drugs
in the *recreational* sense) is **None**.

Unrestricted web access: **No**. The app opens no web views.

## 8. URLs (both required for submission)

Replace `USERNAME` with your GitHub username after creating the repo:

- **Privacy policy URL**: `https://github.com/USERNAME/cause-and-cure/blob/main/privacy.md`
- **Support URL**: `https://github.com/USERNAME/cause-and-cure`
- **Marketing URL**: leave blank (optional; nothing to point at yet)

## 9. Copyright

```
2026 Sasha Lawrence
```

## 10. Review notes (private — reviewers read this)

```
Cause & Cure is an offline study reference for medical students. There is no account and no sign-in, so no demo credentials are needed — all functionality is available immediately on launch.

A medical disclaimer is presented as a full-screen gate on first launch and must be acknowledged before the app can be used. It is re-readable at any time from Settings > About > Disclaimer & safety.

The app is explicitly a study/education tool and is not intended for patient care or clinical decision-making. This is stated in the disclaimer gate, in the App Store description, and in the app's interaction reference, which carries additional messaging that it is not a real-world interaction checker and that an empty result does not imply safety.

The app collects no data whatsoever: no account, no analytics, no tracking, no third-party SDKs. Its only network request is a public file download that checks whether an updated reference dataset is available. It uploads nothing. A privacy manifest (PrivacyInfo.xcprivacy) is included declaring UserDefaults access under reason CA92.1.

Clinical content is curated by the developer from published third-party references for personal study use.
```

---

## Screenshots — required sizes and what to capture

Apple requires **6.9-inch** screenshots. 6.5-inch is strongly recommended (older
devices) and Apple will scale 6.9" down for other sizes if you don't supply them.

| Display | Simulator device | Pixel size (portrait) |
|---|---|---|
| 6.9" (required) | iPhone 17 Pro Max / 16 Pro Max | 1320 × 2868 |
| 6.5" (recommended) | iPhone 11 Pro Max / XS Max | 1242 × 2688 |

**You need 3–10 per size. Capture these 5, in this order** — the first two are what
most people ever see:

1. **A disease detail screen** with tagged treatments visible — e.g. Community-Acquired
   Pneumonia. This is the whole pitch in one image.
2. **A medication detail screen** showing the pharmacology sections — pick something
   meaty like Vancomycin or Amiodarone.
3. **An organism screen** showing "presents as" and "covered by".
4. **The daily quiz** mid-question.
5. **Global search** with results across all three types — search something like
   "staph" that hits several sections.

**How to capture from the simulator you're already running:**

1. Xcode → the device selector at the top → choose **iPhone 17 Pro Max** → ⌘R
2. Navigate to the screen you want
3. **⌘S** saves a screenshot to your Desktop at the correct pixel size
4. Repeat for iPhone 11 Pro Max

Do not add marketing frames or text overlays for v1.0 — plain screenshots are honest,
faster, and Apple has no objection to them.

---

## Order of operations

1. **Reserve the name** in App Store Connect. Everything else is wasted work if
   "Cause & Cure" is gone.
2. Create the GitHub repo, upload `Dataset.json`, `README.md`, `privacy.md`.
3. Tell me your GitHub username → I set `remoteDatasetURL` and verify the fetch.
4. Screenshots.
5. Paste the copy above into App Store Connect.
6. Archive and upload from Xcode.
