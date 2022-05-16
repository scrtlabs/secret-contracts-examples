# Secret Contract Examples List
A curated list of Secret Contracts ordered by complexity. Secret Agents are welcome to suggest their own projects and improve these.

### Basic
1. [Counter](https://github.com/scrtlabs/secret-counter) - Increments a counter which you can query.
2. [Reminders](https://github.com/darwinzer0/secret-contract-tutorials/tree/main/tutorial1/code) - Lets users create a private reminder on the blockchain.
Includes [tutorial](https://learn.figment.io/tutorials/creating-a-secret-contract-from-scratch).
4. [Voting](https://github.com/scrtlabs/SecretSimpleVote) - Lets users vote "yes" or "no" privately [^1]. 
5. [Dice](https://github.com/scrtlabs/SecretDice) - Two players bet 1 scrt. Player 1 wins the pot if dice shows 1-3.
   * Demonstrates sending scrt.
   * Demonstrates randomness.
6. Calculator - Privately calculates basic arithmetic operations which are saved to the user's History.
   1. [With Cookies](https://github.com/liorbond/secretnetwork_sec4/tree/master/calc/src) - Includes stylized SecretJs client.
   2. [With Viewing Keys](https://github.com/eladr7/simplecalculator) - Simple Typescript SecretJs [client](https://github.com/eladr7/calculator-client).
   3. [With Permits](https://github.com/eshelB/secret-contract-calculator-with-permits) - Basic Javascript SecretJs [client](https://github.com/eshelB/secret-calculator-frontend).


### Advanced
1. [Decentralized Reviews](https://github.com/eshelB/decure/) - Users can review/rate businesses they transacted with[^1]. 
   * Includes basic inter-contract querying.
   * Basic Demonstration of an [Iterable Map](https://github.com/scrtlabs/secret-toolkit/tree/master/packages/incubator#cashmap), which isn't trivial concept in Secret Network.
2. [Blackjack](https://github.com/scrtlabs/SecretJack).
   * Includes Random number usage.
   * Includes deploying a contract from a parent contract.
3. [Poker](https://github.com/scrtlabs/SecretHoldEm).
   * Includes Random number usage.
4. [Sealed-Bid Auction](https://github.com/baedrik/SCRT-sealed-bid-auction).
5. [Migrations](https://github.com/scrtlabs/secret-migrate-example).
6. [AMM](https://github.com/scrtlabs/SecretSwap). 
   * 4 contracts: A [factory](https://github.com/scrtlabs/SecretSwap/tree/master/contracts/secretswap_factory) contract creates and lists many trading 
   [pairs](https://github.com/scrtlabs/SecretSwap/tree/master/contracts/secretswap_pair), which enable swaps based on liquidy added by providers who are rewarded LP [tokens](https://github.com/scrtlabs/SecretSwap/tree/master/contracts/secretswap_token).
   A [router](https://github.com/scrtlabs/SecretSwap/tree/master/contracts/secretswap_router) contract helps the UI show what paths between unexistent pairs

### Reference implementations
1. [SNIP-20](https://github.com/scrtlabs/snip20-reference-impl) - Transferable, private, fungible store of value (Token).
2. [SNIP-721](https://github.com/baedrik/snip721-reference-impl) - Transferable, private, non-fungible Token.

[^1]: currently vulnerable to replay attacks.
