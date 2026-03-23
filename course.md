# SRE Bootcamp with career support (40 Hours | 8 Weeks)

## Program Architecture
- Mode: Virtual
- Weeks: 8
- Target Audience: Devops Engineer, System Admin, Network Admin, Automation Engineer, SDE, Cloud Engineer, Performance Engineer, Application Support 
- Hours: 40 total
  - Weekday: 1 hrs × 1 day/wk → 8 hrs
  - Saturday: 1 hrs × 1 day/wk → 8 hrs
  - Self-study and Hands-on: 3 hrs × 1 day/wk → 24 hrs
- Modality: Theory + Case Studies + Labs
- Assessment: Labs + Weekly Toil Challenges + Capstone Project
- Outcome: SRE Practitioner 

## Career Support
- LinkedIn positioning & personal brand
- Strategic community participation
- Conference exposure & networking
- Building SRE credibility through content
- Presenting talks / papers
- Proof-of-work portfolio
- Alumni + mentor connect
- Job search strategy for SRE pivot

## Theme Sequencing Rationale
Logical progression:
Service Contract → Visibility → Engineering Reliability → Change Risk → Failures → Optimization → Scaling SRE

## Detailed Week-by-week Outline

## 📅 Week 1 — Foundation + Service Levels (5 hrs)
### Objectives
- Understand how to define and measure service health using SLIs/SLOs.
- Translate business expectations into service contracts (SLA/SLO).
- Use error budgets as a risk management and release decision tool.
- Introduce reliability vs velocity tradeoffs in practical contexts.
### Outcomes
- Can define SLIs/SLOs for any service.
- Can construct error budget policies and link actions to budget burn.
- Can negotiate reliability targets with product & leadership.
- Can reason about reliability as a business constraint, not just technical metric.
### Concepts
- What is SRE vs DevOps (mindset shift)
- Reliability as a business function
- SLA vs SLO vs SLI
- Error Budgets & Policy
- Reliability vs Agility Tradeoffs
- Risk-based Decision Making
### Case Studies
- Google SLO Framework
- E-commerce SLA Breach → Business Outcomes
### Hands-on Lab
- Define SLIs & SLOs for a sample service (e.g. Checkout API)
- Draft Error Budget Policy & Decision Matrix
- Deliverable
- SLO Charter

## 📅 Week 2 — Observability (5 hrs)
### Objectives
- Learn observability pillars (metrics, logs, traces, profiles).
- Understand instrumentation strategies (OTEL) and telemetry pipelines.
- Build high-signal dashboards & actionable alerting.
- Use observability to accelerate debugging and improve MTTR.
### Outcomes
- Can instrument services for rich telemetry.
- Can design dashboards that answer “Why is this slow/off?”
- Can reduce alert fatigue using better signal/noise ratios.
- Can apply observability for incident diagnosis and prevention.
### Concepts
- Telemetry Pillars (Metrics, Logs, Traces, Profiles)
- OTEL Standard
- Monitoring vs Observability vs Insight
- Instrumentation Strategy
- Alerting & On-call Quality
### Case Studies
- “The page was slow” → tracing root-cause
- Alert Fatigue & Noise Budget
### Hands-on Lab
- Instrument a microservice w/ OTEL
- Create dashboards + alert rules
### Deliverable
- Observability Pack

## 📅 Week 3 — Reliability Engineering (5 hrs)
### Objectives
- Understand failure modes, cascading failures, and systemic risk.
- Learn distributed system patterns for resilience.
- Apply performance, capacity, and degradation strategies.
- Introduce chaos & gameday as structured reliability validation.
### Outcomes
- Can design services that fail gracefully.
- Can identify and mitigate reliability bottlenecks (CPU, DB, network).
- Can use resiliency techniques (timeouts, retries, backoff, circuit breakers).
- Can model failure domains and plan for blast-radius containment.
### Concepts
- Failure Domains & Modes
- Distributed Systems Reliability
- Consistency vs Availability Tradeoffs
- Retry/Backoff/Timeout Patterns
- Capacity Planning + Performance
- Chaos & GameDays (Intro)
### Case Studies
- Netflix: Regional evacuation
- Payment Processor: Cascading failure
### Hands-on Lab
- Fault injection (latency + partial failures)
- Performance budget analysis

## 📅 Week 4 — Release & Change Management (5 hrs)
### Objectives
- Connect releases to risk budgets & error budgets.
- Understand deployment strategies for safe rollouts.
- Enable progressive delivery and automated rollback mechanisms.
- Improve CI/CD safety and velocity synergistically.
### Outcomes
- Can choose appropriate deployment strategy (canary, blue/green, etc).
- Can link SLOs to release decisions, freeze, or rollback.
- Can improve stability without reducing delivery speed.
- Can operationalize release risk governance across teams.
### Concepts
- Release Strategies (Blue-Green, Canary, Rolling)
- Progressive Delivery
- Deployment Safety
- Release vs Risk Budget
- CI/CD for SLO governance
### Case Studies
- Feature flag rollback save
- Bad deployment + error budget burn
### Hands-on Lab
- Progressive rollout w/ automated rollback via SLO guardrails

## 📅 Week 5 — Incident & Problem Management (5 hrs)
### Objectives
- Learn structured incident handling & escalation.
- Reduce MTTA/MTTR through comms, tooling, and runbooks.
- Enable blameless postmortems and systemic learning.
- Differentiate between incident resolution vs root cause analysis vs problem mgmt.
### Outcomes
- Can coordinate high-severity incidents effectively.
- Can produce high-quality blameless postmortems.
- Can institutionalize learning across teams for reliability improvements.
- Can build repeatable on-call and response processes.
### Concepts
- Incident Lifecycle
- Severity Models
- Incident Comms (internal vs external)
- Problem Management & Postmortems
- Timeline Reconstruction
- Escalation Playbooks + Runbooks
### Case Studies
- Real-world public outage analyses
- “Good postmortem vs bad postmortem”
### Hands-on Lab
- Simulated outage war-game (Zoom/Slack simulation)
- Write blameless postmortem

## 📅 Week 6 — Toil Reduction (5 hrs)
### Objectives
- Distinguish toil from engineering work and automation.
- Quantify toil impact across operations, CI/CD, and platform.
- Use automation & AI to eliminate repetitive manual operations.
- Design long-term toil elimination programs (not tactical scripting).
### Outcomes
- Can measure and prioritize toil reduction initiatives.
- Can justify automation investments with ROI and quality metrics.
- Can apply LLM/AI tools for ops workflows and incident timelines.
- Can drive continuous reduction of operational overhead in teams.
### Concepts
- What is Toil (Google definition)
- Toil vs Work vs Craft
- Automation ROI
- AI/LLM for Ops & Incident timelines
- Workflow Design for SRE
### Case Studies
- CI Pipeline toil → attrition
- Ticket elimination → developer satisfaction
### Hands-on Lab
- Identify toil → design automation → implement quick POC

## 📅 Week 7 — Cost & Efficiency Engineering (5 hrs)
### Objectives
- Introduce cloud cost economics and FinOps patterns.
- Connect cost with performance, reliability, and architecture.
- Teach cost-aware design, rightsizing, and resource efficiency.
- Integrate cost into release & production operations.
### Outcomes
- Can audit workloads for efficiency opportunities.
- Can optimize infra without compromising performance or reliability.
- Can use cost as a negotiating lever between product & infra teams.
- Can design efficiency SLOs / budgets for sustainable scaling.
### Concepts
- FinOps 101 for SRE
- Cloud Unit Economics
- Cost vs Reliability vs Performance
- Right-sizing & Efficiency Metrics
- Efficiency SLOs (Emerging pattern)
- Cost-aware Architecture (AWS focus)
- Chargeback & Accountability Models
### Case Studies
- Cost blowout & Cloud migrations
- SLO-driven scale-back
### Hands-on Lab
- Cost analysis on a sample workload
- Efficiency opportunity assessment

## 📅 Week 8 — Developer Experience Platform + Cultural Reliability (5 hrs)
### Objectives
- Understand how reliability scales through platforms, paved roads, and shared abstractions.
- Treat internal platforms as “products” with UX, feedback, and adoption curves.
- Reduce cognitive load on teams through standardized workflows & golden paths.
- Embed reliability into decision-making across product, finance, and engineering.
- Build blameless, learning-oriented cultures that improve after incidents.
- Enable cross-functional negotiation of SLOs, error budgets, and cost/performance tradeoffs.
### Outcomes
- Can identify developer experience bottlenecks across build→deploy→operate loops.
- Can design platform UX that increases autonomy & reduces operational friction.
- Can operationalize reliability adoption via SLO governance and postmortems.
- Can influence product & leadership decisions using reliability economics.
- Can drive cultural change where reliability becomes shared responsibility.
- Can scale SRE impact beyond tooling by shaping behaviors, incentives, and norms.
### Developer Experience Platform
- Golden Paths
- Paved Roads vs Choose-Your-Own
- Platform as a Product
- Internal APIs & Abstraction Layers
### Cultural Reliability
- SLO Adoption Culture
- Blameless Culture
- Reliability Product Mgmt
- Prioritization & Negotiation
- Organizational Anti-patterns
- Cross-functional decision-making
### Case Studies
- Why SRE orgs fail vs succeed
- Reliability negotiations w/ Product & Finance
### Hands-on Lab
- Platform UX redesign exercise
- Reliability policy design workshop

## Capstone Project (Final Week Deliverable)

A full end-to-end service reliability exercise:
Participants must:
- Define SLO/SLI
- Implement Observability
- Design Release Safety
- Simulate Incident
- Write Postmortem
- Submit Cost & Efficiency Report
- Present Reliability Strategy & Platform Recommendations

Capstone can be based on:
- e-commerce checkout
- payments microservice
- rideshare dispatching
- multi-tenant SaaS
or real corporate workloads (best)
