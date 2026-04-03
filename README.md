# Dytallix Contracts

On-chain WASM smart contracts for the Dytallix protocol.

## Status

Under construction.

## Contracts

- emission_controller — PID-governed DRT emission controller. Adjusts issuance based on network utilization. 40% validators, 30% stakers, 30% treasury.
- dgt_token — Dytallix Governance Token. Fixed supply 1,000,000,000 DGT. Used for governance voting and staking delegation. Never spent on gas.
- drt_token — Dytallix Reward Token. Elastic supply. Used for all gas fees, validator rewards, and staking rewards. Burnable.
- staking — DGT delegation and DRT reward accrual. Reward index accounting for O(1) distribution.
- governance — Typed proposal creation, DGT-weighted voting, timelock execution.
- algorithm_registry — Cryptographic algorithm lifecycle management. Active, Deprecated, Revoked states. Emergency circuit breaker.

## Links

- SDK: https://github.com/DytallixHQ/dytallix-sdk
- Documentation: https://github.com/DytallixHQ/dytallix-docs
- Whitepapers: https://dytallix.com
- Website: https://dytallix.com
- Discord: https://discord.com/invite/eyVvu5kmPG