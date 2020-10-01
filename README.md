# Web3API DAO

The Web3API DAO is responsible for stewarding the Web3API ecosystem. `W3API` governance token holders will have immediate control of the:
- Treasury
- `W3API` token issuance
- DAO configuration
- ENS domain (web3api.eth)

In the future, it is anticipated that the DAO will also govern:
- Web3API repositories
- Web3Hub platform deployments
- DAO-verified APIs (hosted at web3api.eth subdomains)

## Getting Started

### Seed Funder

To become a *Seed Funder*:

1. Go to the [DAO's Token Request App](https://client.aragon.org/#/w3api/0x9bb4ea752a3096104c7765ad318b0f9cabaaf95f/).
2. Click **New Request** in the top right corner.
3. In **Offered Amount** enter the amount you would like to contribute (DAI, USDC or USDT).
4. In **Requested Amount** enter the amount of `W3API` you'd like to receive. This can be calculated by dividing the **Offer Amount** by the seed price of $250.
5. Press **Create Request** to initiate the proposal and deposit your funds.
6. Email **web3api@dorg.tech** with subject line 'Token Request' and the following info:
   - Name
   - ETH Address
   - Brief background on who you are and what strategic value you bring to the project

`W3API` holders will receive this information and vote on your request. If approved, your funds will transfer to the DAO and `W3API` will be minted to your wallet. If rejected, you will be able to withdraw your funds. You may also withdraw your funds at any time before the request is approved.

### Seed Builder

To become a *Seed Builder*:
1. Fork [web3-api/dao](https://github.com/web3-api/dao)'s `master` branch'.
2. Duplicate the [`TEMPLATE.md`](./roadmaps/TEMPLATE.md) file in the [`./roadmaps`](./roadmaps) folder.
3. Name the file, complete all required fields, and feel free to get creative with anything else you'd like to add.
4. Open a PR against [web3-api/dao](https://github.com/web3-api/dao)'s `master` branch.
5. Create an informational proposal in the [DAO's voting app](https://client.aragon.org/#/w3api/0x5f78d0668ba666b4ed9674b313419d9db6cd48a6/), linking to the open PR.
6. If the DAO proposal passes, the PR can then be merged into master.

## Token Distribution

At launch 4,000 `W3API` are minted to *Pre-Seed Builders* in proportion to work contributed before launch on October 1st (viewable [here](./token-allocations/pre-seed-builders.csv)).

In the first 12 months after launch, it is anticipated that the DAO will mint no more than:
- 4,000 `W3API` to *Seed Funders* for $250/token (viewable [here](./token-allocations/seed-funders.csv))
- 12,000 `W3API` to *Seed Builders* in proportion to value-added contributions (~1,000/month)

<img src="./img/token-distribution.png" height="300px"/>

After the 12 month seed period, the `W3API` holders will decide on further fundraising and token emission plans.

NOTE: Tokens are initially set to be non-transferable.

## Use of Funds

In the first 12 months, it is anticipated that the DAO will allocate funds for:
- Development - $42,000 / month
- Ops & Adoption - $15,000 / month
- Legal & SaaS - $5,500 / month

<img src="./img/fund-usage.png" height="400px"/>

## Legal

Holders of `W3API` do not constitute any sort of partnership or joint venture, only the right to participate in the governance of the DAO. Further, becoming a Seed Builder does not constitute any sort of partnership, joint venture, principal-agent relationship, or an employer-employee relationship. 

## DAO Configuration

Initial governance parameters are as follows:
| Parameter | Value | Description |
|-|-|-|
| *Minimum Approval* | 10% | Percentage of the total token supply that is required to vote “Yes” on a proposal before it can be approved. |
| *Support* | 60% | Relative percentage of tokens that are required to vote “Yes” for a proposal to be approved. |
| *Vote Duration* | 7 days| Maximum length of time that the vote will be open for participation. |

The DAO uses the following Aragon apps:
| App | Address | Description |
|-|-|-|
| *[Voting](https://help.aragon.org/article/19-voting)* | 0x5f78d0668ba666b4ed9674b313419d9db6cd48a6 | Used to create and participate in votes. Votes can be linked to an action, such as minting `W3API` or transferring funds, or be purely informative. |
| *[Finance](https://help.aragon.org/article/20-finance)* | 0xc19a9f41df38e0f01f809d257d6c71f892adaaff | Manages the organization's financial assets, including ETH and ERC20s. |
| *[Tokens](https://help.aragon.org/article/18-tokens)* | 0x8baa4cd6bf2a01e96e421c18b0231ce7791ed869 | Manages the supply and distribution of `W3API`. |
| *[Token Request](https://github.com/1Hive/token-request-app/blob/master/docs/user-guide.md)* | 0x9bb4ea752a3096104c7765ad318b0f9cabaaf95f | Mints `W3API` in exchange for payment.|
| *[Agent](https://help.aragon.org/article/37-agent)* | 0x8fe59d8fb5ffd3509e5cb3d386be8bdb2d363662 | Enables the organization to interact directly with any other smart contract on Ethereum. For example, setting an ENS resolver. |

See the full configuration [here](https://client.aragon.org/#/w3api/permissions/).
