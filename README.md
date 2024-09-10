# SmallBlockchain

This project simulates the fundamental concepts of a blockchain, including transactions, Proof of Work, block mining, and wallet management. Below are the main components and functionalities:

## Main Components

1. **Create Wallets**
   - **Description:** You can create wallets (digital wallets) that contain public and private keys. Each wallet has an initial balance that can be used to perform transactions.
   - **Functionality:** Generate wallets to manage and transfer digital coins.

2. **Create Transactions**
   - **Description:** You can generate transactions between wallets by specifying the amount of coins you want to transfer. The system will validate whether the sender has sufficient funds before processing the transaction.
   - **Functionality:** Perform transfers between wallets and validate balances.

3. **Mine Blocks**
   - **Description:** Once you have generated enough transactions (or periodically), you can mine a new block. This process includes the Proof of Work, where the system adjusts the nonce until it finds a hash that meets the difficulty criteria.
   - **Functionality:** Mine blocks with Proof of Work and nonce adjustments.

4. **Verify Transactions**
   - **Description:** Every time a block is mined, the transactions within that block are verified and processed. This includes updating the balances of the involved wallets.
   - **Functionality:** Verify and process transactions in the blocks.

5. **Blockchain Validation**
   - **Description:** The code allows you to verify the integrity of the blockchain, ensuring that the blocks are correctly connected and haven't been tampered with by checking the hashes of previous blocks.
   - **Functionality:** Validate the blockchain's integrity and structure.

6. **Mining Rewards**
   - **Description:** As in a real blockchain, the miner who validates a block receives a reward (in this case, 50 coins). This is implemented through a special transaction called coinbase.
   - **Functionality:** Implement mining rewards via coinbase transactions.

## Documentation

The documentation used for this implementation is available at the following [link](https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf) and will be attached to this repository.

## Code

The code was developed in Google Colab to be used on other devices. The link to the notebook is attached in this document.
