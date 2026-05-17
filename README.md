# SideContacts Privacy Policy

Last updated: May 2026

SideContacts is designed to help you manage secondary and temporary contacts privately and securely. This policy explains what data the app accesses, how it is used, and how it is protected.

---

## Data We Store

Contacts you create inside SideContacts are stored locally on your device in an app-only database. This includes:

* Name
* Phone number
* Notes
* Tag/category
* Favorite and archive status

This data remains on your device unless you explicitly enable cloud backup.

---

## Cloud Backup (Optional)

Cloud backup is entirely optional and disabled by default.

If you choose to enable it:

* You sign in using your Google account via Firebase Authentication
* Your contact data is encrypted with AES-256 before upload
* Data is never stored in plain text in cloud storage
* Backups are securely stored using Firebase Firestore

Backed up fields include contact names, phone numbers, notes, and contact metadata.

You can disable backup, delete your cloud backup, or permanently delete your account and associated cloud data at any time from within the app settings.

---

## Phone Permission (READ_PHONE_STATE)

SideContacts requests READ_PHONE_STATE to identify incoming calls from numbers saved in the app.

* On Android 9 and below: if an incoming number matches a saved contact, a local notification is shown
* On Android 10 and above: the incoming number is not accessible to apps; this feature silently does nothing
* No call data is recorded, stored, or transmitted
* This feature can be disabled in Settings

The app uses the system dialer (ACTION_DIAL) for outgoing calls. No CALL_PHONE permission is requested or used.

---

## WhatsApp Integration

The app can open a WhatsApp chat using a saved phone number via a standard system URL. No WhatsApp messages are read, stored, or transmitted by the app.

---

## Data Sharing

SideContacts does not sell your data.

Your data is not shared with third parties except as required for the features you explicitly use:

* **Firebase Authentication** — used only for Google Sign-In when backup is enabled
* **Firebase Firestore** — used only to store your encrypted backup data

---

## Your Control

You are in full control of your data:

* Delete any contact at any time
* Disable cloud backup in Settings
* Delete your cloud backup at any time
* Permanently delete your account and associated cloud data
* Sign out from backup services at any time
* Uninstall the app to remove all local data from your device

---

## Changes to This Policy

This policy may be updated to reflect app changes or legal requirements. The "Last updated" date at the top will always reflect the most recent revision.

---

## Contact

Questions or support requests:

[sidecontacts.app@gmail.com](mailto:sidecontacts.app@gmail.com)
# sidecontacts-privacy
