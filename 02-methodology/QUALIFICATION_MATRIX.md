# ✅ BANT++ Qualification Matrix

**PROPRIETARY & CONFIDENTIAL**

---

## Overview

**Qualify hard. Close easy.**

The BANT++ framework helps you determine if an opportunity is worth pursuing. It's BANT (Budget, Authority, Need, Timeline) enhanced with Competition and Champion analysis.

**Rule of Thumb:**
- Score 80%+ = Qualified (pursue aggressively)
- Score 50-80% = Conditional (pursue with caution)
- Score <50% = Disqualified (politely exit)

---

## The BANT++ Framework

### 1. Budget (B)

**Question:** Does the prospect have money to spend?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **25** | ✅ Budget allocated and approved | "We have $500K budgeted for infrastructure improvements" |
| **20** | ✅ Budget not allocated, but can be justified | "We'd need to build a business case, but we can reallocate from cloud spend" |
| **15** | ⚠️ Budget exists, but competitive | "We have budget, but we're looking at multiple solutions" |
| **10** | ⚠️ No budget, but willing to find it | "We don't have budget, but if ROI is strong, we can make it happen" |
| **0** | ❌ No budget and no path to get it | "We have zero budget for this" |

#### Discovery Questions

```
"What's your current annual infrastructure spend? (Cloud bills + DevOps headcount)"

"Do you have budget allocated for infrastructure improvements?"

"If not, how do budget approvals work at your company?"

"What's the approval threshold? (e.g., <$100K = VP approval, >$100K = CFO approval)"

"Have you purchased similar solutions before? What was the budget range?"
```

#### Red Flags
- 🚩 "We have no budget" + no willingness to create budget
- 🚩 "We're just doing research" with no near-term timeline
- 🚩 Price is the ONLY consideration (not value)

---

### 2. Authority (A)

**Question:** Can the prospect make or influence the buying decision?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **25** | ✅ Economic buyer engaged (CFO, CEO, VP) | Direct access to decision-maker who can sign |
| **20** | ✅ Technical buyer + economic buyer in process | CTO/VP Eng + CFO both engaged |
| **15** | ⚠️ Champion + path to decision-maker | Strong internal advocate who can sell for us |
| **10** | ⚠️ Influencer but not decision-maker | Individual contributor or manager (not VP+) |
| **0** | ❌ No access to decision-maker | Stuck at low level, no executive sponsorship |

#### Decision-Maker Hierarchy

**Economic Buyer** (Signs the contract):
- CFO, CEO, COO
- VP Finance
- Head of Procurement (for large companies)

**Technical Buyer** (Validates the solution):
- CTO, VP Engineering
- Head of Infrastructure/DevOps
- Solutions Architect

**User Buyer** (Uses the product):
- DevOps engineers
- SREs, Platform engineers
- Development teams

**Champion** (Internal advocate):
- Anyone who actively sells for you internally

#### Discovery Questions

```
"Who else will be involved in this decision?"

"Who has the final say on spending $X?"

"Walk me through your typical buying process for infrastructure tools."

"Who signs the contract?"

"Who needs to say 'yes' for this to happen?"

"If you could only get one person to approve, who would it be?"
```

#### Red Flags
- 🚩 "I'll present this to my boss" (and you never meet the boss)
- 🚩 Can't identify the economic buyer
- 🚩 Decision-maker is avoiding meetings

---

### 3. Need (N)

**Question:** Do they have a real, urgent pain that we solve?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **25** | ✅ Critical pain, quantifiable impact | "Downtime costs us $50K/month. We need this solved ASAP." |
| **20** | ✅ Significant pain, clear business impact | "Slow deployments are delaying product launches" |
| **15** | ⚠️ Pain exists, but not urgent | "We have issues, but they're manageable for now" |
| **10** | ⚠️ Nice-to-have improvement | "This would be nice, but not essential" |
| **0** | ❌ No pain or unclear problem | "Just exploring options" |

#### Pain Indicators (High Need)

- **Compliance deadline:** "We need SOC 2 by Q2 to close enterprise deals"
- **Rapid growth:** "We're scaling 10x and infrastructure can't keep up"
- **Outages/incidents:** "We had 3 production outages last month"
- **High costs:** "Our AWS bill is $100K/month and growing"
- **Team burnout:** "DevOps team is working 60-hour weeks"
- **Competitive pressure:** "Competitors ship 3x faster than us"

#### Discovery Questions

```
"What's the business impact of [problem]?"

"How much is this costing you? (Time, money, opportunity cost)"

"What happens if you don't solve this in the next 6 months?"

"On a scale of 1-10, how urgent is this? What's driving that urgency?"

"What triggered you to start looking for a solution now?"

"What's the cost of the status quo?"
```

#### Red Flags
- 🚩 "No major pain, just exploring"
- 🚩 Can't quantify impact
- 🚩 "We'll solve it eventually, no rush"

---

### 4. Timeline (T)

**Question:** When do they need this solved?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **25** | ✅ Urgent: <3 months | "We need to be live by end of Q1" |
| **20** | ✅ Near-term: 3-6 months | "Planning to implement in Q2" |
| **15** | ⚠️ Mid-term: 6-12 months | "Evaluating for next fiscal year" |
| **10** | ⚠️ Long-term: 12+ months | "This is for 2027 planning" |
| **0** | ❌ No timeline | "Just researching for someday" |

#### Timeline Drivers

**External Deadlines (Best):**
- Compliance certification deadline
- Product launch date
- Funding round dependency
- Contract renewal (existing vendor)
- Regulatory requirement

**Internal Deadlines (Good):**
- Budget cycles (fiscal year, quarter)
- Roadmap commitments
- Executive mandate

**No Deadline (Bad):**
- "Whenever we get around to it"

#### Discovery Questions

```
"When do you need this solved by?"

"What's driving that timeline?"

"What happens if you miss that deadline?"

"Is this tied to a product launch, funding round, or compliance requirement?"

"When does your budget year end?"

"Are there any external deadlines (customer commitments, regulatory, etc.)?"
```

#### Red Flags
- 🚩 "No timeline, just exploring"
- 🚩 Timeline keeps slipping ("We'll decide next quarter" → "We'll decide next quarter" ad infinitum)
- 🚩 "We'll implement when we have time"

---

### 5. Competition (C)

**Question:** What alternatives are they considering?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **15** | ✅ Competitive but favorable | Evaluating us + 1-2 others, we're leading |
| **12** | ✅ Early in evaluation | Just starting to look, no strong preference |
| **9** | ⚠️ Competitive and close | Us + competitors, neck-and-neck |
| **6** | ⚠️ Incumbent advantage (not us) | Existing vendor has inside track |
| **0** | ❌ Already decided on competitor | "We're going with [Competitor], just checking boxes" |

#### Competitive Scenarios

| Scenario | Strategy |
|----------|----------|
| **No competition** | "Just you" → Great, but verify (might be lying or uninformed) |
| **Us + AWS/DIY** | Position on simplicity + TCO |
| **Us + Heroku/PaaS** | Position on scalability + cost at scale |
| **Us + OpenShift/Tanzu** | Position on speed + simplicity + cost |
| **Incumbent (AWS/Azure)** | Position as cloud abstraction layer (complement, not replace) |
| **Budget competitor (DIY)** | Quantify opportunity cost + risk |

#### Discovery Questions

```
"What alternatives are you evaluating?"

"How did you narrow down to this shortlist?"

"What do you like and dislike about each option?"

"Which vendor are you leaning toward right now?"

"What would it take for us to win this deal?"

"Have you used [Competitor] before? What was your experience?"
```

#### Red Flags
- 🚩 "We're going with [Competitor], just getting another quote"
- 🚩 Existing vendor with multi-year contract (hard to displace)
- 🚩 Strong executive relationship with competitor

---

### 6. Champion (C)

**Question:** Do we have an internal advocate?

#### Scoring Criteria

| Score | Criteria | Evidence |
|-------|----------|----------|
| **10** | ✅ Strong champion at VP+ level | VP Eng is actively selling for us internally |
| **8** | ✅ Champion with influence | Senior engineer/architect who influences decision |
| **6** | ⚠️ Weak champion | Interested individual, but limited influence |
| **3** | ⚠️ No champion, just contact | Point of contact, but not advocating |
| **0** | ❌ Hostile champion | Internal blocker or competitor advocate |

#### Champion Qualities

**Good Champion:**
- Has authority or strong influence
- Understands our value prop
- Actively sells us internally (without us being there)
- Gives us inside information (process, politics, objections)
- Introduces us to other stakeholders

**Weak Champion:**
- Low-level individual contributor
- Passive (interested but not advocating)
- Can't navigate internal politics

#### Discovery Questions

```
"Who internally is pushing for this solution?"

"Who's the strongest advocate for solving this problem?"

"If you could only get one person to say 'yes,' who would it be?"

"Can you help us understand the internal dynamics? Who's supportive? Who's skeptical?"

"Would you be comfortable introducing us to [decision-maker]?"
```

#### Building a Champion

**How to Turn a Contact into a Champion:**

1. **Make them successful:**
   - Provide data, ROI models, competitive analysis
   - Arm them to sell internally

2. **Understand their motivations:**
   - Career advancement? (Show how this makes them a hero)
   - Pain relief? (Show how this solves their problem)
   - Innovation? (Show how this differentiates their company)

3. **Give them credit:**
   - "This was [Champion's] idea"
   - Make them the hero, not you

---

## BANT++ Scorecard

### Scoring Summary

| Criteria | Max Score | Your Score |
|----------|-----------|------------|
| **Budget** | 25 | ___ |
| **Authority** | 25 | ___ |
| **Need** | 25 | ___ |
| **Timeline** | 25 | ___ |
| **Competition** | 15 | ___ |
| **Champion** | 10 | ___ |
| **TOTAL** | **125** | **___** |

---

### Qualification Thresholds

| Score | Status | Action |
|-------|--------|--------|
| **100-125** (80%+) | ✅ **Highly Qualified** | Pursue aggressively, prioritize |
| **80-100** (64-80%) | ✅ **Qualified** | Pursue, but watch for risks |
| **63-80** (50-64%) | ⚠️ **Conditionally Qualified** | Pursue cautiously, derisk gaps |
| **<63** (<50%) | ❌ **Disqualified** | Politely exit or stay in touch for later |

---

### Example: Qualified Opportunity

**Company:** TechCo (500 employees, SaaS company)

| Criteria | Score | Rationale |
|----------|-------|-----------|
| **Budget** | 20 | No formal budget, but CTO says "We can reallocate from AWS spend" |
| **Authority** | 25 | CTO engaged + CFO introduction scheduled |
| **Need** | 25 | Critical: 3 outages last month, CEO demanding fix |
| **Timeline** | 25 | Must be live by end of Q1 (compliance requirement) |
| **Competition** | 12 | Evaluating us + AWS (DIY), no strong preference yet |
| **Champion** | 8 | VP Engineering is strong advocate, sells us internally |
| **TOTAL** | **115 / 125** | **92% - Highly Qualified** ✅ |

**Verdict:** Pursue aggressively. High urgency, strong need, exec engagement.

---

### Example: Disqualified Opportunity

**Company:** StartupCo (20 employees, pre-revenue)

| Criteria | Score | Rationale |
|----------|-------|-----------|
| **Budget** | 0 | "We have $0 budget, can you do free trial for 6 months?" |
| **Authority** | 10 | Junior engineer, no access to founder/CEO |
| **Need** | 10 | "It would be nice to have, but not critical" |
| **Timeline** | 0 | "Someday, when we raise our Series A" |
| **Competition** | 6 | Using Heroku, happy enough |
| **Champion** | 3 | Weak champion (no influence) |
| **TOTAL** | **29 / 125** | **23% - Disqualified** ❌ |

**Verdict:** Politely disengage. No budget, no urgency, no authority.

**Disqualification Email:**
> "Based on our conversation, it sounds like BlackRoad OS might be over-engineered for your current needs. I'd recommend sticking with Heroku for now. If things change when you raise your Series A, happy to reconnect. Best of luck!"

---

## When to Disqualify

### Hard Disqualifiers (Walk Away Immediately)

1. **No budget + no willingness to find it**
   - "We have $0 and no plan to get budget"

2. **No decision-maker access**
   - "I can't introduce you to my boss"

3. **No pain**
   - "We're happy with current solution, just exploring"

4. **No timeline**
   - "Someday, maybe"

5. **Already decided on competitor**
   - "We're going with [Competitor], just checking boxes"

6. **Bad-fit use case**
   - They need features we don't have and won't build

---

## Derisking Conditional Opportunities

**If score is 50-80%, try to derisk:**

### Low Budget Score?
- Build ROI model to justify budget
- Offer phased approach (start small, expand)
- Identify budget reallocation opportunities

### Low Authority Score?
- Request introduction to decision-maker
- Multi-thread to economic buyer
- Use champion to navigate politics

### Low Need Score?
- Quantify cost of inaction
- Create urgency via competitive pressure or external deadline
- Walk away if pain isn't real

### Low Timeline Score?
- Create urgency (price increase, limited availability)
- Tie to external deadline (compliance, product launch)
- Stay in touch, revisit when timing improves

### Low Competition Score?
- Differentiate aggressively
- Offer unique value (pilot, custom POC)
- Address specific concerns vs. competitor

### Low Champion Score?
- Invest in building champion relationship
- Arm them with materials to sell internally
- Find alternative champion (multi-threading)

---

## Qualification Cadence

### When to Qualify

**Initial Qualification:** First call (20-30 minutes)
- Quick BANT++ assessment
- Decide: Pursue or politely exit?

**Deep Qualification:** Discovery call (60+ minutes)
- Comprehensive BANT++ scoring
- Technical and business alignment

**Re-Qualification:** Throughout the sales cycle
- Things change (budget cuts, timeline shifts, new competitors)
- Re-score monthly or after major events

---

## CRM Integration

**Track BANT++ scores in your CRM:**

**HubSpot Custom Fields:**
- BANT++ Total Score (0-125)
- Budget Score (0-25)
- Authority Score (0-25)
- Need Score (0-25)
- Timeline Score (0-25)
- Competition Score (0-15)
- Champion Score (0-10)
- Qualification Status (Qualified / Conditional / Disqualified)

**Use scores to:**
- Prioritize deals (focus on high scores)
- Forecast accuracy (high scores = higher close probability)
- Coaching (identify patterns in wins/losses)

---

## FAQs

**Q: What if they score high but we still lose?**
A: BANT++ predicts fit, not guarantees. You can have a qualified opportunity and still lose on execution, price, or competitive positioning.

**Q: What if they score low but we want to pursue anyway?**
A: Sometimes strategic deals justify lower scores (e.g., anchor customer in new market). But acknowledge the risk and manage expectations.

**Q: How often should I re-score?**
A: Monthly, or after major events (budget cuts, new decision-maker, competitor entry).

**Q: Can I skip BANT++ for inbound leads?**
A: No. Inbound ≠ qualified. Always qualify.

---

**Version:** 1.0.0
**Last Updated:** January 4, 2026
**Owner:** Joaquin, Sales Master

*Qualify hard. Close easy. Never waste time on bad-fit deals.*
