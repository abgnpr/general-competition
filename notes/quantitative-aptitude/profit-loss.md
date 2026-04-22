---
title: Profit & Loss
parent: Quantitative Aptitude
nav_order: 13
---

# Profit & Loss

**Tier 1 · Priority 4.** Pure application of Percentages. If Percentages is solid, P&L is a one-week chapter; if it isn't, no amount of P&L drill helps. Do AFTER Percentages.

Status: not started

## The ONE Mental Model

P&L has only **four variables**: CP (cost price), SP (selling price), MP (marked price / list price), D (discount). Everything is a multiplicative relationship between them:

$$\text{SP} = \text{CP} \times (1 + \text{profit}\%) = \text{MP} \times (1 - \text{discount}\%)$$

> **Convert every % into a multiplier, chain them, done.** Don't add percentages. Don't subtract discount from profit. The whole chapter collapses to: start with CP, multiply by markup to get MP, multiply by $(1 - d)$ to get SP, compare SP to CP for profit/loss.

Corollaries that eliminate most traps:

- **Profit % is always on CP.** Discount % is always on MP. Never mix bases.
- **SP / CP** is the profit multiplier; **SP / MP** is the "after-discount" multiplier.
- If the item is sold, SP is the common meeting point of the two chains (CP→SP via profit, MP→SP via discount).

## The Central Diagram

```
CP ──×(1 + p)──▶ SP ◀──×(1 − d)── MP
```

Every P&L question gives you 2 of {CP, SP, MP, p%, d%} and asks for a third. Pick the right edge of the diagram:

- CP and p% known → SP = CP × (1+p).
- MP and d% known → SP = MP × (1−d).
- CP and MP known, find markup % → markup is on CP: $(\text{MP} - \text{CP})/\text{CP}$.
- Both sides known → solve for the missing %.

## The Full Formula Set

Core five in **bold**. Rest are one-line tools.

### A. Basic definitions

| # | Formula | When |
|---|---------|------|
| **1** | **Profit = SP − CP; Loss = CP − SP** | Sign tells you which |
| **2** | **Profit% = (SP − CP)/CP × 100** (base is CP) | Any profit/loss % |
| **3** | **SP = CP × (1 + p/100)** for profit; **× (1 − l/100)** for loss | The profit multiplier |
| 4 | CP = SP / (1 + p/100) | Reverse — find CP from SP and profit% |
| 5 | CP = SP / (1 − l/100) | Reverse — loss version |

### B. Markup & Discount

| # | Formula | When |
|---|---------|------|
| **6** | **SP = MP × (1 − d/100)** (base is MP) | After a discount |
| 7 | MP = CP × (1 + markup/100) | Markup is on CP, just like profit |
| 8 | Discount = MP − SP; Discount% = (MP − SP)/MP × 100 | Any discount question |
| 9 | MP = SP / (1 − d/100) | Reverse — find MP from SP and discount |

### C. The master chain

| # | Formula | When |
|---|---------|------|
| **10** | **SP = CP × (1 + m) × (1 − d)** where $m$ = markup%, $d$ = discount% | Most P&L MCQs collapse to this line |
| 11 | No-discount case: SP = MP, so profit% = markup% | Store does not discount |
| 12 | Break-even: SP = CP → $(1 + m)(1 − d) = 1$ → $d = m/(1 + m)$ | "At what discount does the seller break even?" |

### D. Successive changes (same form as Percentages Formula 9)

| # | Formula | When |
|---|---------|------|
| **13** | **Two successive discounts $d_1, d_2$: net = $d_1 + d_2 − (d_1 d_2)/100$** | Shops that stack discounts |
| 14 | Equivalent single discount of $d_1, d_2$: $1 − (1 − d_1)(1 − d_2)$ | Multi-discount, fastest via multiplier |
| 15 | Profit on profit / markup on markup: chain multipliers | Multi-stage resale |

### E. Per-unit / quantity problems

| # | Formula | When |
|---|---------|------|
| 16 | Profit on $n$ items at SP $s$: profit = $n(s − c)$ where $c$ = CP each | Bulk arithmetic |
| 17 | "$x$ articles bought for ₹$y$, sold at ₹$z$ per article" → profit% = $(z − y/x)/(y/x) \times 100$ | Classic phrasing |
| 18 | "CP of $a$ articles = SP of $b$ articles" → profit% = $\dfrac{a − b}{b} \times 100$ (profit if $a > b$) | Memorize — frequent PYQ |

### F. Dishonest dealer / faulty weight

| # | Formula | When |
|---|---------|------|
| **19** | **Sells at CP but uses false weight $w'$ instead of true $w$: gain% = $\dfrac{w − w'}{w'} \times 100$** | Dishonest dealer, no discount |
| 20 | False weight + markup: gain% = $\dfrac{\text{true weight}}{\text{false weight}} \times (1 + \text{markup}) − 1$, then $\times 100$ | Combined dishonesty |
| 21 | Sells $n$ items, passes off $k$ free: effective CP per sold = $\text{CP} \times n/(n − k)$; gain% follows | "Buy 3 get 1 free" from seller's side |

### G. Multi-article MCQ staples

| # | Formula | When |
|---|---------|------|
| 22 | Sells two items at same SP, one at $+x\%$ and the other at $−x\%$: **net loss = $x^2/100$ %** (always a loss) | Classic trap — always loss, never profit |
| 23 | Overall gain/loss when different items have different profit% — use weighted average by CP | Multi-item shop |
| 24 | "Gain = SP of $k$ items" → in $n$ items sold, CP of $n$ = SP of $(n − k)$ | Phrasing variant of Formula 18 |

## High-Yield Shortcuts

1. **Multiplier chain, never addition.** SP = CP × 1.2 × 0.9 (20% markup, 10% discount) = CP × 1.08 → 8% profit. Computing "20 − 10 + something" loses marks.
2. **Equal ±x% trap (Formula 22).** Same SP, one at +x% and one at −x% → always loss = $x^2/100$%. Memorize. Appears every other banking paper.
3. **CP of $a$ = SP of $b$ (Formula 18).** Profit% = $(a - b)/b \times 100$. Instant.
4. **Reverse-multiplier for "find CP".** After +25% profit, SP is ₹250 → CP = 250 / 1.25 = 250 × 4/5 = 200. Use fraction table, never decimals.
5. **Discount on MP only.** "20% discount on MP ₹500, CP is ₹320, profit%?" → SP = 500 × 0.8 = 400. Profit = 80. Profit% = 80/320 = 25%.
6. **Markup-then-discount.** Markup 40%, discount 25% → multiplier 1.4 × 0.75 = 1.05 → 5% profit. Don't write 40 − 25.
7. **Dishonest dealer reflex (Formula 19).** True weight 1000 g, uses 900 g, sells at CP → gain = 100/900 = 11.11%. One line.
8. **Break-even discount (Formula 12).** Markup 25% → break-even discount = 25/125 = 20%. (Offer > 20% → loss.)

## MCQ Tactics (exam-only)

- **Assume CP = 100.** When only percentages are given, let CP = 100. Every number becomes an absolute; arithmetic is trivial.
- **Assume CP = LCM of denominators.** If markup is 1/4 and discount is 1/5, set CP = 20 (LCM of 4 and 5) to keep everything integer.
- **Back-solve from SP.** Four options for CP → plug each, check if (SP − option)/option gives the stated profit%.
- **Ballpark via multiplier.** Profit% + discount% roughly cancel for small numbers. If answer options differ wildly, this picks the right bucket.
- **Divisibility check.** If profit% is $16\tfrac{2}{3}\%$ (= 1/6), the profit amount must be divisible by CP/6. Eliminate mismatched options.
- **Sign sanity.** Markup > discount → profit; markup < discount → loss; equal → break-even-ish (but see equal-±x trap).

## Calculation Speed Hacks

- **All profits/discounts as fractions.** 25% → ×5/4, 20% → ×4/5, 37.5% → ×11/8 (markup) or ×5/8 (discount), 12.5% → ×9/8 or ×7/8. Never compute with decimals.
- **Cross-cancel the chain.** CP × 5/4 × 4/5 → cancels to CP. Spot these in successive markup-discount combos.
- **"Same SP" trick.** Two items sold at same SP, gains/losses $x\%$ and $y\%$ → overall = $\dfrac{2xy}{x+y}\%$ if same-sign; for opposite sign, use Formula 22. (Harmonic flavor.)
- **Fractional articles.** "20 apples for ₹100, sold 15 for ₹100" → CP = 5/apple, SP = 20/3/apple ≈ 6.67 → profit% = 33.33%. Convert to per-unit immediately.
- **Discount on discount.** Two discounts 10%, 20% → effective = 1 − 0.9 × 0.8 = 1 − 0.72 = 28%. Not 30%.

## Base-Confusion (the highest-trap sub-topic)

P&L traps almost all reduce to "which base did you use?"

| Quantity | Base | Formula |
|----------|------|---------|
| Profit % | **CP** | (SP − CP)/CP × 100 |
| Loss % | **CP** | (CP − SP)/CP × 100 |
| Markup % | **CP** | (MP − CP)/CP × 100 |
| Discount % | **MP** | (MP − SP)/MP × 100 |
| "% above CP" | CP | same as markup |
| "% below MP" | MP | same as discount |
| "% off" | MP (almost always) | same as discount |

> Rule of thumb: profit/markup look **up** from CP; discount looks **down** from MP. Keep the diagram in your head.

## Common Traps (memorize — these are where marks leak)

1. **Wrong base.** Discount ON MP, profit ON CP. "Discount of 20% gives profit of 20%" is *not* a contradiction — bases differ.
2. **Adding profit% and discount%.** Markup 30%, discount 20% → **not** +10%. It's 1.3 × 0.8 = 1.04 → 4%.
3. **Equal ±x% trap (Formula 22).** Same SP, one gain one loss of x% → net loss, not no-change.
4. **"Marked up by x, gives y profit"** — confusion between markup% and profit%. Markup is before discount; profit is after. They're equal only if no discount.
5. **"Profit is 20% of SP" vs "of CP".** Always default to CP unless the question *explicitly* says "on SP".
6. **Successive discount direction.** 10% then 20% = 20% then 10% (multiplication commutes). But "first discount 10% + additional 20% on the discounted price" is the same as 10% then 20% — not 30%.
7. **"Selling at CP"** with false weight → Formula 19. Gain is on the *reduced* weight, not the full.
8. **Articles-bought vs articles-sold.** "Buys 12 at ₹10, sells 10 at ₹12" — CP per article = 10/12, SP per article = 12/10. Do per-unit first.
9. **"Overhead charges" / "transportation".** Add to CP before computing profit. $CP_{\text{effective}} = \text{CP} + \text{overheads}$.
10. **Profit per unit vs total profit.** Read carefully — the question may ask total or per-unit.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "Marked up by 40%" | MP = 1.4 × CP |
| "Sold at 40% profit" | SP = 1.4 × CP (no discount mentioned) |
| "Discount of 40%" | SP = 0.6 × MP |
| "40% off" | same as above |
| "Profit of 20% on CP" | standard profit, SP = 1.2 CP |
| "Profit of 20% on SP" | profit = 0.2 SP → CP = 0.8 SP → profit% on CP = 25% |
| "Marked 40% above CP, 20% discount" | SP = CP × 1.4 × 0.8 = 1.12 CP → 12% profit |
| "20% discount on marked price, still 12% profit" | back-solve markup: 1.12 = (1+m) × 0.8 → m = 0.4 → 40% markup |
| "Sells two articles at ₹X each, one at +20%, one at −20%" | same SP → Formula 22, net loss = 4% |
| "Sells two articles, gains 20% on one and loses 20% on other (CPs given)" | weighted by CP, not same SP — different answer |
| "Gain is 20% of selling price" | profit/SP = 0.2 → SP = 1.25 CP → profit% on CP = 25% |
| "CP of 10 = SP of 8" | Formula 18: profit% = (10−8)/8 × 100 = 25% |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **Direct profit/loss** | Formulas 1–3. CP = 100 assumption often makes it trivial. |
| **Markup + single discount** | Formula 10: SP = CP × (1+m) × (1−d). One-line. |
| **Successive discounts** | Formula 13 or multiply $(1−d_1)(1−d_2)$. |
| **Equivalent single discount** | Formula 14: $1 − \prod (1 − d_i)$. |
| **"Find CP given SP and profit%"** | Formula 4: CP = SP / (1+p). |
| **"CP of $a$ = SP of $b$"** | Formula 18: profit% = $(a−b)/b × 100$. |
| **Two items at same SP, ±x%** | Formula 22: net loss = $x^2/100$%. |
| **Two items with different CPs and profits** | Weighted profit = (Σ profits)/(Σ CPs) × 100. |
| **Dishonest dealer, sells at CP** | Formula 19. Gain = (true−false)/false × 100. |
| **Dishonest dealer with markup** | Formula 20. Chain both effects multiplicatively. |
| **Buy-X-get-Y-free (seller side)** | Effective CP per sold = CP × N/(N−free). Then compute profit%. |
| **Break-even discount** | Formula 12: $d = m/(1+m)$. |
| **"Profit is 25% of SP"** | Profit/SP = 0.25 → CP = 0.75 SP → profit% on CP = 1/3. |
| **"Overheads added"** | Adjust CP upward first, then apply standard formulas. |

## Links to Other Chapters

- **Percentages** — P&L IS applied percentages. Every trap here has a twin in Percentages.
- **Ratio & Proportion** — CP:SP ratios, partner profit splits (via Ratio Formula 19).
- **SI/CI** — similar multiplicative structure. Compound interest ≈ successive profit.
- **Averages** — overall profit% in a multi-item shop is a weighted average by CP.
- **Mixtures & Alligation** — dishonest dealer / dilution problems are P&L + mixture hybrids.
- **Partnership** — profit distribution ∝ (capital × time); the *profit* itself comes from P&L.
- **DI** — tabular "revenue / cost / margin" questions are P&L on top of a table. Common in RBI/NABARD DI.

## DI Integration Checklist

- **"Profit" and "revenue"** are not the same. Profit = Revenue − Cost. If table gives revenue and cost, subtract first.
- **Margin % vs Markup %** — margin is on SP, markup is on CP. Banking DI sometimes uses "margin".
- **"Profit as a % of …"** — always check the base. If unstated, assume CP; if stated as revenue/SP, use it.
- **YoY profit growth** — compute each year's profit absolute, then % change — do **not** average % margins across years.
- **Multi-product tables** — weighted overall profit% is by CP (or revenue, if that's the stated base).

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Direct SP/CP/profit% with CP = 100 | 20 s | 35 s |
| Markup + discount (1 step) | 25 s | 40 s |
| Successive discounts | 30 s | 50 s |
| "CP of $a$ = SP of $b$" | 20 s | 35 s |
| Same-SP ±x% trap | 15 s | 30 s |
| Dishonest dealer | 30 s | 50 s |
| Two-item weighted profit | 45 s | 75 s |
| Break-even / reverse-discount | 45 s | 75 s |
| DI cell with profit% | 30 s | 50 s |

If successive-discount or markup+discount slows you down, the bottleneck is fraction-table recall from Percentages — not P&L.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI/IBPS PO**: 2–3 P&L Qs per paper. Markup + discount combos, dishonest dealer once every 2 papers, same-SP ±x% trap recurring.
- **IBPS Clerk / SBI Clerk**: direct profit% given CP/SP, simple discount. Speed > depth.
- **RBI Grade B / NABARD**: embedded in DI (cost vs revenue tables) + occasional standalone with multi-step markup/discount.
- **LIC AAO**: data-heavy P&L — tables with cost, SP, quantity, compute overall margin.
- **Keyword → attack**:
  - "marked price" → MP; discount applied to this
  - "listed price" → same as MP
  - "cost price" → CP; profit applied to this
  - "at a profit of x%" / "at a loss of x%" → multiplier on CP
  - "x% discount" / "x% off" → multiplier on MP
  - "marked x% above CP" → markup (CP base)
  - "sold at CP" → SP = CP (dishonest dealer setup likely)
  - "gain is x% of SP" → non-standard base, convert carefully
  - "two successive discounts" → multiplier chain
  - "equivalent single discount" → Formula 14
  - "break even" / "neither profit nor loss" → SP = CP

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each.

1. **(IBPS PO — markup + discount)** An article marked up 40% above CP is sold at 25% discount. Profit/loss%?
   *Multiplier = 1.4 × 0.75 = 1.05 → 5% profit.*

2. **(SBI PO — successive discount)** Two successive discounts of 20% and 10% on an article marked at ₹500. SP?
   *SP = 500 × 0.8 × 0.9 = 360.*

3. **(IBPS Clerk — direct)** An article is bought at ₹400 and sold at ₹480. Profit%?
   *(80/400) × 100 = 20%.*

4. **(RBI Grade B — CP of a = SP of b)** CP of 12 articles = SP of 10 articles. Profit%?
   *Formula 18: $(12-10)/10 \times 100 = 20\%$.*

5. **(NABARD — dishonest dealer)** A shopkeeper sells rice at CP but uses 900 g weight instead of 1 kg. Profit%?
   *Formula 19: $(1000-900)/900 \times 100 = 11.11\%$ ($= 1/9$).*

6. **(LIC AAO — equal ±x%)** A man sells two articles at ₹1,200 each. On one he gains 20%, on the other he loses 20%. Overall profit/loss%?
   *Formula 22: net loss = $20^2/100 = 4\%$. Absolute loss = 2 × 1200 × 4/96 ≈ ₹100. (Or compute: CPs = 1000 and 1500, total CP = 2500, total SP = 2400 → loss ₹100 = 4%.)*

7. **(SBI PO — reverse)** An article sold at ₹1,260 at 20% discount on MP. MP?
   *Formula 9: MP = 1260 / 0.8 = ₹1,575.*

8. **(IBPS PO — break-even)** Markup is 25%. What maximum discount can be given without loss?
   *Formula 12: $d = 25/125 = 20\%$.*

9. **(IBPS Clerk — base confusion)** Profit is 20% of SP. Find profit% on CP.
   *Profit/SP = 0.2 → CP = 0.8 SP → profit% on CP = 0.2/0.8 = 25%.*

10. **(SBI PO — multi-article weighted)** A shopkeeper buys 3 articles at ₹200, 300, 500 and sells at profits of 10%, 20%, 30% respectively. Overall profit%?
    *Profits: 20, 60, 150 → total 230. Total CP = 1000. Profit% = 23%.*

11. **(RBI Grade B — successive single-equivalent)** Equivalent single discount of 20%, 10%, 5%?
    *$1 - 0.8 \times 0.9 \times 0.95 = 1 - 0.684 = 0.316 → 31.6\%$.*

12. **(IBPS PO — overhead)** CP = ₹800, overhead = ₹100, sold for ₹1,080. Profit%?
    *Effective CP = 900. Profit = 180. Profit% = 20%.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. Markup 50%, discount 20%. Profit%? *(1.5 × 0.8 = 1.2 → 20%)*
2. Same SP, +25% and −25%. Overall? *(loss of $25^2/100 = 6.25\%$)*
3. CP of 20 = SP of 16. Profit%? *($(20-16)/16 \times 100 = 25\%$)*
4. Dishonest dealer uses 800 g for 1 kg, sells at CP. Gain%? *($200/800 = 25\%$)*
5. Successive discounts 10%, 20%. Equivalent single? *($1 - 0.9 \times 0.8 = 28\%$)*
6. SP = ₹480 at 20% loss. CP? *($480/0.8 = 600$)*
7. Markup x%, break-even discount 20%. Find x. *($x/(100+x) = 0.2$ → $x = 25$)*
8. Profit is 1/4 of CP. Profit%? *(25%)*
9. Profit is 1/4 of SP. Profit% on CP? *(1/3 → 33.33%)*
10. Gain% = Loss% = 10% on two items sold at ₹990 each. Net? *(loss = $10^2/100 = 1\%$; in absolute: CPs 900 and 1100, total 2000, total SP 1980 → loss ₹20 = 1%)*

If you can explain **why** each answer is right without the formula sheet, P&L is done.

## Revision Triggers

- If "markup + discount" takes more than 25 seconds, the bottleneck is fraction-to-multiplier recall. Drill Percentages fraction table.
- If Formula 22 (same-SP ±x%) feels mysterious, derive once from CP = 100 and check with $x = 20$ → always a loss of 4%.
- If dishonest-dealer problems stall, write Formula 19 three times by hand — it's counter-intuitive because the base is the *false* weight.
- Whenever SI/CI or Partnership drills feel slow, check if the blocker is actually P&L multipliers — they share the same mental machinery.
