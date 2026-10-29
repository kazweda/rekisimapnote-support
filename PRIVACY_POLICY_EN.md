---
title: Privacy Policy - Rekisi Map Note
description: Privacy Policy for the Rekisi Map Note app. This document describes how personal data is collected, used, and protected.
version: 0.3
lastUpdated: 2026-10-29
lang: en
updatedLabel: Last updated
assetDepth: 2
---

# Privacy Policy

> This is a draft written before the app's release. Details of in-app purchases (a one-time purchase for cloud sync) will be added when they are introduced.

## Overview

**Rekisi Map Note** (歴史マップノート) is a personal notebook app for writing events of Japanese history onto a map. This policy describes how the app collects, uses, and protects personal data.

---

## 1. Data Collection

### 1.1 Data Stored Locally (User Input and Automatic Records)

**Following the principle of minimal data collection, the app handles only the following:**

| Data Type | Collection Method | Purpose | Storage |
|---------|--------|------|-------|
| Event title, date, memo, source, tags | User input | Managing your notes | Local storage on the device |
| Event place (latitude and longitude on the map) | User input | Showing the event on the map and its historical place name | Local storage on the device |
| Era definitions (names and years) | Initial data (editable by the user) | Showing the era slider | Local storage on the device |
| Sample events | Initial data (editable and deletable by the user) | Showing the events that mark the start of each era | Local storage on the device |
| Identifier (a random string) | Automatic | Telling events apart and importing backups | Local storage on the device |
| Metadata<br/>(created, updated, and moved-to-trash date/time) | Automatic | Managing your notes, the trash, and importing backups | Local storage on the device |

The identifier is created for each event. It does not identify you or your device.

### 1.2 Data We Do Not Collect

The app **never collects** the following:

- ❌ Personally identifiable information such as name, address, or phone number
- ❌ User profiles or credentials
- ❌ Device location (for places on the map, only the position you choose yourself is stored)
- ❌ Device IDs (including for analytics)
- ❌ Usage data (access frequency, time spent, etc.)
- ❌ Cookies or tracking

---

## 2. Data Storage

### 2.1 Local Storage (On the Device)

**Everything you write is stored on your device.**

- **Technology**: SQLite database (drift)
- **Location**: Inside the iOS/Android app sandbox
- **Owner**: You (deleted automatically when the app is uninstalled)

The app does not create backups automatically. To prepare for a device change or failure, please export a backup (Section 4.3).

### 2.2 Cloud Sync

The first released version does not sync with the cloud.

Sync to the app-specific storage of iCloud (iOS) and Google Drive (Android) is planned for the future. Data would go to your own account, never to a server managed by the developer. If sync is added, this policy will be updated and the change announced first.

### 2.3 Network Access for Displaying the Map

To display the map, the app downloads map images from the provider's server (GSI Tiles from the Geospatial Information Authority of Japan are planned).

- Only map images are downloaded. Your notes are never sent
- When downloading, the provider's server receives information such as your IP address and the area of the map being displayed
- Communication uses SSL/TLS

---

## 3. Data Sharing

### 3.1 Sharing with Third Parties

**Your notes are never shared with third parties.** The developer cannot access your notes either.

### 3.2 Advertising and In-App Purchases

**The app does not include advertising.** No mechanism that tracks you, including ad SDKs, is built into the app.

A one-time in-app purchase for cloud sync is planned for the future. The first released version has no in-app purchases.

- Payments are processed by Apple (App Store) / Google (Google Play). The developer does not receive your name or payment information
- When in-app purchases are introduced, the information they handle will be added to this policy before the change is announced

---

## 4. Your Rights

### 4.1 Right of Access

You can access your data in the following ways:

1. **In the app**: View everything you have written at any time
2. **Backup file**: Export all your data in JSON format (Section 4.3)

### 4.2 Right to Erasure

| Method | Scope | Timing |
|-----|------|---------|
| Deleting in the app | Moves selected events (including sample events) to the trash (the content stays on the device) | Immediately |
| Permanently deleting from the trash | Deletes the content of selected events, or of all events in the trash | Immediately |
| Replacing by restoring a backup | Replaces the data on the device with the backup; events not in the backup are moved to the trash | When restoring |
| Uninstalling the app | All local data | When the app is deleted |

**About deleted events**:
- Deleted events are moved to the trash with their content, and can be restored from the trash
- Events permanently deleted from the trash have their content (title, date, place, memo, source, tags) removed from the device and cannot be restored

### 4.3 Right to Data Portability

You can export all your data to a file at any time. The exported file is in JSON format and can be processed with other tools.

When restoring from a backup, you can choose one of the following:

- **Replace**: Replaces the current data with the backup. Events not in the backup are moved to the trash
- **Merge**: Imports the backup while keeping the current data. If the same event exists in both, the one updated more recently is kept

The steps will be added when the feature is released.

---

## 5. Security

### 5.1 Encryption

The app does not implement its own encryption layer. Data protection relies on the mechanisms provided by the OS and platform:

- **Local data**: OS sandbox, device encryption, and screen lock (iOS/Android)
- **When downloading map images**: SSL/TLS

Exported backup files are not encrypted. You choose where to save them (files on the device, cloud storage, etc.), and their protection depends on that location.

### 5.2 Reporting Security Issues

If you discover a security vulnerability, please report it privately to the following email address rather than in a public issue:

```
support (at) netplan.co.jp
```

---

## 6. Compliance with Privacy Laws

### 6.1 Japan's Act on the Protection of Personal Information

The app complies with the following:

| Law | Scope | Status |
|-----|---------|------|
| **Act on the Protection of Personal Information** | Acquisition and use of personal data | ✅ Compliant*1 |
| **GDPR** | Users in the EU | ✅ Compliant*2 |
| **Children's protection** | Under 18 | ✅ No personally identifiable information collected |

*1: Stored locally only, not shared with third parties  
*2: Users in the EU are protected by the same privacy principles described above

### 6.2 Regions Covered by This Policy

- Japan
- All other countries (including regions covered by the GDPR)

---

## 7. Changes to This Privacy Policy

Any changes to this policy will be recorded in this document, and the date of the change will be reflected in "Last updated".

---

## 8. Contact

If you have questions or concerns about privacy or security, please contact us at:

```
support (at) netplan.co.jp
```

---

## 9. Policy Version History

| Version | Date | Changes |
|---------|-----|---------|
| 0.3 | 2026-10-29 | Changed the opening note to the planned in-app purchase. Section 3.2: Stated that the app does not include advertising, and added the planned in-app purchase (a one-time purchase for cloud sync) |
| 0.2 | 2026-10-29 | Section 1.1: Added sample events, the identifier, and the moved-to-trash date/time. Section 2.1: Added the storage technology (SQLite / drift) and that the app does not create backups automatically. Section 2.2: Stated that the first release has no sync, with iCloud / Google Drive planned. Section 4: Added the trash, permanent deletion, JSON export, and replace/merge when restoring. Section 5.1: Stated that backup files are not encrypted |
| 0.1 | 2026-10-29 | Created a pre-release draft |

---

**This policy will be updated as the app develops.**
