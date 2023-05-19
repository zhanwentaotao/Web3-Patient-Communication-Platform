# Lens SDK + wagmi + Bundlr

本app是基于`@lens-protocol/react` 以及[wagmi](https://wagmi.sh/)、[Bundlr](https://github.com/Bundlr-Network) 构造的web3患者交流社群

## Getting Started

You can run the dev server in this steps:

# Install pnpm
npm i -g pnpm

# Install dependencies
pnpm install

# Copy & fill environments
# NOTE: Documentation of environment variables can be found in the according `.example` files
cp packages/frontend/.env.local.example packages/frontend/.env.local
cp packages/contracts/.env.example packages/contracts/.env
``
### Quickstart
```bash
# Generate contract-types, start local hardhat node, and start frontend with turborepo
pnpm dev

