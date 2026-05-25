# Infrastructure Modernization & Operational Efficiency Proposal

A comprehensive IT infrastructure consultation for Network Funtime Co., a 100-person engineering and design firm. This proposal transitions the company from manual, decentralized workflows to a structured, automated IT infrastructure.

## Current Problems Identified

| Problem | Impact |
|---------|--------|
| Manual laptop procurement | HR buys after hire starts, causing delays |
| Manual onboarding | Hours of personal orientation per new hire |
| No data backups | Single file server, no redundancy, messy permissions |
| No password recovery | Machine must be wiped if password forgotten |

## Recommended Solutions

| Problem Layer | Solution | Technical Tool |
|--------------|----------|----------------|
| User Identity | Centralized Auth & Recovery | Microsoft Active Directory |
| Hardware | Standardized Procurement | Business Vendor Portal |
| Data Safety | Redundant Storage & Backup | RAID NAS + Cloud Backup (Azure/GCP) |
| Fleet Management | Automated Deployment | Microsoft Endpoint Manager (Intune) |
| Security | Access Control | RBAC for file server |

## Process Improvements

### 1. Standardize Hardware

- Stop buying random cheapest laptops
- Recommend standard model (e.g., HP EliteBook)
- Benefits: Easier repairs, consistent imaging, predictable performance

### 2. Centralized Authentication

- Implement Active Directory
- Automate user account creation
- Self-service password reset
- Benefits: Removes burden from HR, IT controls access

### 3. Asset Inventory

- Physical labeling + digital tracking (Snipe-IT)
- Benefits: You can't manage what you don't track

### 4. Automated Onboarding

- Replace personal HR orientation with imaging
- Tools: Clonezilla or Windows Autopilot
- Benefits: Saves hours per new hire, consistent setup

### 5. Security Policies

- Enforce Password Complexity Policy
- Implement MFA via directory service
- Benefits: Protects intellectual property

## Technical Stack Summary

| Category | Recommended Tool | Rationale |
|----------|-----------------|-----------|
| Directory Services | Microsoft Active Directory | Centralize accounts, stop manual logins |
| Asset Management | Snipe-IT | Track hardware, stop losing equipment |
| Deployment | Microsoft Endpoint Manager | Image 50 laptops at once |
| Backup | Google Cloud Backup | Off-site redundancy |
| Communication | Microsoft Teams | Secure instant communication |

## Business Impact

By transitioning from manual, decentralized workflows to structured IT infrastructure:

- **Reduced operational downtime** through proactive monitoring
- **Lower security risks** via RBAC and MFA
- **Scalable growth** â IT can manage 100+ users efficiently
- **Strategic transformation** â IT becomes an asset, not a cost center

## What I Learned

- Enterprise IT infrastructure design
- Active Directory and identity management concepts
- Cloud backup strategies (Azure, GCP)
- Configuration management and imaging
- How to align IT solutions with business needs
- The difference between reactive break-fix and strategic IT

## Environment

- Context: Google IT Support Professional Certificate â System Administration Course
- Date: April 2026
