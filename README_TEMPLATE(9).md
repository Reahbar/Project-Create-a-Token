# Project: Create a Token

This Solidity program is a simple "Token" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point of Token contract for those who are new to Solidity and want to get a feel for how it works.

## Description

This program is a simple contract of Token written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. This contract is made as per requirments which is defined inside the smart contract. This program have 3 State veribles which are: string,string, and uint with the value of TokenName, TokenAbbrv, and TotoalSupply. This contract is defined with mapping(address=>uint) and it have two functions mint and burn with if condition inside burn function. The function mint takes 2 inputs which is address _address and uint _value which works increases the total supply by that number and increases the balance of the address by that amount. The function burn works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address. Lastly burn function have a condition of if to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.  

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Token.sol). Copy and paste the following code into the file:

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
