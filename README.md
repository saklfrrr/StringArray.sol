# StringArray.sol
StringArray.sol
pragma solidity ^0.8.20;

contract StringArray {
    string[] public names;

    function addName(string memory _name) public {
        names.push(_name);
    }
}
