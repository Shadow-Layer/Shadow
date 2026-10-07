---
kind: spec
title: "SHADOW Part III: Governance Framework"
---

# SHADOW Operating System — Part III: Governance Framework

**Authority, Decision-Making, Delegation & Constitutional Mechanisms**

---

## 1. Authority Model

### 1.1 Definition of Authority

**Authority** is the legitimate right to make a binding decision.

SHADOW distinguishes between:

- **Operational authority** — right to direct work within a defined scope (Team Leader)
- **Governance authority** — right to make decisions about rules and structures (Commons, Assembly)
- **Arbitral authority** — right to resolve disputes (Arbitration Panel)
- **Financial authority** — right to allocate and spend money (Team Leader for projects; Commons for Commons funds)
- **Structural authority** — right to change governance rules (Member Assembly)

**Key principle:** Authority is contextual and bounded, never absolute.

### 1.2 Authority Hierarchy

No single person has authority over everything. Instead, SHADOW uses **nested, bounded authority domains**:

```
Level 1: Individual Authority
├─ Controls own time, participation, personal assets
├─ Cannot: Force others to work, override Commons rules, claim false authority
│
Level 2: Team Leader Authority (Project)
├─ Controls project direction, team recruitment, internal decisions
├─ Bounded by: Project charter, SHADOW Core Rules, member contracts, legal obligations
├─ Cannot: Override member rights, seize pre-existing IP, operate outside law
│
Level 3: Commons Authority
├─ Controls identity, reputation, shared infrastructure, arbitration
├─ Bounded by: Written policies, member appeal rights, financial limits
├─ Cannot: Seize project revenue, control projects, override project charters
│
Level 4: Member Assembly Authority (Stage 3+)
├─ Controls governance rules, Commons oversight, constitutional changes
├─ Bounded by: Written bylaws, super-majority requirements
├─ Cannot: Override individual rights, violate member agreements unilaterally
```

---

## 2. Decision-Making Framework

### 2.1 Decision Types

**Type A: Unilateral Decisions** (Individual makes decision alone)

**Example:** "I'm leaving this project" / "I'm working this week"

**Authority:** Individual only

**Requirement:** None. Autonomy protected.

---

**Type B: Project-Level Decisions** (Team Leader decides)

**Examples:**
- Project objective and scope
- Team recruitment and removal
- Technical approach
- Work assignment and prioritization
- Internal project rules
- Project-specific compensation

**Authority:** Team Leader (after consulting team, if desired)

**Requirement:** Project Charter defines these decisions belong to Team Leader

**Constraint:** Cannot override member contracts or SHADOW Core Rules

---

**Type C: Project Governance Decisions** (Team + Team Leader consensus needed)

**Examples:**
- Changes to project charter
- Major scope expansions
- Ownership or IP assignment changes
- Long-term commitments beyond original agreement
- Project pause or closure

**Authority:** Team Leader proposes; team ratifies (can override with 70% team vote)

**Requirement:** Written amendment to Project Charter

**Process:** 
1. Team Leader proposes change
2. Team has 7 days to raise objections
3. If team consensus not reached, escalate to arbitration

---

**Type D: Commons Operational Decisions** (Commons Stewards decide)

**Examples:**
- Routine infrastructure maintenance
- Access control decisions
- Normal budget expenditures
- Project status updates
- Member onboarding/verification

**Authority:** Commons Stewards (by consensus or majority vote)

**Requirement:** Documented decision

**Constraint:** Cannot exceed delegated authority limits

---

**Type E: Commons Policy Decisions** (Commons proposes, Member Assembly approves at Stage 3+)

**Examples:**
- New policies affecting all members
- Major budget changes (>20% reallocation)
- Governance structural changes
- Member fees or Commons revenue-share percentages
- Significant infrastructure decisions

**Authority:** Commons Stewards propose; Member Assembly votes (simple majority)

**Requirement:** 2-week public notice before vote

**Constraint:** Cannot contradict SHADOW Charter

---

**Type F: Constitutional Decisions** (Member Assembly only)

**Examples:**
- Charter amendments
- Governance structure changes
- Removal of Commons leadership
- Major directional changes

**Authority:** Member Assembly (super-majority: 2/3 vote)

**Requirement:** 30-day public notice; written justification; special assembly

**Constraint:** Cannot violate Core Principles

---

### 2.2 Decision Escalation Path

```
Individual Decision
        ↓ (if contested by Team Leader)
Team Leader proposes override
        ↓ (if team disagrees)
Arbitration Panel
        ↓ (if legal issue)
External legal authority
```

```
Team Leader Decision
        ↓ (if contested by team member)
Team mediation/discussion
        ↓ (if unresolved)
Commons arbitration
        ↓ (if decision violated rights)
Arbitration Panel reverses
        ↓ (if core principle violated)
Member Assembly appeal
```

```
Commons Operational Decision
        ↓ (if affects member directly)
Commons review
        ↓ (if exceeds delegated authority)
Member Assembly override
```

```
Commons Policy Decision
        ↓ (if members object)
Member Assembly vote
        ↓ (if contradicts Charter)
Constitutional review
```

---

## 3. Responsibility & Accountability

### 3.1 Individual Responsibility

**A member is responsible for:**

- Fulfilling agreed project commitments
- Respecting project confidentiality and rules
- Following SHADOW security and privacy policies
- Treating others with respect (Code of Conduct)
- Reporting serious misconduct
- Paying attention to SHADOW communications

**A member is NOT responsible for:**
- Other members' work
- Projects they don't participate in
- SHADOW's overall success
- Other members' personal issues

**Accountability mechanism:** Arbitration + sanctions (suspension, removal)

---

### 3.2 Team Leader Responsibility

**A Team Leader is responsible for:**

- Defining and communicating project objectives
- Ensuring team has resources and support
- Treating contributors fairly and respectfully
- Maintaining contributor records
- Fulfilling project deadlines and deliverables
- Adhering to project charter
- Handling sensitive information securely
- Addressing misconduct within project
- Reporting critical issues to Commons

**A Team Leader is NOT responsible for:**
- Other projects' success
- SHADOW's strategic direction
- Members' personal lives
- Members who voluntarily leave

**Accountability mechanism:** Arbitration + sanctions (project removal, Commons sanctions)

**Authority limits:**
- Cannot operate outside project scope
- Cannot override SHADOW Core Rules
- Cannot claim false authority
- Cannot retaliate against members reporting misconduct

---

### 3.3 Commons Steward Responsibility

**Commons Stewards are collectively responsible for:**

- Maintaining identity infrastructure
- Operating shared technical systems
- Arbitrating disputes fairly
- Enforcing SHADOW policies
- Protecting member privacy and security
- Distributing reputation credit accurately
- Managing Commons finances responsibly
- Communicating decisions transparently
- Responding to member concerns

**Commons Stewards are NOT responsible for:**
- Managing individual projects
- Supervising all member work
- Guaranteeing project success
- Controlling project direction

**Accountability mechanism:** Member Assembly can remove stewards; quarterly review; term limits

**Authority limits:**
- Cannot exceed written policy
- Cannot take action affecting members without process
- Cannot use Commons position for personal gain
- Cannot retaliate against members raising concerns

---

### 3.4 Accountability Cycle

For every decision-maker:

```
Decision → Document → Implement → Monitor → Review → Adjust
              ↓           ↓         ↓        ↓       ↓
           Public       Notify   Execute   Audit   Iterate
           record      affected  per       by      based on
                       parties   plan      members feedback
```

---

## 4. Delegation Framework

### 4.1 What Can Be Delegated

**Team Leaders can delegate:**

- Specific work tasks (to contributors)
- Technical decisions (to technical leads)
- Team scheduling (to designated coordinator)
- Project communication (to designated spokesperson)
- BUT NOT: Overall project authority, final approval on major decisions

**Commons can delegate:**

- Infrastructure operations (to technical team)
- Member onboarding (to dedicated steward)
- Reputation verification (to designated reviewers)
- Dispute investigation (to arbitration panel)
- BUT NOT: Policy decisions, final arbitration authority, governance

**Delegator remains accountable** for delegated work.

### 4.2 Delegation Rules

1. **Explicit:** Delegation must be documented and acknowledged
2. **Bounded:** Scope is clearly defined
3. **Revocable:** Delegator can revoke at any time
4. **Transparent:** Affected parties know who has delegated authority
5. **Accountable:** Delegate reports back to delegator; delegator remains responsible

---

## 5. Consent & Veto

### 5.1 Informed Consent

**Consent in SHADOW requires:**

1. **Information** — Affected party understands what is being decided
2. **Time** — Adequate time to consider (minimum 7 days for major decisions)
3. **Ability to object** — Clear process to raise concerns
4. **Binding power** — Objection can halt decision (if valid)
5. **Recourse** — If consent is violated, arbitration is available

### 5.2 Who Has Veto Rights

| Situation | Who Can Veto |
|-----------|---|
| Project charter change | Team (by 70% vote); member (unilateral if contract violated) |
| Major policy | Member Assembly (by 50%+1) overrules Commons |
| Governance change | Member Assembly (by 2/3) required for constitutional changes |
| Individual contract | Individual member (by withdrawing consent) |
| Commons decision | Member Assembly (by majority) can overturn |

**Veto is NOT absolute:**
- Veto can be challenged via arbitration
- Veto cannot be used to prevent all change
- Repeated vetoes without cause can trigger escalation

### 5.3 Consensual Arbitration

**Arbitration requires consent:**

- Both parties must agree to arbitration
- If one party refuses, escalate to formal dispute process
- Arbitration is binding only if both parties agreed in advance

---

## 6. Conflict Resolution Hierarchy

### Level 1: Direct Resolution (7 days)

**Direct negotiation between parties**

- No formal process
- Goal: mutual understanding and solution
- If successful: document agreement, move forward
- If unsuccessful: escalate to Level 2

**Required:** Good-faith effort to resolve

---

### Level 2: Project Mediation (14 days)

**Third-party neutral mediates (often Cluster Coordinator)**

- Mediator is mutually acceptable
- Mediator has no stake in outcome
- Hearing is documented
- Goal: agreement on solution
- If successful: binding on both parties
- If unsuccessful: escalate to Level 3

**Required:** Both parties agree to mediation

---

### Level 3: Commons Arbitration (30 days)

**Formal arbitration panel decides**

**Panel composition:**
- 3 arbiters (at Stage 1, 2 can be Commons stewards + 1 member)
- At Stage 3+: 1 Commons representative, 1 chosen by each party
- Arbiters must have no conflict of interest

**Process:**
1. Formal complaint filed with Commons
2. 10-day period for response
3. Hearing held (both parties present evidence)
4. 5-day deliberation period
5. Decision issued and documented
6. 7-day appeal period

**Outcome:**
- Binding decision on SHADOW members
- Enforceable through Commons (member suspension, removal)
- May require financial compensation
- May require project changes

**Grounds for arbitration:**
- Breach of project charter
- Unpaid compensation
- Portfolio credit disputes
- IP ownership disputes
- Harassment or misconduct
- Breach of confidentiality

---

### Level 4: Appeals (14 days)

**Member Assembly reviews arbitration decision**

- Available if decision violated member rights
- Requires written appeal with new evidence
- Assembly votes (simple majority) to uphold, overturn, or remand
- Binding final decision within SHADOW

---

### Level 5: External Legal Process

**Normal legal system**

- Available for criminal matters, severe violations
- SHADOW does not prevent legal action
- Members may sue each other or Commons in courts
- SHADOW's arbitration decisions are evidence but not binding in court

---

## 7. Enforcement Mechanisms

### 7.1 Remedies for Violations

**For contract breach:**
- Specific performance (make person fulfill contract)
- Financial compensation (reimburse for damages)
- Project removal (remove person from project)
- Public notice (reputation impact)

**For misconduct:**
- Written warning (first offense, minor)
- Project suspension (temporary removal from project)
- Project removal (permanent expulsion from project)
- SHADOW suspension (temporary loss of SHADOW privileges)
- SHADOW removal (permanent expulsion from SHADOW)

**For serious crimes:**
- Financial penalties (compensate victim)
- Identity disclosure (to law enforcement if warranted)
- Expedited removal process
- Legal action forwarding

### 7.2 Enforcement Process

1. **Investigation** — Commons investigates allegation
2. **Notice** — Alleged violator is notified with charges
3. **Response period** — 10 days to respond
4. **Hearing** — Arbitration panel hears evidence
5. **Decision** — Panel issues decision with remedies
6. **Enforcement** — Remedies are implemented
7. **Appeal** — 7-day appeal period to Member Assembly

**Interim protection:**
- If person poses immediate risk (harassment, threats, theft), Commons can suspend pending arbitration
- Suspension is temporary (max 30 days pending hearing)

---

## 8. Anti-Abuse Safeguards

### 8.1 Preventing Authority Abuse

**Team Leaders cannot:**
- Use project authority to coerce personal favors
- Deny portfolio credit to retaliate against criticism
- Claim false authority over other projects
- Require work outside project scope
- Punish members for reporting misconduct

**Commons cannot:**
- Use identity access to expose members unfairly
- Take Commons funds for personal use
- Make decisions without documented process
- Retaliate against members raising concerns
- Unilaterally override project agreements

**Arbiters cannot:**
- Decide disputes they have conflict in
- Collude to favor one party
- Take bribes or inducements
- Disclose confidential information

**Violations trigger:**
- Removal from position
- Member sanctions up to expulsion
- Financial liability
- External legal action

### 8.2 Whistleblower Protection

**Members reporting misconduct are protected from:**

- Retaliation
- Termination from projects
- Suspension or removal
- Reputation damage
- Legal liability (for good-faith reports)

**Whistleblower process:**

1. Member reports serious misconduct to Commons
2. Commons investigates confidentially
3. Commons commits to protecting reporter's identity
4. Commons ensures no retaliation
5. If retaliation occurs, retaliation is also misconduct

---

## 9. Emergency Authority

### 9.1 When Emergency Authority Applies

**Emergency authority activates when:**

- Security breach is imminent or ongoing
- Infrastructure is failing (members can't access systems)
- Serious crime is suspected
- Safety is at immediate risk
- Legal requirement demands immediate action

### 9.2 Emergency Powers

**Commons can unilaterally, without normal process:**

- Freeze accounts or access
- Shut down compromised infrastructure
- Suspend members pending investigation
- Disclose identity to law enforcement (with warrant)
- Halt project if safety risk

**Limits:**
- Emergency powers last max 72 hours without Member Assembly approval
- After 72 hours, normal process resumes
- Member must be notified of suspension reason
- Appeals process available immediately
- Commons must document emergency decision

### 9.3 Emergency Authority Oversight

**After emergency action:**

1. Commons submits full report within 24 hours
2. Member Assembly reviews within 7 days
3. Assembly can overturn or modify decision
4. If Assembly overturns, affected member may seek arbitration

---

## 10. Governance Transparency

### 10.1 What Must Be Transparent

**Public to all members:**

- Project charters
- Project status (monthly)
- Commons financial reports (quarterly)
- Governance decisions (logged and published)
- Arbitration outcomes (anonymised)
- Policy changes
- Member assembly minutes

**Public to external parties:**

- SHADOW's public reputation system (see portfolio link)
- Privacy policy and data handling
- General governance structure
- SHADOW's mission and principles

**Confidential (restricted access):**

- Member legal identities
- Project client information
- Ongoing investigations
- Sensitive personal information
- Internal arbitration arguments (while dispute active)

### 10.2 Decision Log Standard

Every major decision includes:

- **Date** — When decision was made
- **Decision** — What was decided
- **Authority** — Who made the decision
- **Rationale** — Why this decision was made
- **Affected parties** — Who is impacted
- **Implementation** — How will it be carried out
- **Appeal deadline** — When can it be challenged

**All logs stored in:**
- SHADOW Commons system (primary)
- Member-accessible archive
- Publicly searchable (anonymised)

---

## 11. Member Assembly (Stage 3+)

### 11.1 Assembly Purpose

**Member Assembly is the highest authority in SHADOW** (Stage 3+).

The Assembly:

- Approves major policy changes
- Holds Commons accountable
- Elects Commons leadership (if desired)
- Votes on constitutional amendments
- Hears appeals of arbitration decisions
- Removes Commons stewards (if necessary)

### 11.2 Assembly Composition

**Who votes:**

- All verified SHADOW members (at Stage 2: all members; at Stage 3+: elected representatives)
- 1 vote per member (or 1 vote per representative)
- Proxies allowed (vote assigned to another member)
- Online voting supported
- Minimum quorum: 30% of members (or representatives)

### 11.3 Assembly Voting Rules

| Type | Majority Required | Notice Required |
|------|---|---|
| Regular policy | 50%+1 | 2 weeks |
| Major policy | 60% | 3 weeks |
| Constitutional amendment | 2/3 | 1 month |
| Commons removal | 60% | 2 weeks |
| Emergency action override | 50%+1 | 24 hours |

### 11.4 Assembly Meeting Frequency

- **Regular:** Quarterly (every 3 months)
- **Emergency:** Can be called by Commons or 25% of members
- **Format:** Online (asynchronous) or in-person (if geography allows)
- **Duration:** Decisions typically take 2-4 weeks (voting period)

---

## 12. Constitutional Principles (Unamendable)

These principles CANNOT be changed, even by Member Assembly super-majority:

1. **Member autonomy** — Members cannot be forced to work without consent
2. **Privacy** — Legal identities protected from unnecessary disclosure
3. **Appeal rights** — Members have right to arbitration and appeal
4. **No slavery** — No member can be bound to perpetual service
5. **No arbitrary removal** — Removal requires process and cause
6. **Project sovereignty** — Projects have operational autonomy
7. **Transparency** — Major decisions must be documented and logged

These are SHADOW's irreducible minimum. If Commons or Assembly attempts to violate them, the decision is void.

---

## 13. Governance Documentation Requirements

**Every SHADOW governance decision must produce:**

1. **Decision Record** — What, who, when, why, how
2. **Impact Statement** — Who is affected and how
3. **Appeal Instructions** — How to challenge the decision
4. **Implementation Plan** — Concrete next steps
5. **Timeline** — When decision takes effect
6. **Review Schedule** — When decision will be re-evaluated

**All stored in:**
- Searchable, timestamped decision archive
- Member-accessible without special permission
- Externally auditable (by regulators, auditors, etc.)

---

## 14. Decision Matrix: Complete Authority Map

| Decision | Authority | Process | Appeal |
|----------|-----------|---------|--------|
| **Individual Authority** | | | |
| Join/leave project | Individual | Unilateral | N/A |
| Accept personal commitment | Individual | Negotiation + consent | Arbitration |
| **Project Level** | | | |
| Project creation | Originator | Self-determination | N/A |
| Recruit contributor | Team Leader | Discretion (within project charter) | Arbitration (if discrimination) |
| Assign roles | Team Leader | Discretion | Arbitration |
| Set deliverables | Team Leader | Consultation with team | Team override (70% vote) |
| Technical decisions | Team Leader | Discretion | Arbitration |
| Project closure | Team Leader | Consultation | Arbitration (for ongoing commitments) |
| **Project Governance** | | | |
| Charter amendment | Team + TL consensus | 70% team vote; TL proposes | Arbitration |
| Major scope change | Team + TL | Negotiation + consent | Arbitration |
| Compensation change | Team + TL | Must amend agreement | Arbitration |
| **Commons Level** | | | |
| Routine infrastructure | Commons | Steward discretion | Member appeal |
| Member verification | Commons | KYC process | Member appeal |
| Reputation credit | Commons | Verification process | Arbitration |
| Arbitration decision | Arbitration panel | Full hearing | Member Assembly |
| **Policy Level** | | | |
| New policy | Commons proposes | Member Assembly votes (50%+1) | Vote of 2/3 can repeal |
| Policy change | Commons proposes | Member Assembly votes (60%) | Member Assembly review |
| Budget change >20% | Commons proposes | Member Assembly votes (60%) | Member Assembly override |
| **Constitutional** | | | |
| Charter amendment | Member Assembly | 2/3 super-majority | Cannot be appealed (final) |
| Governance restructure | Member Assembly | 2/3 super-majority | Cannot be appealed (final) |
| Commons removal | Member Assembly | 60% vote | Cannot be appealed (final) |

---

## Summary

SHADOW's governance is **bounded, transparent, and multi-layered:**

✓ Individual autonomy is protected  
✓ Team Leaders have operational freedom within boundaries  
✓ Commons provides services, not commands  
✓ Member Assembly is the ultimate check on power  
✓ Conflicts are resolved through arbitration with appeal rights  
✓ All major decisions are documented and auditable  
✓ Authority is distributed; no single person has absolute power  
✓ Emergency authority is temporary and reviewable  
✓ Accountability mechanisms are clear and enforced  

This framework prevents accidental re-creation of hierarchy while maintaining sufficient structure for SHADOW to function reliably.

