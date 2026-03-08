---
layout: default
title: Privacy Policy
permalink: /Antzua/privacy/en/
---

# Privacy Policy

> *This document was translated from Traditional Chinese by machine translation. (2026-03-08)*

**Effective Date: March 1, 2026**

Antzua takes your privacy very seriously. This policy explains how we collect, use, and protect your information.

---

## 1. Data Collection Scope

This app collects and uses the following information:

- **Location Data**: Used for route planning, navigation, and address search. Accessed only after your authorization. During navigation, location is continuously accessed in the background (configured with `location` Background Mode in Info.plist). Upon launch, the app determines your service region via GPS or system language.
- **Camera**: Used for scanning and recognizing addresses, names, and phone numbers. Activated only after your authorization. All image recognition is performed on-device using Apple Vision Framework. Images and recognition results are never uploaded to any server.
- **Notification Permission**: Used for navigation background notifications. When the app is in the background or the screen is locked, local notifications alert you to navigation events such as upcoming turns and arrivals. Notification content is generated entirely on-device and does not go through any remote push server.
- **Address Data**: Addresses and place names you manually enter or scan are stored locally on your device.
- **Subscription Status**: Verified through Apple StoreKit 2 for subscription eligibility. This app does not store any payment information.
- **Voice Output**: Voice navigation uses Apple AVSpeechSynthesizer to synthesize speech on-device. No data is transmitted externally. During navigation, voice playback continues in the background (configured with `audio` Background Mode in Info.plist).

## 2. How We Use Your Data

- **Route Planning**: Uses your location and entered addresses to calculate optimal routes and waypoint ordering via Google Routes API.
- **Place Search**: Uses Google Places API to provide address search and autocomplete functionality. During searches, only the search keywords, your region's country code, and approximate location are transmitted.
- **Turn-by-Turn Navigation**: This app features built-in 2D/3D turn-by-turn navigation using Apple MKDirections to calculate real-time navigation routes and turn instructions, with GPS for real-time position tracking. You can also send destinations to your preferred external navigation app (Apple Maps, Google Maps, or Waze).
- **Region Detection**: Upon launch, the app determines your service region (Taiwan, Japan, South Korea, Singapore) via GPS reverse geocoding or coordinate boundary checking. This is used to configure search scope, voice language, address format, and other regional settings. If you are not in a supported service region, a notice screen will be displayed.

## 3. Data Storage

All address and trip data is stored locally on your device (using Apple SwiftData). If you are signed in to iCloud, data is automatically synced to your iCloud account via Apple CloudKit for sharing across devices with the same Apple ID. Synced data is protected by Apple's iCloud privacy policy. This app cannot access your iCloud account information.

### Local Cache

This app caches the following data on your device to reduce redundant network requests:

- **Place Details Cache**: Place information returned by Google Places API (expires after 30 days, maximum 500 entries), stored in the app's private directory.
- **Route Cache**: Route results calculated by MKDirections (expires after 7 days, maximum 10,000 entries), stored in the app's private directory.

These caches are retained with iCloud backups and can be cleared via "Settings → Data Management → Clear All Data."

### Deleting Data

Deleting the app only removes local data on that device; synced data on iCloud is not affected. To completely delete all data (including iCloud and all devices), go to "Settings → Data Management → Clear All Data" before deleting the app.

If you are not signed in to iCloud, data is stored locally on your device only, and deleting the app removes all data.

## 4. Third-Party Services

This app uses the following third-party services for route planning and place search:

- **Google Places SDK for iOS**: Used for address search and autocomplete. Only search keywords, country code, and approximate location are transmitted.
- **Google Routes API**: Used for route calculation and waypoint ordering. Only address coordinates and transport mode are transmitted.
- **Apple MapKit / MKDirections**: Used for map display, route rendering, and turn-by-turn navigation. Governed by Apple's privacy policy.
- **Apple StoreKit 2**: Used for subscription management and verification. Payments are processed by Apple.
- **Apple CloudKit**: Used for iCloud data sync. Governed by Apple's iCloud privacy policy.
- **Apple AVSpeechSynthesizer**: Used for voice navigation. Speech synthesis is performed entirely on-device.

Google services are governed by their privacy policy. See [Google Privacy Policy](https://policies.google.com/privacy).

## 5. Data We Do Not Collect

This app does not collect the following information:

- **Personal Identification Data**: We do not collect names, email addresses, phone numbers, etc.
- **Usage Behavior Tracking**: We do not use any analytics or tracking SDKs.
- **Payment Information**: All subscription payments are processed by the Apple App Store. This app cannot access your payment details.
- **Navigation Tracks**: We do not record or upload your driving routes or location history.

## 6. Children's Privacy

This app is not designed for children under 13 and does not proactively collect personal information from children.

## 7. Policy Updates

This privacy policy may be updated with app updates. Significant changes will be notified within the app. Continued use of this app indicates your agreement to the updated policy.

## 8. Contact Us

If you have any questions or suggestions about this privacy policy, please leave a comment on the App Store and we will respond as soon as possible.

---

Online version of this privacy policy: [https://mingyuan-tech.github.io/AntzuaDocs/privacy](https://mingyuan-tech.github.io/AntzuaDocs/privacy)
