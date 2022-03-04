# 20-22.win Token List for Ethereum, Binance Smart Chain (BSC) and Polygon (Matic) Mainnet

<p align="center"><img src="https://raw.githubusercontent.com/Uniswap/tokenlists-org/master/public/card.png"></p>

https://github.com/2022-win/2022win-token-list/blob/master/2022win-token-list.json <br>
*We are using this token-list to show tokens on the major DEXs (1inch, Uniswap, Sushiswap, Quickswap, Pancakeswap) on Polygon, BSC and Ethereum Chain*

Other token lists: https://tokenlists.org/

# Add your token in 2022win Token List 
## 1. Press on "Fork" in the top right corner, wait for process to complete.

```
git clone https://github.com/2022-win/2022win-token-list
```

## 2. Add your token image in folder "Assets"

```
https://github.com/2022-win/2022win-token-list/tree/master/assets 
```

### Image Requirements
File extension: png. Uppercase PNG is considered invalid.
File name：<contract_address>.png, all lowercase.
Dimension: 256 x 256 pixels (recommended) or 512 x 512 pixels.
Background: preferably transparent (should fit dark mode as well; deny logos need light border/background).
File size: maximum 100kB.  Tip: optimize image size, e.g. using simple drag-and-drop online service tinypng.

## 3.1 Add your token data in 2022win-token-list.json

Address contract must be ***checksummed***. Check or convert your address in checksummed address here: https://web3-tools.netlify.app/

```json
{
 "address": "0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82",
 "chainId": 56,
 "name": "Pancakeswap",
 "symbol": "CAKE",
 "tags": [],
 "decimals": 18,
 "logoURI": "https://raw.githubusercontent.com/2022-win/token-list/master/assets/0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82.png"
},
```
*Please use "chainId": 1 for Ethereum Mainnnet and "chainId": 137 for Polygon Mainnet and "chainId": 56 for BSC*

## 3.2 Tags

You can add any tag from the list below to your token data. You can use up to 3 tags.

```json
"tags": 
    {
      "defi": {
      "name": "DeFi Market",
      "description": "Decentralized Finance protocols"
    },
    "aavev2": {
      "name": "Aave V2",
      "description": "Aave interest bearing tokens"
    },
    "comp": {
      "name": "Compound",
      "description": "Compound protocol balance token"
    },
    "nft": {
      "name": "NFT",
      "description": "Non fungible token"
    },
    "indexes": {
      "name": "DeFi Indexes",
      "description": "Tokenized baskets of high quality DeFi projects"
    },
    "stable": {
      "name": "Stablecoin",
      "description": "Stablecoins may be pegged to a currency like the US dollar or to a commoditys price such as gold"
    },
    "dex": {
      "name": "DEX Tokens",
      "description": "Tokens from AMM protocols"
    },
    "wrap": {
      "name": "Wrapped",
      "description": "Wrapped tokens pegged to the value of cryptocurrency from another chain"
    },
    "eth2": {
      "name": "Eth 2 Staking",
      "description": "Eth 2 Staking Tokens"
    },
    "pools": {
      "name": "Pools",
      "description": "Earn trading fees by providing liquidity in a single transaction"
    },
    "stock": {
      "name": "Stock",
      "description": "Synthetic stocks by Mirror protocol"
    }
   },
```

## 3.3 Add your token to 20-22.win Decentralized Market Page + Create Token Page

To add your token on our market and create page for it, please fork our second token list https://github.com/2022-win/2022win-token-list and add your token there also.

## 4. Make a new PR (pull request)

```
git add -A
git commit -m “Add <token_name>”
git push origin <branch_name>
```

# 🔉 Social Media
[Telegram](https://t.me/win20_22) <br>
[Medium](https://20-22win.medium.com/) <br>

### [20-22.win](https://20-22.win/):
#### Platform
- [Market](https://20-22.win/#/market)
- [Swap](https://20-22.win/#/hyper-dex)

#### How To
- [Documentation and DeFi University](https://docs.2022-win/)
