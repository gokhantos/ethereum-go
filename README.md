## Go Ethereum

Official Golang implementation of the Ethereum protocol.

### Adding NewField to Ethereum Transactions

* NewField added to transaction types
* new_field_tx created in core/types
* New block called Paris block added in config file
* Paris block added to chain rules
* New transaction signer called paris signer created (same as london signer)
* NewField added to message struct in transaction.go
* NewField added to transaction args
* NewField added to state transition
* NewField added to smart contracts (DeployContract, Call vs)


### TODOS
* Update hardcoded binaries of smart contracts in simulated_test, oracle_test, bind_test,base_test

### How to run
[How to create an ethereum private network](https://collincusce.medium.com/using-puppeth-to-manually-create-an-ethereum-proof-of-authority-clique-network-on-aws-ae0d7c906cce)
* You should use puppeth to create a private ethereum network

`make all`

`./go-ethereum/build/bin/puppeth`

* Proof of Authority (Clique) should be chosen
* Bootnode should be created so that other nodes can join the network
* Sealer node should be created (for mining)