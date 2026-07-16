# Cause & Cure

**Know the cause. Find the cure.**

A study reference for medical students and clinicians in training: look up a disease
and see its treatments, look up a drug and see what it treats, look up an organism and
see what it causes and what covers it — in either direction.

> ### ⚠️ Study reference — not for patient care
>
> Cause & Cure is a personal study and reference tool for medical education. It is
> **not medical advice** and **not a substitute for professional clinical judgement.**
> It must not be used to diagnose, treat, or make decisions for real patients.
>
> Drug doses and treatment information are study drafts curated from third-party
> references and may be incomplete, out of date, or incorrect. **Always verify against
> an authoritative source and current guidelines before any clinical use.**
>
> Do not enter patient-identifiable information into the app.

---

## Support

**Found a mistake in the data, or something not working?**

Open an issue on this repository, or email causeandcuresupport@gmail.com.

If you're reporting a data problem, it helps enormously to include:

- the disease, drug, or organism name exactly as it appears in the app
- what it currently says
- what you believe it should say, and the source that says so

Clinical content is curated from published references. Corrections that cite a
guideline, label, or study get fixed fastest.

## Frequently asked

**Is my data private?**
Yes — entirely. The app has no account, no analytics, and no servers. Everything you
add stays on your device. See the [privacy policy](privacy.md).

**Does it work offline?**
Yes. The full reference ships inside the app. The only network request is an
occasional check for an updated dataset.

**How do updates to the clinical data work?**
The app checks `Dataset.json` in this repository on launch and pulls it in if it's
newer than what it has. That means data corrections can reach you without waiting for
an App Store update.

**Can I flag something as verified or needing correction?**
Yes — that's built in, and it's personal to you. Your review status is never shared
and is never overwritten by a data update.

---

## Dataset.json

The app's reference dataset. The app fetches this file directly; it isn't intended to
be edited by hand.
