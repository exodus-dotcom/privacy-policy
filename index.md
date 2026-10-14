# Exodus Extension Privacy Policy

**Effective date:** October 14, 2026
**Last updated:** October 14, 2026

Exodus Extension is a web3 browser extension that lets you manage blockchain accounts and interact with decentralized
applications (dApps). This policy explains what information the extension handles, where it is stored, and when it is sent
anywhere.

Exodus Extension is provided by [Company Name] ("we", "us"). Contact us at [contact email address].

## 1. Summary

- Your account keys and settings are stored locally on your device, encrypted with your password.
- We do not operate servers that hold your private keys, seed phrase, or passwords.
- The extension sends requests to public blockchain nodes to read blockchain data and broadcast transactions you approve.
- The extension sends a limited analytics event to PostHog in the circumstances described in section 4.

## 2. Information stored on your device

The extension stores the following in your browser's local extension storage:

- Encrypted account data, including your seed phrase or private keys, encrypted with your password.
- Account names, addresses, and the networks you have selected.
- Settings, such as language, currency, and connection preferences.
- Permissions you have granted to dApps and websites.
- Cached token, transaction, and price data, so the extension loads quickly.

This data never leaves your device unless you take an action that requires it, such as sending a transaction.

## 3. Information sent to blockchain networks and third-party services

To function, the extension communicates with:

- **Public blockchain nodes** (for example, Polygon and other supported networks). Requests include the addresses you
query, the transactions you sign and broadcast, and standard technical data such as your IP address.
- **Price, token, and name-service providers.** These receive the identifiers needed to return data, such as token
contract addresses or account names.
- **dApps you connect to.** When you approve a connection, the dApp receives your public account address and the network
you have selected.

Blockchain transactions are public and permanent. Anything you broadcast to a blockchain can be seen by anyone.

## 4. Analytics

The extension may check whether a specific blockchain storage value is set for your account, and in that case it sends an
analytics event to PostHog (https://posthog.com). The event may include:

- Your public account address.
- The storage value that was read from the blockchain.
- A session key derived from your account data on your device.

We use this event to understand eligibility for a promotion. We do not sell this data, and we do not use it for
advertising.

## 5. Permissions the extension requests

The extension asks for browser permissions only to provide its features:

- **storage and unlimitedStorage:** store encrypted account data and cached data on your device.
- **scripting and host access (http and https):** provide the web3 interface on websites so dApps can request connections and signatures.
- **activeTab and tabs:** identify the site you are viewing so the extension can show its connection status.
- **sidePanel:** open the extension interface in the browser side panel.
- **declarativeNetRequestWithHostAccess:** route requests to the extension's own interface.
- **offscreen:** run background tasks in a hidden document.
- **clipboardWrite:** copy addresses and transaction data when you click copy.

We do not read or collect the content of web pages beyond what is needed to inject the interface and show connection status.

## 6. Data we do not collect

We do not collect your seed phrase, private keys, or password on our servers. We do not track your browsing history. We do not use advertising identifiers.

## 7. Security

Your account data is encrypted with your password, which is never sent to us. We cannot recover your password or your funds. If you lose your password and your seed phrase, we cannot restore access to your accounts. Keep your seed phrase in a safe, offline place.

## 8. Children

Exodus Extension is not directed at children under 16, and we do not knowingly collect information from them.

## 9. Your choices

- You can delete all extension data by removing the extension from your browser or using the reset option in settings. This deletes local data on your device; it does not affect blockchain data.
- You can disconnect any dApp at any time from the permissions settings.

## 10. Changes to this policy

We may update this policy. We will change the "Last updated" date above when we do. Continued use of the extension after an update means you accept the updated policy.
