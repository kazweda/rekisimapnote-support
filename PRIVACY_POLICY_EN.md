---
title: Privacy Policy - Rekisi Map Note
description: Privacy Policy for the Rekisi Map Note app. This document describes how personal data is collected, used, and protected.
version: 0.1
lastUpdated: 2026-10-29
lang: en
updatedLabel: Last updated
assetDepth: 2
---

# Privacy Policy

> This is a draft written before the app's release. It will be updated once storage, sync, advertising, and in-app purchases are decided.

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
| Metadata<br/>(created and updated date/time) | Automatic | Managing your notes | Local storage on the device |

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

- **Location**: Inside the iOS/Android app sandbox
- **Owner**: You (deleted automatically when the app is uninstalled)

### 2.2 Cloud Sync

As of this draft, the app does not sync with the cloud. If sync is introduced, this policy will be updated and the change announced first.

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

As of this draft, the app has no advertising and no in-app purchases. If they are introduced, the information they handle and the providers' privacy policies will be added to this policy before the change is announced.

---

## 4. Your Rights

### 4.1 Right of Access

You can view everything you have written in the app at any time.

### 4.2 Right to Erasure

| Method | Scope | Timing |
|-----|------|---------|
| Deleting in the app | Selected events (including sample events) | Immediately |
| Uninstalling the app | All local data | When the app is deleted |

### 4.3 Right to Data Portability

A feature to export your notes to a file is planned. The format and steps will be added when the feature is released.

---

## 5. Security

### 5.1 Encryption

The app does not implement its own encryption layer. Data protection relies on the mechanisms provided by the OS and platform:

- **Local data**: OS sandbox, device encryption, and screen lock (iOS/Android)
- **When downloading map images**: SSL/TLS

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
| 0.1 | 2026-10-29 | Created a pre-release draft |

---

**This policy will be updated as the app develops.**
