# 🗳️ Blockchain-Based Voting DApp

A decentralized voting application built using **React** and **Solidity**, aimed at demonstrating the fundamentals of blockchain in secure voting systems.

---

## 🧾 Project Overview

**Blockchain-Based Voting System** is a web application that leverages **Ethereum blockchain** technology to create a secure and transparent online voting platform. Traditional voting systems often suffer from issues such as centralization, lack of transparency, and vulnerability to tampering. Blockchain technology addresses these concerns by introducing:

* 🔄 **Decentralization** – No single point of control
* 🔍 **Transparency** – Everyone can verify the process
* 🔐 **Immutability** – Votes cannot be altered once recorded
* 🤝 **Trustlessness** – No need to trust a central authority

This system allows eligible voters to securely vote for their preferred candidates and see the final results immediately once the election concludes.

---

## ⚙️ Features

* ✅ Admin can add candidates and voters
* 🗳️ Voting begins only after admin starts the election
* 🔒 Voters can vote only once
* 📊 Real-time result display after election ends

---

## 🧪 Tech Stack

* **Frontend**: React
* **Smart Contracts**: Solidity
* **Blockchain**: Ethereum (Local via Ganache)
* **Development Tools**: Truffle, Metamask, Ganache

--

## 🚀 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/MohitRajKashyap/Voting-dAPP
```

### Step 2: Launch Ganache

Start your local Ethereum blockchain using the **Ganache GUI**.

### Step 3: Compile and Deploy Smart Contract

```bash
truffle migrate --reset
```

> You’ll need to re-deploy the contract each time Ganache restarts.

### Step 4: Configure Metamask

* Unlock Metamask
* Connect to Ganache’s local Ethereum network
* Import an account from Ganache

### Step 5: Run the Frontend

```bash
cd ./client
yarn install
yarn start


---

## 🔮 Future Enhancements

* Integrate biometric verification for voters
* Enhanced management of voter and candidate data
* Support for multiple election positions

---

