# Web3API DAO

## Purpose
Stewarding The Web3API Ecosystem

## TODO: put this some place
DAO URL: [Mainnet](https://client.aragon.org/#/web3-api)
token name: Web3API DAO
token symbol: W3API

## Token Distribution

At launch, 4,000 tokens are minted to "seed builders" in proportion to work contributed before launch (Oct 1, 2020). Next, 4,000 new tokens will be minted over time to "seed funders" through the token request app. In the same period, 

Allocation:
- 20% to seed builders at launch (4,000)
- 20% to seed funders starting October 1st (4,000)
- 60% to future builders & adopters starting October 1st (12,000)

| Period | Start Date | Builder Tokens | Funder Tokens |
|-|-|-|-|
| Pre-Seed | May 17, 2019 | 4,000 | 0 |
| Seed | Oct 1, 2020 | 12,000 | 4,000 |
| Beyond | Oct 1, 2021 | TBD | TBD |


## Participation

### Contribute Funds
1. Go to the [DAO's Token Request App](TODO)
2. Click `New Request` in the top right corner
3. In `Offered Amount` enter the amount you would like to contribute (DAI, USDC or USDT)
4. In `Requested Amount` enter the amount divided by the seed price of $250.
5. Press `Create Request`
6. Send an email to `web3api@dorg.tech` the subject line 'Token Request' and the following information:
   - Name
   - ETH Address
   - Email Address
   - Why you want to contribute funds and receive tokens
7. All current token holders will receive this information and have 7 days to vote on your request. 

### Cancel your Contribution
At any time in the 7 day voting period you can cancel your request and have all funds returned.
1. Locate your request in the [Token Reqest App](TODO).
2. Click the dropdown next to the`Pending` status 
3. Click `Withdraw` and then `Create Transaction`

## Legal

...

## DAO Configuration

The Web3API DAO created from the [Reputation DAO Template](https://github.com/aragon/dao-templates/tree/master/templates/reputation), with the addition of the Token Request App.   

### Permissions
TODO, update: https://rinkeby.client.aragon.org/#/web3api/permissions/

### Voting App
[Usage Details](https://help.aragon.org/article/19-voting)  

#### Parameters
| Parameter | Description | Value |
|-----------|-------------|-------|
| Support | Relative percentage of tokens that are required to vote “Yes” for a proposal to be approved. For example, if “Support” is set to 50%, then more than 50% of the tokens used to vote on a proposal must vote “Yes” for it to pass. | 60% |  
| Minimum Approval | Percentage of the total token supply that is required to vote “Yes” on a proposal before it can be approved. For example, if the “Minimum Approval” is set to 20%, then more than 20% of the outstanding token supply must vote “Yes” on a proposal for it to pass. | 10% |  
| Vote Duration | Length of time that the vote will be open for participation. For example, if the Vote Duration is set to 7 days, then token holders have 7 days to participate in the vote. | 7 days |  

### Tokens App
[Usage Details](https://help.aragon.org/article/18-tokens)  

#### Parameters
| Parameter | Description | Value |
|-----------|-------------|-------|
| Transferable | Whether the token can be transferred by holders | false |  
| Max Account Tokens | Maximum amount of tokens an account can have (0 for infinite tokens) | 0 |  

### Finance App
[Usage Details](https://help.aragon.org/article/20-finance)  

#### Parameters
| Parameter | Description | Value |
|-----------|-------------|-------|
| Vault | Address of the vault Finance will rely on (non changeable) | Agent App |  
| Period Duration | Duration in seconds of each period | 2592000 (30 Days) |  

### Token Request App
[Usage Details](https://github.com/1Hive/token-request-app/blob/master/docs/user-guide.md)  

#### Parameters
TODO: verify these

| Parameter | Description | Value |
|-----------|-------------|-------|
| Token Manager | TokenManager address | Token Manager App |  
| Vault | Vault address | Agent App |  
| Accepted Deposit Tokens | Unique list of redeemable tokens in ascending order | TODO: ETH, DAI, USDC, USDT, etc |  

### Agent App
[Usage Details](https://help.aragon.org/article/37-agent)  
