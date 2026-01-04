# AWS-SQL-Server-Migration
AWS DMS / MSSQL

## High-Level Architecture
<img width="787" height="292" alt="image" src="https://github.com/user-attachments/assets/cbe7b7d4-d5bd-49dd-af84-b43e3bb7073c" />


# On-Premises → AWS SQL Server Migration
**AWS DMS · EC2 · Site-to-Site VPN · SQL Server**  
**May – June 2025**

---

## Overview
This repository documents the migration of a Microsoft SQL Server database from an on-premises environment to AWS EC2, executed with **minimal downtime**. The migration leveraged **AWS Database Migration Service (DMS)** for continuous replication and a **site-to-site VPN** for secure hybrid connectivity.

Validation evidence, monitoring, and screenshots are included in the attached project PDF.

---

## Objectives
- Migrate production SQL Server workloads from on-premises to AWS EC2
- Minimize downtime using **Full Load + CDC** replication
- Establish secure hybrid connectivity between on-premises and AWS
- Validate data consistency before final cutover
- Ensure a controlled cutover and rollback capability

---

## Tech Stack
- **Database:** Microsoft SQL Server  
- **Migration:** AWS Database Migration Service (DMS)  
- **Compute:** Amazon EC2  
- **Networking:** Amazon VPC, Subnets, Security Groups, Site-to-Site VPN  
- **Monitoring:** Amazon CloudWatch  

---

