# AWS Cloud Migration – FishTank Ltd (PETRA CRM)

## 🚀 Overview
This project documents the design and cost analysis of migrating FishTank Ltd's business-critical CRM system (PETRA) from legacy infrastructure to a secure, scalable AWS cloud environment.

The PETRA application is used by over 5,000 users and is hosted on aging infrastructure across two third-party data centers. This migration aims to provide:
- Disaster recovery
- Global availability
- Scalability
- Cost optimization

---

## 🧭 Architecture Design

The system is designed as a **three-tier application** architecture with high availability and low latency across **multi-region, multi-AZ** AWS deployment.

**Architecture Diagram:**
![AWS Architecture Diagram](architecture/AWS_Cloud_Diagram.jpg)

---

## 📂 Project Contents

### 📚 Documentation
| File | Description |
|------|-------------|
| `FishTank_Cloud_Migration_Proposal.pdf` | High-level strategy explaining the need for cloud migration and benefits. |
| `FishTank_AWS_Architecture_and_Costing.pdf` | Detailed AWS architecture design, instance types, and cost breakdown across two regions. |
| `FishTank_Case_Study_Technical_Specs.pdf` | Case study-style response including server specs, firewall rules, role rates, and pricing summary. |

### 💰 Pricing Estimates
| File | Region |
|------|--------|
| `Estimate_Iceland_Region.pdf` | AWS cost estimate for EU (Iceland) region |
| `Estimate_North_Virginia.pdf` | AWS cost estimate for US East (North Virginia) region |

---

## 🧰 Technologies Used
- **AWS Services**: EC2, RDS (SQL Server), ALB, CloudFront, Directory Services
- **Tools**: AWS Pricing Calculator, Microsoft Word, Draw.io (for architecture)

---

## 👩‍💻 Author

**Vandana Sharma**  
Email: [vandsharma17@gmail.com](mailto:vandsharma17@gmail.com)  
Prepared as part of the **Digital Futures Data Engineering Academy**, 2024.

---

## 📝 License
This project is for demonstration purposes and subject to standard open-source license terms.
