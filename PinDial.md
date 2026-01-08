# Privacy Policy

Effective date: 2026-01-05

This Privacy Policy explains how PinDial (“the App”) handles information when you use it.

## Summary

- The App does **not** read your system contacts, call logs, or SMS.
- Pins you create (phone number + map location) are stored **locally** on your device in **encrypted** storage.
- You can export/import an **encrypted** backup file from the Settings screen.
- Pro (optional, via Google Play in-app purchase): unlimited Pins + encrypted contact card export/import.
- Reverse geocoding is optional; when enabled, selected coordinates are sent to a backend proxy and then to Google to resolve country/region names.

## Information you provide

When you create a Pin, you may provide:

- Name (optional)
- Phone number
- Notes (optional)
- Tags (optional)
- Location you select on the map (latitude/longitude)

## How the App uses this information

The App uses your Pins to:

- Display markers on the map
- Search Pins around a selected center point and radius
- Open your phone dialer using `ACTION_DIAL` when you tap “Call”

## In-app purchases

If you choose to buy Pro, the purchase is processed by Google Play Billing. The App may query your purchase status (product ID and purchase token) from Google Play on your device to unlock Pro features and to restore purchases after reinstall.

We do not receive or store your payment card details.

## What the App does not access

The App does not request or access:

- System contacts
- Call logs
- SMS messages

## Third-party services

The App uses third-party services for core functionality:

- Google Maps SDK for Android (map display)
- Google Play Billing (in-app purchases)
- Google Geocoding API (only if reverse geocoding is enabled)

These providers may process standard request metadata (for example, IP address) as part of providing the service. Please review their policies for details.

## Reverse geocoding (optional)

If reverse geocoding is enabled in your build/configuration, the App may send the coordinates of a Pin to:

1) a backend proxy you control, and then
2) the Google Geocoding API,
   to obtain country/administrative area information for display.

We do not store your Pins on our servers in P0. Network providers and third parties may process standard request metadata (for example, IP address) as part of providing the service.

## Storage and retention

- Local storage: Pins are stored on your device until you delete them or uninstall the App.
- System backups: Android system backup is disabled for this App. Use the in-app encrypted export feature for backups.

## Your choices

You can:

- Delete individual Pins
- Clear all contacts from Settings
- Export/import an encrypted backup file

## Security

We use:

- Encryption at rest for local storage
- Password-based encryption for exported backup files
- HTTPS for network requests (when reverse geocoding is enabled)

## Children

The App is not directed to children under 13.

## Contact

Support email: qq260316514@gmail.com
