# Your $200K CFO Decision Is Probably Wrong

Most founders either hire a CFO too early (burning $200K+ on a $2M company) or too late (when cash is already critical).

There's a third option.. skip the hire, keep the rigor.

---

## What This Actually Does

Sprint CFO runs the same financial diagnostics a top-tier CFO would — unit economics, cash management, capital allocation, forecasting — calibrated for companies that fund growth from profits, not pitch decks.

No VC assumptions. No "raise more money" answers.

## The Numbers That Matter

| Metric | Target | Danger Zone |
|--------|--------|-------------|
| LTV:CAC | 3:1+ | <1:1 |
| CAC Payback | <12 months | >18 months |
| Runway | 24-36 months | <12 months |
| NRR | >100% | <90% |
| Gross Margin | 70-80% | <50% |
| Revenue/Employee | $200K+ | <$110K |
| Rule of 40 | Growth % + Margin % >= 40 | <20 |

These aren't aspirational. They're the line between survival and death spiral.

## Five Patterns From Companies That Got It Right

Mailchimp ($12B exit, zero VC). Basecamp (25+ years profitable). ConvertKit ($40M ARR, 51% margins). Zapier. Zoho.

What they share:

1. **Revenue per employee above $500K** — elite efficiency beats headcount
2. **CAC approaching zero** — product-led growth, partnerships, ecosystems
3. **Margins before growth** — profitability is non-negotiable, even early
4. **Simple pricing** — complex pricing requires complex sales operations
5. **Annual prepay** — customers finance your growth at 0% interest

Case studies and detailed calculations in [references/](references/).

## How to Use It

### Claude Code slash command

```
/cfo should I hire a second developer at $120K?
/cfo what metrics should I track at $2M ARR?
/cfo help me build a 13-week cash forecast
```

### Installation

**Global (every Claude Code session):**

```bash
git clone https://github.com/SimonTheSalesBooster/cfo.git
cp cfo/.claude/commands/cfo.md ~/.claude/commands/
cp -r cfo/cfo.md cfo/references ~/cfo/
```

**Per-project:**

```bash
cd your-project
git clone https://github.com/SimonTheSalesBooster/cfo.git .claude/skills/cfo
```

### Standalone

Paste `cfo.md` into ChatGPT, Claude, or any frontier model. Then ask your question.

---

## About

Built by Simon Severino — author of *Strategy Sprints* and *Time Freedom* with Jay Abraham. Added over $2 Billion in sales to B2B clients in finance, software, and consulting.

[Book a free Strategy Sprint call](https://www.strategysprints.com)

*keep rolling, Simon & The Sprinters*
