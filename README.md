##Overview
This contract demonstrates basic functionalities and best practices in Solidity programming.

Functions
setValue(uint256 newValue): Sets a new value (greater than zero).
resetValue(): Resets the value to zero (only callable by the owner).
testAssert(): Checks that the value is never negative.
safeDivide(uint256 a, uint256 b): Safely divides two numbers (handles division by zero).
Deployment
Compile using Solidity v0.8.0+. Deploy on Ethereum network.

Usage
Interact with the contract:

Set and reset values.
Ensure safe division and value assertions.
Security
Owner-only access for critical functions.
Handle edge cases like division by zero.
