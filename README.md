# Solidity Beginner Assessment
This project is for the Solidity Beginner Course that demonstrates how I created my own Token as my final assessment.
## Description
This program used Solidity as the programming language for constructing the smart contract on the Ethereum blockchain platform. This contract has a minting and burning function for the token.
## Getting Started
### Installing
* To run this program, Remix is used as a compiler and IDE to build the contract using Solidity. Follow the Remix website to begin: https://remix.ethereum.org/
* On the Remix website, create a new file (click on the "+" icon in the left-hand sidebar). Then, save the file with a .sol extension (e.g., myToken.sol). Copy and paste the following code into the file:

```javascript
pragma solidity 0.8.18;

contract MyToken {
    // public variables here

    // mapping variable here

    // mint function

    // burn function
}
```
### Executing program
* To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar, and then click on the "Compile myToken.sol" button.

* Once the code is compiled, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

* When the contract is deployed on the left-hand sidebar, copy the address from the 'Account' then paste it on the _address in the myToken mint function. Input a solid number on the _value (e.g. 500). Finally, click on the "transact" button to execute the function and retrieve the totalSupply and balances of token, which you can check by clicking on it.

* To use the burn tokens in the deployed contract, you can paste the same address in the myToken burn function and then input a solid number on the _value. Next is clicking on the "transact" button the execute the function and retrieve the totalSupply and balances of token, which will show the decreased number of the tokens you have.

## Authors

Michaella Sangalang
61903364@ntc.edu.ph

## License
This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
