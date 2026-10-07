---
kind: spec
title: "SHADOW Part II: Organisational Topology"
---

# SHADOW Operating System — Part II: Organisational Topology

**Decentralised Structure at Scale**

---

## 1. The SHADOW Network Model

SHADOW is structured as a **network of autonomous projects** organised around shared infrastructure and governance, not hierarchy.

```
                                 SHADOW
                                   |
                    ┌──────────────┴──────────────┐
                    |                             |
              COMMONS LAYER                 MEMBER NETWORK
              (Shared services)                   |
                    |               ┌─────────────┼─────────────┐
              - Identity              |             |             |
              - Reputation         PROJECT A    PROJECT B    PROJECT C
              - Infrastructure       |             |             |
              - Arbitration      Team Lead     Team Lead     Team Lead
              - Apps                 |             |             |
                                 Contributors Contributors Contributors
```

**Key characteristic:** There is **no pyramid**.

Projects are peers, not hierarchical subordinates. The Commons provides services, not commands.

---

## 2. The Three Layers of SHADOW

### 2.1 Individual Layer

**Members**

Each member is an autonomous individual with:
- Personal pseudonym (SHADOW identity)
- Verified legal identity (held securely by Commons)
- Portfolio and reputation
- Ability to originate projects
- Right to join/leave projects
- Ownership of pre-existing personal IP

**Individual sovereignty:**
- Member controls own time and availability
- Member chooses projects to join
- Member retains personal assets
- Member can withdraw from SHADOW

**Individual responsibility:**
- Fulfils agreed commitments
- Respects project confidentiality
- Follows SHADOW security and Code of Conduct
- Participates in arbitration if disputes arise

---

### 2.2 Project Layer

**Projects and Teams**

Each project is an operational unit led by a Team Leader with:
- Defined objective and scope
- Autonomous team of contributors
- Project-specific rules and workflow
- Project-specific decision authority
- Negotiated commitment terms (volunteer, paid, revenue-share)

**Project sovereignty:**
- Team Leader determines project direction
- Team Leader recruits and manages contributors
- Team Leader allocates project resources
- Team Leader sets internal processes
- Team Leader negotiates with external clients
- Project is operationally independent

**Project boundaries:**
- Cannot force participation in unrelated projects
- Cannot override members' personal rights
- Cannot claim ownership of pre-existing member IP
- Cannot override SHADOW Core Rules
- Cannot operate outside legal compliance

**Projects relate to other projects:**
- May share members (member A on Project X and Project Y)
- May share resources (hosted on same Commons server)
- May coordinate (if mutually beneficial)
- Do NOT have authority over each other

---

### 2.3 Commons Layer

**SHADOW Commons**

The Commons is the shared infrastructure and governance layer, run by **Commons Stewards** (typically 3-7 people).

**Commons responsibilities:**

1. **Identity Infrastructure**
   - Member identity verification
   - Pseudonym registry
   - Legal identity storage (encrypted)
   - KYC/verification procedures
   - Data protection compliance

2. **Reputation System**
   - Portfolio management
   - Contribution tracking
   - Peer attestations
   - Reputation verification
   - Public reputation platform

3. **Shared Technical Infrastructure**
   - Hosting and servers
   - Domain names and SSL certificates
   - Database and backup systems
   - Communication tools
   - Access control systems

4. **Governance & Arbitration**
   - Dispute arbitration
   - Misconduct investigation
   - Member suspension/removal
   - Rule enforcement
   - Member assembly coordination

5. **Legal & Compliance**
   - Tax compliance
   - Data protection (GDPR, etc.)
   - Contract administration
   - Insurance
   - Regulatory navigation

6. **Commons-Owned Revenue Apps**
   - Housing Archive (subscription app)
   - Tenga Inventory POS (subscription app)
   - Any future Commons ventures

**Commons authority limits:**

The Commons CANNOT:
- Unilaterally seize project resources
- Redirect project revenue
- Force project direction changes
- Override project agreements
- Remove a Team Leader without cause
- Prevent projects from operating (unless legal liability)
- Impose arbitrary fees

**Commons dependencies:**

Projects do NOT depend on Commons for:
- Operational decisions
- Project management
- Technical direction
- Team recruitment
- Revenue management

Projects DO depend on Commons for:
- Identity and reputation infrastructure
- Arbitration (if disputes arise)
- Legal protection (if opted into revenue-share)
- Professional insurance (if opted in)
- Security incident response
- Shared hosting (if using Commons infrastructure)

---

## 3. Scaling Model

SHADOW governance evolves as membership grows. At each stage, the model adds structure **without creating permanent hierarchy**.

### Stage 1: Founding (5–15 members)

**Structure:**

```
Commons (5 co-founders)
    ↓
Direct member relationships
    ↓
Projects (2–5 active projects)
```

**Decision-making:**
- Commons makes decisions by consensus or majority
- Members participate in all major decisions
- Arbitration is informal (mediation)
- No formal assembly needed

**Communication:**
- Direct messaging (Slack, Discord, etc.)
- Synchronous meetings (all members)
- Real-time dispute resolution

**Governance overhead:**
- Minimal (one policy document, basic rules)
- Decisions recorded but not formally published
- Informal role assignments

---

### Stage 2: Growing (15–50 members)

**Structure:**

```
Commons Steward Team (3–5 people)
    ├─ Operations
    ├─ Legal/Compliance
    └─ Identity/Reputation
         ↓
Project Representatives (1 per project)
         ↓
Individual Members + Projects (10–20 projects)
```

**Decision-making:**
- Commons makes routine decisions
- Member representatives meet quarterly
- Formal arbitration process begins (3-person panel)
- Project-level decisions remain autonomous

**Communication:**
- Asynchronous updates (email, documentation)
- Quarterly assembly (all members, major decisions)
- Project updates (monthly)

**Governance overhead:**
- Formal policies (identity, arbitration, revenue distribution)
- Project charters for all projects
- Written decision logs
- Member handbook

**New roles:**
- Commons stewards become part-time or full-time
- Arbitration panel (trained members)
- Project representatives (elected by active project members)

---

### Stage 3: Established (50–250 members)

**Structure:**

```
Commons Council (5–7 stewards, paid roles)
    ├─ Executive Council
    ├─ Steward: Identity & Reputation
    ├─ Steward: Legal & Compliance
    ├─ Steward: Technical Infrastructure
    └─ Steward: Community & Arbitration
         ↓
Project Clusters (5–10 thematic groups)
    ├─ Cluster Coordinator (volunteer)
    └─ 5–25 projects per cluster
         ↓
Individual Members (200–250)
```

**Decision-making:**
- Commons stewards make routine decisions
- Member assembly (elected representatives) meets quarterly
- Standing arbitration panel (5–7 members, rotating)
- Project clusters coordinate internally
- Major changes require member vote

**Communication:**
- Formal announcements (email, website)
- Quarterly member assembly
- Cluster meetings (monthly)
- Transparent decision logs (published)
- Public reputation data (auditable)

**Governance overhead:**
- Comprehensive policy manual
- Formal bylaws
- Constitutional governance
- Regular audits
- Professional legal counsel (part-time)

**New roles:**
- Commons stewards become paid roles (budget from app revenue)
- Cluster coordinators (volunteer, with stipends)
- Professional arbitration panel
- Legal/compliance specialist
- Community manager

---

### Stage 4: Large Network (250–1,000 members)

**Structure:**

```
SHADOW Foundation/Cooperative (legal entity)
    ├─ Executive Council (5–9 members, elected)
    ├─ Member Assembly (representatives, 40–100 people)
    └─ Commons Infrastructure (10–20 paid staff)
         ├─ Identity & Security
         ├─ Reputation & Portfolio
         ├─ Technical Infrastructure
         ├─ Legal & Compliance
         ├─ Finance & Operations
         └─ Arbitration & Community
         ↓
Project Clusters (15–30 clusters by domain)
    ├─ Cluster Council (3–5 members, elected)
    ├─ Local Arbitration Panel
    └─ 30–70 projects per cluster
         ↓
Individual Members (700–1,000)
```

**Decision-making:**
- Executive Council handles routine operations
- Member Assembly votes on major changes
- Cluster councils handle cluster-level coordination
- Professional arbitration system (with appeals)
- Project autonomy remains absolute (unless legal risk)

**Communication:**
- Formal governance website
- Quarterly member assembly (in-person or virtual)
- Monthly cluster meetings
- Weekly Commons updates
- Published reputation data (fully auditable)
- Transparent financial reports

**Governance overhead:**
- Professional governance staff
- Formal constitutional bylaws
- Regular external audits
- Member handbook (comprehensive)
- Advanced dispute resolution

**New roles:**
- Executive director (Commons operations)
- Regional cluster coordinators
- Professional arbiters (3–5 people, paid)
- Financial officer
- Legal counsel
- Community lead
- Technical operations team
- Reputation/portfolio manager

---

### Stage 5: Ecosystem (1,000–10,000+ members)

**Structure:**

```
SHADOW International Cooperative (formal legal entity)
    ├─ Board of Directors (9–15, elected by member assembly)
    ├─ Member Assembly (100–200 elected representatives)
    ├─ Commons (50–100 paid staff across departments)
    └─ Regional Federations (5–20 regional entities)
         ├─ Regional Council (elected)
         ├─ Regional Commons (5–15 staff)
         └─ 150–300 projects per region
         ↓
Professional Communities (30–50 by skill/domain)
    ├─ Community Lead
    └─ Community Working Groups
         ↓
Individual Members (5,000–10,000+)
```

**Decision-making:**
- Board handles governance; member assembly approves major changes
- Regional councils handle regional matters
- Professional communities coordinate by domain
- Algorithmic reputation system (automated verification)
- Distributed arbitration (local + appeals)
- Project sovereignty is absolute (unless legal/safety risk)

**Communication:**
- Decentralised governance platform
- Regional assemblies (monthly)
- Global member assembly (quarterly)
- Automated reputation and portfolio updates
- Real-time financial transparency
- Public decision archive

**Governance overhead:**
- Formal international structure
- Professional governance team (20+ people)
- Federated arbitration system
- Member support team
- Legal departments (multiple jurisdictions)
- Technical operations (10+ people)

**New roles:**
- Regional directors
- Community leads
- Professional arbiters (20+)
- Member support team
- Governance specialists
- International legal counsel

---

## 4. Project Clustering

As SHADOW grows, related projects naturally cluster.

### Cluster Structure

**Cluster** = 5–30 related projects coordinated by a Cluster Coordinator.

**Possible clustering approaches:**

1. **By Domain**
   - Web Development cluster
   - Design cluster
   - Research cluster
   - AI/ML cluster

2. **By Industry**
   - Healthcare projects
   - Finance projects
   - Education projects

3. **By Geography**
   - EU cluster
   - Asia cluster
   - Americas cluster

4. **By Project Type**
   - Portfolio-building projects
   - Revenue-generating projects
   - Open-source projects

### Cluster Responsibilities

**Cluster Coordinator (volunteer, with stipend at scale):**

- Facilitates knowledge sharing between projects
- Identifies resource conflicts (e.g., multiple projects needing same expert)
- Coordinates cross-project collaboration opportunities
- Represents cluster interests in Member Assembly
- Helps onboard new projects in cluster
- Does NOT manage or control projects

**What clusters do NOT do:**

- Override project autonomy
- Force resource sharing
- Dictate technical approaches
- Control revenue distribution
- Assign members to projects

**Cross-cluster coordination:**

- Clusters meet periodically to identify standards and best practices
- Commons coordinates between clusters
- Conflicts between clusters go to Commons arbitration

---

## 5. Network Topology Diagram

### At Stage 1 (5–15 members):

```
        COMMONS
       (5 people)
           |
    ┌──────┼──────┐
    |      |      |
  Project Project Project
    A      B      C
    |      |      |
   TL +   TL +   TL +
  Contribs Contribs Contribs
```

### At Stage 2 (15–50 members):

```
         COMMONS
       (3–5 stewards)
           |
    ┌──────┼──────┬────────┐
    |      |      |        |
  Cluster Cluster Project Project
  (X)     (Y)     (Z1)     (Z2)
    |      |      |        |
  5 prj  5 prj   TL+C   TL+C
```

### At Stage 3 (50–250 members):

```
              COMMONS (5–7 stewards, paid)
                      |
    ┌─────────────────┼─────────────────┐
    |                 |                 |
  CLUSTER 1        CLUSTER 2        CLUSTER 3
  (10 projects)    (12 projects)    (8 projects)
    |                 |                 |
   Coord              Coord             Coord
    |                 |                 |
  5–10 projects   5–10 projects     5–10 projects
    |                 |                 |
  TL+C              TL+C              TL+C
```

### At Stage 4 (250–1,000 members):

```
            EXECUTIVE COUNCIL (5–9)
                    |
    ┌───────────────┼───────────────┐
    |               |               |
  MEMBER ASSEMBLY    |         COMMONS STAFF (10–20)
  (40–100 reps)      |               |
    |               |         ┌──────┼──────┐
    |               |         |      |      |
  REGION 1       REGION 2   REGION 3 ... (15–30 regions)
    |               |         |
  300 members   350 members 350 members
    |               |         |
  Cluster Cluster Cluster Cluster Cluster Cluster
  (3–5 per region)
    |
  30–50 projects per cluster
```

---

## 6. Member Roles & Responsibilities

### Member Roles (Not Hierarchy)

**SHADOW Member**
- Verified individual with pseudonym
- Participated in ≥1 project
- Responsible for project commitments
- Can originate new projects

**Project Contributor**
- Member actively participating in project
- Fulfils defined role and deliverables
- Represented in project records

**Team Leader**
- Project originator (or designate)
- Operational authority within project
- Answerable for project delivery and member treatment

**Commons Steward** (Paid role at Stage 2+)
- Manages Commons infrastructure/governance
- Part-time or full-time position
- Held for 2–3 year terms
- Rotational (prevents permanent power concentration)

**Cluster Coordinator** (Volunteer, stipend at Stage 3+)
- Facilitates cross-project collaboration within cluster
- Represents cluster in Member Assembly
- Does not control projects

**Arbitration Panel Member** (Volunteer, stipend at Stage 3+)
- Trained in arbitration and SHADOW governance
- Assigned to disputes on rotation basis
- Neutral with respect to disputants

**Member Assembly Representative** (Elected, volunteer)
- Elected by member vote (1 per 10–50 members depending on scale)
- Attends quarterly assembly
- Votes on major decisions
- Represents member interests to Commons

**Project Nominating Committee** (Only at Stage 4+, volunteer)
- Helps Commons identify candidates for Council positions
- Does not directly select, only recommends

### No Permanent Hierarchy

**Key principle:** No member holds a permanent position of power over others.

- Stewards serve fixed terms (2–3 years)
- No individual can be irreplaceable
- Roles are rotational where possible
- Power is distributed across multiple people
- Members can remove stewards via vote

---

## 7. Information Flow Architecture

### Upward Flow (Project → Commons)

**Projects report to Commons:**

- Project creation notification
- Monthly project status
- Quarterly financial update (if revenue project)
- Critical issues (security, legal, abuse)
- Completion/closure notification

**Purpose:** Commons maintains institutional knowledge, coordinates across projects, manages reputation system.

### Downward Flow (Commons → Project)

**Commons notifies projects of:**

- Security incidents
- Governance changes
- Policy updates
- Maintenance windows
- Arbitration decisions (if relevant)

**Principle:** Minimal information push. Commons pulls data, doesn't broadcast unless necessary.

### Lateral Flow (Project ↔ Project)

**Projects coordinate peer-to-peer:**

- Resource sharing agreements
- Cross-project collaboration
- Shared infrastructure requests
- Knowledge sharing

**Role of Cluster Coordinator:** Facilitates, doesn't control.

### External Flow (SHADOW → Clients)

**SHADOW represents externally:**

- Only Commons can legally represent SHADOW
- Team Leaders represent only their projects
- Members represent only themselves (as contributors)
- No member can accidentally represent entire SHADOW

---

## 8. Resilience Architecture

### Distributed Authority

At every scale, authority is distributed:

**Stage 1:** Consensus (requires agreement of most founders)  
**Stage 2:** Steward team (no single person decides everything)  
**Stage 3:** Executive Council (9 people, no person has unilateral power)  
**Stage 4+:** Board + Assembly (board is elected, can be removed)

### Succession Planning

Every critical role has:
- Defined responsibilities documented
- Backup person trained
- Handover procedures
- Emergency deputy named
- Rotation schedule

### Infrastructure Redundancy

- Multiple servers (not single server failure = SHADOW failure)
- Backup infrastructure in multiple locations
- Distributed identity system (if Commons goes offline, identity system continues)
- Reputation data distributed (members can audit and export)
- Financial records audited externally

### Exit Plan

If SHADOW as Commons collapses:
- Projects continue independently
- Members retain reputation data
- Shared infrastructure is transferable
- Legal entity and IP remain accessible

---

## 9. Anti-Centralisation Safeguards

Specific mechanisms prevent accidental re-creation of hierarchy:

### 1. Term Limits

- Commons stewards serve 2–3 years
- Cannot serve more than 2 consecutive terms
- Prevents entrenched leadership

### 2. Recusal Rules

- Stewards recuse from decisions affecting their projects
- Arbiters cannot arbitrate disputes involving their own conflicts
- Prevents corruption of neutrality

### 3. Transparent Decision Logs

- All major decisions documented and published
- Members can audit and appeal
- Decisions explained publicly

### 4. Member Veto

- At Stage 3+, member assembly can overrule Commons decisions
- Requires 60% vote to override
- Prevents Commons power grab

### 5. Financial Transparency

- Quarterly financial reports published
- Budget visible to all members
- Revenue distribution published
- External audit required (Stage 3+)

### 6. Infrastructure Ownership

- Commons infrastructure owned by legal entity (cooperative, foundation)
- Not owned by individual stewards
- Prevents person from controlling infrastructure through ownership

### 7. Credential Rotation

- API keys and access credentials rotated regularly
- No person has permanent "master key"
- Multi-signature required for critical changes

### 8. Regular Chaos Drills

- Founders intentionally step back quarterly
- System must function without them
- Tests whether succession actually works

---

## 10. Decision Matrix: Who Decides What

| Decision | Individual | Team Leader | Commons | Member Assembly |
|----------|---|---|---|---|
| Create project | ✓ | - | - | - |
| Join project | ✓ | - | - | - |
| Leave project | ✓ | - | - | - |
| Project objective | - | ✓ | - | - |
| Team recruitment | - | ✓ | - | - |
| Technical approach | - | ✓ | - | - |
| Member compensation | - | ✓ | - | - |
| Project confidentiality | - | ✓ | - | - |
| Identity verification | - | - | ✓ | - |
| Reputation credit | - | Recommends | ✓ | - |
| Arbitration decision | - | - | ✓ (panel) | - |
| Member removal | - | - | ✓ | - |
| Governance change | - | - | ✓ (proposes) | ✓ (votes) |
| Constitutional amendment | - | - | - | ✓ (2/3 vote) |
| Revenue distribution | - | Individual/Commons per agreement | ✓ | - |
| Commons budget | - | - | ✓ (proposes) | ✓ (approves) |
| Major policy | - | - | ✓ (proposes) | ✓ (votes) |

---

## Summary

SHADOW's topology evolves from:
- **Flat network** (5–15 members) →
- **Cluster + Commons** (15–250 members) →
- **Federated clusters** (250–1,000 members) →
- **International cooperative** (1,000+ members)

At every scale, the architecture maintains:
- ✓ Project autonomy
- ✓ Member agency
- ✓ Commons service orientation (not command)
- ✓ Distributed authority
- ✓ Transparent decision-making
- ✓ Anti-centralisation safeguards

The topology scales **without recreating hierarchy**, because governance evolves to match complexity, not concentrate power.

