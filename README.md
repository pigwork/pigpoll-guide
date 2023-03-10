# pigpoll operation guide 📄

Technical Operation Guide for the Distributed Polling System🗳:

Account Generation: any generated accounts or public addresses by default are considered 🔴non-voters,  meaning they are not willing to vote.

Voter Registration: to participate in the voting process, a non-voter must first register their public address with the smart contract. Once registered, the status of the address will be changed to ⚪️voter,  indicating that the owner of the address is willing to vote.

Voting Process: voter can execute his/her right to vote by interacting with the smart contract. Once the vote is cast, the status of the voter address will be changed to ⚫️voted,  meaning that the voter is no longer able to vote again in this ballot.

Transparency and Audibility: everyone can check the number of addresses or accounts that are interacting with the polling contract, but they cannot see what exactly the voters voted for, as the voting information is encrypted inside the contract during the process. After the polling process has been completed, the results will be revealed, and the whole process and code will be open-sourced, allowing anyone to participate in auditing work and help improve the system.
