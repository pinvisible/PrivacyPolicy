# Privacy Policy — PaperScan

**Last updated:** 12 October 2026

This Privacy Policy describes how the **PaperScan - Document Scanner** mobile application
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
- **The document scanner and text recognition run entirely on your device.**
  Both models are provided by Google ML Kit and operate locally — your camera
  frames and your scans are not sent over the network for scanning or for
  reading text.
- **The app reports crashes and basic usage statistics** to Google Firebase
  (Crashlytics and Analytics) so we can fix bugs and see which features are used.
  This never includes the content of your scans.
- **Removing ads is an optional one-time purchase** processed entirely by Google
  Play. PaperScan never sees your payment details.

---

## 2. Information the App stores on your device

The following stays **on your device only** and is never transmitted to us or
to any other party by PaperScan:

- **Scanned images** (JPEG files) and **PDFs you create or import**, stored in
  the app's private external storage directory
  (`Android/data/com.app.scantopdf/files/Folders/`).
- **PDFs you export to the public Documents folder** via the "Export to
  Documents" action, stored in `Documents/PaperScan/`.
- **Recognized text** produced by the optional "Recognize text" feature, stored
  as a small hidden file next to the scan or PDF it belongs to (inside the same
  private folder), and — for PDFs — as an invisible text layer inside the PDF
  itself so the file is searchable in other apps too. It is deleted together
  with the file.
- **Signatures you draw** with the optional "Sign" feature, stored as small
  vector files in the app's private internal storage. They are used only to
  stamp the signature onto PDF pages you choose, are never transmitted, and can
  be deleted individually from the signature picker (long-press) or all at once
  by clearing the app's data or uninstalling.
- **App preferences** stored in private SharedPreferences:
  - Sort order, list/grid view mode
  - "Save-count for interstitial" counter (anonymous, local)
  - First-launch migration banner dismissal flag
  - Consent state cached by Google's UMP SDK
  - Whether you have purchased "Remove ads" (a yes/no flag)
  - Your favorite (starred) folders and the last folder you used
  - Whether "Recognize text automatically" is switched on
  - Whether "Tips every few days" is switched on, and which tip comes next

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

### 3.3 Google ML Kit — Document Scanner and Text Recognition

PaperScan uses two Google ML Kit modules:

- **Document Scanner** detects document edges, corrects perspective, and
  captures pages.
- **Text Recognition** reads the printed text in a scan or PDF page (Latin and
  Devanagari scripts — for example English and Hindi) when you use "Recognize
  text" or switch on "Recognize text automatically". The recognized text makes
  your documents searchable inside the App and lets you copy or share it.

**Both modules run entirely on your device** — the camera frames and page
images they process never leave your device, and the recognized text is stored
only on your device (see §2). The modules are delivered via Google Play Services
and may be downloaded the first time you use them.

ML Kit is part of Google Play Services. Google's relevant terms:
**https://policies.google.com/terms**

### 3.4 Google Play Services

PaperScan depends on Google Play Services for AdMob, UMP, the ML Kit scanner
and text recognition, Google Play Billing, Firebase, and the in-app review prompt. Google Play Services
is part of your Android device and is governed by Google's privacy policy:
**https://policies.google.com/privacy**

### 3.5 Google Firebase — Crashlytics and Analytics

PaperScan uses two Google Firebase services:

- **Crashlytics** collects a report when the App crashes: the stack trace, device
  model, OS version, app version, free memory and storage at the time, and a
  Firebase-generated installation identifier. We use these reports only to find
  and fix bugs.
- **Analytics** records anonymous usage events — which screens are opened and
  which features are used (for example that a scan was saved, shared, zipped or
  searched for, and how many pages or files were involved — never what they
  contain), whether a tip, the guide, an ad or the Remove-ads purchase was shown
  or used, a few App settings (such as theme, PDF page size and whether text
  recognition is on), and the rough size of your library in bands (for example
  "6–20 files"). It also records how often the App is used, app version, device
  model, OS version, language, and approximate (country-level) location derived
  from IP address. We use this to understand which features matter and where to
  improve the App.

Neither service receives the content of your scans, your file names, or your
folder names. Firebase identifies your installation with an app-instance ID that
is separate from the Advertising ID; it is reset when you clear the App's data
or uninstall.

Firebase's data practices:
**https://firebase.google.com/support/privacy**

### 3.6 Google Play Billing (optional "Remove ads" purchase)

PaperScan offers a one-time in-app purchase that removes advertising. The purchase
is processed entirely by Google Play: PaperScan never sees your payment method,
card number, or billing address. The App receives only a purchase confirmation
from Google Play, which it stores locally to remember that ads should stay off.
Purchase history, receipts, and refunds are handled in your Google Play account.

Google Play's terms and privacy policy:
**https://play.google.com/about/play-terms/** and
**https://policies.google.com/privacy**

---

## 4. Permissions the App uses

PaperScan declares the following permissions in its manifest:

- **`INTERNET`** — required by Google AdMob to fetch ads, by Firebase to send
  crash and usage reports, and by Google Play Billing.
- **`ACCESS_NETWORK_STATE`** — required by Google AdMob to detect connectivity.
- **`POST_NOTIFICATIONS`** (Android 13 and later) — lets the App show an optional
  tip about one of its features about once every 3 days. Asked only after you save
  your first scan; you can say no, or turn tips off later in Settings → Notifications.
  The tips are created on your device; nothing is downloaded or sent to show them.
- **`com.android.vending.BILLING`** — added automatically by the Google Play
  Billing library for the optional "Remove ads" purchase.
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
- **Saved signatures** persist until you delete them in the signature picker,
  clear app data, or uninstall the App. A signature already stamped onto a PDF
  is part of that PDF and goes wherever you share it.
- **Preferences** are removed when you clear app data
  (Settings → Apps → PaperScan → Storage → Clear data) or uninstall the App.
- **Third-party SDK data** (AdMob, UMP, Firebase, Play Billing) is governed by
  Google's retention policies — see the links in §3. Crashlytics crash reports
  are retained by Google for 90 days.

---

## 7. Your rights

Depending on your jurisdiction, you may have the following rights regarding
information collected by third-party services integrated in PaperScan:

- **Right to access** the data those services hold about you
- **Right to correct or delete** that data
- **Right to opt out** of personalized advertising (see §3.1)
- **Right to withdraw consent** previously given (you can clear app data and
  re-launch to see the UMP consent form again)

To exercise these rights with respect to Google AdMob, UMP, or Firebase data,
follow the links in §3 to Google's account-level privacy controls. PaperScan itself does
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
