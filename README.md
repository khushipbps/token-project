# Token Project

This Solidity program is a simple program that demonstrates the basic usage of functions and variables, and mappings. The purpose of this program is to apply the usage in this project.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a two functions which are used to balance of the addresses and totalSupply i.e `burn` functions is used to decrease `totalSupply` and balance of the given address only if having enough balance. `mint` function is used to increase the `totalSupply` and balance of the gievn address. We have more variable such as `tokenName`, `abbr` and a map `balances` to store balance of each address.

## Getting Started

### Pre-requisites
- Install solidity version 0.8.18;

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with error_handling.sol extension (e.g., HelloWorld.sol). Copy and paste the `tokenproject.sol` file into the file:


To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile error_handling.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "Module1" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the `mint`, `burn` functions and also check values in `tokenName`, `abbr`, `totalSupply`. Also using `balances`, you can check balance in a given address . Click on the "MyToken" contract in the left-hand sidebar. You can also check `totalSupply` by clicking on it.

## Authors

Khushi Kumari


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
