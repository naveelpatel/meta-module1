# ERC20 and Vault Contracts

## Overview

This repository contains an ERC20 token contract and a Vault contract for securely managing these tokens.

## Contracts

### ERC20 Contract

- **Standard ERC20 functions**: `totalSupply()`, `balanceOf(address)`, `transfer(address, uint256)`, `allowance(address, address)`, `approve(address, uint256)`, `transferFrom(address, address, uint256)`
- **Additional features**: `mint(address, uint256)`, `burn(uint256)`
- **Events**: `Transfer(address, address, uint256)`, `Approval(address, address, uint256)`

### Vault Contract

- **Core functions**: `deposit(uint256)`, `withdraw(uint256)`, `getBalance(address)`, `totalDeposits()`
- **Events**: `Deposited(address, uint256)`, `Withdrawn(address, uint256)`


## License

MIT License. See the [LICENSE](LICENSE) file for details.
