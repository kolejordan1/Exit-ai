# $EXIT / SOL — Draft Liquidity Funding and Custody Plan

**STATUS: DRAFT ONLY. No mint, pool creation, token transfer, liquidity funding, listing, or on-chain action is authorized.**

## Confirmed planning inputs
- Token: EXIT AI (EXIT), original Solana SPL Token, draft 1,000,000,000 total supply, 9 decimals.
- Proposed trading pair: EXIT/SOL.
- Liquidity budget: 200,000,000 EXIT (20% of supply).
- Community distribution: 400,000,000 EXIT (40%); separate from pool reserves.
- Creator public address: `9sMaCfsHPMRChEnGA5KJRrupoowf3pfmQPUF4Fpx9s87`; ownership not yet verified and not automatically an LP custody wallet.
- DEX, SOL budget, actual pool deposit, custody policy and launch date: **TBD**.

## Illustrative constant-product pool ratios
| Scenario | EXIT deposited | SOL deposited | Spot price SOL per EXIT | EXIT remaining from 200M liquidity budget |
|---|---:|---:|---:|---:|
| A | 200,000,000 | 5 | 0.000000025 | 0 |
| B | 200,000,000 | 20 | 0.000000100 | 0 |
| C | 50,000,000 | 5 | 0.000000100 | 150,000,000 |

Formula: initial SOL/EXIT spot ratio = SOL pool reserve / EXIT pool reserve. Values are *not* USD prices, token valuations, predictions, guaranteed execution prices or commitments. If using concentrated liquidity, the deposit ratio, selected range and current price need venue-specific calculations. Deposits may incur rent, network and platform fees. Reserve SOL separately for these costs.

## Funding approvals required
1. Select DEX and pool mechanism (e.g. Raydium CPMM or an Orca pool); independently verify official contracts and fee schedule.
2. Confirm how much SOL can be committed and its source. Do not share private keys or seed phrases.
3. Select the exact EXIT amount for the initial pool (maximum 200M under current draft); approve the remaining liquidity-token reserve schedule.
4. Verify pool spot ratio, slippage, fee tier, rent and potential opening-price manipulation; simulate on devnet where possible.
5. Approve initial circulating supply and publish allocation/insider holding disclosures.

## Custody model (proposal, not deployed)
- **Creator signer:** use the supplied public address only after ownership is verified via a signed message.
- **Liquidity vault/LP position:** dedicated multisig or audited timelock; define signers, quorum, emergency procedure, and on-chain proof of custody/lock. LP tokens or concentrated-liquidity NFTs are not automatically locked.
- **Undeployed liquidity reserve:** separate disclosed multisig-controlled wallet; no automatic releases.
- **Community allocation:** distinct distribution vault, documented eligibility and unlock schedule.
- **Development / treasury / marketing:** dedicated vesting or multisig accounts, not mixed with liquidity funding.

## Release and withdrawal policy decisions
- Determine whether liquidity ownership is locked, burned, or held by a multisig. Do not claim any lock until verified on-chain.
- Approve any initial lock duration, withdrawal rights, renewal rules and signer threshold.
- Establish rules for staged additions/removals of liquidity, public notices, and reporting.
- Approve community claim eligibility, vesting, distribution start and unclaimed token handling.
- Get independent legal and security review and final transaction-by-transaction user authorization.

## Explicit no-action guardrail
No transaction is approved by this document. Final mint, transfer, pool creation, funding, lock or listing each requires explicit user authorization.
