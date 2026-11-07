# Governance, Risk, and Compliance (GRC) Charter

**Organization:** Hilltop Guest House

**Framework Alignment:** ISO 27001 (Information Security Management System - ISMS)

**Version:** 0.1

**Effective Date:** Not set yet

**Review Cycle:** Annual (or upon major operational changes)

## Purpose & Executive summary

The purpose of this Governance, Risk, and Compliance (GRC) Charter is to establish a formal Information Security Management System (ISMS) framework in accordance with **ISO 27001** for **Hilltop Guest House**.

Operating a 20-room boutique hotel with an on-site restaurant and an online booking portal requires systematic management of information security risks, safeguarding guest privacy, securing payment transactions, and ensuring business continuity across all physical and digital touch-points.

## **Organizational Context & Background**

Hilltop Guest House doesn’t have any previous security documentation or risk register.

## Scope

The scope of the GRC/ISMS framework encompasses all operational, physical, and technological assets required to deliver guest services at Hilltop Guest House:

1. **Digital & IT Assets:** Online booking engine, website, Property Management System (PMS), Point of Sale (POS) terminals, administrative laptops, storage servers, internal management networks, and guest Wi-Fi.
2. **Information Assets:** Guest Personally Identifiable Information (PII), payment card data, employee records, financial ledgers, and operational SOPs.
3. **Physical Assets & Facilities:** 20 guest rooms, front desk, administrative offices, restaurant, kitchen, server/network closets, and physical access control systems.
4. **Third-Party Services:** Managed Service Providers (MSPs), web hosting, payment gateways, and maintenance vendors.

## Objectives:

To measure the effectiveness of the Information Security Management System (ISMS) and maintain alignment with ISO 27001, Hilltop Guest House establishes the following measurable security objectives. These targets apply across the boutique hotel, the on-site restaurant, and the digital booking infrastructure:

1. **Data Protection & Confidentiality:** Ensure zero (0) unauthorized disclosures of guest Personally Identifiable Information (**PII**) or credit card data by performing monthly access log audits of the Property Management System (PMS) and online booking portal.
2. **Payment Card Security (PCI-DSS Consistency):** Achieve and maintain 100% compliance with Payment Card Industry Data Security Standards (PCI-DSS) for all physical restaurant POS terminals and digital booking systems by enforcing annual PCI-DSS Self-Assessment Questionnaire (SAQ) completion and quarterly network vulnerability scans.
3. **System Availability & Business Continuity:** Maintain a minimum of 99.99% (yearly) uptime for the online booking portal and guest check-in systems to eliminate operational downtime and revenue loss by automated tracking of hosting provider server uptimes and monthly IT infrastructure reporting.
4. **Staff Security Awareness:** Ensure 100% of all full-time, part-time, and seasonal hotel/restaurant staff complete basic information security and data privacy training by evaluating  training completion records collected during onboarding and reinforced during annual refresher courses.
5. **Incident Response & Remediation:** Contain any identified security anomaly or suspected data incident within two (2) hours of initial detection.

These objectives will be reviewed at least annually during management reviews or immediately following any significant upgrade to the hotel's operational technologies.

## **Stakeholders**

1. **Internal Stakeholders:** 
    1.  **Business Owner:** Holds ultimate accountability for overall risk approval, legal liability, business operations, and funding the GRC budget.
    2. **Compliance Coordinator:** Owns risk assessments, policy documentation, internal audit cadences, PCI-DSS SAQ tracking, and regulatory oversight.
    3. **Front Desk & Reservations Lead:** Manages physical check-ins, guest registration, keycard access controls, and booking engine entries inside the Property Management System (PMS).
    4. **Restaurant & Kitchen Lead:** Responsible for food safety storage, kitchen sanitation, allergen tracking, public health compliance, and restaurant POS operations.
    5. **Housekeeping & Maintenance Staff:** Handles physical room access, facility/safety inspections, lost-and-found items, and chemical/cleaning supply storage.
    6. **General & Seasonal Staff:** Executes daily operational SOPs, processes payment transactions, and adheres to security/privacy policies.

1. **External Stakeholders:**
    1. **Web Hosting Vendor:** Manages and secures the website, booking portal, network firewalls, Wi-Fi segmentation, system backups, and software updates.
    2. **Payment Processors & Merchant Banks (PCI SSC):** Defines financial transaction security standards (PCI-DSS) for Points of Sale (POS) terminals and the web payment portal.
    3. **Regulatory & Government Agencies:**
        1. **Public Health Department:** Inspects food handling, storage, and restaurant hygiene.
        2. **Local Fire & Building Authorities:** Enforces building occupancy limits, fire detection systems, and emergency exits.
        3. **Data Protection Regulators:** Overseas compliance with data protection laws (e.g., GDPR/local privacy statutes) regarding guest PII.
    4. **Insurance Carriers:** Requires proof of baseline physical, operational, and cyber risk controls to maintain policy coverage and coverage rates.

## Risk Assessment & Information Security Criteria

All information assets, physical operations, and technological controls across Hilltop Guest House shall be evaluated against formal risk acceptance thresholds and ISO 27001 control criteria.

#### A. Organizational & Access Controls

- **Least Privilege:** Property management system and booking portal access must be role-based. Staff members are granted access strictly necessary for their immediate job functions.
- **Legal & Payment Compliance:** Guest Parsonally identifiable information collection must comply with data privacy laws. Credit card processing must maintain strict PCI-DSS compliance across all points of sale terminals and online booking integrations.
- **Incident Management:** Security events or potential privacy breaches must be reported within **1 hour** of discovery.

#### B. Technical & Infrastructure Security

- **Network Isolation:** Guest Wi-Fi networks must remain strictly segmented via VLANs and firewalls from internal Property Manage Systems, points of sale, and administrative networks.
- **Encryption:** All guest data and financial tokens must be encrypted in transit using TLS 1.3 and at rest using AES-256.
- **Backups & Recovery:** Automated daily backups of guest reservation logs and financial records are mandatory.

#### C. Physical & Environmental Security

- **Access Restraints:** Network closets, server hardware, and front-desk key-card creation terminals must remain physically secured and restricted to authorized personnel.
- **Surveillance:** CCTV monitoring is restricted to public perimeters, reception, and dining areas. Surveillance in guest rooms or restrooms is strictly prohibited.
- **Environmental Safety:** Fire alarms, smoke detectors, and emergency lighting must undergo documented quarterly inspections and certified annual servicing.

#### D. Supplier & Third-Party Security

- All external vendors must provide valid evidence of security compliance prior to contract execution and upon annual review.

## Timeline

Estimated Timeline: 18 days (06 Nov 2026 – 23 Nov 2026)

- **Task 1:** Create project repository, charter and basic templates (06 Nov - 07 Nov)
- **Task 2:** Generate realistic asset inventory for the hotel (08 Nov - 10 Nov)
- **Task 3:** Perform ISO 27001 gap analysis against the asset list (11 Nov - 14 Nov)
- **Task 4:** Develop a risk register based on identified gaps (15 Nov - 17 Nov)
- **Task 5:** Draft core security policies and control implementation plan (18 Nov - 21 Nov)
- **Task 6:** Compile final GRC package and publish on GitHub Pages (22 Nov - 23 Nov)