# Shaycoin
This is an ERC20 token that I built for fun to learn more about Ethereum and programming in Solidity.

Shaycoin (SHAY) is pegged to ETH at a rate of 5,000 SHAY : 1 ETH. You can call the "buy" and "sell" contract functions to exchange SHAY and ETH.

You can transfer SHAY from account to account just like you would with ETH.

The contract will never run out of SHAY - it produces more if it needs to.

There is a kill function that, if called by the contract owner, will refund all SHAY holders with ETH at the exchange rate before calling the selfdestruct function and removing the contract from the Ethereum blockchain.

You can also donate ETH to Shaycoin by using the "donate" function. The contract owner can collect donations at his/her discretion.
