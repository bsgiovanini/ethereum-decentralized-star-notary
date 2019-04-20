# Project 5: Decentralized Star Notary

Project created as an assignment for Udacity BlockChain Developer Nanodegree Program - Project 5.

It was designed using these core technologies:

```
Truffle v5.0.12 (core: 5.0.12)
Solidity v0.5.0 (solc-js)
Node v11.6.0
Web3.js v1.0.0-beta.37
OpenZeppelin v2.1.2
Truffle-hdwallet-provider v1.0.2
```

The contract generated was deployed in Rinkeby ethereum network under the Contract address [0x7616EC697f3fed50b8e1d51a27f98F340dD3BD17](https://rinkeby.etherscan.io/address/0x7616ec697f3fed50b8e1d51a27f98f340dd3bd17)

## Requirements

Plugin Metamask up and running in Chrome pointing to local truffle node

```
localhost:9545
```

## Instructions for testing

For starting the development console, run:

```
truffle develop
```

For compiling the contract, inside the development console, run:

```
compile
```

For migrating the contract to the locally running Ethereum network, inside the development console, run:

```
migrate --reset
```

For running unit tests the contract, inside the development console, run:

```
test
```

For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:

```
cd app

npm run dev
```

And it will be available at the Url address

```
http://localhost:8080
```
