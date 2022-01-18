# wallet
A command-line EVM compatible wallet.

## Account management

To add a new account 

    wallet account add ethmain 0x57B6611dE36d8C093cA1c01E054dB301d8e092F5
    wallet account add -network ethereum-mainnet ethmain 0x57B6611dE36d8C093cA1c01E054dB301d8e092F5

To remove an account

    wallet account remove ethmain
    
To get an account balance

    wallet account balance ethmain
    
To get all account balances

    wallet balances
