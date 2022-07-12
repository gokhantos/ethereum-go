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
* NewField added to smart contracts (DeployContract, Call)


### TODOS
* Update hardcoded binaries of smart contracts in simulated_test, oracle_test, bind_test,base_test