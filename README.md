# Crypto Star DAPP

- Token Address: 0x2256df7fd6a6da2e222bd9bbf3344ff8dd97eb8b ([Contract deployed in Rinkeby](https://rinkeby.etherscan.io/address/0x2256df7fd6a6da2e222bd9bbf3344ff8dd97eb8b))
- Token Name: The Pupi Stars
- Token Symbol: PUPI
- Truffle: v5.3.0
- truffle-hdwallet-provider-1.0.2
- openzeppelin-solidity-2.1.2

## Truffle Setup

1. Clone the repo
1. Go to the folder
1. Install `npm install truffle -g`
1. Install `npm install --save truffle-hdwallet-provider`
1. Install `npm install --save openzeppelin-solidity`
1. Run `truffle develop`
1. Migrate contracts `migrate --reset`
1. Run `test` inside the truffle console

## Frontend Setup

1. Go to `app` folder
1. Install dependencies with `npm install`
1. Run local server `npm run dev`
1. Open `localhost:8080` in yout browser

## Deploy in Rinkeby

1. Run `truffle migrate --reset --network rinkeby`
