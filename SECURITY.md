# Security Policy

Pera Wallet protects people's keys and funds, so we take security reports seriously and appreciate responsible disclosure.

## Reporting a vulnerability

**Please don't open a public issue, PR or discussion for security problems.**

Email **security@perawallet.app** with:

- what the issue is and its impact (what an attacker could do)
- the affected product and version (app version, extension version, npm package version, or repo and commit)
- steps to reproduce, or a proof of concept
- any logs, screenshots or transaction IDs that help

Never include your own or anyone else's seed phrase or private key in a report.

## What happens next

- We'll acknowledge your report within 3 business days.
- We'll keep you updated while we investigate and fix it.
- Once it's fixed and users have had time to update, we're happy to credit you if you'd like.

Please give us a reasonable chance to fix the issue before sharing it publicly.

## Scope

**In scope**

- Pera Wallet apps: iOS, Android and the browser extension ([pera-react-native](https://github.com/perawallet/pera-react-native))
- Our SDKs: [`@perawallet/connect`](https://github.com/perawallet/connect), [`@perawallet/use-wallet-pera`](https://github.com/perawallet/use-wallet-pera), [`@perawallet/walletconnect`](https://github.com/perawallet/pera-walletconnect-ts), [`@perawallet/swap`](https://github.com/perawallet/pera-swap)
- Pera web properties and APIs on `perawallet.app`

**Out of scope**

- Archived repositories
- Third-party dApps, wallets or services that integrate with Pera
- The Algorand protocol itself (report those to the Algorand Foundation)
- Phishing sites or scam accounts impersonating Pera (please still tell us, at the same address)
- Social engineering, physical attacks, and denial-of-service or spam testing

## Supported versions

We fix security issues in the latest release of each product: the current app store and extension releases, and the latest published version of each npm package. Please check that the issue still exists in the latest version before reporting.

## Testing guidelines

- Only test against accounts and funds you own. Use TestNet or LocalNet where you can.
- Don't access, change or move other people's data or funds.
- Don't degrade our services for other users.

If you follow these guidelines and act in good faith, we won't pursue legal action against you for your research.
