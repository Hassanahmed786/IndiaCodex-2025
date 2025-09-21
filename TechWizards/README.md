# TechWizards - IndiaCodex 2025 Hackathon Submission

## 🎁 Project: Cardano NFT Gift Card dApp (Lovelace Treasury)

### Live Project Link
🚀 **[Try our app: https://lovelacetreasury.vercel.app/](https://lovelacetreasury.vercel.app/)**

## 📝 Project Description

Lovelace Treasury is a revolutionary decentralized application that transforms traditional gift cards into personalized NFTs on the Cardano blockchain. Our platform allows users to create beautiful, customizable NFT gift cards that can be loaded with ADA and redeemed by recipients, bringing a new dimension to digital gifting on the blockchain.

## 🎯 Problem We Are Solving

Traditional gift cards have several limitations:
- **Centralized Control**: Gift cards are controlled by centralized entities
- **Expiration Issues**: Many gift cards expire and lose value
- **Limited Customization**: Traditional gift cards lack personalization
- **Trust Issues**: Recipients must trust the issuing company
- **No Ownership**: Users don't truly own their gift cards

Our solution addresses these problems by:
- Creating **truly decentralized** gift cards as NFTs
- Ensuring **no expiration** through blockchain permanence
- Providing **extensive customization** options
- Enabling **trustless transactions** through smart contracts
- Giving users **complete ownership** of their NFT gift cards

## 🛠️ Tech Stack

### Blockchain & Smart Contracts
- **Aiken** (Plutus V3) - Smart contract development
- **Cardano Blockchain** - Preprod Testnet
- **MeshJS** - Blockchain integration and wallet connectivity

### Frontend Development
- **Next.js 15** - React framework with TypeScript
- **TypeScript** - Type-safe development
- **TailwindCSS** - Modern styling and responsive design
- **React Hooks** - State management and lifecycle

### Development & Deployment
- **Node.js** - Runtime environment
- **Vercel** - Deployment platform
- **Git** - Version control
- **npm** - Package management

## ✨ Key Features

### 🎨 **Personalized NFT Gift Cards**
- 6 Beautiful Themes: Birthday, Holiday, Anniversary, Celebration, Modern, Minimal
- Custom Templates: Classic, Modern, Elegant, Fun, Vintage designs
- 10 Background Colors: Vibrant gradient options
- Personal Messages: Add heartfelt messages to your gift cards
- 16 Decorative Elements: Emojis and symbols to enhance your design
- Real-time Preview: See your NFT design as you create it

### ⚡ **Advanced Functionality**
- Real-time transaction status updates
- Gift card management dashboard
- Secure wallet integration
- Blockchain-verified transactions
- Trustless smart contract execution

## 📸 Project Demo

### Screenshots
![App Interface](frontend/cardano-gift-card/public/demo-screenshot-1.png)
*Main interface showing gift card creation*

![Gift Card Design](frontend/cardano-gift-card/public/demo-screenshot-2.png)
*Customizable gift card design options*

### Demo Video
🎥 **[Watch Demo Video](./demo-video.mp4)** *(Please add your demo video file)*

## 📊 Presentation

📄 **[Project Presentation (PPT)](./Cardano-NFT-Gift-Card-dApp.pptx)**

## 👥 Team Members

### TechWizards Team

1. **Shaik Hassan Ahmed** - Team Lead
   - Role: Full Stack Developer & Blockchain Developer
   - GitHub: Hassanahmed786
   - Email: [Please add email if needed]

2. **Shruti Keshri** - Team Member
   - Role: Frontend Developer & UI/UX Designer
   - GitHub: [Please add GitHub username]
   - Email: [Please add email if needed]

## 🚀 How to Run the Project

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Aiken (v1.1.19 or higher)
- Cardano wallet (Nami, Eternl, Flint, etc.) with Preprod testnet ADA

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone [repository-url]
   cd TechWizards/frontend/cardano-gift-card
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Compile Smart Contract**
   ```bash
   cd smart-contract
   aiken build
   cd ..
   ```

4. **Run Development Server**
   ```bash
   npm run dev
   ```

5. **Open in Browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 How It Works

1. **Connect Wallet**: Users connect their Cardano wallet
2. **Create Gift Card**: Design and customize NFT gift cards with ADA value
3. **Send to Recipient**: Gift cards are sent to recipient's Cardano address
4. **Redeem**: Recipients can redeem their NFT gift cards for ADA
5. **Blockchain Verification**: All transactions are verified on Cardano blockchain

## 🏆 Innovation Highlights

- **First NFT Gift Card** platform on Cardano
- **Extensive Customization** options for personalized gifts
- **Trustless Smart Contracts** ensuring secure transactions
- **User-Friendly Interface** making blockchain accessible
- **Real-time Updates** for enhanced user experience

## 📁 Project Structure

```
TechWizards/
├── frontend/
│   └── cardano-gift-card/
│       ├── smart-contract/     # Aiken smart contracts
│       ├── src/                # Next.js application source
│       ├── public/             # Static assets
│       ├── utils/              # Utility functions
│       └── ...                 # Configuration files
├── README.md                   # This file
├── [Presentation.pptx]         # Project presentation
└── [demo-video.mp4]           # Demo video
```

---

**Submitted for IndiaCodex 2025 Hackathon**  
**Team: TechWizards**  
**Project: Lovelace Treasury - Cardano NFT Gift Card dApp**