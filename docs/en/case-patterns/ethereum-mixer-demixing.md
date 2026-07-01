# Ethereum Mixer Demixing Pattern

This page describes an Ethereum incident pattern where stolen ETH or ERC20 assets enter a mixer, privacy tool, or fixed-denomination pool.

Mixer analysis should be expressed through methods, confidence levels, and limitations rather than absolute claims.

## Anonymized Case Summary

In one anonymized wallet-theft scenario, approximately 119.78 ETH was moved out of a compromised wallet after phishing or malicious authorization activity. The attacker moved the ETH to controlled addresses, then deposited funds into a fixed-denomination mixer. On the withdrawal side, candidate addresses appeared, followed by peeling, consolidation, and suspected centralized-exchange deposit behavior.

The key difficulty is that ETH is a native asset and does not have the same issuer-freeze mechanism as some stablecoins. The practical focus is to reconstruct the pre-mixer path, identify candidate post-mixer relationships, label confidence levels, and prepare exchange or legal-process materials quickly if funds approach a cooperative platform.

The public case pattern can be summarized as:

```text
Victim wallet
  -> attacker collection address
  -> fixed-denomination mixer deposits
  -> candidate withdrawal addresses
  -> downstream peeling / consolidation
  -> suspected exchange deposit address
```

Real mixer identifiers, wallet addresses, hashes, exchange accounts, and personal identifiers are not published.

## Typical Scenario

A wallet is compromised through phishing, private-key exposure, or malicious approval. ETH is moved to attacker-controlled addresses, deposited into a mixer, and later withdrawn to candidate addresses before further consolidation or exchange deposit activity.

## Materials to Prepare

- Compromised wallet address
- First theft transaction hash
- Amount and timestamp
- Attacker collection address
- Mixer deposit transaction hashes
- Candidate withdrawal addresses
- Downstream consolidation or exchange indicators
- Phishing website, signature records, and wallet screenshots

## Analysis Methods

### Pre-Mixer Reconstruction

The path before mixer deposit is usually more certain and should be reconstructed first.

### Timing Window

Deposits and withdrawals may be compared within a defined time window. Timing alone is not enough for a final conclusion.

### Amount and Denomination

Fixed-denomination pools may support candidate matching, but matching denominations do not prove ownership by themselves.

### Gas Source and Address Reuse

Gas funding sources, address reuse, downstream consolidation, and behavioral patterns may increase confidence.

### Confidence Labels

Use clear labels such as high confidence, medium confidence, low confidence, or pending platform/law-enforcement verification.

## Evidence Package Structure

```text
01-wallet-compromise-or-phishing-narrative
02-first-theft-transaction-and-attacker-collection-address
03-mixer-deposit-transaction-list
04-candidate-withdrawal-address-and-timing-window-analysis
05-gas-source-address-reuse-and-behavioral-pattern-notes
06-downstream-consolidation-or-exchange-entry-notes
07-confidence-level-labels
08-exchange-law-enforcement-or-legal-process-support-materials
```

## Native Asset Consideration

ETH is a native asset and does not have the same issuer-freeze mechanism as some stablecoins. If funds leave cooperative platforms, on-chain freezing may not be available.

## Important Notice

This pattern is for documentation and analytical framing. It does not guarantee demixing, freezing, or recovery.
