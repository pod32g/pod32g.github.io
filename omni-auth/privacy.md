---
title: Privacy Policy
permalink: /omni-auth/privacy/
---

# Privacy Policy

**Last updated: 3 August 2026**

Omni Auth is an offline-first authenticator app. **We do not collect, transmit, sell, or share any
personal information.** There is no account to create, no analytics, no advertising, no tracking,
and no third-party SDKs in the app.

## What Omni Auth stores

Everything Omni Auth stores lives **on your device**:

- The two-factor secrets you add, plus their issuer/account names, icons, colours, folders and tags.
- Your settings (App Lock preference, auto-lock delay, sort order).

Your two-factor secrets are encrypted with **AES-256-GCM** under a key held in the device Keychain,
on top of the operating system's own file protection. We have no server, no copy of your data, and
no ability to recover it for you.

## What leaves your device

Omni Auth makes network requests in only two situations, both optional and both off by default:

**1. iCloud sync (opt-in).** If you turn on iCloud Sync, your accounts are encrypted **on your
device** and only the resulting ciphertext is uploaded to *your own private iCloud database*. We
never receive it. Apple stores the encrypted blob but cannot read its contents; Apple can see
technical metadata such as when a record was last modified. Sync is handled by Apple's CloudKit and
is covered by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). You can turn sync off
at any time in Settings, and remove the stored data from your iCloud account.

**2. Clock accuracy check (opt-in, manual).** Time-based codes only work if your device clock is
correct. If you tap **Check Clock Accuracy** in Settings, the app makes a single `HEAD` request to
`https://www.apple.com` and reads only the `Date` response header to compare against your device
clock. No personal data, identifier, or account information is sent, and nothing is stored. This
happens only when you tap the button.

Apart from these, Omni Auth works entirely offline.

## Camera and photos

- **Camera** is used solely to scan QR codes when you add an account. Frames are processed on your
  device and are never stored or transmitted.
- **Photos** are only accessed when you pick an image yourself to scan a QR code from it. The image
  is decoded on your device and is not stored or transmitted.

## Clipboard

When you copy a code, it is placed on your device's local clipboard only — it is marked so it does
not sync to your other devices via Universal Clipboard, and it expires automatically.

## Data retention and deletion

Because your data is stored only on your device, deleting the app deletes it. You can also delete
individual accounts in the app, and remove synced data from your iCloud account at any time. We
hold nothing to delete on our side.

## Children

Omni Auth is a general-purpose security utility and is not directed at children. It collects no
personal information from anyone, including children.

## Changes to this policy

If this policy changes, the updated version will be published on this page with a new "Last
updated" date.

## Contact

Questions about this policy: **[thepod32g@gmail.com](mailto:thepod32g@gmail.com?subject=Omni%20Auth%20Privacy)**
