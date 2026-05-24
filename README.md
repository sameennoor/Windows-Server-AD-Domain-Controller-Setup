# Windows-Server-ADDS-Infrastructure Setup
This project demonstrates the implementation of a Windows Server-based Domain Controller using Windows Server 2012 R2 in a virtualized environment. It focuses on building and managing a centralized network infrastructure using Active Directory services for user, computer, and resource administration.

## ⚡ Core Operational Capabilities
The virtualized network core drives organizational access through three high-availability infrastructure layers:

* **Centralized Identity Federation (AD DS):** Deploys a unified directory lookup catalog to govern authentication, object trees, and global administrative access control lists.
* **Deterministic Network Routing (Static IP Control):** Establishes hardcoded, non-volatile network address bindings to ensure consistent service discoverability and server node validation.
* **Hypervisor-Isolated Sandbox Topology (VMware NetCore):** Emulates bare-metal data center operations within a software-defined Type-2 hypervisor boundary, protecting host integrity.

## 🔬 System Configurations & Implementation Vectors
### 1. Active Directory Directory Services Core
* Provisions structured tree topologies consisting of secure root domains, organizational units (OUs), and centralized asset catalogs.
* Enforces structural security policies and domain-wide credential validation protocols across all joined nodes.

### 2. Static Interface Anchoring
* Normalizes localized communication layers by decoupling the primary infrastructure node from dynamic DHCP pools.
* Establishes reliable point-to-point service request patterns for directory access and domain authentication queries.
### 3. Hypervisor Virtual Interconnects
* Provisions virtual switch fabrics (vSwitches) and custom network interfaces to mimic real-world LAN structures.
* Secures packet transmissions between virtual endpoints while managing intra-guest communications safely.

## Project objective
The objective of this project is to demonstrate practical implementation of enterprise-level network administration, including domain creation, centralized user management, and virtualized infrastructure setup using Windows Server and Active Directory.

## 🛠️ Infrastructure Provisioning Blueprint (Deployment Process)
The system is deployed through a systematic, multi-tiered engineering pipeline:

```text
Phase 1: Hypervisor Setup        ──► Installation of VMware Workstation 15 Pro virtualization engine.
Phase 2: Guest OS Instantiation  ──► Bare-metal emulation of Windows Server 2012 R2 with hardened privileges.
Phase 3: Static IP Anchoring     ──► Manual network interface binding to lock stable communication pathways.
Phase 4: Role Provisioning       ──► Binary compilation and execution of Active Directory Domain Services (AD DS).
Phase 5: Domain Tree Promotion   ──► New forest root initialization, DNS zone indexing, and administrative deployment.
Phase 6: Object Orchestration    ──► System lifecycle tracking, group policy assignment, and identity management.

