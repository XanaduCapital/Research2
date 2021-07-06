<h3 align="center">
    <img width="10%" src="https://docs.near.org/img/near_logo.svg"><br>
    Near Protocol (5th July, Zombie)
</h3>

---

## Table of Contents

- [Overview](#Overview)
- [Links](#Links)
- [Tokenomics](#Tokenomics)
- [Code Overview](#Code)
- [Team Members](#Team)
- [Advisors & Early Backers](#Advisors)
- [Project Roadmap](#Roadmap)
- [Ecosystem & Network Effect](#Ecosystem)
- [Community Support](#Community)
- [Potential Competitors](#Competitors)
- [Problems and areas of concern](#Problems)
- [Final Verdict](#Verdict)
- [Your Impressions](#Thoughts)

## Overview <a name = "Overview"></a>

- Problem: Many current smart contract platforms have issues with scalability (Ethereum currently) and decentralization (BSC, Solana, Ethereum side chains). They also face challenges updating and iterating (Eth upgrade to 2.0, and Cardano... 1.0) and have steep learning curves for users.
- Solution: Near Protocol is a fast, decentralized blockchain with a focus on providing a friendly experience to non crypto native users while remaining nimble enough to quickly iterate and evolve.
- Unique Features:
  - Near will have a simpler experience that is more familiar for non crypto native users.
    - Accounts have human readable names
    - User-authorized apps have application-specific access keys and spending limits, providing a single sign on type experience and limiting the number of authorizations needed from users.
    - Application-specific access allows for subscription models for dapps
    - Developers can pay for users' usage. In crypto, users usually pay gas for every transaction. But outside crypto, when doing transactions like these (like using a credit card or sending a friend money), transaction costs for the users are usually covered by the organizations that they are interacting with.
  - For Near, creating a nimble organizational design was a foundational principle. The governance and organization structure were made to avoid the long development times and delays in upgrades that have plagued projects like Cardano and Ethereum.
  - The protocol will dynamically rebalance itself by increasing or decreasing the number of shards, depending on network demand.
- Technology:
  - Sharded, proof of stake, delegated
  - 100,000 transactions per second
  - Near-instant finality / 1 second block cadence.
  - [Trustless bridge to eth](https://near.org/blog/eth-near-rainbow-bridge/). There are a number of bridges between eth and other chains, but most rely on multi sig relayers and are not trustless. Near's bridge can also send smart contract data. So, for example, an Ethereum protocol could hold DAO votes on NEAR and record the results on Ethereum.
  - [Aurora](https://near.org/blog/aurora-launches-near/) - The ability to run EVM apps on Near; this will provide a sidechain-type experience. The Near protocol uses WASM for smart contracts, but for Aurora, they made a smart contract that runs the EVM, so dapps can run through this contract.
- Project History: Alexander Skidanov and Illia Polosukhin founded Near in 2018 after meeting while taking part in the Y Combinator startup accelerator program.
- Value Proposition: Fast/scalable blockchain; focus on user experience; focus on protocol upgradability; collaborative culture
- Token Use Cases: Staking / delegating; governance; gas.

## Links <a name = "Links"></a>

- Website: [https://near.org/](https://near.org/)
- Whitepaper: [https://near.org/papers/the-official-near-white-paper/](https://near.org/papers/the-official-near-white-paper/)
- Github: [https://github.com/near](https://github.com/near)
- Twitter: [https://twitter.com/nearprotocol](https://twitter.com/nearprotocol)
- Telegram Announce: [https://t.me/nearprotocolnews](https://t.me/nearprotocolnews)
- Telegram Community: [https://t.me/cryptonear](https://t.me/cryptonear)
- CoinMarketCap: [https://coinmarketcap.com/](https://coinmarketcap.com/currencies/near-protocol/)
- Block Explorer [https://explorer.near.org/](https://explorer.near.org/)

## Tokenomics <a name = "Tokenomics"></a>

[Token distribution details](https://near.org/blog/near-token-supply-and-distribution/)<br>
Inflation, transfers, and unlocking began when the final Mainnet phase started on 10/13/2020.

- Circulating Supply: 411,574,082
- Total Supply: 1,000,000,000
- Maximum Supply: Inflationary (5% annual). Transaction fees are burned, but they are so low that huge volume would be needed to make a big dent.
- TGE Event Info:<br>
  <img width="50%" src = "https://near.org/wp-content/uploads/2020/06/near_purchases_unlock_cumulative-1024x568.png"><br>
  <img width="50%" src = "https://near.org/wp-content/uploads/2020/06/near_purchases_rounds_2-1024x528.png">
- Token Distribution:<br>
  <img width="50%" src = "https://near.org/wp-content/uploads/2020/06/near-genesis-pie-chart-4b-1024x580.png">
- Token Unlock Schedule:<br>
  <img width="50%" src = "https://near.org/wp-content/uploads/2020/06/near-circ-supply-by-category-4-1024x564.png">

## Code Overview <a name = "Code"></a>

Development seems active, and I believe core parts of the code were audited.

## Team <a name = "Team"></a>

[Link to team profiles](https://near.org/team/)

1. [Alexander Skidanov](https://www.linkedin.com/in/skidanovalex) - Co-Founder.
2. [Illia Polosukhin](https://www.linkedin.com/in/illia-polosukhin-77b6538) - Co-Founder.
3. [Erik Trautman](https://ch.linkedin.com/in/erik-trautman) - CEO.

## Advisors & Early Backers <a name = "Advisors"></a>

- Coinbase Ventures (could there be a Coinbase listing down the line?)
- Multichain Capital
- Numerous others

## Roadmap <a name = "Roadmap"></a>

- [Original roadmap](https://near.org/blog/mainnet-roadmap/)
- [Current roadmap](https://gov.near.org/t/protocol-development-roadmap/2903)

## Ecosystem & Network Effect <a name = "Ecosystem"></a>

Some of the first projects include a [dex](https://app.ref.finance/), and [NFT platform](https://paras.id/), a [launchpad](https://skyward.finance/), and a [prediction market](https://near.org/blog/aurora-launches-near/). The Near site lists MakerDAO as a project that is building on Near. I wasn't able to find any references for this, but Maker did host Near on a [community call](https://www.youtube.com/watch?v=ZeCzFwFZeU4&t=1s).

There is a [community-run site](https://awesomenear.com/) with a list of projects building on Near.

## Community Support <a name = "Community"></a>

- Observations.
  - [Telegram](https://t.me/cryptonear): Over 26,000 members, but the group doesn't have a ton of activity.
  - [Discord](http://near.chat/): Over 14,000 members
  - [Twitter](https://twitter.com/nearprotocol): Over 83,000 followers.

## Potential Competitors <a name = "Competitors"></a>

- Other leading, advanced Layer 1 smart contract protocols - i.e. Ethereum (2.0 and/or scaled with rollups and side chains) , Polkadot, Cardano, Solana, Avalanche, Cosmos ecosystem, etc.

## Problems and areas of concerns<a name = "Problems"></a>

- There's 15 months left with steep token unlocking.
- The [Near Foundation](https://near.org/blog/introducing-the-near-foundation/) has a lot of power - including deciding who makes updates to the protocol and how treasury funds are used. The whitepaper mentions that community operated governance will be implemented in the future, but there is no timeline or date for this. This foundation is run by four board members, so a lot of power is concentrated in their hands.
- There is no composability because the chain is sharded.

## Final Verdict <a name = "Verdict"></a>

There's a lot to like here:

- The team is elite. One co-founder (Illia Polosukhin) worked at Google, where he was a major contributor to TensorFlow. The other co-founder (Alexander Skidanov) worked at Microsoft before moving to the database system company memSQL, where he was Director of Engineering. Skidanov is also a former International Collegiate Programming Contest gold medalist - one of many programming challenge champions on their team.
- They seem to really understand and focus some very important factors that not all projects pay enough attention to.
  - Communication - the whitepaper is written beautifully - it written at a level that makes it accessible for non technical people, while still going over many details and providing references to more technical documents for people who want to take a deeper dive into the weeds.
  - Organizational design - there's a foundational focus on having an organizational design that allows the project to quickly iterate in a competitive, fast-moving landscape.
  - User experience - many confusing parts about doing things on chain are abstracted away from end users
  - Collaborative culture - some protocols and their communities (such as, arguably, Cardano and Avalanche) seem to have an "Ethereum killer" / maximalist mindset. Others, such as Polkadot and the Cosmos ecosystem, are more collaborative. Near definitely is the latter. This was evidenced in their [whiteboard series](https://www.youtube.com/playlist?list=PL9tzQn_TEuFWweVbfTbaedFdwVrvaYPq4), where they met with designers of many other protocols (including Ethereum 2.0, Solana, Polkadot, and Cosmos) for deep technical dives into their protocols. This series hhighlights Near's collaborative mindset. Also, the fact that so many competitors participated in this series is an indication that the Near team is well respected in the crypto industry.
- The tech seems good too - 100,000 tps, fast finality, low fees, dynamic sharding that re-allocates accounts based on congestion, and support for both WASM and Solidity. I'm not an expert on blockchain tech though, so this is just from my understanding of it.
- Drawbacks include:
  - The large amount of tokens that will be unlocked over the next 15 months
  - The current centralization of governance in the Near Foundation
  - Also worth noting - not everything from the whitepaper has shipped yet. See the [current roadmap](https://gov.near.org/t/protocol-development-roadmap/2903).

## What are your thoughts on Near? <a name = "Thoughts"></a>

[![](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Great!)](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Great!/vote)
[![](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Meh.)](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Meh./vote)
[![](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Not%20good!)](https://api.gh-polls.com/poll/01F9X1QPG8WM8MSEVXG4S0PMQZ/Not%20good!/vote)
