# GRC102: Developing Security Policies and Procedures
**Student:** Victoria Mbachu 

**Course:** GRC102 

**Week:** 2 

**Date:** March 14, 2026

---

> **Scenario:** NexusTech Solutions has grown from 50 to 250 employees. Their only security document is a 5-year-old "IT Rules" file that mixes policies, instructions, and vague suggestions. This submission builds a proper security policy framework from scratch.

---

## Table of Contents

- [Task 1 — Security Policy Hierarchy](#task-1--security-policy-hierarchy)
- [Task 2 — Acceptable Use Policy](#task-2--acceptable-use-policy)
- [Task 3 — User Access Request Procedure](#task-3--user-access-request-procedure)
- [Task 4 — Communication and Training Plan](#task-4--communication-and-training-plan)
- [Task 5 — Policy Review Memo](#task-5--policy-review-memo)

---

## Task 1 — Security Policy Hierarchy

### 1.1 Hierarchy Definition Table

Security documentation is like a building. Policies are the foundation. Standards and guidelines are the walls. Procedures are the step-by-step manual for how to actually do the work.

| Level | Name | What it does | Mandatory? | Who approves it |
|:---:|---|---|:---:|---|
|  1 | **Policy** | Sets the rules: what must happen and why it matters to the business | Yes | CEO / Board |
|  2 | **Standard** | Gives the specific details that back up a policy: exact numbers, tools, or limits | Yes | CISO / IT Director |
|  3 | **Guideline** | Offers helpful suggestions and best practices: but nobody gets in trouble for ignoring them | No | Security / IT Manager |
|  4 | **Procedure** | Step-by-step instructions for completing a specific task: written so anyone can follow it | Yes (when task applies) | IT Manager |

---

### 1.2 Categorization Exercise

Each statement from the brainstorming list is sorted below with a short reason.

| # | Statement | Classification | Why |
|---|---|---|---|
| 1 | "All employees must use MFA when accessing the network remotely." | **Policy** | Broad mandatory rule. Says what must happen, not how to do it. |
| 2 | "To configure MFA, download the Authenticator app, scan the QR code, enter the 6-digit code." | **Procedure** | Sequential steps. Tells someone exactly how to complete the task. |
| 3 | "It is recommended that developers use parameterized queries to prevent SQL injection." | **Guideline** | The word "recommended" signals this is advice, not a requirement. |
| 4 | "NexusTech is committed to protecting the confidentiality, integrity, and availability of client data." | **Policy** | High-level statement of intent. Sets the "why" for the entire programme. |
| 5 | "All laptops must have full-disk encryption using BitLocker (Windows) or FileVault (macOS)." | **Standard** | Mandatory and specific. Names the exact tools required, a measurable minimum. |
| 6 | "Employees should avoid connecting to public Wi-Fi when travelling." | **Guideline** | "Should" means advisory. No consequences for non-compliance stated. |
| 7 | "If a breach is suspected, employees must call the IT Helpdesk at extension 5555 immediately." | **Procedure** | A specific action for a specific situation. Tells you exactly what to do. |
| 8 | "Passwords must be at least 14 characters and include uppercase, lowercase, a number, and a symbol." | **Standard** | Mandatory and measurable. Defines the exact minimum password requirement. |

---

## Task 2 — Acceptable Use Policy

---

<div align="center">

# NexusTech Solutions
## Acceptable Use Policy

`NTS-SEC-POL-001` &nbsp;|&nbsp; `Version 1.0` &nbsp;|&nbsp; `March 14, 2026`

</div>

---

### 1. Purpose

NexusTech gives employees devices and systems to do their jobs. This policy sets the rules for how those resources can be used. The goal is to keep company data safe, protect client information, and make sure NexusTech meets its obligations under ISO 27001 and SOC 2.

---

### 2. Scope

This policy covers:

- Every NexusTech employee, contractor, and consultant
- All company-owned devices: laptops, phones, tablets
- All NexusTech systems: email, software, internal network, cloud tools
- All use of these resources, whether on-site or working remotely

---

### 3. Policy Statements

#### 3.1 General Use
Company devices and systems exist for work. Some personal use is fine as long as it does not get in the way of work or break any rule in this policy.

#### 3.2 Software
Only IT-approved software may be installed on company devices. Installing personal, unlicensed, or unapproved software is not allowed.

#### 3.3 Prohibited Activities

The following are strictly not allowed on any NexusTech device or system:

- Accessing, downloading, or sharing illegal or inappropriate content
- Trying to access systems, files, or accounts you are not authorised to use
- Sharing your login details with anyone else
- Using company equipment to run a personal business or for private financial gain
- Disabling or bypassing any security tool, antivirus, or monitoring software

#### 3.4 Data Handling
Company data must never be saved to personal devices or personal cloud storage accounts like Google Drive or Dropbox. All data must be stored and shared using NexusTech-approved tools only, in line with the Data Classification Policy.

#### 3.5 Remote Access
Anyone accessing NexusTech systems from outside the office must connect through the company VPN. Accessing company systems on a public or unsecured network without VPN is not allowed.

---

### 4. Roles and Responsibilities

| Who | What they are responsible for |
|---|---|
| **All Staff and Contractors** | Follow this policy. Report suspected violations to IT or HR. |
| **IT Department** | Apply technical controls. Monitor for violations. Respond to reports. |
| **HR Department** | Include policy sign-off in onboarding. Handle disciplinary cases. |
| **Information Security Manager** | Own this policy. Review it every year. Keep it current. |
| **CEO** | Approve this policy and model acceptable behaviour across the company. |

---

### 5. Compliance and Enforcement

All staff must read and sign this policy during onboarding and after each annual update.

Breaking this policy can lead to disciplinary action, up to and including dismissal. Illegal activity may be reported to the relevant authorities. The response will match the seriousness of the violation.

---

### 6. Review

This policy is reviewed every year, or sooner if there is a major change to NexusTech's systems, regulations, or business operations.

---

<div align="center">

**Approved by:** Marcus Vance, CEO &nbsp;|&nbsp; 
**Date:** March 14, 2026 &nbsp;|&nbsp; 
**Next Review:** March 14, 2027

</div>

---

## Task 3 — User Access Request Procedure

---

<div align="center">

# NexusTech Solutions
## User Access Request Procedure

`NTS-IT-PRO-001` &nbsp;|&nbsp; `Version 1.0` &nbsp;|&nbsp; `March 14, 2026`

</div>

---

### 1. Purpose

This procedure makes sure every user account at NexusTech is created properly, with the right approvals, the right permissions, and a full record. It supports the AUP requirement that all system access must be formally authorised.

---

### 2. Scope

Use this procedure for:

- Creating any new employee or contractor account
- Changing or expanding access for an existing user
- All NexusTech systems including internal apps, cloud platforms, and the corporate network

---

### 3. Prerequisites

Before starting, the IT Helpdesk technician needs:

- [ ] Active login to the IT ticketing system
- [ ] Active Directory administrator rights
- [ ] Access to the Role-Based Access Control (RBAC) reference list

---

### 4. Step-by-Step Instructions

```
Step 1 → Receive the request
Step 2 → Verify manager approval
Step 3 → Create the account
Step 4 → Assign permissions
Step 5 → Notify user and manager
Step 6 → Close and document the ticket
```

---

#### Step 1 — Receive the Request

The user's direct manager submits a ticket through the IT ticketing system.

> Requests sent by email or Slack are **not accepted**.

The ticket must include:
- Full name of the user
- Job title and department
- Systems or applications requiring access
- Required start date
- Manager's name and approval confirmation

---

#### Step 2 — Verify Manager Approval

Confirm the ticket was submitted by the user's direct manager. If someone else submitted it, contact the manager directly to get written confirmation before continuing.

Tickets without confirmed manager approval are placed **on hold**. The submitter is notified of what is missing.

---

#### Step 3 — Create the Account

Once approval is confirmed, create the user account in Active Directory using the company's standard naming format. Set a temporary password that forces a reset at first login.

---

#### Step 4 — Assign Permissions

Use the RBAC reference list to assign the correct permissions for the user's job role. Follow the **principle of least privilege** — grant only the access the role requires. Nothing extra.

---

#### Step 5 — Notify the User and Manager

Send the temporary login credentials to the manager using secure internal messaging. The manager hands them to the new user directly. Add a confirmation note to the ticket.

---

#### Step 6 — Close and Document the Ticket

Update the ticket with:
- Date and time the account was created
- Systems and permission levels assigned
- Technician name
- Confirmation that manager approval was verified

Mark the ticket as **Resolved**.

---

### 5. Exceptions

| Situation | What to do |
|---|---|
| Incomplete ticket | Place on hold. Send the submitter a list of missing items. Do not proceed until all information is received. |
| Emergency access needed | A verbal approval from a Head of Department is acceptable as a temporary measure. A formal ticket must follow within **one business day**. Note the verbal approval in the record. |
| Uncertain permission level | Escalate to the Information Security Manager before provisioning. Do not guess. |

---

## Task 4 — Communication and Training Plan

### Overview

The AUP is approved. The job now is making sure every employee knows about it, understands it, and formally confirms they have read it, before the policy is enforced.

---

### Audiences and Messages

| Audience | Core Message | How it is delivered |
|---|---|---|
| **All Employees** | A new AUP is in place. Personal and prohibited use of company devices is now clearly defined. Non-compliance has consequences. | CEO announcement email, intranet posting, mandatory online training module |
| **IT and Security Staff** | The AUP is enforceable now. IT is responsible for monitoring and responding to violations. Know what to look for. | Team briefing by the Information Security Manager, updated internal runbook |
| **Managers and Team Leads** | Managers must make sure their teams complete training and sign the acknowledgement. They are the first point of contact for staff questions. | Dedicated manager briefing session, email with guidance document |

---

### Rollout Timeline

```
Week 1 ── CEO sends company-wide announcement. Policy published on intranet.
Week 2 ── Online training module launched. Manager briefing held. IT team briefed.
Week 3 ── Reminder sent to staff who have not completed training yet.
Week 4 ── Deadline. All staff must finish training and sign acknowledgement.
Week 5 ── Completion report reviewed. Non-completions escalated to HR.
```

---

### Acknowledgement Mechanism

Every employee must complete both steps before the Week 4 deadline:

1. **Finish the online training module** — completion is tracked automatically by the Learning Management System (LMS).
2. **Sign the acknowledgement form** — available at the end of the training module. This confirms the employee has read and understood the policy.

All records are stored by HR and the security team. Any non-completion after the deadline is flagged to the line manager and escalated to HR if not resolved within five business days.

---

## Task 5 — Policy Review Memo

---

<div align="center">

## MEMORANDUM

</div>

**To:** Information Security Steering Committee

**From:** Victoria Mbachu, Information Security Manager

**Date:** March 14, 2026

**Subject:** Acceptable Use Policy: Review and Proposed Updates

---

**Why this review is needed**

Two things have happened that require a formal review of the Acceptable Use Policy. The first is the migration of NexusTech's primary database to AWS. This is a major change to the company's technology environment that was not considered when the AUP was originally written. The policy needs to be updated to reflect how cloud infrastructure is now used and what rules apply to it. The second is the security incident where an employee transferred a sensitive document to a personal cloud storage account. This is a direct violation of the AUP. It shows that either the policy language is not clear enough, or that employees did not fully understand it. Both possibilities need to be looked at.

**The review process**

The review will start with a focused risk assessment on both trigger events. The IT team will be consulted on the details of the AWS migration. The incident report for the cloud storage event will be reviewed in full. The Compliance Officer will confirm whether either issue affects NexusTech's standing under ISO 27001 or SOC 2. Feedback from managers and staff will also be collected to find out whether the current AUP language on data handling is clear enough to be followed day-to-day.

**Proposed update**

The data handling section of the AUP needs to be strengthened. The current version says employees must not use personal cloud accounts for company data, but it does not list which cloud platforms are approved or how sensitive documents should be shared externally. The proposed update would name the approved platforms explicitly, ban personal accounts such as Google Drive and Dropbox for any company data, and point employees to the correct approved tool for all file sharing. This closes the gap that allowed the recent incident to happen and gives staff a clear, enforceable rule to follow.

---
