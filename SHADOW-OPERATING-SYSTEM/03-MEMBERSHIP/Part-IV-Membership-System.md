---
kind: spec
title: "SHADOW Part IV: Membership System"
---

# SHADOW Operating System — Part IV: Membership System

**Identity, Anonymity, Participation & Member Lifecycle**

---

## 1. Membership Overview

### 1.1 What SHADOW Membership Is

**SHADOW membership is status only.**

Membership means:

- ✓ Verified identity (legal name confirmed, stored securely)
- ✓ Assigned SHADOW pseudonym (persistent identifier)
- ✓ Access to SHADOW infrastructure (projects, reputation, arbitration)
- ✓ Participation rights (project joining, voting at scale)
- ✓ Reputation portfolio (publicly verifiable work history)

**Membership does NOT automatically mean:**

- ✗ Employment by SHADOW
- ✗ Obligation to work
- ✗ Payment or compensation
- ✗ Availability or commitment
- ✗ Participation in all activities
- ✗ Acceptance of specific projects

---

### 1.2 Membership is Voluntary

**A member may:**

- Join SHADOW freely
- Leave SHADOW freely (with notice)
- Participate in some projects and decline others
- Change commitment levels between projects
- Withdraw from projects at any time
- Request data deletion (subject to legal/contractual obligations)

**A member may NOT:**

- Be forced to work
- Be prevented from leaving
- Be trapped in unlimited commitment
- Be forced to accept payment
- Be required to transfer ownership
- Be punished for declining projects

---

## 2. Identity Architecture

### 2.1 The Four-Layer Identity System

SHADOW uses layered identity to balance pseudonymity with accountability.

#### Layer 1: Legal Identity

**What it contains:**
- Full legal name
- Date of birth
- Government ID (passport, ID number, etc.)
- Tax number / NIN
- Verified home address
- Payment account information (if applicable)

**Who can access:**
- Commons identity verification team (encrypted storage only)
- No other SHADOW member has access
- Government/law enforcement (only with warrant)
- Auditors (only if legal/tax compliance requires)

**Why it exists:**
- Taxation (if member receives payment)
- Banking and financial transactions
- Legal liability (contracts, insurance)
- Employment verification (if applicable)
- Regulatory compliance (data protection, labor law)
- Emergency contact
- Fraud prevention

**When it's disclosed:**
- NEVER to SHADOW collective
- Only to external parties (clients, employers) if member chooses
- Only to authorities with legal right (warrant, subpoena)
- Only to insurance/legal counsel when necessary

**Protection:**
- Encrypted storage (AES-256 minimum)
- Compartmentalised access (identity team only)
- Regular audits (who accessed, when, why)
- Deletion upon member request (if no outstanding obligations)

---

#### Layer 2: Verified SHADOW Identity

**What it contains:**
- SHADOW pseudonym (e.g., "Zenith", "Arctic", "Pulse")
- Email address (for SHADOW communications)
- Verification status (confirmed member)
- Membership date
- Project participation history (summary, pseudonymous)
- Reputation score (if applicable at scale)

**Who can access:**
- All SHADOW members (can see others' pseudonyms and verified status)
- Commons stewards (full access)
- Arbitration panels (for dispute resolution)
- Project team members (for project collaboration)
- Reputation system (for portfolio display)

**Why it exists:**
- Persistent, consistent identity across SHADOW
- Enables reputation to follow member
- Allows verification ("Is 'Zenith' a real verified member?")
- Enables project collaboration
- Enables arbitration (who is involved in dispute)

**When it's disclosed:**
- To any SHADOW member (pseudonym only, no legal identity)
- To external employers/clients (member may share portfolio with pseudonym)
- To arbiters (for dispute resolution)

**Protection:**
- Pseudonym is permanent (cannot be reused)
- Once chosen, pseudonym belongs to member
- Member can request privacy controls on when pseudonym is displayed
- Member can export verification history anytime

---

#### Layer 3: Project Identity

**What it contains:**
- Role in specific project (e.g., "Lead Developer")
- Project-scoped identifier (if member uses different name in project)
- Contributions to that project
- Responsibilities and deliverables
- Project-specific reputation/feedback

**Who can access:**
- Project team members only (while active)
- Project Team Leader (always)
- Commons (for reputation verification)
- Member themselves (always)

**Why it exists:**
- Project-scoped collaboration (team sees role and responsibility)
- Verification of who did what ("Who implemented the auth system?")
- Portfolio building (what specifically did member contribute)
- Project confidentiality (sensitive work is project-scoped)

**When it's disclosed:**
- Within project only
- To member's portfolio (summary for external employers)
- To arbitration (if dispute involves project contribution claims)

**Protection:**
- Confidentiality of project details (unless project makes them public)
- Permanent record (contributions cannot be retroactively claimed/denied)
- Member can dispute credit (goes to arbitration)

---

#### Layer 4: Public Identity

**What it contains:**
- SHADOW pseudonym (e.g., "Zenith")
- Public portfolio URL
- Verified projects (list of completed work)
- Verified skills and competencies
- Recommendations from project leads
- Work samples (if contributed to public/open-source work)
- Reputation status (e.g., "4.8/5 from 23 projects")

**Who can access:**
- Anyone online (publicly listed on SHADOW portfolio platform)
- External employers and clients
- SHADOW members
- Search engines (if portfolio is indexed)

**Why it exists:**
- Professional credibility ("I'm 'Zenith' from SHADOW; here's my verified work")
- Portfolio for job seeking
- External reputation transfer (member can use SHADOW portfolio with employers)
- Marketing (SHADOW portfolio showcases the collective's quality)

**When it's disclosed:**
- Public by default (member can restrict visibility)
- Member controls what appears (can opt projects out of public portfolio)
- Member can export portfolio JSON (portable to other platforms)

**Protection:**
- Does NOT include legal identity
- Does NOT include email or personal contact
- Does NOT include payment/financial details
- Does NOT include personal information
- Member can delete outdated entries
- Member can request anonymisation (remove from search, but keep historical record)

---

### 2.2 Identity Verification Process (KYC)

**Goal:** Verify that member is a real person, eligible to participate legally.

**Process:**

1. **Application**
   - Member provides legal name, email, rough location
   - Member reviews and accepts SHADOW Charter + Privacy Policy
   - Applicant reads "Is SHADOW Right For Me" guide

2. **Identity Verification (3–7 days)**
   - Member submits government-issued ID (passport, driver license, etc.)
   - Verification service (or Commons volunteer) confirms identity
   - Checks for sanctions lists, fraud indicators
   - Documents verification (encrypted, permanent record)
   - Verifier may ask follow-up questions ("What's your relationship to SHADOW?")

3. **Approval**
   - If verified: Member is issued SHADOW pseudonym + member ID
   - If rejected: Reason given; applicant can reapply after 30 days
   - If uncertain: Verification service requests more information

4. **Onboarding**
   - Member receives welcome packet
   - Member sets security (password, 2FA if available)
   - Member reviews SHADOW policies
   - Member can view reputation system and existing projects
   - Member can now create or join projects

**Verification requirements:**

- **Must have:** Real identity verified against government ID or official registry
- **Must not have:** Criminal record disqualifying involvement (varies by jurisdiction)
- **Location:** SHADOW accepts members from most countries (some restricted by sanction lists)
- **Age:** Member must be legal adult (18+ typically; 16+ with guardian consent if applicable)
- **Language:** Applicant must understand English (SHADOW operates in English; regional groups may differ)

---

### 2.3 Pseudonym Selection

**Rules for pseudonyms:**

- **Unique:** No two members use the same pseudonym
- **Permanent:** Member keeps pseudonym for entire membership
- **Chosen by member:** Member selects (Commons suggests if needed)
- **Portable:** Member owns their pseudonym; can be used across platforms
- **Professional:** Pseudonym should be workplace-appropriate (avoid slurs, offensive content)
- **Meaningful:** Preferably reflects member's interests or values
- **Persistent:** If member leaves and rejoins, they use same pseudonym

**Examples:**
- "Zenith" — aspiration
- "Arctic" — coolness/calm
- "Catalyst" — drives change
- "Echo" — amplifies ideas
- "Forge" — builds things

**Pseudonym cannot:**
- Impersonate another member
- Impersonate a real company/person
- Use slurs or hate speech
- Mislead about identity (e.g., "RealJohnDoe" when name is Jane)

**Changing pseudonym:**
- Member can request ONE name change in first 30 days (during onboarding adjustment)
- After that, pseudonym is permanent
- Reason: Reputation is tied to pseudonym; changing it breaks reputation continuity

---

## 3. Membership States

Members progress through defined states from application to departure.

### 3.1 State Diagram

```
APPLICANT
    ↓
VERIFICATION PENDING
    ↓ (verified)
VERIFIED MEMBER ← ─────── (reactivation)
    ↓                          ↑
ACTIVE CONTRIBUTOR            │
    ↓                          │
INACTIVE (no projects > 6 mo)──┘
    ↓ (not reactivated)
DEPARTED
    ↓
ARCHIVED (historical record)
```

---

### 3.2 Applicant

**Definition:** Person who has applied to SHADOW but not yet verified.

**Duration:** 1–7 days (pending verification)

**Status:**
- Can read public SHADOW information
- Cannot access projects
- Cannot create projects
- Cannot access reputation system
- Cannot participate in governance

**Transitions:**
- → Verified Member (identity confirmed)
- → Rejected (identity cannot be verified; can reapply in 30 days)
- → Withdrawn (applicant requests to withdraw application)

---

### 3.3 Verified Member

**Definition:** Identity is verified; member has SHADOW pseudonym; eligible to participate.

**Duration:** Indefinite (until member leaves)

**Status:**
- Can create projects
- Can join projects
- Can view SHADOW infrastructure
- Can participate in arbitration (if dispute resolution needed)
- Can participate in governance (at Stage 3+)
- Can build reputation and portfolio

**Transitions:**
- → Active Contributor (joins a project)
- → Inactive (no project participation for 6+ months)
- → Suspended (serious misconduct investigation)
- → Departed (member leaves SHADOW)

---

### 3.4 Active Contributor

**Definition:** Member is currently participating in ≥1 project(s).

**Duration:** For length of project participation

**Status:**
- Same as Verified Member plus:
- Contributions are tracked in reputation system
- Portfolio is being built
- Subject to project-level discipline (Team Leader authority)
- Subject to project confidentiality rules

**Transitions:**
- → Inactive (leaves all projects)
- → Suspended (serious misconduct)
- → Departed (member leaves SHADOW)

---

### 3.5 Inactive

**Definition:** Member has been verified but has no active project participation for 6+ consecutive months.

**Duration:** Up to 12 months (then transitioned to Archived)

**Status:**
- Membership is paused, not terminated
- Reputation/portfolio is preserved
- Can rejoin projects by contacting Commons
- Cannot be automatically re-added to projects (must actively rejoin)
- Can re-activate by joining a new project

**Triggers for Inactive:**
- Last active project ended
- No new projects joined for 6 months
- Member didn't request continuation

**Transitions:**
- → Verified Member (if rejoins project within 12 months)
- → Archived (if no activity for 12+ months)
- → Departed (member chooses to leave formally)

---

### 3.6 Suspended

**Definition:** Member is temporarily barred from SHADOW participation pending investigation/decision.

**Duration:** Max 72 hours (emergency); thereafter only with arbitration approval

**Reasons:**
- Security investigation (account compromise, identity fraud, etc.)
- Serious misconduct allegation (harassment, theft, abuse, etc.)
- Legal concern (law enforcement request, regulatory issue, etc.)
- Emergency safety risk

**Status during suspension:**
- Cannot access SHADOW systems
- Cannot create/join projects
- Cannot access reputation system
- Cannot participate in governance
- Member is notified of suspension reason and appeal process

**Transitions:**
- → Verified Member (investigation cleared, no cause found)
- → Departed (member chooses to withdraw)
- → Removed (investigation finds serious misconduct; goes to removal)

---

### 3.7 Departed

**Definition:** Member has formally left SHADOW, or has been removed.

**Duration:** Permanent (can reapply as new member if circumstances change)

**Causes:**
- Member voluntary withdrawal (no cause needed)
- Member removal (serious misconduct, after due process)
- Account expiration (no activity for 12+ months, archived)

**Status after departure:**
- Historical reputation data is preserved
- Portfolio contributions credited to departed member's pseudonym
- Cannot access SHADOW systems
- Can request data export (historical record)
- Can reapply as new member (subject to re-verification)

**Reputation preservation:**
- "Contributed to ProjectX from [date] to [date]" — permanently visible
- Credit cannot be retroactively claimed by another member
- Others can reference departed member's contributions

**Data handling:**
- Reputation data: permanent (publicly auditable)
- Legal identity: encrypted and deleted (unless legal hold)
- Project records: permanent (contributions remain credited)
- Communications: deleted after 90 days (unless legal dispute)

---

### 3.8 Archived

**Definition:** Historical record of departed member; no active participation.

**Duration:** Indefinite (permanent historical record)

**Status:**
- No systems access
- Reputation data visible (historical)
- Can view own profile/portfolio (read-only)
- Cannot create/modify anything
- Can request data export

---

## 4. Membership Privileges & Obligations

### 4.1 What SHADOW Membership Provides

**Infrastructure:**
- Access to project directory
- Participation in projects
- Identity and reputation system
- Arbitration services
- Shared hosting (if applicable)

**Community:**
- Network of peers
- Collaborative opportunities
- Knowledge sharing
- Professional community

**Reputation:**
- Portfolio documentation
- Verification of work
- Public credibility
- Professional references

**Governance:**
- Right to participate in arbitration (if dispute)
- Right to member assembly (at Stage 3+)
- Right to appeal decisions affecting you

**Support:**
- Onboarding assistance
- Technical support (access issues)
- Privacy protection
- Security incident response

**What membership does NOT guarantee:**
- Employment
- Income
- Specific projects
- Promotion or leadership
- Permanent residence
- Benefits (health insurance, retirement, etc.)

---

### 4.2 Member Obligations

**A SHADOW member is obligated to:**

1. **Respect Charter** — Follow SHADOW Charter and Code of Conduct
2. **Confidentiality** — Respect project and personal confidentiality
3. **Honesty** — Represent themselves truthfully; don't impersonate
4. **Security** — Protect account credentials; report compromises
5. **Communication** — Respond to important SHADOW notices
6. **Fulfil commitments** — Complete work agreed with projects
7. **Fair treatment** — Treat other members respectfully
8. **Report misconduct** — Report serious violations to Commons

**Obligations during project participation:**
- Fulfill defined role and deliverables
- Respect project timeline and confidentiality
- Communicate issues/blockers to Team Leader
- Follow project security practices
- Attend required project meetings (if stipulated)
- Deliver quality work (standard of care)

**Obligations related to portfolio:**
- Provide accurate work history (don't claim false contributions)
- Allow accurate attribution of work
- Don't plagiarise or steal credit
- Allow Commons to verify contributions

---

### 4.3 Member Rights

**A SHADOW member has the right to:**

1. **Autonomy**
   - Choose which projects to join
   - Choose when to participate
   - Leave projects or SHADOW
   - Decline projects without penalty

2. **Privacy**
   - Keep legal identity private within SHADOW
   - Pseudonym protection (not revealed to collective)
   - Confidential communications
   - Personal information protected

3. **Fairness**
   - Arbitration if disputes arise
   - Appeal of decisions affecting them
   - Written process for removal/suspension
   - Due process (accusation, response, hearing, decision)

4. **Transparency**
   - Know what work they did (portfolio visibility)
   - Know governance rules
   - Access decision logs
   - Know why decisions affecting them were made

5. **Compensation**
   - Negotiate terms (what they get paid, if anything)
   - Receive agreed compensation on time
   - Dispute unmet compensation (via arbitration)
   - Request itemised accounting

6. **Reputation**
   - Build and maintain portfolio
   - Dispute inaccurate credit
   - Export reputation data
   - Use reputation with external employers

7. **Withdrawal**
   - Leave at any time
   - Request data export
   - Data deletion (if no outstanding obligations)

---

## 5. Onboarding Process

### 5.1 Application Phase (1–2 days)

**Step 1: Pre-Application**
- Applicant reads "Is SHADOW For You" guide
- Applicant reviews SHADOW Charter (full text)
- Applicant reviews Privacy Policy and Identity Policy
- Applicant reviews Code of Conduct

**Step 2: Application Submission**
- Applicant fills application form:
  - Full legal name
  - Email address
  - Geographic location (country/region)
  - Brief motivation ("Why do you want to join SHADOW?")
  - Accept terms/policies checkbox

**Step 3: Confirmation**
- Confirmation email sent
- Email includes verification link
- Applicant confirms email address

---

### 5.2 Verification Phase (3–7 days)

**Step 1: Identity Verification**
- Applicant uploads government ID (passport or ID card)
- Verification service performs check:
  - Confirms ID is authentic
  - Confirms applicant matches ID
  - Checks sanctions/fraud lists
  - May ask follow-up questions

**Step 2: Approval Decision**
- If verified: Proceed to Step 3
- If unclear: Commons requests clarification
- If rejected: Reason provided; can reapply in 30 days

**Step 3: Pseudonym Assignment**
- Applicant selects pseudonym (Commons suggests options if needed)
- Commons confirms pseudonym is unique
- Pseudonym is assigned and permanent

---

### 5.3 Onboarding Phase (1–2 days)

**Step 1: Welcome**
- Welcome email with:
  - SHADOW pseudonym
  - Permanent member ID
  - Portal login credentials
  - Getting started guide

**Step 2: Security Setup**
- Member creates password (strong requirements)
- Member enables 2FA if available
- Member reviews security checklist

**Step 3: System Access**
- Member logs into SHADOW portal
- Member reviews project directory
- Member views their empty portfolio/reputation
- Member reads FAQ and help documentation

**Step 4: Policy Review**
- Member reviews (at their own pace):
  - SHADOW Governance Framework
  - Arbitration Policy
  - Information Classification Policy
  - Community Standards

**Step 5: Ready to Participate**
- Member can now create or join projects
- Member can attend member assembly (if Stage 3+)
- Member can request arbitration (if dispute arises)

---

## 6. Privacy & Data Protection

### 6.1 Data Categories

**Legal Identity Data**
- Encrypted storage (AES-256)
- Compartmentalised access
- Deleted upon departure (unless legal hold)
- Annual privacy audit

**Reputation Data**
- Permanent storage (historical record)
- Publicly auditable
- Not deleted (but can be anonymised)
- Member-exportable

**Communication Data**
- Project communications (stored for project duration + 90 days)
- SHADOW admin communications (stored 1 year)
- Arbitration communications (stored indefinitely)
- Deleted unless legal hold

**Transaction Data**
- Financial records (stored per tax law, typically 7 years)
- Payment receipts (stored indefinitely)
- Invoice records (permanent)

**Access Data**
- Login audit logs (stored 1 year)
- Infrastructure access logs (stored 30 days)
- Deleted unless security incident requires preservation

---

### 6.2 Member Data Rights

**Member can:**
- Access all their data (on request)
- Download data export (portable format)
- Request correction (if data is inaccurate)
- Request deletion (subject to legal/contractual holds)
- Know who accessed their data (audit log)
- Object to certain processing (in limited cases)

**Member cannot:**
- Force deletion of reputation data (historical record)
- Force deletion of project contributions (attributed permanently)
- Prevent SHADOW from storing legal identity (required for legal/tax)

---

## 7. Code of Conduct

### 7.1 Expected Behavior

**SHADOW members are expected to:**

1. **Treat others with respect**
   - No harassment, bullying, or abuse
   - No discrimination based on identity
   - Disagreement is okay; personal attacks are not
   - Respect others' time and boundaries

2. **Be honest**
   - Represent yourself truthfully
   - Don't claim credit for work you didn't do
   - Disclose conflicts of interest
   - Report problems clearly

3. **Respect confidentiality**
   - Don't share project details outside project
   - Don't expose other members' identities
   - Don't share meeting notes or private communications
   - Only disclose what member consents to

4. **Follow the law**
   - Don't use SHADOW for illegal activity
   - Don't contribute to illegal projects
   - Report suspected illegal activity to Commons
   - Respect intellectual property rights

5. **Be professional**
   - Use platform appropriately
   - Don't spam or harass
   - Deliver quality work or communicate when you can't
   - Respond to reasonable communication from team/Commons

---

### 7.2 Enforcement

**Minor violations** (rude comment, small confidentiality slip):
- Private warning from Team Leader or Commons
- Member acknowledges and commits to improvement
- No formal record

**Moderate violations** (repeated rudeness, confidentiality breach):
- Formal written warning
- Required training or counseling
- May be suspended from project
- Recorded in incident log

**Serious violations** (harassment campaign, fraud, identity theft):
- Investigation by Commons
- Arbitration hearing
- Possible sanctions: suspension from SHADOW, removal, legal action
- Legal disclosure if warranted (law enforcement)

**Criminal violations:**
- Immediate suspension pending investigation
- Disclosure to law enforcement
- Expedited removal process
- Possible legal action by victim

---

## 8. Membership Data Export

**Members can request complete data export:**

**Included in export:**
- SHADOW pseudonym and member ID
- Verified projects and contributions
- Portfolio summary
- Reputation score (if applicable)
- Recommendations received
- Project team memberships (dates, roles)

**NOT included in export:**
- Legal identity data (confidential)
- Other members' identities
- Sensitive project information
- Arbitration details (confidential)
- Commons internal notes

**Format:** Exportable as JSON, CSV, or PDF (member choice)

**Use:** Member can take portfolio to other platforms, employers, etc.

---

## Summary

SHADOW's membership system is designed to:

✓ Protect member privacy (legal identity hidden)  
✓ Enable public credibility (pseudonym with verifiable portfolio)  
✓ Support voluntary participation (no automatic obligation)  
✓ Provide clear lifecycle (Applicant → Verified → Active → Inactive → Departed)  
✓ Enforce accountability (even pseudonymously)  
✓ Respect member autonomy (right to join/leave/decline)  
✓ Maintain data integrity (reputation is permanent; contributions are credited accurately)  
✓ Enable due process (suspension/removal requires process)  

Members are verified, accountable individuals operating under pseudonyms to protect privacy while building public reputation.

