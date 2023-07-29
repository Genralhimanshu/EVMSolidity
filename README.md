# EVMSolidity

# ASSESEMENT

This program show how to make tokens in remix.ethereum.org

# MyToken

MyToken is an Ethereum  mytoken contract that allows the contract owner to mint tokens to a provided address, and users to burn and transfer tokens.

# Features

- Mint tokens to a specified address by the contract owner.
- Burn tokens by any user.
- 
# DESCRIPTION

mytoken.sol fulfills the requirements for creating a contract with Solidity features used:

Public variables that store information about the coin. These variables are the following: tokenName, tokenAbbrv, and totalSupply. A public mapping variable named balances to map addresses to balances. The address is of the address data type, and the balance is of uint data type, or unsigned integer. Unsigned integers are integers that cannot have a negative value. There are three functions, mintToken, burnToken, and balance. mint and burn functions take two arguments, an address and a value and balance function take one arguments only address. The mintToken function increases the balance of the address by the value given, and increases the total supply. The burnToken function is the opposite: it decreases the balance of the address by the value given, and decreases the total supply.

# Usage

1. Compile the smart contract:

2. Deploy the contract on the local network:

3. Use Remix or any other Ethereum development tool to interact with the deployed contract on the local network.

# Author

Himanshu Pal

# License

This project is licensed under the MIT License - see the LICENSE file for details
