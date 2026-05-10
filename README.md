# Chainlink CCIP Cross-Chain Token (CCT) — Foundry

This repository contains my implementation of a Chainlink CCIP Cross-Chain Token (CCT) project using Foundry.

The project focuses on deploying and configuring Burn & Mint token pools across Avalanche Fuji and Arbitrum Sepolia for future reference and experimentation with cross-chain token transfers using Chainlink CCIP.

Here is the Cross chain message hash that can be viewed on CCIP explorer:

### Message ID - 0x612b581dae1f70edb6af50442f7bbb06c4588bc8431b760f08f5a7aa5f821bc5

### CCIP Explorer Link - https://ccip.chain.link/msg/612b581dae1f70edb6af50442f7bbb06c4588bc8431b760f08f5a7aa5f821bc5

## References

This work was built by following and studying the official Chainlink resources below:

- Chainlink Documentation - [Enable your tokens in CCIP (Burn & Mint): Register from an EOA using Foundry](https://docs.chain.link/ccip/tutorials/evm/cross-chain-tokens/register-from-eoa-burn-mint-foundry#overview)

- Chainlink & Solidity Bootcamp Video - [Deploy a Cross-Chain Token (CCT)](https://youtu.be/hxFydEiYDh4)

- Original Chainlink Example Repository - [smart-contract-examples](https://github.com/smartcontractkit/smart-contract-examples/blob/main/ccip/cct/foundry/README.md)

## Notes

This repository is intended primarily as a portfolio and learning reference.

The original scripts from the Chainlink example implementation were left unchanged.  
The main modifications in this version are related to deployed token and token pool configurations on:

- Avalanche Fuji
- Arbitrum Sepolia

This setup is useful for future CCIP testing, experimentation, and deployment reference.

## Tech Stack

- Solidity
- Foundry
- Chainlink CCIP
- Avalanche Fuji Testnet
- Arbitrum Sepolia Testnet

## Features

- Burn & Mint Cross-Chain Token setup
- CCIP token registration from an EOA
- Token pool deployment and configuration
- Cross-chain messaging infrastructure setup
- Foundry deployment and interaction scripts

## Reference
- More details can be obtained from the original README of the cloned example by Chainlink [here](https://github.com/smartcontractkit/smart-contract-examples/blob/main/ccip/cct/foundry/README.md)
