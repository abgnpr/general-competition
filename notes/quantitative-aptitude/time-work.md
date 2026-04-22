---
title: Time & Work
parent: Quantitative Aptitude
nav_order: 15
---

# Time & Work (+ Pipes & Cisterns)

**Tier 1 · Priority 6.** Ratio + LCM thinking applied. Pipes & Cisterns is the same chapter with signs: inlets are positive workers, outlets are negative workers. Master one, get both free.

Status: not started

## The ONE Mental Model

Work has three variables: **Work done $W$, Rate $r$, Time $t$** — linked by $W = r \times t$. For "together" problems, rates add:

$$r_{\text{together}} = r_A + r_B + r_C + \dots$$

> **The killer move: set total work $W$ = LCM of everyone's individual times. Every worker's rate becomes an integer.** Fractions evaporate. All arithmetic becomes mental.

Everything else is this plus a sign convention (outlets negative), a wage split (by rate ratio), or a schedule twist (alternate days, leaving mid-work).

Corollaries that kill 80% of problems:

- Rate is "work per day"; time is "days to finish alone"; $\text{rate} = W/t$.
- **Efficiency ∝ 1/time** (inverse proportion). If A is twice as efficient as B, A takes half the time.
- Ratio of times = reciprocal of ratio of efficiencies.
- Pipes: inlet rate positive, outlet rate negative. Net rate fills (positive) or drains (negative).

## The LCM Method (the only method worth using)

This single technique replaces every fraction-heavy formula in the textbook.

**Procedure:**

1. Let Work $W$ = LCM of all given times.
2. Compute each worker's rate: $r_i = W / t_i$ (integer).
3. Add/subtract rates as the problem demands.
4. Time to finish = (remaining work) / (combined rate).

**Example.** A does a job in 12 days, B in 15 days. Together?

- $W$ = LCM(12, 15) = 60. $r_A$ = 5/day, $r_B$ = 4/day. Combined = 9/day. Time = 60/9 = 6.67 days.

No fractions, no $\frac{1}{A} + \frac{1}{B}$ manipulation. Just division.

## The Full Formula Set

Core five in **bold**. Everything else is either a corollary or a specific pattern.

### A. Basic

| # | Formula | When |
|---|---------|------|
| **1** | **$W = r \times t$** | Definition |
| **2** | **Rate $r_i = W/t_i$** with $W$ = LCM of times | LCM method — always use this |
| **3** | **Combined rate = sum of rates (signed)** | Inlets +, outlets − |
| 4 | Time together = $W / \sum r_i$ | After computing rates |
| 5 | If A and B together take $T$ days and A alone takes $T_A$, then B alone = $\dfrac{T \cdot T_A}{T_A - T}$ | Shortcut for "B alone" problems |

### B. Efficiency / Ratio

| # | Formula | When |
|---|---------|------|
| **6** | **Efficiency ratio = reciprocal of time ratio** | If A:B time = 3:5, A:B efficiency = 5:3 |
| 7 | If A is $k$% more efficient than B and takes $T_A$ days, B takes $T_A \times (1 + k/100)$ days | Efficiency-difference problems |
| 8 | Two workers, efficiency ratio $a:b$, together finish in $T$ days → alone: $T(a+b)/a$, $T(a+b)/b$ | Given combined + ratio, find individual |

### C. Wages

| # | Formula | When |
|---|---------|------|
| **9** | **Wages split in ratio of rates (efficiencies)** | "₹X paid, split among workers by efficiency" |
| 10 | Equivalently: wages ratio = reciprocal of individual-time ratio | Same thing, different framing |

### D. Pipes & Cisterns

| # | Formula | When |
|---|---------|------|
| 11 | Inlet fills in $t_i$ hrs → rate $+W/t_i$ | Inlet pipe |
| 12 | Outlet empties in $t_o$ hrs → rate $-W/t_o$ | Outlet pipe / leak |
| 13 | Net rate = sum (signed). Time to fill = $W / \text{net rate}$ | Standard pipes problem |
| 14 | Leak reduces filling rate: if inlet alone fills in $t_1$ and with leak in $t_2$, leak empties full tank in $\dfrac{t_1 t_2}{t_2 - t_1}$ | "Leak in the tank" classics |

### E. Schedule variants

| # | Formula | When |
|---|---------|------|
| 15 | Alternate days (A, B, A, B, ...): 2-day cycle work = $r_A + r_B$; find how many full cycles fit, handle leftover | Alternate-day problems |
| 16 | A works for $x$ days then leaves; B finishes: remaining work = $W - x \cdot r_A$, time = remaining/$r_B$ | Leaving mid-work |
| 17 | C joins mid-way: split into two phases, sum work done | Joining mid-work |
| 18 | Half the work by A, then B: total time = $W/(2 r_A) + W/(2 r_B)$ | Sequential work |

### F. Man-Day / MDH equation

| # | Formula | When |
|---|---------|------|
| **19** | **$M_1 D_1 H_1 / W_1 = M_2 D_2 H_2 / W_2$** (men × days × hours ∝ work) | Classic MDH problem |
| 20 | With efficiency $E$: $M_1 D_1 H_1 E_1 / W_1 = M_2 D_2 H_2 E_2 / W_2$ | Men + women with different efficiencies |
| 21 | "If $M$ men do work in $D$ days, $M'$ men do same work in $M D / M'$ days" | Inverse proportion |

## High-Yield Shortcuts

1. **LCM everything.** Even if one number is a multiple of another, still compute LCM — keeps the framework consistent and speeds up the brain.
2. **"A and B together in T, A alone in $T_A$, find B alone"** — Formula 5: $T_B = T T_A / (T_A - T)$. One line.
3. **Pipe net rate** — compute inlet rate minus outlet rate once. Then time = capacity / net.
4. **Wages by rate.** Never by time. If A rate 5, B rate 4, C rate 3, wages split 5:4:3.
5. **Alternate-day shortcut.** 2-day cycle work = $r_A + r_B$. Number of full cycles = ⌊$W / (r_A + r_B)$⌋. Handle the partial last day explicitly.
6. **Efficiency % directly to time.** "A is 25% more efficient than B" → efficiency ratio 5:4 → time ratio 4:5.
7. **Leak formula (Formula 14).** Memorize. Appears 1× per 2 papers.
8. **Inverse proportion reflex.** Workers double → time halves. Work doubles → time doubles. Efficiency doubles → time halves.
9. **"Fraction of work done" conversion.** After 3 days combined rate of 9/day, work done = 27. Fraction = 27/60. Remaining = 33/60. Work in integers, convert to fraction only at the final answer.

## MCQ Tactics (exam-only)

- **Set $W$ = LCM** before reading the options. Every option becomes a simple division.
- **Plug time options.** If asked "A takes how many days?", plug each option back: does $r_A \cdot t_A = W$? Fastest for ugly numbers.
- **Ballpark combined time.** Two workers together finish in less than either alone, more than half the faster. Eliminate options outside this bracket.
- **Ratio cross-check.** If A:B:C efficiency = 3:4:5 and total wage ₹600, the wages are 150, 200, 250 — these must sum to 600. Arithmetic self-check.
- **Sign check for pipes.** If all pipes together take longer to fill than some inlet alone, there must be an outlet. Catch contradictions early.

## Calculation Speed Hacks

- **LCM via prime factors.** 12 = 4·3, 15 = 3·5, 20 = 4·5 → LCM = 60. Never use "trial and error" for LCMs.
- **Sum of rates, not sum of reciprocals.** With LCM method, rates are integers — addition is free.
- **Quick rate flip.** If A takes 20 days and W=60, rate = 3. Don't write "1/20 + 1/30".
- **Per-hour conversion.** "A works 8 hrs/day" → multiply rate by 8 only if hours differ; otherwise keep per-day.
- **Wage division via ratio.** Wages = total × $r_i / \sum r_j$. Skip individual-day computations.

## Efficiency & Ratio Core

This is where Time & Work reduces to pure Ratio.

> **Ratio of times = reciprocal of ratio of efficiencies.**

| Given | Interpretation |
|-------|----------------|
| A takes 12 days, B takes 20 days | Time ratio 12:20 = 3:5; efficiency ratio 5:3 |
| A is twice as efficient as B | Efficiency 2:1; time 1:2; A takes half the time |
| A is 50% more efficient than B | Efficiency 3:2; time 2:3 |
| A is 25% less efficient than B | Efficiency 3:4; time 4:3 |
| A + B finish in 8 days, A alone 12 days | $r_A = W/12$, $r_{A+B} = W/8$ → $r_B = W/8 - W/12 = W/24$ → B alone 24 days |
| 2 men + 3 women = 4 men + 1 woman | $2M + 3W = 4M + W$ → $2W = 2M$ → $M = W$ (1 man = 1 woman) |

## Pipes & Cisterns — same chapter, signs flipped

| Concept | Work | Pipes |
|---------|------|-------|
| Worker (positive rate) | Person doing job | Inlet filling tank |
| Anti-worker (negative rate) | None (unusual) | Outlet / leak |
| Work quantum $W$ | LCM of days | LCM of hours (tank capacity) |
| Combined time | $W / \sum r_i$ | Same |
| "All pipes open" | Sum all rates (signed) | Net fills if positive, drains if negative |

**The only new trap:** if a "full tank with outlets open" scenario is given, check the sign of the net rate. If net < 0, the tank drains; an "inlet-only" full-tank answer is wrong.

## Common Traps (memorize — these are where marks leak)

1. **Efficiency vs time confusion.** "A is twice as efficient" means A takes *half* the time, not double.
2. **Wages split by time, not efficiency.** Wages split by **rate** (= efficiency). If A takes 10 days and B 15 days, A gets more (not less) — he worked faster.
3. **Forgetting outlet in pipes.** If problem mentions a leak or drain anywhere, it has to be in the net-rate sum.
4. **Alternate-day residue.** After $n$ full cycles of 2 days, $r_A + r_B$ of work per cycle. Leftover work done by whoever starts next — handle separately.
5. **"Half the work each"** vs "working together" — very different. Sequential vs parallel.
6. **Leaving mid-work.** Work done before leaving = (days worked) × (rate). Remaining = $W$ − (that). Don't forget the "remaining" step.
7. **MDH proportionality direction.** More men → fewer days (inverse). More work → more days (direct). Check both before setting up Formula 19.
8. **"A can do in $x$ days, B in $y$, C in $z$ — together?"** Compute rates first, sum, divide. Don't use $\frac{xyz}{xy + yz + zx}$ formula — LCM is faster and less error-prone.
9. **Fraction of work + time remaining.** "After 4 days, 1/3 of work remains" → work done = 2/3 in 4 days → full work in 6 days. Easy to invert.
10. **Men ↔ women equivalence.** Don't add unless told. "3 men + 2 women" must be resolved via given equations before LCM-ing.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "A is twice as efficient as B" | Eff 2:1; time 1:2 (A takes half) |
| "A takes twice as long as B" | Time 2:1; eff 1:2 (A is half efficient) |
| "A is 20% more efficient" | Eff 6:5; time 5:6 |
| "A takes 20% less time" | Time 4:5; eff 5:4 |
| "Finish work in 12 days" (together) | Combined rate × 12 = $W$ |
| "Each finishes in 12 days" | Rates are equal; two workers |
| "Half work done by A, rest by B" | Sequential: $W/(2 r_A) + W/(2 r_B)$ |
| "A and B together for half the work" | Same as above but parallel: $W/[2(r_A + r_B)]$ |
| "Inlet fills in 6 hrs, outlet empties in 4 hrs" | Net rate negative → tank drains if starting full |
| "2 pipes fill in 6 and 4 hrs" | Both inlets; combined rate > either |
| "With leak, inlet takes 8 hrs instead of 6" | Leak empties full tank in $6 \cdot 8 / (8-6) = 24$ hrs |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **A alone $x$, B alone $y$, together?** | LCM method. Sum rates, divide $W$. |
| **A+B together, A alone, find B** | Formula 5 or subtract rates. |
| **Efficiency-ratio given** | Set efficiencies as integers; $W$ = product or LCM; compute rates. |
| **Wages split** | Ratio of efficiencies. Formula 9. |
| **Alternate days (A, B, A, B, ...)** | 2-day cycle → how many cycles fit → leftover. |
| **Leaving mid-work** | Compute work done before leaving; rest at new rate. |
| **Joining mid-work** | Split into phases; sum work. |
| **Pipes inlet + outlet** | Signed rates. Formula 13. |
| **Leak problem** | Formula 14: time for leak to empty = $t_1 t_2 / (t_2 - t_1)$. |
| **MDH (men × days × hours)** | Formula 19. Set up ratio. |
| **Men vs women efficiency** | Resolve $aM + bW = cM + dW$ first → get M:W ratio → then LCM. |
| **"Fraction of work left"** | Convert to integer work units; subtract. |
| **A, B, C together; C leaves last 2 days; total time?** | Two phases: (A+B+C) for unknown days + (A+B) for 2 days. Set sum = $W$. |

## Links to Other Chapters

- **Ratio & Proportion** — efficiency ratios are inverse time ratios. Wage splits use Ratio Formula 19.
- **LCM/HCF number theory** — the LCM method is the main tool; revisit if LCM calculation is slow.
- **Time, Speed & Distance** — same inverse-proportion shape (speed ↔ efficiency). Many TSD problems are T&W in disguise.
- **Percentages** — efficiency change (%) translates to time change (%) via Formula 7 and base-change flips.
- **Averages** — when multiple workers' rates are mixed, "average rate" is the weighted mean by days worked.
- **Partnership** (indirectly) — work × time compounds like capital × time in partnership.
- **DI** — "man-days to complete project X" tables appear in RBI/NABARD DI occasionally.

## DI Integration Checklist

- **"Work rate per person"** in a table → convert to daily rate; combined rate = sum across rows selected.
- **Crew schedules** (who works when) → treat as leaving/joining; track work phase-by-phase.
- **Productivity % comparisons** → efficiency ratios; convert to time ratios.
- **"Project completion by date"** → MDH with extra variables (shift length, holidays).

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Two workers together | 25 s | 40 s |
| Three workers together | 30 s | 50 s |
| Find third worker's alone time | 30 s | 50 s |
| Wages split | 30 s | 50 s |
| Alternate days | 45 s | 75 s |
| Leaving / joining mid-work | 60 s | 90 s |
| Pipes + outlet (2–3 pipes) | 35 s | 60 s |
| Leak formula | 30 s | 50 s |
| MDH (men, days, hours) | 45 s | 75 s |
| Efficiency % → time % | 25 s | 40 s |

If two-worker combined time takes more than 25 s, the bottleneck is LCM computation — drill LCM pairs up to 30.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI / IBPS PO**: 1 direct T&W + 1 pipes per paper. Alternate-day and leaving-mid-work appear ~50% of papers.
- **IBPS Clerk / SBI Clerk**: direct "together" problems. Speed > depth.
- **RBI Grade B / NABARD / SEBI**: efficiency-based + MDH with mixed workforce. Embedded in reasoning-style caselets.
- **LIC AAO**: data-driven — tables of productivity per person, compute combined output.
- **Keyword → attack**:
  - "in how many days" → time
  - "rate of work" / "per day" → rate
  - "together" / "simultaneously" → sum of rates
  - "alternately" / "on alternate days" → cycle work (Formula 15)
  - "leaves after $x$ days" → leaving mid-work
  - "joins after $x$ days" → joining mid-work
  - "leak" / "hole" → Formula 14 flavor
  - "wages" / "paid" → ratio of efficiencies
  - "twice as efficient" / "half as fast" → efficiency ratio — flip for time
  - "$k$% more / less efficient" → efficiency ratio with multiplier
  - "emptied" / "drained" — negative rate in pipes

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each.

1. **(IBPS PO — together)** A does a job in 12 days, B in 18 days. Together?
   *$W$ = 36. $r_A = 3, r_B = 2$, total = 5. Time = 36/5 = 7.2 days.*

2. **(SBI PO — find C)** A, B, C can do work in 20, 30, X days. Together in 10 days. Find X.
   *$W$ = 60. $r_A = 3, r_B = 2$, together rate = 6 → $r_C = 1$ → C alone 60 days.*

3. **(IBPS Clerk — wages)** A does in 10 days, B in 15 days. Work completed together; total wage ₹500. A's share?
   *$W$ = 30, $r_A = 3, r_B = 2$, ratio 3:2. A = 300, B = 200.*

4. **(RBI Grade B — efficiency)** A is 25% more efficient than B. Together they finish in 10 days. A alone?
   *Efficiency 5:4. $r_A + r_B = 9 \text{ parts/day}$. Time together 10 → $W = 90$ parts. A alone = $90/5 = 18$ days.*

5. **(NABARD — alternate days)** A does work in 12 days, B in 15 days. They work alternately starting with A. Time to finish?
   *$W$ = 60. $r_A = 5, r_B = 4$. 2-day cycle: 9. After 6 cycles (12 days): 54. Remaining: 6. Day 13: A does 5. Remaining 1. Day 14: B does 1 (takes 1/4 day). Total = 13.25 days.*

6. **(LIC AAO — pipes)** Pipe A fills tank in 6 hrs, B in 8 hrs, C empties in 12 hrs. All open — time to fill empty tank?
   *$W$ = 24. $r_A = 4, r_B = 3, r_C = -2$. Net = 5. Time = 24/5 = 4.8 hrs.*

7. **(SBI PO — leak)** An inlet fills a tank in 6 hrs. Due to a leak, it takes 8 hrs. Time for leak alone to empty full tank?
   *Formula 14: $6 \times 8 / (8 - 6) = 24$ hrs.*

8. **(IBPS PO — leaving)** A and B together finish in 10 days. A leaves after 6 days; B finishes the rest in 12 more days. A alone?
   *Together 6 days = 6/10 = 3/5 of work. Remaining 2/5 by B alone in 12 days → B alone in 30 days. From combined: $1/10 = 1/A + 1/30$ → $1/A = 1/15$ → A alone 15 days.*

9. **(IBPS Clerk — MDH)** 10 men can finish in 15 days working 8 hrs/day. 12 men, 6 hrs/day, how many days?
   *MDH: $10 \times 15 \times 8 = 12 \times D \times 6$ → $D = 1200 / 72 = 16.67$ days.*

10. **(SBI PO — men vs women)** 2 men and 3 women finish in 8 days. 4 men and 1 woman finish in 6 days. 1 man in?
    *Rates: $2M + 3W = 1/8$; $4M + W = 1/6$. Multiply first by 2: $4M + 6W = 1/4$. Subtract: $5W = 1/4 - 1/6 = 1/12$ → $W = 1/60$. Then $4M = 1/6 - 1/60 = 9/60$ → $M = 9/240 = 3/80$. So 1 man alone in 80/3 ≈ 26.67 days.*

11. **(RBI Grade B — joining)** A does work in 20 days, B in 30 days. A works alone for 5 days, then B joins. Time from start?
    *$W$ = 60. $r_A = 3, r_B = 2$. After 5 days alone: $15$ done, $45$ left. Combined rate 5/day. Time = $45/5 = 9$ more days. Total = 14 days.*

12. **(LIC AAO — three workers)** A, B, C alone in 24, 36, 48 days. Working together, how long?
    *$W$ = LCM(24, 36, 48) = 144. $r_A = 6, r_B = 4, r_C = 3$, sum = 13. Time = 144/13 ≈ 11.08 days.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. A in 10 days, B in 15. Together? *(LCM 30; rates 3 + 2 = 5; 30/5 = 6 days)*
2. A is 50% more efficient than B. B takes 18 days. A? *(eff 3:2, time 2:3, $A = 12$ days)*
3. A + B in 6 days, A in 10 alone. B alone? *(Formula 5: $10 \times 6 / 4 = 15$ days)*
4. Wages ₹720 split between A (15 days) and B (12 days) for work done together. *(rate ratio 4:5 → $720 \times 4/9 = 320$, $720 \times 5/9 = 400$)*
5. Inlet A = 10 min, B = 15 min, outlet C = 20 min. All open, fill time? *(LCM 60; rates +6, +4, −3 = 7; $60/7 \approx 8.57$ min)*
6. Leak empties tank in 30 hrs. Inlet alone fills in 10 hrs. With leak? *(rates: inlet +3, leak −1 (per LCM 30); net 2; time = 15 hrs)*
7. 15 men finish in 20 days. 12 men in? *(inverse: $15 \times 20 / 12 = 25$ days)*
8. A does half in 10 days, B finishes remaining half in 15 days. Total work time? *(10 + 15 = 25 days)*
9. A and B alternate; A starts. A in 12 days, B in 24 days. Work finished on which day? *(LCM 24; rates 2, 1; 2-day cycle = 3; 7 cycles = 14 days = 21 work; day 15: A does 2, total 23; day 16: B does 1, total 24. Finishes on day 16 but B works only half day → 15.5 days.)*
10. 3 men = 5 women in efficiency. 6 men + 5 women finish in 10 days. 1 woman alone? *(3M = 5W → M = 5W/3. $6M + 5W = 10W + 5W = 15W$. Total work = 150 W-days. 1 W in 150 days.)*

If you can explain **why** each answer is right without the formula sheet, Time & Work is done.

## Revision Triggers

- If LCM computation takes more than 5 seconds for 2–3 numbers, drill LCM pairs up to 30.
- If the wages split direction confuses (time vs efficiency), re-state: **wages pay the faster worker more**.
- If pipes with outlet trips you up, write "+" on inlets and "−" on outlets literally on the question paper for the first 10 problems.
- If alternate-day problems eat time, drill cycle-based work: 2-day work, leftover, last-day partial.
- If efficiency % ↔ time % conversions slow you down, the bottleneck is in Percentages base-change — revisit that chapter first.
