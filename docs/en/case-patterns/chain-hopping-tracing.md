# Chain-Hopping and Multi-Step DEX Tracing Pattern

This page describes incidents where stolen or scam-related funds move through DEX swaps, wrapped assets, bridge transfers, and destination-chain swaps.

## Typical Scenario

Funds are transferred to a source-chain address, then:

1. Swapped through one or more DEX routes
2. Converted into a bridgeable or wrapped asset
3. Bridged to another chain
4. Swapped again on the destination chain
5. Consolidated or deposited into an exchange

## Materials to Prepare

- First loss transaction hash
- Source-chain victim and recipient addresses
- DEX swap transaction hashes
- Bridge transaction hashes
- Destination-chain recipient address
- Destination-chain swap hashes
- Consolidation or suspected exchange address
- Chat records, platform screenshots, and source-of-funds materials

## Analysis Focus

### DEX Route Decoding

DEX transactions may involve multi-hop routes such as:

```text
USDT -> USDC -> WETH -> bridge asset
```

Transaction logs should be reviewed instead of relying only on wallet balance changes.

### Bridge Event Matching

Bridge activity should be matched across source and destination chains by amount, time, protocol, recipient address, and transaction records.

### Destination-Chain Reconstruction

After funds reach the destination chain, reconstruct swaps, consolidation, and possible exchange deposit behavior separately.

### Exchange Entry Preparation

If funds appear to reach an exchange, the full path before exchange entry should be prepared before submitting a support ticket or preservation request.

## Important Notice

Chain-hopping tracing should be written in evidence-chain language: what is confirmed, what is suspected, and what requires further verification by exchanges, bridge protocols, law enforcement, or legal process.
