# EXIT AI launch gates

## Current evidence
- GitHub repository and Railway service exist.
- Website deployed; Railway reported SUCCESS on latest observed deployment.
- Backend samples DEX Screener Solana token profiles; not an exhaustive new-launch feed.
- Basic rules-based scoring and market filters exist.
- AI endpoint is optional and requires OPENAI_API_KEY in Railway.
- On-chain security verification is **not** implemented; automated entries fail closed.
- Server paper account is in-memory; it is **not** durable or suitable for production claims.

## Must finish before claiming full autonomous AI trading
- [ ] Solana RPC contract checks (mint/freeze authorities, Token-2022 extensions, transfer restrictions)
- [ ] LP custody, holder concentration and creator wallet verification
- [ ] Persistent paper account (database), idempotency and execution realism
- [ ] Live data staleness checks, circuit breakers, daily loss limits
- [ ] Reproducible tests and independent security review
- [ ] Configure AI credentials server-side; verify output and usage limits
- [ ] Verify mobile UX, scanner uptime and error monitoring

## Token release approvals
- [ ] Confirm EXIT AI name/ticker and brand ownership
- [ ] Approve final image/banner and official social accounts
- [ ] Approve creator wallet, initial purchase and fee settings
- [ ] Publish creator holdings, any vesting, and conflicts of interest
- [ ] Obtain jurisdiction-specific legal review before marketing/sale
- [ ] Final user approval of Pump.fun mint transaction

Do not imply token ownership provides trading returns or guaranteed access. No promises of future price appreciation.
