# GDPR-And-SOC-2-Readiness-Capstone-PayGo
Scenario-based GDPR data mapping and SOC 2 readiness assessment for a fictional Dublin fintech: gap analysis, 26-item evidence register and a 20-action prioritised remediation plan.
# PayGo GDPR Data Mapping & SOC 2 Readiness Assessment

A GRC capstone project completed for **10Alytics** (Pod Nova), assessing the privacy
and security posture of **PayGo Financial Technologies Ltd.**, a fictional
Dublin-based digital payments company with 120 employees.

The project combines a GDPR data mapping and gap assessment with a SOC 2 readiness
assessment, then consolidates both into a single prioritised remediation plan.

## Project Overview

PayGo wants to strengthen its data privacy and security practices and prepare for a
potential SOC 2 examination. Working only from the facts in the case study, I
assessed the company's processing activities, controls and evidence, and produced
findings that are each traceable to a stated scenario fact.

**Approach principle:** where the scenario was silent, the matter is recorded as an
*evidence gap* rather than a failure, so findings stay defensible and nothing is
assumed.

## Scope

- **GDPR:** 7 processing activities from the case study (customer registration,
  identity verification, payment processing, customer support, employee
  administration, security monitoring, card payments), plus email communications,
  which appears only as a provider relationship
- **SOC 2:** payment platform and supporting infrastructure against the
  **Security, Availability and Confidentiality** categories (AICPA Trust Services
  Criteria)
- **Third parties:** six provider types (cloud hosting, payment processing, identity
  verification, customer support, payroll, email)

## Key Deliverables

| Deliverable | Description |
|---|---|
| **GDPR Data Inventory** | Data categories, subjects, purposes, systems, recipients and retention for each activity, with unspecified information flagged |
| **Data Flow Descriptions** | Written flows covering source, system, storage, retention and deletion practice |
| **GDPR Gap Assessment** | 16 areas mapped to GDPR articles, with status, risk, recommended action and evidence needed |
| **SOC 2 Control Assessment** | 7 control areas assessed for design, implementation and operating effectiveness against TSC criteria |
| **SOC 2 Evidence Register** | 26 evidence items classified as Available, Evidence gap identified or Not specified |
| **Integrated Remediation Plan** | 20 prioritised actions with owners, risks and completion evidence |

## Headline Findings

**GDPR (16 areas assessed)**
- 7 Confirmed gaps, 7 Evidence gaps, 2 No gap established
- Confirmed gaps: incomplete Record of Processing Activities (Art. 30), incomplete
  privacy notice, retention without documented justification, untested deletion,
  inconsistent processor role and risk records, unrecorded transfer arrangements,
  and Art. 32 security evidence limitations
- Strengths: a documented retention schedule, and a design decision not to store
  full card numbers or card verification codes

**SOC 2 (7 control areas)**
- 4 confirmed weaknesses: access management, incident response testing, change
  management evidence, third-party risk management
- 3 evidence gaps: multi-factor authentication, alert review, backup restoration
- No central evidence register linking controls to criteria

**Remediation:** 6 High, 12 Medium and 2 Low priority actions. Several are *shared
remediation* items that close GDPR and SOC 2 findings together, such as a single
vendor assessment programme, one tabletop exercise covering both incident response
and breach notification, and one shared evidence register.

## Skills Demonstrated

- GDPR data mapping and Article 30 record-keeping
- Regulatory gap analysis (Arts. 5, 6, 12-22, 28, 30, 32-35, 44-49)
- SOC 2 Trust Services Criteria mapping (CC1-CC9, A1, C1)
- Control design vs. operating effectiveness assessment
- Evidence-based audit reasoning and exception identification
- Third-party and vendor risk management
- Risk-based prioritisation and remediation planning
- Translating framework requirements into actionable recommendations
