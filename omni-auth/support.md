---
title: Support
permalink: /omni-auth/support/
---

# Support

## Getting help

Email **[thepod32g@gmail.com](mailto:thepod32g@gmail.com?subject=Omni%20Auth%20Support)**.

It helps to include your iOS version, your device model, the app version (Settings ▸ About ▸
Version), and what you were doing when the problem happened. **Never include a two-factor secret,
QR code, backup file, or Recovery Key** in a support request — anyone who sees them can generate
your codes.

## Common questions

### My codes are being rejected

Almost always a clock problem: time-based codes are derived from the current time, so a device
clock that is off by more than about 30 seconds produces codes the server won't accept. In Omni
Auth, open **Settings ▸ Check Clock Accuracy**. If it reports significant drift, fix it in the
system Settings app under **General ▸ Date & Time** (turning "Set Automatically" on is usually
enough).

### I got a new phone — how do I move my accounts?

Two options, both set up *before* you lose access to the old device:

- **iCloud Sync** (Settings ▸ iCloud Sync). Requires a Recovery Kit, because your data is
  end-to-end encrypted and the new device needs your key to read it.
- **Encrypted backup** (Settings ▸ Backup ▸ Export Encrypted Backup). Save the file somewhere safe
  and remember the password.

### I lost my device and had no backup

We're sorry — the codes cannot be recovered. Omni Auth stores secrets only on your device and we
have no copy. You'll need to use each service's own account-recovery process (this is what the
recovery codes services give you at setup are for), then re-enrol two-factor authentication.

### What is a Recovery Kit?

A Recovery Key (shown once) plus a Recovery Kit file. Together they let a new device decrypt your
synced vault. Both are required, and neither can be recovered for you — store them separately from
your device.

### Can I import from another authenticator?

Yes: Google Authenticator (export QR), 2FAS, Aegis, FreeOTP, CSV, and Omni Auth backups —
including password-protected 2FAS and Aegis vaults. Microsoft Authenticator cannot be imported
because it does not allow exporting secrets; you'll need to re-enrol those accounts.

### Why doesn't my widget show a code?

Widgets deliberately never show accounts you marked **Require Face ID to reveal**, and they hide
codes on the Lock Screen. Counter-based (HOTP) accounts aren't available in widgets because a
widget cannot advance the counter.
