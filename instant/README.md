# Instant Subgraphs

[Goldsky's Instant Subgraphs](https://docs.goldsky.com/subgraphs/guides/create-a-no-code-subgraph)

Simple JSON config file to index a contract with an ABI.

In this example we are deploying a subgraph for [Inko ETH (IETH)](https://explorer-sepolia.inkonchain.com/token/0x87B4bD3A657c4D739730e115Dad11246c0D8D2b1?tab=contract)

To deploy, run:
`goldsky subgraph deploy inko-eth/1 --from-abi config.json`

By default, the deployed subgraph will create as many entities as events it finds in the ABI. You can extend this functionality using [Enrichments](https://docs.goldsky.com/subgraphs/guides/create-a-no-code-subgraph#extending-your-subgraph-with-enrichments)