# $EXIT / SOL — Draft Liquidity Funding and Custody Plan

**STATUS: DRAFT ONLY. No mint, pool creation, token transfer, liquidity funding, listing, or on-chain action is authorized.**

## Confirmed planning inputs
- Token: EXIT AI (EXIT), original Solana SPL Token, draft 1,000,000,000 total supply, 9 decimals.
- Proposed trading pair: EXIT/SOL.
- Liquidity budget: 200,000,000 EXIT (20% of supply).
- Community distribution: 400,000,000 EXIT (40%); separate from pool reserves.
- Creator public address: `9sMaCfsHPMRChEnGA5KJRrupoowf3pfmQPUF4Fpx9s87`; ownership not yet verified and not automatically an LP custody wallet.
- Draft initial paired-asset funding budget: **2 SOL** (not committed or funded).\n- DEX, actual EXIT pool deposit, custody policy and launch date: **TBD**.

## Initial pool pricing examples — draft 2 SOL budget

| EXIT deposited | SOL deposited | Initial SOL per EXIT | EXIT per SOL | Undeployed EXIT from liquidity budget |
|---:|---:|---:|---:|---:|
| 200,000,000 | 2 | 0.000000010 | 100,000,000 | 0 |
| 100,000,000 | 2 | 0.000000020 | 50,000,000 | 100,000,000 |
| 50,000,000 | 2 | 0.000000040 | 25,000,000 | 150,000,000 |
| 20,000,000 | 2 | 0.000000100 | 10,000,000 | 180,000,000 |

Constant-product initial spot ratio = SOL reserve / EXIT reserve. These ratios are hypothetical, **not USD prices or valuations**, and assume a conventional constant-product pool. Actual quotes, fees, price impact, opening pool parameters and concentrated-liquidity math may differ. 2 SOL is the proposed *pool contribution*; additional SOL may be required for rent, transaction fees, pool creation and operational reserve. With only 2 SOL, liquidity can be shallow and volatile; a smaller EXIT deposit changes nominal opening price, not SOL-side depth. No scenario is approved for execution.

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

## Outstanding 2 SOL funding and custody decisions

- [x] Draft pair EXIT/SOL and 2 SOL funding budget recorded (no transfer authorization).
- [ ] Select exact EXIT initial deposit (20M, 50M, 100M, 200M or another amount no more than 200M).
- [ ] Confirm whether 2 SOL is solely pool funding and approve separate fee/rent/operating reserves.
- [ ] Confirm funding source and wallet control; verify creator address ownership by signed message.
- [ ] Choose DEX and constant-product versus concentrated-liquidity pool; verify current fees and pool requirements.
- [ ] Specify LP ownership wallet, multisig signers/quorum, lock/escrow/burn decision and withdrawal policy; publish verifiable proof only after implementation.
- [ ] Specify release schedule for unused liquidity tokens and community distribution (400M EXIT), with enforceable custody/vesting.
- [ ] Complete legal review, devnet rehearsal, final transaction review and separate explicit approval for each on-chain action.
