# Real Estate NFT

This repository contains the smart contract code for the Real Estate NFT project. Real Estate NFTs represent unique digital assets representing ownership or rights to real-world properties.

## Overview

The Real Estate NFT project is built on the Ethereum blockchain using the ERC721 standard. Each NFT token represents ownership of a specific real estate property. The metadata associated with each token includes information about the property, such as its location, description, and images.

## Smart Contract

The smart contract code is implemented in Solidity and is located in the `contracts/` directory. The main contract file is `RealEstate.sol`, which defines the RealEstate contract inheriting from the ERC721URIStorage contract provided by OpenZeppelin. This contract includes functions for minting new NFTs and retrieving the total supply of tokens.

## Deployment

The Real Estate NFT contract has been deployed on the Sepolia testnet. Below are the deployment details:

- **Network:** Sepolia Testnet
- **Contract Address:** 0xAfd2746431a8caF713fb7320ce1Dcc2c2f022019

## Usage

### Minting Tokens

To mint a new Real Estate NFT, users can call the `mint` function, providing the token's metadata URI as an argument. This function assigns a new token ID and sets the metadata URI for the token. Only the contract owner can mint new tokens.

### Total Supply

The `totalSupply` function allows users to query the total number of Real Estate NFTs minted so far.
