# Evidence-Protection-system-Using-Blockchain-Technology
Overview
An Evidence Protection System using Blockchain is a secure platform designed to store, verify, and track digital evidence (such as images, documents, or logs) in a tamper-proof manner. This ensures the integrity, authenticity, and immutability of the evidence, which is crucial for legal and forensic investigations.

🎯 Objective
To develop a system that leverages blockchain’s decentralized ledger to securely store and verify digital evidence, ensuring it has not been altered from its original state — even years later.

🛠️ Key Features
File Upload & Hashing: Users can upload digital evidence. Each file is hashed (e.g., SHA-256) to generate a unique fingerprint.

Blockchain Storage: The hash, timestamp, uploader ID, and metadata are stored on a blockchain, making it immutable and traceable.

Verification: Users can later verify if the evidence is genuine by comparing the current file’s hash with the one stored on the blockchain.

Chain of Custody: The system tracks who accessed or modified the evidence (if permitted), supporting legal audit trails.

🧰 Tech Stack
Frontend: HTML/CSS, JavaScript or React

Backend: Python (Flask or Django)

Blockchain: Ethereum / Hyperledger / private blockchain using Ganache + Solidity

Database: MongoDB / PostgreSQL (for metadata)

IPFS (optional): For decentralized storage of files

🔐 Why Blockchain?
Immutability: Once evidence is recorded, it can’t be altered.

Transparency: Every action is logged and traceable.

Security: Decentralization reduces single points of failure and manipulation.

📦 Outcome
A prototype system that securely records and verifies digital evidence using blockchain, suitable for use in legal proceedings, cybercrime investigations, journalism, and corporate forensics.

