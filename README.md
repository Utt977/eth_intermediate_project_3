# eth_intermediate_project_3
This is eth intermediate course of module 3 of project of 3.

# MyToken
MyToken is an Ethereum ERC721 token contract built using Solidity. It provides a basic implementation of an NFT (non-fungible token) with the ability to mint new tokens.

## Features

- ERC721 compliant: MyToken follows the ERC721 standard, which allows for the creation of unique and indivisible tokens.
- Minting: The contract owner can mint new tokens using the `safeMint` function, which assigns a unique `tokenId` to the specified address.
- Burning: The contract inherits the burn functionality from `ERC721Burnable`, allowing token owners to burn (destroy) their tokens.

## Prerequisites

To deploy and interact with the MyToken contract, you will need the following:

- An Ethereum development environment such as Remix IDE or Truffle.
- A compatible Ethereum wallet (e.g., MetaMask) connected to your development environment.

## Deployment

Follow these steps to deploy the MyToken contract using Remix IDE:

1. Open Remix IDE (https://remix.ethereum.org/) and create a new file named "MyToken.sol".
2. Copy and paste the provided Solidity code into "MyToken.sol".
3. Make sure the Solidity Compiler version is set to at least 0.8.9.
4. Compile the code by clicking the "Compile" button.
5. Once the code is successfully compiled, switch to the "Deploy & Run Transactions" panel.
6. Select "Injected Web3" from the "Environment" dropdown to connect Remix to your Ethereum-enabled browser wallet (e.g., MetaMask).
7. In the "Deploy" section, select the "MyToken" contract from the dropdown.
8. Click the "Deploy" button and confirm the transaction in your browser wallet.

After deployment, we will receive a transaction hash and a contract address.


