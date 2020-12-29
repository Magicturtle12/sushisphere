#  Episode  Outline

* * *

## Sushinomics
##### Price: 2.59



##### 24hr Trading volume(avg of last 7 days): ~$145 million



## News and Development

### croco.finance adds sushiswap lp support


### HUGE bentobox update post

https://medium.com/@boringcrypto/bentobox-to-launch-and-beyond-d2d5dc2350bd 


    All the DeFi protocols work with tokens. They need to be stored somewhere. 
    In most cases, they are stored in the contract that works with them. In the 
    USDC-WBTC pair on SushiSwap for instance, the USDC and WBTC tokens are held
    in the contract for this specific pair. This way you need to approve each 
    token for use in each protocol.

     This is where the BentoBox comes in. The BentoBox is a single vault that holds all tokens.
     Not just for the lending contracts, but also for any other protocols and future extensions.
     Anyone can build extensions that use the BentoBox as their vault with these benefits:

    Once a token is approved for the Vault, any protocol built using BentoBox doesn’t need per token approval anymore.
    Low flat gas fees for internal token transfers (even between different protocols using BentoBox) and advanced transfers such as one-to-many transfers.
    Funds of users and protocols are separated internally. Only protocols that the user approves can access the user’s funds.



    Issue Synthetic Assets (such as Stablecoins)

    Once lending is live, only a small change is needed to allow users to deposit collateral 
    and instead of lending assets, they can mint synthetic assets. Oracles, liquidation, etc 
    all work the same. When the synthetics are returned, they are burned and collateral is returned.

    Initially, we could support xSushi as the main collateral, so you can be earning SUSHI while minting synthetic assets.


    Once the BentoBox has Lending, AMM, etc and the BentoBox Plus is live, here’s an example of how it could be used:

    Let’s say you HODL ETH and BTC. You could add your WBTC and ETH to the BentoBox and provide both assets for Lending.
    This will give you lending tokens. These tokens could be placed in an AMM pair and they will be arbitraged by 
    traders as the price of ETH-BTC moves (indirectly providing more liquidity to the overall on-chain ETH-BTC market).
    This will mint you SLP tokens for this pair. This could be supplied as collateral to borrow for instance USDC
    (or to borrow more WBTC and ETH to repeat the above and leverage this position).

    This takes capital efficiency options to a whole new level.


Anticipated release date mid-january 


### Binance Staking Launches SUSHI Super Rewards 
Binance launching built-in sushi staking for binance users 
https://www.binance.com/en/support/announcement/da8663d40f7e434da2431b26c7f077c8



### Zerion adds sushiswap support 
https://twitter.com/SushiSwap/status/1339648402188087297



### Thread by @Future_Fund_ on the optimistic future of Sushiswap
https://twitter.com/FUTURE_FUND_/status/1341006450311581696



### 




### Cover Protocol Exploit and Recovery of funds
funds safu(mostly) https://twitter.com/emilianobonassi/status/1343706279596986368



* * *

## Noteworthy Proposals

### oneSUSHI Proposal: A Stablecoin Governed by Sushipowah 
##### Made by: Masanobu_Fukuoka
https://forum.sushiswapclassic.org/t/hiring-guideline/1605

**Summary**

Create a sushi-backed stablecoin via the ichi.farm platform, 25k sushi sent to collateral vault on ichi.farm 50k ichi sent to ichi-oneSUSHI liquidity rewards.

Here are the basics:

    - When you mint, you pay the $1 of value in two parts: part USDC and part SUSHI. When you redeem, you only get back USDC. That is how you can make a strong guarantee that you will get $1 of value when redeeming.
    - The SUSHI paid in goes into a community treasury.
    - The ratio of USDC to oneSUSHI minted is called the minting ratio. It will initially be 100%. The ratio of buying to selling in any given hour will raise or lower the minting ratio by 0.2%. There is a minimum ratio set by oneSUSHI holders as well for safety purposes.
    - Minting (0% now) + Redemption (0.5% now) fees stay in USDC reserves, helping to drive over-collateralization even at a stable ICHI price. These fees should be lowered to 0% over time.





### Hiring Proposal: Hire BoringCrypto as Lead Architect for Sushi
Boring Crypto has been with sushiswap since the earliest of the early days. A short list of work done

    - Did the first and only test migration on Ropsten testnet
    - Created https://app.boring.finance 27
    - Identified the problem with SushiMaker and fixed it (serving of USDT was broken)
    - Took over protocol maintenance from SBF and team. Created tools to manage the MasterChef contract through the TimeLock and multi-sig wallet effectively.
    - Championed and organized the Menu of the Week system
    - Proposed and implemented emission reduction schedule
    - Implemented 2/3 lockup (even though I wasn’t a fan of this solution :P)
    - Invented and created BentoBox and the BentoBox Lending solution
    - And I’ve been helping out in the discord and discussing many proposals on the forums, writing some Medium post to inform the community, etc.

Boring's roles on the team would include 
    
    - Setting a roadmap for core Sushi development
    - Vetting the roadmap with the community
    - Delivering on the roadmap together with the core team and many great contributors
    - Helping/guiding any “side projects” to create the best integration with the core Sushi protocol
    - Communicating the planning and progress made and incorporating feedback

Boring's thoughts on compensation

    First I’d like to point out that with the rising price of SUSHI, I do believe the core team is currently 
    a bit overpaid. Although we have to keep in mind that a large part of this is the reward for believing 
    in Sushi when things weren’t going great and sticking with it and taking a risk. This risk should be 
    rewarded.Since I’ve been part of this ride since the beginning I feel it’s fair that I would receive 
    compensation in line with the other members of the core team (or the compensation of the core team 
    should be adjusted, which I would support).

https://forum.sushiswapclassic.org/t/hire-boringcrypto-me-as-lead-architect-for-sushi/1699/36

***

