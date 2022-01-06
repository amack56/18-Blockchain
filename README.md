# 18-Blockchain

## Environment Set Up

There is no .env file or dependencies

## Get Flags

Please use the following flags to initialize the nodes:

./geth --datadir node1 --unlock "0x6005cd59c9514961967E4A7C0fCb67add3d05e18" --mine --rpc --allow-insecure-unlock

./geth --datadir node2 --unlock "0x989931973cCF44B7f6f68061F2f0E4C38b089354" --mine --port 30304 --bootnodes "enode://f1e35a7192707ba13e118f279ccc238841e4eeccebb21f51e2d2e89141cd3f60cb0bc7efa11c55ab5e53f6442ac14f9fd6dde799113607a0a28068d1f3bed28d@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock

# Passwords, ChainID, etc

The password for both nodes is "pass"

The chainID is: 35442

The port is http://127.0.0.1:8545

To connect to mycrypto create a custom network named alexnet4 with the information above. A test transaction can be found in the Screenshots folder, titled "transaction_status_mycrypto"