# 🎯 AlgoHealX – Blockchain Medicine Tracking System

[![Algorand](https://img.shields.io/badge/Blockchain-Algorand-000000?style=for-the-badge&logo=algorand&logoColor=white)](https://algorand.com)
[![PyTeal](https://img.shields.io/badge/Smart_Contracts-PyTeal-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://pyteal.readthedocs.io)
[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Healthcare](https://img.shields.io/badge/Industry-Healthcare-FF6B6B?style=for-the-badge&logo=heart&logoColor=white)]()
[![Supply Chain](https://img.shields.io/badge/Use_Case-Supply_Chain-4ECDC4?style=for-the-badge&logo=truck&logoColor=white)]()


## 🔭 Overview

AlgoHealX is a next-generation blockchain-based medicine tracking system designed to eliminate counterfeit drugs and bring complete transparency to the pharmaceutical supply chain.

Using **Algorand smart contracts (PyTeal)**, AlgoHealX ensures that every stage of a medicine batch's journey is recorded immutably — from manufacturing ➝ regulatory approval ➝ distribution ➝ pharmacy delivery ➝ consumer verification.

Every transaction is **tamper-proof**, **auditable**, and **verifiable**, making AlgoHealX a trusted solution for:

- 🏭 **Manufacturers**
- 🛂 **Regulators**
- 🚚 **Distributors**
- 👤 **Consumers**

With blockchain security and complete traceability, AlgoHealX aims to eliminate counterfeit medicines and bring **trust**, **safety**, and **transparency** to healthcare supply chains.


### 🚀 Features

- **Immutable Records**: Every medicine batch is tracked on the Algorand blockchain
- **Supply Chain Transparency**: Full visibility from manufacturing to consumer
- **Counterfeit Prevention**: Verification system to detect fake medicines
- **Multi-Stakeholder Access**: Role-based access for all supply chain participants
- **Consumer Verification**: End users can verify medicine authenticity


### 🛠️ Technology Stack

- **Blockchain**: Algorand
- **Smart Contracts**: PyTeal
- **Frontend**: React, TypeScript, Vite
- **UI**: Tailwind CSS, shadcn/ui
- **State Management**: TanStack Query

---
## 🛠️ Setup & Installation

### **Prerequisites**
Ensure these tools are installed:

- AlgoKit CLI  
- Docker (required for LocalNet)  
- Node.js & npm  
- Python 3.10+  

### ⚙️ Initial Setup

#### **1. Clone the Repository**
```sh
git clone https://github.com/nikshiptha2505/AlgoHealX.git
```

#### **2. Open Command Prompt in the Project Folder**

#### **3. Start AlgoKit LocalNet**

```sh
algokit localnet start
```

#### **4. Install All Dependencies**

```sh
algokit project bootstrap all
```

#### **5. Build the Entire Project (Contracts + Frontend)**

```sh
algokit project build
```

### 🌐 Run the Frontend

#### **6. Navigate to the Frontend Folder**

```sh
cd projects
cd AlgoHealX-frontend
```

#### **7. Start the Development Server**

```sh
npm run dev
```

The website will be available at:

👉 **[http://localhost:8080](http://localhost:8080)**

---

## 📱 Live Deployment

Our smart contract is deployed and running on the **Algorand TestNet**:

🔗 **Contract Address**: [View on Lora Explorer](https://lora.algokit.io/testnet/application/749652245)

![AlgoHealX Smart Contract on Lora](./public/loraapp.jpg)

---
#### 🔐 Security

AlgoHealX leverages Algorand's Pure Proof-of-Stake consensus mechanism to ensure:

- **High Security**: Cryptographic verification of all transactions
- **Immutability**: Records cannot be altered or deleted
- **Decentralization**: No single point of failure
- **Fast Finality**: Transactions confirmed in seconds

---

### 🤝 Contributing

We welcome contributions from the community! Please read our contributing guidelines before submitting pull requests.

---

### 📄 License

This project is licensed under the MIT License.

---

### 🌐 Links

- **Project URL**: https://lovable.dev/projects/bd68e73d-dc78-4f12-9a63-907393a63b8c
- **Documentation**: Coming soon
- **Support**: Contact our team for support

---

**Built with ❤️ for a safer pharmaceutical future**
