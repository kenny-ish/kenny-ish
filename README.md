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
| [btc-block-intervals](https://github.com/kenny-ish/btc-block-intervals) | Go | Analyze recent Bitcoin block intervals from mempool.space and compare them with the exponential distribution of a Poisson process |
| [crypto-address-classifier](https://github.com/kenny-ish/crypto-address-classifier) | Python | Identify which chain and address type a string belongs to (EVM, Bitcoin, Solana, Tron, Cosmos, Litecoin...) with checksum checks |
| [calldata-decoder](https://github.com/kenny-ish/calldata-decoder) | TypeScript | Decode ERC-20/ERC-721/WETH transaction calldata by selector and flag risky patterns like unlimited approvals |
| [rpc-timing-sh](https://github.com/kenny-ish/rpc-timing-sh) | Shell | Break down JSON-RPC latency into DNS, TCP, TLS and server time with curl timing variables, to see where the milliseconds go |
| [gas-oracle-server](https://github.com/kenny-ish/gas-oracle-server) | Go | HTTP gas oracle serving EIP-1559 fee suggestions from eth_feeHistory percentiles, refreshed in the background |
| [rpc-list-audit](https://github.com/kenny-ish/rpc-list-audit) | Python | Find dead endpoints in the chainlist and ethereum-lists RPC lists, reporting only failures that look the same from anywhere: NXDOMAIN, HTTP 410, revoked API keys, wrong chain id |
| [name-registry](https://github.com/kenny-ish/name-registry) | Solidity | ENS-style name registry with yearly fees, expiry and grace period, renewals, transfers and address resolution |
| [nonce-watch-go](https://github.com/kenny-ish/nonce-watch-go) | Go | Watch EVM addresses and report every new outgoing transaction by polling their account nonce |
| [impermanent-loss](https://github.com/kenny-ish/impermanent-loss) | Python | Impermanent loss calculator for Uniswap v2 style pools and v3 concentrated ranges |
| [multichain-block-monitor](https://github.com/kenny-ish/multichain-block-monitor) | TypeScript | Live table of block height, block time, gas usage and base fee across Ethereum, Base, Arbitrum, Optimism, Polygon and BSC |
| [constant-product-pool](https://github.com/kenny-ish/constant-product-pool) | Solidity | Uniswap v2 style constant-product AMM pool for two ERC-20 tokens with LP shares, 0.3% fee, slippage limits and reentrancy guard |
| [halving-countdown](https://github.com/kenny-ish/halving-countdown) | Python | Bitcoin halving countdown with block-time based ETA, current and next block subsidy |
| [minimal-erc20](https://github.com/kenny-ish/minimal-erc20) | Solidity | Gas-conscious ERC-20 token with owner mint, burn, infinite-allowance shortcut and custom errors, tested with Foundry |
| [evm-chain-directory](https://github.com/kenny-ish/evm-chain-directory) | TypeScript | Offline directory of EVM chains (chain id, currency, explorer, public RPC) with search and live RPC chain-id verification |
| [btc-difficulty-rs](https://github.com/kenny-ish/btc-difficulty-rs) | Rust | Bitcoin compact-bits, target, difficulty and network hashrate conversions, plus solo-mining odds for a given hashrate |

...and 13 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
