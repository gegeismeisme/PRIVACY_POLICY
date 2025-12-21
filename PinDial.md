# Privacy Policy (P0) — PinDial

Effective date: 2025-12-21

This Privacy Policy explains how **PinDial** (“the App”) handles information when you use it. PinDial is designed to be privacy-first and does **not** read your system contacts, call logs, or SMS.

If you have questions, contact: **qq260316514@gmail.com**

## 1) What information the App handles

### 1.1 Information you enter (stored on your device)

PinDial lets you manually create and manage “pins” on a map. The App may store the following information **only on your device**:

- Contact name (optional)
- Phone number(s) (optional; contact phones and/or location-specific phones)
- Notes (optional)
- Tags (optional)
- Location coordinates you select on the map (latitude/longitude)
- Optional location labels / address notes you type
- Optional region fields (e.g., country/administrative area) if reverse geocoding is enabled

### 1.2 Information processed for map display

To display map tiles, the App uses **Google Maps SDK for Android**. Your device will connect to Google’s services to load map content.

### 1.3 Reverse geocoding (optional)

If reverse geocoding is enabled in the build/configuration, the App may send the coordinates you selected to:

- A reverse-geocoding endpoint you configure (if any), and/or
- Google Geocoding API (via that endpoint)

This is used only to derive human-readable region information (e.g., country/region). PinDial is intended to avoid storing reverse-geocoding inputs on a server beyond transient processing; however, you should review the hosting provider’s logging settings if you operate the endpoint.

### 1.4 What the App does **not** access

PinDial does not request or access:

- Your system contacts
- Call logs
- SMS / messages
- Background location

PinDial uses the system dialer via `ACTION_DIAL` and does not auto-call numbers.

## 2) How the App uses information

PinDial uses your information to:

- Create, edit, and display your pins on a map
- Search pins near a selected center point and radius
- Let you open the system dialer for a stored phone number
- Export and import encrypted backups you create manually
- (Optional) display region information derived from reverse geocoding

## 3) Sharing and third-party services

PinDial does not sell your personal information and does not include ads in P0.

The App relies on third-party services for core functionality:

- **Google Maps SDK for Android** (map display and tile loading)
- **Google Geocoding API** (only if reverse geocoding is enabled)

When you tap “Dial”, the phone number is passed to your device’s dialer app to populate the dialing screen.

## 4) Data storage, encryption, and retention

### 4.1 On-device storage

Your pin data is stored locally on your device and protected with encryption at rest (Android Keystore + AES-GCM).

### 4.2 Manual backup export/import

If you export a backup, PinDial creates an encrypted file protected by the password you choose. If you forget the password, the backup cannot be recovered.

### 4.3 Retention

Your data remains on your device until you delete it or uninstall the App.

## 5) Your choices and controls

You can:

- Add and edit your data at any time
- Export an encrypted backup and import it later
- Delete individual entries
- Use “Clear all contacts” to remove all stored data from the device
- Uninstall the App to remove local data

## 6) Security

PinDial uses reasonable safeguards designed to protect your information, including encryption at rest and encrypted backups. No method of storage or transmission is 100% secure; you are responsible for protecting your device and any exported backup files.

## 7) Children’s privacy

PinDial is not intended for children under 13. If you believe a child has provided personal information, contact us and we will take appropriate steps.

## 8) Changes to this policy

We may update this Privacy Policy from time to time. We will update the “Effective date” above when changes are made.

## 9) Contact

Email: **qq260316514@gmail.com**
