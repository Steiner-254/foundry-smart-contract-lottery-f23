# Foundry Smart Contract Lottery F23 🎲

![GitHub last commit](https://img.shields.io/github/last-commit/Steiner-254/foundry-smart-contract-lottery-f23)
![GitHub issues](https://img.shields.io/github/issues/Steiner-254/foundry-smart-contract-lottery-f23)
![GitHub license](https://img.shields.io/github/license/Steiner-254/foundry-smart-contract-lottery-f23)

## Overview

Welcome to the **Foundry Smart Contract Lottery F23**! This project is designed to create a provably random, fully automated lottery using smart contracts on the Ethereum blockchain.

### Key Features:
- **Provably Random Draw**: Utilizing Chainlink's VRF (Verifiable Random Function) to ensure randomness.
- **Automated Draws**: The lottery winner is automatically selected after a specified period using Chainlink Automation.
- **Decentralized Tickets**: Users can enter the raffle by purchasing a ticket. Ticket fees go into the prize pool.
- **Fair & Secure**: Built on top of Ethereum, ensuring transparency and security.

## How it Works 🛠️

1. **Enter the Lottery**: Users buy tickets by interacting with the smart contract.
2. **Prize Pool**: Ticket fees accumulate, forming the prize for the lottery.
3. **Drawing the Winner**: Chainlink VRF generates a random number, and Chainlink Automation triggers the lottery at regular intervals.
4. **Winner Receives Prize**: The smart contract automatically sends the entire prize pool to the winner.

## Tech Stack ⚙️

- **Smart Contracts**: Written in Solidity, deployed using Foundry.
- **Randomness**: Chainlink VRF for provable randomness.
- **Automation**: Chainlink Automation for triggering the draw.
- **Testing**: Foundry for unit tests.

## Directory Structure 📂

```bash
.
├── .github/workflows     # GitHub actions for CI/CD
├── lib                   # External libraries and dependencies
├── script                # Deployment and interaction scripts
├── src                   # Core smart contracts
├── test                  # Unit and integration tests
├── .gitignore            # Ignored files
├── README.md             # Project overview (this file)
├── foundry.toml          # Foundry configuration
├── remappings.txt        # Library remappings
```

# Local Setup 💻
## Clone the repository:

```bash
git clone https://github.com/Steiner-254/foundry-smart-contract-lottery-f23.git
cd foundry-smart-contract-lottery-f23
```

## Install Dependencies:
- Ensure you have Foundry installed. If not, install it using:
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

## Compile the Smart Contracts:
```bash
forge build
```

## Run Tests:
```bash
forge test
```

## Deploy to a Local Network:
```bash
forge script script/Deploy.s.sol
```

## License 📜
- This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing 🤝
- Project Developed By: ![Steinet254](https://twitter.com/Steiner254)
- Feel free to fork this repo, submit issues, or create pull requests! Contributions are welcome.

## Acknowledgments 🙌
- `Chainlink` for providing the VRF and Automation tools.
- `Foundry` for making smart contract development and testing easy.
- `Cyfrin Updraft` for the learning content aiding to this project development.

## Happy Coding! 🚀
```vbet
Happy Web3 Revolution <3
```
