# AvilaOps — Job Search Command Center (Android)

Mobile job-search tracker: applications, networking contacts, interviews, offers, and skills — with response-rate KPIs, auto follow-up dates, referral-source tracking, priority scoring for remote + Michigan roles, stale-application flagging, and JSON backup export/import.

- The app itself is a single self-contained HTML file (`app/src/main/assets/index.html`) running in an Android WebView.
- Data persists on-device via localStorage. No permissions, no network calls.
- Pushing to `main` triggers GitHub Actions to build `app-debug.apk` (see the Actions tab → Artifacts).

Built for Jose Avila Lara · Erebus Options LLC
