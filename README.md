# Demo App

This repository contains documentation proving the completion of the specified tasks.

1. Understand the Product and Swap Lifecycle
2. SDK Installation and Integration
3. Localnet Setup
4. Submission

## LocalNet Dapp

Leveraging the Garden SDK, this project focuses on creating a **decentralized application for secure medical image analysis**. Healthcare providers can upload **medical images to be analyzed by sophisticated AI algorithms**, ensuring data integrity and security through the Garden SDK's Bitcoin cross-chain capabilities. **Payments for services are managed transparently and securely.** The application also includes a **crowdfunding feature**, enabling the community to provide financial assistance to patients in need of emergency medical funds. This integration of AI-driven analysis and decentralized financial support aims to improve diagnostic accuracy and streamline funding for urgent medical care.

**Here's How this Dapp works**

![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/94a0aba288161875d150a0ed9b85d2841082606d/Assets/Dapp%20for%20Medical%20Image%20Analysis.jpeg)

**For this Prototype we have built the LocalNet Dapp to transfer between BTC and WBTC.**

## LocalNet Environment Setup

To run the created dapp, please follow the following steps :

1. Install Merry

```bash
curl https://get.merry.dev | bash
```

2. Start Merry

```bash
# Start Merry with explorer
merry go
```

or

```bash
# Start Merry without explorer
merry go --headless
```

3. Fund your EVM address

```bash
 merry faucet --to <EVM Address>
```

## LocalNet Project Setup

1. Clone the repository

```bash
git clone https://github.com/Vasanth2310/Garden-Task.git
cd demoapp
```

2. Install dependencies

```bash
bun install
```

3. Run the development server

```bash
bun run dev
```

## LocalNet Transaction Results

The dApp that I have created and the transaction held on it are as follows

![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/41b5a68f4c84c82f4c508d4cd7289b13d487531c/Assets/Screenshot%20(82).png)
![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/41b5a68f4c84c82f4c508d4cd7289b13d487531c/Assets/Screenshot%20(85).png)
![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/41b5a68f4c84c82f4c508d4cd7289b13d487531c/Assets/Screenshot%20(89).png)
![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/41b5a68f4c84c82f4c508d4cd7289b13d487531c/Assets/Screenshot%20(88).png)
![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/41b5a68f4c84c82f4c508d4cd7289b13d487531c/Assets/Screenshot%20(87).png)

## TestNet Setup 

   - Review [BTC-WBTC Swap Guide](https://docs.garden.finance/home/basics/guides/btc-wbtc).
   - Get testnet BTC from the [Faucet](https://faucet-v1.netlify.app/).
   - Complete a swap on [Testnet](https://testnet.garden.finance).

## TestNet Transaction Results

![Please visit the Assets Folder if Image is not displayed](https://github.com/Vasanth2310/Garden-Task/blob/d550efe11f6cd240a5fd82e9beb5424d6462dfb7/Assets/Screenshot%20(90).png)
