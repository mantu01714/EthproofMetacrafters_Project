## Mytoken Contract for EthProof Project

This repository contains the smart contract code for the "Mytoken" contract, which is part of the EthProof project submitted to the MetaCrafters team. The EthProof project aims to create a simple ERC-20 token contract for educational purposes.

## Introduction 

In this section, you will find essential details about the Mytoken contract, including its name, the version of Solidity used for its development, and the licensing information. These details provide a foundational understanding of the contract's identity and its permissions for use and distribution.

## Description

The Mytoken contract is a basic ERC-20 token contract written in Solidity. ERC-20 is a widely accepted standard for fungible tokens on the Ethereum blockchain. This contract allows for the creation of tokens and the transfer of tokens between Ethereum addresses.

## Contract Features

**Token Properties**
```
Token Name: Mytoken
Token Symbol: token
Total Supply: 0 (initially)
```

**Functions**

mint(address _to, uint256 _value) external

**Description:** Mint new tokens and assign them to the specified address.
**Parameters:**
_to: The address to which new tokens will be assigned.
_value: The number of tokens to mint.

**Usage:** This function allows for the creation of new tokens and increases the total token supply.

burn(uint256 _value) external

**Description:** Burn a specific amount of tokens owned by the sender.

**Parameters:**
_value: The number of tokens to burn.
Usage: This function allows token holders to burn their tokens, reducing the total token supply.

**Getting Started**
To interact with the Mytoken contract on the Ethereum blockchain, you can use Ethereum wallet applications such as MetaMask, or you can interact programmatically using Web3.js or ethers.js and for easy way use remix to getting started with smart contract on ethereum.

**License**
This project is licensed under the MIT License - see the LICENSE file for details.
