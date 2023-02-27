<img width="1200" alt="Labs" src="https://user-images.githubusercontent.com/99700157/213291931-5a822628-5b8a-4768-980d-65f324985d32.png">

<p>
 <h3 align="center">Chainstack is the leading suite of services connecting developers with Web3 infrastructure</h3>
</p>

<p align="center">
  <a target="_blank" href="https://chainstack.com/build-better-with-ethereum/"><img src="https://github.com/soos3d/blockchain-badges/blob/main/protocols_badges/Ethereum.svg" /></a>&nbsp;  
  <a target="_blank" href="https://chainstack.com/build-better-with-bnb-smart-chain/"><img src="https://github.com/soos3d/blockchain-badges/blob/main/protocols_badges/BNB.svg" /></a>&nbsp;
  <a target="_blank" href="https://chainstack.com/build-better-with-polygon/"><img src="https://github.com/soos3d/blockchain-badges/blob/main/protocols_badges/Polygon.svg" /></a>&nbsp;
  <a target="_blank" href="https://chainstack.com/build-better-with-avalanche/"><img src="https://github.com/soos3d/blockchain-badges/blob/main/protocols_badges/Avalanche.svg" /></a>&nbsp;
  <a target="_blank" href="https://chainstack.com/build-better-with-solana/"><img src="https://github.com/soos3d/blockchain-badges/blob/main/protocols_badges/Solana.svg" /></a>&nbsp;
</p>

<p align="center">
  <a target="_blank" href="https://chainstack.com/protocols/">Supported protocols</a> •
  <a target="_blank" href="https://chainstack.com/blog/">Chainstack blog</a> •
  <a target="_blank" href="https://docs.chainstack.com/">Chainstack docs</a> •
  <a target="_blank" href="https://docs.chainstack.com/api/">Blockchain API reference</a> •
  <a target="_blank" href="https://console.chainstack.com/user/account/create">Start for free</a>
</p>

# Querying full and archive EVM nodes with Python

This project allows the retrieval of historical data from the blockchain programmatically, switching between a full and archive node provider when necessary.

See the full tutorial on the Chainstack blog:
* [Querying full and archive Ethereum nodes with Python](https://chainstack.com/querying-full-and-archive-evm-nodes-with-python/)

## Project details

This repository holds the Python version of a tool to query common state functions. Some essential functions include getting an address balance and storage at a given position, a contract bytecode, or even the whole transactions included on a given block.

This tool queries the blockchain using the web3 and inquirer libraries for Python. 

## Quick start

### Clone this repository


```sh
git clone https://github.com/chainstacklabs/chainstack-full-vs-archive-query-py.git
```

### Install dependencies

```sh
pip install -r requirements.txt 
```

### edit the .env.sample file

Add your RPC node URLs and rename the file to `.env`.

```env
CHAINSTACK_FULL_NODE="CHAINSTACK_FULL_NODE_URL"
CHAINSTACK_ARCHIVE_NODE="CHAINSTACK_ARCHIVE_NODE_URL"

### Run the program

```sh
python main.py
```

## Prerequisites

* Python: ^3.7— [install Node](https://www.python.org/downloads/)
* A full and archive node RPC endpoints.

Deploy a full and archive node with Chainstack:

1. [Sign up with Chainstack](https://console.chainstack.com/user/account/create).  
1. [Deploy a node](https://docs.chainstack.com/platform/join-a-public-network).  
1. [View node access and credentials](https://docs.chainstack.com/platform/view-node-access-and-credentials). 

## Dependencies
* inquirer==3.1.2
* python-dotenv==1.0.0
* web3==5.29.2

## Install

Clone this repository:

```sh
git clone https://github.com/chainstacklabs/chainstack-full-vs-archive-query-py.git
```

Install the dependencies in the project's directory:

```sh
cd query-full-and-archive-nodes-python
```

```sh
pip install -r requirements.txt 
```
