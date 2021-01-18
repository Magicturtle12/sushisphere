

#  Episode 14 Outline

* * *

## Sushinomics
##### Price: 7.13
>up 104% 14day
>sushibar staking at ATH


##### 24hr Trading volume(avg of last 7 days): ~$377 million



## News and Development


### 2021 Roadmap Release
https://sushiswapchef.medium.com/2021-3e1f45cf86a2

##### -Sushibar v2 
    - No lockup so we can integrate inside Aave-Maker
    - Keep3r auto-serving of rewards
    - Wrapped-SLP to be used in various money market


##### -AMM v2 + Deriswap
    - Franchised Pools
    - Double Yield
    - K3PR dynamic Yield Rebalancing
    - Integrated 1-Click Zap

##### -BentoBox
https://boringcrypto.medium.com/bentobox-to-launch-and-beyond-d2d5dc2350bd

    We expect to be done with Formal Verification led by Certora (3–4 weeks) after the soft-launch 
    and hope to secure audits led by Trails of Bits in addition to the current ones already done 
    by Quantstamp & PeckShield.

##### -Domain + IPFS
    Sushiswap will be moving to a new consolidated domain in 2021 to reflect better how we 
    aren’t an AMM anymore moving forward but an OpenOrg part of the Yearn ecosystem.
    
##### -Governance
    AragonV2 being considered https://gov.yearn.finance/t/adopt-snapshot-aragon-for-binding-governance/5568/67 
    
    Another option would be to follow the steps of Synthetix 
    and opt for a Council of community members voted by the community.
    
    Targeting governance upgrade by Q4 2021

#### -Miso

The launchpadV1 will bundle together multiple features which is widely known are going to be available out-of-the-box :

    - Freeze of SLP with vesting for teams
    - Liquidity Mining
    - ICBO
    - Farms
    - Auctions
    - Crowdsales

#### Integrations
        - Cross-chain AMM enabled by (Rune/Moonbeam)
            - Polkadot/Moonbeam should have a live testing version of Sushiswap Q2 on Kusama
        - MEV integration via ArcherDAO
            -(SLP pools should aim to be last in a block when deployed to prevent sniping by bots)
        -Incentivize teams, wallets, dApps & protocols to build with Sushiswap via an emission enabled pool of 0.1x
 
###### A current list of projects secured for Q1 2021 :

- FRAX (https://frax.finance)

- DSD (https://dsd.finance)

- BAO (https://www.bao.finance)

###### More will be joining our establishment soon.

#### Layer 2
    We will move in sync with the greater Yearn ecosystem. Zk-rollups are currently the option privileged 
    since composability is key. Matter labs have been quite supportive, and we are keeping up with the 
    latest development of Zinc.

    Ultimately this decision will lay in the hands of our CTO — core devs and Yearn ecosystem participants.


### Pro trading UI developed and released by GoldenNaim
https://trader.sushiswap.fi/
live Arbitrage view, compact yield farming stats, and API documentation for builders 

### 0xMaki interview with Puzzle Ventures
https://twitter.com/PuzzleVentures/status/1351102467832950788

     scheduled Tuesday Jan 19 at 3pm UTC+8 (Beijing Time)
     
------------------------------------------
     
## Recap from dev q&a, Writeup by: @orionmuir

**When can we expect Bento? When will the audit become available to the public?

Bento should be integrated into our main UI and available to the public mid next month. The audit was completed last month and we have successfully implemented Peckenshield’s suggestions. However, we are committed to delivering a product that we are sure is safe for our users. We have continued to test Bento, as many protocols with respected audits have been exploited. We discovered issues that were not found in the audit and have patched these. Maki has been on holiday recently, he will be back in action and the pace of things should pick up.

**What are sushi’s plans with the dot network?

So far we are collaborating specifically with the moonbeam protocol. The planis to have the moonbeam network airdrop a small amount of native token as well as taking their ethereum sushi balance giving them a corresponding amount of moonsushi tokens. 

**Any updates on Aave allowing xsushi as collateral?

Since the original announcement I have heard nothing. (double checks chainlink) There isn’t a proper oracle for xSushi. I (boring) could easily make one, but haven’t been directed to.

**What is the status of the limit order functionality for Sushi?

This was developed by LevX and had been available in tester mode on https://sushiswap.fi/, but very recently its functionality was removed due to a bug. We noticed very little activity for this feature and decided other features such as bento box UI should be prioritized by LevX. He still plans on completing this, but there is no release date yet.

**Yearn has a newsletter which helps get the word out about new developments in the ecosystem. I notice that sushi has so many developments, but no one knows about them. Does sushi have any plans for a newsletter?

We desperately need one. I think that we should hire somebody. I will take to Miya about this.

**Any updates on that cool traderview ui for sushi that I saw referenced a while ago on your discord?

Actually we already released this. Further proof we need to get news out to the community. You can access it at https://www.sushitrader.io 5 or https://trader.sushiswap.fi/ 5 I really like how it shows you all the swaps that are taking place in real time.




### Core Developer AMA 
    
    There will be an AMA today at 1.15 pm PT, 10:15 pm CET on Keno's(core dev) youtube channel
    https://www.youtube.com/watch?v=BtnUJ4Sq2tw





* * *

## Noteworthy Proposals

### Mint SUSHIO Stablecoin with SUSHI collateral
##### Made by: OpenDAOLogan
https://forum.sushiswapclassic.org/t/mint-sushio-stablecoin-with-sushi-collateral/1944
Summary
>

    The creation of a SUSHIO stablecoin provides the community of SUSHI holders an incentive to go long on SUSHI by 
    giving them the ability to mint a stablecoin (redeemable against other stablecoins) using SUSHI as collateral, 
    thereby allowing holders to employ their capital without selling any SUSHI holdings.

    This is made possible via the collaboration between OpenDAO and UMA, and is part of ‘flagship’ series of 
    stablecoins. Incentivised liquidity pools will need to be set up with SUSHI support to ensure liquidity 
    against other major stables such as USDC. OpenDAO will operate and oversee the process.


Thoughts:
Very similar to the ichi farm concept, aswell as frax. The proposal is much more straightforward than ichifarm's proposal however I personally feel the Onsen application process is the proper channel for any erc20 token to earn AP weight. I also agree with several people in the forums that it's in sushiswaps best interest to deploy a stablecoin that is wrapped on the bentobox, rather than relying on a third parties code.



***

Follow @TheSushiForum on twitter for sushi forum updates
and follow @NewSushiTimes for great sushiswap updates
