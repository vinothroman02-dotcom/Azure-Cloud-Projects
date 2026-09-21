# Azure Cloud Infrastructure Portfolio

Enterprise cloud architecture projects focused on disaster recovery, high availability, centralized monitoring, and network security.

---

## 📌 Project 2: Centralized Cloud Monitoring & Automated Alerting Architecture

### Overview
Configured end-to-end cloud infrastructure monitoring and metric-based alerting rules using Azure Monitor and Action Groups to detect performance bottlenecks dynamically.

### Architecture & Key Features
- **Target Infrastructure:** Azure Virtual Machine (`vm-monitoring-01`).
- **Metric Alert Rule:** Configured `High-CPU-Usage-Alert` with a threshold condition (`Percentage CPU > 80%`).
- **Automated Notifications:** Configured Action Group to trigger automated email alerts upon condition failure.
- **Incident Severity:** Severity 3 (Informational/Warning).

---

### 📸 Proof of Work (Azure Monitor & Alert Verification)

#### 1. Metric Alert Fired Status (Azure Portal)
![Alert Fired](Screenshot%202026-09-19%20131316.png)

#### 2. Automated Email Alert Notification
![Email Notification](Screenshot%202026-09-19%20131411.png)

#### 3. Alert Condition & Metric Details
![Metric Threshold Details](Screenshot%202026-09-19%20131434.png)

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
