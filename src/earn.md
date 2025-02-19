# Earn
## Yield Aggregator

The yield aggregator is our autonomous algorithm that searches for the highest yield through a collection of safety-assessed DeFi lending protocols. To participate, you can choose from three distinct pools to deposit into: USDC, DAI, and ETH.  You will earn yield on your deposit, typically seen as APY%, and you may withdraw your funds at any time into any of our supported assets.

Our yield aggregator finds yield through partnered protocols as well as our internal Fuse protocol which collects borrowing and lending fees of customized assets.

![E4vpYizVEAIf755](https://user-images.githubusercontent.com/50163445/123555712-36a93300-d73c-11eb-870f-72ac74a2b87d.jpg)

## How Does Rari Capital Earn Yield?

The Yield Aggregator system optimizes for the highest returns across a series of protocols within the Ethereum DeFi ecosystem. Our USDC and DAI pools are broadcast into stable-asset strategies, while the ETH pool maintains exposure to price volatility of Ethereum. These pools earn yield for users by lending and farming across various DeFi protocols such as Compound Finance, dYdX, KeeperDAO, mStable, yEarn, Aave, and Fuse Pools. We are actively expanding our strategy set to focus on more sustainable yields on and off of the blockchain. The pools are now playing an active role within Fuse by providing liquidity to borrowers, as well as letting pool depositors reap the benefits of high-yield opportunities.

## Rari Capital USDC Pool

The Rari Capital Stable Pool allows users to deposit ETH or any ERC20 token and receive $RSPT in return. The $RSPT token tracks your interest-accruing position. All ERC20s will be swapped to USDC (meaning there is slippage for all deposits except USDC). As a holder of $RSPT, the Yield Aggregator protocol is working autonomously to deliver the highest yield on your principle.

**Integrated Strategies:**

- **Lending USDC on [Compound Finance](https://compound.finance/)**
  - Compound Finance generates yield by supplying USDC to borrowers who pay interest. 
- **Lending USDC on [Aave](https://aave.com/)**
  - Aave generates yield by supplying USDC to borrowers who pay interest. 
- **Lending USDC on [dYdX](https://dydx.exchange/)**
  - dYdX generates yield by supplying USDC to borrowers who pay interest. 
- **Providing liquidity to [mStable](https://mstable.org/)**
  - mStable generates yield by lending the underlying assets behind mUSD to decentralized lending pools such as Compound Finance and Aave, as well as returning all fees generated by the protocol to all holders of mUSD. 
- **Lending USDC to [Fuse Pools](app.rari.capital/fuse)**
  - USDC Fuse Pools generate yield by supplying USDC to borrowers who pay interest. 

## Rari Capital DAI Pool

The Rari Capital DAI Pool allows users to deposit DAI or any ERC20 token and receive $RDPT in return. The $RDPT token tracks your interest-accruing position. All ERC20s will be swapped to DAI (meaning there is slippage for all deposits except DAI). As a holder of $RDPT, the Yield Aggregator protocol is working autonomously to deliver the highest yield on your principle.

**Integrated Strategies:**

- **Lending DAI on [Compound Finance](https://compound.finance/)**
  - Compound Finance generates yield by supplying DAI to borrowers who pay interest. 
- **Lending DAI on [Aave](https://aave.com/)**
  - Aave generates yield by supplying DAI to borrowers who pay interest. 
- **Lending DAI on [dYdX](https://dydx.exchange/)**
  - dYdX generates yield by supplying DAI to borrowers who pay interest. 
- **Providing liquidity to [mStable](https://mstable.org/)**
  - mStable generates yield by lending the underlying assets behind mUSD to decentralized lending pools such as Compound Finance and Aave, as well as returning all fees generated by the protocol to all holders of mUSD. 
- **Lending DAI to [Fuse Pools](app.rari.capital/fuse)**
  - USDC Fuse Pools generates yield by supplying DAI to borrowers who pay interest. 



## Rari Capital ETH Pool

The Rari Capital DAI Pool allows users to deposit ETH or any ERC20 token and receive $REPT in return. The $REPT token tracks your interest-accruing position. All ERC20s will be swapped to ETH (meaning there is slippage for all deposits except ETH). As a holder of $REPT, the Yield Aggregator protocol is working autonomously to deliver the highest yield on your principle.

**Integrated Strategies:**

- **Earning yield from liquidations (facilitated by [KeeperDAO](https://app.keeperdao.com/))**
  - KeeperDAO is an on-chain liquidity underwriter. The users who join KeeperDAO work together to liquidate DeFi loans and attain rewards. 
- **Lending ETH on [Compound Finance](https://compound.finance/)**
  - Compound Finance generates yield by supplying ETH to borrowers who pay interest. 
- **Lending ETH on [Aave](https://aave.com/)**
  - Aave generates yield by supplying ETH to borrowers who pay interest. 
- **Lending ETH on [dYdX](https://dydx.exchange/)**
  - dYdX generates yield by supplying ETH to borrowers who pay interest. 
- **Lending ETH to [Fuse Pools](app.rari.capital/fuse)**
  - ETH Fuse Pools generate yield by supplying ETH to borrowers who pay interest. 

If you are interested in learning more about each of the strategies and our framework for identifying which ones to implement, check it out [here](https://www.notion.so/Rari-Strategy-Assessment-Framework-2d1edffcf80f4750973f6e90e97b70a4).

## What Are The Fees?

**Stable Pool: 17.5% profits**

**Yield Pool: 12.5% profits + 0.5% withdrawal**

(The withdrawal fee is required to prevent arbitrage within this pool since it is composed of various stablecoins which may have minor price fluctuations)

**ETH Pool: 17.5% of profits**

## How to Deposit

**Step 1: Connect a Wallet**

The Rari Capital ecosystem currently supports [MetaMask](https://metamask.io/), [WalletConnect](https://walletconnect.org), [Portis](https://portis.io), [Torus](https://tor.us/), [Fortmatic](https://fortmatic.com/), and [Authereum](https://authereum.com/). If you do not have a wallet, we recommend you refer to [this guide ](https://metamask.zendesk.com/hc/en-us/articles/360015489531-Getting-Started-With-MetaMask-Part-1)for [MetaMask](https://Metamask.io). Users can connect their wallets by selecting the "Connect Wallet" button on the [Rari Capital Earn Portal](https://app.rari.capital/Earn).

**Step 2: Choose a Pool**

Once connected, users are able to view the multi-pool dashboard, equipped with a comparative graph of the returns between each pool. Users may then deposit into the pool(s) of their choosing by selecting the transaction button (the button with two arrows). This will prompt the deposit window, where users can select a supported asset of their choice to deposit.

**Step 3: Deposit a Supported Asset**

After choosing a pool and selecting the deposit button, users can then select any of the supported crypto-assets and deposit them within the pool. This can be done by selecting the asset menu, choosing your desired asset, inputting your desired amount, or hitting the "max" button to select the maximum amount in your wallet, and hitting the deposit button. For MetaMask users, you will then receive a transaction approval window, where first-time users must approve contract interactions, and all users must approve of individual transactions.

It is worth noting that depositing in a currently active token will require less gas for the transaction than depositing an inactive asset. This means that it will use more gas to deposit an inactive asset, as it will also need more swaps to reach an active asset.

Additionally, you are able to deposit hundreds of different assets that will instantly be swapped on deposit through our integration with 0x.

**Step 4: Track Your Interest Accrued**

After depositing, your returns can be viewed either within the individual pool dashboards or on the multi-pool dashboard, where you can rotate through returns across the entire protocol for various time periods.

## How to Withdraw

**Step 1: Choose a Pool**

Once connected, users can view the multi-pool dashboard. Users may then withdraw from the pool(s) of their choosing by selecting the transaction button (the button with two arrows). This will prompt a new window.

**Step 2: Withdraw Into a Supported Asset**

After choosing a pool and selecting the transaction button, users can then toggle the withdrawal function with the gear button in the top right. Then, select any of the supported crypto-assets and withdraw from the pool. This can be done by selecting the asset menu, choosing your desired asset, the amount, and by pressing the "Withdraw" button.

It is worth noting that it will cost less gas to withdraw in any tokens currently active within the protocol, as it will require fewer swaps. Conversely, this means that it will require more gas for withdrawals in assets not currently active.

------

If you noticed anything throughout your experience that was not described in this tutorial, we encourage you to reach out in our [Discord](https://discord.gg/9SHdAGdW) for assistance and a community member will always be wiling to help.