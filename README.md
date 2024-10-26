# go-zether

The official Go implementation of the [Zether](https://zether.org/) blockchain protocol, designed to empower miners and drive decentralization in a fair and robust ecosystem. Zether leverages an aggressive tokenomics structure, EVM compatibility, and Ethash-based Proof-of-Work (PoW) consensus, ensuring secure and decentralized operations.

## Key Features

- **Decentralized**: Built to support a fully decentralized, distributed network that promotes security and autonomy.
- **Proof of Work**: Utilizes Ethash, a battle-tested consensus mechanism ensuring network reliability and decentralization.
- **Aggressive Tokenomics**: High initial block rewards, decreasing over time, encourage long-term miner participation.
- **EVM Compatibility**: Supports the Ethereum Virtual Machine (EVM), allowing seamless deployment of smart contracts and DApps.
- **Fair Launch**: No premine or instamine, ensuring equitable distribution from the genesis block.
- **Low Transaction Fees**: Minimal fees make interactions affordable and efficient for all users.
- **No Uncle Rewards**: Focus on main blocks only, simplifying incentives and enhancing network clarity.

## Block Reward Structure

Zether adopts a decreasing block reward system, incentivizing sustained engagement over time. Below is the reward schedule:

| Block Range             | Reward per Block (ZTH) |
|-------------------------|------------------------|
| 0 - 100,000             | 10,000                |
| 100,001 - 200,000       | 9,000                 |
| 200,001 - 300,000       | 8,000                 |
| 300,001 - 400,000       | 7,000                 |
| 400,001 - 500,000       | 6,000                 |
| 500,001 - 600,000       | 5,000                 |
| 600,001 - 700,000       | 4,000                 |
| 700,001 - 800,000       | 3,000                 |
| 800,001 - 900,000       | 2,000                 |
| 900,001 - 1,000,000     | 1,000                 |
| ...                     | ...                   |
| 2,700,001 - onwards     | 10                    |

> For the full reward schedule, please refer to the [Emission Table](https://zether.org/emission).

## Technical Details

- **Chain ID**: 715131
- **Currency Ticker**: ZTH
- **Mining Algorithm**: Ethash
- **Average Block Time**: ~10 seconds
- **Max Supply**: Infinite
- **Foundation Fee**: 5% of block rewards
