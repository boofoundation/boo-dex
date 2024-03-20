# Introduction
Boo Dex is a Solana Token Program Aggregator which instructs transaction into the solana blockchain; swap. By aggregating transaction, Boo Dex generate some revenue from the transaction fee everytime a transaction is successfully confirmed.

## Notice
You may see blowfish warning - It is normal because Blowfish is a protocol that may give some wallet user warning of suspicious transaction. Why Suspicious? Let us explain :
1. Our domain (boocoin.co) has just registered at March 2024, which is new. Blowfish may read this as a suspicious website.
2. Boo Dex has not yet verified by the Blowfish protocol. (Which we will get our verification status done and remove the warning as soon as possible)

Then, how to get rid of this warning? Simply by pressing ignore button. (Transaction may fail if you ignore it more than 20 seconds due to timeout, you may swap again).

## Signing and Transacting
- Boo Dex only aggregates transaction and perform swap instruction over Solana Blockchain.
- Boo Dex does not have full access to your wallet, the sign is only required once you swap between tokens.

## Requirement
At version 1.0, we only support Phantom Wallet which you can get it from : https://phantom.app/

## Step-by-step Guide
1. Get your Phantom Wallet installed in your device.
2. Access the Boo Dex Aggregator - https://boocoin.co/dex
3. Try to connect your wallet to the dex
4. Select your token to swap, the above one is the spending token and the bottom one is the receive token.
5. Make sure you have the amount of token to swap from the spending token.
6. Press on Swap button, then sign the transaction. (Once signed, the instruction of swap will be sent to the blockchain)
7. Once the transaction is okay, then the dApp will send you the instruction detail that is verified on solscan.
