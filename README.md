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
| [arb-batch-status](https://github.com/kenny-ish/arb-batch-status) | Python | Show which sequencer batch holds an Arbitrum block or transaction, its L1 confirmations, and whether it is below the safe and finalized heads, using only JSON-RPC and NodeInterface |
| [evm-cbor-audit](https://github.com/kenny-ish/evm-cbor-audit) | Python | Decode Solidity CBOR metadata trailers from deployed EVM bytecode using only JSON-RPC |
| [evm-state-anchor-audit](https://github.com/kenny-ish/evm-state-anchor-audit) | Python | Compare EVM RPC providers using block hashes and EIP-1898 state reads to find lag, inconsistent data and unsupported historical queries |
| [evm-commitment-auditor](https://github.com/kenny-ish/evm-commitment-auditor) | Python | Recompute EVM transaction, receipt, and log bloom commitments from JSON-RPC responses. |

...and 65 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
