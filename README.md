```
TODO:
- [ ] fix dev mining steps with new process
- [ ] Builder onboarding flow

** Point of Contact **
[BuilderNameHere](https://github/Web3-API/dao/builder-squads/builders/buildername.md)

1. fork the `dao` repo
   - add `NN-spending_proposal.md`, following the template
   - Add builder profile (if necessary)

1. Submit PR

1. Gather feedback from the DAO and other Builders
   - Share your proposal on community channels
   - Submit to snapshot if necessary
   - Modify the spending proposal to achieve concensus
  
1. Once concensus is reached in the community, the spending proposal should be merged to master and work can be initiated.

1. When payment is scheduled, the assigned squad should submit the payment proposal to the Web3API DAO and notify other builders to check the deliverables and to vote on the payment proposal.

```

# Web3API DAO
[![Generic badge](https://img.shields.io/badge/Wallet-Aragon-52EBFF.svg)](https://client.aragon.org/#/w3api) [![Generic badge](https://img.shields.io/badge/Consensus-Snapshot-f6ad32.svg)](https://snapshot.page/#/web3-api)  

The Web3API DAO is responsible for stewarding the Web3API ecosystem. `W3API` governance token holders will have immediate control of the:
- Web3API [roadmap](https://github.com/Web3-API/roadmap)
- [Treasury](https://client.aragon.org/#/w3api/0x8fe59d8fb5ffd3509e5cb3d386be8bdb2d363662/)
- `W3API` token issuance
- DAO configuration
- ENS domain (web3api.eth)

In the future, it is anticipated that the DAO will also govern:

- Web3API [repositories](https://github.com/Web3-API)
- Web3Hub platform deployments
- DAO-verified APIs (hosted at web3api.eth subdomains)

## Getting Started

### How to contribute:

To become a *Builder* read the instructions in the [`contribute.md` file](./contribute.md):

### Benefits of being a builder:

*Builders* are granted funds and `W3API` tokens on a per-project basis by the Web3API DAO. Projects are approved ahead of time to help manage the DAO budget, maintain accountability, and schedule developments.

## Token Distribution
> NOTE: Tokens are initially set to be non-transferable.

<img src="./img/token-distribution.png" width="300px"/>

### Pre-Seed Builders
At launch 4,000 `W3API` were minted to *Pre-Seed Builders* in proportion to work contributed before launch on October 1st (viewable [here](./token-allocations/pre-seed-builders.csv)).

### Pre-Seed Funders
4,000 `W3API` were minted to *Pre-Seed Funders*, with a goal of raising $1M to sustain the project. Tokens were distributed in three batches (viewable [here](./token-allocations/pre-seed-funders.csv))

### Dev Mining
12,000 `W3API` will be minted to *Builders* in proportion to value-added contributions over the first 16 months (~750/month). `W3API` holders will decide on further fundraising and token emission plans after the 16 month pre-seed period.


## Use of Funds

In the first 16 months (Sept 2020 to Dec 2021), it is anticipated that the DAO will allocate funds for:
- Development - $42,000 / month
- Ops & Adoption - $15,000 / month
- Legal & SaaS - $5,500 / month

<img src="./img/fund-usage.png" width="600px"/>

With the goal of delivering the items listed on the [Web3API public roadmap](https://github.com/Web3-API/roadmap)

<img src="./img/roadmap.png" width="600px">

## DAO Configuration

Initial governance parameters are as follows:
| Parameter | Value | Description |
|-|-|-|
| *Minimum Approval* | 10% | Percentage of the total token supply that is required to vote “Yes” on a proposal before it can be approved. |
| *Support* | 60% | Relative percentage of tokens that are required to vote “Yes” for a proposal to be approved. |
| *Vote Duration* | 7 days| Maximum length of time that the vote will be open for participation. |

See which Aragon Apps the DAO is using [here](./dao_config.md).

See the full configuration [here](https://client.aragon.org/#/w3api/permissions/).

## Legal

Holders of `W3API` do not constitute any sort of partnership or joint venture, only the right to participate in the governance of the DAO. Further, becoming a Builder does not constitute any sort of partnership, joint venture, principal-agent relationship, or an employer-employee relationship. 

## FAQ

**What can I do with my `W3API` tokens?**  
Once your token request is approved, you instantly have the power to vote on all on-chain decisions, such as spending funds or minting new tokens.

**What about vesting?**  
`W3API` tokens are initially set to be non-transferable. The DAO can decide to change this in the future and mint tokens to contributors via timelock or vesting contracts.
