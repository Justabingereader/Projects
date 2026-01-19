# Cybersecurity & IT Knowledge Repository

## Overview
This repository is a longitudinal, applied cybersecurity and IT knowledge base.
It documents hands-on learning, experimentation, analysis, and formal reporting across networking, systems administration, cloud infrastructure, cybersecurity operations, governance, risk, and compliance (GRC).

It is not a collection of tutorials.
It is a record of system interaction, decision-making, failures, mitigations, and structured reasoning across real and simulated environments.

The repository should be interpreted as:
- A timeline of skill acquisition
- A cross-domain knowledge graph
- A portfolio of applied security and infrastructure work
- A reference archive for audits, reports, and tooling

## Design Philosophy
- Emphasis on real system behavior, not abstractions
- Focus on cause → effect → mitigation
- Preference for documentation, reporting, and traceability
- Security treated as risk management, not tool usage
- Clear separation between learning artifacts, tools, and formal assessments

## High-Level Domain Map
1. Networking & Routing
2. Cybersecurity & Threat Analysis
3. Systems & Operating Systems
4. Virtualization & Cloud Infrastructure
5. Governance, Risk & Compliance (GRC)
6. Auditing, Reporting & Documentation
7. Offensive & Defensive Security Tooling
8. Enterprise Infrastructure & Identity
9. Cryptography, Confidentiality & Data Protection
10. Foundational IT & Hardware
11. Research, Referencing & Academic Rigor

---

## 1. Networking & Routing
**Purpose:** Understand segmentation, routing logic, traffic flow, and enterprise network behavior.

### Core Topics
- **Network Fundamentals** 
  - Hosts, clients, servers and their roles in network communication
  - IP addressing, subnetting, subnet design and network segmentation
  - Internet architecture and general network communication principles
  
- **Network Devices & Architecture**
  - Repeaters, hubs, bridges as physical layer devices
  - Switches as multiport combination of hubs and bridges
  - Routers, default gateway, and routing table operations
  - Multiple methods of routing table population (static, dynamic)
  - Default routes and route summarization
  - Packet forwarding with unknown destination addresses

- **OSI Model & Layer Functions**
  - Layer 2 (Data Link): Hop-to-hop delivery mechanism
  - Layer 3 (Network): End-to-end delivery mechanism
  - Layer 4 (Transport): Service-to-service delivery mechanism
  - Layer 5 (Session), Layer 6 (Presentation), Layer 7 (Application): Role in network communication and cookies
  - General rules governing network communication

- **Data Transmission Processes**
  - Encapsulation and de-encapsulation processes
  - Host communication (directly connected and router-mediated)
  - Switching operations and data forwarding in networks
  - MAC address tables, ARP tables, and routing tables - their mappings and roles

- **Network Protocols & Standards**
  - RFC (Request for Comments) and its role in building the internet
  - Internet standards development and implementation

### Applied Knowledge
- VLAN design, trunking, access ports, SVIs
- OSPF routing protocols
- ACLs (Access Control Lists)
- SME network models
- Secured inter-router networks

---

## 2. Cybersecurity & Threat Analysis
**Purpose:** Treat security as structured risk identification, assessment, and mitigation.

### Core Topics
- CVE analysis and vulnerability lifecycle management
- CVSS scoring and risk quantification
- KEV/EPSS usage for prioritization
- Threat modeling methodologies
- NIST SP 800-30 risk assessments

### Practical Application
- **Packet Analysis & Network Security** 
  - ICMP protocol analysis and security implications
  - ICMP tunneling attack vectors and mitigation strategies
  - ICMP/Ping flooding (DDoS) detection and prevention
  - DNS query/response analysis and proxy behavior identification
  - ARP protocol security: spoofing detection, scanning, and mitigation
  - IP fragmentation analysis and fragmentation attack prevention
  - Network traffic filtering and baseline establishment
  - Wireshark packet decoding and protocol stack analysis

### Security Considerations
- Protocol vulnerabilities (ICMP, ARP, DNS)
- Man-in-the-middle attack vectors
- Network reconnaissance techniques
- Traffic analysis for anomaly detection
- Firewall configuration for protocol-specific threats

---

## 3. Systems & Operating Systems
**Purpose:** Understand operating systems as security boundaries.

### Core Topics
- Linux and Windows internals
- Privilege separation and access control
- Scripting for automation and security
- System logging and audit trails
- Patch management and vulnerability remediation

---

## 4. Virtualization & Cloud Infrastructure
**Purpose:** Model modern infrastructure realistically and cost-consciously.

### Core Topics
- Docker containerization
- Virtual machine management
- Oracle Cloud Infrastructure
- Firewall rules and network security groups
- SSH hardening and secure remote access
- TLS/SSL implementation
- Cost-avoidance strategies

---

## 5. Governance, Risk & Compliance (GRC)
**Purpose:** Translate technical systems into compliance-aware structures.

### Core Topics
- GDPR compliance and data protection
- ISO 27001 control frameworks
- Control mapping and gap analysis
- Policy development and implementation
- BYOD risk management
- Data protection by design principles

---

## 6. Auditing, Reporting & Documentation
**Purpose:** Ensure technical work is explainable, defensible, and reviewable.

### Core Competencies
- **Formal Technical Reporting**
  - Executive summaries and findings presentation
  - Evidence-based analysis with supporting screenshots
  - Structured question-answer format for technical assessments
  - Network traffic analysis documentation
  - Protocol behavior documentation

- **Academic Rigor**
  - Harvard UL referencing system
  - Citation of technical sources (RFCs, vendor documentation, standards)
  - Proper attribution of tools, techniques, and methodologies
  - Integration of theoretical knowledge with practical application

- **Evidence Tables & Appendices**
  - Wireshark captures and analysis
  - Network diagrams and topology documentation
  - Filter expressions and their purposes
  - I/O graphs and traffic pattern visualization

### Applied Examples
- Packet Analysis Report (ATU Letterkenny - Threat Management 1)
- Daily learning logs with comprehensive tagging systems
- Protocol-specific analysis with security implications

---

## 7. Offensive & Defensive Security Tooling
**Purpose:** Learn tools as instruments for understanding systems.

### Core Tools & Techniques
- **Network Analysis**
  - Wireshark: Packet capture, protocol dissection, display filters
  - Packet decoding methodology and protocol stack analysis
  - I/O graphs for traffic pattern visualization
  - Name resolution and FQDN identification

- **Network Scanning & Enumeration**
  - Nmap for host discovery and port scanning
  - ARP scanning for internal network mapping
  - ICMP-based reconnaissance (ping, traceroute)

- **Security Testing**
  - OpenVAS vulnerability scanning
  - Netcat for network debugging
  - Ethical exploitation analysis

### Analysis Techniques
- Display filter creation for protocol isolation
- Traffic baseline establishment
- Anomaly detection through statistical analysis
- Attack pattern recognition (flooding, spoofing, tunneling)

---

## 8. Enterprise Infrastructure & Identity
**Purpose:** Understand identity as the core security primitive.

### Core Topics
- Active Directory domain services
- Identity and Access Management (IAM)
- Multi-Factor Authentication (MFA)
- Single Sign-On (SSO) implementations
- Switch security and port security
- Least-privilege design principles

---

## 9. Cryptography, Confidentiality & Data Protection
**Purpose:** Protect data, not just systems.

### Core Topics
- Encryption tools and algorithms
- Password managers and credential security
- Steganography techniques
- Secure messaging applications
- Key management and PKI

---

## 10. Foundational IT & Hardware
**Purpose:** Ground security in physical reality.

### Core Topics
- CPU architecture and instruction sets
- Memory hierarchy and management
- Storage technologies and data persistence
- BIOS/UEFI and boot processes
- POST (Power-On Self-Test)
- Hardware abstraction layers

---

## 11. Research, Referencing & Academic Rigor
**Purpose:** Ensure claims are traceable and defensible.

### Research Tools & Methods
- Zotero for reference management
- Vendor documentation analysis
- CVE databases and vulnerability tracking
- Standards-based reasoning (RFC, NIST, ISO)
- IANA protocol assignments
- Technical white papers and security advisories

### Citation Standards
- Harvard UL referencing format
- Proper attribution of technical concepts
- Source verification and fact-checking
- Integration of multiple authoritative sources


## How an AI Should Interpret This Repository

1. **Treat files as interconnected nodes** forming a knowledge graph
2. **Expect overlapping domains** and progressive complexity
3. **Interpret repetition as reinforcement**, not redundancy
4. **Recognize the learning trajectory** from fundamentals to advanced application
5. **Value both theoretical understanding and practical application**
6. **Understand that tags create cross-references** across temporal and topical boundaries

---

## Final Note
This is a professional-grade applied cybersecurity knowledge base.
It represents continuous learning, hands-on experimentation, and formal academic assessment in cybersecurity and IT infrastructure.
The progression from basic networking concepts to advanced threat analysis demonstrates systematic skill development and knowledge integration.
