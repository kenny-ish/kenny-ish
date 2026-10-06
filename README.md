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
| [keystore-backup](https://github.com/kenny-ish/keystore-backup) | Shell | Encrypted, rotated backups of wallet keystores or validator keys with gpg AES-256, checksums and restore verification |
| [keystore-inspector](https://github.com/kenny-ish/keystore-inspector) | Go | Inspect Ethereum keystore V3 JSON files without the password: KDF strength, cipher, MAC and address, with weak-parameter warnings |
| [solana-token-holders](https://github.com/kenny-ish/solana-token-holders) | Python | Show supply and the largest holders of any Solana SPL token from RPC alone, resolving token accounts to their owner wallets |
| [blob-basefee-rs](https://github.com/kenny-ish/blob-basefee-rs) | Rust | EIP-4844 blob base fee calculator in Rust using the spec's fake_exponential, with Cancun and Prague update fractions |
| [univ3-twap-oracle](https://github.com/kenny-ish/univ3-twap-oracle) | Python | Compute a manipulation-resistant TWAP from any Uniswap v3 pool's built-in oracle via observe(), and compare it with the spot price |
| [eip1559-sim-rs](https://github.com/kenny-ish/eip1559-sim-rs) | Rust | Simulate EIP-1559 base fee dynamics in Rust under demand shocks and see how quickly the fee converges back to the target |
| [block-at-timestamp](https://github.com/kenny-ish/block-at-timestamp) | TypeScript | Find the Ethereum block for any date with an interpolation-guided binary search over JSON-RPC, counting every RPC call |
| [erc4337-userop-stats](https://github.com/kenny-ish/erc4337-userop-stats) | Python | Account abstraction activity from EntryPoint logs: UserOperation counts, success rate, paymaster share and gas costs over recent blocks |
| [rpc-failover-proxy](https://github.com/kenny-ish/rpc-failover-proxy) | Go | JSON-RPC reverse proxy with automatic failover across multiple upstreams, cooldowns, a method denylist and a health page |
| [proxy-detector](https://github.com/kenny-ish/proxy-detector) | Python | Detect what's behind an EVM address: EOA, EIP-7702 delegated account, EIP-1167 clone, EIP-1967 transparent/UUPS/beacon proxy or plain contract |
| [code-hash-compare](https://github.com/kenny-ish/code-hash-compare) | Go | Check whether the same address holds identical bytecode on several EVM chains by hashing eth_getCode results |
| [eth-burn-tracker](https://github.com/kenny-ish/eth-burn-tracker) | Python | Measure ETH burned by EIP-1559 base fees and EIP-4844 blob fees over recent blocks, from block headers and fee history |
| [wallet-connect-demo](https://github.com/kenny-ish/wallet-connect-demo) | JavaScript | Plain-JS wallet connection demo with EIP-6963 multi-wallet discovery, chain switching, balance lookup and message signing |
| [block-builder-share](https://github.com/kenny-ish/block-builder-share) | Python | Measure Ethereum block builder market share over recent blocks from on-chain extraData and fee recipients |
| [l2-fee-compare](https://github.com/kenny-ish/l2-fee-compare) | TypeScript | Compare the current cost of a transfer and a swap across Ethereum, L2s and sidechains using live gas prices and token prices |

...and 32 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
