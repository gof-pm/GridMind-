# Data Flywheel Map

> Score each loop 1-5. Your weakest loop is where competitors attack first.
> The four loops below are the M2 starting point - adapt if your product has 2 or 6 loops instead of 4.

## Flywheel Loops

| Loop | What It Measures | Score 1 | Score 5 | Score |
|------|------------------|---------|---------|-------|
| **Correction** | Do users fix AI outputs? Is that signal captured and reused? | No capture | Automated retraining | __/5 |
| **Preference** | Does the product learn individual / team preferences over time? | Stateless | Deep personalization | __/5 |
| **Domain Context** | Does usage in one area improve quality in adjacent areas? | Siloed | Cross-domain transfer | __/5 |
| **Network** | Does each new user / team make the product better for everyone? | Isolated | Strong network effects | __/5 |

### Correction Loop - 3/5
**What you capture today:**
**How it compounds:**

### Preference Loop - 4/5
**What you capture today:**
**How it compounds:**

### Domain Context Loop - 4/5
**What you capture today:**
**How it compounds:**

### Network Loop - 4/5
**What you capture today:**
**How it compounds:**

**Total Flywheel Score: 15/20**
**Weakest Loop:**
**Fix for weakest loop:**

---

## Encroachment Threat Assessment

### 1. Platform Encroachment

**Attacker:** Microsoft  
**Vector:** Launch "Copilot for Grid Operators" targeting utilities directly via
existing Azure contracts — cutting GridMind's access to the outcome data
it needs to compound  
**Time-to-threat:** 30–90 days to ship a functional agent  
**% of value at risk:** 80% if attack happens early; drops to 20–30% after
18+ months of proprietary data accumulation  

### 2. Vertical Competitor

**Attacker:** Regional specialist startup (e.g. solar-only, California/CAISO)  
**Vector:** Deeper regional dataset, lower price point, surgical focus vs
GridMind's generalist approach  
**Time-to-threat:** 12–18 months to gain meaningful regional traction  
**% of value at risk:** 25–35% — loss of California market, the largest
solar market in the US  
**Defense:** Acquire if their regional moat is real (Google/Waze playbook);
or subdivide GridMind internally into regional verticals with authority
marketing — "most experience in your market"

### 3. Adjacent Expansion

**Attacker:** Wood Mackenzie or S&P Global Commodity Insights  
**Vector:** Add permitting intelligence as a new module inside a platform
developers already pay for and trust — no need to build the customer
relationship from scratch  
**Time-to-threat:** 6–12 months if they prioritise it  
**% of value at risk:** 40–50% — distribution advantage is significant  
**Defense:** Walled garden — restrict API access so permitting intelligence
is only accessible via GridMind directly. Then approach Wood Mackenzie
as a business partner, not a competitor — position GridMind as the
permitting intelligence layer they license, not a tool they absorb

---

## 90-Day Encroachment Plan

**Attacker:** Microsoft  
**Attack vector:** Copilot for Grid Operators — targets utilities directly,
cutting GridMind's access to outcome data and undermining developer
trust through Microsoft's existing enterprise relationships

**Weeks 1–4 — what they ship:**
Microsoft announces a Copilot for Grid Operators pilot with 3–5 major
utilities. Basic permitting checklist and document generation via
Azure OpenAI. No proprietary data yet — but the brand is enough to
create doubt among GridMind's early prospects.

**Weeks 5–8 — how they poach users:**
Microsoft bundles the tool into existing Azure enterprise agreements
at no additional cost. Developers already using Azure find it in
their dashboard. Marketing positions it as "enterprise-grade" vs
GridMind's startup credibility. Price pressure becomes existential.

**Weeks 9–12 — why users don't come back:**
Utilities start routing GridMind data requests through Microsoft's
infrastructure. GridMind loses access to outcome signals. The data
flywheel slows. Microsoft's distribution advantage compounds.

**GridMind's defense:**

1. **Freemium moat** — launch a free tier with project limits before
Microsoft ships. Developers already using GridMind for free are
harder to displace than prospects who haven't started yet.
Free with no limits for projects under non-profit or community
energy programmes — builds brand loyalty and press coverage
that Microsoft cannot replicate.

2. **Specialisation** — subdivide GridMind into regional and
technology verticals. A developer in Texas doing battery storage
gets a product that feels built for them specifically.
Microsoft builds horizontal — GridMind wins vertical.

3. **Reliability agent** — deploy an agent that proactively flags
inconsistencies in project submissions and proposes corrections,
but always routes final validation through a human specialist.
This builds a trust contract that an enterprise Copilot cannot
replicate at speed — reliability becomes the brand.

4. **Data lockdown** — restrict API access immediately. GridMind's
permitting outcome data is not licensable. It is the product.
