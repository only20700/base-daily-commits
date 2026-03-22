# base-daily-commits
Daily commits while building on Base ecosystem
Day 1: Started building on Base ecosystem
Day 2: Testing contracts
Day 3: Interacting with dApps
Day 4: Reading docs
Day 5: Writing notes
README.md
# Base Daily Activity

This repository tracks my daily building activity on Base.

## Goals
- Deploy contracts
- Test scripts
- Document learning
- Stay consistent

## Structure
- contracts/ → smart contracts
- scripts/ → deploy scripts
- logs/ → daily logs
- notes/ → ideas
contracts/SimpleStorage.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleStorage {
    uint256 private value;

    function set(uint256 _value) public {
        value = _value;
    }

    function get() public view returns (uint256) {
        return value;
    }
}
scripts/deploy.js
async function main() {
  console.log("Deploying contract...");
}

main();
logs/day-01.md
# Day 01

- Created repository
- Added simple contract
- Prepared deploy script
