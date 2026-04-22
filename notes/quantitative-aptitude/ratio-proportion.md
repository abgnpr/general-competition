---
title: Ratio & Proportion
parent: Quantitative Aptitude
nav_order: 11
---

# Ratio & Proportion

**Tier 1 · Priority 2.** Feeds Partnership, Ages, Mixtures, Time & Work, Time-Speed-Distance, DI. If Percentages is the master key, Ratio is the master lens — most arithmetic word problems become one-step once you see the ratio.

Status: not started

## The ONE Mental Model

A ratio is a **scaling relationship**, not two numbers. `a : b` means "for every $a$ units of the first, there are $b$ units of the second." The absolute numbers don't matter — only the **multiplier $k$** that turns the ratio into actuals: $a : b \;\Rightarrow\; (ak, bk)$.

Every ratio problem reduces to one question: **find $k$.** Once you have $k$, every quantity falls out by multiplication.

Corollaries:

- Ratios can be scaled freely: $2:3 = 4:6 = 200:300$. Pick whichever form the arithmetic likes.
- A ratio **is a fraction in disguise**: $a:b = a/b$. Everything you know about fractions applies.
- Percentages and ratios are the same object in different dress: $40\% : 60\% = 2 : 3$.

## Ratio ↔ Percentage ↔ Fraction Table (memorize cold)

Same table as in Percentages, read in ratio form. Flip between all three representations in under a second — this is the single highest-ROI skill for arithmetic and DI.

| Ratio | Fraction (smaller/larger) | % of larger | Flip case |
|-------|---------------------------|-------------|-----------|
| 1 : 1 | 1/1 | 100% | equal |
| 1 : 2 | 1/2 | 50% | half |
| 2 : 3 | 2/3 | 66.67% | 3/2 → 150% |
| 3 : 4 | 3/4 | 75% | 4/3 → 133.33% |
| 1 : 4 | 1/4 | 25% | 4× |
| 2 : 5 | 2/5 | 40% | 5/2 → 250% |
| 3 : 5 | 3/5 | 60% | 5/3 → 166.67% |
| 4 : 5 | 4/5 | 80% | 5/4 → 125% |
| 5 : 6 | 5/6 | 83.33% | 6/5 → 120% |
| 5 : 8 | 5/8 | 62.5% | 8/5 → 160% |
| 3 : 8 | 3/8 | 37.5% | 8/3 → 266.67% |
| 7 : 8 | 7/8 | 87.5% | 8/7 → 114.29% |
| 5 : 7 | 5/7 | 71.43% | 7/5 → 140% |
| 4 : 9 | 4/9 | 44.44% | 9/4 → 225% |
| 7 : 9 | 7/9 | 77.78% | 9/7 → 128.57% |
| 5 : 11 | 5/11 | 45.45% | 11/5 → 220% |
| 7 : 12 | 7/12 | 58.33% | 12/7 → 171.43% |

**Usage under exam conditions:**

1. See **ratio 3:5** → think "3/5 = 60%" → 60% of total is the larger share... wait, reverse: smaller is 3/8 of total, larger is 5/8. (See "Share division" below — always split by **total parts**, not by the ratio itself.)
2. See **62.5%** → think `5:8` → answer will be a clean multiple of 8.
3. See **2:3** between A and B → A is 2/3 of B, B is 3/2 of A (i.e. 50% more than A), A is 1/3 less than total.

## The Full Formula Set

Organized by purpose. Core four in **bold** — if pressed for time, these four handle 80% of problems.

### A. Basic ratio

| # | Formula | When |
|---|---------|------|
| **1** | **$a:b:c \Rightarrow$ actuals $= (ak, bk, ck)$ for some $k$** | Every ratio problem — let $k$ be the multiplier |
| 2 | $a:b$ scaled by $m$ → $am : bm$ (ratio unchanged) | Compare ratios with different terms |
| 3 | Ratio in simplest form: divide by $\gcd(a,b,c)$ | Simplify before comparing |
| 4 | $a:b$ as fraction = $a/b$ | Convert to % or decimal for lookup |

### B. Combining ratios

| # | Formula | When |
|---|---------|------|
| **5** | **Linking: $A:B = 2:3$, $B:C = 4:5 \Rightarrow A:B:C = 8:12:15$** | Scale B to common value (LCM of 3 and 4 = 12) |
| 6 | Compound ratio: $(a:b) \times (c:d) = ac:bd$ | Two independent ratios combined multiplicatively |
| 7 | Duplicate ratio of $a:b$ = $a^2:b^2$; triplicate = $a^3:b^3$ | Areas (duplicate), volumes (triplicate) |
| 8 | Sub-duplicate of $a:b$ = $\sqrt{a}:\sqrt{b}$; sub-triplicate = $\sqrt[3]{a}:\sqrt[3]{b}$ | Reverse of above — given areas, find side ratio |

### C. Proportion

| # | Formula | When |
|---|---------|------|
| **9** | **$a:b :: c:d \Leftrightarrow ad = bc$ (cross-multiply)** | Any proportion / "find the missing term" |
| 10 | Mean proportional of $a$ and $b$ = $\sqrt{ab}$ | "$x$ such that $a:x :: x:b$" |
| 11 | Third proportional to $a, b$ = $b^2/a$ | "$x$ such that $a:b :: b:x$" |
| 12 | Fourth proportional to $a, b, c$ = $bc/a$ | "$x$ such that $a:b :: c:x$" |
| 13 | Continued proportion $a:b:c$ → $b^2 = ac$ | Three terms in geometric progression |

### D. Transformations (componendo-dividendo family)

Use these when the question gives a ratio equation and asks for a rearranged ratio. Memorize the two bolded ones — the others follow.

| # | Transformation | Formula |
|---|----------------|---------|
| 14 | Componendo | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a+b}{b} = \dfrac{c+d}{d}$ |
| 15 | Dividendo | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a-b}{b} = \dfrac{c-d}{d}$ |
| **16** | **Componendo-Dividendo** | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a+b}{a-b} = \dfrac{c+d}{c-d}$ |
| 17 | Invertendo | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{b}{a} = \dfrac{d}{c}$ |
| 18 | Alternendo | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a}{c} = \dfrac{b}{d}$ |

### E. Share division (the workhorse)

| # | Formula | When |
|---|---------|------|
| **19** | **Total $T$ split as $a:b:c$ → shares are $\dfrac{a}{a+b+c}T, \dfrac{b}{a+b+c}T, \dfrac{c}{a+b+c}T$** | Every "divide ₹X in ratio..." problem |
| 20 | Difference between two shares $= \dfrac{|a-b|}{a+b+c} T$ | "A got ₹Y more than B" |
| 21 | Given one share $= S_a$, find total: $T = \dfrac{a+b+c}{a} S_a$ | Reverse — given one piece, reconstruct the whole |

### F. Inverse ratio

| # | Formula | When |
|---|---------|------|
| 22 | $a$ inversely proportional to $b$: $a \cdot b = k$ → ratio of $a$'s = reciprocal of ratio of $b$'s | Time ∝ 1/Speed, Time ∝ 1/Workers, Price ∝ 1/Quantity |
| 23 | Time ratio $= 1/\text{Speed ratio}$ (for same distance) | TSD — ratio problems in disguise |
| 24 | Work-days ratio $= 1/\text{efficiency ratio}$ | Time & Work |

## Ratio Arithmetic — the operations that actually appear

- **Add a constant to both terms.** $a:b$ with $+x$ each → $(a+x):(b+x)$. Ratio changes; not additive. Use variables: let actuals be $ak, bk$, set $(ak+x)/(bk+x)$ = new ratio, solve for $k$. Shows up in "Ages" constantly.
- **Multiply both terms by the same factor.** Ratio unchanged. Free scaling.
- **Compare two ratios.** $a:b$ vs $c:d$ → cross-multiply: $ad$ vs $bc$. Bigger product indicates the bigger ratio (when all positive).
- **Scale to a common term** (the linking trick). Make B's value match across two ratios so you can stitch them into a single $A:B:C$.

## High-Yield Shortcuts

1. **"Divide ₹N in ratio $a:b:c$"**: total parts = $a+b+c$. One part $= N/(a+b+c)$. All three shares drop out by multiplication. Never set up equations.
2. **Difference-given trick.** "A got ₹600 more than B, ratio 5:3" → difference is $5-3=2$ parts $= 600$ → one part $= 300$ → A = 1500, B = 900, total = 2400. **Identify which quantity the given number maps to, then solve one part.**
3. **Linking ratios fast.** $A:B = 2:3$, $B:C = 4:5$. B must match → scale first by 4 → $8:12$, scale second by 3 → $12:15$. Result: $8:12:15$. Always rescale on the shared term.
4. **"$a:b :: c:d$ → find $d$"**: $d = bc/a$. Don't set up cross-multiplication longhand.
5. **Squares/cubes of ratios.** If side ratio is $2:3$, area ratio is $4:9$, volume ratio is $8:27$. Mensuration MCQs live on this.
6. **Ratio ↔ % flip is free.** $3:2$ means A is 1.5× B, i.e. A is 50% more than B; B is 1/3 less than A (33.33%). Use Percentages base-change table.
7. **Adding/removing the same amount from numerator and denominator.** Brings the ratio toward $1:1$. (Adding $x$ to both makes the ratio closer to $1$; subtracting pushes it away.) Useful as a sanity check.
8. **Coin problems trick.** "Coins of ₹1, 50p, 25p in ratio $2:3:4$, total ₹X" → convert all to same unit (paise), apply ratio of **values** not counts: value ratio = $2 \times 100 : 3 \times 50 : 4 \times 25 = 200 : 150 : 100 = 4:3:2$.

## MCQ Tactics (exam-only)

- **Assume total = $a+b+c$** or its LCM. If ratio $2:3:5$, set total = 10. If ratios $1/2, 1/3, 1/6$, set total = 6 (LCM of denominators).
- **Assume one part = 1** (or smallest convenient integer). All shares become small integers; scale at the end using the given absolute number.
- **Option elimination by divisibility.** If answer is "one share" and the ratio has total parts 7, the total income must be divisible by 7. Eliminate options that aren't.
- **Ballpark the biggest share.** If ratio is $2:3:7$, the largest is $7/12 \approx 58\%$ of total. Mark only an option near that fraction.
- **Plug options in ages/partnership.** Faster than solving when only 2 unknowns and 4 options.

## Calculation Speed Hacks

- **$k$-method beats algebra.** Let shares be $2k, 3k, 5k$ instead of $x, y, z$ with constraints. One unknown, one equation.
- **Parts-per arithmetic.** "$\text{One part} = \frac{\text{given number}}{\text{parts it represents}}$". Internalize this as a reflex — it solves 40% of ratio problems in one line.
- **Convert ratios to integers early.** $\frac{1}{2} : \frac{1}{3} : \frac{1}{4}$ → multiply by LCM (12) → $6:4:3$. Don't carry fractions.
- **Decimal ratios → integers.** $1.5 : 2.5 : 3 \;\xrightarrow{\times 2}\; 3:5:6$.

## Base Change (the highest-trap sub-topic, again)

Same as in Percentages, restated in ratio form. If $A:B = 5:4$:

- A is $1/4$ more than B (since $A-B = 1$ part and $B = 4$ parts) → +25%.
- B is $1/5$ less than A (since $A-B = 1$ part and $A = 5$ parts) → −20%.

**Base change is just dividing the difference by the appropriate term.** "$A$ is what % more/less than $B$" → denominator is $B$ (or $A$), depending on direction.

| Ratio | "A is ___% more than B" | "B is ___% less than A" |
|-------|-------------------------|-------------------------|
| 5 : 4 | 25% (1/4) | 20% (1/5) |
| 4 : 5 | −20% (B is more) | flip: B is 25% more than A |
| 3 : 2 | 50% (1/2) | 33.33% (1/3) |
| 5 : 3 | 66.67% (2/3) | 40% (2/5) |

## Common Traps (memorize — these are where marks leak)

1. **Dividing by ratio instead of by total parts.** Total ₹600, ratio $2:3$ → A's share = $\frac{2}{2+3} \times 600 = 240$, **not** $600/2 = 300$. Bottom is the **sum of parts**, not the first term.
2. **Ages trap.** "5 years ago the ratio was $3:4$, now $5:6$." Let current ages be $5k, 6k$. Then $(5k-5)/(6k-5) = 3/4$. Don't subtract from the ratio terms themselves.
3. **Coins/notes confusion.** Ratio of **numbers** of coins ≠ ratio of **values**. Convert explicitly.
4. **Linking ratios without rescaling.** $A:B = 2:3$ and $B:C = 2:5$ don't combine to $2:3:5$. Rescale B first.
5. **Adding ratios.** $(2:3) + (4:5)$ is meaningless unless the totals are defined. Always anchor to an absolute quantity.
6. **Treating ratio like %.** Ratio $2:3$ is **not** "2% to 3%". It's the proportion $2/5 : 3/5 = 40\% : 60\%$. Apply Formula 19 first.
7. **Inverse proportion missed.** If 6 workers finish in 10 days, 15 workers take not $10 \times 15/6$ but $10 \times 6/15 = 4$ days (time ∝ 1/workers).
8. **Square/cube forgotten.** If side ratio $= 2:3$, area ratio is $4:9$ (not $2:3$). Mensuration MCQs trap here.
9. **"Divided equally" vs "in ratio".** "Three people share ₹600 equally" → ₹200 each. "In ratio 1:1:1" → same answer, but read carefully if the ratio is non-trivial.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "A:B = 2:3" | $A/B = 2/3$, i.e. A = (2/3)B |
| "A is to B as 2 is to 3" | same as above |
| "A is 2/3 **of** B" | A = (2/3)B — ratio 2:3 ✓ |
| "A is 2/3 **more than** B" | A = (1 + 2/3)B = (5/3)B — ratio 5:3 |
| "Divide 600 **between** A and B in 2:3" | 240 : 360 (total = 5 parts) |
| "Divide 600 **among** A, B, C as 2:3:5" | 120 : 180 : 300 (total = 10 parts) |
| "Ratio of ages 5 years ago was 3:4" | $(a-5):(b-5) = 3:4$, NOT $a:b = 3:4$ then subtract 5 |
| "A and B in ratio 2:3, C joins with ratio 1:2 w.r.t. B" | rescale B before linking |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **Direct share division** | Formula 19. One part $= \text{total}/(\text{sum of parts})$. |
| **Difference-based** | "A got ₹X more than B" → X = (difference in parts) × (one part). Solve for one part. |
| **Ages** | Let current ages be $ak, bk$. Apply the time-shift inside each term. Cross-multiply. |
| **Coins/Notes mix** | Convert denomination ratio to **value** ratio (multiply count ratio by denomination ratio). Then apply share division. |
| **Partnership (Tier-1 follow-on)** | Profit split ∝ (capital × time). Compute each partner's capital·months product, reduce to ratio, split profit by Formula 19. |
| **Mixtures (two liquids)** | Use ratio of quantities. If A:B = 3:2 and total = 20 L, A has 12 L, B has 8 L. Adding/removing → recompute with new amounts. |
| **A's share + B's share relation** | "A + B = X, A:B = p:q" → A = pX/(p+q), B = qX/(p+q). |
| **Change in ratio after transaction** | Let originals be in old ratio ($ak, bk$), modify by the transaction amounts, set equal to new ratio, solve for $k$. |
| **Inverse proportion (work/speed)** | Invert the ratio: if workers 3:5, days 5:3 (same work). |
| **Squares and cubes** | If a ratio of lengths gives area, square it; if it gives volume, cube it. |
| **Componendo-dividendo** | If $(a+b)/(a-b) = p/q$, use Formula 16 in reverse to get $a:b = (p+q):(p-q)$. |

## Links to Other Chapters

Ratio is **upstream** of almost every Tier 1 arithmetic chapter. Mastery compounds.

- **Partnership** — profit ratio $=$ (capital × time) ratio. One direct application of Formula 19.
- **Ages** — current ages in ratio, modified by ±time. Linear equation in $k$.
- **Mixtures & Alligation** — concentrations as ratios; alligation rule is a visual shortcut for weighted-ratio split.
- **Time & Work / Pipes & Cisterns** — work done ∝ efficiency × time. Efficiency ratios make 3-worker problems trivial.
- **Time, Speed & Distance / Trains / Boats** — speed, time, distance in ratio; invert for same-distance or same-time cases.
- **Profit & Loss** — CP:SP ratio, discount ratios, gain% ratios all flip into Ratio.
- **Averages** — weighted average = weighted ratio. Alligation is ratio in disguise.
- **SI/CI** — interest rates given as ratios, amounts in ratio.
- **Data Interpretation** — 60%+ of DI caselets resolve faster via ratio than via percentage. Tables with category splits are ratios.
- **Geometry/Mensuration** — similar figures: length ratio → area (squared) → volume (cubed).

## DI Integration Checklist

- **Pie charts** are ratios by definition (slice : total). Convert once, reuse.
- **Tabular category splits** (e.g., "Product A:B:C = 3:5:7 across 4 cities") → one part per row × the row total = each cell.
- **Percentage growth + base** — convert the percentage to a ratio (e.g., +25% = ×5/4), multiply. Fraction table is the bridge.
- **"Approximately what is the ratio..."** → simplify both sides to 1-digit form, compare; don't divide fully.
- **Comparison of two category splits across years** — line them up as parallel ratios, scale both to a common total, compare cell-by-cell.

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Direct share division | 20 s | 35 s |
| Linking two ratios $A:B$ and $B:C$ | 25 s | 40 s |
| Difference-given, find total | 25 s | 40 s |
| Ages (2 people, 2 time-frames) | 45 s | 75 s |
| Partnership profit split | 45 s | 75 s |
| Mixtures — add/remove one liquid | 60 s | 90 s |
| Componendo-dividendo / algebraic | 45 s | 75 s |
| DI cell via ratio | 20 s | 35 s |

If stuck over red-flag times on share division or linking, the bottleneck is the ratio-to-% table, not the concept.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI PO / IBPS PO**: ratio + partnership + mixtures combos, 2–3 Qs per set. Ages as a standalone Q every paper.
- **IBPS Clerk / SBI Clerk**: direct share division, simple linking, "A's share is ₹X find B's". Speed > depth.
- **RBI Grade B / NABARD / SEBI**: embedded in DI caselets more than standalone. Expect multi-ratio splits across categories.
- **LIC AAO**: pie chart + tabular splits using ratios. Fraction-to-ratio table is decisive.
- **Keyword → attack**:
  - "respectively" → positional ratio, preserve order
  - "between" (two people) / "among" (three+) → share division
  - "in the ratio of" → Formula 19
  - "mean/third/fourth proportional" → Formulas 10/11/12
  - "is to ... as ... is to" → proportion, cross-multiply
  - "if $x$ is added/subtracted from both" → let original = $ak, bk$, apply change, set new ratio, solve
  - "in the same proportion" / "directly proportional" → ratio equal; "inversely proportional" → product equal

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each. Each maps to a recurring pattern.

1. **(SBI PO — share division)** ₹8,400 divided among A, B, C in ratio $3 : 5 : 4$. Find C's share.
   *One part $= 8400/12 = 700$. C $= 4 \times 700 = \text{₹}2800$.*

2. **(IBPS PO — difference given)** A and B share a sum in ratio $7:5$. A gets ₹1,200 more than B. Find total.
   *Difference in parts $= 2 = 1200$ → one part $= 600$. Total $= 12 \times 600 = \text{₹}7200$.*

3. **(IBPS Clerk — linking ratios)** $A:B = 2:3$, $B:C = 4:5$. Find $A:B:C$.
   *LCM of B-terms 3 and 4 is 12. Scale: $A:B = 8:12$, $B:C = 12:15$. Answer: $8:12:15$.*

4. **(RBI Grade B — ages)** Present age ratio of A and B is $5:7$. After 6 years, ratio becomes $3:4$. Find current ages.
   *$(5k+6)/(7k+6) = 3/4$. $4(5k+6) = 3(7k+6)$ → $20k + 24 = 21k + 18$ → $k = 6$. A = 30, B = 42.*

5. **(NABARD — partnership)** A invests ₹12,000 for 8 months, B invests ₹15,000 for 6 months. Profit $= \text{₹}7,200$. Find A's share.
   *Capital·months: A $= 96000$, B $= 90000$. Ratio $96:90 = 16:15$. A's share $= 16/31 \times 7200 \approx \text{₹}3,716.13$. (In banking papers the numbers are almost always chosen so the split is clean — expect variants like 15000/8 vs 12000/6 that give tidy ratios like 5:3.)*

6. **(LIC AAO DI — pie chart)** A pie chart shows expenditure on Food, Rent, Transport, Other in ratio $5:4:2:3$. If total expenditure is ₹28,000, Rent = ?
   *Sum = 14. Rent $= 4/14 \times 28000 = \text{₹}8,000$.*

7. **(SBI PO — base-change disguised)** A's salary is $3/2$ times B's. By what percent is B's less than A's?
   *Ratio $A:B = 3:2$. B is $1/3$ less than A → 33.33%.*

8. **(IBPS Clerk — mixture)** A mixture of 40 L has milk and water in ratio $3:1$. How much water must be added so that the ratio becomes $3:2$?
   *Milk $= 30$, water $= 10$. Milk unchanged. New ratio $3:2$ → water $= 2/3 \times 30 = 20$. Add $20 - 10 = 10$ L.*

9. **(IBPS PO — componendo-dividendo)** If $(a+b)/(a-b) = 5/3$, find $a:b$.
   *By Formula 16 reversed: $a:b = (5+3):(5-3) = 8:2 = 4:1$.*

10. **(SBI PO — coins)** A bag has ₹1, 50p, 25p coins in ratio $2:3:4$ by number. Total value $= \text{₹}44$. Find number of 50p coins.
    *Value ratio $= 2(1) : 3(0.5) : 4(0.25) = 2 : 1.5 : 1 = 4:3:2$. Sum $= 9$ parts $= \text{₹}44$ — doesn't divide evenly, so the question likely uses numbers to give a clean total. Typical exam version: value ratio $4:3:2$, total $\text{₹}45$ → one part $= 5$ → 50p value $= \text{₹}15$ → 30 coins of 50p.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. Convert instantly: $3:5$, $5:8$, $7:12$ → % (of larger and of total).
2. $A:B = 4:7$. A is what % less than B? *($3/7 \approx 42.86\%$)*
3. ₹1,800 split as $5:4:3$. B's share? *(600)*
4. $A:B = 2:3$, $B:C = 5:7$. Find $A:B:C$. *($10:15:21$)*
5. Mean proportional of 9 and 16? *(12)*
6. Fourth proportional to 3, 5, 9? *(15)*
7. If side ratio of two squares is $3:5$, area ratio? *(9:25)*
8. $a:b = 2:3$. $(3a+2b):(2a-b) = ?$ *(plug $a=2, b=3$: $(6+6):(4-3) = 12:1$)*
9. If $x:y = 3:4$, $(x+y)/(x-y) = ?$ *($7/-1 = -7$, or $|7/1| = 7$ if absolute)*
10. 20 L of milk-water $1:1$. Add 5 L water. New ratio? *(milk 10, water 15 → 2:3)*

If you can explain **why** each answer is right without the formula sheet, Ratio & Proportion is done.

## Revision Triggers

- Re-drill the ratio↔%↔fraction table if any conversion takes > 2 seconds.
- If Partnership, Mixtures, or DI feels slow, the bottleneck is almost always here — come back and retime Stage-7.
- If Ages problems stall, you're probably subtracting the time-shift from the ratio terms instead of from $ak, bk$. Re-read Trap 2.
