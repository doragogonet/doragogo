# doragogo
https://github.com/doragogonet/doragogo.git

# Ethereum Development with Go

> Human Resources BlockchainA  [doraGoGo](http://www.filcoin.jp/) Development with [Go](https://golang.org/) (golang)

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Mentioned in Awesome Go](https://awesome.re/mentioned-badge.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

## Online

[https://www.filecoin.jp](http://www.filecoin.jp)

## Help & Support

Contact us [#HELP](http://www.filecoin.jp/?page_id=617)

## RPC-API
[wiki](https://github.com/doragogonet/doragogo/wiki)

## Development

Install dependencies:

Apply for a node address and private key in the [contact form](http://www.filecoin.jp/?page_id=617)

Initialize:

```bash
doragogo  --datadir ./n0
```
Add a private key to the static-nodes.json and owner.node file Place owner.node file in datadir


*  Start then doaGoGo Node:

```bash
doragogo  --datadir ./n0 --syncmode "full"  --rpcport "8545" --rpc --rpcaddr "0.0.0.0"  --rpcapi "admin,do.shh" --shh --ws --wsport 8546 --wsaddr "0.0.0.0"  --rpccorsdomain "*" --allow-insecure-unlock --nodiscover --port 40400  --miner.etherbase "hode-address" --mine console
```

