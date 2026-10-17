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
| [evm-log-range-probe](https://github.com/kenny-ish/evm-log-range-probe) | Python | Measure filter-specific eth_getLogs range limits across multiple EVM JSON-RPC providers. |
| [timelock-queue-audit](https://github.com/kenny-ish/timelock-queue-audit) | Python | Audit Compound Timelock queue entries from RPC logs and on-chain state. |
| [op-output-root-check](https://github.com/kenny-ish/op-output-root-check) | Python | Recompute an OP Stack output root from an L2 node (eth_getProof + block header) and check it against the root claim of a dispute game on L1, including super root games |
| [skipguard](https://github.com/kenny-ish/skipguard) | Python | Fail a CI step when the tests it reports as green did not actually run: required tests skipped, filters that matched nothing, suites that skipped themselves |
| [token-gate-rehearsal](https://github.com/kenny-ish/token-gate-rehearsal) | Python | Simulate token-gated EVM calls with hypothetical native balances, ERC-20 balances and allowances using eth_call state overrides |
| [governor-proposal-audit](https://github.com/kenny-ish/governor-proposal-audit) | Python | Inspect Governor proposal state and voting deadlines through direct contract calls. |
| [erc20-allowance-checker](https://github.com/kenny-ish/erc20-allowance-checker) | Python | Check an address's ERC-20 and Permit2 allowances against common DeFi spenders with eth_call |
| [stale-pyc](https://github.com/kenny-ish/stale-pyc) | Python | Find .pyc files Python would still load after the source changed: same-size edits within the same second, mtime-preserving copies, unchecked-hash caches |
| [node-disk-alert](https://github.com/kenny-ish/node-disk-alert) | Shell | Disk usage and growth-rate alerts for blockchain nodes, predicting days until full and notifying via Telegram |
| [univ3-position-reader](https://github.com/kenny-ish/univ3-position-reader) | Python | Read a Uniswap v3 LP position NFT on-chain: pool, range, in-range status, current token amounts and uncollected owed tokens |
| [amm-lp-simulator](https://github.com/kenny-ish/amm-lp-simulator) | Rust | Monte Carlo simulator of a constant-product AMM LP position vs holding, with arbitrageurs, fees and GBM price paths |
| [mutant-check](https://github.com/kenny-ish/mutant-check) | Python | Check that a test really covers a guard: replace one spot in the code, rerun the tests, restore the file, and report killed or survived |
| [nonce-gap-checker](https://github.com/kenny-ish/nonce-gap-checker) | TypeScript | Detect stuck transactions by comparing an address's latest and pending nonce on several EVM chains |
| [keystore-backup](https://github.com/kenny-ish/keystore-backup) | Shell | Encrypted, rotated backups of wallet keystores or validator keys with gpg AES-256, checksums and restore verification |
| [keystore-inspector](https://github.com/kenny-ish/keystore-inspector) | Go | Inspect Ethereum keystore V3 JSON files without the password: KDF strength, cipher, MAC and address, with weak-parameter warnings |

...and 45 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
