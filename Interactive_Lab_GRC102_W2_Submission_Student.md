# Interactive Lab GRC102 — Week 2 Submission
**Course:** GRC102 - Information Security Governance
**Lab:** Lab 2 — Developing Security Policies and Procedures
**Role:** Information Security Manager, NexusTech Solutions
**Submission Date:** March 8, 2026

---

# Table of Contents

1. [Task 1 — Establishing the Security Policy Hierarchy](#task-1)
   - 1.1 Hierarchy Definition Table
   - 1.2 Categorization Exercise
2. [Task 2 — Writing an Effective Security Policy](#task-2)
   - 2.1 Completed Acceptable Use Policy
3. [Task 3 — Creating Actionable Security Procedures](#task-3)
   - 3.1 Completed User Access Request Procedure
4. [Task 4 — Policy Implementation and Communication](#task-4)
   - 4.1 Communication and Training Plan
5. [Task 5 — Policy Review and Maintenance](#task-5)
   - 5.1 Policy Review Memo

---

<a name="task-1"></a>
# Task 1 — Establishing the Security Policy Hierarchy

## Deliverable 1.1 — Hierarchy Definition Table

A well-structured security policy framework operates across four distinct tiers. Each tier serves a specific governance or operational function, and each carries a different level of authority, specificity, and flexibility. Confusing these tiers — as seen in the IT Director's draft that mixed policy intent with operational steps — leads to documents that are difficult to enforce, difficult to update, and difficult to audit.

| Tier | Purpose | Characteristics | Mandatory or Recommended | Typical Approval Authority |
|---|---|---|---|---|
| **Policy** | States the organisation's position, intent, and high-level requirements on a security topic. Answers *what* must be done and *why* it matters. | Broad in scope; principle-based; does not specify technical implementation; relatively stable over time. | **Mandatory** — non-compliance carries formal consequences. | CEO, Board of Directors, or Executive Leadership. |
| **Standard** | Defines the specific, measurable requirements that must be met to comply with a policy. Answers *how much* or *how specifically* something must be done. | More specific than a policy; technology or process-referenced; quantifiable and testable; updated when technology or regulatory requirements change. | **Mandatory** — provides the minimum acceptable threshold. | CISO, Information Security Manager, or IT Director. |
| **Guideline** | Provides recommended approaches, best practices, and suggested methods for implementing policies and standards. Answers *how it is advisable* to do something. | Advisory, not mandatory; provides flexibility for different teams or contexts; useful for staff needing practical direction without a rigid requirement. | **Recommended** — not enforced, but deviation may increase risk. | Information Security team or subject matter experts. |
| **Procedure** | Delivers step-by-step operational instructions for performing a specific task in a consistent, repeatable manner. Answers *exactly how* a task is carried out. Procedures implement policies, standards, and guidelines at the operational level. | Highly specific; action-oriented; sequential; tied to a particular system, role, or process; updated most frequently as systems and processes change. | **Mandatory** when referenced by a policy or standard; the procedure itself defines the required steps. | IT Operations, Helpdesk Manager, or Process Owner. |

**Relationship Between Tiers:**
Policies sit at the top and set direction. Standards translate policy intent into measurable, mandatory requirements. Guidelines offer recommended approaches for implementation — they are not enforced but reduce risk when followed. Procedures operationalise everything into repeatable, executable steps that implement policies, standards, and guidelines simultaneously. A change at the policy level cascades down through all tiers; a change in a procedure does not necessarily require a policy update, but must remain aligned with the policy's intent.

---

## Deliverable 1.2 — Categorization Exercise

| # | Statement | Classification | Justification |
|---|---|---|---|
| 1 | "All NexusTech employees must use multi-factor authentication (MFA) when accessing the corporate network remotely." | **Policy** | This is a high-level mandatory requirement stating *what* must be done (use MFA for remote access) without specifying *how* to configure or implement it. It reflects organisational intent and applies broadly to all employees. |
| 2 | "To configure MFA on your mobile device, download the Authenticator app, scan the QR code provided in the IT portal, and enter the 6-digit verification code." | **Procedure** | This is a sequential, step-by-step instruction that tells a specific user *exactly how* to perform a specific task. It is action-oriented, tool-specific, and operational — the defining characteristics of a procedure. |
| 3 | "It is recommended that developers use parameterized queries to prevent SQL injection vulnerabilities." | **Guideline** | The word "recommended" and the absence of a mandatory requirement make this a guideline. It advises a best practice for a specific audience (developers) without mandating compliance or specifying a minimum threshold. |
| 4 | "NexusTech is committed to protecting the confidentiality, integrity, and availability of all client data." | **Policy** | This is a broad, principle-based statement of organisational intent — the classic language of a policy preamble. It states *why* security matters to NexusTech without specifying any technical requirement or action. |
| 5 | "All corporate laptops must have full-disk encryption enabled using BitLocker (Windows) or FileVault (macOS)." | **Standard** | This is a specific, mandatory, measurable, and technology-referenced requirement. It names the exact tools (BitLocker, FileVault) and sets a clear minimum requirement for all corporate laptops — the defining characteristics of a standard. |
| 6 | "Employees should avoid connecting to public, unsecured Wi-Fi networks when traveling." | **Guideline** | The word "should" (rather than "must") signals a recommendation rather than a mandate. This provides sensible behavioural advice without imposing a measurable or enforceable requirement — making it a guideline. |
| 7 | "In the event of a suspected security breach, employees must immediately contact the IT Helpdesk at extension 5555." | **Procedure** | This is a specific, action-oriented instruction that tells employees *exactly what to do* in a defined situation (a suspected breach), referencing a specific contact method. It is a procedural step within an incident response process. |
| 8 | "Passwords must be a minimum of 14 characters in length and contain at least one uppercase letter, one lowercase letter, one number, and one special character." | **Standard** | This is a specific, quantifiable, mandatory requirement that defines the minimum acceptable threshold for password construction. It supports a broader access control or password policy, and it is measurable and testable — the hallmarks of a standard. |

---

<a name="task-2"></a>
# Task 2 — Writing an Effective Security Policy

## Deliverable 2.1 — Completed Acceptable Use Policy

---

# NexusTech Solutions Acceptable Use Policy

## 1. Policy Title and Version Control

**Title:** Acceptable Use Policy
**Version:** 1.0
**Date:** March 8, 2026
**Classification:** Internal — All Staff
**Next Review Date:** March 2027
**Policy Owner:** Information Security Manager

---

## 2. Purpose

NexusTech Solutions provides its employees, contractors, and authorised third parties with access to information technology resources — including devices, networks, systems, and data — to support the effective delivery of business operations. These resources are an asset of the company and must be used responsibly, legally, and in a manner consistent with NexusTech's obligations to its clients, regulators, and employees.

The purpose of this Acceptable Use Policy (AUP) is to define the boundaries of acceptable behaviour when using NexusTech's IT resources. It protects the confidentiality, integrity, and availability of NexusTech's information assets; safeguards the company from legal, regulatory, and reputational risk; and ensures that IT resources remain available and effective for legitimate business use.

---

## 3. Scope

This policy applies to:

- **All persons** who access NexusTech IT resources, including full-time and part-time employees, contractors, consultants, interns, and authorised third-party vendors.
- **All NexusTech-owned or managed IT resources**, including laptops, desktop computers, mobile devices, servers, network infrastructure, cloud services, software applications, email systems, and internet access.
- **All locations** from which NexusTech IT resources are accessed, including NexusTech offices, home environments, client sites, and public locations.

This policy applies regardless of whether the device used is owned by NexusTech or personally owned, if it is used to access NexusTech systems or data.

---

## 4. Policy Statements

### 4.1 General Acceptable Use

All users of NexusTech IT resources must:

- Use NexusTech IT resources primarily for authorised business purposes.
- Take reasonable precautions to protect the security of the devices, accounts, and data they access, including locking unattended devices and not sharing login credentials under any circumstances.
- Comply with all applicable laws, regulations, and NexusTech security standards when using IT resources, including those governing data protection (e.g., GDPR, HIPAA where applicable), intellectual property, and electronic communications.
- Report any suspected security incident, unauthorised access, or policy violation to the IT Helpdesk promptly. Failure to report a known or suspected incident is itself a policy violation.

### 4.2 Prohibited Activities

The following activities are strictly prohibited on NexusTech IT resources:

- Accessing, downloading, storing, or distributing content that is illegal, obscene, defamatory, discriminatory, or harassing.
- Installing, executing, or distributing software that has not been approved by the IT department, including personal applications, browser extensions, and tools obtained from unofficial sources.
- Attempting to circumvent, disable, or interfere with NexusTech's security controls, monitoring tools, or access management systems.
- Using NexusTech systems to conduct personal commercial activities, run external businesses, or engage in activities that create a conflict of interest with NexusTech.
- Sharing, transmitting, or storing NexusTech client data or sensitive business information through personal email accounts, personal cloud storage services, or any platform not approved for that purpose.
- Using NexusTech's network or systems to launch or facilitate attacks against third-party systems, or to engage in any activity that could damage NexusTech's reputation or expose the company to legal liability.

### 4.3 Personal Use of Company Resources

Limited, incidental personal use of NexusTech IT resources is permitted, provided that it:

- Does not interfere with the user's job responsibilities or business operations.
- Does not consume significant bandwidth, storage, or computing resources.
- Does not violate any other provision of this policy.
- Does not involve accessing or sharing any content that would be inappropriate in a professional workplace setting.

NexusTech reserves the right to monitor the use of its IT resources, including internet activity and communications conducted on company systems, in accordance with applicable law. Users should have no expectation of privacy when using NexusTech-owned systems or networks.

### 4.4 Remote and Mobile Access

Users accessing NexusTech systems from outside the corporate office must:

- Connect through NexusTech's approved remote access solution (VPN or equivalent) at all times.
- Use only NexusTech-approved devices that meet the security standards set out in the NexusTech Device Security Standard.
- Ensure that the physical environment from which they work does not permit unauthorised individuals to view sensitive information on their screen.

### 4.5 Data Handling on Company Devices

Users must not store NexusTech client data, financial data, or any data classified as Confidential or Restricted on personal devices or unauthorised cloud storage platforms. All data must be stored and shared in accordance with the NexusTech Data Classification Policy.

---

## 5. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| **All Users (Employees, Contractors, Third Parties)** | Read, understand, and comply with this policy. Complete mandatory AUP training and acknowledgement. Report policy violations and suspected security incidents. |
| **Information Security Manager** | Own and maintain this policy; conduct periodic reviews; investigate reported violations; provide guidance on acceptable use questions. |
| **IT Department** | Enforce technical controls that support this policy (e.g., endpoint monitoring, software whitelisting, access controls); manage approved software lists; provide helpdesk support. |
| **Human Resources** | Incorporate AUP acknowledgement into the employee onboarding process; manage disciplinary processes arising from policy violations in collaboration with line managers. |
| **Line Managers** | Ensure all team members complete AUP training and acknowledgement; escalate suspected violations to the Information Security Manager and HR. |

---

## 6. Compliance Requirements

This policy supports NexusTech's obligations under the following regulatory frameworks and standards:

| Regulation / Standard | Relevance to This Policy |
|---|---|
| **ISO/IEC 27001** | Requires documented policies for information security management, including acceptable use of assets (Annex A.8). This AUP directly supports NexusTech's ISO 27001 certification objectives. |
| **SOC 2 (Trust Services Criteria)** | Requires controls governing logical and physical access restrictions, monitoring of system activity, and acceptable use of company systems. This AUP supports SOC 2 Common Criteria CC6 and CC9. |
| **GDPR** | Requires technical and organisational measures to protect personal data. Sections 4.2 and 4.5 of this policy directly restrict activities that could result in unauthorised disclosure of personal data held by NexusTech. |
| **HIPAA (where applicable)** | For NexusTech's healthcare sector clients, this policy supports administrative safeguard requirements for workforce use of electronic information systems containing Protected Health Information (PHI). |

NexusTech will monitor regulatory changes on at least an annual basis and update this policy accordingly to maintain compliance with applicable requirements.

---

## 7. Definitions and References

### Key Terms

| Term | Definition |
|---|---|
| **IT Resources** | All hardware, software, networks, data, cloud services, and communication systems owned, leased, or managed by NexusTech Solutions. |
| **Authorised User** | Any individual who has been granted formal access to NexusTech IT resources through the approved User Access Request Procedure. |
| **Confidential Data** | Information classified as Confidential or Restricted under the NexusTech Data Classification Policy, including client data, financial records, employee data, and intellectual property. |
| **Approved Software** | Software that has been evaluated and formally approved for use by the NexusTech IT department. The current approved software list is maintained on the NexusTech intranet. |
| **Personal Cloud Storage** | Third-party cloud storage services not approved by NexusTech IT (e.g., personal Google Drive, personal Dropbox, personal iCloud). |
| **Compensating Control** | An alternative security measure implemented when a standard requirement cannot be met, designed to provide an equivalent level of protection. |

### Related Documents

- NexusTech Data Classification Policy
- NexusTech Access Control Policy
- NexusTech Device Security Standard
- NexusTech Password Standard
- NexusTech Incident Response Policy
- NexusTech User Access Request Procedure
- NexusTech Disciplinary Policy

---

## 8. Verification and Policy Effectiveness Metrics

The Information Security Manager is responsible for measuring the effectiveness of this policy on a continuous basis using the following metrics framework:

| Metric Category | Measurement Method | Target |
|---|---|---|
| **Compliance Rate** | Percentage of staff who have completed AUP acknowledgement; tracked via LMS. | 100% within 30 days of policy effective date; 100% for all new joiners at onboarding. |
| **Security Incident Tracking** | Number of incidents attributable to AUP-related violations (e.g., unauthorised software, data sharing via personal platforms), tracked monthly via the IT ticketing system. | Zero repeat incidents in any AUP-covered category within 12 months of policy launch. |
| **Awareness and Understanding** | Post-training quiz scores from the mandatory e-learning module; phishing simulation results (where conducted). | Minimum 80% pass rate on first attempt; improvement trend over successive assessments. |
| **Exception Tracking** | Number, type, and frequency of AUP exception requests logged in the central exception register. | Patterns of repeated exceptions for the same clause will trigger a policy review. |
| **Risk Reduction** | Reduction in unauthorised software installations and personal cloud storage usage incidents, measured via endpoint monitoring and DLP tooling (once implemented). | Measurable downward trend within 6 months of policy launch. |

Metrics are reviewed monthly by the Information Security Manager and reported quarterly to the CEO and, where applicable, the Information Security Steering Committee.

---

## 9. Compliance and Enforcement

Compliance with this policy is mandatory for all persons within scope. Violations of this policy may result in:

- Immediate suspension of access to NexusTech IT resources pending investigation.
- Disciplinary action up to and including termination of employment or contract, in accordance with NexusTech's disciplinary procedures.
- Civil or criminal legal action where the violation constitutes a breach of applicable law.

All suspected violations will be investigated by the Information Security Manager in coordination with HR and, where necessary, Legal. The outcome of investigations will be documented and retained.

**Exception Management Process:** Exceptions to this policy may only be granted through the formal exception management process, which follows these steps:
1. The requesting business unit submits a written request to the Information Security Manager, stating the business justification, the specific policy clause in question, the duration required, and proposed compensating controls.
2. The Information Security Manager conducts a risk assessment of the proposed exception.
3. Compensating controls are agreed upon and implemented before the exception is activated.
4. The exception is formally approved or denied in writing by the Information Security Manager.
5. All approved exceptions are recorded in the centralised exception register with an expiration date.
6. Exceptions are reviewed periodically; patterns of repeated exceptions for the same policy area trigger a formal policy review.

No exception may be approved without an expiration date. Exceptions do not constitute permanent amendments to this policy.

---

## 10. Version Control and Review

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | March 8, 2026 | Information Security Manager | Initial policy. Supersedes "IT Rules" document. |

This policy will be reviewed **annually** as a minimum, or sooner upon any of the following triggers:
- A confirmed security incident involving AUP-covered activities.
- A material change to NexusTech's technology environment (e.g., new cloud platform, acquisition).
- A change in applicable regulatory requirements (ISO 27001, SOC 2, GDPR, HIPAA).
- A significant change in organisational structure or workforce composition.

Review is led by the Information Security Manager. Updated versions require approval from the CEO before taking effect.

---

## 11. Approval Information

**Approved By:** Marcus Vance, CEO
**Approval Date:** March 8, 2026
**Policy Owner:** Information Security Manager
**Next Review Date:** March 2027

---

*This policy supersedes the previous "IT Rules" document in its entirety. All staff are required to read and acknowledge this policy upon its effective date.*

---

<a name="task-3"></a>
# Task 3 — Creating Actionable Security Procedures

## Deliverable 3.1 — Completed User Access Request Procedure

---

# NexusTech Solutions User Access Request Procedure

**Document Type:** Procedure
**Version:** 1.0
**Date:** March 8, 2026
**Classification:** Internal — IT Staff
**Procedure Owner:** IT Helpdesk Manager
**Related Policy:** Acceptable Use Policy v1.0; Access Control Policy
**Next Review Date:** March 2027

---

## 1. Purpose

This procedure defines the standardised process for requesting, approving, provisioning, and documenting user account access to NexusTech systems and applications. It operationalises the Acceptable Use Policy requirement that "all access to NexusTech systems must be formally requested, approved, and provisioned."

The purpose is to ensure that access is granted consistently, at the appropriate level for each role, with a documented approval trail — eliminating the current practice of provisioning accounts based on informal communication.

---

## 2. Scope

This procedure applies to:

- **All new user account requests**, including new employees, contractors, interns, and authorised third-party vendors requiring access to NexusTech systems.
- **All modifications to existing access**, including role changes, department transfers, and requests for elevated permissions.
- **All Helpdesk technicians** responsible for provisioning accounts in Active Directory, cloud applications, and other NexusTech systems.

This procedure does not cover emergency break-glass access, which is governed by the NexusTech Incident Response Procedure.

---

## 3. Prerequisites

Before executing this procedure, the Helpdesk technician must have:

- Active login credentials to the NexusTech IT Ticketing System (ServiceDesk).
- Active Directory (AD) administrative rights sufficient to create and configure user accounts.
- Access to the NexusTech Role-Based Access Control (RBAC) Matrix, which defines the standard permission sets for each job role.
- Access to the approved onboarding request form (available on the NexusTech intranet under IT Forms).

---

## 4. Procedure Steps

### Step 1 — Receiving the Access Request

1.1 All access requests must be submitted through the NexusTech IT Ticketing System (ServiceDesk). Requests submitted via email, Slack, or verbal communication are not valid and must not be actioned.

1.2 The request must be submitted using the standard **New User Access Request Form**, which requires the following information:
- Full name of the new user.
- Job title and department.
- Start date or access required date.
- Name and employee ID of the requesting line manager.
- Systems and applications for which access is required.
- Justification for any access that falls outside the standard RBAC profile for the role.

1.3 Upon receipt, the Helpdesk technician assigns the ticket to themselves and sets its status to **In Progress**.

---

### Step 2 — Verifying Approval

2.1 Before any account is created, the technician must confirm that the request has been formally approved by the user's direct line manager.

2.2 Approval is confirmed when the line manager has responded to the automated approval notification sent by ServiceDesk, or has added a written approval comment directly within the ticket.

2.3 If approval has not been obtained within **two business days** of the request being submitted, the technician sends a reminder to the line manager via ServiceDesk and flags the ticket as **Pending Approval**.

2.4 If no approval is received within **five business days**, the ticket is escalated to the IT Helpdesk Manager for follow-up. The account must not be provisioned until written approval is confirmed.

---

### Step 3 — Creating the User Account

3.1 Once approval is confirmed, the technician creates the user account in Active Directory following the NexusTech AD Account Naming Convention (available on the intranet).

3.2 Account settings must be configured as follows:
- Account status: **Disabled** (accounts are activated only after all permissions are correctly assigned — see Step 4).
- Password: A temporary password is generated in accordance with the NexusTech Password Standard. The user will be required to reset this password at first login.
- Password expiry: Set per the NexusTech Password Standard.

3.3 The technician records the account creation timestamp and their own employee ID in the ticket as evidence of action.

---

### Step 4 — Assigning Permissions

4.1 The technician retrieves the standard RBAC profile for the user's job role from the NexusTech RBAC Matrix.

4.2 The user is added to the Active Directory security groups corresponding to their standard role profile.

4.3 If the request includes access to systems or applications beyond the standard RBAC profile (e.g., elevated database access, access to client financial data), the technician must confirm that these additional permissions have been explicitly listed in the approved request and signed off by the line manager and, where required, the Information Security Manager.

4.4 Access to systems classified as **Restricted** (as defined in the NexusTech Data Classification Policy) requires a secondary approval from the Information Security Manager before provisioning.

4.5 Once all permissions are correctly applied and verified, the technician enables the user account in Active Directory.

---

### Step 5 — Notifying the User and Line Manager

5.1 The technician sends a notification email to the new user and their line manager via ServiceDesk containing:
- The user's login username.
- The temporary password (sent separately via a secure channel — do not include in the same email as the username).
- A link to the NexusTech IT self-service portal and the First Login Guide.
- A reminder that the user must complete mandatory security awareness training within five business days of their start date.

5.2 The notification is logged automatically by ServiceDesk as part of the ticket record.

---

### Step 6 — Documenting, Verifying, and Closing the Ticket

6.1 Before closing the ticket, the technician must verify that provisioning was successful by:
- Confirming the account appears in Active Directory with the correct attributes and group memberships.
- Performing a test authentication (where system policy permits) or requesting the user or their manager to confirm first login was successful within one business day of notification.
- Confirming that access to each provisioned system reflects the correct permission level as defined in the RBAC Matrix — not elevated, not under-provisioned.

6.2 The technician records the following in the ticket notes as the formal evidence of procedure execution:
- Date and time of account creation.
- Active Directory groups and applications provisioned.
- Approvals received (line manager, and Information Security Manager if applicable), including dates.
- Date and time of user and manager notification.
- Confirmation of successful first login or equivalent verification outcome.

6.3 The ticket status is updated to **Resolved** and the ticket is closed in ServiceDesk.

6.4 Access provisioning records are retained in ServiceDesk for a minimum of **three years**, in accordance with NexusTech's records retention requirements and ISO 27001 audit trail obligations.

---

## 5. Exceptions

**Incomplete Requests:** If the submitted form is missing required information, the technician places the ticket in **Pending User** status and requests the missing details from the line manager via ServiceDesk. The ticket clock is paused until the information is received.

**Emergency Access:** In cases where access is required urgently (e.g., a critical business continuity scenario), the IT Helpdesk Manager may authorise provisional access with a reduced approval timeline. A full retrospective approval must be obtained and documented within 24 hours. Emergency access grants are flagged in ServiceDesk for review by the Information Security Manager within five business days.

**System Unavailability:** If ServiceDesk is unavailable, access requests may temporarily be submitted by email to the IT Helpdesk distribution list. The technician must create a retrospective ServiceDesk ticket as soon as the system is restored, documenting all approvals and actions taken during the outage.

---

<a name="task-4"></a>
# Task 4 — Policy Implementation and Communication

## Deliverable 4.1 — Communication and Training Plan

**Policy Being Rolled Out:** Acceptable Use Policy v1.0
**Roll-Out Owner:** Information Security Manager
**Planned Launch Date:** March 15, 2026

---

### Rationale for a Structured Rollout

Simply distributing a PDF of the new AUP is insufficient. Staff who receive a policy without context, explanation, or relevance to their own role are unlikely to read it carefully, retain its key requirements, or change their behaviour accordingly. Research and governance best practice consistently identify leadership support, clear communication of business rationale, and role-specific training as the primary drivers of successful policy adoption. This plan addresses all three.

---

### Target Audiences, Key Messages, and Channels

| Audience | Key Messages | Communication Channels |
|---|---|---|
| **All General Staff** | What the AUP covers; what is now prohibited (notably: personal cloud storage for work data, unauthorised software); what to do if they are unsure; how to report a suspected incident. Emphasis: this policy protects them as well as the company. | Company-wide email from the CEO (launch announcement); mandatory e-learning module via the LMS; intranet policy page; FAQ document. |
| **IT Staff and Helpdesk** | Full technical detail of the AUP; their enforcement and monitoring responsibilities; how to handle reports of violations; the new User Access Request Procedure. | Dedicated briefing session led by the Information Security Manager; updated internal IT runbook; Q&A channel on the internal IT Slack workspace. |
| **Management and Team Leads** | Their responsibility to ensure team compliance and acknowledgement completion; how to handle a suspected violation on their team; that they will receive completion reports. | Manager briefing (in-person or virtual) led by the CEO and Information Security Manager; one-page management summary of the policy and their obligations. |
| **New Joiners (Ongoing)** | AUP is a condition of employment; must acknowledge before system access is granted; where to find the policy and support resources. | Integrated into the onboarding checklist managed by HR; included in the IT First Login Guide sent at account provisioning. |

---

### Communication Timeline

| Week | Activity | Owner |
|---|---|---|
| **Week 1 (Launch)** | CEO sends company-wide email announcing the new AUP, explaining the business context (growth, new clients, compliance obligations), and confirming executive endorsement. Policy published on the intranet. | CEO / InfoSec Manager |
| **Week 1** | IT Staff briefing session held. Updated IT runbook distributed. | InfoSec Manager |
| **Week 1** | Management briefing held. One-page summary distributed to all team leads. | InfoSec Manager / CEO |
| **Week 2** | Mandatory e-learning module activated for all staff in the LMS. Completion deadline set for end of Week 4. Automated reminders enabled for non-completers. | InfoSec Manager / HR |
| **Week 2** | FAQ document published on the intranet. Intranet inbox opened for staff questions. | InfoSec Manager |
| **Week 3** | Mid-rollout check: managers receive completion rate report for their teams. InfoSec Manager reviews outstanding completions and escalates persistent non-completers to HR. | InfoSec Manager / HR |
| **Week 4** | Completion deadline. All outstanding acknowledgements chased by HR. | HR |
| **Week 5** | Final completion report submitted to CEO. Non-completers formally logged. | InfoSec Manager |
| **Ongoing** | AUP acknowledgement added to employee onboarding checklist for all new joiners. | HR / IT |

---

### Acknowledgement Mechanism

Acknowledgement is mandatory for all staff and must be completed by the end of Week 4. The following mechanism is used:

- The mandatory e-learning module includes a final attestation screen requiring the employee to confirm: *"I have read, understood, and agree to comply with the NexusTech Acceptable Use Policy v1.0."* Clicking confirm is logged with the employee's name, employee ID, and timestamp in the LMS — implementing the attestation process for compliance recommended in Week 2 best practices.
- For staff without LMS access (e.g., certain contractors), HR will issue a paper acknowledgement form, which is scanned and stored in the employee's personnel file.
- Completion data is reported weekly to the Information Security Manager. 100% completion is the target.
- Non-completion by the Week 4 deadline is escalated to the employee's line manager by HR. Persistent non-compliance with the acknowledgement requirement is treated as a policy violation under Section 9 of the AUP.

---

### Supporting Tools

To make compliance as easy as possible and reduce resistance — a key lesson from the Week 2 case study and a recognised policy implementation success factor — the following supporting tools will be made available to all staff at launch:

- **Quick Reference Card:** A single-page, plain-language summary of the AUP's key do's and don'ts, formatted for desktop or mobile reference. Published on the intranet and distributed in the Week 1 announcement email.
- **Approved Software List:** A searchable, up-to-date list of IT-approved applications, maintained by the IT department on the intranet. Eliminates ambiguity about what is and is not permitted.
- **Approved Cloud Storage Reference:** A clearly labelled list of approved platforms for storing and sharing NexusTech data, directly addressing the risk behaviour identified in the scenario.
- **Exception Request Form:** A standardised form available on the intranet for submitting formal AUP exception requests, removing friction from the exception management process.
- **IT Helpdesk FAQ:** A searchable FAQ document on the intranet covering the most common AUP compliance questions, reducing the volume of individual helpdesk queries.

Automation will be used wherever practical: LMS reminders for non-completers, automated acknowledgement logging, and automated manager reports — consistent with the case study finding that automation significantly improves compliance rates and reduces administrative burden.

---

### Monitoring, Feedback, and Continuous Improvement

Implementation does not end at Week 5. The following mechanisms will be established to monitor compliance and improve the programme over time:

**Monitoring:**
- Endpoint monitoring tools will track unauthorised software installation attempts; alerts will be routed to the IT Helpdesk.
- A monthly compliance dashboard will be maintained by the Information Security Manager, drawing on the five metric categories defined in the AUP's Verification and Metrics section (Section 8): compliance rates, incident frequency, awareness scores, exception volume, and risk reduction indicators.

**Feedback:**
- A short staff survey will be distributed in Week 6 to gather feedback on clarity, usability, and perceived fairness of the AUP requirements. This directly addresses the risk of ineffective communication — identified in Week 2 as one of the highest-severity implementation challenges.
- Feedback from the survey, together with helpdesk query patterns and exception request trends, will be reviewed by the Information Security Manager at the 3-month and 6-month marks.

**Recognition and Incentives:**
- Departments achieving 100% acknowledgement completion by the Week 4 deadline will be recognised in the company newsletter.
- Security awareness and policy compliance will be incorporated as a standard item in the annual performance review conversation, coordinated with HR — consistent with the Week 2 recommendation to recognise and reward compliance.

**Continuous Improvement:**
- The implementation approach itself will be reviewed at the 6-month mark. If completion rates, incident data, or survey results indicate a gap, the training content, communication channels, or supporting tools will be revised accordingly. The goal is not a one-time rollout but a sustainable compliance programme that improves with each policy cycle.

---

<a name="task-5"></a>
# Task 5 — Policy Review and Maintenance

## Deliverable 5.1 — Policy Review Memo

---

**MEMORANDUM**

**To:** NexusTech Information Security Steering Committee
**From:** Information Security Manager
**Date:** March 8, 2027
**Subject:** Acceptable Use Policy — Triggered Review and Proposed Updates

---

Two recent developments at NexusTech require a formal review of the Acceptable Use Policy (AUP) v1.0, currently also due for its scheduled annual review. Both events are recognised triggers for a priority review. First, NexusTech has completed the migration of its primary database to AWS — a material change to the technology environment that the current AUP did not specifically anticipate. References to data storage, approved platforms, and cloud usage may no longer be sufficiently specific or accurate for this updated environment. Second, a confirmed incident occurred in which an employee shared a sensitive document via a personal cloud storage account. This is a direct violation of Section 4.2 (Prohibited Activities) of the AUP. The incident confirms that either the policy language was insufficiently specific, the training and communication did not produce the intended behaviour change, or both. Under the Week 2 Policy Effectiveness Metrics Framework, this event registers as both a **Security Incident Metric** failure and an **Awareness and Understanding** gap — two of the five categories used to measure whether a policy is achieving its objectives.

The review process will proceed as follows. I will gather inputs across all five effectiveness measurement categories. For **Compliance Metrics**, I will pull AUP acknowledgement completion data and any compliance audit findings from the past 12 months. For **Security Incident Metrics**, I will obtain the full incident report and root cause analysis for the data sharing event, and review any other AUP-related incidents logged during the year. For **Awareness and Understanding**, I will review training completion rates, quiz scores from the e-learning module, and any feedback survey results collected at the 3-month and 6-month marks. For **Exception Tracking**, I will review the exception register to determine whether any patterns suggest the policy language around cloud storage is generating repeated exception requests — a signal that the policy may need revision rather than repeated workarounds. For **Risk Reduction Metrics**, I will compare the pre-launch and post-launch frequency of unauthorised cloud storage and software incidents as measured by endpoint monitoring. In parallel, I will consult with the IT Director on the approved platform list post-AWS migration, and with Legal on any updated data residency or contractual obligations arising from the new cloud environment.

On the basis of the incident alone, at least two specific AUP sections require strengthening before the next version is issued. Section 4.2 (Prohibited Activities) and Section 4.5 (Data Handling on Company Devices) should be revised to explicitly name the data categories that must not be transmitted through personal cloud accounts, and to reference the IT-maintained approved cloud platform list by name and intranet location — removing the ambiguity that appears to have contributed to the incident. Additionally, Section 4.4 (Remote and Mobile Access) must be reviewed to ensure it accurately reflects NexusTech's updated cloud architecture following the AWS migration. I will bring a revised draft of the AUP v1.1, together with the full metrics review findings and a risk assessment summary, to the next Steering Committee meeting for discussion and approval. Going forward, the annual review cycle will be anchored to a structured metrics review using the five-category framework, ensuring that policy effectiveness is assessed with evidence rather than assumption.

---

*End of Submission*

---

**Document:** Interactive_Lab_GRC102_W2_Submission
**Course:** GRC102 — Information Security Governance
**Institution:** [Your Institution]
**Submission Date:** March 8, 2026
