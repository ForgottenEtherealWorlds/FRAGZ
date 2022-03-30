
![enter image description here](https://i.imgur.com/GomkIzR.jpeg)

# Introduction

Forgotten Ethereal Worlds ("FEW") is an Ethereum-based NFT project centered around NFT trading and crypto discussion. Forgotten Ethereal Worlds has so far released two ERC721 tokens and one ERC20 token.

* Website: https://forgottenethereal.world/
* Twitter: https://twitter.com/Forgot3thWorlds
* OpenSea (ERC721 "Genesis") https://opensea.io/collection/forgotten-ethereal-worlds

This document holds details about the technical details and mechanisms ("tokenomics") of Forgotten Ethereal World's tokens:
* FRAGZ (ERC20)
* Genesis (ERC721)
* Genesis Prime (ERC721)

# Forgotten Ethereal Worlds

->>>>> **Who are we, what is it, and why will it grow in value? Why does an Exchange want to list us and FRAGZ?"**

* Partnerships
* Quality
* Mint speed
* Floor price
* Success metrics
* Community engagement
* Twitter engagement
* Twitter followers
* Social media numbers
* Etc

# FRAGZ token generation
The FRAGZ (ERC20) token is generated by the continued ownership ("passive staking") of either of two tokens (ERC721) in an Ethereum account:
* Genesis
* Genesis Prime

ERC721 token ownership is considered from the time of creation ("mint") until present for the purposes of calculating total yield of FRAGZ. Minting of FRAGZ tokens may be done at any time. 

Unminted FRAGZ are tied to the ownership of the ERC721 tokens. Any unminted FRAGZ will be transferred with the token upon transfer of ownership of either ERC721 token.

FRAGZ will continue to be generated for approximately 5 years, specifically from time of the mint of an ERC721 token to **2027-01-30** (1801317960 unix). For more details, see section [Deflationary mechanisms.](#deflationary-mechanisms)


# Token info

Values are taken as of date **2022-03-26**

## FRAGZ

* **Type:** ERC20
* **Network**: Ethereum
* **Supply**: 1,296,130.875 (after 5 years)
* **Contract** (address): 0x445ba08dad96a3d03ce8ffcbb1f246397f971b8c
* **Contract** (deployed): https://etherscan.io/address/0x445ba08dad96a3d03ce8ffcbb1f246397f971b8c
* **Contract** (code): https://github.com/ForgottenEtherealWorlds/FRAGZ/tree/main/contracts/fragz
* **Circulating supply:** ~30,000
* **Supply (total yield):** 38,925
* **Supply cap:** 1,296,130.875
* **Market cap:** $381,653.91


## Genesis 
* **Type:** ERC721
* **Network:** Ethereum
* **Mint date:** 2022-01-30
* **Contract** (address): 0x590bbc539d4fa56afaf030378577dd8bc6b6f0fc
* **Contract** (deployed): https://etherscan.io/address/0x590bbc539d4fa56afaf030378577dd8bc6b6f0fc
* **Contract** (code): https://github.com/ForgottenEtherealWorlds/FRAGZ/tree/main/contracts/genesisFEW
* **OpenSea:** https://opensea.io/collection/forgotten-ethereal-worlds
* **Yield:** 2 FRAGZ per day (86400 unix time)
* **Supply:** 345 (fully claimed)
* **Market cap:** $8,224,813.8

## Genesis Prime 
* **Type:** ERC721
* **Network:** Ethereum
* **Mint date:** 2022-02-23
* **Contract** (address): 0x04d65881d18b12109611df239edae21129fee73f
* **Contract** (deployed): https://etherscan.io/address/0x04d65881d18b12109611df239edae21129fee73f
* **Contract** (code): https://github.com/ForgottenEtherealWorlds/FRAGZ/tree/main/contracts/primeFEW
* **OpenSea:** https://opensea.io/collection/forgotten-ethereal-worlds-specials
* **Yield:** 4 FRAGZ per day (86400 unix time)
* **Supply:** 5 (fully claimed)
* **Market cap:** $2,836,964.76

# FRAGZ supply

Notes: 
* Calculations were made in the morning of the date **2022-03-26** which affects the number of days below (.5 and .2125).
* Genesis Prime was launched after Genesis and consequently Genesis Prime has been yielding FRAGZ for a shorter amount of time.
* As previously stated, FRAGZ token generation will proceed from time of mint until the current date reaches **2027-01-30** (1801317960 unix). We will call this the "end date" below.
* Both Genesis and Genesis Prime were fully minted practically immediately upon contract launch, so for the purposes of calculation mint date of all tokens the day of contract deployment may be used to approximately summarize all token yield.

**Genesis** 
* Supply: 345
* FRAGZ yield per day: 2
* Days since first mint: 55.5
* **FRAGZ yield to date:** 345 * 2 * 55.5 = **38,295**
* Days from mint to end date: 1826.2125
* **FRAGZ yield (max):** 345 * 2 * 1826.2125 = **1,260,086.625**

**Genesis Prime**
*  Supply: 5
* FRAGZ yield per day: 4
*  Days since first mint: 31.5
*  **FRAGZ yielded to date:** 5 * 4 * 31.5 = **630**
*  Days from mint to end date: 1802.2125
*  **FRAGZ yield (max):** 5 * 4 * 1802.2125 = **36,044.25**

**FRAGZ**
*  **Supply to date:** 38295 + 630 = **38,925**
*  **Supply cap:** 1260086.625 + 36 044.25 = **1,296,130.875**

# Deflationary mechanisms

Generation of FRAGZ by Genesis and Genesis Prime will stop at 2027-01-30 (1801317960 unix) and cannot be generated by any other token nor any other mechanism. The purpose of a set date for the end of supply generation is to provide a defined max value of all tokens in existence in order to establish it's valuation. 

The total active and max supply of FRAGZ fluctuate over time due to being subject to current and future destruction ("burning") mechanisms. These will function as deflationary mechanisms. We will also continuously develop more deflationary mechanisms over time in order to continuously promote a rise of price, continued interest in trading and increasing the value of the FRAGZ token. However, we will closely monitor the rate of burning in relationship to creation for the purpose of reducing price volatility and promote an orderly market.

Notably, our next ERC721 token (called "Paradigm") will have a supply of 5000 and many of it's mechanisms will require the burning of FRAGZ. This concept will also apply for future ERC721 tokens released. This will sustain a high incentive to purchase and trade FRAGZ as long-term investment and enabling participation in future utility.

Current burning mechanisms:
* Changing the name of an ERC721 token.
* Changing the description of an ERC721 token.
* Investing in ERC721 tokens to change their appearance and rarity traits.
* Claim right to mint of an upcoming ERC721 token ("Paradigm") from Forgotten Ethereal Worlds.
* Investing in an ERC721 token to unlock **future burning mechanisms**.

Future burning mechanisms: 
* Claim right to future ERC721 token creation from Forgotten Ethereal Worlds.
* Investing in future ERC721 tokens from Forgotten Ethereal Worlds to change their appearance, traits and unlock burning mechanisms tied to that token.
* Claiming membership of partnership collaborations between Forgotten Ethereal Worlds and other NFT projects.
* Creation of blockchain assets tied to an immersive 3D experience (metaverse) by Forgotten Ethereal Worlds.
* Participation in a blockchain-based game created by Forgotten Ethereal Worlds.
* Other mechanisms not yet outlined in planning.

# Liquidity pool

The FRAGZ liquidity pool is currently available on Dextools: https://www.dextools.io/app/ether/pair-explorer/0x976626dbe6ae90fbd7cba25e44633163d3d2ee32
