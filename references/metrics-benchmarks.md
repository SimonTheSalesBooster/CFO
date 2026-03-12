# CFO Metrics & Benchmarks Reference

## Unit Economics Calculations

### Customer Lifetime Value (LTV)
```
LTV = ARPU × Gross Margin % × Average Customer Lifetime

Where:
- ARPU = Average Revenue Per User (monthly or annual)
- Gross Margin % = (Revenue - COGS) / Revenue
- Average Customer Lifetime = 1 / Monthly Churn Rate
```

Example:
- ARPU: $200/month
- Gross Margin: 80%
- Monthly Churn: 2%
- LTV = $200 × 0.80 × (1/0.02) = $8,000

### Customer Acquisition Cost (CAC)
```
CAC = Total Sales & Marketing Spend / New Customers Acquired

Include:
- Salaries (sales + marketing team)
- Ad spend
- Tools and software
- Content production costs
- Event costs
```

### LTV:CAC Ratio
| Ratio | Assessment | Action |
|-------|-----------|--------|
| <1:1 | Losing money on every customer | Stop acquiring, fix unit economics |
| 1-2:1 | Unsustainable | Reduce CAC or increase LTV urgently |
| 3:1 | Healthy minimum | Maintain |
| 5:1+ | Strong | Can invest more in growth |
| 7-8:1 | Best-in-class | May be underinvesting in growth |

### CAC Payback Period
```
CAC Payback = CAC / (ARPU × Gross Margin %)
```

| Payback | Assessment |
|---------|-----------|
| <6 months | Excellent — fast capital recycling |
| 6-12 months | Good — healthy for bootstrapped |
| 12-18 months | Concerning — cash tied up too long |
| >18 months | Dangerous — bootstrapped companies can't sustain this |

## SaaS Benchmarks by Stage

### Revenue Growth Rates
| ARR | Median Growth | Top Quartile |
|-----|--------------|--------------|
| $1-2.5M | 100-200% | 300%+ |
| $2.5-10M | 60-80% | 100%+ |
| $10-25M | 40-60% | 80%+ |
| $25-50M | 30-40% | 50%+ |
| $50M+ | 25-30% | 40%+ |

### Net Revenue Retention (NRR)
```
NRR = (Starting MRR + Expansion - Contraction - Churn) / Starting MRR × 100
```

| NRR | Assessment |
|-----|-----------|
| <90% | Leaky bucket — fix churn before growing |
| 90-100% | Stable but not growing from base |
| 100-110% | Good — existing customers growing |
| 110-130% | Excellent — strong expansion revenue |
| 130%+ | Best-in-class (usually enterprise) |

### Gross Margin
| Type | Target |
|------|--------|
| SaaS | 70-85% |
| Services | 50-70% |
| Marketplace | 60-75% |
| Hardware + Software | 40-60% |

## Cash Flow Metrics

### Operating Cash Flow
```
OCF = Net Income + Non-Cash Charges + Changes in Working Capital

Key non-cash charges:
- Depreciation & amortization
- Stock-based compensation
- Deferred revenue changes
```

### Free Cash Flow
```
FCF = Operating Cash Flow - Capital Expenditures
```

### Cash Conversion Score
```
CCS = Free Cash Flow / EBITDA
```
- Target: >0.5 (converting half of EBITDA to cash)
- Best-in-class: >0.8

### Monthly Burn Rate
```
Gross Burn = Total monthly operating expenses
Net Burn = Total expenses - Total revenue
```

### Runway
```
Runway (months) = Cash Balance / Net Monthly Burn
```

| Runway | Status |
|--------|--------|
| >36 months | Strong — can be aggressive |
| 24-36 months | Healthy minimum |
| 12-24 months | Caution — start conserving |
| 6-12 months | Danger — cut costs now |
| <6 months | Crisis — survival mode |

## Spending Benchmarks by ARR

### $1-3M ARR (Early Stage)
| Category | % of ARR | Notes |
|----------|----------|-------|
| COGS | 20-30% | Infrastructure, support |
| R&D | 30-40% | Product development |
| Sales | 15-20% | Often founder-led |
| Marketing | 10-15% | Primarily content/SEO |
| G&A | 10-15% | Lean operations |
| **Total** | **85-120%** | May not be profitable yet |

### $3-10M ARR (Growth Stage)
| Category | % of ARR | Notes |
|----------|----------|-------|
| COGS | 20-25% | Scale efficiencies |
| R&D | 25-30% | Platform maturity |
| Sales | 10-15% | Repeatable process |
| Marketing | 8-12% | Brand building |
| G&A | 12-15% | Process investment |
| **Total** | **75-97%** | Should be approaching profit |

### $10-50M ARR (Scale Stage)
| Category | % of ARR | Notes |
|----------|----------|-------|
| COGS | 15-25% | Economies of scale |
| R&D | 20-25% | Maintenance + innovation |
| Sales | 8-12% | Efficient machine |
| Marketing | 5-10% | Brand leverage |
| G&A | 10-14% | Optimized |
| **Total** | **58-86%** | Healthy margins |

## Rule of 40 Scenarios

The Rule of 40 states that a healthy SaaS company's revenue growth rate plus profit margin should exceed 40%.

```
Rule of 40 Score = Revenue Growth % + EBITDA Margin %
```

| Growth | Margin | Score | Profile |
|--------|--------|-------|---------|
| 50% | -10% | 40 | Investing heavily in growth |
| 40% | 0% | 40 | Growth-focused, breakeven |
| 30% | 10% | 40 | Balanced |
| 20% | 20% | 40 | Profitable growth |
| 10% | 30% | 40 | Profit-focused |
| 5% | 35% | 40 | Cash cow |

**For bootstrapped companies:** Bias toward the bottom rows. You don't have VC money to fund negative margins. Target 15-25% growth + 15-25% margin.

## Revenue Quality Metrics

### Monthly Recurring Revenue (MRR) Components
```
Starting MRR
+ New MRR (new customers)
+ Expansion MRR (upgrades, add-ons)
- Contraction MRR (downgrades)
- Churned MRR (cancellations)
= Ending MRR
```

### Revenue Concentration Risk
| Metric | Green | Yellow | Red |
|--------|-------|--------|-----|
| Largest customer | <5% revenue | 5-10% | >10% |
| Top 5 customers | <15% revenue | 15-25% | >25% |
| Top 10 customers | <25% revenue | 25-40% | >40% |

### Revenue Mix
| Type | Predictability | Margin | Preference |
|------|---------------|--------|------------|
| Recurring (subscriptions) | High | 70-85% | Best |
| Usage-based | Medium | 60-80% | Good |
| One-time (setup, consulting) | Low | 40-70% | Minimize |
| Services | Low | 30-60% | Strategic only |

## Hiring ROI Framework

### Cost of a Hire
```
True Annual Cost = Salary × 1.25-1.40

Multiplier includes:
- Benefits (health, dental, vision)
- Payroll taxes
- Equipment
- Software licenses
- Office/remote stipend
- Training
```

### Revenue Per Employee
| Stage | Target | Best-in-class |
|-------|--------|---------------|
| $1-5M ARR | $110-150K | $200K+ |
| $5-10M ARR | $150-200K | $250K+ |
| $10-50M ARR | $200-250K | $350K+ |
| $50M+ ARR | $250-400K | $500K+ |

### Hire Payback Calculation
```
Time to Productivity: 3-6 months (role dependent)
Payback Period = (True Annual Cost × (Months to Productivity / 12) + True Annual Cost) / Annual Revenue Impact
```

Rule of thumb: If you can't articulate how a hire generates 3x their cost in 12 months, don't make the hire.
