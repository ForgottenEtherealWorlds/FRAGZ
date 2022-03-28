# Introduction

Forgotten Ethereal Worlds ("FEW") is an Ethereum-based project centered around NFT trading and crypto discussion. Forgotten Ethereal Worlds has so far released two ERC721 tokens and one ERC20 token.

* Website: https://forgottenethereal.world/
* Twitter: https://twitter.com/Forgot3thWorlds

This document holds details about the technical details and mechanisms ("tokenomics") of Forgotten Ethereal World's tokens:
* FRAGZ (ERC20)
* Genesis (ERC721)
* Genesis Prime (ERC721)

# FRAGZ token generation
The FRAGZ (ERC20) token is generated by the continued ownership ("passive staking") of either of two tokens (ERC721) in an Ethereum account:
* Genesis
* Genesis Prime

The time of ERC721 token ownership is considered from the time of mint until present for the purposes of calculating total yield of FRAGZ.
FRAGZ are tied to the token itself, consequently any unminted FRAGZ will be transferred with the token upon transfer of ownerning of either ERC721 token.

FRAGZ will continue to be generated for approximately 5 years, specifically from time of mint per individual token to **2027-01-30** (1801317960 unix).

# Token info

## Genesis 
* **Type:** ERC721
* **Network:** Ethereum
* **Supply:** 345 (fully minted)
* **Mint date:** 2022-01-30
* **Contract** (address): 0x590bbc539d4fa56afaf030378577dd8bc6b6f0fc
* **Contract** (deployed): https://etherscan.io/address/0x590bbc539d4fa56afaf030378577dd8bc6b6f0fc
* **Contract** (code):
* **Opensea:** https://opensea.io/collection/forgotten-ethereal-worlds
* **Yield:** 2 FRAGZ per day (86400 unix time)

## Genesis Prime 
* **Type:** ERC721
* **Network:** Ethereum
* **Supply:** 5 (fully minted)
* **Mint date:** 2022-02-23
* **Contract** (address): 0x04d65881d18b12109611df239edae21129fee73f
* **Contract** (deployed): https://etherscan.io/address/0x04d65881d18b12109611df239edae21129fee73f
* **Contract** (code):
* **OpenSea:** https://opensea.io/collection/forgotten-ethereal-worlds-specials
* **Yield:** 4 FRAGZ per day (86400 unix time)

## FRAGZ

* **Type:** ERC20
* **Network**: Ethereum
* **Supply**: 1 296 130.875 (after 5 years)
* **Contract** (address): 0x445ba08dad96a3d03ce8ffcbb1f246397f971b8c
* **Contract** (deployed): https://etherscan.io/address/0x445ba08dad96a3d03ce8ffcbb1f246397f971b8c
* **Contract** (code):

# FRAGZ supply


Calculations are based as of date **2022-03-26**. As previously stated, FRAGZ token generation will proceed from time of mint until **2027-01-30** which is a total of 1826.2125 days (based on time of contract deployment).

**Genesis** 
* Supply: 345
* FRAGZ yield per day: 2
* Days since mint: 55.5 
* **FRAGZ yield to date:** 345 * 2 * 55.5 = **38 295**
* **FRAGZ yield (max):** 345 * 2 * 1826.2125 = **1 260 086.625**

**Genesis Prime**
*  Supply: 5
* FRAGZ yield per day: 4
*  Days since mint: 31.5
*  **FRAGZ yielded to date:** 5 * 4 * 31.5 = **630**
*  **FRAGZ yield (max):** 5 * 4 * 1826.2125 = **36 044.25**

**FRAGZ**
*  **Yield to date:** 38295 + 630 = **38 925**
*  **Yield (max):** 1 260 086.625 + 36 044.25 = **1 296 130.875**

# Burn mechanisms

The total active and max supply of FRAGZ will fluctulate over time due to being subject to current and future burning mechanisms.

Todo

# Liquidity pool

The FRAGZ liquidity pool is currently available on Dextools: https://www.dextools.io/app/ether/pair-explorer/0x976626dbe6ae90fbd7cba25e44633163d3d2ee32

It may also be imported into Uniswap with the FRAGZ token contract address: 0x445ba08dad96a3d03ce8ffcbb1f246397f971b8c
