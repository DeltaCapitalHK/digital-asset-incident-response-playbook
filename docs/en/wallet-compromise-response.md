# Wallet Compromise Response

Wallet compromise may involve seed phrase exposure, private key exposure, malicious approvals, device compromise, phishing signatures, fake wallet apps, or risky browser extensions.

## Protect Remaining Assets

- Stop using the suspected compromised wallet.
- Create a new wallet on a clean device.
- Move remaining assets to the new wallet, if safe to do so.
- Do not enter the old seed phrase or private key into websites, chat tools, or untrusted devices.

## Preserve Evidence

Save:

- Compromised wallet address
- Theft transaction hashes
- Token, chain, amount, and timestamp
- Wallet balance screenshots
- Websites or DApps connected before the incident
- Signature request screenshots
- Approval records
- Wallet app or browser extension source

## Check for Approvals

For EVM chains and some other smart-contract environments, check whether the wallet granted:

- Unlimited approval
- Approval to an unknown spender
- Permit or Permit2 signature
- setApprovalForAll
- Interaction with a malicious contract

## Organize the Fund Path

Use the first unauthorized transaction as the starting point and record whether the funds:

- Entered a consolidation address
- Split into multiple addresses
- Entered a DEX
- Bridged to another chain
- Reached a centralized exchange deposit address
- Entered a mixer or privacy tool

## Important Notice

If a private key or seed phrase has been exposed, the original wallet should be treated as unsafe. This guide is for documentation and response preparation, not a guarantee of recovery.
