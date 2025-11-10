# The Easy Dollar: Content Plan & Task Breakdown

## Overview

This document contains the complete plan for completing *The Easy Dollar* financial education book. Each task is self-contained and executable. When you assign a task to Claude Code, it will have all the context needed to understand what to write, how to write it, and what values/philosophy to embed.

---

## CRITICAL: Read These Skills First

**Every agent working on this content MUST read and understand these foundational resources:**

1. **Financial Expertise Skill** (`.claude/skills/financial-expertise/`)
   - Ensures all financial recommendations align with Bogleheads and Dave Ramsey principles
   - Validates calculations, terminology, and evidence-based advice
   - Corrects common misconceptions and failures (stock picking, day trading, leverage)
   - Read the core-philosophy, retirement-accounts, investment-vehicles, and calculations files

2. **Writing Clearly & Concisely** (`.claude/skills/writing-clearly-and-concisely/`)
   - Apply William Strunk Jr.'s *Elements of Style* principles
   - Use active voice, positive form, concrete language
   - Omit needless words; place emphatic words at end of sentence
   - Keep related words together

---

## The Easy Dollar Philosophy & Voice

### Core Mission
"Never put your money into something you don't fully understand."

This site teaches financial literacy to **everyday people who feel lost or conned**. The tone is:
- **Empathetic, not condescending**: "I still feel like an idiot" (from Introduction). Acknowledge that financial advice is confusing by design.
- **Practical, not theoretical**: Show people how to actually do things, not just understand concepts.
- **Anti-bullshit**: Call out what doesn't work with evidence. No hype, no get-rich-quick, no market timing.
- **Encouraging**: "You can do this" (from Retirement Investing). People at every income level achieve financial independence.

### What This Book Is
- A **reference**, not a blog with weekly posts
- Organized by topic, not chronologically
- Written to teach self-sufficiency, not to sell anything
- Free of conflicts of interest

### What This Book Is NOT
- Financial advice ("I'm not here to tell you what to do with your money")
- Stock picking guidance (you can't beat the market)
- Cryptocurrency investment promotion (probably don't, but here's why you might care)
- A get-rich-quick scheme
- For people who want to "game the system"

---

## Author's Values & Biases (Encode These)

### Strongly Believe & Recommend
✅ Index fund investing via Vanguard, Fidelity, or Schwab
✅ Dave Ramsey's 7 Baby Steps (debt elimination first, then investing)
✅ YNAB / zero-based budgeting philosophy
✅ Boring, passive, long-term investing
✅ Diversification and simplicity (1-fund or 3-fund portfolios)
✅ Bogleheads philosophy
✅ Financial independence as the real goal of retirement (not age-based)
✅ Emergency funds before aggressive investing
✅ Roth accounts (psychological win: pay taxes now, enjoy tax-free growth)
✅ Compound interest as life-changing
✅ "Leave it the f*** alone" approach to investing

### Explicitly Reject (with Evidence)
❌ Stock picking (89.5% of pros can't beat the market)
❌ Day trading (80-95% failure rate)
❌ Market timing (impossible to predict)
❌ Credit card rewards chasing (behavioral spending increases 12-18%)
❌ Debt leverage for investing (risk amplification is dangerous)
❌ High-fee actively managed funds
❌ Mint.com-style passive tracking apps (doesn't drive behavior change)
❌ "Get rich quick" schemes
❌ Trusting financial "advisors" without questioning them

### Tone Notes
- Reference Dave Ramsey, Bogleheads, and trusted sources by name
- Use real examples and scenarios (e.g., car emergencies, compound growth over 43 years)
- Acknowledge the reader's fear/confusion without dismissing it
- Use conversational, direct language
- Include disclaimers when appropriate (e.g., "I'm not a tax pro!")

### Personality Quirks
- Self-aware about not being an expert in everything ("This topic has been written on a million times")
- Willing to say "I don't know" or "This is complex"
- References external sources (Investopedia calculators, Ramsey Solutions tools)
- Uses humor to make dry topics approachable
- Respects the reader's intelligence

---

## The Reorganized Book Structure

**CRITICAL CHANGE FROM ORIGINAL OUTLINE:**

The original outline put "Investing" (section 2) before "Personal Finances" (section 3). This is backwards. Most people can't optimize their investments if they can't manage their cash flow.

### New Order (What This Content Plan Delivers)

1. **Introduction** (existing) ← Keep as-is
2. **Personal Finances** (NEW FIRST) ← Foundation skills
   - Budgeting basics
   - Banking 101
   - Insurance essentials
   - Emergency fund strategy

3. **Investing Fundamentals** (existing, reorganized)
   - What is (and isn't) investing (existing)
   - Retirement investing basics (existing)
   - The power of compound growth (existing)
   - Stocks, bonds, and diversification (existing)
   - *Missing: Where to invest (Vanguard, Fidelity, Schwab)*
   - *Missing: Allocations and rebalancing*
   - *Missing: Alternatives to stocks and bonds*

4. **Retirement Accounts Deep Dive** (existing + expanded)
   - 401k, 403b, IRA, TSP, etc. (existing)
   - Roth vs. Traditional (existing)
   - Planning for inflation (existing)
   - Myths to avoid (existing: debt interest rates)
   - *Missing: Tax fundamentals*

5. **The Simplest Investing Paths** (existing)
   - 1-fund portfolio (existing)
   - 3-fund portfolio (existing)

6. **Advanced Topics** (optional depth)
   - Common investing mistakes
   - Technical analysis / market timing (why not to do it)
   - How free brokerages make money
   - Hedge funds
   - Cryptocurrency (brief: why probably not)

---

## Content Plan: Three Phases

### PHASE 1: Personal Finances Foundation (4 Articles)
**Why first**: You can't invest your money wisely if you don't know where it's going.

#### Task 0: Reorganize Outline & Book Structure
- **Type**: Site structure / metadata update
- **What to do**:
  - Update `/content/outline.md` to reflect the new order (Personal Finances FIRST)
  - Update `/content/posts/_index.md` to reflect the new structure
  - Update `/content/_index.md` homepage if needed to direct people to "start here" correctly
  - Move posts around in the filesystem if necessary for organization
  - Ensure Hugo menu structure reflects new order
- **Deliverable**: Updated Hugo site with correct navigation and outline
- **Notes**: This is the scaffolding task. Do this first so other tasks build on the right structure.

---

#### Task 1: "How to Budget: The Zero-Balance Method"
- **Topic**: Zero-based budgeting philosophy, YNAB/EveryDollar approach
- **Tone**: "You've probably tried budgeting and failed. Here's why, and how to actually do it."
- **What to cover**:
  - Why budgeting is hard (behavior change, not math)
  - What a zero-based budget is (every dollar has a job)
  - The difference between traditional budgeting and YNAB philosophy
  - Why Mint.com-style apps don't work (passive tracking ≠ behavior change)
  - Practical steps to set up a 0-balance budget
  - When to use which tool (YNAB, EveryDollar, spreadsheet)
  - Marital harmony (couples managing money together)
- **Key principle to encode**: Budgeting is about control and intentionality, not punishment
- **Avoid**: Complexity. Keep it actionable.
- **Length**: Medium (1500-2000 words)
- **Similar to**: The explanation of compound interest—show the mechanics, then the "why it matters"

---

#### Task 2: "Banking 101: Checking, Savings, and High-Yield Accounts"
- **Topic**: Where to keep money, understanding account types, maximizing interest
- **Tone**: "Banking seems boring and simple, but most people are leaving money on the table."
- **What to cover**:
  - Checking accounts (low/no interest, access, safety)
  - Savings accounts (interest, safety, FDIC insurance)
  - High-yield savings accounts (where to find them, current rates)
  - Money market accounts
  - CDs (certificates of deposit)
  - The difference between banks, credit unions, online banks
  - When to use each (e.g., emergency fund in HYSA)
  - Why interest rates matter (compound it!)
  - How banks make money (don't worry, you're safe)
- **Key principle to encode**: Your money should work for you, even sitting still
- **Avoid**: Complex derivatives or investment banking (not relevant)
- **Length**: Medium (1500-2000 words)
- **Connection**: Links to emergency fund task and investing tasks

---

#### Task 3: "Insurance: What You Actually Need"
- **Topic**: Life, health, home, auto insurance—practical decision tree
- **Tone**: "Insurance is boring and confusing, but getting it wrong is catastrophic. Let's demystify it."
- **What to cover**:
  - Why insurance exists (catastrophic risk transfer, not savings)
  - Life insurance (term, whole, who needs it, how much)
  - Health insurance (employer, individual, ACA, understanding coverage)
  - Homeowners/renters insurance (requirements, what's covered)
  - Auto insurance (liability, collision, comprehensive, minimums)
  - Disability insurance (overlooked, critical for income earners)
  - Umbrella policies (when to consider)
  - What's probably a waste (extended warranties, credit monitoring, etc.)
  - Red flags (predatory practices to avoid)
- **Key principle to encode**: Insurance protects against catastrophic loss, not minor inconveniences
- **Avoid**: Specific recommendations without context (varies by individual)
- **Length**: Medium (2000-2500 words)
- **Note**: Acknowledge "I'm not an insurance expert" but share general framework

---

#### Task 4: "Building an Emergency Fund: Why and How Much"
- **Topic**: The critical bridge between budgeting and investing
- **Tone**: "This is unglamorous, but it's the most important financial decision you'll make."
- **What to cover**:
  - Why emergency funds matter (protection from derailing investments)
  - How much to save (Dave Ramsey: $1000 mini emergency fund, then 3-6 months expenses)
  - How to calculate "months of expenses"
  - Where to keep it (high-yield savings, not under mattress, not in stocks)
  - The tension: emergency fund sits idle but is essential
  - How emergency fund prevents bad decisions (emergency car bill doesn't derail retirement investing)
  - Building it gradually (it's okay to start with $500)
  - What counts as "emergency" (car repair yes, vacation no)
  - Once you have it, don't touch it (unless actually emergency)
- **Key principle to encode**: Emergency fund = permission to invest confidently
- **Connection**: Links back to budgeting, forward to investing
- **Length**: Medium (1500-2000 words)
- **Real example to use**: The compound interest article's example of needing $100 for car emergency mid-investment (show why having it set aside helped)

---

### PHASE 2: Complete the Investing Gaps (4 Articles)
**Why next**: Foundation is set; now complete what you started

---

#### Task 5: "Allocations and Rebalancing: The Math Behind 60/40"
- **Topic**: How to decide portfolio splits, when to rebalance
- **Tone**: "This sounds complex. It's not. Here's the simple version."
- **What to cover**:
  - Asset allocation basics (stocks vs. bonds vs. alternatives)
  - Common allocations (60/40, 70/30, 80/20, 100% stocks)
  - Age-based rules of thumb (100 - age = stock percentage)
  - Risk tolerance assessment (without the nonsense quiz)
  - How to choose YOUR allocation
  - Why rebalance (drift over time, brings you back to plan)
  - How often to rebalance (annually, or when allocation drifts 5%+)
  - How to actually rebalance (sell winners, buy losers—psychological trick!)
  - Tax implications of rebalancing
  - Dollar-cost averaging and rebalancing in taxable accounts
- **Key principle to encode**: Your allocation is YOUR choice based on YOUR timeline. No single answer.
- **Connection**: Builds on what stocks/bonds are (existing article). Links to 1-fund and 3-fund portfolios.
- **Length**: Long (2000-2500 words)
- **Note**: Use concrete examples (e.g., "You're 35, so roughly 65% stocks, 35% bonds")

---

#### Task 6: "Where to Invest: Vanguard, Fidelity, Schwab—and Why It Matters"
- **Topic**: Brokerage comparison, how to choose where to open an account
- **Tone**: "You've got choices. Here's what they are and why I recommend Vanguard (but understand Fidelity/Schwab too)."
- **What to cover**:
  - The landscape: Vanguard, Fidelity, Schwab, others
  - What to look for in a brokerage (fees, fund selection, service, reputation)
  - Vanguard philosophy (client-owned, index-heavy, low-cost)
  - Fidelity (broader selection, good for all strategies)
  - Schwab (strong service, good fees, growing)
  - Account types available at each
  - How to open an account (step-by-step)
  - Fee structures (expense ratios, transaction fees, advisory fees)
  - Why fees matter (compound in reverse!)
  - Comparing fund options (not all "S&P 500 funds" are equal)
  - Red flags (high fees, salesy behavior, unclear pricing)
  - What to avoid (discount brokers known for bad behavior, etc.)
- **Key principle to encode**: Brokerages are a commodity. Choose based on low fees and simplicity.
- **Personal note**: Include why author uses Vanguard (philosophy alignment), but acknowledge others work too
- **Length**: Medium-long (2000-2500 words)
- **Note**: This was promised in original outline as "Vanguard rocks"—deliver that opinion but substantiate it

---

#### Task 7: "Alternatives to Stocks and Bonds: Real Estate, Commodities, and Others"
- **Topic**: What else exists beyond the classic 3-fund portfolio
- **Tone**: "You don't need these. But here's what they are if you're curious."
- **What to cover**:
  - Real estate (primary residence vs. investment property, REITs, risks/rewards)
  - Commodities (gold, oil, why most people shouldn't bother)
  - Bonds (more detail: Treasuries, corporate, municipal, inflation-protected)
  - Alternative investments (hedge funds, private equity—why most people shouldn't)
  - Peer-to-peer lending (risky, probably avoid)
  - Savings bonds (I Bonds, Series EE, inflation protection)
  - Annuities (complex, often not worth it, but explain them)
  - Collectibles/art (not really investments, usually poor returns)
  - Cryptocurrency (defer to longer discussion, but mention here)
  - Why the 3-fund portfolio is usually sufficient
- **Key principle to encode**: Complexity doesn't improve returns. Stick to the basics unless you have a specific reason.
- **Tone caveat**: Acknowledge real estate appeal (tangible, tax benefits) but note it's outside scope for most people
- **Length**: Long (2000-2500 words)
- **Note**: This was outlined as "Alternatives to stocks and bonds"—fill the gap

---

#### Task 8: "Tax Basics for Investors: Capital Gains, Harvesting, and Deductions"
- **Topic**: What taxes you owe on investments, how to minimize them legally
- **Tone**: "Taxes are boring, but understanding them saves you money. I'm not a tax pro, but here's the framework."
- **What to cover**:
  - Types of investment income (ordinary dividends, qualified dividends, capital gains, interest)
  - Short-term vs. long-term capital gains (holding period, tax rates)
  - Tax-advantaged accounts (401k, IRA, HSA—deferred/elimination)
  - Taxable accounts (pay taxes annually, but more flexible)
  - Tax-loss harvesting (selling losers to offset gains)
  - Wash-sale rules (don't immediately rebuy the same thing)
  - Qualified vs. non-qualified dividends
  - Tax-efficient fund selection (index funds are naturally tax-efficient)
  - Municipal bonds (tax-free, but probably not worth complexity)
  - I Bonds and Series EE (tax benefits)
  - Year-end tax planning basics
  - When to call a professional
- **Key principle to encode**: Pay what you legally owe, not a penny more. But taxes shouldn't drive bad investment decisions.
- **Disclaimer**: "I'm not a tax pro! Use this as a framework, consult a professional for your situation."
- **Length**: Long (2000-2500 words)
- **Note**: This was outlined as promised but missing—deliver it

---

### PHASE 3: Advanced Topics & Polish (4-6 Articles, Optional)
**Why later**: These add depth and address edge cases. Only if Phase 1 & 2 are solid.

---

#### Task 9: "Common Investing Mistakes and How to Avoid Them"
- **Topic**: Behavioral finance pitfalls people actually fall into
- **Tone**: "You're not stupid for making these mistakes. Your brain is wired wrong for investing. Here's how to fight it."
- **What to cover**:
  - Checking your portfolio too often (leads to panic selling)
  - Panic selling in downturns (lock in losses)
  - FOMO investing (buying after gains, during bubbles)
  - Overconfidence after wins (leads to risky bets)
  - Anchoring to entry price (doesn't matter for future decisions)
  - Recency bias (recent returns aren't predictive)
  - Chasing hot funds/managers (doesn't work)
  - Trading too much (fees, taxes, and you're probably wrong)
  - Not diversifying (concentration risk)
  - Trying to time the market (impossible)
  - Conflating net worth with self-worth
  - Comparing yourself to others
  - Having a clear plan (then abandoning it)
- **Key principle to encode**: The biggest enemy is your own brain. Systems and rules beat willpower.
- **Connection**: Comes after all the basics are established
- **Length**: Long (2000-2500 words)

---

#### Task 10: "Marital Finances: Combining Money and Staying Sane"
- **Topic**: Money in relationships, communication, decisions, conflict
- **Tone**: "Money fights don't have to destroy your marriage. Here's how to talk about it."
- **What to cover**:
  - The tension (independence vs. transparency, control vs. partnership)
  - Different money personalities (spender, saver, risk-taker, risk-avoider)
  - Setting shared goals (budget together, invest together)
  - Separate accounts vs. joint accounts (both can work)
  - Communication strategies (monthly "money dates")
  - Handling debt (whose debt is it? How to tackle together)
  - When partners disagree on investments (risk tolerance talk)
  - Allowance/discretionary spending (autonomy within bounds)
  - Life changes (marriage, kids, income changes, job loss)
  - Divorce considerations (financial independence matters)
  - Teaching kids about money
- **Key principle to encode**: Money conversations are relationship conversations. Transparency builds trust.
- **Empathy**: Acknowledge this is hard and emotions are valid
- **Length**: Medium-long (1800-2200 words)
- **Note**: This was outlined but missing—fill it

---

#### Task 11: "Cryptocurrency: Why (Probably) Not, and What You're Missing"
- **Topic**: Brief overview of crypto, philosophy on whether/how to engage
- **Tone**: "Crypto is fascinating, but treating it like an investment is usually a mistake. Here's why, and what it actually is."
- **What to cover**:
  - What is money? (connects to existing "What is Money" article)
  - Cryptocurrency as money, not investment (foundational distinction)
  - Bitcoin, Ethereum, stablecoins, altcoins (what they are)
  - Why the author is skeptical of crypto as an investment (volatility, no cash flow, speculation)
  - How to think about it philosophically (decentralization, censorship resistance, sound money)
  - If you do get involved: wallets, exchanges, security, avoiding fees
  - Crypto as part of portfolio (probably not, or tiny speculation allocation only)
  - Common mistakes (YOLOing into coins, keeping on exchanges, believing hype)
  - Taxes on crypto (complex, track it)
  - The future (fun to think about, but uncertain)
- **Key principle to encode**: Don't invest in things you don't understand. Crypto is novel—understand it first.
- **Caveat**: Acknowledge this is the author's opinion; some people disagree
- **Length**: Medium (1500-1800 words)
- **Note**: Fulfill the outlined crypto section without promoting speculation

---

### PHASE 4: Deferred (Not Required, Nice-to-Have)
These were in the original outline but are lower priority:

- **Technical Analysis and Trading** (article explaining why it doesn't work)
- **How Free Brokerages Make Money** (article on the model)
- **Hedge Funds** (article on what they are, why you can't access them, why you shouldn't want to)
- **Alpha and Beta Parameters** (technical deep-dive for math nerds)
- **Active vs. Passive Management** (already covered implicitly, could expand)
- **Market Sectors** (nice-to-have topic, educational)
- **Policy Section** (Federal Reserve, fractional reserve banking, gold standard—interesting but not essential)

---

## Task Execution Format

When you execute a task, **you should**:

1. ✅ Read the Financial Expertise and Writing Clearly & Concisely skills
2. ✅ Review the author's voice by reading the existing articles (a few examples are listed for each task)
3. ✅ Write in Markdown with proper Hugo front matter (title, date, categories, tags, etc.)
4. ✅ Place the file in `/content/posts/` with kebab-case filename
5. ✅ Link to related articles using Hugo syntax: `[link text](/posts/article-slug/)`
6. ✅ Include any images/diagrams if they help explain the concept
7. ✅ Add a brief disclaimer if making recommendations or discussing areas outside expertise
8. ✅ Test that the file is valid Markdown and Hugo-compatible

When you **finish a task**, provide:
- Link to the article (file path)
- Summary of what was written
- Any notes for follow-up tasks
- Confirmation that skills were applied

---

## Notes on Voice & Integration

### Key Voice Elements to Preserve
1. **Self-aware humility**: "I'm not a tax pro," "I don't know everything about X"
2. **Conversational directness**: "leave it the f*** alone," "that's complete and utter crap"
3. **Empathy for reader confusion**: Start from "this is confusing" not "this is simple"
4. **Evidence over opinion**: "Studies show...," "89.5% of professionals...," "Historical data..."
5. **Reader-centric language**: "You can do this," "don't be scared," "here's hope"
6. **Connection to bigger purpose**: Most articles should tie back to financial independence, freedom, or peace of mind

### Integration & References
- Articles should reference each other extensively
- "See my article on X for more details" format
- Build from foundational to advanced
- Each article assumes reader has read Introduction but maybe not others
- Later articles can assume earlier Phase articles exist

---

## Success Criteria

A completed task has:
- ✅ Clear, jargon-free explanation of the topic
- ✅ Practical guidance (how to actually do the thing)
- ✅ Evidence-based recommendations (Bogleheads, Ramsey, or data)
- ✅ Empathetic tone (acknowledges difficulty, validates emotion)
- ✅ No conflicts of interest or promotional language
- ✅ Proper citations/links to external resources
- ✅ Correct Hugo front matter and markdown
- ✅ Proofread and free of typos
- ✅ Applied writing clarity principles

---

## How to Use This Document

**To execute a task**, say:

> "Execute Task 1: How to Budget: The Zero-Balance Method"

or

> "Execute Tasks 1-4 in parallel" (if multiple agents)

The agent will:
1. Reference this document
2. Review the skill requirements
3. Research the author's voice
4. Write the article
5. Commit and push to your feature branch
6. Report completion

---

## Git & Commit Strategy

- Work on the designated feature branch: `claude/review-content-plan-011CUwMxooc8GW9334CsMJhR`
- Commit per task (one article per commit, or one structural change per commit)
- Commit messages format: "Add article: [title]" or "Reorganize outline and structure"
- Push after each task completion
- No need to push to main until user requests

---

End of Content Plan. Ready to start executing tasks!
