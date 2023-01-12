---
title: btc-dev
layout: default
---

* notes:
- private key security: multi-sig setup has some privacy downside(specially if it's a non-standard setup like 2-of-3 that most people use). 2-of-2 is the second most used (blockstream green, lightning).
For single-sig setup additional options include seedxor, shamir-secrets and passphrase but extra-cautious with exotic setups. 


#### cli:
- [regtest, commands](https://www.willianantunes.com/blog/2022/04/bitcoin-node-with-regtest-mode-using-docker/)
- [learning bitcoin from cli](https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line)

#### open-source payment solutions:
- [btcpay](https://btcpayserver.org/)
- [coinos](https://coinos.io)

#### misc:
- [blkdat files](https://learnmeabitcoin.com/technical/blkdat)
- [magic bytes](https://learnmeabitcoin.com/technical/magic-bytes)
- [python blockchain parser](https://github.com/alecalve/python-bitcoin-blockchain-parser)
- [esplora: blockchain explorer](https://github.com/Blockstream/esplora/blob/master/API.md)



#### pruned nodes/assumeutxo:
- [prune node](https://bitcoin.stackexchange.com/questions/92769/bitcoin-full-node-how-to-run-a-pruned-node-explaining-pruning)
- [assumeutxo](https://bitcoinops.org/en/topics/assumeutxo/)
- [assumeutxo vs pruned, read thread](https://bitcoin.stackexchange.com/questions/116030/skip-ibd-on-pruned-node/116106)
- trusted pruned snapshots: BTCPay [fastsync](https://docs.btcpayserver.org/Docker/fastsync/), [specter](https://prunednode.today/), [eznode](https://ezno.de/)