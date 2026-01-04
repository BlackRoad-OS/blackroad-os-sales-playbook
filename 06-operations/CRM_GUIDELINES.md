# 🗂️ CRM Guidelines & Data Hygiene

**PROPRIETARY & CONFIDENTIAL**

---

## Overview

**Your CRM is your single source of truth.**

Clean data = accurate forecasting = better sales outcomes.

This document defines CRM usage standards, data hygiene rules, and best practices for HubSpot (our CRM of choice).

**Golden Rule:** If it's not in the CRM, it didn't happen.

---

## CRM Philosophy

### 1. **Data Integrity is Non-Negotiable**

Bad data leads to:
- ❌ Inaccurate forecasting
- ❌ Lost deals (missed follow-ups)
- ❌ Poor pipeline visibility
- ❌ Wasted time (duplicate work)

Good data enables:
- ✅ Predictable revenue
- ✅ Efficient territory management
- ✅ Accurate compensation
- ✅ Data-driven coaching

---

### 2. **Real-Time Updates**

**Update CRM in real-time, not end-of-week.**

| Activity | When to Log |
|----------|-------------|
| **Call/Meeting** | Immediately after (within 15 minutes) |
| **Email Sent** | Automatically (via email integration) |
| **Demo Delivered** | Same day |
| **Stage Change** | Immediately when it happens |
| **Deal Closed** | Within 1 hour |

---

### 3. **Complete, Not Perfect**

Better to have **complete data** than perfect data.

**Don't overthink:**
- Log the call, even if notes are brief
- Update stage, even if uncertain (you can adjust later)
- Add contact, even if you don't have full info

**Aim for 80% completeness within 24 hours.**

---

## HubSpot Setup

### Required Fields (Must Be Filled)

#### **Contact Fields**

| Field | Required | Example |
|-------|----------|---------|
| **First Name** | ✅ | "Sarah" |
| **Last Name** | ✅ | "Chen" |
| **Email** | ✅ | "sarah.chen@techco.com" |
| **Job Title** | ✅ | "VP Engineering" |
| **Company** | ✅ | "TechCo" |
| **Phone** | ⚠️ If available | "+1-555-123-4567" |
| **LinkedIn URL** | ⚠️ If available | "linkedin.com/in/sarahchen" |

#### **Company Fields**

| Field | Required | Example |
|-------|----------|---------|
| **Company Name** | ✅ | "TechCo" |
| **Domain** | ✅ | "techco.com" |
| **Industry** | ✅ | "SaaS" |
| **Number of Employees** | ✅ | "500" |
| **Annual Revenue** | ⚠️ Estimate if needed | "$100M" |
| **Funding Stage** | ⚠️ If known | "Series C" |
| **Tech Stack** | ⚠️ If known | "Kubernetes, AWS, React" |

#### **Deal Fields**

| Field | Required | Example |
|-------|----------|---------|
| **Deal Name** | ✅ | "TechCo - Enterprise" |
| **Amount** | ✅ | "$180,000" (annual contract value) |
| **Close Date** | ✅ | "2026-03-31" |
| **Deal Stage** | ✅ | "Proposal Sent" |
| **Pipeline** | ✅ | "Sales Pipeline" |
| **Deal Owner** | ✅ | Auto-assigned to you |
| **ICP Score** | ✅ | "85" (see ICP framework) |
| **BANT++ Score** | ✅ | "100" (see qualification matrix) |
| **Product Tier** | ✅ | "Enterprise" |
| **Competitor** | ⚠️ If known | "AWS DIY" |
| **Pain Points** | ✅ | "Slow deployments, high costs" |

---

## Deal Stages & Criteria

### Stage Definitions

| Stage | Definition | Entry Criteria | Exit Criteria | Avg Duration | Win Probability |
|-------|------------|----------------|---------------|--------------|-----------------|
| **1. Prospect** | Identified potential customer | Name + company + contact info | First conversation scheduled | 1-7 days | 5% |
| **2. Qualified** | BANT++ passed | BANT++ score >63 | Discovery call completed | 1-3 days | 10% |
| **3. Discovery** | Deep needs analysis | Discovery call scheduled | Discovery complete, demo scheduled | 1-2 weeks | 25% |
| **4. Demo** | Product demonstration | Demo scheduled | Demo delivered, positive feedback | 1 week | 40% |
| **5. Proposal** | Formal proposal sent | Proposal requested by customer | Proposal sent, review in progress | 3-7 days | 60% |
| **6. Negotiation** | Terms being finalized | Customer verbally committed | Contract sent to legal/procurement | 1-3 weeks | 80% |
| **7. Closed-Won** | Contract signed | Signatures complete, payment received | Deal marked won, CS handoff | N/A | 100% |
| **8. Closed-Lost** | Lost to competitor or no decision | Deal is dead | Loss reason documented | N/A | 0% |

---

### Stage Advancement Rules

**Only advance stages when exit criteria are met.**

**Bad:** Move to "Proposal" because "we talked about pricing"
**Good:** Move to "Proposal" because "customer requested formal proposal in writing"

**When in doubt, stay in earlier stage.** Better to be conservative than optimistic.

---

## Activity Logging

### What to Log (Mandatory)

**Every customer interaction must be logged:**

1. **Calls & Meetings**
   - Date/time
   - Duration
   - Attendees (tag contacts in HubSpot)
   - Summary (3-5 bullet points)
   - Next steps
   - Sentiment (positive, neutral, negative)

2. **Emails**
   - Auto-logged via HubSpot email integration
   - Tag important emails manually

3. **Demos**
   - Date/time
   - Attendees
   - Use cases shown
   - Objections raised
   - Next steps

4. **Proposals**
   - Date sent
   - Amount
   - Link to proposal document
   - Decision timeline

5. **Closed Deals**
   - Won/Lost
   - Win/Loss reason (detailed)
   - Competitor (if lost)
   - Lessons learned

---

### Call/Meeting Notes Template

```
**Date:** 2026-01-15
**Duration:** 45 minutes
**Attendees:** Sarah Chen (VP Eng), John Doe (CTO)
**Type:** Discovery Call

**Summary:**
- TechCo is struggling with slow deployments (deploy 1x/week, want daily)
- Current AWS setup costs $80K/month, growing 20%/quarter
- Need SOC 2 by Q2 to close enterprise deals
- 5 DevOps engineers, all focused on infrastructure toil
- Strong pain: Lost 2 enterprise deals due to lack of SOC 2

**Pain Points:**
1. Deployment velocity (biggest pain)
2. Cloud cost optimization
3. SOC 2 compliance

**BANT++ Assessment:**
- Budget: $200K allocated for infrastructure improvements (20 pts)
- Authority: CTO engaged, will loop in CFO for final approval (20 pts)
- Need: Critical pain, losing deals (25 pts)
- Timeline: Must have SOC 2 by Q2 (June 30) (25 pts)
- Competition: Evaluating us + OpenShift (12 pts)
- Champion: VP Eng is strong advocate (8 pts)
- **BANT++ Score: 110/125 (Highly Qualified)**

**Next Steps:**
- [ ] Schedule demo for Jan 22 (Sarah, John, + DevOps team)
- [ ] Send case study: Similar SaaS company, SOC 2 timeline
- [ ] Intro to CFO (via Sarah)

**Sentiment:** 🟢 Positive - strong interest, clear pain, timeline urgency
```

---

## Data Hygiene Rules

### Rule 1: No Duplicate Records

**Before creating a new contact/company:**
1. Search HubSpot first
2. Use company domain to find existing records
3. Merge duplicates immediately if found

**How to Merge:**
- HubSpot → Contacts → Select duplicates → Actions → Merge

---

### Rule 2: Keep Data Current

**Update records when:**
- Job title changes (LinkedIn check)
- Contact leaves company (mark as "Left Company")
- Company gets acquired or rebrands
- Funding round announced (update "Funding Stage")

**Quarterly cleanup:**
- Review all open deals >90 days old (close or update)
- Update contact info (titles, emails)
- Archive inactive contacts

---

### Rule 3: Standard Naming Conventions

| Record Type | Format | Example |
|-------------|--------|---------|
| **Deal Name** | `[Company] - [Product Tier]` | "TechCo - Enterprise" |
| **Contact Name** | `[First] [Last]` | "Sarah Chen" |
| **Company Name** | Official legal name (no abbreviations unless standard) | "TechCo Inc." (not "TC") |
| **Email** | Lowercase | "sarah.chen@techco.com" |

---

### Rule 4: Use Picklists Consistently

**Don't free-text when picklists exist.**

**Example: Deal Lost Reason**
- ✅ Use: "Price - Too Expensive"
- ❌ Don't write: "they said we cost too much"

**Common Picklist Fields:**
- Industry
- Deal Stage
- Lead Source
- Product Tier
- Competitor
- Loss Reason

---

## Deal Hygiene Checklist

### Weekly (Every Friday)

- [ ] Review all open deals
- [ ] Update deal stages (based on recent activity)
- [ ] Add notes for all customer interactions this week
- [ ] Update close dates (if timeline changed)
- [ ] Flag stalled deals (no activity in 14+ days)

### Monthly

- [ ] Review pipeline coverage (do you have 3x quota in pipeline?)
- [ ] Close/archive dead deals (lost or disqualified)
- [ ] Update BANT++ scores (if new info learned)
- [ ] Review forecast accuracy (were your predictions correct?)

### Quarterly

- [ ] Clean up old contacts (mark inactive if no response in 90+ days)
- [ ] Review win/loss reasons (spot patterns)
- [ ] Update ICP scores (based on wins/losses)
- [ ] Archive closed deals from 12+ months ago

---

## Forecasting in HubSpot

### Weighted Forecast Formula

```
Weighted Pipeline = Σ (Deal Value × Stage Probability)
```

**Example:**

| Deal | Value | Stage | Probability | Weighted Value |
|------|-------|-------|-------------|----------------|
| TechCo | $180K | Proposal | 60% | $108K |
| FinServ Inc | $500K | Negotiation | 80% | $400K |
| HealthCo | $250K | Demo | 40% | $100K |
| **Total** | **$930K** | - | - | **$608K** |

**Your forecast is $608K for the quarter.**

---

### Forecast Categories

| Category | Criteria | Accuracy Expectation |
|----------|----------|---------------------|
| **Commit** | Verbal agreement + contract in legal | >90% close probability |
| **Best Case** | Proposal sent, positive feedback | 60-90% close probability |
| **Pipeline** | Qualified opportunities in discovery/demo | <60% close probability |
| **Omitted** | Long-shot deals or unqualified | Exclude from forecast |

**Only commit to deals you're >90% confident will close.**

---

## Custom Fields (BlackRoad OS Specific)

### ICP Score (0-100)

**Calculated based on ICP framework:**
- 80-100: Perfect Fit
- 60-79: Good Fit
- <60: Poor Fit

**Use this to prioritize deals.**

---

### BANT++ Score (0-125)

**Calculated based on qualification matrix:**
- Budget (0-25)
- Authority (0-25)
- Need (0-25)
- Timeline (0-25)
- Competition (0-15)
- Champion (0-10)

**Use this to assess close probability.**

---

### Pain Points (Multi-Select)

Options:
- Deployment velocity
- Cloud costs
- Compliance/security
- Scalability
- DevOps headcount
- Vendor lock-in
- Infrastructure complexity

---

### Competitor (Dropdown)

Options:
- AWS DIY
- Heroku
- Render
- Railway
- OpenShift
- Tanzu
- Vercel
- Netlify
- DIY Kubernetes
- None
- Other

---

## Reporting & Dashboards

### Sales Rep Dashboard (Daily View)

**Key Metrics:**
- Pipeline coverage (current pipeline / remaining quota)
- Deals closing this month (by stage)
- Activity this week (calls, demos, proposals)
- Open tasks (overdue + due today)

---

### Sales Manager Dashboard

**Team Metrics:**
- Team quota attainment (% to goal)
- Pipeline health (coverage, velocity)
- Win rate by rep
- Activity metrics (calls, demos per rep)
- Forecast accuracy (predicted vs. actual)

---

### Executive Dashboard

**Business Metrics:**
- Revenue (actual vs. target)
- New customers (count, ACV)
- Win rate (overall and by source)
- Sales cycle length (trend)
- CAC and NRR

---

## CRM Automation

### Email Integration

**Connect your email to HubSpot:**
1. HubSpot → Settings → Email Integration
2. Connect Gmail/Outlook
3. Enable auto-logging of emails

**Result:** All customer emails auto-log to CRM (no manual work)

---

### Meeting Scheduler (Calendly Integration)

**Embed Calendly link in outreach:**
- "Book time: [calendly.com/yourname]"

**Auto-creates HubSpot meeting when booked.**

---

### Deal Stage Automation

**Auto-advance stages based on triggers:**
- Email opened → Move to "Qualified"
- Demo booked → Move to "Demo Scheduled"
- Proposal sent → Move to "Proposal"

**Configure in HubSpot Workflows.**

---

## Common CRM Mistakes & Fixes

### Mistake 1: Logging Activities Late

**Problem:** Forget details, data is inaccurate

**Fix:** Log immediately after call/meeting (within 15 minutes)

---

### Mistake 2: Optimistic Stage Movement

**Problem:** Deals in "Proposal" but no proposal sent

**Fix:** Only advance when exit criteria met. Stay conservative.

---

### Mistake 3: Duplicate Records

**Problem:** Same contact exists 3 times, data fragmented

**Fix:** Search before creating. Merge duplicates weekly.

---

### Mistake 4: Missing Close Dates

**Problem:** Deals sit in pipeline forever, forecast inaccurate

**Fix:** Every deal must have realistic close date. Update monthly.

---

### Mistake 5: No Loss Reasons

**Problem:** Can't learn from losses, repeat mistakes

**Fix:** Always document detailed loss reason when marking "Closed-Lost"

---

## CRM Audit Checklist

### Monthly CRM Health Check

- [ ] **Duplicate Check:** Search for duplicates, merge
- [ ] **Stage Accuracy:** Review all deals, ensure stages match reality
- [ ] **Close Date Review:** Update close dates for all open deals
- [ ] **Activity Logging:** All calls/meetings logged?
- [ ] **Contact Updates:** Job titles current? (LinkedIn check)
- [ ] **Dead Deal Cleanup:** Close deals with no activity in 30+ days

**Run this audit first Friday of every month.**

---

## CRM Performance Metrics

### Individual Rep Scorecard

| Metric | Target | How to Measure |
|--------|--------|----------------|
| **Data Completeness** | >90% | Required fields filled in CRM |
| **Activity Logging** | 100% | All calls/meetings logged within 24 hours |
| **Deal Hygiene** | >95% | Deals have notes, accurate stages, close dates |
| **Forecast Accuracy** | 90-110% | Forecast vs. actual revenue |
| **Duplicate Rate** | <2% | Duplicate contacts/companies |

---

## Training & Resources

### HubSpot Academy

**Required Courses:**
- HubSpot CRM Fundamentals (2 hours)
- Sales Pipeline Management (1 hour)
- Forecasting Best Practices (30 minutes)

**Access:** academy.hubspot.com

---

### Internal Resources

**CRM Admin:** salesops@blackroad.io
**HubSpot Support:** support.hubspot.com
**Slack Channel:** `#crm-questions`

---

## FAQs

**Q: What if I forget to log a call?**
A: Log it as soon as you remember. Better late than never.

**Q: How do I know if a deal is "qualified"?**
A: BANT++ score >63. If unsure, err on side of caution (keep in "Prospect").

**Q: Can I delete old contacts?**
A: No. Archive instead (mark as "Inactive"). We need historical data.

**Q: What if the customer doesn't fit ICP but I want to pursue?**
A: Discuss with sales manager. Sometimes strategic deals justify exceptions.

**Q: How often should I update deal stages?**
A: Real-time. If stage changed today, update today.

---

## Final Thoughts

**Your CRM is your most important tool.**

Good CRM hygiene = predictable revenue.

**Commit to:**
- ✅ Logging all activities within 24 hours
- ✅ Accurate deal stages (no sandbagging or optimism)
- ✅ Complete required fields (100%)
- ✅ Weekly pipeline reviews
- ✅ Monthly data cleanup

**The discipline you show in CRM management directly correlates to sales success.**

---

**Version:** 1.0.0
**Last Updated:** January 4, 2026
**Owner:** Joaquin, Sales Master

*Clean data. Accurate forecasts. Predictable revenue.*
