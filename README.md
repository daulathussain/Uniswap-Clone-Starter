
# Building and Deploying a Uniswap Exchange Clone for DeFi

Enter the world of decentralized finance (DeFi) with our Uniswap Exchange clone, UniClone. This project focuses on replicating the functionalities of the popular decentralized exchange Uniswap, providing users with a seamless and efficient platform for swapping tokens, providing liquidity, and earning fees.

UniClone leverages smart contracts and blockchain technology to enable trustless and permissionless token swaps directly from users' wallets. By replicating Uniswap's automated market maker (AMM) mechanism, our clone ensures liquidity for all listed tokens and allows users to trade without the need for traditional order books or centralized intermediaries.

## Project Overview

![alt text](https://www.daulathussain.com/wp-content/uploads/2023/04/Uniswap-clone.jpg)

## Instruction

Kindly follow the following Instructions to run the project in your system and install the necessary requirements


- [Final Source Code](https://www.theblockchaincoders.com/sourceCode/build-uniswap-dapp-project-source-code)

#### Setup Video
- [Final Code Setup video](https://youtu.be/NAuuGa_7oro?si=hHXzjfPR_mPQx78p)

```https://code.visualstudio.com/download
  WATCH: Setup & Demo Of Project
```

#### Install Vs Code Editor

```https://code.visualstudio.com/download
  GET: VsCode Editor
```

#### NodeJs & NPM Version

```https://nodejs.org/en/download
  NodeJs: v18.12.1
  NPM: 8.19.2
```

#### Clone Starter File

```https://github.com/daulathussain/Airdrop-Crypto-Starter-File
  GET: Project Starter File Download
```


All you need to follow the complete project and follow the instructions which are explained in the tutorial by Daulat

## Final Code Instruction

If you download the final source code then you can follow the following instructions to run the Dapp successfully

#### Setup Video

```https://code.visualstudio.com/download
  WATCH: Setup & Demo Of Project
```

#### Final Source Code

```https://www.theblockchaincoders.com/SourceCode
  Download the Final Source Code
```

#### Install Vs Code Editor

```https://code.visualstudio.com/download
  GET: VsCode Editor
```

#### NodeJs & NPM Version

```https://nodejs.org/en/download
  NodeJs: v18.12.1
  NPM: 8.19.2
```


#### Test Faucets

Alchemy will provide you with some free test faucets which you can transfer to your wallet address for deploying the contract

```https://www.alchemy.com/faucets
  Get: Free Test Faucets
```

#### RemixID

We are using RemixID for deploying the contract and generation of the ABI in the project, but you can use any other tools like Hardhat, etc.

```https://remix-project.org
  OPEN: RemixID
```

#### Polygon Mumbai

```https://mumbai.polygonscan.com/
  OPEN: Polygon Mumbai
```

## Important Links

- [Get Pro Blockchain Developer Course](https://www.theblockchaincoders.com/pro-nft-marketplace)
- [Support Creator](https://bit.ly/Support-Creator)
- [All Projects Source Code](https://www.theblockchaincoders.com/SourceCode)


## Authors

- [@theblockchaincoders.com](https://www.theblockchaincoders.com/)
- [@consultancy](https://www.theblockchaincoders.com/consultancy)
- [@youtube](https://www.youtube.com/@daulathussain)


# IMPORTANT INFO

# Address

MAINNEXT TOKEN ADDRESS

"0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48",
"0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2",
"0xdAC17F958D2ee523a2206206994597C13D831ec7",
"0xB8c77482e45F1F44dE1745F52C74426C631bDD52",
"0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0",
"0x6B175474E89094C44Da98b954EedeAC495271d0F",
"0x95aD61b0a150d79219dCF64E1E6Cc01f0B64C4cE",
"0x4278C5d322aB92F1D876Dd7Bd9b44d1748b88af2",
"0x0D92d35D311E54aB8EEA0394d7E773Fc5144491a",
"0x24EcC5E6EaA700368B8FAC259d3fBD045f695A08",

ISwapRouter(0xE592427A0AEce92De3Edee1F18E0157C05861564);

TEST

const DAI = "0x6B175474E89094C44Da98b954EedeAC495271d0F";
const USDC = "0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48";
const DAI_WHALE = "0x97f991971a37D4Ca58064e6a98FC563F03A71E5c";
const USDC_WHALE = "0x97f991971a37D4Ca58064e6a98FC563F03A71E5c";

const WETH9 = "0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2";

const qutorAddress = "0xb27308f9F90D607463bb33eA1BeBb41C27CE5AB6";

ETHERSCAN URL: `https://api.etherscan.io/api?module=contract&action=getabi&address=${address}&apikey=${ETHERSCAN_API_KEY}`;

V3_SWAP_ROUTER_ADDRESS = "0x68b3465833fb72A70ecDF485E0e4C7bD8665Fc45";

const name0 = "Wrapped Ether";
const symbol0 = "WETH";
const decimals0 = 18;
const address0 = "0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2";

const name1 = "DAI";
const symbol1 = "DAI";
const decimals1 = 18;
const address1 = "0x6B175474E89094C44Da98b954EedeAC495271d0F";

# //SECOND PACKAGE.JSON FILE

{
"name": "uniswapclone",
"version": "0.1.0",
"private": true,
"scripts": {
"dev": "next dev",
"build": "next build",
"start": "next start",
"lint": "next lint"
},
"dependencies": {
"axios": "^1.2.1",
"ethers": "^5.7.2",
"next": "13.0.3",
"react": "18.2.0",
"react-dom": "18.2.0",
"web3modal": "^1.9.9",
"@nomicfoundation/hardhat-chai-matchers": "^1.0.6",
"@nomicfoundation/hardhat-network-helpers": "^1.0.8",
"@uniswap/smart-order-router": "^2.5.30",
"@nomicfoundation/hardhat-toolbox": "^2.0.2",
"@nomiclabs/hardhat-ethers": "^2.2.3",
"@nomiclabs/hardhat-etherscan": "^3.1.7",
"@openzeppelin/contracts": "^4.8.3",
"@typechain/ethers-v5": "^10.2.1",
"@typechain/hardhat": "^6.1.6",
"@types/chai": "^4.3.5",
"@types/mocha": "^10.0.1",
"@uniswap/v3-periphery": "^1.4.3",
"@uniswap/v3-sdk": "^3.9.0",
"bignumber.js": "^9.1.1",
"chai": "^4.3.7",
"dotenv": "^16.0.3",
"hardhat": "^2.14.0",
"hardhat-gas-reporter": "^1.0.9",
"solidity-coverage": "^0.8.2",
"ts-node": "^10.9.1",
"typechain": "^8.1.1",
"typescript": "^5.0.4"
}
}




