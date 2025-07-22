# SimpleToken - Alephium Ralph Smart Contract

This repository contains a simple token smart contract written in **Ralph** for the **Alephium blockchain**.

## Features

- Create and track token balances.
- Mint new tokens (contract-controlled).
- Transfer tokens between accounts.
- Emits `Transfer` events for easy tracking.

## Contract Overview

The `SimpleToken` contract includes:

- **symbol**, **name**, and **decimals** to define the token.
- `getBalance()` to read the current balance.
- `mint(amount)` to create new tokens.
- `transfer(to, amount)` to send tokens to other addresses.

## How to Use

1. Deploy the `SimpleToken` contract on Alephium.
2. Call `mint()` to create initial tokens.
3. Use `getBalance()` to check token balances.
4. Transfer tokens between accounts with `transfer()`.

## Repository Structure

- `simple-token.ralph` — The Ralph smart contract source code.
- `README.md` — This documentation file.

## License

This project is licensed under the MIT License.

---

Feel free to reach out if you have questions or want to contribute!
