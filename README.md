# NEAR Contract Registry

## Why Contract Registry?

1. **Improve contract metadata discoverability.** It's frequently asked by developers about where to find the mainnet/testnet contract accounts, DApp URLs and source code of the smart contracts on NEAR. To make the contract metadata more discoverable, we created this contract registry to make it easy to find all the necessary information about the contracts of the core projects on NEAR. 
2. **Improve user security.** The contract registry can be leveraged by security infrastructure in the ecosystem such as wallet to verify the contract and dapps when user access them. For example, if the user is connecting the contract from a dapp URL that doesn't match with the contract address in the registry, the wallet will warn the user of potential risks.
 

## Contract Metadata

In the table, we have listed some of the most frequently asked contracts and projects. If you think your project should be listed, please feel free to create pull requests or submit issues.

The currently supported metadata includes

1. project name
2. contract source on GitHub
3. contract account on mainnet
4. app URL for mainnet
5. contract account on testnet
6. app URL for testnet

The testnet contracts and app URLs are usually helpful when developers are building their new contracts / DApps.

For CSV version of the table, check out [here](/near-contract-registry.csv)

| Project | Contract Source | Mainnet Contract | Mainnet App | Testnet Contract | Testnet App
| -------- | -------- | -------- | -------- | -------- | -------- |
| [Aurora](https://awesomenear.com/aurora-dev) | [aurora-is-near/aurora-engine](https://github.com/aurora-is-near/aurora-engine) | [aurora](https://explorer.near.org/accounts/aurora) | https://aurora.dev/start | [aurora](https://explorer.testnet.near.org/accounts/aurora) | https://aurora.dev/start |
| [Rainbow Bridge](https://awesomenear.com/rainbow-bridge) | [aurora-is-near/rainbow-bridge](https://github.com/aurora-is-near/rainbow-bridge) | [aurora](https://explorer.near.org/accounts/aurora) | https://rainbowbridge.app | [aurora](https://explorer.testnet.near.org/accounts/aurora) | https://testnet.rainbowbridge.app |
| [Ref Finance](https://awesomenear.com/ref-finance) | [ref-finance/ref-contracts](https://github.com/ref-finance/ref-contracts) | [v2.ref-finance.near](https://explorer.near.org/accounts/v2.ref-finance.near) | https://app.ref.finance | [exchange.ref-dev.testnet](https://explorer.testnet.near.org/accounts/exchange.ref-dev.testnet) | https://testnet.ref.finance |
| [Paras](https://awesomenear.com/paras) | [ParasHQ/paras-marketplace-contract](https://github.com/ParasHQ/paras-marketplace-contract) | [marketplace.paras.near](https://explorer.near.org/accounts/marketplace.paras.near) | https://paras.id | [paras-marketplace-v2.testnet](https://explorer.testnet.near.org/accounts/paras-marketplace-v2.testnet) | https://testnet.paras.id |
| [Mintbase](https://awesomenear.com/mintbase) | [Mintbase/mintbase-core](https://github.com/Mintbase/mintbase-core) | [mintbase1.near](https://explorer.near.org/accounts/mintbase1.near) | https://mintbase.io | [mintspace2.testnet](https://explorer.testnet.near.org/accounts/mintspace2.testnet) | https://testnet.mintbase.io |
| [AstroDAO](https://awesomenear.com/astrodao) | [near-daos/sputnik-dao-contract](https://github.com/near-daos/sputnik-dao-contract) | [sputnik-dao.near](https://explorer.near.org/accounts/sputnik-dao.near) | https://app.astrodao.com | [sputnikv2.testnet](https://explorer.testnet.near.org/accounts/sputnikv2.testnet) | https://testnet.app.astrodao.com |
| [Skyward](https://awesomenear.com/skyward-finance) | [skyward-finance/contracts](https://github.com/skyward-finance/contracts) | [skyward.near](https://explorer.near.org/accounts/skyward.near) | https://app.skyward.finance | [skyward.testnet](https://explorer.testnet.near.org/accounts/skyward.testnet) | https://test.skyward.finance |
| [Meta Pool](https://awesomenear.com/meta-pool) | [Narwallets/meta-pool](https://github.com/Narwallets/meta-pool) | [meta-pool.near](https://explorer.near.org/accounts/meta-pool.near) | https://metapool.app/dapp/mainnet/meta | [meta-v2.pool.testnet](https://explorer.testnet.near.org/accounts/meta-v2.pool.testnet) | https://metapool.app/dapp/testnet/meta |

## How do you collect the metadata?

We refer to [AwesomeNEAR](https://awesomenear.com/) for searching the basic descriptions of the projects. 

However, most contract metadata are not listed there. We found the open source repository location, dapp URLs, and contract accounts based on own knowledge about the projects if not found on AwesomeNEAR, and verified the contract IDs by interacting the apps with our NEAR accounts, and confirmed in NEAR Explorer. If you have any metadata that is incorrect, please report via issues or pull requests. 

## What's Next

This repo is only the initial version of the contract registry, and we'll add more enhancements later. 

- [ ] Add more contract metadata such as owners (single account or DAO), security auditors, etc.
- [ ] For dapps that used multiple contracts, list all the contracts' metadata. Now we only include the core contracts for the dapps.  
- [ ] Create mainnet / testnet contract registry for storing the contract metadata that could be updated by the project DAOs or owners.
- [ ] Turn the contract registry to be maintained by a developer DAO from NEAR developer community.

## How to Contribute

If you have any suggestions of improving the contract registry, or if you'd like to add your own projects, please feel free to create pull requests or submit issues.
