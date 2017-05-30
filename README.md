# Blockchain Demo
A Web-based demonstration of Blockchain PoC Proof of Concepts.

[![Blockchain 101 - Demo](https://img.youtube.com/vi/_160oMzblY8/0.jpg)](https://www.youtube.com/watch?v=_160oMzblY8)

This is a very basic visual introduction to the concepts behind a blockchain. We introduce 
the idea of an immutable ledger using an interactive web demo that is available here:

http://smartbiz.vn/blockchain/

> Hash: 

Some data is mapped to a seemingly random string for basic encryption.

> Block: 

A block adds a nonce field to the hashed data to introduce a concept of “signed” or “valid” hashes (in his example, the hash must start with 4 zeros).

> Blockchain: 

As the name suggests, a blockchain is a chain of blocks. A change in a block higher up the chain affects all of its trailing blocks.

> Distributed Blockchain: 

Copies of each blockchain are stored by multiple peers. Any changes in the chain is broadcast to everyone in the network, and the change must be approved by the network.

> Tokens & Coinbases: 

For a practical example, let’s see how cryptocurrency (Bitcoin) works with blockchain. When A wants to send money to B, a block is created to represent that transaction. This new change is broadcast to all the peers in the network, and if approved by the peers, the new block is added to the chain, completing the transaction. The popularity and the controversy surrounding Bitcoin skewed the general perception of blockchain as a technology limited to cryptocurrency application.

[![Blockchain](https://github.com/smartbiz/blockchain-demo/blob/master/public/images/blockchain.png)](https://github.com/smartbiz/blockchain-demo/blob/master/public/images/blockchain.png)

## Setup
Get the code:

```
 sudo git clone https://github.com/smartbiz/blockchain-demo.git
```

Install dependencies:

```
 cd blockchain-demo
 sudo npm install
```
Run the server:

```
 sudo ./bin/www
```

Point a web browser at the demo:

```
http://localhost:3000
```

## Setup using Docker

Get the code:

```
git clone https://github.com/smartbiz/blockchain-demo.git
```

Run the Docker setup:

```
cd blockchain-demo
docker-compose up -d
```

Point a web browser at the demo:

```
http://localhost:3000
```

## Send Thanks
Bitcoin greatfully accepted: `1f437e40-cdfa-42c7-ae57-c0b73a9f750b`
