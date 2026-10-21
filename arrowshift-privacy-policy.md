# ArrowShift: Logic Puzzle — Privacy Policy Specification

## 1. Objective
Create a professional, responsive Privacy Policy webpage for the Android mobile game **ArrowShift: Logic Puzzle**, suitable for publishing on GitHub Pages and submitting to Google Play Console.
The page is written in clear, professional English and optimized for mobile devices, tablets, and desktop displays.

---

## 2. Project Information
- **App Name:** ArrowShift: Logic Puzzle
- **Platform:** Android
- **Developer / Publisher Contact:** hungtk.forwork@gmail.com
- **Hosting Platform:** GitHub Pages
- **Filename:** `arrowshift-privacy-policy.html`
- **Root Repository:** `https://github.com/HungTk3110/hungtk3110.github.io`
- **Expected Public URL:** [https://hungtk3110.github.io/arrowshift-privacy-policy.html](https://hungtk3110.github.io/arrowshift-privacy-policy.html)
- **Root Index Preserved:** `index.html` (maintained for Free Learn Piano without modification)
- **AdMob Status:** AdMob publisher identity verified via root `app-ads.txt` (`pub-7692599728154289`).

---

## 3. Design & Architecture Characteristics
- **Color Palette & Visuals:** Clean light background (`#f8fafc`), clean surface containers (`#ffffff`), and subtle indigo accents (`#4f46e5`, `#6366f1`, `#eef2ff`) inspired by modern logic puzzle aesthetics.
- **Typography & Layout:** System font stack for zero-latency loading, high-contrast accessible typography (WCAG AA/AAA compliant), centered responsive container (`max-width: 860px`).
- **Semantic Structure:** Valid HTML5 with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
- **Navigation:** Table of Contents with smooth anchor links to all sections.
- **Self-Contained:** Zero external runtime JS libraries or heavy dependencies, rendering natively in any browser or embedded webview.

---

## 4. Privacy Policy Sections Included
1. **Introduction:** Identification of ArrowShift: Logic Puzzle, scope of policy, and developer contact.
2. **Information We Collect:**
   - *Information Provided Directly:* Contact email & user-submitted feedback.
   - *Information Collected Automatically:* Technical telemetry, device identifiers (GAID), operating system version, and approximate network location.
3. **Advertising (Google AdMob):** Disclosures on advertising identifiers, personalized vs non-personalized ads, regional consent frameworks (GDPR/UMP), and link to [Google Advertising & Privacy Policy](https://policies.google.com/technologies/ads).
4. **Analytics & Diagnostics:** App performance, ANR tracking, and crash diagnostics.
5. **How We Use Information:** Legitimate operational purposes (gameplay, stability, monetization, user support, fraud prevention).
6. **Third-Party Services:** Direct disclosures and links for Google Play Services and Google AdMob.
7. **Data Retention & Security:** Explains that gameplay data is stored locally on-device, third-party retention cycles, and reasonable security protocols (HTTPS/TLS) without absolute claims.
8. **Children's Privacy:** General audience classification (not directed at children under 13/16) and contact procedure for parental inquiries.
9. **Your Privacy Rights:** GDPR and CCPA/CPRA rights breakdown, including Android advertising ID reset steps and developer inquiry instructions.
10. **International Data Transfers:** Overview of global cloud infrastructure and Standard Contractual Clauses (SCCs).
11. **Changes to This Policy:** Policy update notifications and effective date tracking.
12. **Contact Us:** Clear contact box specifying app name, platform, and direct developer contact email (`hungtk.forwork@gmail.com`).

---

## 5. Developer Confirmation Checklist (Action Items for Developer)
Before releasing or updating the Google Play Data Safety form in Play Console, confirm the following items against your actual Android project build files (`build.gradle`, `AndroidManifest.xml`):

| # | Item | Status / Verification Needed |
|---|------|------------------------------|
| 1 | **Legal Entity Name** | Currently displayed as the developer of ArrowShift: Logic Puzzle. If you have an official studio name (e.g. registered company name), you can update the header/footer text. |
| 2 | **AdMob Integration** | Confirmed presence of `app-ads.txt` with AdMob publisher ID `pub-7692599728154289`. Confirm if mediation or additional ad networks (e.g., Unity Ads, AppLovin) are integrated. |
| 3 | **Analytics SDKs** | Confirm if Firebase Analytics (`com.google.firebase:firebase-analytics`) or Firebase Crashlytics is included in `build.gradle`. If neither is used, Google Play Console automatic vitals still apply. |
| 4 | **In-App Purchases (IAP)** | If ArrowShift offers any in-app purchases (e.g., ad removal or hint packs) via Google Play Billing, ensure that Google Play Billing is added under Third-Party Services. |
| 5 | **Target Age Group** | In Google Play Console > App Content > Target Audience and Content, ensure the target age matches the policy (not directed to children under 13). |
| 6 | **Data Safety Form** | Ensure choices in Google Play Console Data Safety section correspond directly to the disclosures in this Privacy Policy. |

---

## 6. GitHub Pages Deployment Instructions

### Step 1: Check Git Status
Run:
```bash
git status
```
You should see `arrowshift-privacy-policy.html` and `arrowshift-privacy-policy.md` as untracked files. Note that `index.html` and `app-ads.txt` are unchanged.

### Step 2: Stage and Commit the Files
```bash
git add arrowshift-privacy-policy.html arrowshift-privacy-policy.md
git commit -m "Add Privacy Policy for ArrowShift: Logic Puzzle"
```

### Step 3: Push to GitHub
```bash
git push origin main
```

### Step 4: Verify Deployment
Wait ~30 to 60 seconds for GitHub Pages to deploy, then visit:
👉 **[https://hungtk3110.github.io/arrowshift-privacy-policy.html](https://hungtk3110.github.io/arrowshift-privacy-policy.html)**

---

## 7. Google Play Console Setup Instructions
When submitting or updating ArrowShift: Logic Puzzle in the Google Play Console:
1. Go to **Policy and programs** &gt; **App content**.
2. Under **Privacy Policy**, click **Start** or **Manage**.
3. In the Privacy policy URL field, enter:
   ```
   https://hungtk3110.github.io/arrowshift-privacy-policy.html
   ```
4. Click **Save**.
