# Election voting system using BlockChain
## Motivation 

Shortcomings of traditional system of voting :- <br>
•	Current voting system is **centralized**, which means there is only one point of centralization, where a **hacker** needs to attack to corrupt the system.  
•	Anyone with physical access to Electronic voting machine(EVM) can sabotage the machine and **tamper** the number of votes.  
•	It is not possible for voters to verify that individual votes were counted correctly. Thus there is **no transparency** in the current system.  
•	People should be allowed to vote from **any place in India**, irrespective of their home district.  
•	 The **time gap** between the election day and result declaration should be minimized.  


## Idea 
Our idea is to build a WebApp using Consortium Blockchain technology which would decentralize the whole voting system and make it secure and transparent by ruling out the possibility of tampering of votes as a unique key/token and transaction ID will be provided to the voter. 
This would even let the voters cast their vote from polling booths anywhere in India after being approved by the validators (Proof of Authority) and the result could be declared on the same date as well.  

## Workflow of idea
![workflow](https://github.com/VedikaJK/Blockchain-in-Voting/blob/master/Workflow.jpeg)

## Analogy with Bitcoin
Bitcoin has demonstrated in the financial space that trusted, auditable computing is possible using a decentralized network peers accompanied by a public ledger. This concept can be brought in the election voting system too.  
![bitcoin analogy table](https://github.com/VedikaJK/Blockchain-in-Voting/blob/master/Bitcoinanalogy.jpeg)  

## Implementation
•	First the physical **authentication** of the voter will be done and the person would retrieve a **token/key** that would allow them to **vote exactly once** and ensure **anonymity** (ring signature). This is the same mechanism used to ensure the double spending problem in bitcoin doesn’t exist, but now with voting.  
•	The voter will cast vote using the token/key. The vote would be validated by the **Proof of Authority Network** and then a **transaction ID** will be given which would ensure that the vote has been appended successfully into the Blockchain database.  
•	The votes can’t be tampered as editing a block on the blockchain changes the **hash function** of the block which disturbs the whole chain.  
•	We’ll be using **Permission Blockchain** (variation of **Consortium based Blockchain**) which is partially centralized where the consensus process is controlled by a preselected set of nodes (the constituencies).  
•	A **private network** will be used in order to limit the possibility for an eavesdropper to monitor the traffic or read the incoming data.  
•	Each voter is bound into a ballot **smart contract** with the district he is enrolled in. Each vote must be agreed upon by district nodes for the vote to get added in the blockchain.  

## Technology 
 Ethereum Proof of authority consortium blockchain published by Microsoft  
 
 ## TEAM NAME - ACUMEN
### Indian Institute of Technology Guwahati
#### Vedika Kulkarni
#### Niyati Chaudhary
#### Pooja Bhagat

