This is a Metacrafters Final Project after completion of "ETH PROOF: Beginner EVM Course".

Explaination of the above code:

=> Features
  1.Token Details: Public variables to store token name, abbreviation, and total supply.
  2.Balance Mapping: A mapping of addresses to balances.
  3.Mint Function: Function to mint new tokens.
  4.Burn Function: Function to burn existing tokens.
  
=> Contract Details
-> Public Variables
  1.string public tokenName: The name of the token. (Example: "CRAFTERS")
  2.string public tokenAbbr: The abbreviation of the token. (Example: "CRAFT")
  3.uint public totalSupply: The total supply of the token.
-> Mappings
  1.mapping(address => uint) public balances: A mapping that stores the balance of each address.
-> Functions
  1.Mint
  "function mint(address _address, uint _value) public"
  This function Increases the total supply of the token and the balance of the specified address.
  Parameters:
  _address: The address to which the tokens will be minted.
  _value: The number of tokens to be minted.
  
  2.Burn
  "function burn(address _address, uint _value) public"
  This function Decreases the total supply of the token and the balance of the specified address.
  Parameters:
  _address: The address from which the tokens will be burned.
  _value: The number of tokens to be burned.
  Condition: The function will check if the balance of the specified address is greater than or equal to the number of tokens to be burned. If this condition is True then                only the tokens will be burned.


  --HARSH KUMAR YADAV
