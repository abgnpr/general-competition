---
title: Averages
parent: Quantitative Aptitude
nav_order: 12
---

# Averages

**Tier 1 · Priority 3.** Feeds Ages, Mixtures, Alligation, DI, cricket-style replacement problems. The third load-bearing arithmetic chapter after Percentages and Ratios. Small concept, huge MCQ surface area.

Status: not started

## The ONE Mental Model

Average is **total ÷ count**, but that definition is useless under time pressure. The useful model: think in **deviations from a chosen reference**.

> Pick any "assumed average" $A_0$. Compute each item's deviation $d_i = x_i - A_0$. Then the **true average** is $A_0 + \dfrac{\sum d_i}{n}$.

Every non-trivial average problem collapses if you:

1. **Pick a smart $A_0$** (usually the old average, or a round number).
2. **Track total change**, not individual values. If total goes up by $\Delta$, average goes up by $\Delta/n$. If $n$ changes too, recompute carefully — this is where the traps live.
3. **Never re-sum all the items.** The shift from $A_0$ to the new average always has a one-line formula.

Corollary: Average is just **weighted ratio at weight = 1 each**. When weights differ, you're in Alligation territory.

## The Deviation Method (the one trick worth drilling)

Given values like $78, 82, 75, 85, 80$. Don't sum them.

- Assume $A_0 = 80$. Deviations: $-2, +2, -5, +5, 0$. Sum $= 0$. Average $= 80 + 0/5 = 80$.
- This is 10× faster than $(78+82+75+85+80)/5 = 400/5 = 80$.

**When deviations are small and count is large, this is the only method worth using.**

## The Full Formula Set

Core four in **bold**. The rest are corollaries memorized once and recognized on sight.

### A. Basic

| # | Formula | When |
|---|---------|------|
| **1** | **$\text{Avg} = \dfrac{\text{Sum}}{n}$** | Definition — use only when $n$ is small |
| **2** | **$\text{Sum} = \text{Avg} \times n$** | The "inverse" — given the average, reconstruct the total |
| 3 | Avg $= A_0 + \dfrac{\sum (x_i - A_0)}{n}$ | Deviation method — fast mental math |

### B. Addition / Removal

| # | Formula | When |
|---|---------|------|
| **4** | **New avg after adding one item $x$**: $\text{new avg} = \dfrac{n \cdot \text{old avg} + x}{n+1}$ | One new entry |
| **5** | **Replacement**: avg changes by $\Delta$ when $x_{\text{old}}$ is replaced by $x_{\text{new}}$ → $x_{\text{new}} - x_{\text{old}} = n \cdot \Delta$ | The workhorse. Memorize. |
| 6 | Removing one item $x$: $\text{new avg} = \dfrac{n \cdot \text{old avg} - x}{n-1}$ | One entry drops out |
| 7 | Adding $k$ items with avg $B$: combined avg $= \dfrac{nA + kB}{n+k}$ | Two groups merging |

### C. Shift shortcuts

| # | Formula | When |
|---|---------|------|
| 8 | Each item +$c$: new avg $=$ old avg $+ c$ | Everyone gets the same bonus |
| 9 | Each item $\times c$: new avg $=$ old avg $\times c$ | Uniform scaling (currency conversion, % hike) |
| 10 | Average of $n$ consecutive integers starting at $a$: $\dfrac{a + (a+n-1)}{2}$ | AP shortcut |
| 11 | Average of first $n$ natural numbers: $\dfrac{n+1}{2}$ | Memorize |
| 12 | Average of first $n$ even numbers: $n+1$ | Memorize |
| 13 | Average of first $n$ odd numbers: $n$ | Memorize |
| 14 | Average of squares of first $n$ naturals: $\dfrac{(n+1)(2n+1)}{6}$ | Rarely tested but appears in SBI PO |
| 15 | Average of cubes of first $n$ naturals: $\dfrac{n(n+1)^2}{4}$ | Rarely tested |

### D. Speed / weighted

| # | Formula | When |
|---|---------|------|
| **16** | **Average speed (equal distances, two speeds $u, v$): $\dfrac{2uv}{u+v}$** (harmonic mean) | Going and returning, same distance |
| 17 | Average speed (3 equal distances, speeds $u, v, w$): $\dfrac{3uvw}{uv+vw+wu}$ | Three-leg journey |
| 18 | Average speed (equal time at different speeds): arithmetic mean $= (u+v)/2$ | "Drives at $u$ for 1 hr then $v$ for 1 hr" |
| 19 | Weighted average of groups $(n_1, A_1), (n_2, A_2)$: $\dfrac{n_1 A_1 + n_2 A_2}{n_1 + n_2}$ | Two groups, different sizes |
| 20 | Alligation rule: $\dfrac{n_1}{n_2} = \dfrac{A_2 - A_{\text{mean}}}{A_{\text{mean}} - A_1}$ | Reverse — given means, find ratio |

## Replacement — the single highest-yield sub-topic

Formula 5 is worth 3× every other formula. Learn to recognize and apply it in under 10 seconds.

> **Replacement rule.** If $n$ items have average $A$, and one item of value $x_{\text{old}}$ is replaced by $x_{\text{new}}$, the average changes by $\Delta$ where $x_{\text{new}} - x_{\text{old}} = n \cdot \Delta$.

**Canonical phrasing:** "Average age of 10 people is 25. One person leaves and a new person joins, average drops by 2. Find difference in ages." → $x_{\text{new}} - x_{\text{old}} = 10 \times (-2) = -20$. New person is 20 years younger.

All of these are the same formula:

- Cricket: batsman's average goes up by 2 after scoring 80 in 11th innings → $80 = 11 A_{\text{new}} - 10 A_{\text{old}}$, with $A_{\text{new}} - A_{\text{old}} = 2$.
- Class: teacher's weight replaces student's; average goes up by some amount.
- Office: new employee replaces old one; average salary changes.
- Family: member leaves, new one joins; average age changes.

**The hidden structure is always: total change = $n \times \Delta$.** Identify $n$, identify $\Delta$, solve.

### Cricket/innings variant (Formula 5 with a twist)

"Batsman's average after 10 innings is 32. In the 11th innings he scores $x$, new average is 34."

- Old total = $10 \times 32 = 320$.
- New total = $11 \times 34 = 374$.
- $x = 374 - 320 = 54$.

**Shortcut:** $x = \text{new avg} + n \cdot \Delta = 34 + 10 \times 2 = 54$. Memorize this form — saves 15 seconds.

> Generalized: scoring $x$ in the $(n+1)$th innings raises the average by $\Delta$ → $x = \text{new avg} + n \Delta$, equivalently $x = \text{old avg} + (n+1) \Delta$.

## High-Yield Shortcuts

1. **Replacement shortcut (Formula 5).** Write it on the inside of your skull. Total shift = $n \cdot \Delta$.
2. **Cricket shortcut.** Score needed = new avg + $n \cdot \Delta$ (where $n$ = old innings count, $\Delta$ = rise).
3. **"Average of averages" is NOT a simple mean.** If group sizes differ, use weighted average (Formula 19). "Class A avg 60 (30 students), Class B avg 80 (20 students), combined avg?" → $(60 \times 30 + 80 \times 20)/50 = (1800 + 1600)/50 = 68$. Not 70.
4. **Consecutive numbers → middle value.** Average of 5 consecutive integers = the middle one. Average of 6 consecutive integers = the mean of the two middle ones.
5. **Uniform shift.** "Each salary goes up by ₹500" → new average = old average + 500. Don't recompute.
6. **Harmonic mean for equal-distance speed.** $\dfrac{2uv}{u+v}$. Drill this until it's reflex. ~1 question per banking paper.
7. **Ages of a group.** "Average age of 5 people is 30, 5 years ago?" → simply 25 (everyone got younger by 5 — Formula 8).
8. **Deviation method** when values cluster around an obvious anchor. Example: weights $68, 72, 70, 69, 71$ → assume 70, deviations $-2, +2, 0, -1, +1$, sum $= 0$, avg $= 70$.

## MCQ Tactics (exam-only)

- **Assume old average = 0** when the question asks only for the change. All the given numbers become deviations. Works when the absolute level is irrelevant.
- **Back-solve replacement problems.** Four options for $x_{\text{new}}$, plug each into $n \Delta = x_{\text{new}} - x_{\text{old}}$, match.
- **Ballpark combined average.** If $A_1 < A_2$, combined average lies between them, closer to the larger group. Eliminate options outside the range.
- **Watch the $n$.** After addition, $n$ increases; after removal, it decreases; after replacement, $n$ is unchanged. Getting this wrong flips the sign.
- **Convert weighted problems to alligation.** Much faster visually for 2-group problems.

## Calculation Speed Hacks

- **Sum via deviation.** $(n \cdot A_0) + \sum d_i$. Skip the long addition.
- **Change in sum = $n \cdot \Delta_{\text{avg}}$.** Always. Memorize the direction (add when avg rises, subtract when it falls).
- **Round anchors.** Pick $A_0$ as the nearest multiple of 10 or 5. Deviations stay small; mental arithmetic is free.
- **"Total age N years ago" trick.** Current total $- n \cdot y$ where $y$ = years elapsed. Avoids computing individual old ages.
- **Replace with multiplication, not division.** Instead of $\text{sum}/n$, compute $\text{sum} \times (1/n)$ only if $1/n$ is a clean fraction (1/5, 1/4, 1/8). Otherwise use deviation.

## Alligation — the ratio-based shortcut for weighted averages

Alligation is Formula 20 drawn as a cross. For two groups with averages $A_1 < A_{\text{mean}} < A_2$:

```
         A_1       A_2
           \       /
            A_mean
           /       \
      A_2 - A_mean     A_mean - A_1
```

**Ratio of weights (group sizes) $n_1 : n_2 = (A_2 - A_{\text{mean}}) : (A_{\text{mean}} - A_1)$.**

The group closer to the mean has the **larger** weight — internalize this to avoid direction errors.

**Example.** Milk at ₹40/L and milk at ₹60/L mixed to get ₹45/L. Ratio?
$\;\; 60 - 45 = 15 \;:\; 45 - 40 = 5 \;\Rightarrow\; 15:5 = 3:1$. (₹40 milk to ₹60 milk.)

## Common Traps (memorize — these are where marks leak)

1. **Average of averages ≠ mean of averages.** If the group sizes differ, you *must* weight. Classic banking trap.
2. **Forgetting $n$ changes after add/remove.** Adding one → denominator becomes $n+1$. Replacement → denominator stays $n$.
3. **Direction of $\Delta$.** "Average increased by 2" → $\Delta = +2$. "Decreased" → $\Delta = -2$. Total shift carries the sign.
4. **Cricket-style confusion.** "Average after 11 innings is 34" vs "average increases by 2 after 11th innings". The first gives you new avg directly; the second requires computing $A_{\text{old}} = 32$.
5. **Speed-average confusion.** Equal distance → harmonic mean. Equal time → arithmetic mean. Mix them up and the answer is wrong by ~5%.
6. **Ages "5 years ago" vs "5 years ago average"**. "Average 5 years ago" = current avg − 5 (Formula 8). "Average of the oldest 5 people" is a sub-group problem, unrelated.
7. **Including / excluding the teacher/captain/leader.** "Average age of class is 15; including the teacher, 16; teacher's age?" → $\text{teacher} = 16 \cdot (n+1) - 15 \cdot n = n + 16$.
8. **Group sizes are coin counts, not values.** In mixture problems, weight = quantity, not the value of the quantity.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "Average of 5 people is 30" | Sum = 150 |
| "Average age 5 years ago was 30" | Sum 5 years ago = 150; current sum = 150 + 25; current avg = 35 |
| "One person leaves, average becomes 28" | New $n = 4$, new sum = 112 → leaver = 150 − 112 = 38 |
| "One person replaces another, average becomes 28" | $n$ still 5, new sum = 140 → $x_{\text{new}} - x_{\text{old}} = -10$ |
| "Average of class including teacher = 16" | $(n+1)$ people, sum = $16(n+1)$ |
| "Average of students is 15, teacher's age is …" | $n$ students alone, sum $= 15n$ |
| "Batsman's avg goes up by 2 after 11th innings" | Old $n = 10$, new $n = 11$; $\Delta = +2$ |
| "Batsman's avg in 11 innings is 34" | Direct: new total $= 374$ |

## Problem Patterns → Attack Plan

| Pattern | Attack |
|---------|--------|
| **Direct: find avg given sum** | Formula 1. Trivial. |
| **Find missing value given new avg** | Formula 4 or 5 depending on add vs replace. |
| **Replacement (weight/age/salary/runs)** | Formula 5: $x_{\text{new}} - x_{\text{old}} = n \cdot \Delta$. One line. |
| **Cricket — next score to raise avg** | $x = \text{old avg} + (n+1) \Delta$ or $\text{new avg} + n \Delta$. |
| **Combined average of two groups** | Formula 19. If group sizes given, weighted; if not, alligation gives ratio. |
| **Class avg + teacher included** | Formula 4 with $n$ = students, new count $n+1$. Teacher's age = $(n+1)A_{\text{new}} - nA_{\text{old}}$. |
| **Ages of group, "$x$ years later/ago"** | Formula 8. Each member shifts by $x$; average shifts by $x$. |
| **Avg speed (two legs)** | Equal distance → harmonic. Equal time → arithmetic. Read carefully. |
| **Avg of first $n$ naturals/evens/odds** | Formulas 11–13. Memorized. |
| **Consecutive integers** | Middle value (odd $n$) or mean of two middles (even $n$). |
| **Avg of averages (weighted)** | Use alligation if you need the ratio; Formula 19 if sizes known. |
| **Mixture at given price** | Alligation: cost₁ vs cost₂ vs mean cost → ratio of quantities. |

## Links to Other Chapters

- **Ages** — every "average age" problem is Formula 4, 5, or 8 in disguise.
- **Mixtures & Alligation** — alligation rule *is* Formula 20.
- **Ratio & Proportion** — weighted average expects the group-size ratio; alligation outputs it.
- **Percentages** — "average increased by 5%" = Formula 9 with $c = 1.05$.
- **Time, Speed & Distance** — harmonic-mean shortcut (Formula 16) is a TSD staple.
- **Time & Work** — effective-rate problems are hidden weighted averages.
- **SI/CI** — rarely used, but "average rate of interest over two schemes" is Formula 19.
- **DI** — tabular "average across years/regions" is a weighted-average question pretending to be data lookup.

## DI Integration Checklist

- **"Average of X across years"** → sum the row, divide by number of years. Don't trust "visual averaging" on line graphs.
- **"Which year had average closest to overall average?"** → compute overall first (one number), then scan for the row with smallest deviation.
- **Tabular row-average vs column-average** → different! Row = one entity across years; column = all entities in one year.
- **Approximation in averaging** → use deviation method. Pick the visible middle value as $A_0$, eye-ball deviations.
- **"Average growth rate"** → NOT the arithmetic mean of year-on-year %s if the base is changing. Use compounded form (CI-style) for precision, or flag approximation.

## Time Budget (per-question targets)

| Sub-pattern | Target | Red flag if > |
|-------------|--------|---------------|
| Direct avg / missing value | 20 s | 35 s |
| Replacement (one swap) | 30 s | 50 s |
| Cricket / innings | 30 s | 50 s |
| Class + teacher included | 35 s | 60 s |
| Combined avg (two groups) | 30 s | 50 s |
| Alligation-style mixture | 45 s | 75 s |
| Avg speed (harmonic) | 25 s | 40 s |
| DI cell (average across row/col) | 25 s | 40 s |

If you're slow on "replacement", the bottleneck is Formula 5 recall — not concept. Drill it.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI/IBPS PO**: expect 1 direct averages Q + 1 embedded in a DI set. Replacement is the most-tested form.
- **IBPS Clerk / SBI Clerk**: direct "find missing value" or "new average after addition". Speed matters.
- **RBI Grade B / NABARD**: averages rarely standalone; embedded in DI with weighted-average flavor.
- **LIC AAO**: classic cricket/replacement problems + table-based averages.
- **Keyword → attack**:
  - "average is" / "average of" → Formula 1 (direct)
  - "new average" → Formula 4 (add) or 5 (replace) depending on context
  - "instead of" → replacement, apply Formula 5
  - "excluding" / "including" → $n$ changes, reconstruct sums
  - "on an average" → same as average, watch for group weights
  - "average speed" → check if equal-distance or equal-time
  - "increased by / decreased by" → $\Delta$; solve for $n \Delta$ = total shift

## PYQ-Flavor Drill Problems

Solve untimed first, then re-time at 45–60 s each. Each maps to a recurring pattern.

1. **(IBPS PO — replacement)** Average weight of 8 people is 65 kg. One person weighing 70 kg is replaced by another. Average becomes 66 kg. Weight of new person?
   *$\Delta = +1$, $n = 8$ → total shift $= 8$. New weight $= 70 + 8 = 78$ kg.*

2. **(SBI PO — cricket)** A batsman has scored an average of 40 runs in 10 innings. What should he score in the 11th innings to make his average 42?
   *Required $= 42 + 10 \times 2 = 62$. Or: new total $= 11 \times 42 = 462$; old total $= 400$; required $= 62$.*

3. **(IBPS Clerk — class + teacher)** Average age of 30 students in a class is 14. When the teacher is included, the average becomes 15. Teacher's age?
   *Sum with teacher $= 31 \times 15 = 465$. Sum without $= 30 \times 14 = 420$. Teacher $= 45$.*

4. **(RBI Grade B — group ages)** Average age of a husband and wife was 23 when they were married 5 years ago. The average age of the husband, wife, and a 4-year-old child is now 20. Age of the child?
   *Husband + wife now: avg $= 23 + 5 = 28$, sum $= 56$. Three-person sum $= 3 \times 20 = 60$. Child's age $= 60 - 56 = 4$. ✓ (consistent)*

5. **(NABARD — combined avg)** Class A: 40 students, average 60. Class B: 60 students, average 70. Combined average?
   *Weighted: $(40 \times 60 + 60 \times 70)/100 = (2400 + 4200)/100 = 66$.*

6. **(LIC AAO — alligation)** In what ratio must rice at ₹25/kg be mixed with rice at ₹35/kg to get a mixture costing ₹28/kg?
   *$(35 - 28) : (28 - 25) = 7 : 3$. (₹25 rice to ₹35 rice.)*

7. **(SBI PO — avg speed)** A car travels from A to B at 60 km/h and returns at 40 km/h. Average speed for the round trip?
   *$\dfrac{2 \times 60 \times 40}{100} = \dfrac{4800}{100} = 48$ km/h.*

8. **(IBPS PO — replacement trap)** Average marks of 10 students is 80. It is found that one student's marks were wrongly entered as 92 instead of 72. Correct average?
   *Total shift $= 72 - 92 = -20$. $\Delta = -20/10 = -2$. Correct avg $= 78$.*

9. **(IBPS Clerk — removal)** Average of 11 numbers is 50. If one number is removed, the average becomes 48. Find the removed number.
   *Old sum $= 550$. New sum $= 10 \times 48 = 480$. Removed $= 70$.*

10. **(SBI PO — consecutive)** Average of 5 consecutive odd numbers is 27. Find the largest.
    *Middle = 27; numbers are 23, 25, 27, 29, 31. Largest = 31.*

## Stage-7 Self-Test (if you can't do these in 45s each, revisit)

1. Avg of first 20 natural numbers? *(10.5)*
2. Avg of first 15 even numbers? *(16)*
3. Avg speed: 60 km/h one way, 30 km/h return, same distance. *(40 km/h)*
4. 7 people avg 25. 8th joins, avg becomes 26. 8th person's age? *(33)*
5. Replacement: $n = 20$, avg up by 3, old value was 15. New value? *(75)*
6. Class A: 20 students, avg 70. Class B: 30 students, avg 80. Combined? *(76)*
7. Milk at ₹30 and ₹50 mixed to give ₹44. Ratio? *(6:14 = 3:7)*
8. Batsman avg in 16 innings is 36. Scores 0 in 17th. New avg? *($16 \times 36 / 17 = 576/17 \approx 33.88$)*
9. Avg of 10 numbers is 20. One is misread as 64 instead of 46. Correct avg? *($20 - 18/10 = 18.2$)*
10. Ages of 4 people avg 28 now. 5 years ago? *(23)*

If you can explain **why** each answer is right without the formula sheet, Averages is done.

## Revision Triggers

- If Replacement (Formula 5) takes > 15 seconds to set up, drill it alone for a day.
- If Alligation feels different from weighted average, re-derive Formula 20 from 19 once — then drop the distinction forever.
- If cricket/innings problems stall, rewrite the shortcut $x = \text{new avg} + n \Delta$ by hand three times.
- Re-drill the deviation method whenever DI caselets feel slow — the bottleneck is almost always additive arithmetic, not concept.
