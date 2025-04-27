—

🪩 BlockTix - Blockchain-powered Ticket Reselling Platform
Reimagining event ticketing with cross-chain payments, fraud-proof reselling, and NFT collectibles.

📜 Table of Contents
About

Features

Tech Stack

Screenshots

Getting Started

Environment Variables

Installation

API Documentation

Contributing

License

🧠 About
BlockTix is a next-generation event ticketing and reselling platform built on blockchain.

It enables users to buy, sell, and resell event tickets safely using crypto wallets.
Powered by Stellar, Base, and NFT technology, BlockTix ensures a secure, transparent, and fraud-free event experience for everyone.

✨ Features
🎟️ Fraud-Proof Ticket Reselling

🔥 Automatic Ticket Validation

🌐 Cross-Chain Crypto Payments

💵 Multiple Payment Options

🖼️ NFT Receipts

📜 Transparent Transaction History

⚙️ Tech Stack

Frontend	Backend	Blockchain
React.js (Next.js + TypeScript + TailwindCSS)	FastAPI (Python)	Stellar, Base Blockchain
Radix UI, Recharts, Sonner	JWT Auth, PostgreSQL	NFT Minting
🖼️ Screenshots

Home Page	Ticket Listing	NFT Receipt
🚀 Getting Started
📋 Prerequisites
Node.js ≥ 18

Python ≥ 3.9

PostgreSQL database

Metamask / Wallet Extension

Git

⚙️ Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/blocktix.git
cd blocktix
2. Backend Setup (FastAPI)
bash
Copy
Edit
cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
Backend runs on ➡️ http://127.0.0.1:8000

3. Frontend Setup (Next.js React)
bash
Copy
Edit
cd frontend
npm install --legacy-peer-deps
npm run dev
Frontend runs on ➡️ http://localhost:3000

🔑 Environment Variables
Create a .env file inside both frontend/ and backend/:

Backend
env
Copy
Edit
DATABASE_URL=postgresql://username:password@localhost:5432/yourdb
JWT_SECRET=your_jwt_secret_here
BASE_API_KEY=your_base_chain_api_key
STELLAR_API_KEY=your_stellar_chain_api_key
Frontend
env
Copy
Edit
NEXT_PUBLIC_API_URL=http://127.0.0.1:8000
NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=your_project_id
📡 API Documentation
Once backend is running ➡️ Open:

Swagger UI: http://127.0.0.1:8000/docs

Redoc: http://127.0.0.1:8000/redoc

🧩 Contributing
We love contributions! 🫶

Fork the repository.

Create your feature branch: git checkout -b feature/your-feature-name

Commit your changes: git commit -m 'Add some feature'

Push to the branch: git push origin feature/your-feature-name

Open a pull request.

🛡️ License
Distributed under the MIT License.
See LICENSE for more information.

