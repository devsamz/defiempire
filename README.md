# DeFi Empire

This project is for building a DeFi Kingdom clone, an exploration of the decentralized finance universe. The project consists of two contracts: an ERC20 token contract, which handles the creation, distribution, and management of a custom cryptocurrency, and a Vault contract, which handles secure storage and asset management features. Both contracts are deployed on the custom LekSubnet network.

## Steps

### 1. Deploy LekSubnet Network with Avalanche CLI

Follow the [Avalanche CLI documentation](https://docs.avax.network/) to deploy your own subnet. Ensure you have the Avalanche CLI installed and configured correctly.

### 2. Add LekSubnet Network to Metamask

1. Open Metamask.
2. Click on the network dropdown at the top.
3. Select "Custom RPC."
4. Enter the following details:
    - **Network Name:** LekSubnet
    - **New RPC URL:** `http://127.0.0.1:64806/ext/bc/2CjwstEsKHrUabbdG8xQCKvmZDZ2hjayvQZkYFroiWyXWMhmWZ/rpc`
    - **Chain ID:** `34567`
    - **Currency Symbol:** LEKS

### 3. Import the Funded Address

Use the private key provided to import the funded address into Metamask. This will be the address used for deploying and interacting with contracts.

1. In Metamask, go to the account dropdown.
2. Select "Import Account."
3. Enter the private key and click "Import."

### 4. Deploy/Interact with Remix

1. Open [Remix](https://remix.ethereum.org/).
2. Connect your Metamask wallet to Remix.
3. Load your Solidity contracts into Remix.
4. Compile and deploy the ERC20 token contract and Vault contract using the LekSubnet network.

## Subnet Details

- **RPC URL:** `http://127.0.0.1:64806/ext/bc/2CjwstEsKHrUabbdG8xQCKvmZDZ2hjayvQZkYFroiWyXWMhmWZ/rpc`
- **Network Name:** LekSubnet
- **Chain ID:** `34567`
- **Currency Symbol:** LEKS