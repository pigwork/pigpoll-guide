# pigup  operation guide

Technical Operation Guide for the Distributed Polling System:

Account Generation: Any generated accounts or public addresses by default are considered non-voters, meaning they are not willing to vote.

Voter Registration: To participate in the voting process, a non-voter must first register their public address with the smart contract. Once registered, the status of the address will be changed to "voter", indicating that the owner of the address is willing to vote.

Voting Process: The voter can execute their right to vote by interacting with the smart contract. Once the vote is cast, the status of the voter's address will be changed to "voted", meaning that the voter is no longer able to vote again in this election.

Polling Completion: After the polling process has been completed, a pre-registered administrator account can call a function in the smart contract to reveal the overall polling results.

Transparency and Audibility: Everyone can check the number of addresses or accounts that are interacting with the polling contract, but they cannot see what exactly the voters voted for, as the voting information is encrypted inside the contract during the process. After the polling process has been completed, the results will be revealed, and the whole process and code will be open-sourced, allowing anyone to participate in auditing work and help improve the system.


Note: This guide assumes that the reader is familiar with the basics of Ethereum and smart contract development.
