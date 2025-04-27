<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  </head>
<body>

<h1 align="center">🚀 BlockTix - Blockchain-powered Ticket Reselling Platform</h1>
<blockquote>
  <p align="center">Reimagining event ticketing with cross-chain payments, fraud-proof reselling, and NFT collectibles.</p>
</blockquote>

<hr>

<h2>📜 Table of Contents</h2>
<ul>
  <li><a href="#about">About</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#tech-stack">Tech Stack</a></li>
  <li><a href="#gallery">Gallery</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#environment-variables">Environment Variables</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#api-documentation">API Documentation</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

<hr>

<h2 id="about" align="center">🧠 About</h2>
<p align="center"><strong>BlockTix</strong> is a next-generation event ticketing and reselling platform built on blockchain.</p>
<p align="center">It enables users to <strong>buy, sell, and resell</strong> event tickets safely using <strong>crypto wallets</strong>.<br> Powered by <strong>Stellar</strong>, <strong>Base</strong>, and <strong>NFT technology</strong>, BlockTix ensures a <strong>secure, transparent, and fraud-free</strong> event experience for everyone.</p>

<hr>

<h2 id="features" align="center">✨ Features</h2>
<ul align="center">
  <li align="center">🎟️ <strong>Fraud-Proof Ticket Reselling</strong></li>
  <li align="center">🔥 <strong>Automatic Ticket Validation</strong></li>
  <li align="center">🌐 <strong>Cross-Chain Crypto Payments</strong></li>
  <li align="center">💵 <strong>Multiple Payment Options</strong></li>
  <li align="center">🖼️ <strong>NFT Receipts</strong></li>
  <li align="center">📜 <strong>Transparent Transaction History</strong></li>
</ul>

<hr>

<h2 id="tech-stack" align="center">⚙️ Tech Stack</h2>

<table align="center">
<thead>
<tr><th>Frontend</th><th>Backend</th><th>Blockchain</th></tr>
</thead>
<tbody>
<tr><td>React.js (Next.js + TypeScript + TailwindCSS)</td><td>FastAPI (Python)</td><td>Stellar, Base Blockchain</td></tr>
<tr><td>Radix UI, Recharts, Sonner</td><td>JWT Auth, PostgreSQL</td><td>NFT Minting</td></tr>
</tbody>
</table>

<hr>

<h2 id="gallery" align="center">🖼️ Gallery</h2>
<div style="text-align: center;">
  <img src="./screenshots/home.png" alt="Home">
  <img src="./screenshots/list_ticket.png" alt="List Ticket">
  <img src="./screenshots/nft_receipt.png" alt="NFT Receipt">
</div>

<hr>

<h2 id="getting-started" align="center">🚀 Getting Started</h2>

<h3 align="center">📋 Prerequisites</h3>
<ul align="center">
  <li>Node.js ≥ 18</li>
  <li>Python ≥ 3.9</li>
  <li>PostgreSQL database</li>
  <li>Metamask / Wallet Extension</li>
  <li>Git</li>
</ul>

<hr>

<h2 id="installation" align="center">⚙️ Installation</h2>

<h3>1. Clone the repository</h3>

<pre><code>git clone https://github.com/yourusername/blocktix.git
cd blocktix
</code></pre>

<h3>2. Backend Setup (FastAPI)</h3>

<pre><code>cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
</code></pre>

<p>Backend runs on ➡️ <strong>http://127.0.0.1:8000</strong></p>

<h3>3. Frontend Setup (Next.js React)</h3>

<pre><code>cd frontend
npm install --legacy-peer-deps
npm run dev
</code></pre>

<p>Frontend runs on ➡️ <strong>http://localhost:3000</strong></p>

<hr>

<h2 id="environment-variables">🔑 Environment Variables</h2>

<h3>Backend</h3>
<pre><code>DATABASE_URL=postgresql://username:password@localhost:5432/yourdb
JWT_SECRET=your_jwt_secret_here
BASE_API_KEY=your_base_chain_api_key
STELLAR_API_KEY=your_stellar_chain_api_key
</code></pre>

<h3>Frontend</h3>
<pre><code>NEXT_PUBLIC_API_URL=http://127.0.0.1:8000
NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=your_project_id
</code></pre>

<hr>

<h2 id="api-documentation">📡 API Documentation</h2>
<p>Once backend is running ➡️ Open:</p>
<ul>
  <li><strong>Swagger UI:</strong> <a href="http://127.0.0.1:8000/docs">http://127.0.0.1:8000/docs</a></li>
  <li><strong>Redoc:</strong> <a href="http://127.0.0.1:8000/redoc">http://127.0.0.1:8000/redoc</a></li>
</ul>

<hr>

<h2 id="contributing">🧩 Contributing</h2>
<p>We love contributions! 🫶</p>
<ol>
  <li>Fork the repository.</li>
  <li>Create your feature branch: <code>git checkout -b feature/your-feature-name</code></li>
  <li>Commit your changes: <code>git commit -m 'Add some feature'</code></li>
  <li>Push to the branch: <code>git push origin feature/your-feature-name</code></li>
  <li>Open a pull request.</li>
</ol>

<hr>

<h2 id="license">🛡️ License</h2>
<p>Distributed under the <strong>MIT License</strong>.<br> See <code>LICENSE</code> for more information.</p>

<hr>

<h1>🚀 BlockTix - Empowering a New Era of Events!</h1>

</body>
</html>
