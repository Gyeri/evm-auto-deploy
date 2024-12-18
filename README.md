# EVM Auto Deploy

A tool for automatically deploying Ethereum smart contracts to various networks.

## Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)
- Ethereum private key
- Ethereum RPC node URL

## Getting Started

To use **EVM Auto Deploy**, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Gyeri/evm-auto-deploy.git
   ```

2. Goto the root diretory:

   ```bash
   cd evm-auto-deploy
   ```
   
3. Install the dependencies:
   
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory with the following variables:

   ```bash
   nano .env
   ```
   ### Example `.env` file

   ```bash
   PRIVATE_KEY=Your Ethereum private key
   ```

6. Add your desired chain configuration to `Testnet` or `mainnet`.

   Testnet
   ```bash
   nano chains/testnet.json
   ```
   Mainnet
   ```bash
   nano chains/mainnet.json
   ```

8. Run the script:

   ```bash
   npm start
   ```


## Installation

To install the dependencies, run the following command:

```bash
npm install
```

## Usage

To use **EVM Auto Deploy**, simply run the script:

```bash
npm start
```

Follow the prompts to select the network, enter the token name, symbol, and supply, and deploy the contract.


**EVM Auto Deploy** is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
