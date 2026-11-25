# PillPal Senior for iOS Support & Two-Phone Family Care Guide

For help with **PillPal Senior**, email [contact.lws.co@gmail.com](mailto:contact.lws.co@gmail.com).

Please include your iPhone or iPad model, iOS version, PillPal Senior version, and a brief description of the issue. Do not email sensitive medical records, pill photos, passcodes, or payment details.

---

## Why Installing PillPal Senior on Both Phones Is the Best Way to Care for a Senior

PillPal Senior is designed from the ground up to work as a **two-phone (or multi-family) care system**—installed on **both the Senior's iPhone and the Caregiver's iPhone**:

### 1. On the Senior's iPhone: Calm, High-Contrast Simplicity (**Senior View**)
- **Zero Clutter:** The Senior's iPhone stays in **Senior View**, showing only today's medications in extra-large, high-contrast cards with Dynamic Type support up to accessibility size AX5.
- **Visual Pill Verification + Real Pill Photos:** Each card displays a clear pill shape and color illustration alongside an optional **real photo of the actual pill or bottle** taken with the camera, helping seniors visually confirm the right medication before taking it.
- **Spoken Lock-Screen Alarms (iOS 26+) & State-Aware Read Aloud:** On iOS 26+, system AlarmKit alarms speak a medication reminder even when the iPhone is locked, with Lock-Screen **Stop** and **Snooze (15 min)** controls. Inside the app, tapping **Read Aloud** speaks the medication name, purpose, and instructions—and if a dose was already taken, it explicitly states *"Recorded taken at [time]. Do not take [Medication] again for this dose"* to help prevent double-dosing.
- **One-Tap Confirmation:** Tapping the large green **"I TOOK IT"** button logs the exact confirmation time and quietly syncs with the family.

### 2. On the Caregiver's iPhone: Peace of Mind Without Hovering (**Caregiver View**)
- **Smart Alert Filtering (No Notification Fatigue):** Routine **"I TOOK IT"** confirmations sync silently in the background so caregivers can check progress at a glance without constant chimes. Audible Apple Push notifications are sent **only when attention is genuinely needed**:
  1. A scheduled dose passes its grace deadline without being confirmed (**Missed-Dose Alert**), or
  2. The senior taps **"Need help with this dose"** (e.g., *"Not sure whether taken"* or *"Pill looks different"*).
- **Remote Schedule Management:** Caregivers can add or edit medications, adjust grace periods, and review 7-day adherence history from their own iPhone, and changes sync automatically to the Senior's iPhone.

### 3. Coordinated Multi-Person Care (**Family Circle — Up to 6 Phones**)
- **Free for 2 Phones (1 Senior + 1 Primary Caregiver):** Pairing a Senior's iPhone and one Primary Caregiver's iPhone is completely free.
- **Family Circle ($1.99 One-Time Unlock for Up to 6 Phones):** One caregiver can unlock **Family Circle** once for **$1.99** on the Family Code so up to **6 family phones** (spouse, adult children, siblings, or a home caregiver) all receive missed-dose push notifications.
- **Shared Follow-Up Claiming ("I'll Check In"):** When a missed-dose or help notification arrives on multiple family phones, one family member can tap **"I'll check in"** and log a resolution note (for example, *"Called Mom — she took it with breakfast"*). Every other family member's iPhone updates immediately so nobody makes duplicate phone calls or wonders if someone checked in.

---

## Step-by-Step: How to Pair Two or More iPhones

1. **On the Senior's iPhone:**
   - Tap **Caregiver** at the top of the screen and hold the gate button for 1.2 seconds (or tap the accessible entry button).
   - Open the **Settings** tab → scroll to **Family Sharing** → tap **Create Family Code**.
   - Ensure **Push Notifications** and **iCloud** are enabled on the iPhone.
2. **On the Caregiver's iPhone:**
   - Install **PillPal Senior**, switch to **Caregiver View → Settings → Family Sharing**.
   - Tap **Scan** to scan the QR code displayed on the Senior's iPhone (or copy and paste the `PP-XXXX-...` Family Code) and tap **Connect to that Family Code**.
   - Tap **Send Test Update** to confirm two-phone Apple Push delivery is active.
3. **Adding Additional Caregivers (3 to 6 Phones):**
   - In **Settings → Family Sharing**, tap **Unlock Family Circle — $1.99 One-Time (Up to 6 Phones)** on any paired iPhone, then scan or enter the same Family Code on up to 6 family iPhones.

---

## Common Questions

**Why didn't the other phone receive a push notification when I tapped "I TOOK IT"?**  
By design! Routine *"I TOOK IT"* confirmations sync quietly in the background so caregivers aren't interrupted several times a day when everything is on track. Audible push notifications fire when a dose is **missed** after its grace period, when the senior reports a **dose concern**, or when you tap **Send Test Update** in Settings.

**A 3rd family phone connected, but push alerts say "Waiting for Family Circle unlock."**  
The free tier includes 2 paired phones (1 Senior + 1 Caregiver). Tap **Unlock Family Circle ($1.99 One-Time)** on any paired phone (or tap **Restore Family Circle Purchase** if you already bought it), or tap **Remove** next to an old/replaced iPhone in the **Connected Family Phones** list to free a slot.

**Why isn't Apple Push (CloudKit) activating?**  
Make sure both iPhones are signed into **iCloud** in **iOS Settings → [Your Name] → iCloud**, have an active internet connection, and have notifications allowed for **PillPal Senior** in **iOS Settings → Notifications**.

**Does tapping "Stop" on the Lock-Screen alarm mark a pill as taken?**  
No. For medication safety, stopping a Lock-Screen alarm only silences the sound. The senior must open PillPal Senior and tap **"I TOOK IT"** to record the dose as taken.

**I need help with an App Store charge or refund.**  
In-app purchases are processed directly by Apple. Visit [Apple Support for billing and refunds](https://support.apple.com/billing).

---

## Safety & Privacy

- All Family Sharing updates are end-to-end encrypted on-device with **AES-256-GCM** before being transmitted through Apple CloudKit. Real pill photos remain local-only on the device where they were taken.
- PillPal Senior is an organizational aid, not a medical device, medical advice, or an emergency monitoring service. Background delivery is best-effort and depends on iOS and network conditions.
- Read the [PillPal Senior for iOS Privacy Policy](privacy-pillpal-ios.md).
