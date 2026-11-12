# Smart Clean: Phone Storage — Privacy Policy Specification

## 1. Objective
Create a professional, responsive Privacy Policy webpage for the Android mobile application **Smart Clean: Phone Storage**, suitable for publishing on GitHub Pages and submitting to Google Play Console.
The page is written in clear, professional English and optimized for mobile devices, tablets, and desktop displays.

---

## 2. Project Information
- **App Name:** Smart Clean: Phone Storage
- **Platform:** Android
- **Developer / Publisher Contact:** hungtk.forwork@gmail.com
- **Hosting Platform:** GitHub Pages
- **Filename:** `smartclean-privacy-policy.html`
- **Root Repository:** `https://github.com/HungTk3110/hungtk3110.github.io`
- **Expected Public URL:** [https://hungtk3110.github.io/smartclean-privacy-policy.html](https://hungtk3110.github.io/smartclean-privacy-policy.html)
- **Root Index Preserved:** `index.html` (maintained for Free Learn Piano without modification)
- **AdMob Status:** AdMob publisher identity verified via root `app-ads.txt` (`pub-7692599728154289`).

---

## 3. Design & Architecture Characteristics
- **Color Palette & Visuals:** Clean light background (`#f8fafc`), clean surface containers (`#ffffff`), and subtle indigo accents (`#4f46e5`, `#4338ca`, `#eef2ff`) identical to ArrowShift's design system.
- **Typography & Layout:** System font stack for zero-latency loading, high-contrast accessible typography (WCAG AA/AAA compliant), centered responsive container (`max-width: 860px`).
- **Semantic Structure:** Valid HTML5 with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
- **Navigation:** Table of Contents with smooth anchor links to all sections.
- **Self-Contained:** Zero external runtime JS libraries or heavy dependencies, rendering natively in any browser or embedded webview.

---

## 4. Privacy Policy Sections Included
1. **Introduction:** Identification of Smart Clean: Phone Storage, scope of policy, and developer contact.
2. **Information We Collect:**
   - *Information Provided Directly:* Contact email & user-submitted feedback.
   - *Information Processed Locally:* Cache files, duplicate checksums, obsolete APKs, and RAM metrics strictly on-device.
   - *Information Collected Automatically:* Technical telemetry, device identifiers (GAID), operating system version, and approximate network location.
3. **Advertising (Google AdMob):** Disclosures on advertising identifiers, personalized vs non-personalized ads, regional consent frameworks (GDPR/UMP), and link to [Google Advertising & Privacy Policy](https://policies.google.com/technologies/ads).
4. **Analytics & Diagnostics:** Firebase Analytics & Crashlytics for application stability and crash diagnostics.
5. **In-App Purchases & Billing:** Secure Google Play In-App Billing for optional VIP subscription upgrades.
6. **Android Permissions & Justifications:** Detailed disclosure cards and justification for `MANAGE_EXTERNAL_STORAGE` (All Files Access), `POST_NOTIFICATIONS`, `PACKAGE_USAGE_STATS` / `KILL_BACKGROUND_PROCESSES`, and `INTERNET`, plus a full permissions summary table.
7. **How We Use Information:** Legitimate operational purposes (service delivery, stability, monetization, user support, fraud prevention).
8. **Third-Party Services:** Direct disclosures and links for Google Play Services, Google AdMob, Firebase Analytics & Crashlytics, and Google Play In-App Billing.
9. **Local Storage & Data Retention:** Explains that preferences are stored locally in `SharedPreferences`, zero external storage of scanned files, and reasonable security protocols (HTTPS/TLS).
10. **Children's Privacy:** General audience classification (not directed at children under 13/16) and contact procedure for parental inquiries.
11. **Your Privacy Rights:** GDPR and CCPA/CPRA rights breakdown, including Android advertising ID reset steps and developer inquiry instructions.
12. **International Data Transfers:** Overview of global cloud infrastructure and Standard Contractual Clauses (SCCs).
13. **Changes to This Policy:** Policy update notifications and effective date tracking.
14. **Contact Us:** Clear contact box specifying app name, platform, and direct developer contact email (`hungtk.forwork@gmail.com`).

---

## 5. Developer Confirmation Checklist (Action Items for Developer)
Before releasing or updating the Google Play Data Safety form in Play Console, confirm the following items against your actual Android project build files (`build.gradle`, `AndroidManifest.xml`):

| # | Item | Status / Verification Needed |
|---|------|------------------------------|
| 1 | **Legal Entity Name** | Displayed as `HungTk`, matching developer identity in ArrowShift. |
| 2 | **AdMob Integration** | Confirmed AdMob integration with `app-ads.txt` publisher ID `pub-7692599728154289`. |
| 3 | **Analytics SDKs** | Firebase Crashlytics & Analytics for anonymous crash telemetry. |
| 4 | **In-App Purchases (IAP)** | Google Play Billing v7 for VIP subscriptions. |
| 5 | **Target Age Group** | In Google Play Console > App Content > Target Audience and Content, ensure the target age matches the policy (not directed to children under 13). |
| 6 | **Data Safety Form** | Ensure choices in Google Play Console Data Safety section correspond directly to the disclosures in this Privacy Policy. |

---

## 6. GitHub Pages Deployment Instructions

### Step 1: Check Git Status
```bash
git status
```

### Step 2: Stage and Commit the Files
```bash
git add smartclean-privacy-policy.html smartclean-privacy-policy.md
git commit -m "Update Smart Clean privacy policy to match ArrowShift design and contact info"
```

### Step 3: Push to GitHub
```bash
git push origin main
```

### Step 4: Verify Deployment
Wait ~30 to 60 seconds for GitHub Pages to deploy, then visit:
👉 **[https://hungtk3110.github.io/smartclean-privacy-policy.html](https://hungtk3110.github.io/smartclean-privacy-policy.html)**

---

## 7. Google Play Console Setup Instructions
When submitting or updating Smart Clean: Phone Storage in the Google Play Console:
1. Go to **Policy and programs** &gt; **App content**.
2. Under **Privacy Policy**, click **Start** or **Manage**.
3. In the Privacy policy URL field, enter:
   ```
   https://hungtk3110.github.io/smartclean-privacy-policy.html
   ```
4. Click **Save**.
