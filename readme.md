# Introduction
Boo Dex is a Solana Token Program Aggregator that facilitates transactions on the Solana blockchain, specifically swaps. By aggregating transactions, Boo Dex generates revenue from transaction fees every time a transaction is successfully confirmed.

## Notice
You may encounter a Blowfish warning - this is normal as Blowfish is a protocol that can give wallet users warnings about suspicious transactions. Why suspicious? Let us explain:
1. Our domain (boocoin.co) was registered in March 2024, which is relatively new. Blowfish may interpret this as a suspicious website.
2. Boo Dex has not yet been verified by the Blowfish protocol (we are working on getting our verification status and removing the warning as soon as possible).

How do you get rid of this warning? Simply press the ignore button. (Transactions may fail if you ignore it for more than 20 seconds due to a timeout; you can retry the swap).

## Signing and Transacting
- Boo Dex only aggregates transactions and performs swap instructions on the Solana Blockchain.
- Boo Dex does not have full access to your wallet; signing is only required when you swap between 

## Requirement
At version 1.0, we only support Phantom Wallet which you can get it from : https://phantom.app/

## Step-by-step Guide
1. Install Phantom Wallet on your device.
2. Access the Boo Dex Aggregator - https://boocoin.co/dex
3. Connect your wallet to the dex.
4. Select the tokens to swap - the top one is the spending token, and the bottom one is the receiving token.
5. Ensure you have enough of the spending token to swap.
6. Press on Swap button, then sign the transaction. (Once signed, the instruction of swap will be sent to the blockchain)
7. Once the transaction is okay, then the dApp will send you the instruction detail that is verified on solscan.
