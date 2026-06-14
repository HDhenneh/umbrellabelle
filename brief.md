---
name: Umbrellabelle
stage: prototype (directory live, EOR/AOR section added June 2026)
accent: "#A78BFA"
domain: umbrellabelle.com
stack: Static HTML (Nightframe template) → Next.js when dynamic features required
journal: recruitment industry + contractor compliance
---

# Umbrellabelle

UK umbrella company directory, EOR/AOR global compliance platform, and the emerging standard-setter for an industry that currently has no governing body.

**Tagline:** Are you covered?

**Short name:** Belle — as in *Ask Belle if you're covered.* International read: bella (Italian/Spanish), belle (French) — maps cleanly to European EOR expansion.

---

## The Problem

Contractors in the UK have no trustworthy comparison resource for umbrella companies. 900+ operate in the market. Only ~30 are FCSA-accredited. The rest are unverified — some are fraudulent mini-umbrella schemes that leave workers with HMRC tax bills. Workers choose blind, based on recruiter recommendation (which is often influenced by the umbrella's gifting programme, not its compliance record).

Globally, businesses hiring cross-border have an adjacent but larger problem: **there is no accreditation body for EOR or AOR providers.** The EOR market is growing from $6.8bn to $14bn+ by 2030. Providers range from platforms with owned legal entities in 180+ countries to brokers with a website and a partner network they don't control. Clients cannot tell the difference until something goes wrong. No body audits them. No mark signals quality. No complaints process exists.

This is the same pre-regulatory moment the UK umbrella market was in before FCSA was founded.

---

## Two Audiences. One Platform.

| Audience | Problem | Belle's solution |
|---|---|---|
| UK contractors | Which umbrella is safe, compliant, and cheap? | FCSA-verified directory + IR35 scorer + rate cards |
| HR directors / hiring managers | How do we hire compliantly in another country? | EOR/AOR directory + compliance landscape guide |
| Recruiters | Which umbrellas on our PSL are actually compliant? | PSL benchmarking + compliance alerts (Phase 2) |

---

## Architecture

```
umbrellabelle.com
├── Rate Cards          — HMRC-approved rates, sector benchmarks, umbrella margins
├── Golden Pay          — Take-home calculator (umbrella vs LTD vs PAYE)
├── IR35 Scorer         — 7-test risk check; clause analysis (Phase 2)
├── Umbrella Directory  — FCSA-verified listing cards with fee/compliance data
├── EOR & AOR           — Global hiring compliance directory + 5-risk explainer
└── For Recruiters      — PSL benchmarking + compliance monitoring (Phase 2)
```

---

## Revenue Model

| Stream | Mechanism | Phase |
|---|---|---|
| Umbrella affiliate | £50–100 per contractor placed (Parasol, Brookson, PayStream, Giant) | Phase 1 |
| EOR affiliate | £500–2,000 per referred customer (Deel, Remote, Omnipresent) | Phase 1 |
| Belle Standard assessment | £5,000–15,000/year per assessed provider | Phase 2 |
| Belle Standard mark licence | Annual renewal fee for mark display rights | Phase 2 |
| Premium verified listings | Monthly subscription per umbrella/EOR for enhanced listing | Phase 2 |
| Recruiter PSL monitoring | Agency subscription for compliance alerts | Phase 3 |
| Belle Standard body membership | Annual membership fee if formal body established | Phase 3+ |

---

## The Belle Standard — Industry Accreditation Play

### The Gap

FCSA (Freelancer & Contractor Services Association) is the accreditation body for UK umbrella companies. Founded in 2004, it started as a self-regulatory initiative — a small group of compliant umbrella companies who wanted to differentiate themselves from mini-umbrella fraud operators. They wrote a standard, paid for audits, displayed the mark. HMRC now references FCSA membership in its guidance. The mark is the de facto signal of quality in a market of 900+ providers.

**No equivalent exists for EOR or AOR providers.** Anyone can claim to be an Employer of Record. There is no standard that defines what responsible EOR provision looks like, no audit process, no complaints mechanism, no mark that employers can trust.

This is not a niche gap. EOR platforms handle payroll for tens of thousands of workers across hundreds of countries. When they fail — and some do — workers go unpaid, companies face unexpected tax liabilities, data is mishandled. The industry is maturing faster than its governance.

### The FCSA Parallel

| Stage | FCSA (umbrella) | Belle opportunity (EOR/AOR) |
|---|---|---|
| Market state | 900+ operators, many fraudulent | 100+ platforms, quality wildly variable |
| Catalyst | Mini-umbrella schemes harming workers | PE risk mis-sold, broker EORs misrepresented as entity EORs |
| First move | Self-regulatory standard published | Belle Standard published as open framework |
| Build-out | Member audits, annual renewal | Provider assessments, mark licensing |
| Recognition | HMRC references FCSA in guidance | BEIS/HMRC/REC alignment |
| Outcome | Gold standard mark — PSL shorthand | Belle Verified mark — procurement shorthand |

### The Three Phases

**Phase 1 — De Facto Standard (Belle as author)**

Publish *The Belle Standard* as a free, public framework defining what responsible EOR/AOR provision looks like. No membership required, no fees. Providers are assessed against it in the Belle directory. The standard document is Belle IP.

This establishes Belle as the authority *before* any formal body exists — the audience is already here (the directory), the expertise is demonstrated (the compliance landscape content), and the standard fills a visible gap that providers will want to be seen to meet.

**Phase 2 — Rated Mark (Belle as assessor)**

Invite the top 8–10 EOR providers to undergo a formal Belle Standard assessment. Assessment is paid (£5,000–15,000/year). Providers who pass display the *Belle Verified* mark in their own marketing materials.

The mark is valuable because:
- Belle's directory audience is the EOR providers' customer base
- No equivalent mark exists — this is not competing with anything
- Providers who decline draw their own conclusions (a useful signal to publish)

**Phase 3 — Formal Body (Belle as convener)**

Convene a working group of assessed providers. Publish draft standards for industry consultation. Establish a body (company limited by guarantee — standard UK structure for industry bodies). Seek recognition from BEIS, REC, and CIPD.

Belle is the secretariat — the body is independent but Belle founded it, writes the standards, and runs the administrative function. This is exactly the FCSA structure.

### The Belle Standard — Accreditation Criteria

**Category 1: Entity Ownership (Critical)**

The most important quality signal in EOR is whether the provider owns legal entities in the countries it covers, or whether it operates through a network of third-party partners it does not control.

| Level | Description | Belle rating |
|---|---|---|
| Owned entity | Provider holds an in-country legal entity, employs workers directly | ✓ Full |
| Controlled partner | Long-term exclusive agreement with local PEO, SLA-governed | ✓ Partial |
| Spot broker | Third-party engagement on an ad-hoc basis | ✗ Not eligible |

**Category 2: Financial Robustness**

- Client money protection: worker payroll ring-fenced from operational funds
- Financial reserves: minimum capitalisation relative to payroll under management
- Insurance: professional indemnity + employer's liability per jurisdiction
- Audited accounts: independently audited, published or available on request

**Category 3: Compliance Infrastructure**

- Data protection: SOC 2 Type II or ISO 27001 certification
- GDPR: Article 28 Data Processing Agreement in place with all clients
- Standard Contractual Clauses (SCCs) for cross-border data transfers
- Named DPO (Data Protection Officer) or equivalent per jurisdiction

**Category 4: Client Protection**

- Transparent pricing: published fee structure, no hidden charges
- Contractual IP assignment: client's IP stays with client regardless of EOR employer status
- Termination handling: documented process, notice periods that comply with local law
- Complaint resolution: documented process with stated resolution SLA (target: 10 business days)

**Category 5: Worker Protection**

- Statutory benefits: local minimum statutory benefits met in all markets (not just salary)
- Benefits portability: worker benefits data transferable if client moves provider
- Worker communication: workers have direct contact with EOR, not just the client
- Payslip transparency: clear itemisation of gross/net, deductions, employer contributions

**Category 6: Operational Transparency**

- Country coverage disclosure: published list distinguishing owned entities vs partner coverage
- Incident reporting: data breaches and payroll failures reported to clients within 24hrs
- Annual review: published annual compliance summary (aggregate, not client-specific)

### The Scoring Model

Providers are scored across all six categories. Publication logic:

| Score | Belle directory status |
|---|---|
| 90–100% | Belle Verified ✓ — mark licensed |
| 75–89% | Belle Listed — flagged improvements noted |
| 50–74% | Listed with compliance caveats |
| < 50% | Not listed |

Providers who decline assessment are listed as *Unassessed* — which is itself a signal the market will interpret.

### Why Belle Can Own This

1. **Audience first.** Belle is already the directory HR directors use to compare EOR providers. The standard emerges from the authority the directory builds, not the other way round.

2. **No incumbent.** FCSA cannot extend into EOR — its mandate is domestic contractor employment. REC touches the space but doesn't own it. The EOR providers themselves are competitors, not collaborators. Belle is the only neutral party with the right positioning.

3. **Founder fit.** Building from inside a recruitment company pursuing agentic transformation. Direct knowledge of how PSLs work, how compliance fails, and what hiring managers actually need. This is not an outsider's view.

4. **DarkCRM flywheel.** The Belle Standard becomes the compliance signal that DarkCRM uses when routing candidates to umbrellas and EOR providers. The directory, the standard, and the CRM are one system.

### Risks

| Risk | Mitigation |
|---|---|
| Provider boycott of assessment | Start with willing providers; publish Unassessed status — peer pressure does the rest |
| Larger body (REC, CIPD) creates a competing standard | Move faster; publish first; establish the document as the reference |
| Standard challenged as not legally authoritative | Publish as a market standard, not a regulatory standard — same as FCSA |
| Founders lose control of the body | Retain secretariat role contractually; Belle IP stays with Belle |

---

## DarkCRM — The Long Game

Umbrellabelle is Phase 1 of DarkCRM, the lights-out agentic recruitment CRM.

The directory builds the audience. The IR35 scorer captures contractor emails. The Belle Standard builds provider relationships. DarkCRM monetises the full stack — routing candidates to the right umbrella or EOR provider, flagging compliance risks, and running 24/7 with human contact only at the relationship moment.

**GDPR architecture:** Store tokens, not PII. Fetch candidate data at point of use from source (LinkedIn URL), discard after. Internal comms use tokens only. Right to erasure satisfied by design.

**Interface:** Three states — Dark (nothing needs you), Amber (one-tap decision), Red (human on the line).

**Dark funnel:** Pixel on Belle directory. Anonymous visitor signals tracked against hashed fingerprint. When fingerprint matches known candidate, pre-contact dossier retroactively attached.

---

## Build Sequence

| Phase | What | Output |
|---|---|---|
| 1a | Directory live (done) | FCSA umbrella cards + rate cards + IR35 preview |
| 1b | EOR/AOR section (done) | 6 provider cards + compliance risks panel |
| 1c | Belle Standard draft | Public document at umbrellabelle.com/standard |
| 2a | IR35 Questionnaire Scorer | Email gate + affiliate trigger |
| 2b | Provider assessment programme | Belle Verified mark + assessment fee revenue |
| 2c | IR35 Contract Paste Scorer (Haiku) | Premium / freemium upgrade |
| 3a | Recruiter PSL monitoring | Agency subscription |
| 3b | DarkCRM beta | Directory audience as first cohort |
| 3c | Belle Standard working group | Convene top 8 providers |
| 4 | Formal body | Company limited by guarantee, Belle as secretariat |

---

## Score

| Dimension | Score | Reason |
|---|---|---|
| Market need | 5 | Genuine compliance vacuum — domestic AND global |
| Founder fit | 5 | Insider recruitment + compliance knowledge; direct access to first customers |
| Monetisation clarity | 5 | Affiliate (Phase 1) → assessment fees (Phase 2) → body membership (Phase 3) |
| Differentiation | 5 | No equivalent EOR standard exists. First-mover is winner. |
| Build complexity | 3 | Directory is simple; body creation is a multi-year relationship play |
| **Avg** | **4.6** | **Tier 1 — flagship** |
