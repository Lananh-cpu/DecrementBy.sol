# DecrementBy.sol
DecrementBy.sol
pragma solidity ^0.8.20;
contract DecrementBy {
    uint public value;

    function decrease(uint x) public {
        value -= x;
    }
}
