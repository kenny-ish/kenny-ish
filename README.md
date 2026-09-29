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
| [constant-product-pool](https://github.com/kenny-ish/constant-product-pool) | Solidity | Uniswap v2 style constant-product AMM pool for two ERC-20 tokens with LP shares, 0.3% fee, slippage limits and reentrancy guard |
| [halving-countdown](https://github.com/kenny-ish/halving-countdown) | Python | Bitcoin halving countdown with block-time based ETA, current and next block subsidy |
| [minimal-erc20](https://github.com/kenny-ish/minimal-erc20) | Solidity | Gas-conscious ERC-20 token with owner mint, burn, infinite-allowance shortcut and custom errors, tested with Foundry |
| [evm-chain-directory](https://github.com/kenny-ish/evm-chain-directory) | TypeScript | Offline directory of EVM chains (chain id, currency, explorer, public RPC) with search and live RPC chain-id verification |
| [btc-difficulty-rs](https://github.com/kenny-ish/btc-difficulty-rs) | Rust | Bitcoin compact-bits, target, difficulty and network hashrate conversions, plus solo-mining odds for a given hashrate |
| [basefee-predictor](https://github.com/kenny-ish/basefee-predictor) | Go | Project EIP-1559 base fees for the next blocks with full, target and empty blocks |
| [eth-node-healthcheck](https://github.com/kenny-ish/eth-node-healthcheck) | Shell | Nagios-style health check for Ethereum execution clients: sync status, head block age and peer count via JSON-RPC |
| [blob-fee-monitor](https://github.com/kenny-ish/blob-fee-monitor) | Python | Watch EIP-4844 blob fees on Ethereum: blob base fee, blob space utilization and the cost of posting a blob, from eth_feeHistory |
| [block-gas-usage](https://github.com/kenny-ish/block-gas-usage) | TypeScript | Chart gas usage versus the gas limit for the last N blocks of any EVM chain in the terminal |
| [btc-fee-stats](https://github.com/kenny-ish/btc-fee-stats) | Python | Bitcoin fee dashboard in the terminal: recommended fees, mempool backlog and recent blocks from mempool.space |
| [eth-timelock-vault](https://github.com/kenny-ish/eth-timelock-vault) | Solidity | Lock ETH until a chosen timestamp, top up or extend the lock but never shorten it, withdraw when it expires |
| [mini-block-explorer](https://github.com/kenny-ish/mini-block-explorer) | JavaScript | Small Ethereum block explorer page that only talks to a JSON-RPC node: recent blocks, block transactions and transaction details |
| [sha256-rs](https://github.com/kenny-ish/sha256-rs) | Rust | SHA-256 (FIPS 180-4) in safe Rust with a streaming API and a sha256sum-style CLI |
| [commit-reveal-lottery](https://github.com/kenny-ish/commit-reveal-lottery) | Solidity | On-chain ETH lottery using commit-reveal randomness from all participants, with forfeits for non-revealers and full refunds if nobody reveals |
| [wallet-health-check](https://github.com/kenny-ish/wallet-health-check) | Python | Check one address across Ethereum, Base, Arbitrum, OP, BNB Chain and Polygon: balances, stuck transactions and EIP-7702 delegations |

...and 3 more in the [repositories tab](https://github.com/kenny-ish?tab=repositories).
