# ICP Matrix: AI-Powered Market Research Platform
# Version: 1.0 | Last Updated: 2026-03-23
# Status: Draft — awaiting worst-customer data and tech stack validation

---

## Overview

Two primary segments identified from initial input. Each segment has a distinct trigger,
buyer profile, and outreach strategy. Do NOT blend in a single campaign.

```
Segment A: "PMF-Seeking Startups"   → Primary segment
Segment B: "Established Innovators" → Secondary segment
```

---

## Segment A: PMF-Seeking Startups

> Early-stage startups that need to understand what real users think, feel, and say
> in order to find (or confirm) product-market fit before they run out of runway.

### Firmographic Profile

| Attribute | Tier 1 | Tier 2 | Tier 3 | DQ |
|-----------|--------|--------|--------|----|
| Company size | 5–30 employees | 31–75 employees | 2–4 employees (solo founder) | 1 person / 75+ employees |
| Revenue | Pre-revenue to $500K ARR | $500K–$2M ARR | $2M–$5M ARR | $5M+ ARR (moved past PMF) |
| Industry | B2B SaaS, Consumer App, Marketplace | D2C brand, Fintech, Edtech | Hardware/IoT, Agency | Services-only, Non-profit |
| Geography | US, UK, Canada | Western Europe, Australia | LATAM, SEA | Restricted markets |
| Business model | Product-led, subscription | Sales-led SaaS | E-commerce | Pure services / consulting |
| Growth stage | Pre-seed to Seed | Series A (early) | Series A (late) | Series B+ |

### Target Personas (Ranked by Priority)

| Rank | Title Pattern | Seniority | Decision Role | Key Pain |
|------|--------------|-----------|---------------|----------|
| P1 | CEO / Co-founder | C-Suite | Economic buyer + Champion | "I don't know why users churn or won't convert — I'm guessing at messaging" |
| P2 | Head of Product / CPO | VP/Director | Champion | "I'm manually reading hundreds of reviews and Reddit threads to find patterns" |
| P3 | Head of Growth / Marketing | Director/Manager | Influencer | "Our positioning feels off but I can't point to specific evidence" |

### Intent Signals (Ranked by Weight)

| Signal | Weight (1–5) | Detection Source |
|--------|-------------|-----------------|
| Actively hiring a Product Manager or Head of Growth | 5 | LinkedIn Jobs, Otta |
| Recently launched on Product Hunt or App Store (< 90 days) | 5 | Product Hunt, App Store |
| Founder posting about "finding PMF" or "user research" on LinkedIn/X | 4 | Social monitoring |
| Recent seed or pre-seed funding announcement | 4 | Crunchbase, LinkedIn |
| Job posting mentions "customer discovery" or "user interviews" | 4 | LinkedIn Jobs |
| Posting jobs in customer success or onboarding roles | 3 | LinkedIn Jobs |
| Founder active on communities (Indie Hackers, Slack groups) | 3 | Community listening |
| No detectable intent signal | 1 | — |

### Technographic Fit

| Tool/Stack Signal | Signal Strength | Why It Matters |
|-------------------|----------------|----------------|
| Uses Intercom, Mixpanel, or Amplitude | Strong | Actively tracking users, budget for tools |
| Uses Notion or Linear for product management | Medium | Modern stack, high tool adoption |
| Uses Typeform / Maze for user research | Strong | Existing research practice, proven budget |
| Zapier or Make in stack | Medium | Automation-friendly, will integrate |
| No product analytics tools at all | Weak | May lack maturity to act on insights |

### Scoring Model

| Dimension | Attribute | Tier 1 pts | Tier 2 pts | Tier 3 pts |
|-----------|-----------|-----------|-----------|-----------|
| Firmographic | 5–30 employees | 8 | 4 | 2 |
| Firmographic | Pre-seed to Seed stage | 8 | 4 | 2 |
| Firmographic | B2B SaaS / Consumer App | 6 | 3 | 1 |
| Technographic | Uses Mixpanel/Amplitude/Intercom | 6 | 3 | 1 |
| Intent | Hiring Product or Growth role | 10 | 5 | 2 |
| Intent | Recent product launch (< 90 days) | 10 | 5 | 2 |
| Intent | Recent seed funding | 8 | 4 | 2 |
| Persona | CEO or Head of Product as contact | 6 | 3 | 1 |
| **Total possible** | | **62** | | |

**Tier thresholds:**
- Tier 1 (Bullseye): 50+ pts
- Tier 2 (Strong Fit): 37–49 pts
- Tier 3 (Good Fit): 25–36 pts
- DQ: Below 25 pts OR firmographic DQ flag triggered

### Outreach Strategy by Tier

| Tier | Criteria | Strategy | Volume |
|------|----------|----------|--------|
| Tier 1 | 50+ pts | Hyper-personalized: reference their product, recent launch, or hiring signal. Multi-channel (email + LinkedIn). 8+ touches. | 5–10% of list |
| Tier 2 | 37–49 pts | Signal-based personalization: reference funding or growth stage. Email-first + LinkedIn connect. 5–6 touches. | 25–35% of list |
| Tier 3 | 25–36 pts | Bucket messaging: "early-stage founders struggling with PMF." Email only. 3–4 touches. | 40–50% of list |
| DQ | < 25 pts | Do not contact | Remove |

---

## Segment B: Established Innovators

> Grown companies with an existing product base that need a competitive or messaging
> edge — either to out-position competitors or to communicate their product's value
> more effectively to their market.

### Firmographic Profile

| Attribute | Tier 1 | Tier 2 | Tier 3 | DQ |
|-----------|--------|--------|--------|----|
| Company size | 50–300 employees | 301–1,000 employees | 20–49 employees | < 20 or > 1,000 |
| Revenue | $5M–$50M ARR | $50M–$150M ARR | $2M–$5M ARR | < $2M or $150M+ |
| Industry | B2B SaaS, Tech, Fintech | Consumer goods, Retail, Media | Healthcare, Edtech | Highly regulated w/ no research budget |
| Geography | US, UK, Canada | Western Europe, Australia | LATAM, SEA | Restricted markets |
| Business model | Subscription / SaaS | E-commerce / DTC | Marketplace | Pure services |
| Growth stage | Series B–D / Profitable SME | Series E+ | Post-IPO (innovation arm) | Pre-revenue |

### Target Personas (Ranked by Priority)

| Rank | Title Pattern | Seniority | Decision Role | Key Pain |
|------|--------------|-----------|---------------|----------|
| P1 | VP of Marketing / CMO | VP/C-Suite | Economic buyer | "We're losing ground to competitors and don't know exactly why customers prefer them" |
| P2 | Head of Innovation / Director of Innovation | Director/VP | Champion | "We need customer insight at scale to drive our product roadmap without expensive research agencies" |
| P3 | CEO / Managing Director (SME) | C-Suite | Economic buyer + Champion | "I want to know what the market is actually saying about us vs. competitors — without hiring a research firm" |

### Intent Signals (Ranked by Weight)

| Signal | Weight (1–5) | Detection Source |
|--------|-------------|-----------------|
| Competitor just launched a major feature or rebranded | 5 | News, LinkedIn |
| Company entered a new market or launched new product line | 5 | Press releases, LinkedIn |
| Hiring a Market Research, Consumer Insights, or Competitive Intel role | 5 | LinkedIn Jobs |
| New CMO or VP Marketing hired in last 6 months | 4 | LinkedIn |
| Company ran a fundraise or M&A event in last 12 months | 4 | Crunchbase, news |
| Hiring content or brand team (signals messaging investment) | 3 | LinkedIn Jobs |
| Mentioned "voice of customer" or "customer insights" in job posts | 4 | LinkedIn Jobs |
| No detectable intent | 1 | — |

### Technographic Fit

| Tool/Stack Signal | Signal Strength | Why It Matters |
|-------------------|----------------|----------------|
| Uses Qualtrics, SurveyMonkey, or Medallia | Strong | Active research budget, replacing/augmenting |
| Uses HubSpot or Salesforce Marketing Cloud | Strong | Established marketing ops, budget for tools |
| Uses Brandwatch, Sprinklr, or Mention | Very Strong | Direct competitor — active buyer in category |
| Uses Tableau or Looker | Medium | Data-driven culture, will value AI insights |
| No research tooling visible | Weak | May not prioritize structured insights |

### Scoring Model

| Dimension | Attribute | Tier 1 pts | Tier 2 pts | Tier 3 pts |
|-----------|-----------|-----------|-----------|-----------|
| Firmographic | 50–300 employees | 8 | 4 | 2 |
| Firmographic | Series B–D or profitable SME | 8 | 4 | 2 |
| Firmographic | B2B SaaS / Tech / Fintech | 6 | 3 | 1 |
| Technographic | Uses research/listening tools | 8 | 4 | 2 |
| Technographic | Uses Salesforce or HubSpot | 4 | 2 | 1 |
| Intent | Hiring Market Research / Insights role | 10 | 5 | 2 |
| Intent | New CMO / VP Mktg in last 6 months | 8 | 4 | 2 |
| Intent | New product launch or market entry | 10 | 5 | 2 |
| Persona | VP Marketing / Head of Innovation as contact | 6 | 3 | 1 |
| **Total possible** | | **68** | | |

**Tier thresholds:**
- Tier 1 (Bullseye): 55+ pts
- Tier 2 (Strong Fit): 41–54 pts
- Tier 3 (Good Fit): 27–40 pts
- DQ: Below 27 pts OR firmographic DQ flag triggered

### Outreach Strategy by Tier

| Tier | Criteria | Strategy | Volume |
|------|----------|----------|--------|
| Tier 1 | 55+ pts | Hyper-personalized: reference their specific competitive landscape, recent move, or new hire. Multi-channel. 8+ touches. | 5–10% of list |
| Tier 2 | 41–54 pts | Signal-based: reference market shift or new hire. Email-first + LinkedIn. 5–6 touches. | 25–35% of list |
| Tier 3 | 27–40 pts | Bucket messaging: "companies looking for competitive market intelligence." Email only. 3–4 touches. | 40–50% of list |
| DQ | < 27 pts | Do not contact | Remove |

---

## Shared Disqualification Triggers

Remove from all lists immediately if:
- Already a customer
- Competitor or partner
- Company has < 2 employees (no budget)
- Pure services firm with no product to research
- Invalid/unverifiable contact data
- Operates in a market you cannot serve (regulatory, geo)

---

## Validation Metrics (Update Quarterly)

### Segment A: PMF-Seeking Startups

| Metric | Tier 1 | Tier 2 | Tier 3 |
|--------|--------|--------|--------|
| Positive reply rate | TBD | TBD | TBD |
| Meeting booked rate | TBD | TBD | TBD |
| Close rate | TBD | TBD | TBD |
| Avg deal size | TBD | TBD | TBD |
| Avg sales cycle | TBD | TBD | TBD |

### Segment B: Established Innovators

| Metric | Tier 1 | Tier 2 | Tier 3 |
|--------|--------|--------|--------|
| Positive reply rate | TBD | TBD | TBD |
| Meeting booked rate | TBD | TBD | TBD |
| Close rate | TBD | TBD | TBD |
| Avg deal size | TBD | TBD | TBD |
| Avg sales cycle | TBD | TBD | TBD |

---

## Open Questions (Validate to Sharpen Matrix)

1. **Worst customer profile** — Who has churned or been a painful deal? What did they have in common? This will sharpen DQ criteria and tier thresholds.
2. **Tech stack of best customers** — What tools do they already use? Helps identify integration-based triggers.
3. **Average deal size by segment** — Informs how much outreach investment each tier deserves.
4. **Sales cycle length** — Determines sequence length and follow-up cadence.
5. **Primary acquisition to date** — How have customers found you so far? Inbound, referral, or outbound? Affects scoring weights.

---

## Next Steps

| Step | Action | Owner |
|------|--------|-------|
| 1 | Interview 5 best customers — validate triggers, titles, and stack | Founder / Sales |
| 2 | Identify 5 churned/bad-fit customers — build DQ pattern | Founder / Sales |
| 3 | Build first prospect lists targeting Tier 1 of each segment | GTM / Sales |
| 4 | Launch test campaign (50–100 contacts per segment) | GTM |
| 5 | After 4 weeks: compare reply/meeting rate by tier, update scoring weights | GTM |
| 6 | Re-run matrix quarterly with campaign data | GTM |
