# RewardToken Contract

## Vision

The **RewardToken** contract is a simple ERC-20 token implementation designed to facilitate the distribution and management of reward tokens. This contract enables the creation, transfer, and minting of tokens, and includes basic functionalities for balance tracking and allowance management. It serves as a foundation for applications requiring a reward mechanism or token-based incentives.

## Features

- **Token Creation**: Initially mints 1,000,000 tokens to the deployer.
- **Ownership Management**: Only the contract owner can mint new tokens.
- **Basic ERC-20 Functionality**: Supports balance checks, transfers, and allowances.

## Flowchart

Below is a flowchart illustrating the primary interactions with the `RewardToken` contract:

```plaintext
+----------------+      +-----------------+
|                |      |                 |
|  User          |      |  Contract Owner |
|                |      |                 |
+--------+-------+      +--------+--------+
         |                       |
         |                       |
         | Transfer Tokens        |
         |----------------------->|
         |                       |
         |                       |
         |                       |
         |                       |
         |                       |
         | Mint Tokens            |
         |<-----------------------|
         |                       |
         |                       |
         |                       |
         | View Balance           |
         |----------------------->|
         |                       |
         |                       |
         |                       |
         | View Allowance         |
         |----------------------->|
         |                       |
         |                       |
         |                       |
         | Approve Spending       |
         |----------------------->|
         |                       |
         |                       |
         |                       |
         | Transfer From          |
         |----------------------->|
         |                       |
         |                       |
         |                       |

```
## Installation

To set up the Blockchain Academy project on your local machine, follow these steps:

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 14.x or later)
- [npm](https://www.npmjs.com/) (Node Package Manager, included with Node.js)
- [Truffle](https://www.trufflesuite.com/truffle) or [Hardhat](https://hardhat.org/) (for Ethereum development and testing)
- [Ganache](https://www.trufflesuite.com/ganache) (optional, for local blockchain testing)

### Clone the Repository

First, clone the repository to your local machine:

git clone https://github.com/yourusername/BlockchainAcademy.git<br/>
cd BlockchainAcademy

### Install Dependencies
Navigate to the project directory and install the necessary Node.js packages:<br/>
npm install<br/>
This will install all dependencies listed in the package.json file.

