# Pump.fun-Smart-Contract
This is the Rust/Anchor smart contract for Pump.fun.

## Contact
telegram: @Takhi77

You can contact me here if you have any problems with this repo then we can decide comfortable contact way.

## Features
It has All features that pump.fun has.

✅ Token Mint

✅ Create Pool with 30 Sol of initial virtual Sol reserve

✅ Add Liquidity

✅ Swap Token with the price of the token (Virtual Sol Reserve / Virtual Token Reserve)

✅ Raydium Launch when the Market Cap of the Token (price of the token * 10 ** 9) is reached to $69M

When the Market Cap meet the KOH, the pumpfun launch the real Sol $12K i.e. $24K Liquidity to the Raydium.
Then the rest of the liquidity will be gained by pumpfun team.

## Bonding Curve Logic
It is using its own specific bonding curve logic.

so It is

X * Y = K ** 2

X : the price of the token

Y : the supply of the token in the pool


It has its own test cases to test all functions except Raydium Launch because it is used my ongoing project.
You can check the tx to Remove vitual LP and Create Raydium Pool in this smart contract with CPI calls.
https://explorer.solana.com/tx/4L6MWmtV1ZsT8NFfbtu68ZYyYVbpvZ4iynJhPdZw8jESi28TxwojjTFs88Q5QRdNUb297aWfkKcoYP9Ya8npx8AV?cluster=devnet
In this smart contract, I set creating LP FEE as 5% of Reserves.
