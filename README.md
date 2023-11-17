## MyToken (MGT) Contract
### Description
The MyToken (MGT) contract is an ERC20 token contract developed using the Solidity programming language. It provides basic functionalities for creating, minting, and burning tokens. The contract is named "MitongToken" (symbol: MGT) and follows the ERC20 token standard.

### Features
- **Token Creation:** The contract allows the creation of new MyToken tokens.
- **Ownership:** The contract has an "owner" variable, which is set to the address of the contract creator. Only the owner can mint new tokens.
- **Minting:** The owner can mint tokens and assign them to a specific address.
- **Burning:** Token holders can burn their own tokens, reducing their balance.
- **Balance Check:** The contract allows for checking the token balance of any address.
### Usage
To use the MyToken contract, follow these steps:

- Deploy the contract on the Ethereum blockchain.
- Set the owner address as desired.
- Call the mint function with the desired recipient address and token amount to create new tokens. Only the owner can call this function.
- Call the burn function with the desired amount to burn tokens from your own balance.
- Use the balanceOf function to check the token balance for a specific address.
### License
The MyToken contract is licensed under the MIT License.
