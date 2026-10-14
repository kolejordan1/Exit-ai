# $EXIT — Draft allocation, custody and vesting

**DRAFT ONLY — no mint, transfer, listing, or on-chain transaction authorized.**

Total supply: **1,000,000,000 EXIT**, 9 decimals. Creator public address supplied: `9sMaCfsHPMRChEnGA5KJRrupoowf3pfmQPUF4Fpx9s87`. Ownership has not been verified. The creator wallet is NOT automatically a destination for any allocation.

| Bucket | Share | EXIT | Destination | Suggested restrictions (NOT approved) |
|---|---:|---:|---|---|
| Liquidity | 20% | 200,000,000 | Pool vault / LP custody TBD | Budget only; actual initial pool deposit, paired capital, LP custody and release TBD. |\n| Community distribution | 40% | 400,000,000 | Community distribution wallet TBD | Eligibility, claim mechanism, schedule, vesting and initial circulation TBD. |
| Development | 20% | 200,000,000 | Dedicated team vesting account TBD | 12-month cliff followed by 24 months of linear vesting; disclose beneficiary wallets. |
| Treasury | 15% | 150,000,000 | Multisig treasury TBD | Suggested 36-month linear release; spending requires multisig approval and public reporting. |
| Marketing | 5% | 50,000,000 | Dedicated marketing vault TBD | Suggested 24 monthly releases; disclose market-making, promotions and compensation. |

All percentages sum to 100%; no allocations have been issued. Proposed vesting schedules are illustrative, not contractual or enforced on-chain.

## Wallet and vesting implementation
1. Confirm creator wallet ownership by a signed message, without revealing private keys.
2. Choose distinct public addresses for liquidity custody, community distribution, development vesting, treasury multisig and marketing vault.
3. Approve multisig signers and quorum, backup procedures and public transparency policy.
4. Select an audited vesting/escrow implementation, verify that release schedules are enforceable, and test on devnet.
5. Approve initial circulating supply, exact pool token quantity, paired SOL/USDC capital, initial pricing and liquidity custody/lock/burn policy.
6. Decide metadata update authority and mint authority revocation sequence. Mint authority revocation is irreversible; verify total supply first.
7. Obtain qualified legal/tax review of allocations, compensation, marketing, sale and any potential securities implications.
8. Obtain separate explicit final user authorization before minting, transferring, funding liquidity or listing.

## Unresolved approvals
- [x] Draft liquidity-vs-community budget recorded: 200M liquidity / 400M community (not authorized for deployment)
- [ ] All receiving public wallet addresses and signed ownership verification
- [ ] Development vesting terms and beneficiaries
- [ ] Treasury multisig signers, quorum and spending controls
- [ ] Marketing vesting and compensation disclosure
- [ ] Initial circulating supply and any team/insider holdings
- [ ] Liquidity venue, pair, paired asset funding and lock/custody terms
- [ ] Metadata authority, mint/freeze authority plan and devnet test results
- [ ] Legal review, final transaction review and explicit final launch authorization

## Liquidity funding, custody and release decisions — outstanding

- Select DEX and pool type, and choose EXIT/SOL or EXIT/USDC pair.
- Approve how many of the 200M EXIT budget enter the initial pool, how much paired SOL/USDC is funded, who funds it, and the resulting initial pool price. **No price is set by token supply alone.**
- Decide whether remaining liquidity-budget tokens stay in treasury/escrow, how they can be deployed, and who can authorize later deposits.
- Identify the wallet/multisig controlling liquidity deposits and any LP position or LP tokens. Decide whether LP positions will be locked, burned, or controlled by a disclosed multisig; verify technical feasibility for chosen pool type.
- Approve timelocks, signer quorum, custody backup, withdrawal rights, and public proof of any lock. No lock is in effect yet.
- Approve community distribution eligibility, snapshot criteria if applicable, anti-sybil rules, claim windows, clawback/expiry handling, recipient wallet, and vesting/unlock schedule.
- Confirm the initial circulating amount, treatment of undistributed tokens, and insider holdings before any public marketing.
- Obtain explicit authorization before any on-chain transaction; no mint, transfer, liquidity funding, listing or sale is approved.
