---
title: Data Deletion Request — Do The Wrong Thing
---

# Data Deletion Request — Do The Wrong Thing

**Last updated:** May 17, 2026

This page explains how to delete your data from *Do The Wrong Thing*. Most of your data is stored locally on your device. The only data that ever leaves your device is anonymous analytics events (if you turned them on) and in-app purchase records (handled by Google Play).

## 1. On-device data — delete it yourself, immediately

The following is stored only on your device: game saves, character names, preferences, error logs, and your local analytics-event log.

**To delete it:**

- **Android:** open **Settings → Apps → Do The Wrong Thing → Storage → Clear storage**. All local data is removed immediately.
- **Or:** uninstall the app. All local data is removed when the app is uninstalled.

**Want a copy first?** In the app, open **Settings → Export Save Data** to save a JSON copy to your device's `Documents/` folder before you delete.

## 2. Anonymous analytics data (Google Firebase) — request by email

Firebase Analytics events are **only collected if you explicitly turned on** *"Share anonymous analytics"* in the in-game Settings. The data is tied to a pseudonymous app-install identifier, not to your name, email, or any personally identifying information.

**To stop further collection immediately:** open the app and toggle **Settings → Share anonymous analytics → Off**. No new events will be sent.

**To request deletion of analytics data already collected:** email **probablyfinegames@gmail.com** with:

- **Subject:** `Data deletion request`
- The approximate date range you played the game
- Your country (helps narrow the Firebase data set)
- Any other detail that might help identify your install (optional)

We will submit a blanket deletion request to Google via Firebase's User Deletion API within **30 days**, as required by GDPR.

## 3. In-app purchase data (Google Play) — contact Google

If you bought *Unlimited Replay*, the purchase record is held by Google Play, not by us. We only receive a signed receipt confirming the purchase. To request deletion of payment-related data, contact Google directly:

- <https://support.google.com/googleplay/>

## Contact

Mihăiță-Bogdan Nistor, trading as **Probably Fine Games**
Email: probablyfinegames@gmail.com
Country: Romania

For the full policy on what data is processed and your GDPR rights, see the [Privacy Policy](./privacy).
