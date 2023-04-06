# Python focused web3 project boilerplate

## Objectives

This repository is aimed to be a base for any web3 project using mainly Python.
I did include node packages because I'm using Solhint and Prettier.

## This project is setup to use the following packages:

* [Python] Brownie as a Solidity development framework
* [Python] Web3.py as a backend integration with the blockchain
* [Python] Slither as a Solidity security analyser
* [Node.js] Solhint as a Solidity linter
* [Node.js] Prettier as a Solidity formatter

* [Python] Pylint as a Python linter
* [Python] Black as a Python formatter

## Continuous Integration

This project uses github actions to run continuous integration for Solidity and Python
code. Please reffer to .github/workflows/main.yml for the script.

The CI will run the following:

* Install Node and Python dependencies
* Run Solidity linter and prettier
* Compile contracts and run tests in Brownie
* Run Slither
* Run Python linter and prettier

## Config files

All config files are served with default values. Refer to each package documentation to
tailor those files to your needs