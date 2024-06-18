# ETH-AVAX-Module-1: Smart Contract Project

# Overview
This repository contains the documents relevant to accomplishing my project for ETH + AVAX Proof: Intermediate EVM, Module 1. It contains a Solidity smart contract, SmartContract.sol, which implements the require(), assert(), and revert() statements. The require() statement functions as an input validator. Meanwhile, the assert() statement is used to detect internal errors, whereas the revert() statement is utilized to revert or undo state changes.

Generally, SmartContract.sol is a smart contract for a basic calculator. It allows users to add, subtract, multiply, and divide two numbers. SmartContract.sol provides the following features:

- a function getSum() that accepts two unsigned integers and computes for their sum.
- a function getDifference() that accepts two unsigned integers and computes for their difference. When the subtrahend > minuend, it reverts to the initial state.
- a function getProduct() that accepts two unsigned integers and calculates their product. It also uses the assert() statement to check for multiplication overflow.
- a function getQuotient() that accepts two unsigned integers and gets their quotient. This function requires that the divisor is not equal to zero, lest an error message will prompt.

# Pre-requisites
To effectively run SmartContract.sol, one must have the following:
- Remix IDE or any Solidity Compiler.

# Usage
To execute the SmartContract.sol, one may use Remix IDE. The following statements provide a step-by-step guide on how to properly run and interact with the project using Remix IDE.

1. Open Remix IDE
2. Create a new file entitled SmartContract.sol, then copy and paste the provided code.
3. On the left sidebar, select Solidity Compiler -> Compile SmartContract.sol. [NOTE: Compiler version should be at least 0.8.18].
4. On the left sidebar, select Deploy & Run Transactions -> Deploy. Set the environment that you prefer, yet I used the default one.
5. Interact with the contract by entering inputs across the getSum(), getDifference(), getProduct(), and getQuotient(). Inputs must be integers separated by commas. (Ex: 2,3).  
