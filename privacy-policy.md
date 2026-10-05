# CuppaNote Privacy Policy

Version: 1.0 Draft  
Last updated: October 5, 2026  
Effective date: October 5, 2026  
Personal information controller/operator: bing.xiao
Contact email: [bigtotorouk@gmail.com]  bigtotorouk@gmail.com

This Policy explains how CuppaNote processes your information, which third-party services it uses, and how you can manage your information. It must reflect the version you actually use. We will provide additional notice and follow applicable procedures when introducing new processing purposes or when renewed consent is required by law.

## 1. Information We Process and Why

### 1.1 Coffee Entries and Settings

Information you enter or select—such as coffee type, date and time, rating, size, milk options, price and currency, notes, photos, coffee shops, locations, beans, and brewing templates—is primarily stored on your device. It is used to display and manage entries, produce statistics and recaps, show entries on maps, and generate share content.

The App also stores preferences such as language and currency, and necessary purchase entitlement information, on your device. The App currently does not require a CuppaNote account.

### 1.2 Photos and Camera

When you take or select a photo, the App processes it to provide a preview, generate diary images and thumbnails, and save it in the App's storage. Diary photos are currently not uploaded to PostHog.

### 1.3 Location and Map Searches

If you grant location permission, the App can read the location provided by your device to center the map and search for nearby coffee shops. Coordinates of a shop you select may be saved with your entries on your device. Location information requires careful protection. You may deny permission or turn it off in system settings. This affects location-based features and nearby searches, while entry features that do not require location remain available.

Maps and place searches use Apple MapKit. Apple services process map requests, search terms, and the location or region used for searches under the applicable [Apple Privacy Policy](https://www.apple.com/legal/privacy/). We do not send precise coordinates or search terms to PostHog as custom analytics events.

### 1.4 Purchases and Subscriptions

Payments are processed by the Apple App Store. Through StoreKit, the App receives product, transaction verification, and subscription entitlement information to provide purchased features, check validity, and restore purchases. We do not directly receive your payment card details or Apple Account password.

### 1.5 Usage Analytics and Diagnostics

We integrate the PostHog SDK to understand feature usage, investigate failures, and improve stability. Current collection includes:

- App startup and lifecycle events; coffee save, photo selection, and share image export events; limited states such as whether an entry is being edited, whether it includes a photo, the photo source, and the share template.
- SDK-generated anonymous user and session identifiers, event timestamps, App version and build number, device model and type, operating system and version, screen dimensions, language, time zone, SDK information, and other runtime context.
- Manually reported error categories, codes, and operation stages, as well as exceptions, stack traces, and other diagnostic information in automatic crash reports.
- Connection information, including the IP address involved in network requests. Whether the service stores IP addresses or derives an approximate location depends on the project's actual configuration: [CONFIRM AND COMPLETE].

Anonymous identifiers associate events within the same installation or session. They do not mean that information is completely anonymized or cannot be linked. We currently do not associate these identifiers with a name, phone number, or email address.

Manually reported errors have their original descriptions and supplementary information removed to reduce the risk of transmitting file paths or user content. Automatic crash reports may still contain runtime diagnostic information. We do not intentionally upload diary note text, photos, prices, or precise coordinates for analytics. Session replay, automatic screen view capture, and automatic interface interaction capture are currently disabled. We do not forward all console logs.

The current version initializes the analytics and diagnostics SDK at App startup and does not yet provide an in-app switch to disable it. To request that processing stop or that uploaded data be deleted, contact us using the details below. Required notice, consent, and withdrawal mechanisms must be implemented under applicable law before release.

## 2. System Permissions

| Permission or system capability | Purpose | Your choice |
| --- | --- | --- |
| Camera | Take coffee photos | Deny permission or disable it in system settings |
| System photo picker / photo access | Import photos you select | The system picker generally provides only selected photos; access depends on the system prompt |
| Add images to the photo library | Save share images when using the corresponding feature | Grant or deny permission when prompted |
| Location while using the App | Center the map and find nearby coffee shops | Deny permission, turn it off, or adjust precise location settings |

We do not require permissions unrelated to a feature as a condition of using basic diary functions.

## 3. Third-Party Services and Recipients

| Service | Purpose and information involved | Policy and contact channel |
| --- | --- | --- |
| Apple MapKit | Maps, location regions, and place search requests | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| Apple App Store / StoreKit | Payments, transaction verification, and purchase entitlements | [App Store & Privacy](https://www.apple.com/legal/privacy/data/en/app-store/) |
| PostHog (contracting recipient entity: [CONFIRM]) | Usage analytics and diagnostic information described above | [PostHog Privacy Policy](https://posthog.com/privacy); recipient contact details: [COMPLETE USING THE CONTRACT AND POLICY] |
| A sharing destination you select | Images or export files you choose to share | The recipient's or destination app's own rules apply |

We do not sell your personal information or use the information currently collected for cross-app advertising tracking. For processors acting on our behalf, we will establish processing limits and security requirements under applicable law. Independent processing by third parties is governed by their own policies.

## 4. Storage, Retention, and International Transfers

Entries and photos are primarily stored on your device. Whether a device backup includes them depends on the system and your settings. The current implementation should not be understood as a guarantee of cloud backup or cross-device restoration.

The PostHog project uses an EU ingestion endpoint. Analytics and diagnostic data are transmitted to a service outside mainland China. The specific storage country or region, recipient entity, and scope of subsequent processing are: [CONFIRM USING THE POSTHOG CONTRACT AND PROJECT SETTINGS]. Accordingly, not all data remains exclusively on your device.

Analytics event retention: [COMPLETE WITH THE ACTUAL PROJECT SETTING]. Error and crash data retention: [COMPLETE WITH THE ACTUAL PROJECT SETTING]. We retain information for the shortest period necessary for its purpose and any applicable legal requirements, then delete or anonymize it when the purpose is fulfilled or the retention period ends.

Where mainland China's personal information protection requirements apply, we must provide the required information about the overseas recipient, purposes, methods, information categories, and rights request channels, and fulfill applicable transfer conditions and separate consent requirements. This Policy or the Terms of Use does not replace those procedures.

## 5. Managing Your Information

You can view and edit entries, export data, delete entries, or use “Delete All Data” in the App. The current “Delete All Data” function targets local business records. It does not necessarily remove every image file, system backup, purchase record, or event already uploaded to PostHog.

You can manage camera, photo, and location permissions in iOS settings. Uninstalling the App generally removes its data from your device, but does not automatically cancel subscriptions or delete information already received by third parties or included in system backups.

To request access, correction, deletion of uploaded information, restriction of processing, withdrawal of consent, or information about international transfers, contact [Privacy email]. We will handle requests under applicable law after verifying the request and any necessary identifying information. Because events are not linked to an account, locating anonymous events may require the corresponding anonymous identifier or other necessary details. Please do not send unnecessary information such as diary photos for this purpose.

Response time and request procedure: [COMPLETE WITH AN ACTUAL, IMPLEMENTABLE PROCESS AND TIME FRAME]. Where retention is legally required or deletion is temporarily technically infeasible, we will restrict further processing as required by applicable law.

## 6. Security

We use measures such as system application isolation, access restrictions, and encrypted network connections to protect information, and aim to minimize analytics fields. No technical measure guarantees absolute security. If a security incident requires notification by law, we will fulfill the applicable notification and response obligations.

## 7. Minors

The App is not specifically designed for children under 14. Minors should use it with guidance from a parent or guardian. Where processing requires parental or guardian consent by law, processing must occur only after the necessary consent and safeguards are in place. Please contact us if you believe information has been collected improperly.

## 8. Changes and Contact

We will communicate material changes to this Policy through an in-app notice or another appropriate method. Where new purposes, information categories, recipients, or other changes require renewed consent, we will request it separately as required by law.
