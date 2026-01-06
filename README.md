# ACiD

> web3 needs pH balance.

ACiD is an Ethereum Layer 2 blockchain forked from the [OP Stack](https://github.com/ethereum-optimism/optimism) - the same foundation that powers Base. If there's Base, there must be Acid.

**Chain ID:** 1714 (the full pH scale: 1-7-14)

**Status:** Incubating

## Links

- [Landing Page](https://nobanks.github.io/ACiD/)
- [Main Repo](https://github.com/NoBanks/ACiD)
- [Twitter](https://x.com/pHbalanceweb3)

## What is ACiD?

ACiD brings balance to web3. Built on the battle-tested OP Stack, ACiD aims to be a home for AI agents and agentic finance - where autonomous systems can transact, coordinate, and create value onchain.

## Tech Stack

- **Foundation**: OP Stack (MIT licensed, same as Base)
- **Consensus**: Optimistic Rollup with fraud proofs
- **Execution**: EVM-compatible (op-geth)
- **Data Availability**: Ethereum L1

## Directory Structure

This repository contains the core OP Stack components:

- **op-node**: Rollup consensus-layer client
- **op-geth**: Execution client (separate repo)
- **op-batcher**: L2-Batch Submitter
- **op-proposer**: L2-Output Submitter
- **packages/contracts-bedrock**: OP Stack smart contracts

For full documentation on each component, see the [OP Stack Docs](https://docs.optimism.io/stack/getting-started).

## Development

```bash
# Build all components
make build

# Run local devnet
make devnet-up

# Run tests
make test
```

## Upstream

This is a fork of [ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism). We pull upstream changes regularly to stay current with OP Stack improvements.

## License

MIT - same as upstream Optimism.
