# PillPal Senior for iOS Privacy Policy

**Last updated:** November 24, 2026

This policy describes **PillPal Senior** for iOS and iPadOS (`com.jiansun.pillpalsenior`).

## 1. Local-First On-Device Storage

PillPal Senior has no user account system and no developer-operated backend server. Your medication names, dosage instructions, schedules, dose confirmations ("I TOOK IT"), snoozes, activity history, and optional real pill or bottle photos are stored locally on your device in protected storage (`FileProtectionType.complete`) and excluded from unencrypted backups.

If you set an optional 4-digit Caregiver PIN, it is stored solely in the local iOS Keychain on that device.

## 2. Camera and Photo Library

PillPal Senior requests camera access only when you choose to:
- Take a photo of a real pill or medication bottle in **Caregiver View → Schedule → Add/Edit Medication**, or
- Scan a Family Pairing QR code in **Caregiver View → Settings → Family Sharing**.

Existing photos are chosen through Apple's system `PhotosPicker`, which grants the app access only to the photo you select. Real pill photos remain strictly local on the device where they were added and are never uploaded or synced to any server or paired device.

## 3. Spoken Alarms, Live Activities, and Local Notifications

With your permission, PillPal Senior schedules local notifications and, on iOS 26 and later, system **AlarmKit** spoken medication alarms with a Lock-Screen Live Activity countdown (`PillPalAlarmWidget`). All reminder scheduling occurs locally on your device. Reminder delivery depends on iOS settings and permissions and cannot be guaranteed indefinitely.

## 4. Optional End-to-End Encrypted Family Sharing (Apple CloudKit & APNs)

Family Sharing is disabled by default. If you choose to pair a Senior's iPhone and one or more Caregivers' iPhones using a 120-bit cryptographic Family Code (`PP-XXXX-XXXX-XXXX-XXXX-XXXX-XXXX`):
- Two independent cryptographic keys are derived on-device from the Family Code using **HKDF-SHA256**: an opaque routing topic identifier and a 256-bit **AES-256-GCM** encryption key.
- Before any schedule update, dose status, missed-dose alert, or caregiver follow-up leaves your device, it is encrypted and authenticated on-device with **AES-256-GCM**.
- Encrypted records are synced and delivered via **Apple CloudKit** (`iCloud.com.jiansun.pillpalsenior`) and **Apple Push Notification service (APNs)**. CloudKit and APNs push payloads carry generic, zero-PHI notification text (such as *"Attention needed: missed medication or help request. Open PillPal Senior to review."*) and opaque ciphertext. Neither LWS nor third parties can decrypt your Family Code traffic.
- Real pill photos are never included in Family Sharing payloads.

## 5. In-App Purchases (StoreKit 2)

Pairing **2 phones** (1 Senior iPhone + 1 Primary Caregiver iPhone) is included free. The optional **Family Circle (Up to 6 Phones)** upgrade (`com.jiansun.pillpalsenior.familycircle`) is a one-time non-consumable in-app purchase processed by Apple using StoreKit 2. PillPal Senior does not receive or store payment card details. Apple processes payments under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). Once unlocked on a Family Code, the entitlement allows up to 6 paired family phones to receive push notifications and includes a **Restore Family Circle Purchase** action.

## 6. No Analytics, Advertising, or Tracking

PillPal Senior includes no advertising SDKs, no third-party analytics SDKs, and no cross-app tracking (`NSPrivacyTracking = false`).

If you email support, LWS receives your email address and message solely to respond to your inquiry. Do not include sensitive medical records, photos, or passwords in support emails.

## 7. Data Deletion and Your Choices

- You can delete individual medications, remove pill photos, or disconnect from a Family Code at any time inside **Caregiver View → Settings**.
- You can permanently erase all local schedules, history, photos, alarms, notifications, PINs, and pairing state at any time by choosing **Caregiver View → Settings → Delete all data on this iPhone**.
- For privacy questions or assistance, contact [contact.lws.co@gmail.com](mailto:contact.lws.co@gmail.com).

## 8. Important Medical Disclaimer

PillPal Senior is an organizational aid only—not medical advice, a medical device, or an emergency monitoring service. Activity records indicate only that an app interaction occurred on a device; they do not prove medication ingestion or confirm anyone's health or safety. Always follow the instructions of a qualified physician or pharmacist.

## 9. Changes to This Policy

If PillPal Senior's data practices change, this policy will be updated at this URL before or when the change takes effect.
