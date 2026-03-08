# Account and Data Deletion

Effective date: 2026-03-08

This page explains how account and data deletion works for PinDial: Sales Route CRM.

## If you only use the App locally

You do not need to create an account to use the core workflow.

To delete local data:

1. Open the App.
2. Go to the settings or danger-zone section.
3. Use the clear-all action to remove local leads from the device.
4. Delete any exported CSV, backup, or encrypted lead-card files that you saved outside the App.

## If account sign-in is exposed in production

If the production release exposes account sign-in, you can delete your account inside the App.

Typical path:

1. Open the account or sign-in screen.
2. Sign in if required.
3. Choose the delete-account action.
4. Confirm the deletion request.

Some providers may require re-authentication before the account can be deleted.

## What may be deleted

Depending on the enabled production features, deletion may include:

- account identity data
- account-linked sync metadata
- encrypted remote vault data controlled by the App's backend or configured sync flow

## What you may still need to delete yourself

- CSV exports saved outside the App
- encrypted backup files saved outside the App
- encrypted lead-card exports saved outside the App
- files stored in cloud folders you selected manually, if that sync path was enabled

## Contact

Support email: qq260316514@gmail.com
