# Current Initiatives

## Research

### Go to market

Discover the optimal market opportunities for open money adoption.

| Initiative | Status |
| :--- | :--- |
| User interview process by OMD | Setting up process |
| Revenue experiments by Mosendo | Creating experiments |

## Prototyping

### Global fiat exchange

**Problem:** usability research discovered that new users have trouble figuring out how to buy crypto with their existing money. This problem is compounded by most countries having very different tools, services, and laws around the purchase and cryptocurrency, leading to highly fragmented markets and the need to use multiple tools and exchanges to acquire the desired crypto currency.

**Solution:** a unified interface that aggregates global fiat gateway solutions. The user can discover the best means to purchase crypto in their country, whether it be bank transfer, credit card, ewallet, cash networks, or other.

**Current progress**: Developers and designer needed.

### GAS relayer for ETH

**Problem:** On the Ethereum network, users holding ERC20 tokens are not able to pay the GAS transaction fees with their token, and must acquire a small amount of ETH to make a transaction. For users who have acquired DAI but don't have a good way to purchase a small amount of ETH, this can add a lot of usability friction or even trap user funds.

**Solution:** So called "relayers" solve this issue by submitting transactions on a user's behalf and paying the ETH costs for them. In exchange they can take a small amount of the ERC20 token to cover the ETH costs they incur.

**Current progress:** [Gasless.js](https://github.com/mosendo/gasless.js) relayer currently operating for DAI transfers. Additional resources needed to increase different types of transactions supported by the relayer.

### Cash exchange network

**Problem:** Many of the highest demand use cases for open money require exchanging cryptocurrencies and cash. For cash exchange to be useful in a given geography it must be safe, ubiquitous and somewhat convenient.

**Solution:** to provide this service, a decentralized cash network must be built which has open problems around reputation and bootstrapping network effects.

**Current progress:** [ZimDai](https://github.com/coinop-logan/ZimDai/blob/master/whitepaper.pdf) proposal for building a cash agent network in Zimbabwe

## Building

### Usability

**Problem:** through thousands of user interviews and discussions with other crypto product builders, several nearly universal barriers to crypto usability were identified:

* Strong aversion to private key / seed phrase management
* Confusion over GAS and fees
* Fees sometimes too high
* Transaction speed sometimes too slow
* Public key errors and aesthetics
* Purchasing / acquiring cryptocurrencies from traditional money system

**Solution:** [Mosendo](https://mosendo.com/)'s product simultaneously tests solutions to all above usability issues with the following features: email/sms/social based key management abstraction, gas-less transactions with relayer, instant no fee transactions with Connext state channels, usernames, fiat gateway integrations.

**Current progress:** Alpha testing complete, beta launch in Feb 2020

