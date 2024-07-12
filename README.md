# MyToken Contract Summary

## Overview

MyToken is an ERC20 token contract implemented in Solidity. It provides basic functionalities such as transferring tokens, burning tokens, and minting new tokens.

## Description

The MyToken contract is a standard ERC20 token implementation written in Solidity. It allows users to transfer tokens to other addresses, burn their own tokens to reduce the total supply, and enables the contract owner to mint new tokens as needed. The token's name and symbol are set during the deployment of the contract, providing flexibility in branding and identification.

## Getting Started

### Installing

To get started with the MyToken contract, you need to have the Solidity compiler and a development environment like Hardhat or Truffle installed.

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/mytoken.git
   cd mytoken
   ```
2. Install Dependencies:
   ```sh
   npm install
   ```

### Executing Program

To deploy and interact with the MyToken contract, follow these steps:

Compile the contract:
  
  ```sh
  npx hardhat compile
  ```
Deploy the contract:
  ```sh
  npx hardhat run scripts/deploy.js --network <network-name>
  ```
Transfer Tokens:
  ```sh
  await myToken.transfer(addressTo, amount);
  ```
Burn Tokens:
  ```sh
  await myToken.burn(amount);
  ```

Mint Tokens (only accessible to contract owner):
  ```sh
  await myToken.mint(addressTo, amount);
  ```
Help
For common issues and troubleshooting:

Ensure you have the correct network configuration in your Hardhat or Truffle setup.
Verify that your wallet is connected and has sufficient funds for gas fees.
For more detailed help, run:
```sh
  npx hardhat help
```

### Authors
James Akolo
### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

