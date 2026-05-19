# Privacy Policy — PaperScan

**Last updated:** 19 May 2026

This Privacy Policy describes how the **PaperScan – Scan to PDF** mobile application
("PaperScan", "the App", "we", "us") handles your information.

PaperScan is a document-scanner app that captures images from your device's camera,
organizes them into folders on your device, and assembles them into PDF files.

---

## 1. Summary in plain language

- **PaperScan does not have an account system.** You don't sign in. We don't know
  who you are.
- **Everything you scan or import stays on your device.** Scans, PDFs, and folders
  are stored in PaperScan's private storage area. We do not upload your documents
  to any server.
- **The app shows ads** (served by Google AdMob) and uses the Google User
  Messaging Platform (UMP) to obtain consent for personalized ads where required.
  These third-party services collect limited information about your device and
  ad interactions, as described below.
- **The document scanner runs entirely on your device.** The image-recognition
  model is provided by Google ML Kit and operates locally — your camera frames
  are not sent over the network for scanning.

---

## 2. Information the App stores on your device

The following stays **on your device only** and is never transmitted to us or
to any other party by PaperScan:

- **Scanned images** (JPEG files) and **PDFs you create or import**, stored in
  the app's private external storage directory
  (`Android/data/com.app.scantopdf/files/Folders/`).
- **PDFs you export to the public Documents folder** via the "Export to
  Documents" action, stored in `Documents/PaperScan/`.
- **App preferences** stored in private SharedPreferences:
  - Sort order, list/grid view mode
  - "Save-count for interstitial" counter (anonymous, local)
  - First-launch migration banner dismissal flag
  - Consent state cached by Google's UMP SDK

PaperScan does not contain any code that uploads, syncs, or otherwise transmits
your scanned content to any server.

---

## 3. Information collected by third-party services integrated in the App

PaperScan integrates the following third-party services. We do not directly
collect any of the data described below — these services do, on our behalf —
and each service's own privacy policy governs their handling of that data.

### 3.1 Google AdMob (advertising)

PaperScan displays banner and interstitial advertisements served by Google
AdMob. To serve relevant ads and prevent fraud, AdMob's SDK may collect:

- Your device's **Android Advertising ID** (a resettable identifier you control
  in your device Settings under "Privacy → Ads")
- General **IP address** and approximate location (typically country-level)
- **Device information** (model, OS version, app version, language)
- **Ad interaction events** (impressions, clicks)
- **App identifier** (`com.app.scantopdf`)

Google AdMob's data practices are described here:
**https://policies.google.com/technologies/ads**

You can reset or opt out of personalized ads at any time via:
- **Android Settings → Privacy → Ads → "Delete advertising ID" / "Opt out of
  Ads Personalization"** (Android 12 and later), or
- Inside the App, by revisiting the consent dialog (see §3.2).

### 3.2 Google User Messaging Platform (UMP)

To comply with the EU General Data Protection Regulation (GDPR), California
Consumer Privacy Act (CCPA), and similar laws, PaperScan uses the Google UMP
SDK to display a consent form on first launch (in jurisdictions where required)
and record your consent choices locally on the device. UMP communicates with
Google's consent servers to retrieve the appropriate form for your region.

Google's UMP terms and data practices:
**https://support.google.com/admob/answer/10113207**

### 3.3 Google ML Kit Document Scanner

PaperScan uses Google's ML Kit Document Scanner module to detect document edges,
correct perspective, and capture pages. **This module runs entirely on your
device** — the camera frames it processes never leave your device. The module
is delivered to your device via Google Play Services and may be downloaded the
first time you scan.

The ML Kit Document Scanner is part of Google Play Services. Google's relevant
terms:
**https://policies.google.com/terms**

### 3.4 Google Play Services

PaperScan depends on Google Play Services for AdMob, UMP, and the ML Kit
scanner. Google Play Services is part of your Android device and is governed by
Google's privacy policy:
**https://policies.google.com/privacy**

---

## 4. Permissions the App uses

PaperScan declares the following permissions in its manifest:

- **`INTERNET`** — required by Google AdMob to fetch ads.
- **`ACCESS_NETWORK_STATE`** — required by Google AdMob to detect connectivity.
- **Advertising ID permissions** added automatically by the AdMob SDK
  (`com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_*`).

PaperScan **does not** request:

- Camera permission (the document scanner runs in Google Play Services'
  process, which holds the camera permission separately).
- Storage permissions on Android 10 and later (the app uses scoped MediaStore
  and the Storage Access Framework, which require no runtime permissions).
- Location, contacts, microphone, calendar, SMS, phone, or any other
  personally-identifying permission.

---

## 5. Children's privacy

PaperScan is not directed to children under 13 (or the equivalent minimum age
in your jurisdiction). We do not knowingly collect personal information from
children. If you believe a child has used the App and information has been
collected through third-party advertising, contact us (§8) and we will work
with the relevant third party to investigate and address the request.

---

## 6. Data retention and deletion

- **Your documents and folders** persist on your device until you delete them
  through the App (Folder → Delete, Folder Detail → Delete) or uninstall the
  App, which removes all app-private files.
- **Soft-deleted items** are retained in a hidden `.trash/` directory inside
  each folder for up to 30 seconds to support the Undo action, after which they
  are permanently removed.
- **Preferences** are removed when you clear app data
  (Settings → Apps → PaperScan → Storage → Clear data) or uninstall the App.
- **Third-party SDK data** (AdMob, UMP) is governed by Google's retention
  policies — see the links in §3.

---

## 7. Your rights

Depending on your jurisdiction, you may have the following rights regarding
information collected by third-party services integrated in PaperScan:

- **Right to access** the data those services hold about you
- **Right to correct or delete** that data
- **Right to opt out** of personalized advertising (see §3.1)
- **Right to withdraw consent** previously given (you can clear app data and
  re-launch to see the UMP consent form again)

To exercise these rights with respect to Google AdMob or UMP data, follow the
links in §3 to Google's account-level privacy controls. PaperScan itself does
not store personal information that we could provide on request.

---

## 8. Contact

If you have questions about this Privacy Policy, contact us at:

**Email:** rajaipunit1411@gmail.com

You may also raise an issue via the App's listing on Google Play.

---

## 9. Changes to this Policy

We may update this Privacy Policy from time to time. The "Last updated" date
at the top reflects the most recent revision. Material changes will be
announced via the Play Store listing's release notes.
