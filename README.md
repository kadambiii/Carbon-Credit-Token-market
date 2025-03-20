# Carbon-Credit-Token-market
The Carbon Credit Marketplace is a decentralized application (DApp) built on the Neo X blockchain, utilizing smart contracts to facilitate the trading of carbon credits. This platform promotes sustainability by creating a transparent and efficient market for carbon offset trading.
# Features
Tokenized Carbon Credits: Carbon credits are represented as ERC20 tokens (CCT - CarbonCredit Token).
Decentralized Order Book: Users can create buy and sell orders for carbon credits.
User Reputation System: Tracks user trading history to build trust in the marketplace.
Admin Functions: Privileged users can mint new carbon credit tokens.
Responsive UI: Built with React and styled using Tailwind CSS for a modern, mobile-friendly interface.
Real-time Market Data: Live updates of order book and user balances.
Seamless Web3 Integration: Easy connection with MetaMask and other Web3 wallets.
# Tech Stack
Blockchain: Neo X (compatible with Ethereum)
Smart Contracts: Solidity
Frontend: React.js
Styling: Tailwind CSS
Web3 Integration: ethers.js
# Smart Contracts
CarbonCreditToken.sol: ERC20 token representing carbon credits.
CarbonMarketplace.sol: Handles the order book and trade execution.
# Components
LandingPage.js: The main entry point of the application, showcasing key features and statistics.
Marketplace.js: The core component for interacting with the carbon credit marketplace.
# Deployment Details
Smart Contracts
Network: NeoX T4 Testnet
# Frontend
Hosting: Local
CI/CD: GitHub Actions
# Demo
Check out our demo video to see the Carbon Credit Marketplace in action: Demo Video Link

# Setup d Installation
Clone the repository:

git clone [repository-url]
cd carbon-credit-marketplace
Install dependencies:

npm install
Set up environment variables: Create a .env file in the root directory and add the following:

REACT_APP_CONTRACT_ADDRESS=[deployed-marketplace-contract-address]
REACT_APP_TOKEN_ADDRESS=[deployed-token-contract-address]
Start the development server:

npm start
# Usage
Connect your Web3 wallet (e.g., MetaMask) to the application.
Ensure you have some CCT tokens and ETH for trading.
Navigate to the Marketplace tab to view the order book.
Create buy or sell orders for carbon credits.
Cancel your own orders if needed.
Admin users can mint new CCT tokens from the admin panel.
# Contributing
We welcome contributions to the Carbon Credit Marketplace! Please follow these steps:

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
# License
This project is licensed under the MIT License. See the LICENSE file for details.
