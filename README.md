# Pumpfun Solana Smart Contract

Welcome to the Pumpfun Solana Smart Contract repository. This repository contains the Rust/Anchor-based smart contract powering the Pumpfun ecosystem. Designed with robust features and innovative logic, this contract is built to manage token minting, liquidity pools, token swaps, and market cap-based launches on Raydium.
If you have any questions or need support, feel free to reach out, and we can discuss the best way to assist you.



## Key Features
The contract includes all the advanced features that define the Pumpfun platform:

✅ Token Minting
Seamlessly mint Pumpfun tokens to kickstart your liquidity pool.

✅ Create Liquidity Pools
Establish a pool with an initial 30 SOL virtual reserve, creating a strong foundation for token transactions.

✅ Add Liquidity
Contribute liquidity to grow the pool and enhance token marketability.

✅  Token Swapping
Facilitates token swaps based on a dynamic bonding curve price, calculated as:
`Price = Virtual SOL Reserve / Virtual Token Reserve.`

✅ Raydium Launch Integration

Automatically launch on Raydium when the token’s market cap (price × 10⁹) reaches $69M. At launch:
- $12K in SOL ($24K total liquidity) is added to Raydium.
- Remaining liquidity reserves are allocated to the Pumpfun team for platform growth.

## Unique Bonding Curve Logic

The contract uses a custom bonding curve mechanism defined by:
`X × Y = K²`
- X: Token price.
- Y: Token supply in the pool.
This ensures a dynamic and balanced liquidity model tailored to Pumpfun’s tokenomics.

## Testing and Validation

### The contract includes comprehensive test cases to validate functionality, covering all features except Raydium Launch (which integrates with the ongoing project).
- Remove Virtual LP and Create Raydium Pool:

### LP Creation Fee
- A 5% reserve fee applies when creating LPs, ensuring sustainable liquidity pool growth.

## Why Choose Pumpfun?

By leveraging this smart contract, you gain access to a cutting-edge decentralized financial ecosystem tailored for scalability, efficiency, and innovation. It’s the ideal solution for managing tokens and liquidity in a dynamic market environment.

```
For inquiries, support, or collaboration opportunities, don’t hesitate to reach out. Let’s revolutionize decentralized finance together!
```


## 👤 Contact Me

#### Discord: [@knightworlds](https://discordapp.com/users/965772784653443215)

#### Twitter: [@knightworlds127](https://twitter.com/knightworlds127)   

#### Telegram: [@knightworlds](https://t.me/knightworlds)   