
# Waitlist Contracts on Aptos

## Overview

This repository contains Move smart contracts for a waitlist-based gaming system on the Aptos blockchain. These contracts facilitate various on-chain gaming experiences, managing assets, randomness, and treasury functions.

## Contracts

Below is a brief description of each contract included in this repository:

-   **coin_flip.move**: Implements a coin flip game where users can wager and win based on a fair probability mechanism.
    
-   **dice_roll.move**: A dice roll game that allows users to bet on dice outcomes, ensuring fair randomness.
    
-   **house_treasury.move**: Manages the treasury for the gaming platform, handling deposits, withdrawals, and house funds.
    
-   **nft.move**: Defines NFT-related functionalities, possibly used for rewards or special access within the system.
    
-   **plinko.move**: Implements a Plinko-style game where users drop a ball and win rewards based on the final landing position.
    
-   **raffle.move**: Handles raffle-based gaming, allowing users to enter draws and win prizes.
    
-   **resource_account.move**: Manages resource accounts, ensuring efficient handling of assets and permissions.
    
-   **wheel.move**: Implements a wheel spin game with multiple winning possibilities based on randomness.
    

## Getting Started

### Prerequisites

-   Aptos CLI installed.
    
-   Move compiler installed and configured.
    
-   Aptos testnet or devnet account set up.
    

### Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/waitlist-contracts/waitlist-contracts.git
    cd waitlist-contracts
    ```
    
2.  Set up your Aptos environment:
    
    ```
    aptos init
    ```
    
3.  Compile the contracts:
    
    ```
    aptos move compile
    ```
    
4.  Deploy to testnet or devnet:
    
    ```
    aptos move publish --profile default
    ```
    

## Usage

-   Players interact with the contracts through transactions.
    
-   Randomness is implemented for fair gaming outcomes.
    
-   House treasury manages platform earnings and distributions.
    

## Contributing

Pull requests and issues are welcome! Please follow standard development practices and test thoroughly before submitting changes.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

----------

For more details, visit the [Aptos documentation](https://aptos.dev).
