# 🚀 BUZZYVERSE - The MemeCoin Launchpad - EDUCHAIN HACKATHON 🎉

Welcome to the **MemeCoin Launchpad**! This project was built for the EDUCHAIN Hackathon, demonstrating a custom L1 subnet on EDUCHAIN that allows users to create, buy, and sell meme tokens in a fun and engaging environment.

### ✨ Key Features

- **💸 Custom Bonding Curve Precompile for Pricing**: 
  - Utilizes a custom bonding curve precompile that dynamically adjusts token prices based on market supply and demand.
  - Ensures fair pricing and maintains liquidity stability.

- **🌊 Decentralized Liquidity Creation**: 
  - Once a meme token reaches its funding goal, liquidity creation is triggered through the Native Liquidity Pool.
  - Early contributors receive rewards through the **Native Minter Precompile**, allowing them to mint additional tokens.

- **🔗 Cross-Chain Notifications via Interchain Messaging (ICM)**: 
  - Leverages EDUCHAIN's ICM to broadcast cross-chain notifications, ensuring state consistency across multiple subnets when liquidity is created.

- **🏪 Marketplace and User Engagement**: 
  - A **Marketplace** where users can view, explore, and trade all launched meme tokens.
  - A **Ranking Page** to highlight the top meme tokens within the community, enhancing visibility.

- **📊 User Dashboard Powered by AvaCloud API**: 
  - The **User Dashboard** provides comprehensive insights on token holdings, balances, recent transactions, and more.
  - AvaCloud API integration ensures users have detailed information on their investments.

- **💧 Community Faucet for EDU Tokens**: 
  - Users can claim 1 EDU every 24 hours to engage in transactions and meme token sales, powered by **Faucet.sol**.

### 🔄 Workflow Overview

1. **🛠️ Token Creation**: Users can create new meme tokens via the **Token Factory Contract**, specifying the details like name, symbol, and description.
2. **💰 Token Sale**: Meme tokens are sold using bonding curves that automatically adjust prices based on demand.
3. **🌐 Liquidity Creation**: Once the funding goal is reached, liquidity is added using the **Native Liquidity Pool** and cross-chain notifications are triggered.
4. **🏆 Reward Minting**: Contributors are rewarded after liquidity creation via **Native Minter Precompile**.
5. **🔔 Cross-Chain Messaging**: Notifications are sent using **ITeleporterMessenger** and **ITeleporterReceiver**, synchronizing liquidity states across subnets.

### 🛠️ Technical Stack Highlights

- **🌍 EDUCHAIN L1 Subnet**: Custom EDUCHAIN subnet that enables low transaction fees and high scalability.
- **📈 Custom Bonding Curve Precompile**: Determines dynamic pricing for meme tokens.
- **🔨 Native Minter Precompile**: Used for minting EDU rewards to contributors.
- **🔗 Interchain Messaging**: Utilizes **ITeleporterMessenger** and **ITeleporterReceiver** for cross-chain updates.
- **☁️ AvaCloud API**: Integrated for providing real-time token and transaction insights to users.

### 🚀 Installation

1. **📥 Clone the Repository**:
   ```bash
   git clone 
   ```
2. **📦 Install Dependencies**:
   - Navigate to the frontend and backend folders to install the required packages using `npm install` or `yarn`.
3. **⚙️ Configure Environment Variables**:
   - Add required RPC URLs, API keys, and other environment configurations.
4. **💻 Run Local Development Server**:
   - Start both backend and frontend using `npm run dev`.

### 📂 Project Structure
- **📜 contract**: Contains Solidity contracts for MemeCoin Launchpad, including Token Factory, Liquidity Pool, and related precompiles.
- **💻 frontend**: React-based frontend for interacting with MemeCoin Launchpad.
- **⚙️ precompile**: Custom bonding curve and native minter precompiles used for pricing and reward minting.

### 🌐 Live Demo


### 📌 GitHub Repository


### 🎥 YouTube Demo




### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

### 🙏 Acknowledgments
- **EDUCHAIN Network** for providing an amazing blockchain ecosystem.
- **EDUCHAIN Judges** for their support and consideration of this project.
