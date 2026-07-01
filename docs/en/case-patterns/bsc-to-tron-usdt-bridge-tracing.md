# BSC to TRON USDT Bridge Tracing Pattern

This page describes a cross-chain scenario where USDT starts on BNB Smart Chain and later appears on TRON through bridge, swap, or consolidation activity.

## Typical Scenario

The victim sends BEP20-USDT to a BSC address. The funds are then split, swapped, bridged to TRON, converted or released as TRC20-USDT, and may later consolidate or enter an exchange.

## Materials to Prepare

- First BSC loss transaction hash
- BEP20-USDT recipient address
- Downstream BSC transaction hashes
- Bridge or contract interaction records
- Destination TRON address
- Corresponding TRON-side transaction
- Timestamps on both chains
- Chat records, fake platform screenshots, and source-of-funds materials

## Analysis Focus

### Source-Chain Confirmation

Confirm the transfer from the victim address to the suspicious BSC address, including hash, amount, and timestamp.

### Bridge Event Matching

Cross-chain tracing often requires matching source-chain lock, burn, or deposit events with destination-chain mint, release, or withdrawal events.

### Destination-Chain Reconstruction

After funds reach TRON, continue tracing TRC20-USDT transfers, splits, consolidation, and potential exchange deposit behavior.

### Evidence Continuity

A complete explanation should connect:

```text
Victim wallet -> BSC recipient -> bridge/swap path -> TRON recipient -> downstream consolidation or exchange
```

Each segment should be supported by transaction hashes, timestamps, and amount relationships.

## Important Notice

Cross-chain tracing should not rely on similar amounts alone. Public documentation should distinguish confirmed facts from suspected links.
