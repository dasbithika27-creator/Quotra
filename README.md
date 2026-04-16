# Quotra — AI-Powered NL-to-Quote CPQ for Mid-Market B2B

> **Enterprise-grade CPQ. Startup pricing. 30-second quotes.**

Quotra is an AI-powered Configure-Price-Quote (CPQ) platform that generates accurate, compliant quotes in 30 seconds—not 2–4 hours. Built for mid-market B2B companies ($5M–$500M ARR) that can't afford enterprise CPQ ($1M+) but can't survive without it.

---

## The Problem

### Mid-Market B2B is Broken

- **Manual quoting is slow:** Most companies still use spreadsheets. 2–4 hours per quote. 10+ hours per week wasted.
- **Legacy CPQ is expensive:** Enterprise ($1M+). Mid-market ($150K–$300K/yr). Startups: locked out.
- **Configuration is complex:** Every vertical has unique rules. Incompatible. Hard-coded. Fragile.
- **No pricing intelligence:** Reps don't know if they're protecting margin, matching competitors, or triggering churn.
- **Onboarding takes forever:** 6–8 weeks typical. 40% of rollouts never finish.
- **Integration hell:** Your CRM is Pipedrive. Your ERP is NetSuite. Your inventory is custom. Nothing talks to anything.

### Who Hurts Most (In Order)

| **Tier 1 — Best Fit** | **Tier 2 — Strong** | **Tier 3 — Emerging** |
|---|---|---|
| Industrial Equipment & Machinery | Solar & Renewable Installers | Medical Device & Life Sciences |
| MSPs / IT Resellers / VARs | Wholesale Distribution & Print | Specialty Chemicals |
| Specialty Contractors (HVAC, Electrical) | | |

---

## The Solution: Quotra

**Tell Quotra what you sell. It handles the rest.**

### Core Value Proposition

```
Upload catalog → Define rules in English → AI generates quotes in 30 seconds
```

### Three Core Pillars

1. **⌨️ Type, Don't Click**
   - No forms. No dropdown hell.
   - Reps describe what they're selling in plain English.
   - Quotra configures the product automatically.

2. **🎯 Catalog-Grounded AI**
   - Every quote is based on your actual products, pricing, and rules.
   - Not generic templates. Not hallucinating.
   - Contextual. Accurate. Compliant.

3. **💰 Enterprise AI at Startup Price**
   - Frontier LLM (Claude) + telco-grade configuration engine.
   - **Starter:** $299/month
   - **Growth:** $599/month
   - **Scale:** $1,200/month
   - Not $150K–$300K. Fair pricing for growing teams.

---

## What Quotra Solves

### 1. Natural Language Configuration
- Upload your product catalog (CSV, PDF, Excel).
- Describe your rules in plain English: *"2% discount if order > $50K, but not for new customers."*
- Quotra learns your business logic using Claude API.
- No coding. No rules engine. No consultants.

### 2. AI-Powered Quote Generation
- Rep: *"I need a quote for 50 Enterprise licenses, 3-year term, Q2 deal, they're in Finance."*
- Quotra:
  - ✅ Configures the product
  - ✅ Applies volume/loyalty/promo rules
  - ✅ Calculates pricing
  - ✅ Checks margin thresholds
  - ✅ Generates branded PDF
  - **Time: 30 seconds**

### 3. Margin Protection Built-In
- AI watches every discount request.
- Flags margin leakage in real-time.
- Checks customer's renewal history → suggests retention pricing.
- Prevents revenue loss silently.

### 4. API-First, CRM-Agnostic
- Integrates with Salesforce, HubSpot, Pipedrive, NetSuite, Zapier.
- Sync quotes back to your CRM.
- Pull inventory in real-time.
- Trigger fulfillment workflows.

### 5. Zero-Touch Onboarding
- Import catalog: 5 minutes.
- Define rules: 1 hour (usually less).
- First quote: 30 seconds.
- No waiting for implementation teams.

---

## Product Features

### Shipped (MVP)
- ✅ Catalog management (products, variants, pricing)
- ✅ Natural language rule definition
- ✅ AI quote generation (Claude API)
- ✅ PDF export (branded, compliant)
- ✅ Basic CRM sync (Salesforce, HubSpot)
- ✅ Multi-tenant architecture (RLS)
- ✅ Mobile-responsive dashboard

### 90-Day Roadmap (Moonshots)

#### Priority 1: Spec-Sheet-to-Catalog Auto-Import (Q2 2026)
Drop a PDF supplier price list → AI extracts SKUs, options, pricing rules, compatibility notes → catalog auto-populated in minutes instead of weeks.
**Impact:** Removes biggest onboarding bottleneck.

#### Priority 2: RFQ Inbox Listener (Q2 2026)
Forward any RFQ to `rfq@yourcompany.quotra.app` → Quotra parses it, maps line items to your catalog, drafts the quote, replies with a signed PDF link.
**Impact:** 30-minute RFQ cycle → 2 minutes.

#### Priority 3: Slack/Teams Quote-in-Chat (Q3 2026)
```
@quotra quote 50 Enterprise seats for Acme, Q2 promo
→ [signed PDF link in Slack]
```
**Impact:** Viral adoption. Reps never leave their chat client.

#### Priority 4: Voice-to-Quote for Field Sales (Q3 2026)
Record a 30-sec voicenote on a jobsite → transcribed → configured → quote in customer's inbox before you drive away.
**Impact:** Killer feature for contractors, solar installers, field reps.

#### Priority 5: Margin-Protecting AI Negotiator (Q4 2026)
Buyer asks for discount. AI:
- Checks current margin
- Pulls customer's purchase history
- Analyzes competitor pricing
- Suggests counter-offer that protects profit
**Impact:** Reps stop leaving money on the table.

#### Priority 6: Renewal Churn Radar (Post-Series A)
Every signed quote becomes a tracked contract. AI watches usage signals and auto-drafts renewal quotes 90 days out with retention pricing when churn risk is elevated.
**Impact:** Predictable, protected revenue.

---

## Competitive Analysis

### vs. Enterprise (Ericsson, Amdocs, Huawei)
| Metric | Enterprise | Quotra |
|--------|-----------|--------|
| Setup Time | 6–12 months | 1 day |
| Price | $1M+ | $299/month |
| Time-to-Quote | 5–10 min + approval | 30 sec |
| Target | Telecoms, massive orgs | Mid-market B2B |

### vs. Mid-Market (Salesforce CPQ, Configit)
| Metric | Salesforce CPQ | Quotra |
|--------|---|---|
| Setup Time | 6–8 weeks | 1 day |
| Price | $150K–$300K/yr | $299–$1.2K/month |
| Time-to-Quote | 2–5 min | 30 sec |
| AI | Add-on | Native |
| CRM Agnostic | ❌ Salesforce-locked | ✅ Any CRM |
| Margin Intelligence | Basic | Built-in + AI negotiator |

### vs. Direct Competitors (Mobileforce AskCPQ, PandaDoc)
| Metric | Mobileforce AskCPQ | PandaDoc CPQ | Quotra |
|--------|---|---|---|
| Time-to-Quote | ~2 min | 2–5 min | 30 sec |
| LLM Used | Rule-based NLP | Rule-based | Frontier LLM (Claude) |
| Catalog Grounding | Limited | Basic | Deep (all rules read context) |
| Price | Not public | $65+/user | $299/org/month |
| Industries | General | General | Vertical-specific templates |

**Quotra's USP:** Frontier LLM + telco-grade configuration engine + $299 price point = first affordable, AI-native CPQ for mid-market.

---

## Business Model

### Pricing (Monthly)

| **Starter** | **Growth** | **Scale** |
|---|---|---|
| $299 | $599 | $1,200 |
| Up to 5 users | Up to 20 users | 20+ users |
| 1 catalog | 5 catalogs | Unlimited |
| Basic CRM sync | Advanced CRM sync | Custom integrations |
| Email support | Priority support | Dedicated success |

### Go-to-Market Strategy

1. **Target verticals:** Industrial Equipment, MSPs, Specialty Contractors
2. **Sales motion:** Self-serve PLG (free trial) + sales-assisted (land expansion)
3. **Distribution:** Direct sales, partner channels (System Integrators), Slack/Teams app marketplace
4. **Unit economics:** 
   - CAC: $2K (organic + SEM)
   - ARPU: $600/mo (growth tier average)
   - LTV: $10.8K (18-month payback)

---

## Industries We Serve

### Tier 1 — Maximum Pain + Willingness to Pay

**Industrial Equipment & Machinery Manufacturing**
- Material handling, compressors, mixers, centrifuges, storage tanks, forklifts
- Pain: Multi-factor pricing (materials + labor + logistics + FX volatility). 30+ min RFQs. High deal value ($50K–$2M).
- Market: $500B+ global equipment market

**MSPs / IT Resellers / VARs**
- Managed services providers, value-added resellers, software resellers
- Pain: Quote complexity (device ratios, license tiers, compliance add-ons). 88% of SMBs now use MSPs.
- Market: $90B+ SMB opportunity through 2026

**Specialty Contractors (HVAC, Electrical, Mechanical)**
- Commercial HVAC, electrical systems, plumbing contractors
- Pain: Fragmented tooling (Dynamics, Sage), field quotes on spreadsheets, system compatibility checks
- Market: $100B+ construction services

### Tier 2 — Strong Pain + Growing Adoption

**Solar & Renewable Installers**
- Residential/commercial solar, heat pump installers
- Pain: 30–45 min per quote, 5–8 hrs/week busywork. Vendor consolidation (Solargraf dominant, others shut down 2023–2025).
- Market: $50B+ renewable energy services (CAGR 15%)

**Wholesale Distribution & Web-to-Print**
- Industrial/MRO distributors, print-on-demand, packaging wholesalers
- Pain: 30-min RFQs, manual takeoffs, complex multi-SKU configurations
- Market: AI in distribution CAGR 20% through 2028. 62% of print shops piloting AI.

### Tier 3 — Highest Value, Longer Sales Cycle

**Medical Device & Life Sciences**
- Capital equipment manufacturers, diagnostic suppliers
- Pain: 8,000+ configurable components, FDA 21 CFR Part 820, ISO 13485:2016, multi-channel distribution
- Market: $500B+ medical device market (slower to adopt, but sticky)

**Specialty Chemicals & Food Ingredients**
- Custom chemical suppliers, food ingredient distributors
- Pain: Supply chain complexity, raw material qualification, spec-per-application, regulatory compliance
- Market: $300B+ specialty chemicals market

---

## Tech Stack

- **Frontend:** Next.js 16 (App Router), Tailwind CSS, shadcn/ui, Lucide icons
- **Backend:** Next.js API Routes, PostgreSQL (Supabase)
- **AI:** Claude API (claude-sonnet-4-20250514, frontier LLM)
- **Auth:** Supabase Auth + Row-Level Security (RLS)
- **Integrations:** Salesforce, HubSpot, Pipedrive, NetSuite, Slack, Teams
- **Deployment:** Vercel (frontend), Supabase (backend)

---

## How It Works (From a User's POV)

### 1. Onboarding (1 hour)
- Sign up → create org
- Upload product catalog (CSV or drag-drop)
- Define 3–5 pricing rules in plain English
- Connect CRM (Salesforce, HubSpot, etc.)

### 2. Generate a Quote (30 seconds)
- Rep in Salesforce/Slack/web app: *"Quote for 10 Enterprise licenses, volume discount, 2-year term, customer in Finance"*
- Quotra:
  - Configures product
  - Applies rules (volume discount → 10% off)
  - Calculates pricing
  - Checks margin (passes)
  - Generates branded PDF
  - Syncs back to CRM

### 3. Buyer Accepts, Revenue Flows
- PDF sent to buyer
- Buyer signs (e-signature optional)
- Quote synced to CRM → fulfillment triggered

---

## Why Teams Choose Quotra

✅ **Fastest quote generator in mid-market** (30 seconds)  
✅ **Most affordable** ($299/month vs. $150K–$300K)  
✅ **Easiest to set up** (1 day vs. 6–8 weeks)  
✅ **CRM-agnostic** (works with Salesforce, HubSpot, Pipedrive, custom)  
✅ **AI-native, not a bolted-on feature** (frontier LLM doing the work)  
✅ **Margin-protecting** (churn radar, negotiator, dynamic pricing)  

---

## Roadmap

### Q2 2026 (Now)
- MVP foundation
- Core features: catalog, rules, quote generation, PDF export, basic CRM sync
- Target: 50 early adopter customers (Industrial Equip + MSPs)

### Q3 2026
- **Spec-Sheet-to-Catalog auto-import** (removes onboarding friction)
- **RFQ Inbox Listener** (viral, removes manual work)
- **Slack/Teams quote-in-chat** (distribution layer)

### Q4 2026 – Series A Positioning
- **Voice-to-Quote** (field sales killer feature)
- **Margin Negotiator** (AI-driven pricing protection)
- **Advanced analytics** (quotes generated, margins protected, deals closed)
- Vertical-specific templates (Solar, Medical Device, HVAC)

### 2027+
- **Renewal Churn Radar** (proactive revenue protection)
- Multi-language/multi-currency support
- Advanced inventory integration (real-time stock checks)
- Industry compliance packs (FDA for medical device, etc.)

---

## Investment Thesis

**Market:** $15B+ CPQ market. 80% is enterprise. 20% ($3B) is mid-market, fragmented, underserved.

**Problem:** Mid-market B2B can't afford enterprise CPQ, but legacy spreadsheet quoting kills sales velocity.

**Solution:** Quotra = frontier LLM + configuration engine + $299/month price point.

**Defensibility:** 
- Moat 1: Catalog grounding (hard for competitors to replicate without deep product understanding)
- Moat 2: Integration ecosystem (CRM agnostic → network effects as reps adopt Slack/Teams bots)
- Moat 3: Pricing (can't be undercut; enterprise CPQ is $1M, mid-market is $150K, we're $299)

**Unit Economics (Year 1)**
- CAC: $2K (organic + SEM)
- ARPU: $600/mo
- Payback: 18 months
- LTV: $10.8K

**Founders:** Bithika Das

---

## Get Started

- **Website:** quotra.app (coming soon)
- **GitHub:** github.com/quotra/quotra
- **Email:** dasbithika27@gmail.com
- **Free Trial:** 14 days, no credit card required

---

**Quotra: The fastest way to quote. The fairest way to price. The smartest way to sell.**
