# Solidity Project - Lottery 
It is a lottery system inspired from ancient chinese lottery game.

How does the lottery work ?
The lottery is managed by a manager externally. Manager interacts with the smart contract to see the total balance and declare the winner.
- Each player has to deposit a fixed amount of ETH which is 0.1ETH to the smart contract. 
- Player is allowed to make multiple deposits whihc can increas chances of winning
- Manager can declare a winner once there are a minimum of 3 participants in the lottery.
- A very large number is created using blocks-timestamp and difficulty 
- This number will be divided by number of players 
- Remainder will be the index of the array of players registered sequencially.
 
WINNER IS DECLARED!!!
