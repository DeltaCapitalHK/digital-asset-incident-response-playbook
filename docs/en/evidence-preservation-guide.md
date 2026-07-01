# Evidence Preservation Guide

The purpose of evidence preservation is to turn a general incident statement into verifiable, reviewable, and submit-ready facts.

## Basic Principles

- Transaction hashes matter more than screenshots alone.
- Wallet addresses should be complete.
- Record both local time and UTC time where possible.
- Record each transaction separately.
- Always include chain name.
- Do not alter, fabricate, or splice evidence.

## Per-Transaction Fields

| Field | Example |
|---|---|
| Chain | TRON / Ethereum / BSC |
| Token | USDT / ETH / BTC |
| Transaction hash | txid / transaction hash |
| From address | Victim wallet or exchange withdrawal address |
| To address | Recipient address |
| Amount | 10000 USDT |
| Time | UTC and local time |
| Block explorer link | Tronscan / Etherscan / BscScan |
| Note | First loss, downstream split, exchange deposit, bridge transfer |

## Screenshot Guidance

Screenshots should show:

- Full address
- Full transaction hash
- Transaction status
- Block timestamp
- From and to addresses
- Amount and token
- Browser URL or explorer identity

## Suggested Folder Structure

```text
case-evidence/
  01-transaction-hashes.xlsx
  02-wallet-addresses.txt
  03-chat-records/
  04-platform-screenshots/
  05-source-of-funds/
  06-police-report/
  07-exchange-contact/
```
