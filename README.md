# CEDAR Enterprise Security Architecture — Graduate Consulting Case Study

## Overview

This project was a graduate-level cybersecurity consulting case study completed as part of my Cybersecurity degree at DePaul University. Working in a small consulting team, we were tasked with designing a comprehensive enterprise security architecture for a simulated FERC-regulated electric distribution utility ("CEDAR") that had just been divested from its parent company and needed to build an independent cybersecurity program from the ground up.

CEDAR is a fictional case study company created for the course. No real client data, systems, or organizations are represented in this project.

This repository contains a summary of my individual contributions to the team's final deliverable, not the full team report, out of respect for my teammates' work and to avoid publishing a complete solved case study for a course that may reuse this scenario.

## My Role: Compliance, Risk & Infrastructure Lead

Within our consulting team, I owned the following workstreams:

### 1. Regulatory Compliance Mapping (PCI-DSS & NERC CIP)
- Mapped CEDAR's security controls to all applicable NERC CIP standards (CIP-002 through CIP-015), covering BES Cyber System categorization, security management controls, personnel training, electronic security perimeters, physical security, systems security management, incident reporting, recovery planning, configuration change management, information protection, and supply chain risk management
- Developed PCI-DSS compliance documentation for the payment card processing environment, including Cardholder Data Environment scoping, network segmentation requirements, encryption standards, and compensating controls for legacy systems
- Documented formal compensating controls (per NERC CIP-007) for end-of-life systems where standard security requirements could not be directly met

### 2. Incident Response & Cyber Resilience Program
- Authored the incident response lifecycle (preparation, detection and analysis, containment/eradication, and post-incident review) aligned to NIST SP 800-61
- Designed a four-tier incident severity classification framework with defined escalation paths and response timelines
- Built out OT-specific incident response considerations, including staged containment procedures and decision-authority requirements for actions affecting operational technology systems

### 3. Cybersecurity Budget & Resource Allocation
- Developed a three-year phased investment roadmap prioritizing spending against the team's risk register
- Built a full hardware and software cost model across firewalls, switching infrastructure, servers, physical security systems, and licensing
- Produced a cost-benefit framework tying security investment to the financial exposure of the highest-priority identified risks

### 4. Network Topology & Segmentation Design
- Designed the network topology across three geographically distributed sites, including the boundary between operational technology (OT) and corporate IT environments
- Defined the VLAN-based segmentation strategy and zone architecture supporting a defense-in-depth approach
- Diagrammed the site-to-site WAN architecture, including redundant connectivity paths supporting business continuity requirements

## Methodologies Applied

- **NIST SP 800-30** — Risk Assessment methodology
- **NIST SP 800-61** — Incident Handling Guide
- **NERC CIP** — Critical Infrastructure Protection standards (CIP-002 through CIP-015)
- **PCI-DSS** — Payment Card Industry Data Security Standard

## Note on Confidentiality & Academic Integrity

The full team report, case study prompt materials, and supporting documentation are not included in this repository. This summary reflects only my individual contribution to a team assignment and is shared for portfolio purposes.
