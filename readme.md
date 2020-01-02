# dApp example with React and Drizzle

This is a very simple dApps example which using Truffle, Solidity, Drizzle and React.

**_DEMO:_**

<img src="./client/src/resource/200102ScreenShot.jpg" width="60%">

## Environment

```bash
$ node -v
v10.16.2
$ yarn -v
v1.19.2
```

- Truffle: `v5.1.6 (core: 5.1.6)`
- Solidity: `v0.5.12 (solc-js)`
- Web3.js: `v1.2.1`
- React: `16.12.0`

## Dependencies

### For Application

- [drizzle, drizzle-react, drizzle-react-components](https://github.com/trufflesuite/drizzle)
  - Reactive Ethereum dapp UI suite (Required Node -v 10.16.2 to install `drizzle` )

### For Development

- [Truffle](https://github.com/trufflesuite/truffle)
  - A tool for developing smart contracts. Crafted with the finest cacaos.
- [Ganache](https://www.trufflesuite.com/ganache)
  - Quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates.
- [MetaMask](https://metamask.io/)
  - MetaMask allows you to run Ethereum dApps right in your browser without running a full Ethereum node.

## How To Use

1. Run the Ganache
2. Change the MetaMask RPC SERVER to `HTTP://127.0.0.1:7545`

```zsh
$ truffle compile
$ truffle migrate
$ cd client
$ yarn
$ yarn start
```
