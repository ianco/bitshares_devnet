
# How to Run a DevNet

See https://dev.bitshares.works/en/master/development/testnets/private_testnet.html

1. Install and build bitshares core
2. Copy executables to this folder - cli_wallet and witness_node
3. Run the witness node (all other config should be checked into github):

```
./witness_node --data-dir data/my-blockprod --enable-stale-production --seed-nodes "[]"
```

The chain should start up and start produing blocks.

Now run through the wallet setup & configure ...  https://dev.bitshares.works/en/master/development/testnets/private_testnet.html#create-a-new-wallet





