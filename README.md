# Simple Blockchain Implementation

A blockchain implementation featuring smart contracts, proof of stake consensus, and a web interface.

## Features

- Proof of Stake consensus mechanism
- Smart contract support
- Web-based block explorer
- Wallet interface
- P2P networking
- Transaction verification
- Event system

## Project Structure

```
/
├── backend/           # Python blockchain implementation
│   ├── blockchain/    # Core blockchain classes
│   ├── consensus/     # Consensus mechanisms
│   ├── contracts/     # Smart contract system
│   └── networking/    # P2P networking
├── frontend/         # React-based UI
│   ├── components/   # React components
│   └── pages/        # Page layouts
└── docs/            # Documentation
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Oterochris/simple-blockchain.git
cd simple-blockchain
```

2. Install backend dependencies:
```bash
cd backend
pip install -r requirements.txt
```

3. Install frontend dependencies:
```bash
cd frontend
npm install
```

## Usage

1. Start the blockchain node:
```bash
python backend/main.py
```

2. Start the frontend development server:
```bash
cd frontend
npm start
```

## License

MIT