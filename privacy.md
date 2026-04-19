---
title: Privacy Policy — Do The Wrong Thing
---

# Privacy Policy — Do The Wrong Thing

**Effective date:** April 19, 2026
**Last updated:** April 19, 2026

## 1. Summary

*Do The Wrong Thing* is a single-player narrative adventure game. It does not require an account, does not ask for any personal details, and does not sell or trade your data. This page explains what data is handled, why, and your rights.

## 2. Who we are

The app is developed and distributed by:

- **Name:** Mihăiță-Bogdan Nistor, acting as a private individual (sole developer)
- **Contact:** mihaita.nistor@gmail.com

For the purposes of the EU General Data Protection Regulation (GDPR), this person is the "data controller".

## 3. What the app does

You create a character, make story choices, and see the consequences. Your progress is saved on your device. There is no sign-in, no cloud save, no friends list, no messaging, and no game server.

## 4. Data stored on your device only

The following data is stored locally on your device — in your web browser's local storage on the web version, and in the Android system's app storage on the mobile version. It never leaves your device unless you explicitly export it via the in-game Settings screen:

- **Game save:** the character name you enter, race / class / gender, your progress, decision flags, and items in your inventory.
- **Preferences:** text size, haptic feedback toggle, music / sound / narration toggles, reduced motion toggle, font choice.
- **Error logs:** technical messages if the app crashes. You can view and clear these from Settings.
- **Gameplay analytics events:** anonymous events (e.g. `game_started`, `route_chosen`, `paywall_shown`, `game_completed`). Capped at the most recent 500 entries.
- **Purchase state:** if you buy the "Unlimited Replay" in-app purchase, a local flag plus an integrity hash is stored so the app knows you've unlocked it.
- **Session counter** and **rating prompt dismissal flag**, used to decide when to show the one-time review prompt.

You can **export your save** (JSON file) from the in-game Settings screen. To delete all local data, either use your Android device's **Settings → Apps → Do The Wrong Thing → Storage → Clear storage**, or uninstall the app.

## 5. Data sent to third parties

The **web version** of the app does not transmit any data to any third party. Everything stays in your browser.

The **Android version** uses the following Google services:

### 5.1 Google Play Billing

If you buy the "Unlimited Replay" in-app purchase, Google Play handles the transaction end-to-end. The app never sees your payment card, billing address, or Google account details — it only receives a signed receipt confirming the purchase. Google's privacy policy applies: <https://policies.google.com/privacy>.

### 5.2 Firebase Analytics (a Google service)

**This is off by default.** Firebase Analytics is only active if you have explicitly enabled it — either by tapping **"Sure"** on the one-time prompt shown on the title screen, or by turning on **Settings → Privacy → Share anonymous analytics**. You can turn it off again at any time in the same place. If you never enable it, nothing is ever transmitted to Firebase.

When enabled, the Android version mirrors the same anonymous gameplay events listed in Section 4 to Firebase Analytics. This helps the developer understand aggregated player behavior (e.g. which story routes players reach, where players drop off) to improve the game.

**What is sent per event:**
- The event name (e.g. `game_started`, `route_chosen`)
- Non-personal gameplay parameters: chosen race, class, gender, screen size, orientation, device language code, and the story route or ending identifier.

The character name and any other free-text input you type are **not** transmitted.

**Data automatically collected by the Firebase SDK:**
- A pseudonymous **Firebase Instance ID** (a random identifier unique to your app install; not tied to your Google account, resets if you reinstall).
- **Approximate location:** country and city derived from your IP address. Your IP address itself is not retained long-term by Google.
- **Device info:** model, Android version, language, country, app version.
- **Session data:** session starts, app first-open, app updates.

The app does **not** collect the Android Advertising ID (the `AD_ID` permission is not declared in the app manifest).

Firebase processes this data on the developer's behalf under Google's data processing terms: <https://firebase.google.com/terms/data-processing-terms>.

### 5.3 Google Play Store (the platform itself)

Google Play — independent of this app — collects installation and basic diagnostics for any app installed from the Play Store. This is governed by Google's own policies, not by this app.

## 6. What is **not** collected

- No name, email, phone number, postal address, date of birth, or identity documents are requested or stored
- No precise (GPS) location
- No access to contacts, photos, camera, microphone, or files
- No web browsing history
- No advertising identifier
- No tracking across other apps or websites
- No data is ever sold, rented, or shared with data brokers or advertisers

## 7. Purposes and legal bases (GDPR Art. 6)

| Data | Purpose | Legal basis |
|------|---------|-------------|
| Game saves & preferences (local) | Let you play and keep your progress | Contract — Art. 6(1)(b) |
| Error logs (local) | Diagnose crashes | Legitimate interests — Art. 6(1)(f): app stability |
| Purchase state | Deliver the feature you paid for | Contract — Art. 6(1)(b) |
| Firebase Analytics events (Android) | Understand aggregate player behavior to improve the game | **Consent — Art. 6(1)(a).** Off by default; activated only by your explicit opt-in. Withdrawable anytime in Settings → Privacy. |

## 8. Data retention

- **Local data:** kept until you clear app storage in Android settings, uninstall the app, or clear your browser's storage for the web version.
- **Firebase Analytics:** retained by Google for **2 months** for user-level identifiers and up to **14 months** for aggregated event data (Firebase defaults), after which it is automatically deleted.

## 9. Your rights (GDPR — applies to EU / EEA / UK residents)

You have the right to:

- **Access** data processed about you
- **Rectify** inaccurate data
- **Erase** your data ("right to be forgotten")
- **Restrict** or **object to** processing
- **Data portability** — receive your data in a machine-readable format
- **Withdraw consent** where processing relies on consent
- **Lodge a complaint** with your national data protection authority (Romania: **ANSPDCP** — <https://www.dataprotection.ro>)

### How to exercise these rights

- **Your local game data:** open the app's **Settings** screen → **Export Save Data** to receive a copy. To delete, clear app storage via Android Settings → Apps, or uninstall.
- **Withdraw consent / stop future analytics collection:** open the in-game **Settings → Privacy** and toggle **Share anonymous analytics** to Off. This takes effect immediately; no further events will be sent.
- **Firebase Analytics data already collected:** email **mihaita.nistor@gmail.com** stating you'd like your Firebase Analytics data deleted, and include the approximate date range you played. Because Firebase data is tied only to a pseudonymous install identifier (not to you personally), blanket deletion of all data associated with your current install can be requested via the Firebase User Deletion API; this will be done within 30 days.

## 10. Children

The app is not directed at children under 13 (or under 16 in the EU). It does not knowingly collect data from children. If you believe a child has provided data through the app, email **mihaita.nistor@gmail.com** and the data will be deleted.

## 11. International transfers

Data processed by Firebase Analytics and Google Play is handled on Google's infrastructure, which may process data in the United States and other countries. Google is self-certified under the EU-US Data Privacy Framework and uses Standard Contractual Clauses for transfers from the EU / UK. Details: <https://business.safety.google/privacy/>.

## 12. Security

Local data is protected by your device's operating system sandbox. Data in transit to Firebase is encrypted over TLS (HTTPS). Because there is no account system, there are no passwords or login credentials at risk.

## 13. Changes to this policy

Material changes will be announced on this page and, where practical, in-app on first launch after an update. The effective date at the top will be updated.

## 14. Contact

Questions? Email **mihaita.nistor@gmail.com**.
