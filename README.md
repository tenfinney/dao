# Web3API DAO
[Mainnet](https://client.aragon.org/#/web3api)  

## Purpose
Stewarding The Web3API Ecosystem

## Configuration: Apps, Parameters, and Permissions

### Voting App
Used to create and participate in votes. Votes can be linked to an action, such as minting new W3 tokens or transfering funds from the vault. They can also be purely informative.  

#### Parameters

| Parameter | Description | Value |
|-----------|-------------|-------|
| Support | Relative percentage of tokens that are required to vote “Yes” for a proposal to be approved. For example, if “Support” is set to 50%, then more than 50% of the tokens used to vote on a proposal must vote “Yes” for it to pass. | 60% |  
| Minimum Approval | Percentage of the total token supply that is required to vote “Yes” on a proposal before it can be approved. For example, if the “Minimum Approval” is set to 20%, then more than 20% of the outstanding token supply must vote “Yes” on a proposal for it to pass. | 10% |  
| Vote Duration | Length of time that the vote will be open for participation. For example, if the Vote Duration is set to 7 days, then token holders have 7 days to participate in the vote. | 7 days |  

#### Permissions

| Permission | Description | Grantee | Manager |
|------------|-------------|---------|---------|
| CREATE_VOTES_ROLE | Create new votes | Tokens App | Voting App
| MODIFY_SUPPORT_ROLE | Modify support | 
| MODIFY_QUORUM_ROLE | Modify quorum | 

### Tokens App

### Finance App

### Token Request

