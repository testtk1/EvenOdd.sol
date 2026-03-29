# EvenOdd.sol
Deploy a contract on Base EvenOdd.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract EvenOdd {
    function isEven(uint x) public pure returns (bool) {
        return x % 2 == 0;
    }

    function isOdd(uint x) public pure returns (bool) {
        return x % 2 != 0;
    }
}
