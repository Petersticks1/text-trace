TexTrace is a blockchain-powered textile traceability platform built on Hedera Hashgraph, enabling manufacturers, retailers, and consumers to verify the origin, quality, and sustainability of fabrics through decentralized records.

By leveraging Hedera’s REST API, Smart Contracts, and the Mirror Node API, TexTrace ensures secure, transparent, and tamper-proof textile data tracking from raw material to final garment — building trust in a global, sustainable textile economy.

🔗 Core Features (Powered by Hedera)
1. 🌿 Decentralized Fabric Traceability

Each batch of textile material is recorded on the Hedera Token Service (HTS) as a unique NFT.

Metadata includes origin, composition, dye certification, and sustainability credentials.

REST API integration: /api/v1/tokens
 for NFT minting and verification.

2. 🧾 Smart Contract-Based Supply Chain

Hedera Smart Contracts automate recording of production milestones.

Seamlessly verify supplier authenticity, production steps, and environmental impact.

Built using Hedera Smart Contract Service
.

3. 🔍 Mirror Node Verification

The Mirror Node API
 provides transparent insights into every transaction.

Brands and auditors can view verified sustainability proofs and ownership trails.

4. 💳 HashPack Wallet Integration

Enables seamless payments between buyers, suppliers, and certifiers.

Users can sign and verify textile ownership transactions through HashPack
.

🏗️ Tech Stack
Layer	Technology
Frontend	React + TypeScript + Tailwind CSS
Blockchain	Hedera Hashgraph (HTS, Smart Contracts, Mirror Node)
Wallet	HashPack
Backend	Node.js + Express
Database	IPFS / Pinata for off-chain textile metadata
UI Design	Modern light theme with soft teal and cream accents
🧰 Installation & Setup
# Clone the repository
git clone https://github.com/yourusername/textrace.git
cd textrace

# Install dependencies
npm install

# Run the development server
npm run dev

🔑 Environment Variables

Create a .env file and configure:

HEDERA_ACCOUNT_ID=your-account-id
HEDERA_PRIVATE_KEY=your-private-key
MIRROR_NODE_URL=https://mainnet.mirrornode.hedera.com/api/v1
HASHCONNECT_APP_METADATA=your-hashpack-app-metadata

🌱 Example Use Case

A cotton farmer mints an NFT representing a verified batch of organic cotton.

A manufacturer logs production events (spinning, dyeing, weaving) using smart contracts.

A retailer attaches the NFT to the final garment for authenticity.

A consumer scans the QR/NFT code to view the product’s verified origin on Hedera.

🧩 Future Enhancements

🌏 Sustainability scoring system using IoT data integration

🧵 NFT marketplace for limited-edition textile designs

🤝 DAO-based governance for supply chain certification

💬 Hedera Consensus Service for verifiable supply-chain messaging