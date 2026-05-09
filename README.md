# CountCalls.sol
CountCalls.sol
pragma solidity ^0.8.20;
contract CountCalls {
    uint public calls;

    function callMe() public {
        calls++;
    }
}
