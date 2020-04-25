<p align="center">
  <a href="" rel="noopener">
 <img width=450px height=200px src="https://github.com/Mousto097/KryptoCoin/blob/master/src/assets/img/github-project-logo.png" alt="Project logo"></a>
</p>

<h3 align="center">KryptoCoin</h3>

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

Angular application that allows you to interact with a blockchain. You can see the blocks on chain, see transaction within them and even create new transactions and mine blocks.

## 🏁 Getting Started <a name = "getting_started"></a>

Get a copy of the KryptoCoin running on your local machine (for playing around, testing or development).

```
git clone https://github.com/Mousto097/KryptoCoin.git
```

Install the dependencies:

```
cd KryptoCoin
npm install
```

Run the application:

```
npm start
```

At this point the application should be running on your machine on [http://localhost:4200](http://localhost:4200)

## 📸 Main Features

**Home page:** Seeing blocks on the chain & exploring transactions in each block.
![](https://github.com/Mousto097/KryptoCoin/blob/master/src/assets/screenshots/blockchain-overview.png)

**Creating new transactions:** You can create new transactions to any wallet for any amount (no validation). New transactions will be added to the "pending transactions", ready to be included in the next block.
![](https://github.com/Mousto097/KryptoCoin/blob/master/src/assets/screenshots/create-new-transactions.png)

**Pending transactinos:** List of all pending transactions. These will be included in the next block when the mining process starts.
![](https://github.com/Mousto097/KryptoCoin/blob/master/src/assets/screenshots/pending-transactions.png)

**Wallet details:** You can click on any wallet address and see an overview of that wallet: its current balance and all transaction to/from that wallet.
![](https://github.com/Mousto097/KryptoCoin/blob/master/src/assets/screenshots/wallet-details.png)
