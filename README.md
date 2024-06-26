## This Project is Live:

Link: [https://scaling-eth-hazel.vercel.app/]
<br>
Chiado Gnosis Deployment: [https://gnosis-chiado.blockscout.com/address/0x2E1e9Ad7020350eF362173161eDB8af8E8260EAb] (targetting for Build consumer focused products on Gnosis Chain for web3 users track)

## Problem Statement

In the volatile world of cryptocurrency trading, investors face a significant challenge: distinguishing genuine trading opportunities from elaborate scams. Despite promises of revolutionary trading bots offering life-changing returns, the landscape is littered with deceptive schemes like BitConnect, where investors lost billions to non-existent bots. This rampant fraud undermines trust and deters potential investors from engaging in algorithmic trading. Existing solutions lack transparency and accountability, perpetuating investor skepticism. Tradier seeks to address this issue by providing a decentralized platform where investors can confidently create, invest in, and withdraw from algorithmic trading bots. However, ensuring the security, reliability, and fairness of these bots remains a paramount challenge in the quest for a trustworthy trading ecosystem.

## Inspiration

Over the years, the investment landscape has been riddled with promises of revolutionary "next-gen trading bots" promising life-changing returns. Unfortunately, many of these turn out to be elaborate Ponzi schemes, with the infamous BitConnect scandal being a prime example. Investors lost over $2.4 billion to a purported "trading bot" that, in reality, never existed. In response to such deceptive practices, Tradier emerged. Our platform is dedicated to fostering a new era of trading by offering a decentralized, transparent environment for creating, investing in, and withdrawing from algorithmic trading bots.

## What it does

Tradier revolutionizes the world of trading through its unique NFT collection, leveraging the robust Avalanche C-chain. Each NFT in this collection is not just a digital asset but also functions as an individual wallet (under the ERC6551 standard), capable of holding and managing on-chain assets. What sets these NFTs apart is their embedded JavaScript code, which dictates their trading behaviors. This on-chain script is executed using Chainlink Functions, a groundbreaking feature that enables our trading bots to access both web2 APIs and external AI models, aiding in their decentralized decision-making process. The deployment of an NFT on Tradier allows the manager to set up automated trading strategies via Chainlink Automation's executeTrade function. This opens the door for external investors to engage with the NFT bot, allowing for both investment and withdrawal. To ensure equitable distribution of shares, the NFT bot utilizes Chainlink Data Feeds. This feature accurately assesses the current value of the wallet's tradable assets, thereby allocating shares in a fair and transparent manner. Moreover, the platform offers a smooth front-end interface for users to create, invest, withdraw, and even interact with "Tradeier" which is powered by GPT-4 and Coinmarketcap to help you make informed decisions on the crypto market.

## How Engineerians developed Tradier 

The frontend utilizes NextJs and ReactJs, the backend is powered by ethers, Thirdweb, OpenAI, and Coinmarketcap. The contracts are written in solidity and powered by chainlink functions, automation, and data feeds. The contracts are hosted on the avalanche C-chain an gnosis chiado.

## What we learned
Through our journey in developing this project, we've gained valuable insights into the critical importance of project planning and early problem mitigation in the infrastructure phase. We've learned that addressing potential issues proactively is crucial, as oversights can lead to significant challenges, especially when the project infrastructure is not functioning optimally. This experience has not only enhanced our technical skills but also reinforced the value of foresight and strategic planning in the complex world of tech development.

## What's next for Tradier

Traderier, currently in its functional prototype phase, is poised for transformation into a Minimum Viable Product (MVP). To achieve this milestone, several key steps are outlined. Expansion of On-Chain Capabilities: We aim to broaden the range of on-chain actions. This includes integrating a variety of routers and functions, surpassing the current offerings, to enhance the versatility and efficiency of our trading bots. Infrastructure Enhancement: Another critical step involves refining the infrastructure to support events and logs more effectively. This enhancement is vital for accurately tracking profit/loss values and integrating performance fees along with other final features. Finalizing and Securing the Platform: The last phase involves a thorough cleanup of our test contracts. This includes removing hardcoded test addresses to ensure greater flexibility and security. Subsequently, a comprehensive audit of the contract will be conducted to ensure its integrity and reliability.


## Getting Started

This is the Tradier, a Decentralized algorithmic trading bot marketplace and platform.

For local use, clone and run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
