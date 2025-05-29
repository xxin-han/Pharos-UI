# Pharos-UI

**Pharos Network** is a blockchain infrastructure project designed to support a more open, decentralized, and efficient Web3 ecosystem. It offers a platform for developers and users to build and interact with decentralized applications (dApps), with a focus on scalability, interoperability, and optimized data access.

## Features

- Dynamic Terminal User Interface (TUI) using Blessed + Chalk
- Direct interaction with smart contracts via Ethers.js
- Supports HTTP and SOCKS Proxy
- Multiple wallet support (via pk.txt and wallet.txt)

## Installation

1. Register [Pharos Tesnet](https://testnet.pharosnetwork.xyz/experience?inviteCode=E84eUZ0c9k0iVB3Q)

2. Install Tools.
```bash
   wget https://github.com/xxin-han/setup/raw/main/setup.sh -O setup.sh && chmod +x setup.sh && ./setup.sh
   ```
3. Clone this repository:
   ```bash
   git clone https://github.com/Svz1404/NTE-Pharos.git
   ```
4. Navigate to the project directory:
   ```bash
   cd NTE-Pharos
   ```
5. Install the required dependencies:
   ```bash
   npm install
   ```
6. Fill the private key list on accounts.txt then save it ctrl + x + y + enter
   ```bash
   nano pk.txt
   ```
7. run it
   ```bash
   node index.js
   ```
8. Stop bot
   ctrl + c
