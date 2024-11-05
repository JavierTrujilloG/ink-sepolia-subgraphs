# Goldsky & Ink Sepolia

This repo contains a couple of examples on how to deploy subgraphs for ERC-20 tokens on the Ink Sepolia network using two different approaches:
- [Goldsky Instant Subgraphs](https://docs.goldsky.com/subgraphs/guides/create-a-no-code-subgraph): use the Goldsky CLI to create deploy no-code subgraph; the CLI will take as input a configuration file and ABI and create all the necessary code. See the config [in this directory](./instant)
- Standard development process: via this method you can use TheGraph's CLI to build a subgraph from scratch, then use Goldsky CLI to deploy it onto your Goldsky project. See the contents of [this directory](./subgraph)