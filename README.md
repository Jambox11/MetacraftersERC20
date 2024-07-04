MyToken Contract Summary

Overview: MyToken is an ERC20 token contract implemented in Solidity. It provides basic functionalities such as transferring tokens, burning tokens, and minting new tokens.

Features:

Name and Symbol: Set during deployment.
Transfer: Users can transfer tokens to other addresses.
Burn: Users can burn their own tokens to reduce the token supply.
Mint: Only the contract owner can mint new tokens.
Deployment:

Deploy the contract with desired name and symbol.
Contract owner can mint new tokens as needed.
Users can transfer tokens or burn their own tokens.
Usage:

Transfer Tokens: transfer(address to, uint256 amount)
Burn Tokens: burn(uint256 amount)
Mint Tokens: mint(address to, uint256 amount) (only accessible to contract owner)
License: MIT License
