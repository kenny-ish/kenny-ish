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
| [block-builder-share](https://github.com/kenny-ish/block-builder-share) | Python | Measure Ethereum block builder market share over recent blocks from on-chain extraData and fee recipients |
| [l2-fee-compare](https://github.com/kenny-ish/l2-fee-compare) | TypeScript | Compare the current cost of a transfer and a swap across Ethereum, L2s and sidechains using live gas prices and token prices |
| [vanity-difficulty](https://github.com/kenny-ish/vanity-difficulty) | Python | Estimate how long a vanity address search takes for EVM, Solana and Bitcoin prefixes at a given key rate |
| [utxo-coin-selection](https://github.com/kenny-ish/utxo-coin-selection) | Go | Bitcoin coin selection with Branch and Bound (changeless) and largest-first fallback, scored by the waste metric |
| [sandwich-attack-sim](https://github.com/kenny-ish/sandwich-attack-sim) | Rust | Simulate MEV sandwich attacks on a constant-product pool to see how slippage tolerance determines what a searcher can extract |
| [solana-epoch-progress](https://github.com/kenny-ish/solana-epoch-progress) | Python | Solana epoch progress and ETA from RPC slot data, using recent performance samples for real slot times |
| [btc-block-intervals](https://github.com/kenny-ish/btc-block-intervals) | Go | Analyze recent Bitcoin block intervals from mempool.space and compare them with the exponential distribution of a Poisson process |
| [crypto-address-classifier](https://github.com/kenny-ish/crypto-address-classifier) | Python | Identify which chain and address type a string belongs to (EVM, Bitcoin, Solana, Tron, Cosmos, Litecoin...) with checksum checks |
| [calldata-decoder](https://github.com/kenny-ish/calldata-decoder) | TypeScript | Decode ERC-20/ERC-721/WETH transaction calldata by selector and flag risky patterns like unlimited approvals |
| [rpc-timing-sh](https://github.com/kenny-ish/rpc-timing-sh) | Shell | Break down JSON-RPC latency into DNS, TCP, TLS and server time with curl timing variables, to see where the milliseconds go |
| [gas-oracle-server](https://github.com/kenny-ish/gas-oracle-server) | Go | HTTP gas oracle serving EIP-1559 fee suggestions from eth_feeHistory percentiles, refreshed in the background |
| [rpc-list-audit](https://github.com/kenny-ish/rpc-list-audit) | Python | Find dead endpoints in the chainlist and ethereum-lists RPC lists, reporting only failures that look the same from anywhere: NXDOMAIN, HTTP 410, revoked API keys, wrong chain id |
| [name-registry](https://github.com/kenny-ish/name-registry) | Solidity | ENS-style name registry with yearly fees, expiry and grace period, renewals, transfers and address resolution |
| [nonce-watch-go](https://github.com/kenny-ish/nonce-watch-go) | Go | Watch EVM addresses and report every new outgoing transaction by polling their account nonce |
| [impermanent-loss](https://github.com/kenny-ish/impermanent-loss) | Python | Impermanent loss calculator for Uniswap v2 style pools and v3 concentrated ranges |

...and 19 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
