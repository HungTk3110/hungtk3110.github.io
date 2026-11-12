# Smart Clean: Phone Storage — Privacy Policy Specification

## 1. Objective
Create a professional, responsive, and legally compliant Privacy Policy webpage for the Android storage utility application **Smart Clean: Phone Storage** (`com.obito.smartclean`), suitable for publishing on GitHub Pages and submitting directly to the Google Play Console Data Safety section.

The page is written in professional English and designed for seamless rendering on mobile webviews, desktop, and tablet displays.

---

## 2. Project Information
- **App Name:** Smart Clean: Phone Storage (Short name: `Smart Clean`)
- **Package Name:** `com.obito.smartclean`
- **Category:** Tools & Utilities / Phone Cleaner & Storage Optimizer
- **Platform:** Android
- **Developer / Publisher:** HungTk / Obito Team
- **Primary Contact Email:** `hungtk.forwork@gmail.com`
- **Alternative Contact:** `trinhkhachung31102001@gmail.com`
- **Hosting Platform:** GitHub Pages
- **File Name:** `smartclean-privacy-policy.html`
- **Root Repository:** `https://github.com/HungTk3110/hungtk3110.github.io`
- **Public Policy URL:** [https://hungtk3110.github.io/smartclean-privacy-policy.html](https://hungtk3110.github.io/smartclean-privacy-policy.html)
- **App Repository:** [https://github.com/HungTk3110/Smart-Clean](https://github.com/HungTk3110/Smart-Clean)
- **Effective Date:** November 12, 2026

---

## 3. Design & Architecture Characteristics
- **Color Palette & Visuals:** Premium dark Slate theme (`#0b1120`, `#1e293b`), high-contrast text (`#f8fafc`, `#cbd5e1`), with Emerald Green (`#10b981`) and Cyan (`#06b6d4`) accents matching Smart Clean's branding.
- **Typography & Layout:** Clean system font stack, high-contrast accessible typography (WCAG AA/AAA compliant), centered responsive container (`max-width: 860px`).
- **Semantic Structure:** Valid HTML5 with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
- **Navigation:** Table of Contents with quick anchor links to all sections.
- **Self-Contained:** Zero external JavaScript libraries or heavy font files, fast zero-latency rendering in any browser or Google Play embedded webview.

---

## 4. Privacy Policy Sections Included
1. **Overview & Privacy Commitment:** Identification of Smart Clean, scope of policy, Google Play Developer Program Policy adherence.
2. **Information Collection & Processing:**
   - *Zero Personal Data:* Explicit declaration that no PII, photos, or private files are uploaded.
   - *Local Metadata:* Explanation of local cache scanning, duplicate hashes, and RAM metrics.
3. **Third-Party Services, Ads & In-App Billing:**
   - Google AdMob (v23.6.0) & UMP SDK (GDPR consent).
   - Firebase Analytics & Crashlytics (diagnostics).
   - Google Play In-App Billing (v7.x) end-to-end payment security.
4. **Android Permissions & Justifications:**
   - Detailed disclosure cards and justification for `MANAGE_EXTERNAL_STORAGE` (All Files Access).
   - `POST_NOTIFICATIONS` (Notification quick-clean toolbar).
   - `PACKAGE_USAGE_STATS` / `KILL_BACKGROUND_PROCESSES` (Memory boost).
   - `INTERNET` & `ACCESS_NETWORK_STATE`.
   - Comprehensive Permissions Summary Table.
5. **Local Storage (Device Only):** SharedPreferences for offline language, VIP flag, and toolbar toggles.
6. **Data Retention & Security:** 100% on-device local execution; TLS encryption for third-party SDK telemetry.
7. **Children's Privacy:** COPPA compliance (general audience 13+, not directed to children).
8. **Google Play Data Safety Declaration Summary:** Direct mapping table for Google Play Console questionnaire.
9. **Your Privacy Rights & Opt-Out:** GDPR / CCPA rights and 4-step Android Advertising ID reset guide.
10. **International Transfers:** Cloud infrastructure disclosures and Standard Contractual Clauses (SCCs).
11. **Changes to This Policy:** Update tracking procedures and effective date.
12. **Contact Us & Project Repository:** Direct contact email and link to GitHub repository.

---

## 5. Google Play Data Safety Quick Checklist
When filling out the Google Play Data Safety form in Play Console for `com.obito.smartclean`:
- **Does your app collect or share any of the required user data types?** -> **Yes** (Only through third-party SDKs: AdMob and Firebase).
- **Is all of the user data collected by your app encrypted in transit?** -> **Yes** (All SDK transmissions use HTTPS/TLS).
- **Do you provide a way for users to request that their data be deleted?** -> **Yes** (Users can reset AAID in Android Settings or uninstall app to purge local SharedPreferences).
- **Photos and Videos / Files and Docs:** -> Select **No** (all file access is handled exclusively on-device for local cache/junk cleanup and is never collected or shared).
