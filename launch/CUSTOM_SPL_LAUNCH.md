# EXIT AI — Custom Solana SPL token launch

STATUS: DRAFT ONLY. No mint, sale, liquidity pool or listing authorized.

## Recommended architecture
Original SPL Token Program, 9 decimals, fixed supply after mint authority revocation, no freeze authority, Metaplex Token Metadata. Official Solana references: https://solana.com/docs/tokens/basics and https://solana.com/docs/tokens/metaplex .

## Approval requirements
- Confirm name EXIT AI, ticker EXIT, icon, social links, official domain.
- Decide exact supply and allocations; identify creator, treasury and community wallets, vesting and disclosures.
- Confirm public wallet or multisig addresses. Never share private keys or recovery phrases.
- Approve revocation of mint authority after approved supply mint; freeze authority none; metadata update authority choice.
- Select liquidity venue and pool pair, initial SOL and EXIT liquidity deposits, custody/lock terms and trading start time.
- Complete legal and tax review for intended jurisdictions and token sale claims.
- Rehearse on devnet; simulate mainnet transactions and independently review before signature.
- Require explicit user approval before mint, listing, liquidity deposit or sale.

## Metadata and image
Use token-metadata.template.json; replace placeholder with a permanent public image URL and verify that URL is accessible. Token icon is in the downloadable launch kit shared in the chat; binary asset not committed here.

## Product disclosure
The deployed EXIT AI prototype samples public Solana DEX token feeds and uses rules-based scoring. Optional AI analysis requires an API key. On-chain safety screening is incomplete and autonomous entries are blocked. Server paper trading is not durable. Do not market these unfinished features as complete.

## Verification after approved mint
Verify mint address, program ID, decimals, supply, authorities, metadata, allocations and any LP pool via independent Solana RPC and explorer; only then publish mint address.
