# huntdefi-clog
Notes on the current state of [Hunt Defi](https://huntdefi.finance/) compiled from the discord, twitter, and other methods.

# Batches & Pools (1-6) : Crabada Idle Game

Pools in batches 1-5 feature teams of 2 [Craboids](https://docs.crabada.com/game-guide/crabadex/craboid) and 1 [Prime](https://docs.crabada.com/game-guide/crabadex/prime). Batch 6 pools however are composed if 2 [Prime](https://docs.crabada.com/game-guide/crabadex/prime) and 1 [Bulk](https://docs.crabada.com/game-guide/crabadex/bulk). This change was because the cost of crabs had gone up and to do the same team would have been an even lower ROI.

| Batch      | TUS @ Crab purchase | Pool Size | Current Expected ROI | TEam Tracker |
| ----------- | ----------- | --- | --- | --- |
| 1      |  $0.20       | $65000 | 1.4% (originally 1%) | [0x9da9](https://crabadatracker.app/profile/0x9da9feb8fad6a9a98594825d14f13cde3ca8fd3e) |
| 2      |  $0.22       | $70000 | 1.4%                 | [0xdef7](https://crabadatracker.app/profile/0xdef7cb0eaa0db7af60dfe90e2b1665441a44d7c1) |
| 3      |  $0.16       | $55000 | 1.4%                 | [0xd42a](https://crabadatracker.app/profile/0xd42a401d2762d8b22dba1bada7f9970457bcfac6) |
| 4      |  $0.16       | $55000 | 1.4%                 | [0xd109](https://crabadatracker.app/profile/0xd1090cfccaf7381db44b06a937a90780d2c61304) |
| 5      |  $0.08       | $37500 | 1.4%                 | [0x0e9c](https://crabadatracker.app/profile/0x0e9ceb3ea6c16d7cc0ad00927e6f038fb3b95525) |
| 6      |  $0.10       | $42500 | 1.1%                 | [0x07b6](https://crabadatracker.app/profile/0x07b6228e674ed8875a9b57db8c06f5bcea9f3f15) |
| 6      |  $0.126      | $46200 | 1.2%                 | [0x01d7](https://crabadatracker.app/profile/0x01d778e7de7e05b541b8c596fb579030ce4db291) |

## Distributions

Distributions of TUS to NFT owners appears to start around 23:00 GMT. (Nonce conflicts are no longer an issue according to chief)

## ROI

ROI is not based on the USDC.e deposited into a pool, but on the TUS that USDC.e bought. This has caused some confusion as participants of earlier batches saw reduced USD returns when the price of TUS fell in the weeks following those first batches.

Take Batch 1 for example, it was approximately 325,000 TUS ($65,000/0.20). 1% (inital ROI at launch) would have been 3,250 TUS/day. For every $100 (0.153% of pool), that would be ~5 TUS/day return.

This formula provides a rough estimate for what rewards you should expect. There is a [calculator located here](https://ipfs.io/ipfs/QmZwxEjRdpTRDkUT32fCkFBzZvAgrhmarHptebFFBykXPQ) that uses it to approximate the returns that should be seen.
```
(HuntPoolSize / TUSPriceAtCrabBuy / (HuntPoolSize/SharePrice) * (PoolROI/100) * (HuntPoolSize / SharePrice * (PercentOfPoolOwned/100)))
```

### CCC's fee/cut

CCC announced that their fee will be reinstated on 3/23/22 and then annouced that it would be lowered to 10%. It is unknown on when it is calculated.

```
(GrossTUS - ReinforcementFees) - CCCFee
(GrossTUS - CCCFee) - ReinforcementFees
```

### Other considerations on returns

Mid March 2022, the CCC mining bots were updated with the ability to reinforce against looting raids from the tavern. This has had an impact on returns and is not reflected in the [Rewards](https://huntdefi.finance/rewards) page.

## Pivots
According to chiefreflektooorrr, pools can pivot to other strategies in Crabada or even liquidate and do something else. Eg. If battle will be a better use of the teams and roi, they can pivot to do that instead of the idle game.

# Secondary Markets

Hunt NFT's can be sold on the secondary market on [Kalao](https://marketplace.kalao.io/collection/0x3b50d61ab8752a10df0ec588b7cd40efc4accf00). While an NFT is listed on this marketplace, you will not receive TUS. While it has not occured for a while, it is assumed that the Kalao contract would receive the TUS.

Generally given advice is to only sell if you need the cash and only buy if the cost is less than 100 days for ROI at current TUS price.

# Links

* [Hunt Defi](https://huntdefi.finance)
* [CCC](https://crosschaincapital.finance/)
* [NFT Market](https://marketplace.kalao.io/collection/0x3b50d61ab8752a10df0ec588b7cd40efc4accf00)
* [Hunt ROI calculator](https://ipfs.io/ipfs/QmZwxEjRdpTRDkUT32fCkFBzZvAgrhmarHptebFFBykXPQ)
* [TUS Price chart](https://dexscreener.com/avalanche/0x565d20bd591b00ead0c927e4b6d7dd8a33b0b319)
* [Tampermonkey script for huntdefi/adv](https://k51qzi5uqu5dl05p70ja8uwvsnlsl9gidm7mfy67ol2xnc19be7hq4cnecvr13.ipns.dweb.link/)
