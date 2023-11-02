# Re-Entrancy Attack Demo

This project is a demonstration of a re-entrancy attack on Ethereum smart contracts. It includes two smart contracts, `GoodContract` and `BadContract`, written in Solidity.

## Setup

To set up this project, you need to install the dependencies using npm:

```bash
npm init --y
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat
```

## Contracts

### GoodContract

`GoodContract` is a smart contract that allows users to deposit and withdraw Ether. However, there is a re-entrancy vulnerability in the `withdraw` function.

### BadContract

`BadContract` is a smart contract that exploits the re-entrancy vulnerability in `GoodContract`. The `attack` function is used to initiate the attack.

## Testing

npx hardhat test

