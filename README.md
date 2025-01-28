# Simple-Blockchain-Simulation

Proof-of-Work:
Implemented via the mine_block method.
A block is mined only when the hash starts with a specified number of leading zeros (difficulty).
Dynamic Transactions:
add_transaction: Adds transactions to a pending list.
mine_pending_transactions: Consolidates all pending transactions into a new block and mines it.
Chain Validation:
Ensures the integrity of the blockchain by verifying hashes.
Tampering Detection:
Allows tampering with block data and demonstrates how validation detects it.
