# SYNOPSIS
[![NPM Package](https://img.shields.io/npm/v/devp2p-dpt.svg?style=flat-square)](https://www.npmjs.org/package/devp2p-dpt)
[![Build Status](https://img.shields.io/travis/ethereumjs/node-devp2p-dpt.svg?branch=master&style=flat-square)](https://travis-ci.org/ethereumjs/node-devp2p-dpt)
[![Gitter](https://img.shields.io/gitter/room/ethereum/ethereumjs-lib.svg?style=flat-square)](https://gitter.im/ethereum/ethereumjs-lib) or #ethereumjs on freenode  

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)  
An node.js implementation of devp2p's Distrubuted Peer Table. A DPT is like DHT but just stores peering info.

# Installation

Because package uses [cryptocoinjs/secp256k1-node](https://github.com/cryptocoinjs/secp256k1-node) you need C++ compiler.

```
npm install devp2p-dpt
```

# Example

See examples in [examples/](examples/)

  - [bootstrap](examples/bootstrap.js)

# API

[API.md](API.md)

But don't hesitate check source code, it's always actual and gives much insight.

# Reference

- [RLPx Node Discovery Protocol](https://github.com/ethereum/go-ethereum/wiki/RLPx-----Node-Discovery-Protocol) (outdated)
- [Node discovery protocol](https://github.com/ethereum/wiki/wiki/Node-discovery-protocol)
- [RLPx: Cryptographic Network & Transport Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md)

# License

[MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/)
