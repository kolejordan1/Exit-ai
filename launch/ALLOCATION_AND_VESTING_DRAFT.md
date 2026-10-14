# $EXIT — Draft allocation, custody and vesting

**DRAFT ONLY — no mint, transfer, listing, or on-chain transaction authorized.**

Total supply: **1,000,000,000 EXIT**, 9 decimals. Creator public address supplied: `9sMaCfsHPMRChEnGA5KJRrupoowf3pfmQPUF4Fpx9s87`. Ownership has not been verified. The creator wallet is NOT automatically a destination for any allocation.

| Bucket | Share | EXIT | Destination | Suggested restrictions (NOT approved) |
|---|---:|---:|---|---|
| Community + liquidity | 60% | 600,000,000 | Pool vault and community-distribution wallets TBD | Define pool amount, distribution eligibility and custody separately. No claim that all 600M are circulating or locked. |
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
- [ ] Exact liquidity-vs-community split within 600M
- [ ] All receiving public wallet addresses and signed ownership verification
- [ ] Development vesting terms and beneficiaries
- [ ] Treasury multisig signers, quorum and spending controls
- [ ] Marketing vesting and compensation disclosure
- [ ] Initial circulating supply and any team/insider holdings
- [ ] Liquidity venue, pair, paired asset funding and lock/custody terms
- [ ] Metadata authority, mint/freeze authority plan and devnet test results
- [ ] Legal review, final transaction review and explicit final launch authorization
