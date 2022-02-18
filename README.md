# CS764_Blockchain2
Javascript implementation of a blockchain with random transactions made by 5 customers, 2 merchants, and 1 miner.

Nonce is a 16 byte binary which is increased by 1 at each failed hash difficulty check.

The hash difficulty cases are:
a. Number of leading zeros (as bit 0) in block hash = 0 (no restriction)
b. Number of leading zeros (as bit 0) in block hash = 5
c. Number of leading zeros (as bit 0) in block hash = 10

To run:
node main.js