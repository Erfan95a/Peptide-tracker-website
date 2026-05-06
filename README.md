# Peptide Tracker

**The smart companion for peptide researchers.**
Track doses, explore research, and stay on schedule — all in one place.

---

## Overview

Peptide Tracker is an iOS app for people who take peptide research compounds seriously. It gives you a clear picture of your active peptide levels throughout the day, keeps a clean injection log, and surfaces real academic research so you can make informed decisions.

---

## Features

### Dose Tracking
Log injections in seconds. Choose from a catalog of 30+ peptides, enter your dose, pick an injection site on a visual body diagram, and set a one-time or recurring schedule. Every log is synced to the cloud so nothing gets lost.

### Active Level Chart
The dashboard shows a real-time concentration curve for each active peptide, calculated from pharmacokinetic half-life data. See when levels peak, when they drop, and when your next dose is due — at a glance.

### Timeline
A full history of every dose, grouped by day. Tap any entry to edit or delete it.

### Research Library
Browse peer-reviewed studies directly in the app. The research screen pulls from **Semantic Scholar** and **PubMed (NIH)**, showing abstracts, AI-generated TLDRs, and citation counts for each paper — organized by evidence tier (FDA Approved, Clinical Study, Animal Data, Estimated).

### Apple Health Integration
Connect to Apple HealthKit to view your activity, heart rate, and other wellness data alongside your peptide log — all in one dashboard.

### Reminders
Set smart notifications so you never miss a scheduled dose.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React Native + Expo (SDK 54) |
| Backend | Supabase (auth + data sync) |
| Auth | Apple Sign-In via Expo |
| Subscriptions | RevenueCat |
| Health data | Apple HealthKit (`@kingstinct/react-native-healthkit`) |
| Research APIs | Semantic Scholar · PubMed (NCBI/NIH) |
| State | Zustand |
| Navigation | React Navigation v7 |

---

## App Store

Available on the **App Store** for iPhone.

> This app is intended for research and educational purposes only. Always consult a qualified healthcare professional before using any compound.

---

## Privacy

- Dose data is stored securely in Supabase and never sold to third parties.
- Apple HealthKit data is read locally and is never uploaded.
- Authentication is handled exclusively through Apple Sign-In.

---

## Support & Contact

For questions, bug reports, or feature requests:

**Email:** [e.ahmadi95@protonmail.com](mailto:e.ahmadi95@protonmail.com)

You can also use the in-app feedback button in Settings.

> Apple requires a reachable support contact for all App Store submissions. The email above is the official support address for this app.

---

## Legal

This app is intended for **research and educational purposes only**. It does not provide medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional before using any compound.

Use of this app is subject to the [Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/us/terms.html).

---

*Built with React Native & Expo.*
