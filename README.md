# Deploy smart contract on a public test network (Rinkeby) 
## Transaction ID
0x308684236d2b62a102ef3e16f08216fffbb6334e681bec8e58915c853e721ba7
## Contract address
0xDc16DE29A877BE80E5d5B2199e3AE779c28A45a9 <br/>
https://rinkeby.etherscan.io/address/0xDc16DE29A877BE80E5d5B2199e3AE779c28A45a9
# UML
## Activity Diagram
![Activity Diagram](./diagrams/ActivityDiagram.png)
## Sequence Diagram
![Sequence Diagram](./diagrams/SequenceDiagram.png)
## State Diagram
![State Diagram](./diagrams/StateDiagram.png)
## Class Diagram
![Class Diagram](./diagrams/ClassDiagram.png)

# Libraries
## truffle-hdwallet-provider: ^1.0.17

# IPFS
Not used IPFS in this project
    
# General write-up
### Explain and motivate the problem you’re trying to solve.
The problem I am trying to solve is to provide a full supply chain tracking item based on blockchain technology.
It adopts blockchain technology to leverage and utilize its properties such as data transparency and world-wide accessibility.
### Provide concrete examples of the problem.
The concrete example is end-to-end supply chain of coffee products from farmers to consumer.
### Describe the architecture of your solution.
The architecture is comprised of two main components : smart contracts based on Ethereum blockchain and front-end app for users to interact with.
### Describe the implementation of that architecture.
The detail implementation is described as below :
## Blockchain component
They are three types of smart contracts. SupplyChain contract plays main role which connects to others Role contract.
Role contracts like FarmerRole, ConsumerRole control what users could do based on their staged roles in the supply chain.
The last one is the Ownnable contract to manage contract ownership itself. 
### Evaluate your implementation architecture, by showing how it addresses several concrete problem examples, and/or with actual experiments.
The first use case of SupplyChain contract is to provide a Farmer a tool to harvest their item (coffee) via interacting by our Front-end App.
Once farmer call a transaction to harvest and declare their product information. It started off first stage of entire supply chain and keep track that item to the consumer end.
By which we could fetch and examine product information and status whenever we would like to.
### Draw thoughtful conclusions from your work.
My conclusion is to upgrade this application beyond learning project so that I could launch it as a real-world application to help my farmer in my own countries.
I am grateful and do not forget to thank Udacity giving me chance to practise my skill on this idea.
    
