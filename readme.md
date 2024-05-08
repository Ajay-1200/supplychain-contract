# Supply Chain Smart Contract

This repository contains the implementation of a supply chain smart contract using the Soroban SDK.

## File Breakdown

### `src/main.rs`

This file contains the Rust code for defining the smart contract and its associated functions.

- `Product`: A struct representing a product with attributes such as ID, current owner, location, status, and history.
- `SupplyChainContract`: A trait defining the functions that can be called on the supply chain smart contract.
- `impl SupplyChainContract for SupplyChainContract`: Implementation of the `SupplyChainContract` trait for the supply chain contract.

### `Cargo.toml`

This file is used by Cargo, Rust's package manager, to manage project dependencies and settings.

## Smart Contract Functions

- `add_product`: Adds a new product to the supply chain.
- `update_product`: Updates the location and status of a product.
- `transfer_ownership`: Transfers ownership of a product to a new owner.
- `get_product_history`: Retrieves the history of a product including its previous locations and statuses.

## Usage

To use this smart contract, follow these steps:

1. Clone the repository.
2. Install Rust and Cargo if you haven't already.
3. Navigate to the project directory.
4. Build the project using `cargo build`.
5. Deploy the compiled smart contract to your desired blockchain platform.

## Dependencies

- `soroban_sdk`: The Soroban SDK used for smart contract development.



