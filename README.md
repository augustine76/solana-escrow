# solana escrow contract & clients

Reference implementation for the guide https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/

# Projecet Structure:
![](https://i.imgur.com/mLbjWlU.gif)

Project Structure:-

The Escrow Contract needs two accounts, Alice and Bob.
Alice starts the Escrow process by initiating the Trade.
Bob completes the Trade by fulfilling the amount of Tokens expected by Alice.
The Escrow process is completed at this point as the program transfers the tokens to Alice and Bob.

Devnet Address: 9vLJhfkCaiBAaNoLr4QFiJUZ6BfE1J1w2sRT4QtjXxQZ