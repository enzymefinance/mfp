# MFP: External Strategy- Automated AMM LP Staking
### Proposal

External Position for AMM DEX Staking Rewards Auto-Compound

### Description of the project

Exponent submits a funding proposal for `External Strategy`, a modular approach to automate passive strategy on DeFi protocols utilizing external position on Enzyme’s Sulu framework. With External Strategy, vault managers can run complex DeFi interactions in one transaction, or even delegate the responsibility automate the strategy to a third party service provider. The first strategy will be to compound staking rewards on Sushiswap and Quickswap on Polygon blockchain, thus allowing all vaults to deploy their own Beefy Finance/ Autofarm-like liquidity mining strategies right on Enzyme without technical knowledge or operations overheads.

### Motivation

With the release of Sulu, a promising feature for vault manager is external position, which allows a fund managers the flexibility to interact with DeFi protocols without the need for external price feeds or asset fungibility, ie. Uniswap V3 or Compound debt position. However, running a complex DeFi strategy requires multiple sequential smart contract interactions which is still very difficult to achieve in the current form. 

Exponent aims to create a general architecture for complex DeFi interactions while utilizing Sulu’s native external position feature 

Benefits to the Enzyme ecosystem includes:

- vault managers still maintain full custody of the assets, still working within Sulu’s security model.
- any vault manager on Enzyme can opt-in to an external strategy they may want to utilize and even configure the contract settings on the fly
- a scope for interaction required by external actor to act on behalf of the manager is limited only to `automate` which performs a single task as required in exchange for a bounty.
- external strategy can be quicker to roll out given the tight scope of application logic and interface
- significant gas savings compared to running the same transactions sequentially through enzyme integration adapters.
- external strategy can hold assets that aren’t available on Chainlink price feeds
- first community external position code contribution.

## Scope of work

The following are the deliverables that Exponent commit to as part of the proposal:

1. Working external strategy contracts with modular contract architecture
2. `UniversalParser`: a generic parser for external position 
3. `ExternalStrategyProxy`: a proxy contract strategy that cross-check for allowlist and delegate calls to a strategy lib for implementation
4. `ExternalStrategyRegistry`: allowlist for pre-approved external strategies
5. `SushiStrategyLib`: Sushiswap + Staking rewards strategy contract. Swap, provide liquidity and stake LP tokens in one atomic transaction.
6. `QuickswapStrategyLib`: Quickswap + Staking rewards strategy contract. Swap, provide liquidity and stake LP tokens in one atomic transaction.
7. Test suite for the set of contracts
8. End to end test with the live contracts on Polygon
9. TypeScript integration library to simplify the process of building transactions and calling the smart contract from client and server side application.
10. Everything will be published as public and open source license on Exponent’s official GitHub organization

### Working Prototype

the first version of a successful transaction flow has already been completed on Polygon with a real vault instance, FRAX and FXS liquidity pair on Sushiswap with SUSHI token reward.

Fund deployment from vault and strategy execution
[Enter() transaction hash](https://polygonscan.com/tx/0x7c835dbdf764b5673d370fddfbc078312c6ff658c75abb1a2d2eccf0a57082d0)

Automated task on behalf of the vault manager 
[Automate() transaction hash](https://polygonscan.com/tx/0xdba37a98a2ca326c5338375fd7d4e9afc7cbb86e6c26e983b89885b52a0864eb)

[Example UniversalParser contract:](https://polygonscan.com/address/0x1b8f25c3e1abcf8d89fa25ac2ff817af6120631e#code)

[Example SushiswapStrategyLib contract:](https://polygonscan.com/address/0x332a93f042a6359639dc24c77409672e22997ac8#code)

### Timeline

the work is to be completed in the next 4 weeks

- working strategy transaction on Polygon (already completed)
- test suites
- code refactoring and clean up
- a TypeScript library developed

### Technical Details

the source code for the deliverables and the technical details can be found here:

[https://github.com/exponent-cx/external-strategy](https://github.com/exponent-cx/external-strategy)

## Team

Exponent is on a mission to facilitate treasury deployment at scale for web3 orgs that won’t compromise on trust. It achieves this objective with productized treasury services that are curated, automated and risk mitigated. Exponent already has experience building on top of the Sulu architecture with the upcoming release of its treasury product: Fennec Stash.

## Other considerations

there are additional development and infrastructure discussion that must be taken into consideration which are currently not included in the scope of work.

- What are the ways Exponent can roll out the external strategy to other Enzyme vault managers, safely and securely
- how Enzyme existing vault manager’s front end may integrate with Exponent’s external strategy
- if applicable, smart contract auditing required to be done before the contract can get real usage.
- if applicable, how to coordinate on new development of StrategyLib and how funding proposals can be structured for individual strategy.

## Funding Required

1500 MLN vested on completion of the above deliverables under the scope of work.

## Future Possibility

There are strong future candidates for future development work on external strategy. For instance: 

- Client application: hosted front end for vault manager to interact with the external strategy
- Off-chain automate task scheduler: Exponent can trigger `automate` transaction on behalf of all registered Enzyme vault managers.
- a Diversified LP Staking Vault: an Enzyme vault with diversified exposure to different liquidity pools on Quickswap and Sushiswap with fully automated liquidity mining positions.

## Contact Information

for any further questions, please contact:

✉️  contact@exponent.ai

or dm us on twitter at 
@exponent_cx