# PocketWise

[![Latest release](https://img.shields.io/github/v/release/Vocabulo-Confiante/pocket-wise-releases?include_prereleases&label=latest%20release)](https://github.com/Vocabulo-Confiante/pocket-wise-releases/releases/latest)

Accounts, transactions, budgets and receipts in one calm place. Connect your
bank, snap a receipt, and PocketWise keeps track for you, on your Mac, your
Windows PC and your phone.

This repository holds the installers and release notes. The source code is
private.

## Download

Get the installer for your platform from the
[**latest release**](https://github.com/Vocabulo-Confiante/pocket-wise-releases/releases/latest).

| Platform | File | Notes |
|---|---|---|
| macOS | `Pocket.Wise-<version>.dmg` | Developer ID signed and notarized |
| Windows (x64) | `Pocket.Wise-Setup-<version>.exe` | Installer |
| Windows (x64) | `Pocket.Wise-<version>-windows.zip` | Portable, no install |

Every release also carries a `SHA256SUMS` file to check your download:

```bash
shasum -a 256 -c SHA256SUMS --ignore-missing
```

iPhone and Android builds are in private beta and reach testers by invitation.

## Installing

**macOS.** Open the `.dmg` and drag Pocket Wise to Applications. The build is
signed and notarized by Apple and opens without warnings.

**Windows.** Run the installer. Until the build is Authenticode signed,
SmartScreen may warn on first launch: choose More info, then Run anyway.

## Releases and versioning

Versions follow `v<major>.<minor>.<patch>` tags. Every release is built and
published by CI from the app's own repository, so what you download is
exactly what passed the pipeline. Releases marked as pre-release are beta
builds.

## Feedback and issues

Found a bug or have an idea? Open an issue in this repository's
[issue tracker](https://github.com/Vocabulo-Confiante/pocket-wise-releases/issues).
Please include your operating system, the app version and the steps to
reproduce. Report a security vulnerability privately instead, as
[SECURITY.md](SECURITY.md) describes.
