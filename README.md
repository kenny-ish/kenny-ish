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
| [bip32-path-tool](https://github.com/kenny-ish/bip32-path-tool) | Python | Parse, validate and explain BIP32/BIP44 derivation paths, and generate address-index ranges |
| [erc1155-supply-audit](https://github.com/kenny-ish/erc1155-supply-audit) | Python | Reconcile ERC-1155 mint and burn logs with totalSupply for one token ID using only EVM JSON-RPC. |
| [erc20-transfer-policy-probe](https://github.com/kenny-ish/erc20-transfer-policy-probe) | Python | Read-only ERC-20 transfer probes that classify accepted, false, and reverted calls across amounts with optional JSON-RPC state overrides. |
| [oracle-round-audit](https://github.com/kenny-ish/oracle-round-audit) | Python | Audit Chainlink AggregatorV3 proxy rounds for staleness, gaps, abnormal moves, and aggregator changes using only EVM JSON-RPC. |
| [solana-alt-gate](https://github.com/kenny-ish/solana-alt-gate) | Python | Check whether a Solana address lookup table and requested indexes are usable in one RPC snapshot |
| [arb-batch-status](https://github.com/kenny-ish/arb-batch-status) | Python | Show which sequencer batch holds an Arbitrum block or transaction, its L1 confirmations, and whether it is below the safe and finalized heads, using only JSON-RPC and NodeInterface |
| [evm-cbor-audit](https://github.com/kenny-ish/evm-cbor-audit) | Python | Decode Solidity CBOR metadata trailers from deployed EVM bytecode using only JSON-RPC |
| [evm-state-anchor-audit](https://github.com/kenny-ish/evm-state-anchor-audit) | Python | Compare EVM RPC providers using block hashes and EIP-1898 state reads to find lag, inconsistent data and unsupported historical queries |
| [evm-commitment-auditor](https://github.com/kenny-ish/evm-commitment-auditor) | Python | Recompute EVM transaction, receipt, and log bloom commitments from JSON-RPC responses. |
| [paymaster-runway-check](https://github.com/kenny-ish/paymaster-runway-check) | Python | Estimate how long each ERC-4337 paymaster can keep sponsoring UserOperations from its EntryPoint deposit, using UserOperationEvent logs and getDepositInfo over JSON-RPC. |
| [safe-multisig-inspector](https://github.com/kenny-ish/safe-multisig-inspector) | Python | Inspect a Safe multisig on-chain: version, owners and threshold, nonce, modules, guard and fallback handler |
| [erc165-interface-auditor](https://github.com/kenny-ish/erc165-interface-auditor) | Python | Read-only ERC-165 matrix audit for NFT interface claims, control-ID behavior, empty returns, and custom interface IDs over JSON-RPC. |
| [create2-deploy-rehearsal](https://github.com/kenny-ish/create2-deploy-rehearsal) | Python | Rehearse CREATE2 deployments through the deterministic deployment proxy without sending a transaction. |
| [userop-hash-recheck](https://github.com/kenny-ish/userop-hash-recheck) | Python | Recompute ERC-4337 userOpHash values from a handleOps transaction's calldata and verify them against the EntryPoint's UserOperationEvent logs (v0.6 to v0.8) using only JSON-RPC. |
| [evm-log-range-probe](https://github.com/kenny-ish/evm-log-range-probe) | Python | Measure filter-specific eth_getLogs range limits across multiple EVM JSON-RPC providers. |

...and 59 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
