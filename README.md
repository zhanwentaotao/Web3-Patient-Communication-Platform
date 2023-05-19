
# Web3患者交流社群
项目描述：我们基于`@lens-protocol/react` 以及[wagmi](https://wagmi.sh/)、[Bundlr](https://github.com/Bundlr-Network) 建立的一个Web3患者交流社群。通过开发基于零知识证明的社区接入机制，为不同类型的患者提供一个信息交流和友好互助的社区，在满足患者需求的同时严格保护个人隐私安全。

技术方法：通过区块链和零知识证明技术为身心疾病患者提供一个安全舒适的web3.0交流平台，同时我们还使用SBT来验证访问。

## Getting Started

You can run the dev server in this steps:

```bash
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
# Generate contract-types, start local hardhat node, and start frontend with turborepo
pnpm dev

