# NFT Raffle for the Solana Blockchain
Raffle that allows the winner to claim an NFT in Solana

# The Setup
- Set up a Solana account and obtain the necessary keys to access it.
- This smart contract on Solana will handle the logic of the raffle.
- This contract will be able to generate random numbers and determine the winner of the raffle based on those numbers.
- Once the raffle is complete and a winner has been determined, the smart contract will be able to transfer the NFT to the winning user's account.

# The UI
- This smart contract needs a user interface (UI) that allows users to enter the raffle by sending a transaction to the smart contract.
- This UI could be a simple web page that allows users to enter their Solana account details and submit a transaction to the contract.

# The Code
This code defines a class called Raffle that represents a raffle contract on the Solana blockchain.

The Raffle class has a few key methods: 
- enter_raffle(), which allows users to enter the raffle by adding their entry to a list of entries stored in the contract;
- draw_winner(), which allows the contract owner to randomly select a winner from the list of entries and transfer the prize (assumed to be an NFT) to the winner's address;
- transfer_token(), which sends the NFT to the winning user's account on the Solana blockchain.
- program(), which returns the instructions for the contract's program.
- program_id(), which return the contract's program ID.
- contract_account_id(), which return the contract account ID.