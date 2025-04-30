# Liminai

![Liminai](https://github.com/user-attachments/assets/1e76b447-9355-47d1-82b3-c518328fa6e1)

## The Decentralized Intelligence Layer for Crypto

(Liminai) is a protocol-level framework that connects AI agents (via Model Context Protocols) with crypto-native services, enabling seamless, standardized interaction across trading, DeFi, governance, and social platforms. It acts as an intelligent coordination layer, supporting discoverability, authentication, and execution across modular AI agents.

## Key Features

- **Liminai Registry Layer**: Access curated AI agent backends through a standardized protocol
- **Agent-Based Execution**: Natural language processing with intelligent tool fallback
- **Modular & Interoperable**: Works with Solana, EVM chains, L2s, and off-chain systems
- **Governance-Ready**: Tokenized curation and incentive mechanisms

## Problem & Solution

AI integration with crypto is fragmented and non-scalable due to bespoke integrations. EPNAI standardizes this via a unified protocol that simplifies agent-to-service interaction, boosting accessibility and scalability.

## Repository Structure

This monorepo contains the following components:

- [**Liminai-core**](./Liminai-core/): Core protocol logic with Solana programs for registry, permissions, and execution tracking
- [**Liminai-agents**](./Liminai-agents/): Agent templates and execution engines with prebuilt AI agents
- [**Liminai-server**](./Liminai-server/): Reference MCP server implementation with context handling and wallet integration
- [**Liminai-examples**](./Liminai-examples/): Full workflow examples using real-world Solana services
- [**Liminai-docs**](./Liminai-docs/): Protocol documentation, architecture, and tutorials

## Why Now?

AI is centralized, crypto is decentralized. This protocol bridges them, leveraging AI's usability and crypto's openness. The goal is to build a decentralized, AI-native interface that works like an OS for crypto workflows.

## Liminai Defined

Each Liminai server exposes context-aware, domain-specific functionality (e.g., Binance, Twitter, smart contracts) in a machine-readable format, enabling AI agents to interact securely and intelligently.

## Token Model & Ecosystem

$Liminai powers decentralized governance, usage, and staking, with network effects tied directly to protocol utility, not speculation.

## Getting Started

To start developing with EPNAI:

```bash
# Clone the repository
git clone https://github.com/your-org/Liminai.git
cd Liminai

# Install dependencies for all packages
npm install

# Build the core components
cd Liminai-core
anchor build

# Run examples
cd ../Liminai-examples
npm run start:jupiter
```

## Launch Strategy

Started with an anonymous dev sharing ideas on social media. Transparent, community-first, and built in public with a light-touch rollout—no hype, no VC dominance, just real infrastructure and community involvement.

## Development Tools

- Solana CLI + Anchor (for smart contracts)
- TypeScript/JavaScript (for client applications)
- WebSockets/RPC listeners (for real-time events)
- gRPC/REST APIs (for service communication)

## Vision

Liminai is building the decentralized intelligence layer for crypto, where agents serve people, not platforms.

## Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines.

## License

This project is licensed under the [MIT License](./LICENSE).
