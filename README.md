# Azure Cloud Infrastructure Portfolio

Enterprise cloud architecture projects focused on disaster recovery, high availability, and network security.

---

## 📌 Project 1: Automated Cloud Backup & Disaster Recovery Architecture

### Overview
Designed and implemented an enterprise-grade Business Continuity and Disaster Recovery (BC/DR) architecture on Microsoft Azure to ensure data resiliency and automated lifecycle management.

### Architecture & Key Features
- **Data Lifecycle Policy:** Automated blob tiering (Hot -> Cool after 30 days -> Archive after 90 days) for storage cost optimization.
- **Centralized Vault:** Recovery Services Vault (`vault-backup-dr`) configured with standard daily backup schedules (`DailyVMBackupPolicy`).
- **Disaster Recovery:** Multi-region replication structure setup using Azure Site Recovery (East US -> West US).

---

### 📸 Proof of Work (Azure Portal Deployment)

#### Azure Recovery Services Vault & DR Dashboard
![Vault Overview](Azure%20Backup.png)
