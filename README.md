### kenny-ish

Ethereum and DeFi tooling in Python, Go, TypeScript, Solidity and Rust. Most of it reads data from
the chain over JSON-RPC: AMM and gas math, contract state, EVM internals.

#### Featured

- [univ3-tick-math](https://github.com/kenny-ish/univ3-tick-math): Uniswap v3 tick, price and sqrtPriceX96 conversions
- [matching-engine-go](https://github.com/kenny-ish/matching-engine-go): limit order book with price-time priority
- [eth-checksum-address](https://github.com/kenny-ish/eth-checksum-address): EIP-55 checksums with a pure-Python Keccak-256

#### Recent

| Project | Language | Description |
|---|---|---|
| [oracle-config-audit](https://github.com/kenny-ish/oracle-config-audit) | Python | Inspect the live OCR configuration behind a Chainlink AggregatorV3 proxy and verify config digests, transmission age, and transmitter set via JSON-RPC. |
| [eth-tx-inspector](https://github.com/kenny-ish/eth-tx-inspector) | Python | Inspect any EVM transaction from its hash: type, status, gas and fee breakdown, blob and 7702 details, and decoded ERC-20 transfers |
| [eip7702-auth-audit](https://github.com/kenny-ish/eip7702-auth-audit) | Python | Audit EIP-7702 type-4 transactions by decoding authorization tuples, recovering senders, and checking delegation state through JSON-RPC. |
| [pr-inbox](https://github.com/kenny-ish/pr-inbox) | Python | See what people said on your pull requests to other projects since you last looked: new human reviews and comments, merges and closes, without bot noise |
| [proxy-upgrade-ledger](https://github.com/kenny-ish/proxy-upgrade-ledger) | Python | Rebuild an upgradeable proxy's admin, implementation and beacon history from Upgraded/AdminChanged logs and check it against the live EIP-1967 slots over plain JSON-RPC. |
| [evm-state-proof-auditor](https://github.com/kenny-ish/evm-state-proof-auditor) | Python | Verify EVM account and storage proofs returned by eth_getProof against a block state root. |
| [withdrawal-log-gap](https://github.com/kenny-ish/withdrawal-log-gap) | Python | Detect missing OP Stack MessagePassed withdrawal logs by reconciling nonce state, event hashes, and sentMessages through JSON-RPC. |
| [solana-stake-lockup-gate](https://github.com/kenny-ish/solana-stake-lockup-gate) | Python | Check whether a Solana stake withdrawal signer passes authority and lockup gates using one RPC snapshot |
| [selector-shadow-map](https://github.com/kenny-ish/selector-shadow-map) | Python | Find Solidity-style dispatcher selector collisions between two deployed EVM runtimes using JSON-RPC bytecode |
| [role-ledger](https://github.com/kenny-ish/role-ledger) | Python | Rebuild OpenZeppelin AccessControl role holders from RoleGranted/RoleRevoked logs, verify them with hasRole and getRoleMember, and flag risky admin setups over plain JSON-RPC. |
| [bip32-path-tool](https://github.com/kenny-ish/bip32-path-tool) | Python | Parse, validate and explain BIP32/BIP44 derivation paths, and generate address-index ranges |
| [erc1155-supply-audit](https://github.com/kenny-ish/erc1155-supply-audit) | Python | Reconcile ERC-1155 mint and burn logs with totalSupply for one token ID using only EVM JSON-RPC. |
| [erc20-transfer-policy-probe](https://github.com/kenny-ish/erc20-transfer-policy-probe) | Python | Read-only ERC-20 transfer probes that classify accepted, false, and reverted calls across amounts with optional JSON-RPC state overrides. |
| [oracle-round-audit](https://github.com/kenny-ish/oracle-round-audit) | Python | Audit Chainlink AggregatorV3 proxy rounds for staleness, gaps, abnormal moves, and aggregator changes using only EVM JSON-RPC. |
| [solana-alt-gate](https://github.com/kenny-ish/solana-alt-gate) | Python | Check whether a Solana address lookup table and requested indexes are usable in one RPC snapshot |

...and 69 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
