# Privacy Policy for AETRON Wallet

**Last Updated: November 2026**

**Effective Date: November 2026**

## Overview

AETRON Wallet is a non-custodial application for the AETRON blockchain, available on iOS, Android, macOS, Windows, Chrome and Firefox Extension. We are committed to protecting your privacy and being transparent about our data practices.

## Data Collection

**We do NOT collect:**

- Personal information or identifiers (name, email, phone number)
- Private keys or recovery phrases
- Location data
- Analytics or telemetry data
- Usage statistics
- Crash reports
- Advertising identifiers

**We do NOT:**

- Track your activity
- Sell or share any data with third parties
- Use advertising networks
- Require account registration

## Data Storage

All data is stored **locally** on your device:

| Data Type              | Storage Location      | Purpose                      |
| ---------------------- | --------------------- | ---------------------------- |
| Encrypted private keys | Device secure storage | Sign transactions            |
| Wallet addresses       | Device secure storage | Display accounts             |
| User preferences       | Device local storage  | Settings (language, network) |
| Biometric data         | Device OS keychain    | Optional quick unlock        |

**Important:** Biometric data (Face ID, Touch ID, fingerprint) is processed entirely by your device's operating system. We never access or store biometric data directly.

## Network Communications

The app connects to the following services. Those marked AETRON are run by us.

- **AETRON blockchain nodes** (AETRON: `entrypoint-mainnet.aetron.ai`, `entrypoint-test.aetron.ai`), or a node you add yourself in Settings — to read balances and staking data and to submit the transactions you sign
- **AETRON Explorer API** (AETRON: `api-explorer.aetron.io`) — transaction history, miner reward history, network statistics and the AET price
- **AETRON Connect relay** (AETRON: `connect.aetron.ai`) — only when you connect the wallet to a site or app. Messages between the wallet and the site are end-to-end encrypted: the relay forwards them, cannot read them, keeps each message only until it expires (at most one hour) and does not log message contents
- **Desktop only: GitHub Releases** — to check for and download updates of the macOS and Windows apps. GitHub's privacy policy applies to these requests

These requests contain public blockchain data (wallet addresses, signed transactions, transaction hashes) and nothing that identifies you personally. Like any internet service, these servers see the IP address a request comes from. We do not use IP addresses to identify or track you.

A site or app you connect through AETRON Connect receives the account address you choose to share and the signatures and transactions you approve. Its own privacy policy applies to what it does with them.


## Third-Party Services

We do not use any third-party:

- Analytics services
- Advertising networks
- Crash reporting services
- User tracking tools

## Device Permissions

| Permission | Why We Need It | Required |
| --- | --- | --- |
| Camera | Scan QR codes for addresses and AETRON Connect | Optional |
| Biometric | Quick unlock and confirmation with Face ID, Touch ID or fingerprint | Optional |
| Internet | Connect to the blockchain network | Required |

You can deny optional permissions and still use the app with limited functionality.

## Security

- Private keys are encrypted using industry-standard encryption before storage
- Keys are stored in the device's secure enclave/keystore when available
- Keys never leave your device unencrypted
- No remote access to your wallet data
- The wallet opens only with your password or biometric confirmation, and you can require that confirmation for every transaction in Settings

## Your Responsibilities

As a non-custodial wallet:

- **You are solely responsible for your recovery phrase**
- We cannot recover lost recovery phrases or private keys
- We cannot reverse or cancel transactions
- We cannot freeze or access your funds
- You should back up your recovery phrase in a safe location

## Children's Privacy

This application is not intended for users under 18 years of age. We do not knowingly collect any information from children.

## Data Deletion

Your wallet data is on your device, not on our servers:

- You can delete individual wallets in Settings, or remove all wallets with "Forgot password?" on the unlock screen
- On Android, uninstalling the app removes its data
- On iOS, data kept in the iOS Keychain can remain after the app is deleted and return if it is installed again. To remove everything, delete your wallets in the app before uninstalling it
- We keep no wallet data on our servers

## International Users

This app can be used worldwide. All data remains on your device regardless of your location.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date above. Continued use of the app after changes constitutes acceptance of the new policy.

## Contact

For questions or concerns about this Privacy Policy:

- Email: support@aetron.io
- Website: https://aetron.io

---

**Summary:** AETRON Wallet is a non-custodial wallet that keeps your keys and wallet data on your device. It has no accounts, analytics, advertising or tracking. To work, it talks to AETRON's blockchain nodes, explorer and, when you connect a site, the end-to-end encrypted AETRON Connect relay; the desktop apps also check GitHub for updates.
