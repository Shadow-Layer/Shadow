---
kind: spec
title: "SHADOW Revised Architectural Model"
---

# SHADOW: Revised Architectural Model

**Response to Adversarial Critique**

---

## 1. Core Identity (Resolved)

### The Clarity

**SHADOW members operate under pseudonyms internally.**

When a member interacts with an external employer/client:
- Member reveals their SHADOW pseudonym ("I am 'Zenith' on SHADOW")
- SHADOW verifies the work that pseudonym completed
- Member's legal identity remains private (between member + SHADOW + any legal/tax authority)
- Employer can confirm: "Zenith completed X, Y, Z projects on SHADOW" ✓

**This resolves the Anonymous/Credible contradiction:**

| Entity | What They Know | Confidence |
|--------|---|---|
| SHADOW Collective | SHADOW pseudonym only ("Zenith") | Internal |
| External Employer | SHADOW pseudonym + verified work history | Public-facing |
| Legal/Tax Systems | Full legal identity + SHADOW activity | Restricted |
| Project Team | SHADOW pseudonym + collaboration record | Team-scoped |

**Key principle:** Anonymity is protection from the collective's external public exposure, not from all accountability.

---

## 2. Revenue Model (Resolved)

### No Automatic SHADOW Cut from Client Projects

**Default Model:**

```text
CLIENT PAYS TEAM LEADER
    ↓
TEAM LEADER DISTRIBUTES TO CONTRIBUTORS
    ↓
CONTRIBUTORS + TEAM LEADER RETAIN 100%
```

SHADOW does NOT automatically take a cut from client work.

### Optional SHADOW Revenue Share

**If a Team Leader/Project Voluntarily Opts Into SHADOW Commons:**

- Team Leader may choose to pass a portion of project revenue to SHADOW Commons
- This is optional, not mandatory
- In exchange, project receives:
  - Priority on Commons-managed resources (infrastructure, legal support, insurance)
  - Access to reputation system (portfolio credit)
  - Dispute arbitration
  - Professional liability protection

**Example:**

```text
Client pays $10,000 for project.

Option A: Team Leader keeps 100%
 → No SHADOW infrastructure support
 → Portfolio credit is unverified
 → No arbitration if disputes arise

Option B: Team Leader gives SHADOW 20% ($2,000)
 → SHADOW funds infrastructure, legal, arbitration
 → Portfolio is SHADOW-verified
 → SHADOW-mediated arbitration available
 → Professional liability insurance covers work
```

### SHADOW's Own Revenue Apps

**Only SHADOW Commons owns:**
- Housing Archive app
- Tenga Inventory POS
- Any apps explicitly built by Commons as corporate ventures

These generate subscription revenue that funds:
- Identity infrastructure
- Reputation system
- Arbitration/legal support
- Security and incident response
- Commons operations

---

## 3. Authority Model (Resolved)

### Three Clear Layers

**LAYER 1: Individual Member**
- Controls own participation
- Controls own time
- Can join/leave projects freely
- Can originate projects
- Negotiates own compensation
- Owns personal assets/IP created outside projects

**LAYER 2: Project**
- Team Leader (project originator) has operational sovereignty
- Can recruit, remove, direct work
- AUTHORITY BOUNDARY: Only within the project
- Cannot override member rights (contract, compensation, safety)
- Cannot claim ownership of pre-existing member IP
- Cannot force participation in non-project SHADOW activities

**LAYER 3: SHADOW Commons**
- Manages identity system
- Maintains reputation/portfolio infrastructure
- Arbitrates disputes (when both parties consent to arbitration)
- Enforces minimum security/compliance standards
- Runs Commons-owned apps
- Distributes revenue (if project opts in)
- AUTHORITY BOUNDARY: Cannot unilaterally control projects
- Cannot override project-level agreements
- Can audit for security/legal compliance only

### The Critical Separation

**Project Autonomy ≠ Commons Veto**

The Commons cannot:
- Redirect a project's revenue without consent
- Force a Team Leader to change project direction
- Unilaterally seize project IP
- Prevent a project from operating

The Commons CAN:
- Refuse infrastructure support if project violates security/legal standards
- Deny portfolio credit if project can't verify contributions
- Require SHADOW-verified identity for revenue projects
- Suspend a project if legal liability is imminent

---

## 4. Membership Architecture (Resolved)

### States

```
APPLICANT
    ↓
VERIFIED MEMBER (given SHADOW pseudonym)
    ↓
ACTIVE CONTRIBUTOR (participating in projects)
```

### Transitions

**Become a Member:**
1. Accept SHADOW Charter
2. Provide legal identity (verified by identity service, stored securely)
3. Choose SHADOW pseudonym
4. Accept Privacy/Confidentiality rules
5. Receive SHADOW member ID

**Leave SHADOW:**
- Member can withdraw at any time
- All project commitments remain binding (contractual)
- SHADOW retains reputation/portfolio data (historical record)
- Member can request data deletion (will comply with regulations; some data may be retained for legal/compliance)

**Suspension/Removal:**
- Grounds: fraud, serious misconduct, security breach, confidentiality violation, abuse of infrastructure
- Process: Commons investigation + written notice + right to appeal
- Appeal resolved by arbitration

---

## 5. Project System (Resolved)

### Project Types

**Type A: Portfolio Project**
- Created by member to build experience
- No external client
- Typically unpaid or volunteer
- SHADOW provides infrastructure + reputation credit
- Member retains all IP
- No Commons revenue share

**Type B: Revenue Project (Closed)**
- Client work by Team Leader + team
- Revenue goes to Team Leader, who distributes
- Optional Commons involvement (if Team Leader opts in for support)
- SHADOW may provide insurance, arbitration, verification
- IP owned per project agreement
- SHADOW takes % only if Team Leader voluntarily enrolls

**Type C: Commons Project**
- Created and operated by Commons
- Generates subscription revenue
- Members hired as contributors (with compensation agreements)
- SHADOW retains IP and revenue
- Used to fund Commons operations

### Project Charter

Every project defines:
- **Originator** (Project Team Leader)
- **Objective & Scope**
- **Team & Roles** (with names/pseudonyms)
- **Commitment Type** (volunteer, hourly, fixed-fee, revenue-share)
- **Compensation** (amount, schedule, conditions)
- **Ownership** (who owns IP; typically originator + contributors per agreement)
- **SHADOW Involvement** (none, infrastructure-only, revenue-share, arbitration)
- **Confidentiality** (project-public, SHADOW-internal, restricted)
- **Exit Clause** (how members leave; what they take)

---

## 6. Arbitration System (Resolved)

### Graduated Resolution

**Level 1: Direct Resolution**
Team Leader + contributor attempt to resolve
- Informal, fast
- No formal record required

**Level 2: Project Mediation**
- Third party (neutral SHADOW member) mediates
- Both parties agree to mediator
- Mediation is documented
- Binding if both parties accept

**Level 3: Commons Arbitration**
- Invoked when Level 2 fails or is inappropriate
- Arbitration council (3 members: 1 Commons representative, 1 chosen by each party)
- Hearing is documented
- Decision is binding on SHADOW members
- Arbitration costs paid by Commons (if Teams are in dispute) or by losing party

**External Legal**
- If arbitration fails or legal matter is criminal/severe, normal courts apply
- SHADOW does not prevent legal action

### What Arbitration Can Resolve

- Compensation disputes
- Portfolio credit disputes
- Intellectual property claims (between contributors/Team Leader)
- Misconduct allegations (harassment, theft, confidentiality breach)
- Contract interpretation

### What Arbitration Cannot Resolve

- Personal disputes unrelated to SHADOW work
- Project strategy disagreements (Team Leader decides)
- Member employment disputes (unless member was hired by SHADOW Commons)

---

## 7. Intellectual Property (Resolved)

### Default Rule

**IP created during a project belongs to whoever originated it, unless explicitly assigned.**

### Specific Models

**Portfolio Projects:**
- Creator retains IP
- SHADOW gets limited license to feature work in portfolio/reputation system
- IP attribution visible (pseudonym used)

**Revenue Projects:**
- Agreement determines ownership (typically: 40% Team Leader, 60% contributors split per agreement, or Project owns collectively)
- Team Leader negotiates with contributors before project starts
- Disputes go to arbitration

**Commons Projects:**
- SHADOW retains IP
- Contributors receive compensation per employment/contractor agreement
- Commons may open-source (at Commons discretion)

**Client Projects:**
- Client typically owns deliverables per contract
- Contributors own underlying tools/components unless client purchases those separately

### IP Registry

Every project creation includes IP assignment:
- Creator
- Contributors
- Ownership model selected
- SHADOW license scope
- Dispute mechanism

---

## 8. Financial Governance (Resolved)

### Account Types

**Member Account**
- Each member has SHADOW account
- Used to receive reputation credits, portfolio assignments
- No money held here (project funds transferred directly)

**Project Account**
- If project is revenue-generating (Type B or C)
- Receives client payments
- Team Leader or Commons distributes per agreement

**Commons Account**
- Holds revenue from Apps (housing archive, POS)
- Funds operations, arbitration, infrastructure

### Revenue Flow for Type B (Revenue Project with Commons Opt-In)

```text
CLIENT PAYS → PROJECT ACCOUNT
                ↓
            TEAM LEADER decides split
                ↓
            ┌───────┬──────────┬─────────┐
            ↓       ↓          ↓         ↓
         SELF    CONTRIB1  CONTRIB2  COMMONS
        (60%)     (15%)      (15%)     (10%)
```

**Key rule:** Unless explicitly agreed, SHADOW takes 0% automatically.

### Expenses

- Projects can request equipment, software, hosting from SHADOW Commons
- Commons evaluates based on:
  - Available budget
  - Strategic value
  - Contributor access (shared resources benefit multiple projects)
- Approval by Commons stewards
- Expense tracked and documented

---

## 9. Security & Privacy (Resolved)

### Identity Layers

```
LEGAL IDENTITY
(Legal name, passport, tax ID)
  - Stored encrypted
  - Accessed only: tax compliance, legal liability, contracts
  - Compartmentalised
  
SHADOW VERIFIED IDENTITY
(Verified member, pseudonym, email)
  - Internal SHADOW systems
  - Accessible to: Commons, arbiters, law enforcement (with warrant)
  - Used for: reputation, portfolio, access control
  
PROJECT IDENTITY
(Role in specific project, project-scoped pseudonym)
  - Accessible to: project team members
  - Used for: collaboration, work assignment, credit
  
PUBLIC IDENTITY
(SHADOW pseudonym, public portfolio)
  - Visible to: external employers, clients
  - Shows: work history, verified projects, skills
  - Does not show: legal identity, email, payment details
```

### Access Control

| Who | Can See | Cannot See |
|-----|---------|------------|
| Member Themselves | All layers | Other members' legal identity |
| Project Team | Project identity + role | Legal identity |
| Commons (operations) | Verified identity | Legal identity (unless needed for legal/tax) |
| External Clients | Public identity + work done | Any personal information |
| Law Enforcement | Legal identity (with warrant) | - |

---

## 10. Failure Scenarios (Addressed)

### Scenario B: Team Leader Becomes Abusive

**Architecture response:**

1. **Immediate:** Member reports to Commons via formal complaint
2. **Investigation:** Commons appoints arbitration panel (independent from Team Leader)
3. **Hearing:** Team Leader + member both present evidence
4. **Decision:** Arbitration panel decides:
   - Was abuse substantiated?
   - What remedies apply? (portfolio credit, compensation, removal)
5. **Enforcement:** If Team Leader refuses, Commons:
   - Removes project from reputation system
   - Suspends Team Leader from future projects
   - Bars access to Commons infrastructure

**Preventive:** Project requires contributor records (immutable log of who did what). Team Leader cannot later claim credit for work they didn't do.

---

### Scenario K: Commons Attempts Authority Seizure

**Architecture response:**

1. **Boundary:** Commons can only control Commons-owned infrastructure and apps
2. **Autonomy:** Projects operating independently don't need Commons permission to exist
3. **Check:** If Commons attempts to redirect project revenue or seize IP:
   - Project can opt out entirely
   - No longer uses SHADOW infrastructure
   - Reputation system becomes project's own responsibility
   - SHADOW has no leverage
4. **Escalation:** Members vote on Commons decisions (quarterly assembly)
   - Can remove Commons stewards if they overreach
   - Can revise Commons charter

---

### Scenario M: Project Becomes Legally Controversial

**Architecture response:**

1. **Separation:** SHADOW itself doesn't own the project (unless Commons Project)
2. **Liability:** Team Leader + contributors are liable, not SHADOW as entity
3. **Protection:** If project opted into Commons (paid the revenue share):
   - SHADOW provides legal defense fund
   - Professional insurance covers work
   - SHADOW reputation protected (project is independent venture)
4. **Consequence:** If project exits Commons:
   - Loses insurance coverage
   - Loses dispute arbitration
   - Operates independently with full liability risk

---

## 11. Scalability (Architecture)

### Stage 1: 5-15 members
- Decisions made by consensus
- Commons is direct (founders make calls)
- All members know each other
- Arbitration is informal/mediation

### Stage 2: 15-50 members
- Commons formalizes into steward team (3-5 people)
- Member council emerges (representatives from active projects)
- Arbitration becomes formal process
- Documentation becomes critical (decisions recorded, published)

### Stage 3: 50-250 members
- Member Assembly quarterly (major decisions, Commons accountability)
- Arbitration panel becomes elected/appointed (not Commons-only)
- Project clusters emerge (groups of related projects coordinate)
- Commons focuses on infrastructure, not project management

### Stage 4: 250+ members
- Fractal governance: clusters have local steering, escalate to Commons
- Professional arbitration pool (paid role)
- Project autonomy increases (less Commons oversight needed)
- Reputation system becomes algorithmic (automated verification)

---

## 12. Resilience Architecture (Resolved)

### No Single Point of Failure

**Identity System:**
- Distributed across multiple secure locations
- 3-of-5 multi-signature for critical changes
- Member can request data export anytime
- Regular backups in secure vaults

**Reputation System:**
- Immutable ledger (blockchain-like: each entry signed, timestamped)
- Cryptographically verified
- Publicly auditable (members can verify their own records)
- Survives Commons infrastructure failure

**Commons Succession:**
- No individual can be indispensable
- Every function has backup personnel
- Keys held by rotating trustees (external to Commons)
- Succession documented in bylaws
- Regular emergency drills

**Project Independence:**
- If Commons disappears, projects continue
- Reputation data can be exported and verified
- No project is locked into SHADOW dependency

---

## 13. Legal Architecture (Flagged)

### This requires jurisdiction-specific legal work (flagged for immediate consultation):

1. **Entity structure** — Should SHADOW be UK cooperative? Malta entity? Multiple local entities in each jurisdiction?
2. **Anonymity + regulation** — Tax authorities, data protection agencies, employment law
3. **Liability** — Who is liable when a SHADOW member commits fraud?
4. **Intellectual property** — How do IP ownership transfers work across jurisdictions?

**Current assumption:** SHADOW operates as a UK Cooperative (or equivalent) with:
- Formal bylaws
- Member voting rights
- Democratic Commons governance
- Legal accountability

---

## 14. Success Criteria (Revised)

✓ A 5-person founding Commons can bootstrap SHADOW  
✓ Projects operate independently without asking central permission  
✓ Members contribute under various commitment types (clear agreements)  
✓ Clear arbitration when conflicts arise  
✓ SHADOW revenue apps (housing, POS) generate subscription income  
✓ Individual contributors build verifiable portfolios with pseudonyms  
✓ Scaling to 250+ members without proportional Commons overhead  
✓ Survival if a founder disappears (succession plan exists)  
✓ Legal viability across primary jurisdiction (UK cooperative)  
✓ Project IP ownership is explicit and dispute-resolvable  

---

## Summary of Changes

| Original Problem | Revised Architecture |
|---|---|
| Anonymous + Credible contradiction | Pseudonymous internally, identifiable to external clients, legal identity hidden from collective |
| Decentralised + Revenue concentration | SHADOW takes 0% by default; opt-in revenue share only for projects requesting Commons support |
| No enforcement of protections | Formal arbitration system with enforcement and appeal rights |
| Undefined IP ownership | Every project specifies ownership model at creation; IP registry tracks assignments |
| Authority unlimited | Commons boundary: only controls Commons infrastructure + apps; cannot unilaterally seize projects |
| Regulatory chaos | Flagged for legal consultation; assumes UK cooperative structure |
| Undersized team | Initial 5-person Commons supplemented by member volunteers; expands with revenue |
| No resilience | Multi-signature infrastructure, distributed reputation, succession plan, project independence |

