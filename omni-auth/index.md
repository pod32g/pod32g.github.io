---
title: Omni Auth
permalink: /omni-auth/
---

# Omni Auth

**A fast, private authenticator for your two-factor codes.**

Omni Auth generates the six-digit codes that protect your accounts. It works entirely offline, your
secrets are encrypted on your device, and there is no account to create — because there is no
server to create one on.

<img src="/omni-auth/img/01-vault.png" alt="The Omni Auth vault showing live codes with countdown rings" width="270">
<img src="/omni-auth/img/04-security.png" alt="Security settings: App Lock, end-to-end encrypted sync, Recovery Kit" width="270">

## Private by design

- **Nothing is collected.** No analytics, no tracking, no advertising, no third-party SDKs.
- **Your secrets stay on your device**, encrypted with AES-256-GCM under a key held in the iOS
  Keychain, on top of the system's own file protection.
- **Optional iCloud sync is end-to-end encrypted.** Only ciphertext is uploaded, to your own
  private iCloud database. Apple can't read it, and neither can we.
- **Offline by default.** The only other network request is a clock-accuracy check you trigger
  yourself.

## Built for daily use

- Tap a code to copy it. The clipboard entry stays on this device and expires on its own.
- A countdown ring on every account, and the next code appears in the final seconds so a code never
  expires mid-login.
- Home Screen and Lock Screen **widgets** — codes are hidden on the Lock Screen, and a widget can
  stay redacted until you tap to reveal.
- **Folders, tags, favourites**, search, and manual or alphabetical ordering.
- Siri and Shortcuts support.

## Extra protection when you want it

- **App Lock** with Face ID, Touch ID, or your passcode.
- **Per-account Face ID** — mark a sensitive account and its code stays hidden until you
  authenticate. Those accounts never appear in widgets or Shortcuts.
- Content is blurred in the App Switcher and while the screen is being recorded, and you are warned
  when a screenshot is taken.

## Moving in is easy

Import from **Google Authenticator**, **2FAS**, **Aegis**, **FreeOTP**, CSV files, or an Omni Auth
backup — including password-protected 2FAS and Aegis vaults. Scan a QR code, pick one from your
photos, paste a link, or type it in by hand.

Supports TOTP and HOTP, SHA-1/SHA-256/SHA-512, and 6–8 digit codes.

## You stay in control of recovery

Because nothing is stored on a server, recovery is yours to arrange — so Omni Auth makes it
straightforward:

- **Encrypted backups**, protected by a password only you know.
- A **Recovery Kit** — a recovery key plus a kit file — that restores your vault on a new device.

If you lose your device without either, the codes cannot be recovered by anyone, including us.
That trade-off is what makes the rest of it private.

---

[Privacy Policy](/omni-auth/privacy/) · [Terms of Use](/omni-auth/terms/) ·
[Support](/omni-auth/support/)
