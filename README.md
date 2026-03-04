# SpifyNetwork - Decentralized Private Messaging & Cryptocurrency Platform

Spify is a comprehensive decentralized application that combines private messaging with a built-in cryptocurrency called Cripamint (Crip). It features a secure P2P network with SSL/TLS encryption, UTXO-based blockchain, and proof-of-work mining.

## Features

### 📱 User Interface
- Dark green and Ferrari yellow color scheme
- Undecorated, draggable window
- Clean and minimalist design
- Custom button components with hover effects

### 🔐 Security
- SSL/TLS encrypted P2P communication
- AES-256-GCM encryption for stored data
- PBKDF2 password hashing with random salts
- Anti-debugging protection
- Integrity checking for JAR files

### 💬 Private Messaging
- End-to-end encrypted private messages
- Messages only visible to sender and recipient
- Chat history stored locally
- Real-time message delivery

### 💰 Cryptocurrency (Cripamint)
- UTXO-based transaction model
- Proof of Work mining (difficulty 4)
- Block reward: 50 Crip
- Genesis block reward: 100 Crip
- Transaction fee: 0.001 Crip

### 🎁 Registration Rewards
- First 2900 users: 58 Crip each
- Special username 'JSapviofny29': 29000 Crip (one-time)

### 🌐 Network Features
- Bootstrap nodes for initial connection
- Automatic peer discovery
- Heartbeat mechanism for connection monitoring
- Chain synchronization between nodes
- Solo mining support for single-node operation

## System Requirements

- Java 21 or higher
- Maven 3.6+
- 256MB RAM minimum
- 100MB disk space

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/spify.git
cd spify
