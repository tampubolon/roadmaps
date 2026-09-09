# Breaking into Cloud Sales (AWS / Azure / GCP)

A guide for a strong seller with an engineering degree, no IT industry experience, and English
at beginner level.

## Candidate profile

| | |
|---|---|
| **Background** | BSc Electrical Engineering, Institut Teknologi Sumatera |
| **Core strength** | Selling — proven |
| **IT industry experience** | None |
| **English** | ~A1. Limited phrases, cannot yet hold a conversation |
| **Target role** | Sales Engineer, cloud — Azure-deep, AWS/GCP conversational |
| **Timeline** | 12 months |

**Two corrections this profile forces on the advice below.**

First, an EE graduate is **not non-technical**. Maths, signals, circuits, digital logic and
probably some C or MATLAB are all transferable, and in Indonesia EE and telecom graduates are a
standard feeder into presales roles. Part 1's "aim for Account Executive instead" advice was
written for a non-technical seller and no longer applies — the Sales Engineer target is
appropriate. Part 1 is retained for the role map and vendor vocabulary.

Second, **English is now the gating skill, not Azure.** See Track B. It also changes which
employer is realistic at month 12 — see "Sequencing against the Indonesian market".


---

## First: pick the right role

**Sales Engineer is the technical role.** It isn't a seller who learned some cloud — it's an
engineer who learned to sell. With strong selling skill and no technical background, the right
targets are the roles *next to* the SE, where the SE is your partner:

| Role | What it is | Technical bar |
|---|---|---|
| **Account Executive / Account Manager** | Owns the relationship and the number; brings the SE in for technical work | Low–medium |
| **Partner / Channel Manager** | Sells through resellers and MSPs; relationship-heavy | Low |
| **SDR → AE at a reseller or MSP** | The realistic entry door with no enterprise-tech track record | Low |
| **AE at cloud-adjacent SaaS** (Datadog, Snowflake, HashiCorp) | Often easier to break into than the big three | Low–medium |
| **Sales Engineer / Solutions Architect** | Technical half of the deal — demos, PoCs, architecture | High |

SE remains reachable later, but it's a 1–2 year build with real hands-on work, not a study plan.
Better to get in the door as an AE and decide from the inside.

**What each vendor calls the technical role**, for reference:

- **AWS** — Solutions Architect (SA)
- **Microsoft** — Technical Specialist (pre-sales) / Cloud Solution Architect (post-sales)
- **Google Cloud** — Customer Engineer (CE)

---

## What to learn — four layers

The goal is not to build anything. It's to hold a credible conversation, ask good questions, and
know when to bring the SE in.

### Layer 1 — Vocabulary and mental model (2–3 weeks)

- What "the cloud" actually is: someone else's data centre, rented by the hour
- Server, virtual machine, container, database — in plain terms
- Why companies move: capex → opex, speed, scale, not staffing a data centre
- **Shared responsibility model** — who secures what (the vendor secures the platform, the
  customer secures what they put on it)
- Regions and availability zones; why data residency matters
- Public vs. private vs. hybrid vs. multi-cloud

You don't need to configure any of it. You need to never be the person in the room who visibly
doesn't know what a container is.

### Layer 2 — The three foundational certifications (6–10 weeks total)

All three vendors publish a foundational cert designed for non-technical staff — salespeople
specifically. Each is roughly 20–30 hours of study.

| Cert | Vendor | Cost | Notes |
|---|---|---|---|
| **AZ-900** Azure Fundamentals | Microsoft | ~$99 | Do this first — gentlest on-ramp |
| **Cloud Practitioner** | AWS | ~$100 | Broadest catalogue coverage |
| **Cloud Digital Leader** | Google | ~$99 | Most business-focused; effectively a sales course |

Holding all three is unusual and signals seriousness on a CV.

**Free study material, from the vendors themselves:**

- Microsoft Learn — free, and the best-written of the three
- AWS Skill Builder — free tier covers Cloud Practitioner
- Google Cloud Skills Boost — free tier covers Cloud Digital Leader

### Layer 3 — The commercial layer (ongoing, and the real differentiator)

This is where most junior AEs are weak and where selling skill compounds.

- **How cloud is bought** — not a one-off purchase. A committed spend agreement (AWS EDP,
  Microsoft EA/MACC, Google commit) plus consumption on top. The number carried is usually
  *consumption growth*, not deals closed.
- **Pricing mechanics** — on-demand vs. reserved/committed discounts; egress charges; why bills
  surprise people. Be able to open a pricing calculator and talk through a rough estimate.
- **Marketplace and private offers** — how third-party software is sold *through* the cloud
  vendor and drawn down against a customer's commitment. A big lever, and poorly understood.
- **Migration programmes** — vendors fund migrations (AWS MAP and equivalents at Azure/Google).
  Knowing free money exists is a real selling tool.
- **Who the buyers are, and what each one actually wants:**

| Buyer | Buys |
|---|---|
| CIO | Risk reduction and cost |
| CTO / VP Engineering | Developer speed and delivery |
| Head of Data | Analytics and AI capability |
| Head of Security | Control, compliance, auditability |
| Procurement | The discount and the contract terms |

### Layer 4 — Competitive positioning (a weekend, then keep current)

Two or three honest sentences on each:

- **AWS** — biggest and most mature, most services, engineers usually already know it.
- **Azure** — wins where the customer already runs Microsoft (Office, Windows, Active Directory);
  the deal arrives bundled with the existing enterprise agreement.
- **Google Cloud** — wins on data, analytics, and AI; usually the challenger fighting for a second
  seat rather than the incumbent.

Being straight about where your own vendor is weaker is what buys trust with technical buyers.
Bluffing is how deals are lost.

---

## Useful background: the same primitives, different names

Not for memorising — for recognising when a customer says a name you don't know.

| Concept | AWS | Azure | Google Cloud |
|---|---|---|---|
| Virtual machines | EC2 | Virtual Machines | Compute Engine |
| Object storage | S3 | Blob Storage | Cloud Storage |
| Managed Kubernetes | EKS | AKS | GKE |
| Serverless functions | Lambda | Functions | Cloud Functions |
| Relational database | RDS / Aurora | Azure SQL | Cloud SQL |
| Data warehouse | Redshift | Synapse / Fabric | BigQuery |
| Identity | IAM | Entra ID | IAM |
| Networking | VPC | VNet | VPC |
| Monitoring | CloudWatch | Azure Monitor | Cloud Operations |

Three genuine differences worth knowing, because they come up in real deals:

1. **Google's network is global**; AWS and Azure networks are regional. Changes multi-region design.
2. **Azure's identity is Entra ID** — which is already the customer's corporate directory. This is
   why Azure wins CIO conversations and why licensing and technology are inseparable there.
3. **BigQuery separates storage from compute** with no cluster to manage. The single biggest
   Google differentiator in data conversations.

---

## Getting hired

The big three rarely hire AEs with zero tech-sector background. The reliable path:

1. **Join a cloud reseller, MSP, or distributor** — Softcat, Insight, Rackspace, Presidio, and
   local equivalents. They hire proven sellers and teach cloud on the job.
2. **Or join a cloud-adjacent SaaS** as an SDR/AE — faster hiring, real cloud exposure.
3. **After ~2 years**, the big three become realistic.

---

## Two things worth taking seriously

**Don't wait to feel ready.** Three fundamentals certs plus the ability to run a good discovery
call already clears the bar for entry cloud sales. Technical depth accumulates on the job, working
next to SEs.

**Get genuinely good at cost conversations.** For a non-technical seller this is the fastest
credibility win available: almost nobody is good at it, customers care enormously about it, and it
is entirely learnable without writing a line of code.

---

## First 90 days — a concrete plan

| Weeks | Focus |
|---|---|
| 1–3 | Layer 1 vocabulary. Start Microsoft Learn's AZ-900 path. |
| 4–5 | Sit AZ-900. |
| 6–8 | AWS Cloud Practitioner via Skill Builder; sit the exam. |
| 9–11 | Google Cloud Digital Leader; sit the exam. |
| 9–12 | In parallel: the commercial layer — pricing calculators, committed-spend models, buyer personas. |
| 10–12 | Start applying to resellers/MSPs and cloud-adjacent SaaS. Certs are already in hand. |

---

# 12-Month Roadmap: Non-Technical Seller → Cloud Sales Engineer (Azure-deep)

**Target role:** Sales Engineer / Solutions Engineer, cloud — able to hold AWS and GCP
conversations, with genuine depth in Azure (Microsoft's equivalent titles: Technical Specialist
for pre-sales, Cloud Solution Architect for post-sales).

**Time budget:** ~12 hours/week, ~600 hours over the year. Roughly **half must be hands-on
keyboard time**, not video. Certificates get the interview; building a working demo live is what
passes the loop.

**Honest framing:** this is demanding from a non-technical start. It is achievable, and the single
variable that decides it is hands-on hours. Anyone who does only the certs will fail the technical
screen.

---

## The seven technical skills that must actually be acquired

Certs are scaffolding around these. If any is missing at month 12, the interview will find it.

1. **Linux and the command line** — navigate a filesystem, read logs, SSH, edit files, run scripts
2. **Networking** — IP/CIDR, DNS, TLS/certificates, load balancers, firewalls, VPN, private connectivity
3. **Identity** — Entra ID, RBAC, service principals, managed identities, SSO via SAML/OIDC
4. **Infrastructure as Code** — Terraform and Bicep, at read-and-modify level minimum
5. **Containers** — Docker, and AKS/Container Apps at deploy-and-troubleshoot level
6. **Data** — SQL at query level; what a warehouse is; Fabric/Synapse vs. BigQuery vs. Snowflake
7. **Scripting** — PowerShell and/or Python, enough to read, modify, and demo

Plus five SE craft skills, which are learned by practice, not study:

- Technical discovery (asking, not pitching)
- Live demo without a script
- Whiteboarding an architecture while talking
- Scoping and running a PoC
- TCO and cost modelling

---

## Quarter 1 — Months 1–3: Foundations and first contact with a keyboard

**Goal:** stop being a non-technical person. Get comfortable in a terminal and in the Azure portal.

### Certifications
- **AZ-900** Azure Fundamentals *(month 2)*
- **SC-900** Security, Compliance & Identity Fundamentals *(month 3)* — cheap, and security
  questions dominate real SE conversations
- **AI-900** AI Fundamentals *(optional, month 3)*

### Hands-on (the important part)
- Open an **Azure free account** and a **personal pay-as-you-go subscription** with a hard budget
  alert at a small number. Spending real money creates real cost intuition.
- Deploy by hand, in the portal, then repeat via CLI: a Linux VM, a VNet with two subnets and an
  NSG, a storage account, an Azure SQL database, an App Service.
- Break things deliberately: block a port and diagnose it, misconfigure a firewall rule, let a
  certificate expire.
- Learn Linux basics — `ls`, `cd`, `cat`, `grep`, `tail`, `ssh`, `vim` or `nano`. Any free
  "Linux Journey"-style course. ~15 hours total.
- Networking fundamentals — subnetting, DNS records, what TLS actually does. ~15 hours.

### Sales craft
- Read the **Microsoft Cloud Adoption Framework (CAF)** and **Well-Architected Framework (WAF)**
  overviews. These are the vocabulary of every Azure architecture conversation.
- Start a running notes file: every unfamiliar term, defined in one plain sentence.

### Month 3 checkpoint — on track if he can:
- Explain the shared responsibility model to a CIO and to an engineer, differently
- SSH into a VM he built and read a log file
- Draw a VNet with subnets, an NSG, and a load balancer on a whiteboard from memory

---

## Quarter 2 — Months 4–6: Real Azure competence

**Goal:** AZ-104 is the pivot point of the whole year. It's the first cert that requires actual
skill, and it's what makes an SE interview possible.

### Certifications
- **AZ-104** Azure Administrator Associate *(month 6)* — the hard one. Budget 80–100 hours.
- **AWS Certified Cloud Practitioner** *(month 5, low effort alongside)* — keeps the multi-cloud
  story alive

### Hands-on
- **Infrastructure as Code**: rebuild everything from Q1 in **Bicep**, then again in **Terraform**.
  This is the highest-leverage skill on the list — it makes demos repeatable and resettable.
- **Identity deep-dive**: Entra ID users, groups, RBAC roles at subscription/resource-group scope,
  service principals, managed identities. Configure SSO to a sample app. Identity is the #1
  enterprise pre-sales topic.
- **Containers**: Docker basics, push an image to Azure Container Registry, run it on Container
  Apps, then on AKS.
- **Observability**: Azure Monitor, Log Analytics, one KQL query written from scratch.
- **PowerShell or Python**: enough to read a script and change it. ~20 hours.

### Sales craft
- **Azure Landing Zones** — what they are and why every enterprise deployment starts there
- **Azure pricing calculator** — build three real TCO estimates for imagined customers
- **Azure Hybrid Benefit**, Reservations, Savings Plans — how Azure discounting actually works
- Watch 10 recorded Microsoft partner/technical webinars purely to absorb how SEs speak

### Month 6 checkpoint — on track if he can:
- Pass AZ-104
- Stand up a working three-tier app in Azure from a Terraform file, from scratch, in under an hour
- Explain to a customer why their Azure bill is what it is

---

## Quarter 3 — Months 7–9: Architecture, breadth, and a demo portfolio

**Goal:** move from "can administer" to "can design and present". Add credible AWS/GCP breadth.

### Certifications
- **AZ-305** Designing Microsoft Azure Infrastructure Solutions → **Azure Solutions Architect
  Expert** *(month 9)* — requires AZ-104. This is the credential that says "SE".
- **AWS Solutions Architect Associate** *or* **Google Associate Cloud Engineer** *(month 8)* —
  pick one, not both. AWS if the target market is startups/tech; GCP if data/AI.

### Hands-on — build the demo portfolio
This is what he'll actually show in interviews and, later, to customers. Three repeatable demos,
each fully scripted in IaC so they can be torn down and rebuilt in minutes:

1. **App modernisation** — a containerised app on AKS or Container Apps, with CI/CD from GitHub
   Actions or Azure DevOps, Key Vault for secrets, and Application Insights for monitoring
2. **Migration** — a "legacy" VM-based app moved to PaaS (App Service + Azure SQL), with a
   before/after cost comparison
3. **Data + AI** — data landing in a storage account, into Fabric or Synapse, with an Azure
   OpenAI / AI Foundry component on top. This is where the current market's money is.

Cross-cloud: rebuild demo #1 on **AWS (EKS or App Runner)** and on **GCP (Cloud Run)**. Two
weekends each. This produces the war stories that make multi-cloud conversations credible.

### Sales craft — start practising the actual job
- **Discovery calls**: learn a framework (MEDDIC, or Microsoft's own qualification model). Run
  10 mock discovery calls with anyone who'll play customer.
- **Whiteboarding**: practise drawing an architecture *while talking*. Record it. Watch it back.
  Painful and effective.
- **Demo delivery**: deliver each portfolio demo to a live human 5 times. The fifth is the good one.
- **Objection handling**: write out honest answers to "why not AWS", "isn't this lock-in", "our
  data can't leave the country", "the bill will be unpredictable".
- **Competitive**: Azure vs. AWS vs. GCP per workload type — compute, data, AI, identity, hybrid.

### Month 9 checkpoint — on track if he can:
- Pass AZ-305
- Deliver a 20-minute demo, live, handling interruptions, without notes
- Answer "how would you migrate this" with a defensible architecture and a cost estimate

---

## Quarter 4 — Months 10–12: Specialise, polish, and get hired

**Goal:** one deep specialty, interview-ready, applications out.

### Certifications — pick ONE specialty and go deep
| Specialty | Cert | Choose if |
|---|---|---|
| **Security** | **AZ-500** Azure Security Engineer | Highest demand; security blocks the most deals |
| **AI / Data** | **AI-102** Azure AI Engineer, or **DP-700** Fabric Data Engineer | Where budget is moving fastest |
| **Networking** | **AZ-700** Azure Network Engineer | Enterprise/hybrid-heavy markets |

*Microsoft rotates its exam catalogue — verify current codes on Microsoft Learn before booking.*

Recommendation: **AZ-500**. Security questions appear in every deal regardless of specialty, and
it pairs with SC-900 already held.

Also consider **Microsoft Applied Skills** — short, free, scenario-based credentials that fill
gaps quickly and show current hands-on ability.

### Hands-on
- Harden the demo portfolio: Defender for Cloud, Private Endpoints, Key Vault, Azure Policy,
  network isolation. "Here's the same demo, now enterprise-secured" is a strong interview moment.
- Build one **PoC-in-a-box**: a scoped, time-boxed proof of concept with defined success criteria,
  exactly as an SE would run for a customer.

### Sales craft — the commercial layer, seriously
- **EA / MACC / CSP** — how Azure is contracted, and how commitment drawdown works
- **Azure Marketplace private offers** — a major and poorly understood deal lever
- **Migration funding** — Azure Migrate programmes and partner incentives
- **RFP/security questionnaire** practice — answer a real public-sector cloud RFP for training

### Job search — start month 10, not month 12
- Target order: **Microsoft partners and CSPs first** (they hire on potential and Azure certs),
  then cloud-adjacent ISVs, then Microsoft itself
- Rebuild the CV around **demos built and problems solved**, not certificates listed
- Publish the portfolio: a GitHub repo of the IaC, plus 3 short recorded demo videos. For a
  career-changer this outperforms any CV bullet.
- Interview loops: expect a **technical presentation to a mock customer panel**. Rehearse it 10
  times. This is the round career-changers lose.

### Month 12 checkpoint — ready if he can:
- Hold **AZ-104 + AZ-305 + one specialty**, plus AWS or GCP associate-level
- Build and present a working Azure solution live, from IaC, under questioning
- Run a discovery call that ends with a qualified technical requirement, not a feature dump
- Model a customer's Azure cost and defend the number

---

## Cadence and cost

**Weekly rhythm (~12 hrs):**

| Block | Hours | Activity |
|---|---|---|
| Study | 4 | Microsoft Learn paths, exam prep |
| Build | 5 | Hands-on labs and portfolio work |
| Craft | 2 | Mock demos, discovery practice, whiteboarding |
| Watch | 1 | Recorded technical webinars, competitive reading |

**Budget for the year:** exams ~$800–1,000 total; Azure lab spend ~$20–50/month with budget alerts
and disciplined teardown; everything else (Microsoft Learn, AWS Skill Builder, Google Cloud Skills
Boost) is free.

**The three failure modes to watch for:**

1. **Cert collecting without building.** Fatal. If a month passes with no hands-on hours, the plan
   has already failed regardless of what got passed.
2. **Going wide too early.** Azure depth first; AWS and GCP are breadth, not parallel tracks.
3. **Leaving sales craft to the end.** Demo and whiteboard skill needs 6 months of repetition. It
   cannot be crammed in month 12.

---

# Track B — English from A1 to Working Fluency

Everything above is **Track A**. It cannot be delivered without Track B, because a Sales Engineer's
entire job is talking: discovery calls, whiteboards, demos, objection handling, panel interviews.
Azure skill with no English produces someone who can build but cannot sell.

## The honest arithmetic

Cambridge's published guidance for cumulative guided study hours:

| CEFR level | Cumulative hours | What it means in practice |
|---|---|---|
| A1 | — | Current position: isolated phrases |
| A2 | ~180–200 | Survives simple exchanges |
| B1 | ~350–400 | Handles routine work conversation, slowly |
| **B2** | **~500–600** | **Working proficiency — can do the job, with effort** |
| C1 | ~700–800+ | "Professional level" — fluent, persuasive, handles pressure |

So from A1, reaching **B2 costs roughly 500–600 hours**, and C1 another 200–300 on top.

**In 12 months, B2 is achievable. C1 is not.** Anyone promising otherwise is selling a course.
B2 is enough to work as an SE at an Indonesian partner. C1 arrives in year two, on the job, which
is where it is actually built anyway.

## The insight that makes both tracks fit in one year

**Do 100% of the technical study in English.** Not translated, not dubbed, not summarised into
Bahasa. Microsoft Learn in English. Azure Friday and Microsoft Mechanics on YouTube with English
subtitles. Notes in English. Demo rehearsals recorded in English.

Done this way, Track A's ~600 hours are *also* ~600 hours of English input, in exactly the
vocabulary the job requires. The incremental cost of English drops from a second full curriculum
to **~250–300 hours of dedicated speaking, pronunciation and grammar work** — the parts that
technical study cannot supply.

It is slower at first. Month 1 studying AZ-900 in English will feel twice as hard as studying it
in Bahasa. By month 4 it is faster, because the vocabulary is no longer being learned twice.

## Revised weekly budget

| Track | Hours/week | Notes |
|---|---|---|
| **Track A** — technical, conducted in English | 12 | As specified above |
| **Track B** — dedicated English | 6 | Speaking, pronunciation, grammar |
| **Total** | **18** | ~2.5 hrs/day, or 2 hrs weekdays + 4 hrs each weekend day |

18 hours a week alongside a full-time job is hard but survivable for a year. If it proves
unsustainable, **cut Track A's cross-cloud work (AWS/GCP), never Track B.** English is the
constraint on employability; a second cloud is not.

## Phase 1 — Months 1–3: Survival English (A1 → A2)

**Target:** hold a five-minute conversation about himself and his work, badly but successfully.

- **Speaking with a tutor: 5 × 30 min per week.** Non-negotiable, and the highest-ROI spend in the
  entire plan. italki, Preply, or Cambly — tutors at $5–12/hour, affordable from Indonesia.
  Book them as fixed calendar appointments, not "when there's time".
- **Pronunciation from day one.** ELSA Speak or similar for Indonesian-speaker-specific issues —
  final consonants, /v/ vs /f/, /θ/, word stress. Fixing accent early is far cheaper than
  correcting it at B2.
- **Core vocabulary: the 1,000 most frequent English words**, via Anki, 20 new cards/day.
- **A real textbook**, not just apps: English File or Headway, Elementary level. Apps like Duolingo
  are supplements, never the spine.
- **Listening:** VOA Learning English (deliberately slow), then BBC Learning English "6 Minute
  English". 15 min daily.
- **Technical crossover starts now, gently:** read Microsoft Learn AZ-900 pages in English with a
  translator open beside them. Do not skip to the Bahasa version.

**Month 3 test:** EF SET (free, ~50 min, CEFR-mapped). Target A2.

## Phase 2 — Months 4–6: Technical English (A2 → B1)

**Target:** describe an Azure architecture out loud, in English, slowly.

- **Cut the translator.** All AZ-104 study in English only. This is the hard transition and the
  one that pays.
- **Shadowing:** pick a 3-minute segment of a Microsoft Mechanics video, play a sentence, pause,
  repeat aloud copying rhythm and stress. 15 min daily. Unglamorous and extremely effective.
- **Tutor sessions shift topic:** stop discussing hobbies, start explaining Azure. Ask the tutor
  to play a customer. He now has something worth saying, which is when adult language acquisition
  accelerates.
- **Output daily:** a 5-sentence written summary in English of whatever was studied that day.
- **Grammar focus:** the tenses that carry business conversation — present perfect, conditionals
  ("if you migrated, you would…"), modals of possibility and recommendation.

**Month 6 test:** EF SET. Target B1. Also: explain, unscripted and in English, what a VNet is and
why it matters — recorded, 2 minutes.

## Phase 3 — Months 7–9: Presentation English (B1 → B1+/B2)

This phase merges completely with Track A's demo work. Every demo rehearsal is an English lesson.

- **Every portfolio demo is rehearsed and recorded in English.** Five deliveries each. Watch the
  recordings — painful, and the fastest correction loop available.
- **Presentation language patterns**, learned as fixed phrases rather than assembled grammar:
  signposting ("let me walk you through…", "the key point here is…"), handling interruption
  ("good question — let me come back to that"), buying time ("that's a fair challenge…").
- **Discovery-call English:** question forms are their own skill. "What does your current setup
  look like?", "What happens today when that fails?", "Who else needs to be comfortable with this?"
- **Find live English practice:** English-language tech meetups and Discord/Slack communities,
  online Azure user groups. Speaking to strangers about technical topics is the real test.
- **Tutor sessions become mock customer calls.** Brief the tutor to interrupt and object.

**Month 9 test:** deliver a full 20-minute demo in English to a fluent speaker who asks hostile
questions.

## Phase 4 — Months 10–12: Interview and workplace English (B2)

- **Interview English specifically:** STAR-format answers, prepared and rehearsed until fluent.
  "Tell me about yourself" and "why this role" should be word-perfect — they are the first
  90 seconds of every interview and they set the interviewer's expectation of his English.
- **Mock interviews** with a fluent speaker, at least 10. Including the technical presentation
  round.
- **Written business English:** follow-up emails, meeting notes, a one-page architecture summary.
  Much easier than speaking, and it visibly raises perceived competence.
- **Optional formal certificate**, if employers in his target list ask for one: Duolingo English
  Test (cheap, fast, widely accepted) or Linguaskill Business (Cambridge, business-specific).
  IELTS/TOEFL are aimed at universities and are usually unnecessary here.

**Month 12 test:** EF SET. Target B2. Real test: get through a 45-minute technical conversation
with a stranger without switching languages.

## English milestones alongside the technical track

| Month | Track A | Track B |
|---|---|---|
| 3 | AZ-900, SC-900 | A2 — simple conversation |
| 6 | **AZ-104** | B1 — explains architecture slowly |
| 9 | **AZ-305** + demo portfolio | B1+/B2 — delivers a demo in English |
| 12 | AZ-500 + applications out | B2 — survives an interview panel |

---

# Sequencing Against the Indonesian Market

English level determines *which employer* is realistic at month 12, and this is the strategic
decision in the whole plan.

## Two tiers of employer, two different English bars

**Tier 1 — Indonesian partners, CSPs and system integrators. Realistic at month 12.**

Working language is usually Bahasa Indonesia; customers are Indonesian; English is needed for
documentation, vendor portals and occasional regional calls. **B2 is sufficient. B1+ may pass.**
Examples to research and verify: Central Data Technology / CTI Group, Metrodata (MII),
Multipolar Technology, TelkomSigma, Elitery, Zettagrid, Lintasarta, Berca Hardayaperkasa, NTT
Indonesia. Microsoft's Indonesia Central region has increased local Azure demand, and these firms
hire presales staff on certifications plus aptitude.

**Tier 2 — Microsoft Indonesia itself, or regional roles run out of Singapore. Month 18–30.**

Working language is English throughout, including internal meetings, and the interview loop is in
English under pressure. **C1 in practice.** This is year two or three, entered from Tier 1.

## The recommended path

1. **Months 1–12** — Track A + Track B as specified. Target Tier 1.
2. **Months 12–18** — working as a presales engineer at an Indonesian partner. English improves
   fastest here, because it is now used daily under real stakes rather than studied.
3. **Months 18–30** — with real deal experience and C1 English, Tier 2 becomes reachable.

Trying to reach Tier 2 directly at month 12 will fail on English alone, regardless of how good the
Azure skills are. Tier 1 is not a consolation prize — it is the standard route, and it is how most
Indonesian presales engineers at the vendors got there.

## What his EE degree is worth here

More than he probably thinks. Indonesian partners hiring presales staff routinely recruit from
electrical, telecom and informatics engineering backgrounds. The degree signals technical aptitude
and study discipline, which is exactly what a hiring manager is trying to establish for a
career-changer. It should be foregrounded on the CV, not buried — paired with AZ-305 it reads as
"engineer who moved into presales", which is the most credible story available to him.

---

# The Three Things That Decide This Plan

1. **Tutor hours in Phase 1.** Five sessions a week for three months, starting immediately. If
   this slips, everything downstream slips, because every later phase assumes a conversational
   base exists.
2. **Studying Azure in English from month 1.** The single decision that makes 12 months feasible
   instead of 24. It will feel inefficient for eight weeks. Do it anyway.
3. **AZ-104 by month 6.** The pivot point of the technical track. If it slips past month 7, drop
   the AWS/GCP breadth work rather than compressing AZ-305 and the demo portfolio.

**And the thing to protect:** if the 18 hours a week proves impossible, cut technical breadth,
never English. An SE with deep Azure and no English is unemployable in this role. An SE with good
English and moderate Azure gets hired and learns the rest on the job.

---

# Compensation — Jakarta Market

**Confidence warning:** these are estimates from general market knowledge, not a dataset.
Indonesian salary data is far less transparent than US/EU. Use them to calibrate expectations,
then verify against the sources at the end of this section.

All figures are **gross monthly base salary**, the way Indonesian offers are actually quoted.
Variable/bonus is excluded. Conversions at roughly IDR 16,000/USD.

## Tier 1 — Local partners, CSPs, system integrators

Metrodata (MII), CTI Group / Central Data Technology, Multipolar Technology, TelkomSigma,
Elitery, Zettagrid, Lintasarta, Berca Hardayaperkasa.

| Level | Monthly base (IDR) | ≈ Annual, 13 mo (IDR) | ≈ USD/yr |
|---|---|---|---|
| Entry presales (0–2 yrs) | 8–15 juta | 104–195 juta | $6.5k–12k |
| Mid (3–5 yrs) | 18–30 juta | 234–390 juta | $15k–24k |
| Senior / lead (6+ yrs) | 30–50 juta | 390–650 juta | $24k–40k |

## Tier 2 — Vendors and global SaaS with a Jakarta presence

Microsoft Indonesia (Technical Specialist / Cloud Solution Architect), AWS Indonesia (Solutions
Architect), Google Cloud Indonesia (Customer Engineer), plus ISVs such as Datadog, Snowflake,
Salesforce.

| Level | Monthly base (IDR) | ≈ Annual, 13 mo (IDR) | ≈ USD/yr |
|---|---|---|---|
| Mid SA / CSA / CE | 45–75 juta | 585–975 juta | $36k–60k |
| Senior / principal | 75–120 juta | 975 juta – 1.56 M | $60k–95k |

The gap between the two tiers is commonly **2–3×**. This is why the Tier 1 → Tier 2 move in years
2–3 matters more financially than any decision made during year one.

## Factors that distort these numbers

- **THR is mandatory** — at least one month's salary before the religious holiday, so annual is a
  minimum of 13×. Some firms pay 14–16 months.
- **Presales is base-heavy** — typically a 70/30 or 80/20 base/variable split, unlike an Account
  Executive's 50/50. The base figures above are therefore most of the package.
- **Vendor roles add equity.** Microsoft, AWS and Google all grant RSUs to Indonesian staff,
  potentially adding 20–40% on top. This never appears in base-salary surveys.
- **Regional roles are a separate market.** Some Indonesia-covering positions are hired out of
  Singapore at Singapore rates — worth targeting explicitly once English reaches C1.

## The year-one reality

For someone currently managing a sales team, **moving into presales at month 12 is most likely a
pay cut, not a raise.** A career-changer holding AZ-305 but with no presales track record lands at
the entry-to-low-mid band of Tier 1 — realistically **IDR 12–20 juta/month**, with a selling
background and an engineering degree pushing toward the upper half of that rather than the floor.

The recovery is quick: mid band by year 2–3, Tier 2 by year 3–5, ending materially ahead of where
staying put would have led. But this needs to be understood **before** starting, not discovered at
the offer stage. Year one is an investment year, and that is the point at which most people
abandon a career change.

## Where to verify

1. **Robert Walters Indonesia Salary Survey** and **Michael Page Indonesia Salary Guide** — free
   annual PDFs, both break out "Pre-Sales / Solution Engineer" as a line item. Best available
   sources.
2. **Glassdoor Indonesia, JobStreet, Kalibrr** — actual posted ranges, though often understated.
3. **LinkedIn, directly.** Message two or three presales engineers at Indonesian partners and ask.
   Indonesian tech people are generally open about ranges in DMs, and this beats every survey.
