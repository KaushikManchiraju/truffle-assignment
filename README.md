## Smart Contract with Truffle

In this assignment, the following steps were followed :

1. Installing, Downloading all the dependencies via npm for Truffle following - Tutorial 1
- > truffle init no longer creates a scaffolding which includes initial Migrations files so instead I used truffle unbox
- > Developed a basic Helloworld contract and compiled it and deployed it on the dev net on my local machine.
- > Used constructors and included checks which would check if the message has minimum ether value and also to check if the owner is the sender

2. Deploying and Managing Migrations - Tutorial 2
-> Developed another smart contract called HelloworldPermanent with a static message. 
-> Deployed both contracts in the same build script using arrow functions in the dev net


3. Developing unit test cases - Tutorial 3
-> Developed 2 unit test cases - one asserts if the message is correct and the other checks if the 1st account is the owner

4. Deployed an example smart contract in the Testnet by following - https://docs.chainstack.com/tutorials/ethereum/asset-tokenization-with-embark
-> Speedy nodes are no longer supported by Moralis
