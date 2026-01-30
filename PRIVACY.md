# Privacy Policy for AETRON Wallet

**Last Updated: January 2026**

**Effective Date: January 2026**

## Overview

AETRON Wallet is a non-custodial application for the AETRON blockchain, available on iOS, Android, macOS, Windows. We are committed to protecting your privacy and being transparent about our data practices.

## Data Collection

**We do NOT collect:**

- Personal information or identifiers
- Wallet addresses or balances
- Transaction history
- Private keys or seed phrases
- Location data
- Analytics or telemetry data
- Usage statistics

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

**No data is transmitted to our servers** because we do not operate any servers.

The app connects only to:

- **AETRON blockchain nodes** — to query balances, submit transactions, and interact with the network (using public WebSocket endpoints)
- **AETRON block explorer API** — to retrieve transaction history and balance information as an additional data source alongside blockchain nodes

These connections contain only public blockchain data (wallet addresses, transaction hashes) necessary for wallet functionality. No personal information is transmitted.

## Third-Party Services

We do not use any third-party:

- Analytics services
- Advertising networks
- Crash reporting services
- User tracking tools

## Device Permissions

| Permission | Why We Need It                        | Required |
| ---------- | ------------------------------------- | -------- |
| Camera     | Scan QR codes for addresses           | Optional |
| Biometric  | Quick unlock with Face ID/fingerprint | Optional |
| Internet   | Connect to blockchain network         | Required |

You can deny optional permissions and still use the app with limited functionality.

## Security

- Private keys are encrypted using industry-standard encryption before storage
- Keys are stored in the device's secure enclave/keystore when available
- Keys never leave your device unencrypted
- No remote access to your wallet data
- Password required for sensitive operations

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

Since all data is stored locally on your device:

- Uninstalling the app removes all wallet data
- You can delete individual wallets within the app
- No data remains on any external servers (we don't have any)

## International Users

This app can be used worldwide. All data remains on your device regardless of your location.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date above. Continued use of the app after changes constitutes acceptance of the new policy.

## Contact

For questions or concerns about this Privacy Policy:

- Email: tech@aetron.io
- Website: https://aetron.io

---

**Summary:** AETRON Wallet is a non-custodial wallet that stores all data locally on your device. We do not collect, transmit, or have access to your personal information, private keys, or wallet data. We do not operate any servers and do not use any analytics or tracking services.
