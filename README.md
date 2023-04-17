# hardhat-interact

_Call functions of smart contracts with no code_

## What

This plugin will help you avoid writing boilerplate code that call smart contracts functions.

## Installation

```bash
npm install @rami-majdoub/hardhat-interact
```

Import the plugin in your `hardhat.config.js`:

```js
require("@rami-majdoub/hardhat-interact");
```

Or if you are using TypeScript, in your `hardhat.config.ts`:

```ts
import "@rami-majdoub/hardhat-interact";
```


## Required plugins

- [@nomiclabs/hardhat-web3](https://github.com/nomiclabs/hardhat/tree/master/packages/hardhat-web3)

## Tasks

This plugin adds the _interacat_ task to Hardhat:

```
Usage: hardhat [GLOBAL OPTIONS] interact [--account-id <INT>] [--contract-address <STRING>]

OPTIONS:

  --account-id      	Id of the account to connect with, default: Account #0 (default: 0)
  --contract-address	Address of the contract 

interact: Calls a function of a contract

For global options help run: hardhat help
```
