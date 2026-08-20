<!-- Banner Image -->
![Banner](./Banner.png)

# Hi, I'm Tani Rahman

### Full-Stack Web Developer | AI Integration | Blockchain & Enterprise Systems

Chattogram, Bangladesh  
Email: **tanimahinurrahman@gmail.com**

---

## About Me

I'm a **Full-Stack Web Developer** interested in building practical, reliable, and scalable software applications.

My experience includes **frontend development, backend engineering, database systems, WordPress, AI integration, and blockchain-based applications**.

I work with technologies such as **JavaScript, Node.js, Express.js, PostgreSQL, Sequelize, Hyperledger Fabric, Docker, React, and WordPress**.

I'm particularly interested in applying **Artificial Intelligence and Blockchain** to solve real-world problems involving data integrity, enterprise systems, automation, and secure digital workflows.

I enjoy learning by building projects, exploring new technologies, and continuously improving my software engineering skills.

---

## Skills

### Languages

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Database

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Blockchain & Infrastructure

![Hyperledger Fabric](https://img.shields.io/badge/Hyperledger%20Fabric-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### AI

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![AI Integration](https://img.shields.io/badge/AI%20Integration-6C63FF?style=for-the-badge)

### Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

# Project 1. ERP Blockchain System

**ERP Blockchain System** is a blockchain-integrated enterprise application designed to improve **transaction integrity, policy-based approval, auditability, and secure transaction verification**.

The system combines traditional ERP transaction management with **Hyperledger Fabric** to provide a blockchain-based audit layer for enterprise transactions.

## Key Features

- Policy-based transaction approval
- Automatic approval for eligible transactions
- Manager approval workflow
- Multi-organization approval workflow
- Hyperledger Fabric transaction anchoring
- SHA-256 transaction integrity verification
- PostgreSQL transaction management
- Approval management
- Approval notifications
- Transaction audit logs
- Dynamic transaction timeline
- ERP-to-blockchain integrity verification
- Blockchain-based transaction auditability

## Policy Engine

The system evaluates transactions according to predefined policies and determines the required approval level.

| Transaction Level | Approval Policy |
|---|---|
| Low Value | Automatic Approval |
| Medium Value | Manager Approval |
| High Value | Manager + Auditor Approval |

## System Workflow

```text
ERP Transaction
       |
       v
Policy Evaluation
       |
       v
Approval Decision
       |
       v
SHA-256 Hash Generation
       |
       v
Hyperledger Fabric Anchoring
       |
       v
Integrity Verification
       |
       v
Audit Trail
