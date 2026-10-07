---
kind: spec
title: "SHADOW Parts VI–XIV: Complete Operating System (Consolidated)"
---

# SHADOW Operating System — Parts VI–XIV

**Consolidated Implementation Guide**

---

# PART VI: ECONOMIC SYSTEM

## 1. Commitment Types

| Type | Payment | Ownership | Duration | Termination |
|------|---------|-----------|----------|-------------|
| **Volunteer** | None | IP per agreement | Flexible | Immediate notice |
| **Hourly** | $/hour | None (work-for-hire) | Flexible | 2 weeks notice |
| **Fixed-Fee** | $ total | None | Project-scoped | Per deliverable |
| **Revenue-Share** | % of revenue | Equity in outcomes | Duration of project | Per agreement |
| **Equity** | Delayed (upside) | Ownership stake | Long-term | Vesting schedule |
| **Fellowship** | Stipend | Special arrangement | Fixed term | Per agreement |

**Key rule:** Commitment type MUST be explicit before work begins.

## 2. Compensation Model

**Revenue Projects (with client payment):**

```
CLIENT PAYS $10,000
    ↓
TEAM LEADER receives $10,000
    ↓
PER AGREEMENT, splits to:
    - Self (Team Leader): $3,000
    - Contributor A: $4,000
    - Contributor B: $2,500
    - Commons (optional): $500 (if opted in)
```

**Volunteer Projects:**

```
NO CLIENT PAYMENT
    ↓
CONTRIBUTORS build portfolio
    ↓
OPTIONAL: Commons provides
    - Hosting
    - Reputation system
    - Support
```

**Commons Projects:**

```
SUBSCRIPTION REVENUE: $5,000/month
    ↓
COMMONS PAYS contributors:
    - Salary/contractor fees
    - Bonus from profitability
    ↓
REST funds Commons operations
    - Infrastructure
    - Arbitration
    - Identity system
    - Growth
```

## 3. Financial Governance

**Team Leaders may:**
- Negotiate compensation with contributors
- Allocate project budget
- Approve expenses (within project authority)

**Team Leaders may NOT:**
- Take cuts without agreed terms
- Pay late without cause
- Reduce pay mid-project (without consent)
- Hide financial information

**Commons may:**
- Request financial transparency (for revenue projects)
- Audit project finances (if misconduct suspected)
- Help resolve payment disputes
- Take Commons revenue-share (if agreed)

**Commons may NOT:**
- Seize project revenue
- Dictate compensation
- Take more than agreed %
- Reduce contributor pay

## 4. Expenses & Resource Requests

**Project can request from Commons:**

1. **Infrastructure** — Hosting, domain, storage, database
2. **Software** — Licenses, tools, platforms
3. **Equipment** — Rare (usually not provided)
4. **Services** — Legal review, design consultation
5. **Funding** — Budget for external contractors, tools

**Process:**
1. Team Leader submits resource request
2. Commons reviews:
   - Budget availability
   - Strategic value
   - Resource sharing potential
3. Approved or denied (with reason)
4. If approved: resource allocated; cost tracked

**Principle:** Shared resources benefit multiple projects; Commons invests strategically.

---

# PART VII: LEGAL & INSTITUTIONAL SYSTEM

## 1. Entity Structure

**SHADOW operates as one or more legal entities.**

**Recommended (jurisdiction-specific legal advice required):**

- **UK:** Cooperative Society or Community Interest Company (CIC)
- **US:** B-Corp or Benefit Corporation
- **EU:** Social Cooperative or Association
- **International:** Multiple local entities coordinating

**Key principle:** Entity exists to serve SHADOW's mission, not to enrich founders.

## 2. Contracts & Agreements

**SHADOW uses templates for:**

| Agreement | Between | Purpose |
|-----------|---------|---------|
| Member Agreement | SHADOW ↔ Member | Membership terms, privacy, conduct |
| Contributor Agreement | Project ↔ Contributor | Work terms, compensation, IP |
| Project Charter | Team Leader ↔ Team | Project governance |
| Client Contract | Project ↔ Client | Deliverables, payment, liability |
| Team Leader Charter | Commons ↔ Team Leader | Leadership responsibilities |
| Commons Bylaw | SHADOW | Governance rules |
| Privacy Policy | SHADOW ↔ External | Data handling |
| Code of Conduct | SHADOW | Community standards |

## 3. Intellectual Property

**Default rule:** Creator owns, unless contract specifies otherwise.

**Portfolio projects:** Contributor retains IP; SHADOW gets license to feature in portfolio.

**Revenue projects:** Per agreement (typically Team Leader + contributors split ownership; client may own deliverable).

**Commons projects:** SHADOW retains IP and revenue.

**Pre-existing IP:** Contributors bring their own tools/libraries; project gets license to use.

**Disputes:** Arbitration panel decides ownership based on project agreement and contribution records.

## 4. External Relationships

**SHADOW represents as:**

- A decentralised collective of professionals
- Operating under shared governance
- Individual projects managed by Team Leaders
- Individual members contribute voluntarily

**SHADOW does NOT:**

- Claim to be a company (unless legally structured as one)
- Guarantee individual member identities
- Accept liability for anonymous contributors (unless insured)
- Make promises about member availability

---

# PART VIII: SECURITY & PRIVACY

## 1. Information Classification

| Level | Audience | Protection | Retention |
|-------|----------|-----------|-----------|
| **PUBLIC** | Anyone | None | Permanent (public record) |
| **INTERNAL** | SHADOW members | Access control | 1 year (unless legal hold) |
| **PROJECT-CONF** | Project team | Encryption | Project duration + 90 days |
| **RESTRICTED** | Authorized only | Strong encryption, audit log | Per regulation/contract |

## 2. Access Control

**Identity verification:** 2FA recommended; passwords strong (12+ chars); no credential sharing.

**Role-based:** Each member has minimal access needed for their role.

**Audit logging:** All access to sensitive data is logged; annual review.

**Revocation:** Access removed immediately when member leaves project/SHADOW.

## 3. Data Protection (GDPR Compliance)

**SHADOW respects:**

- Right to access personal data
- Right to data portability (export)
- Right to correction (fix inaccurate data)
- Right to deletion (with exceptions for legal/contractual holds)
- Right to privacy (minimal data collection)

**Mechanisms:**

- Data deletion upon request (30 days)
- Retention schedule (data doesn't persist longer than needed)
- Breach notification (within 72 hours if data exposed)
- Privacy impact assessment (annually)

## 4. Incident Response

**Security breach response:**

1. **Immediate:** Isolate affected systems; prevent further access
2. **Assess:** Determine scope and severity
3. **Notify:** Affected members within 24 hours
4. **Investigate:** Root cause analysis
5. **Remediate:** Fix vulnerabilities
6. **Report:** Public incident report (anonymised details)
7. **Prevent:** Implement safeguards to prevent recurrence

---

# PART IX: OPERATIONS

## 1. Documentation Standards

**Every project maintains:**

- Project Charter (governance)
- Contribution records (who did what)
- Decision log (major decisions)
- Meeting notes (if applicable)
- Risk register (known issues/risks)
- Lessons learned (postmortem)

**Commons maintains:**

- Governance decisions (logged, published)
- Financial reports (quarterly)
- Arbitration outcomes (anonymised)
- Member records (audit trail)
- Incident reports (summary log)

**Retention:** Minimum 7 years (for legal/tax compliance); reputation data permanent.

## 2. Communications

**Official communications from:**

- **Team Leaders:** Represent only their projects
- **Commons:** Represent SHADOW-wide matters
- **Members:** Represent themselves (not SHADOW)

**Channels:**

- Email (official, persistent record)
- SHADOW platform (access-controlled)
- Public website (external communication)

**No member can claim to represent SHADOW without authorization.**

## 3. Meetings & Decision-Making

**Synchronous (real-time):**

- Project team meetings (per project need)
- Commons coordination (monthly)
- Member assembly (quarterly, at scale)

**Asynchronous:**

- Decision log updates (within 48 hours)
- Member notifications (within 24 hours)
- Arbitration decisions (within 30 days)

**Quorum:** 50% for project decisions; 30% for Commons; 50% for Member Assembly.

---

# PART X: FAILURE & RESILIENCE

## 1. Continuity Planning

**Succession for every critical role:**

- Team Leader → Designated successor
- Commons steward → Rotational team
- Member assembly rep → Alternate
- Infrastructure admin → Cross-trained backup

## 2. Disaster Recovery

**If Commons is compromised:**
- Identity data is encrypted (safe even if leaked)
- Reputation data is distributed (can be reconstructed)
- Projects continue independently (don't depend on Commons)

**If infrastructure fails:**
- Backup systems activate within 4 hours
- Member data is recoverable
- Project work is not lost (version control, backups)

**If SHADOW shuts down:**
- Member reputation data can be exported
- Projects become independent entities
- IP reverts to defined owners

## 3. Scenario Testing

**Regular chaos drills:**

- Founders absent for a week; system must function
- Arbitration needed with no Commons steward
- Reputational crisis; how does SHADOW respond
- Legal threat; escalation procedure tested

---

# PART XI: SCALABILITY

## Stage Progression

| Stage | Members | Governance | Decision-making | Infrastructure |
|-------|---------|-----------|---|---|
| **1** | 5–15 | Consensus | Direct | Minimal |
| **2** | 15–50 | Stewards | Representatives | Formal |
| **3** | 50–250 | Council | Assembly | Professional |
| **4** | 250–1,000 | Board + Assembly | Voting + appeals | Distributed |
| **5** | 1,000+ | Federation | Regional + global | Decentralized |

**Key:** Governance SCALES without RECREATING hierarchy.

---

# PART XII: DIGITAL ARCHITECTURE

## Data Model

**Core entities:**

```
Member ← → Pseudonym (SHADOW ID)
Member ← → Legal Identity (encrypted)
Member ← → Projects (participation)
Project ← → Team Leader (owner)
Project ← → Contributors (team)
Project ← → Charter (governance)
Contribution ← → Reputation (portfolio)
Reputation ← → Verification (audit trail)
Financial Transaction ← → Project/Member
Dispute ← → Arbitration (resolution)
```

## Systems Needed

| System | Purpose | Requirements |
|--------|---------|---|
| **Identity** | Pseudonym + legal mapping | Encrypted, secure, auditable |
| **Project Mgmt** | Charter, team, timeline | Accessible, searchable |
| **Reputation** | Portfolio building | Permanent, verifiable, portable |
| **Finance** | Payment tracking | Transparent, auditable |
| **Arbitration** | Dispute resolution | Confidential, documented |
| **Communication** | Async updates | Archived, searchable |
| **Governance** | Decision logging | Public, timestamped |

## Technology Recommendations

- **Identity:** Purpose-built IAM system or Keycloak
- **Project Mgmt:** Open-source (Taiga, OpenProject) or custom
- **Reputation:** Blockchain-like ledger (verifiable but not necessarily blockchain)
- **Finance:** Stripe or similar for payments; internal ledger
- **Arbitration:** Confidential wiki + email workflow
- **Communication:** Email + intranet (not centralized chat)
- **Governance:** GitHub Wiki or Notion for transparency

---

# PART XIII: DOCUMENT LIBRARY

**Required documents:**

```
GOVERNANCE/
  - SHADOW Charter
  - Membership Agreement
  - Member Handbook
  - Code of Conduct
  - Privacy Policy
  - Identity Policy

PROJECTS/
  - Project Charter Template
  - Contributor Agreement Template
  - Team Leader Charter
  - Project Status Template

OPERATIONS/
  - Decision Log Format
  - Meeting Notes Template
  - Financial Report Template
  - Incident Report Template

ARBITRATION/
  - Arbitration Policy
  - Dispute Escalation Process
  - Appeal Procedure

POLICIES/
  - Information Classification
  - Data Retention
  - Access Control
  - Security Incident Response
  - Conflict of Interest
```

---

# PART XIV: IMPLEMENTATION ROADMAP

## Phase 1: Foundation (Months 1–2)

**Goal:** Operational basics in place.

**Tasks:**
1. Draft SHADOW Charter and Bylaws
2. Set up legal entity (cooperative/CIC)
3. Create identity verification process
4. Establish basic project charter template
5. Launch Commons as 5-person team
6. Recruit first 5–10 members

**Success:** SHADOW operates with founding team + first projects.

## Phase 2: Infrastructure (Months 3–4)

**Goal:** Systems in place for scale.

**Tasks:**
1. Deploy identity management system
2. Launch project management platform
3. Create reputation/portfolio system
4. Set up arbitration process
5. Publish comprehensive handbook
6. Grow to 15–30 members

**Success:** Multiple projects running; infrastructure robust.

## Phase 3: Governance (Months 5–6)

**Goal:** Formal governance structures.

**Tasks:**
1. Establish Member Assembly (if Stage 2 reached)
2. Formalize Arbitration Panel
3. Create Cluster Coordinators (if needed)
4. Publish Decision Logs publicly
5. Conduct first governance review
6. Grow to 30–50 members

**Success:** Governance is formal; decisions are transparent.

## Phase 4: Revenue Apps (Months 7–12)

**Goal:** Core revenue apps operational.

**Tasks:**
1. Launch Housing Archive (subscription SaaS)
2. Launch Tenga Inventory POS (subscription SaaS)
3. Recruit members for Commons projects
4. Establish revenue distribution model
5. Create financial reporting
6. Grow to 50–100 members

**Success:** SHADOW generates revenue; Commons operations sustainable.

## Phase 5: Scale (Months 13+)

**Goal:** Scaled operations without losing decentralisation.

**Tasks:**
1. Add project clusters as scale warrants
2. Transition Commons to professional staff (if needed)
3. Implement federated governance (if crossing region/jurisdiction)
4. Grow to 100–250+ members
5. Expand revenue apps or launch new ones
6. Regular scaling audits (governance still decentralised?)

**Success:** SHADOW operates at scale with distributed authority intact.

---

## Critical Path Dependencies

```
PHASE 1 FOUNDATION
  ├─ Legal Entity Setup
  │   ├─ Charter Draft
  │   └─ Bylaws Written
  │
  ├─ Identity System
  │   ├─ Verification Process
  │   └─ Pseudonym Registry
  │
  └─ First Projects
      ├─ Charter Templates
      ├─ Contributor Agreements
      └─ Project Launch

PHASE 2 INFRASTRUCTURE
  ├─ Project Management Tool
  ├─ Identity Management System
  ├─ Reputation System
  └─ Arbitration Framework

PHASE 3 GOVERNANCE
  ├─ Member Assembly (if Stage 2+)
  ├─ Arbitration Panel
  └─ Published Decisions

PHASE 4 REVENUE
  ├─ Housing Archive Launch
  ├─ POS System Launch
  ├─ Payment Processing
  └─ Revenue Distribution

PHASE 5 SCALE
  ├─ Clustering System
  ├─ Federated Governance
  ├─ Regional Operations
  └─ Multi-jurisdiction Legal
```

---

## Quick-Start Checklist

**Before first member joins:**

- [ ] Charter written and accepted by founders
- [ ] Legal entity established
- [ ] Privacy policy and identity verification process documented
- [ ] Project charter template ready
- [ ] Contributor agreement template ready
- [ ] Code of Conduct published
- [ ] Arbitration process documented
- [ ] Member handbook written
- [ ] Basic project management tool set up
- [ ] Reputation system framework designed

**Before 10 members:**

- [ ] Identity verification system operational
- [ ] Project management tool tested
- [ ] First 2–3 projects launched
- [ ] Arbitration process tested (if conflict arises)
- [ ] Financial tracking in place
- [ ] Decision logs published monthly

**Before 50 members:**

- [ ] Formal Member Assembly structure
- [ ] Arbitration Panel trained and operational
- [ ] Cluster coordinators identified
- [ ] Revenue apps in development or launched
- [ ] Governance review completed
- [ ] Annual audit planned

**Before 250 members:**

- [ ] Professional Commons staff hired
- [ ] Regional clustering operational
- [ ] Federated governance if needed
- [ ] Revenue apps generating income
- [ ] Scalability audit completed

---

## Success Metrics

**Month 3:**
- 15+ verified members
- 3+ active projects
- 0 critical infrastructure issues
- 100% Charter compliance

**Month 6:**
- 30+ verified members
- 8+ active projects
- 1 arbitration completed (if needed)
- Revenue apps in development

**Month 12:**
- 80–100 verified members
- 20+ active projects
- Revenue apps generating £5k+/month
- 0 misconduct escalations to external legal

**Month 24:**
- 200+ verified members
- 50+ active projects
- Revenue apps generating £20k+/month
- Scaling to 250+ members planned

---

## Risks & Mitigations

| Risk | Mitigation |
|------|-----------|
| Founder burnout | Hire Commons staff by month 4; rotate stewards |
| Governance paralysis | Clear decision thresholds; defaults (Team Leader decides) |
| Revenue app failure | Diversify revenue; membership fees if needed |
| Misconduct crisis | Strong arbitration; quick response; transparency |
| Legal liability | Insurance; legal counsel; clear contracts |
| Infrastructure failure | Backup systems; distributed reputation |
| Fragmentation (too many clusters) | Clear governance boundaries; quarterly coordination |

---

## Decision Log (Implementation)

| Decision | Rationale | Status |
|----------|-----------|--------|
| Cooperative structure (not company) | Enables member control; aligns with principles | FINAL |
| 5-person founding Commons | Balances expertise + agility | FINAL |
| Phase-based scaling | Prevents over-complication early | FINAL |
| Revenue apps as Commons projects | Funds operations; demonstrates viability | FINAL |
| Quarterly Member Assembly | Governance oversight without bureaucracy | FINAL |

---

## What Happens Now

This comprehensive operating system is ready for implementation.

**Next step:** Share with founding team; get alignment on principles.

**Then:** Begin Phase 1 (Foundation) immediately.

**Key insight:** This system will evolve as SHADOW grows. Use these principles to guide evolution, not to prevent it.

