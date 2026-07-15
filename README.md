# Blockchain Based Secure Voting System

A blockchain-based electronic voting project that aims to make elections more secure, transparent, tamper-resistant, and efficient by storing encrypted votes as immutable blockchain transactions and using smart contracts to validate voters and enforce election rules.[cite:1]

## Overview

This project was developed as a Major Project Phase-I report under the Department of Computer Science and Engineering at Yenepoya Institute of Technology, Moodbidri, for the academic year 2025â€“26.[cite:1] The proposed system addresses common election problems such as fake voting, duplicate voting, fake addresses, and lack of trust in centralized voting methods.[cite:1]

The system combines blockchain, cryptographic vote encryption, and secure voter authentication to improve election integrity while preserving voter privacy.[cite:1] It is designed to offer public verifiability, lower operational cost, and better reliability than traditional paper-based or manually managed election systems.[cite:1]

## Objectives

- Design a secure blockchain-based voting system that stores votes as immutable records.[cite:1]
- Implement strong voter authentication using biometric verification or secure digital credentials.[cite:1]
- Preserve privacy and confidentiality of votes through encryption techniques.[cite:1]
- Reduce election cost and time by minimizing manual processes and physical infrastructure.[cite:1]

## Features

- Secure voter registration and authentication.[cite:1]
- Encrypted vote submission and storage.[cite:1]
- Blockchain-based immutable ledger for tamper-proof vote records.[cite:1]
- Smart contracts for voter validation and duplicate-vote prevention.[cite:1]
- Transparent result publication with public verifiability.[cite:1]
- Monitoring for suspicious activity and fraud detection during the election process.[cite:1]

## System workflow

1. The voter registers using valid identification details and biometric data or secure credentials.[cite:1]
2. The system authenticates the voter before granting access to the voting interface.[cite:1]
3. The selected vote is encrypted using cryptographic methods such as ElGamal encryption.[cite:1]
4. The encrypted vote is submitted to the blockchain as a transaction.[cite:1]
5. Smart contracts validate voter eligibility and prevent duplicate voting.[cite:1]
6. After the election ends, votes are securely counted and results are published for verification.[cite:1]

## Architecture modules

| Module | Purpose |
|--------|---------|
| Voter Registration and Authentication | Verifies voter identity using biometric data or secure credentials.[cite:1] |
| Vote Encryption | Encrypts the selected vote before transmission and storage.[cite:1] |
| Blockchain Storage and Smart Contract | Stores encrypted votes as immutable transactions and enforces election rules.[cite:1] |
| Result Decryption and Display | Decrypts votes after polling ends and publishes the final result.[cite:1] |

## Technology stack

| Category | Tools / Technologies |
|---------|-----------------------|
| Programming language | Python 3.8.[cite:1] |
| Blockchain interaction | Web3.py, Ethereum blockchain.[cite:1] |
| Smart contracts | Solidity, Remix IDE.[cite:1] |
| Web framework | Flask.[cite:1] |
| Computer vision | OpenCV for gesture detection.[cite:1] |
| Testing tools | Ganache, MetaMask, Jupyter Notebook, VS Code.[cite:1] |

## Hardware and software requirements

### Hardware

- Standard laptop with Intel i5/i7 CPU and 8 GB RAM.[cite:1]
- 720p HD webcam.[cite:1]
- Minimum 10 GB free storage.[cite:1]

### Software

- Windows 10/11, Linux, or macOS.[cite:1]
- Python 3.8 environment.[cite:1]
- Flask, Web3.py, cryptography libraries, OpenCV, and related dependencies.[cite:1]
- Solidity development and Ethereum testing tools such as Remix, Ganache, and MetaMask.[cite:1]

## Project structure

```text
Blockchain-Based-Secure-Voting-System/
â”œâ”€â”€ README.md
â”œâ”€â”€ report/
â”‚   â””â”€â”€ blockchain-literature-survey-1.docx
â”œâ”€â”€ src/
â”‚   â”œâ”€â”€ frontend/
â”‚   â”œâ”€â”€ backend/
â”‚   â”œâ”€â”€ contracts/
â”‚   â””â”€â”€ auth/
â”œâ”€â”€ docs/
â”‚   â”œâ”€â”€ block-diagram
â”‚   â”œâ”€â”€ dataflow-diagram
â”‚   â”œâ”€â”€ use-case-diagram
â”‚   â””â”€â”€ activity-diagram
â””â”€â”€ requirements.txt
```

## Expected outcome

The proposed system is expected to provide a secure and reliable election platform that prevents vote tampering, supports transparent result verification, protects voter confidentiality, and improves trust in the election process.[cite:1] It is also intended to reduce time, paperwork, and infrastructure costs compared with traditional voting systems.[cite:1]

## Limitations and future scope

Current blockchain voting research still faces challenges related to scalability, voter anonymity, and coercion resistance, as highlighted in the literature survey included in the report.[cite:1] Future improvements can include stronger zero-knowledge proof integration, better self-tallying mechanisms, improved accessibility features, and deployment on more optimized blockchain networks.[cite:1]

## Contributors

- Ishaq Mohammed Nawaz
- Isra Zainab
- Madeeha Mohammed Mubeen
- Shamma Shirin M A[cite:1]

## Institution

Yenepoya Institute of Technology, Moodbidri, Karnataka, under Visvesvaraya Technological University.[cite:1]
