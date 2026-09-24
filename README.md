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
| [commit-reveal-lottery](https://github.com/kenny-ish/commit-reveal-lottery) | Solidity | On-chain ETH lottery using commit-reveal randomness from all participants, with forfeits for non-revealers and full refunds if nobody reveals |
| [wallet-health-check](https://github.com/kenny-ish/wallet-health-check) | Python | Check one address across Ethereum, Base, Arbitrum, OP, BNB Chain and Polygon: balances, stuck transactions and EIP-7702 delegations |
| [abi-lite](https://github.com/kenny-ish/abi-lite) | TypeScript | Solidity ABI encoder/decoder for static types, strings and bytes, with bigint support |
| [evm-disassembler-rs](https://github.com/kenny-ish/evm-disassembler-rs) | Rust | Disassemble EVM bytecode into opcodes with PUSH data, list the 4-byte selectors it dispatches on and detect the Solidity metadata tail |
| [erc4626-vault](https://github.com/kenny-ish/erc4626-vault) | Solidity | Minimal ERC-4626 tokenized vault with correct rounding directions and virtual-share protection against the inflation attack |
