# Solidity Program:MyToken
This is a Solidity smart contract that implements a basic token called MyToken (META) with functionalities for minting and burning tokens.

#Requirements
1.The contract has public variables to store details about the token, including its name, 
  abbreviation, and total supply.
2.A mapping is used to track the token balances of different addresses (address => uint).
3.The contract includes a mint function that takes an address and a value as parameters. It 
  increases the total supply by the specified value and adds that value to the balance of the 
  sender's address.
4.The contract also includes a burn function that works in the opposite way of the mint function. 
  It takes an address and a value as parameters, deducts the value from the total supply, and 
  reduces the balance of the sender's address accordingly.
5.The burn function includes conditionals to ensure that the balance of the sender is greater 
  than or equal to the amount to be burned.


