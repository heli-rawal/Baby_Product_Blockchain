# Baby Blockchain

* Python BlockChain to register the baby projects
<hr>

>Operations:
	/chain  -- for entire chain
	/register  -- for manufacturers
	/transfer  -- for transaction history
	/nodes/register  -- for registering the node
	/nodes/resolve  -- To apply the Replication thing

>Replication:
	Pass the longest chain to the node passing GET request through /nodes/resolve

>Blockchain:
	First block is genesis
	Second block will get the hash value from previous block
	Transactions field will be empty first and then it'll be filled when transactions occur

>Things working:
	Blockchain - main idea
	Proof of Work - 2*number = last digits should be 0000 find number (Puzzle before validation)
	Consensus - lenghth of all the registered nodes chain
	Replication - after Consensus --> GET the highest one
	Merkle tree - data structure used to store tranactions in a binary tree format