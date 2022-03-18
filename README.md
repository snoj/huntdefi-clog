# huntdefi-clog
Notes on the current state of [Hunt Defi](https://huntdefi.finance/) compiled from the discord, twitter, and other methods.

# Batches & Pools (1-6) : Crabada Idle Game

Pools in batches 1-5 feature teams of 2 [Craboids](https://docs.crabada.com/game-guide/crabadex/craboid) and 1 [Prime](https://docs.crabada.com/game-guide/crabadex/prime). Batch 6 pools however are composed if 2 [Prime](https://docs.crabada.com/game-guide/crabadex/prime) and 1 [Bulk](https://docs.crabada.com/game-guide/crabadex/bulk). This change was because the cost of crabs had gone up and to do the same team would have been an even lower ROI.

| Batch      | TUS @ Crab purchase | Pool Size | Current Expected ROI
| ----------- | ----------- | --- | --- |
| 1      |  $0.20       | $65000 | 1.4% (originally 1%) |
| 2      |  $0.22       | $70000 | 1.4% |
| 3      |  $0.16       | $55000 | 1.4% |
| 4      |  $0.16       | $55000 | 1.4% |
| 5      |  $0.08       | $37500 | 1.4% |
| 6      |  $0.10       | $42500 | 1.1% |

## Distributions

Distributions of TUS to NFT owners appears to start around 23:00 GMT.

## ROI

ROI is not based on the USDC.e deposited into a pool, but on the TUS that USDC.e bought. This has caused some confusion as participants of earlier batches saw reduced USD returns when the price of TUS fell in the weeks following those first batches.

Take Batch 1 for example, it was approximately 325,000 TUS ($65,000/0.20). 1% (inital ROI at launch) would have been 3,250 TUS/day. For every $100 (0.153% of pool), that would be ~5 TUS/day return.

This formula provides a rough estimate for what rewards you should expect. There is a [calculator located here](https://ipfs.io/ipfs/QmZwxEjRdpTRDkUT32fCkFBzZvAgrhmarHptebFFBykXPQ) that uses it to approximate the returns that should be seen.
```
(HuntPoolSize / TUSPriceAtCrabBuy / (HuntPoolSize/SharePrice) * (PoolROI/100) * (HuntPoolSize / SharePrice * (PercentOfPoolOwned/100)))
```

## CCC's fee/cut

While kinks are being ironed out and due to the decreased TUS price, CCC has waived their 15% cut/fee that would flow into the CCC treasury.

### Other considerations on returns

Mid March 2022, the CCC mining bots were updated with the ability to reinforce against looting raids from the tavern. This has had an impact on returns and is not reflected in the [Rewards](https://huntdefi.finance/rewards) page.

# Secondary Markets

Hunt NFT's can be sold on the secondary market on [Kalao](https://marketplace.kalao.io/collection/0x3b50d61ab8752a10df0ec588b7cd40efc4accf00). While an NFT is listed on this marketplace, you will not receive TUS. While it has not occured for a while, it is assumed that the Kalao contract would receive the TUS.

Generally given advice is to only sell if you need the cash and only buy if the cost is less than 100 days for ROI at current TUS price.

# Links

* [Hunt Defi](https://huntdefi.finance)
* [CCC](https://crosschaincapital.finance/)
* [NFT Market](https://marketplace.kalao.io/collection/0x3b50d61ab8752a10df0ec588b7cd40efc4accf00)
* [Hunt ROI calculator](https://ipfs.io/ipfs/QmZwxEjRdpTRDkUT32fCkFBzZvAgrhmarHptebFFBykXPQ)
* [TUS Price chart](https://dexscreener.com/avalanche/0x565d20bd591b00ead0c927e4b6d7dd8a33b0b319)
