# sol-trace

Trace runtime failures for solidity

Inspired by 0x-monorepo https://github.com/0xProject/0x-monorepo/pull/705

### Installation

```
$ npm install --save sol-trace # or yarn add sol-trace
```

### Usage

Add following code in your truffle test cases:

```js
import { injectInTruffle } from "/Users/jdkanani/matic/sol-trace";
injectInTruffle(web3, artifacts);
```
