# Viem Transition Guide for Celo Developers

Welcome to the **Viem Transition Guide** for Celo! This project is designed to help developers transition from using `ContractKit`, `web3.js`, and `ethers.js` to the **Viem** library for interacting with the Celo blockchain.

As Celo has officially moved away from supporting ContractKit, many developers face challenges with the switch due to the lack of educational resources. This guide aims to bridge that gap by providing clear, practical examples and code snippets to help you migrate your existing Celo projects to Viem.

## What You’ll Find Here:

- **Step-by-step Instructions**: Easy-to-follow tutorials for setting up Viem, creating wallets, checking balances, sending transactions, and interacting with smart contracts on Celo.
- **Code Examples**: Ready-to-use code snippets for key functionalities like wallet management, custom gas payments (cUSD, USDC), and reading/writing to smart contracts.
- **Community-Driven**: Open-source and community-focused—feel free to contribute, report issues, or ask questions in the discussions!

By using this guide, you’ll save time and get up to speed with Viem quickly, helping you build better Celo applications.

## Content Outline

### 1. **Setting Up Viem for Celo**
   - Instructions on installing Viem and configuring it for Celo’s mainnet and testnet.
   - Example code for connecting to Celo’s RPC endpoints.

### 2. **Core Functionalities with Viem on Celo**
   
   #### **Creating a Wallet**
   - Steps to generate a new wallet or derive it from a private key.
   - Code examples for account management.

   #### **Checking Wallet Balance**
   - Guide to checking CELO, cUSD, and other asset balances.
   - Examples to retrieve and format balance data.

   #### **Sending Funds to a Wallet Address**
   - Steps for creating and sending transactions, including recipient addresses, amounts, and tokens.
   - Error-handling code examples.

   #### **Setting Custom Tokens for Gas Fee Payment**
   - Explanation of Celo’s custom token gas payment feature (cUSD or USDC).
   - Code examples on setting custom tokens for gas payment.

### 3. **Interacting with Smart Contracts**

   #### **Reading from a Smart Contract**
   - Guide to fetching data from smart contracts with Viem.
   - Examples for reading variables or calling view functions.

   #### **Writing to a Smart Contract**
   - Instructions for invoking state-changing functions on a contract.
   - Code examples demonstrating transaction parameters, error handling, and awaiting transaction receipt.

### 4. **Optional Advanced Section**
   - Tips for managing gas fees efficiently on Celo.

---

Let’s make the transition to Viem smooth and easy!
