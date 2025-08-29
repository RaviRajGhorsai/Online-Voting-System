# Online-Voting-System

# 🗳️ Online Voting System – Backend Contributions
🔗 [View Main Project Repository](https://github.com/YogenStha/Voting-System)

This repository highlights my backend contributions to a **project** where we built a secure **Online Voting System**. The system ensures election integrity and voter privacy by combining modern web frameworks, cryptography, and blockchain technology.

---

## 🔧 Technologies Used
- **Backend Framework:** Django & Django REST Framework (DRF)  
- **Database:** MySQL  
- **Encryption Algorithms:**  
  - **RSA** – for public/private key generation (voters & elections)  
  - **AES** – for secure vote encryption (hybrid encryption approach)  
  - **SHA-256** – for hashing and building a simple blockchain ledger  

---

## 🛠️ My Role (Backend Developer)
I was responsible for designing and implementing the **entire backend system**, focusing on security, scalability, and data integrity. My main contributions include:

### 1. **User & Election Key Management**
- Implemented **RSA-based key pair generation** for voters and election authorities.  
- Ensured secure storage of keys with proper cryptographic handling.  

### 2. **Vote Encryption & Verification**
- Developed a **hybrid encryption workflow**:
  - Each vote is encrypted using **AES**.  
  - The AES key itself is encrypted using **RSA**.  
- Implemented **digital signature mechanism** where:
  - Votes are **signed using the voter’s private key**.  
  - Signatures are verified in the backend with the corresponding **public key**.  

### 3. **Blockchain Integration**
- Built a **simple blockchain** using **SHA-256 hashing** to store votes and results.  
- Each block contains a hash of the previous block, forming an immutable chain.  
- This ensures that **votes cannot be tampered with retroactively**, providing transparency and auditability.  

### 4. **API Development**
- Built **RESTful APIs** using Django REST Framework for:  
  - Voter registration & authentication.  
  - Election creation & management.  
  - Secure vote casting & verification.  
  - Real-time election results tallying.  

### 5. **Database Design**
- Designed and optimized **MySQL schema** for:
  - Users, Elections, Candidates.  
  - Encrypted votes, digital signatures, blockchain blocks, and verification logs.  

---

## 🔐 Security & Integrity Highlights
- **End-to-End Confidentiality** – votes encrypted using AES.  
- **Integrity & Non-Repudiation** – RSA digital signatures validate each vote.  
- **Tamper-Proof Records** – SHA-256 blockchain guarantees votes cannot be altered once recorded.  
- **Scalable API Architecture** – ready for integration with frontend dashboards.  

---

## 📌 Importance of Blockchain in Voting
Blockchain plays a crucial role in ensuring **transparency and trust** in online voting systems. By linking each vote in a tamper-resistant chain of blocks, the system:  
- Prevents vote manipulation after submission.  
- Provides an auditable trail of election results.  
- Increases voter confidence by ensuring data immutability.  

---

## 📌 Summary
As the **backend developer**, I focused on delivering a **secure, reliable, and efficient system** for online elections. My role combined database management, cryptography, blockchain, and REST API development to ensure that votes remain **private, verifiable, and tamper-proof**.  

---
