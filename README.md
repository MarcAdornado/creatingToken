**Description**

This code defines a simple smart contract called MyToken that creates a cryptocurrency-like token on the Ethereum blockchain. It allows users to mint and burn tokens, and tracks balances across addresses. 
The contract includes functionality to increase (mint) and decrease (burn) the total token supply, with certain checks to ensure security during token burning.


**Executing program**

Ensure you have a compatible Ethereum development environment set up.
Copy the provided Solidity code into your preferred development environment.




**How to Run:**

Compile and deploy the contract on an Ethereum network (In the remix.ethereum.org).
Use the following commands for minting and burning tokens.

**Mint Function:**

To mint tokens to an address, use the mint function.
mint(address _address, uint _value)
_address: The recipient's address.
_value: The number of tokens to mint.

**Burn Function:**

To burn tokens from an address, use the burn function. Ensure the address has enough tokens to burn.
burn(address _address, uint _value)
_address: The address whose tokens will be burned.
_value: The number of tokens to burn.


**Author**

Marc Denzyl C. Adornado

202110010@fit.edu.ph


**License**

This project is licensed under the MIT License - see LICENSE.md for details

