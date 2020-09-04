# Solidity Greeting

greeting.sol is a smart contract that aims to present some features of the Solidity language in the context of a university exercise.

## Implementing the code with a Solidity smart contract

1. Open [Remix IDE](https://remix.ethereum.org/);
2. Create a new file greeting.sol and paste into it the script contained in this repository;
3. Compile greeting.sol;
4. Deploy greeting.sol locally;
5. Try to say Hello (sayHello()) to the smart contract.
6. Try to set a greeting message (setGreeting()) to everyone else accessing your smart contract.
7. Try to say Hello (sayHello()) to the smart contract with another account.

Now try using the Ropsten public test network (team up with someone else)!

8. Install [Metamask](https://metamask.io/) and follow the wizard;
9. Connect to the Ropsten network;
10. Withdraw funds for free from the Ropsten faucet;
11. As a Remix IDE environment select Injected Web3, so as to interact with Ropsten;
12. (Only one of you) deploy greeting.sol;
13. (The other person) invoke (at address) greeting.sol from the other instance of Remix IDE using the smart contract address;
14. Try to say Hello (sayHello()) to the smart contract.
15. Try to set a greeting message (setGreeting()) to everyone else accessing your smart contract.
16. Try to say Hello (sayHello()) to the smart contract with another account.

## Exercise part

We have been asked by the marketing department to provide analytics and benchmarkings see how popular our new smart contact is.
They want a way to count the number of times other people (not the owner) clicks on our function: sayHello()

