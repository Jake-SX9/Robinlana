### Base on Solana

[![npm downloads](https://img.shields.io/npm/dm/@coinbase/cdp-agentkit-core?style=flat-square)](https://www.npmjs.com/package/@coinbase/cdp-agentkit-core)
[![GitHub star chart](https://img.shields.io/github/stars/coinbase/cdp-agentkit-nodejs?style=flat-square)](https://star-history.com/#coinbase/cdp-agentkit-nodejs)
[![Open Issues](https://img.shields.io/github/issues-raw/coinbase/cdp-agentkit-nodejs?style=flat-square)](https://github.com/coinbase/cdp-agentkit-nodejs/issues)

# Solana Base Chain AgentKit for Node.js

The **Solana Base Chain AgentKit for Node.js** simplifies bringing your AI Agents onchain on Solana. Every AI Agent deserves a crypto wallet!

## Key Features
- **Framework-agnostic**: Common AI Agent primitives that can be used with any AI framework.
- **LangChain.js integration**: Seamless integration with [LangChain.js](https://js.langchain.com/docs/introduction/) for easy agentic workflows. More frameworks coming soon!
- **Twitter (X) integration**: Seamless integration of LangChain with [Twitter (X)](https://developer.twitter.com/en/docs/twitter-api) for easy agentic workflows.
- **Support for various on-chain actions**:

  - Airdrops for Solana devnet funds
  - Getting wallet details and token balances
  - Sending and swapping SPL tokens
  - Creating and managing Solana wallets
  - Deploying SPL tokens
  - Minting and managing Solana NFTs
  - Interacting with Solana DeFi protocols
  - Launching tokens on Solana bonding curve platforms
  - Executing onchain transactions with AI Agents
  
  Or [add your own](./CONTRIBUTING.md#adding-an-action-to-agentkit-core)!

## Examples
Check out [solana-langchain/examples](./solana-langchain/examples) for inspiration and help getting started!

- [Chatbot](./solana-langchain/examples/chatbot/README.md): Simple example of a Chatbot that can perform complex onchain interactions using OpenAI.
- [Trading Agent](./solana-langchain/examples/trading-agent/README.md): AI Agent capable of swapping and managing SPL tokens.
- [NFT Minter](./solana-langchain/examples/nft-minter/README.md): Example agent for minting and managing Solana NFTs.

## Repository Structure
Solana Base Chain AgentKit Node.js is organized as a [monorepo](https://en.wikipedia.org/wiki/Monorepo) that contains multiple packages.

### @solana/agentkit-core
Core primitives and framework-agnostic tools that are meant to be composable and used via AgentKit framework extensions (ie, `solana-langchain`).

See [AgentKit Core](./solana-agentkit-core/README.md) to get started!

### @solana/langchain
LangChain.js Toolkit extension of Solana AgentKit. Enables agentic workflows to interact with Solana onchain actions.

See [Solana LangChain](./solana-langchain/README.md) to get started!

### @solana/twitter-langchain
LangChain Toolkit extension for Twitter (X). Enables agentic workflows to interact with Twitter, such as posting tweets and automating social interactions.

See [Twitter LangChain](./twitter-langchain/README.md) to get started!

## Contributing
Solana Base Chain AgentKit welcomes community contributions.

See [CONTRIBUTING.md](CONTRIBUTING.md) for more information.

## Security and bug reports
The Solana Base Chain AgentKit team takes security seriously.

See [SECURITY.md](SECURITY.md) for more information.

## Documentation
- [Solana AgentKit Documentation](https://solana.com/docs)
- [API Reference: Solana AgentKit Core](https://github.com/)
- [API Reference: Solana LangChain Extension](https://github.com/)
- [API Reference: Twitter LangChain Extension](https://github.com/)

## License

Apache-2.0
