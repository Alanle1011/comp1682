## COMP1682 Final Year Individual Project

Welcome to the COMP1682 Final Year Individual Project repository! This repository contains the codebase for a NFT marketplace developed as part of the final year project.

## Overview

This project aims to create a decentralized NFT marketplace where users can buy, sell, and trade non-fungible tokens (NFTs) securely on the blockchain. The repository is organized into three main subdirectories:

1. **contract-marketplace**: Contains the smart contract code for the NFT marketplace. This includes the Solidity contracts responsible for managing NFT ownership, transfers, and marketplace functionality.

2. **frontend-marketplace**: Houses the frontend code for the NFT marketplace. This directory includes the user interface components built using HTML, CSS, and JavaScript frameworks like React.js or Vue.js. Users interact with the marketplace through this interface.

3. **subgraph-marketplace**: Stores the subgraph code for indexing and querying blockchain data relevant to the NFT marketplace. This directory contains the GraphQL schema and mappings necessary to extract and structure blockchain data for efficient querying by the frontend.

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the Repository**: 

2. **Install Dependencies**: 
- Navigate to each subdirectory (`contract-marketplace`, `frontend-marketplace`, `subgraph-marketplace`) and run:
```bash
npm run dev
# or
yarn dev
```
3. **Configure Environment Variables**: 
- Ensure that you have necessary environment variables configured for connecting to your blockchain network and other services (e.g., Infura API keys, wallet addresses, etc.). Refer to the respective `README.md` files in each subdirectory for specific configuration instructions.

4. **Run the Applications**: 
- Start the smart contract deployment process and deploy the contracts to your chosen blockchain network (e.g., Ethereum).
- Launch the frontend application to interact with the NFT marketplace.
- Deploy the subgraph to index blockchain data.
## Contributing

Contributions to the project are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
