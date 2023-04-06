# Python Web3 Project Boilerplate

## Objective

The Python Web3 Project Boilerplate is a ready-to-use base for developing web3 projects using mainly Python. It also includes Node.js packages for Solidity linting and formatting.

## Packages

This project includes the following packages:

* [Python] Brownie as a Solidity development framework
* [Python] Web3.py as a backend integration with the blockchain
* [Python] Slither as a Solidity security analyzer
* [Node.js] Solhint as a Solidity linter
* [Node.js] Prettier as a Solidity formatter
* [Python] Pylint as a Python linter
* [Python] Black as a Python formatter

## Continuous Integration

This project uses GitHub Actions to run continuous integration for Solidity and Python code. Please refer to `.github/workflows/main.yml` for the script. The CI performs the following actions:

* Installs Node.js and Python dependencies
* Runs Solidity linter and formatter
* Compiles contracts and runs tests in Brownie
* Runs Slither
* Runs Python linter and formatter

## Configuration Files

All configuration files have default values. Refer to each package's documentation to customize the files to your needs.

By using this boilerplate, you can easily get started on developing your own web3 project with Python. It provides a solid foundation with necessary tools and configurations, allowing you to focus on developing your application logic.
