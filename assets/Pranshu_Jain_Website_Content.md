# Pranshu Jain — Personal Website Content (v3)

Oct 3, 2026 · @Pranshu

## Before you publish

Four data points conflict across your sources or need a decision. Each section uses the version marked in bold; placeholders in [brackets] still need your input.

| Item | What the sources say | Used in this draft |
| --- | --- | --- |
| Escrow TAT | One-page CV: 60–90 days to 3–4 days. Detailed CV: 90 to 30 days (66%). LoR: "months to a few weeks" | **90 to ~30 days**, matching the LoR |
| DA share of AUM | Detailed CV says "20% by end of FY25" (typo) | **50% of AUM in FY25, 20% in FY26** |
| Confidentiality | AUM shares, disbursal volumes and AOP targets are Jio Credit internal figures | Confirm these are cleared for a public site |
| Inflation project | R² = 0.037 signals a weak relationship | Framed as a finding that inflation alone explains little |

## Experience

### Product Manager, MD & CEO's Office — Jio Credit Limited (Jio Financial Services)

Aug 2024 – Sep 2026 · Mumbai

**Role in one line:**  
PM and Business Planning Manager to the MD & CEO, owning lending products, strategic projects, banking system architecture and structured credit end to end.

**Roles and responsibilities**

- Business Planning Manager to the MD & CEO
- Loan Against Property (LAP): strategy, tech and processes
- Direct Assignment (DA): product and transactions
- Channel distribution (DSA network)
- Banking system architecture: Loan Origination System (LOS), Loan Management System (LMS), Lead Management System and Customer Servicing Portal
- New product initiatives

**Impact at a glance**

- 250% AUM growth roadmap authored in the FY26 Annual Operating Plan
- 50% of FY25 AUM and 20% of FY26 AUM from 10 DA transactions
- 92% of monthly mortgage disbursals sourced through a 530+ DSA network
- 60% faster disbursals: 15 days to 6 days

#### 1. Business Planning Manager to the MD & CEO

- **Objective:** Identify the projects that needed leadership attention for the next financial year and drive them to completion with clear ownership.
- **Approach:**
  - Collated proposed projects from all CXOs and their direct reports
  - Shortlisted projects against the primary issues faced on the floor
  - Hosted the Annual Strategy Meet (Jan 2025, Jan 2026), where each group presented its project plan
  - Ran the shortlisted portfolio as the CEO's project manager, with regular follow-ups
  - Facilitated cross-functional help whenever a team was blocked
  - Authored the FY26 Annual Operating Plan
- **Outcome:**
  - 2 annual strategy cycles run end to end
  - FY26 AOP set a roadmap to scale AUM by 250% through product and market expansion
  - Strategic projects included new products, Customer 360, credit enhancements and automated regulatory reporting
- **Skills:** Strategic planning, portfolio prioritisation, program management, CXO stakeholder management, executive communication

#### 2. Loan Against Property (LAP) launch

- **Objective:** Launch the LAP product within 4 weeks, without a LAP-specific journey in the LOS.
- **Approach:**
  - Adapted an existing LOS flow rather than building from scratch
  - Wrote BRDs and SOPs for Sales, Credit and Operations: data and document upload, underwriting, sanction and disbursal
  - Wrote LMS BRDs: post-disbursal servicing, top-ups, mandate-based repayment reconciliation, part payment, closure, GL and bank reconciliation
  - Covered gaps outside the flow (loan agreement, rate approval) with Google Sheets and Apps Script workflows
- **Outcome:**
  - LAP launched on time in September 2024
  - Every journey step covered from day one, with manual gaps contained in auditable workflows
- **Skills:** 0→1 launch, BRD and SOP writing, scope trade-offs under time pressure, Google Sheets, Docs and Apps Script automation

#### 3. LAP journey enhancements

- **Problem:** Post-launch, the mortgage journey had redundant steps, pages and fields; due diligence was largely manual, raising TATs and errors.
- **Approach:**
  - Audited the live journey and removed redundant steps, pages and fields
  - Integrated 8 APIs into the sales LOS journey for automated due diligence
  - Added upfront rejection of ineligible customers
  - Automated sanction letter and loan agreement generation from the LOS
- **Outcome:**
  - Sourcing-to-disbursal TAT cut 60%, from 15 days to 6 days
  - Fewer manual errors and less rework for credit and ops
- **Skills:** Funnel analysis, API integration, journey redesign, TAT optimisation

#### 4. Direct Assignment (DA) transactions

- **Objective:** Scale AUM faster than organic disbursals allowed by acquiring loan pools through DA.
- **Approach:**
  - Ran DA transactions end to end: sourcing, due diligence and negotiations with originators
  - Integrated deals into internal systems to track repayments and reconcile payouts
- **Outcome:**
  - 10 DA transactions closed by end of FY25
  - 50% of AUM at end of FY25; 20% at end of FY26
- **Skills:** Structured credit, deal negotiation, due diligence, Google Sheets and Apps Script automation

#### 5. DA payout reconciliation fix

- **Problem:** Finance flagged mismatches between DA payout files and bank reconciliation across transactions.
- **Approach:**
  - Traced the root cause: originator collection dates differed from JCL's receipt dates, creating interest mismatches missed in the original LMS build
  - Found that both originator and JCL share files were kept in the system, causing accounting errors and double work for ops
  - Moved to a single JCL-share file in the LMS
  - Built a Google Sheets calculator for ops to handle part payments and rate changes at the originator's end
  - Wrote a Python validator for the solutions team to check originator data completeness before customer-level upload
- **Outcome:**
  - Single source of truth for DA accounting
  - Duplicate file maintenance removed from operations
  - [add: mismatches or hours saved per month]
- **Skills:** Root-cause analysis, financial reconciliation, process redesign, Google Sheets and Apps Script automation

#### 6. DSA channel distribution network

- **Problem:** No structured channel to source mortgage customers at scale; onboarding needed Sales, Risk and Finance aligned.
- **Approach:**
  - Aligned Sales, Risk and Finance on one DSA onboarding process and SOP
  - Drafted the BRD for a partner portal: self-onboarding, payout reconciliation and real-time case status via LOS/LMS integration
  - Built an interim Apps Script flow: sales onboarding, agreement signing, RCU checkpoint, ERP finance onboarding for payout release
- **Outcome:**
  - 500+ retail and 30+ corporate DSAs onboarded across 20 locations
  - 92% of the ₹900 Cr monthly mortgage disbursals sourced via DSAs (~₹830 Cr)
  - Mix: 30% retail, 70% corporate DSAs
- **Skills:** Go-to-market, channel strategy, cross-functional alignment, partner portal design, workflow automation

#### 7. LRD Escrow Accounts

- **Problem:** Escrow accounts for LRD transactions took 60–90 days to open, delaying disbursals.
- **Approach:**
  - Designed a pooled escrow structure in place of per-deal accounts
  - Partnered with banks to operationalise it
- **Outcome:** Escrow account opening cut by ~66%, from 90 days to ~30 days
- **Skills:** Bank partnerships, solution design, process innovation

### Quant Analyst Intern — Futures First

May 2023 – Jul 2023 · Global derivatives trading

- **Objective:** Explain and anticipate shifts in the Eurodollar yield curve to support trading decisions.
- **Approach:**
  - Tracked yield curve shifts and mapped them to underlying market developments
  - Implemented 4 interest rate models (Vasicek, Cox-Ingersoll-Ross, Heath-Jarrow-Morton, Hull-White) to plot forward curves
  - Built vectorised backtesting in Pandas
- **Outcome:** Backtested model used to generate trading signals
- **Skills:** Stochastic modelling, fixed income, backtesting, Python and Pandas

### Data Scientist Intern — Ripik.AI

Apr 2022 – Jul 2022 · Industrial optimisation through AI/ML

**Piramal plant: furnace optimisation**

- **Objective:** Raise output efficiency and cut furnace energy use.
- **Approach:** Integrated a Distributed Random Forest (DRF) model into plant operations and analysed its results
- **Outcome:**
  - DPR efficiency up 3%
  - Specific fuel consumption down 116.64 Kcal/Kg
- **Skills:** Machine learning, industrial data analysis, model deployment

**Mahendra Brothers Exports: diamond pricing**

- **Objective:** Optimum price discovery based on diamond characteristics in the B2B market.
- **Approach:** Built and deployed a DRF price-prediction model
- **Outcome:** Model deployed to maximise B2B sales and profit
- **Skills:** Predictive modelling, pricing analytics, client delivery

## Projects

### Controller Placement in Software-Defined Networks

Aug 2023 – Apr 2024 · B.Tech project, guide: Prof. Amber Srivastava, IIT Delhi

- **Objective:** Find optimal controller placement in large software-defined networks, an NP-hard non-linear integer program, to cut network delay and message overhead.
- **Approach:**
  - Designed a multi-controller edge system
  - Applied the Maximum Entropy Principle to avoid suboptimal local solutions
  - Solved and benchmarked with MATLAB-based optimisation
- **Outcome:**
  - Solutions 2x faster than traditional methods
  - 40% lower design cost on larger networks
  - Lower network delay and message overhead
- **Skills:** Combinatorial optimisation, network design, MATLAB, algorithm benchmarking

### Impact of Inflation on Stock Market Performance

Jan 2023 – May 2023 · Guide: Prof. Neeru Chaudhary, IIT Delhi

- **Objective:** Quantify how far the inflation rate explains Nifty performance.
- **Approach:**
  - Analysed historical inflation and Nifty data for patterns
  - Built a multiple regression model to predict Nifty price from inflation
- **Outcome:**
  - 17.6% correlation; a 1% rise in inflation coincided with a 17.28% rise in Nifty
  - R² of 0.037 showed inflation alone explains little of index movement, pointing to multi-factor models
- **Skills:** Regression analysis, econometrics, hypothesis testing, Python

### Solving the Swift-Hohenberg Equation with Physics-Informed Neural Networks

Feb 2022 – Apr 2022 · Guide: Prof. Sitikanta Roy, IIT Delhi

- **Objective:** Solve the non-linear Swift-Hohenberg PDE with neural networks and validate against numerical methods.
- **Approach:**
  - Built a Physics-Informed Neural Network (PINN) for the equation
  - Generated discrete-time data points with the Finite Difference Method and cross-validated both
  - Retrained across hidden layers, neuron counts and batch sizes to compare performance
- **Outcome:** ~82% accuracy, validated against the finite difference solution
- **Skills:** Deep learning, numerical methods, PyTorch/TensorFlow, hyperparameter tuning

## Leadership & Positions of Responsibility

### Captain, IIT Delhi Basketball Team

- **Role:** Led the institute's basketball squad through selection, training and inter-college tournaments.
- **Key Contributions:**
  - Ran team trials, training plans and match preparation
  - Won 1st place at Urja 2024
  - Won 2nd place at the 55th Inter IIT Sports Meet 2023
- **Skills:** Team leadership, performance under pressure, discipline

### Sports Contingent Lead, Hostel

- **Role:** Led the hostel's multi-sport contingent in the IIT Delhi Inter Hostel Sports General Championship.
- **Key Contributions:**
  - Organised summer and winter training camps in semester breaks
  - Scheduled trials and team selections for each sport
  - Planned and booked travel for the contingent to tournaments at other colleges
  - Won the General Championship in 2023 and 2024
- **Skills:** Multi-team coordination, scheduling, logistics

### Finance and Operations, Technical Fest

- **Role:** Managed budget and coordination for IIT Delhi's 4-day technical fest.
- **Key Contributions:**
  - Built a budget-tracking platform for line-item spend
  - Coordinated a team of 200+ members across functions
  - Reduced overall festival budget through tighter accounting [add: % or ₹ saved]
- **Skills:** Budgeting, financial control, large-team management

## Impact Highlights

**Product ownership, 0→1 and 1→100**  
Launched LAP in 4 weeks, then cut its disbursal TAT from 15 to 6 days through 8 API integrations and journey redesign.

**Strategy with execution**  
Ran two CEO-level annual strategy cycles and authored a FY26 AOP targeting 250% AUM growth, then project-managed the portfolio to completion.

**Lending domain depth**  
Hands-on experience with LOS, LMS, the mortgage business, digital lending, Direct Assignment, and banking and DSA partnerships.

## What I bring to the table

How I work, and what teams can expect from me.

**Complete ownership**  
I treat every problem as mine end to end, from the first BRD to the last reconciliation entry, and follow it through until it is closed.

**Fast learning and quick adaptability**  
I have worked and delivered across four fields in four years: industrial ML, fixed-income derivatives, network optimisation research and fintech lending. At Jio Credit, I launched a new lending product within weeks of joining.

**Root-cause, data-driven thinking**  
I fix the system, not the symptom: I trace an issue to where it starts, back decisions with numbers, and build the fix myself with Google Sheets, Apps Script or Python when a system gap blocks the team.

**Bridge across functions**  
I translate between Sales, Credit, Risk, Finance, Ops and Tech, communicate with clarity at CXO level, and bring a captain's team-first discipline to every group I work with.

> "What has particularly stood out is the complete ownership Pranshu takes of every problem or project given to him." — Kusal Roy, MD & CEO, Jio Credit Limited

## Get in touch

Open to product and strategy roles in fintech and high-ownership teams. I reply within 48 hours.

- **Email:** pranshuc01@gmail.com
- **LinkedIn:** [add profile URL]
- **Location:** Pune, Maharashtra
- **Résumé:** [Download PDF]

CTA button text: **Let's talk** (opens email)

Phone number left off deliberately; public sites attract spam calls. Share it on request.
