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
| [erc20-allowance-checker](https://github.com/kenny-ish/erc20-allowance-checker) | Python | Check an address's ERC-20 and Permit2 allowances against common DeFi spenders with eth_call |
| [stale-pyc](https://github.com/kenny-ish/stale-pyc) | Python | Find .pyc files Python would still load after the source changed: same-size edits within the same second, mtime-preserving copies, unchecked-hash caches |
| [node-disk-alert](https://github.com/kenny-ish/node-disk-alert) | Shell | Disk usage and growth-rate alerts for blockchain nodes, predicting days until full and notifying via Telegram |
| [univ3-position-reader](https://github.com/kenny-ish/univ3-position-reader) | Python | Read a Uniswap v3 LP position NFT on-chain: pool, range, in-range status, current token amounts and uncollected owed tokens |
| [amm-lp-simulator](https://github.com/kenny-ish/amm-lp-simulator) | Rust | Monte Carlo simulator of a constant-product AMM LP position vs holding, with arbitrageurs, fees and GBM price paths |
| [mutant-check](https://github.com/kenny-ish/mutant-check) | Python | Check that a test really covers a guard: replace one spot in the code, rerun the tests, restore the file, and report killed or survived |
| [nonce-gap-checker](https://github.com/kenny-ish/nonce-gap-checker) | TypeScript | Detect stuck transactions by comparing an address's latest and pending nonce on several EVM chains |
| [keystore-backup](https://github.com/kenny-ish/keystore-backup) | Shell | Encrypted, rotated backups of wallet keystores or validator keys with gpg AES-256, checksums and restore verification |
| [keystore-inspector](https://github.com/kenny-ish/keystore-inspector) | Go | Inspect Ethereum keystore V3 JSON files without the password: KDF strength, cipher, MAC and address, with weak-parameter warnings |
| [solana-token-holders](https://github.com/kenny-ish/solana-token-holders) | Python | Show supply and the largest holders of any Solana SPL token from RPC alone, resolving token accounts to their owner wallets |
| [blob-basefee-rs](https://github.com/kenny-ish/blob-basefee-rs) | Rust | EIP-4844 blob base fee calculator in Rust using the spec's fake_exponential, with Cancun and Prague update fractions |
| [univ3-twap-oracle](https://github.com/kenny-ish/univ3-twap-oracle) | Python | Compute a manipulation-resistant TWAP from any Uniswap v3 pool's built-in oracle via observe(), and compare it with the spot price |
| [eip1559-sim-rs](https://github.com/kenny-ish/eip1559-sim-rs) | Rust | Simulate EIP-1559 base fee dynamics in Rust under demand shocks and see how quickly the fee converges back to the target |
| [block-at-timestamp](https://github.com/kenny-ish/block-at-timestamp) | TypeScript | Find the Ethereum block for any date with an interpolation-guided binary search over JSON-RPC, counting every RPC call |
| [erc4337-userop-stats](https://github.com/kenny-ish/erc4337-userop-stats) | Python | Account abstraction activity from EntryPoint logs: UserOperation counts, success rate, paymaster share and gas costs over recent blocks |

...and 39 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
