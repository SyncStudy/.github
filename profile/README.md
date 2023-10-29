# Quantum Oracles: Decentralized Quantum Computing on Blockchain

![Architecture](./assets/Screenshot%202023-10-29%20at%205.29.31%20AM.png)

[Architecture and Data Flow Diagram](https://miro.com/app/board/uXjVNVN3tMU=/?share_link_id=58900692180)

## Overview

Quantum Oracles aims to revolutionize the landscape of quantum computing by decentralizing quantum computations and reducing the trust needed for executing quantum programs. Our project allows smart contracts to execute quantum programs, stores the results on-chain, and aggregates the results from multiple quantum computers. Users can pay for their quantum jobs using cryptocurrency, effectively creating an end-to-end decentralized ecosystem for quantum computing.

## Features

- **Efficient Retrieval**: Store results of quantum computations on-chain, making the execution of the same program only required once.
  
- **Decentralization**: Execute quantum programs on multiple quantum computers to reduce trust and dependency on a single service provider.

- **Payment in Cryptocurrency**: Integrated cryptocurrency payments for seamless user experience.


## Tech Stack

- **Flare**: Fast and cheap blockchain for storing quantum computation results.
  
- **Scaffold ETH**: For front-end development and smart contract integration.
  
- **Google Cloud**: For deploying quantum API and API3 Airnode.
  
- **API3**: For the price feed for calculating the code in different cryptocurrencies for running the quantum computation.

## Smart Contract: QuantumOracleV1

The heart of the project lies in the `QuantumOracleV1` smart contract, which is responsible for handling oracle management, circuit creation, and result aggregation.

## Installation

### Dependencies

Make sure you have Node.js and npm installed. Then clone the repository and install dependencies.

```bash
git clone https://github.com/Quantum-Oracles/DAPP.git
cd DAPP 
yarn
```

### Running Locally

Start the front-end application.

```bash
yarn start
```

## Usage

- **Submit Circuit**: Users can submit a new quantum circuit, which is then sent to the oracles and then they send the circuits to quantum computers for execution. 

- **Fetch Results**: Once executed, the results are stored on-chain and can be fetched by users and also they can be used by other smart contracts for conditional execution of logic.

## Demo Images

![Image 1](./assets/Screenshot%202023-10-29%20at%205.26.04%20AM.png)

![Image 2](./assets/Screenshot%202023-10-29%20at%205.26.14%20AM.png)

![Image 3](./assets/Screenshot%202023-10-29%20at%205.26.29%20AM.png)

![Image 4](./assets/Screenshot%202023-10-29%20at%205.26.38%20AM.png)

![Image 5](./assets/Screenshot%202023-10-29%20at%205.26.52%20AM.png)


## Contributing

We welcome contributions from the community.

## License

This project is licensed under the MIT License.

## Contact

For more information, contact us at [contact@yashgoyal.dev](mailto:contact@yashgoyal.dev), [contact@jessicapointing.com](mailto:contact@jessicapointing.com)

---
