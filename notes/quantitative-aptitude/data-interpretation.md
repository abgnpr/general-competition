---
title: Data Interpretation
parent: Quantitative Aptitude
nav_order: 17
---

# Data Interpretation

**Tier 1 · Priority 8.** The payoff chapter. DI is not a new skill — it is Percentages + Ratios + Averages speed-tested on presented data. Every calculation lives in a chapter you already know; the new skill is **reading fast, approximating hard, and picking smart**.

Status: not started

## The ONE Mental Model

> **Read → Extract → Reduce → Approximate → Match.** In that order, always.

DI problems fail when you skip step 2 (wrong number extracted from wrong row/column) or step 4 (full calculation instead of approximation). Most wrong answers in DI are reading errors or over-computation, not conceptual errors. **Exact arithmetic in DI is usually the wrong strategy** — it's slower than the options require.

## The 30-Second Chart Scan (before any question)

1. **Title** — what is being measured?
2. **Axes / columns** — what are the labels? What's on each axis?
3. **Unit** — Lakhs? Crores? Thousands? % of total? Degrees?
4. **Range** — approximate min and max (sets the denominator for % questions)
5. **Categories / series** — how many bars per group? legend order?
6. **Hidden structure** — dual Y-axis? stacked (not grouped) bars? cumulative totals?

### Common reading stumbles (flag before starting)

- **Dual Y-axis line graph** — two lines, two different scales. Labels only tell you which line maps to which axis.
- **Stacked bar vs grouped bar** — stacked: read cumulative, subtract for component. Grouped: read each bar directly.
- **Pie in degrees vs %** — always check. 36° ≠ 36%.
- **Cumulative totals in tables** — "Upto 2023" columns vs "in 2023" columns require subtraction to get per-year value.
- **Units mixed across columns** — revenue in Cr, employees in thousands, in the same table. Happens more than you'd expect.

## Approximation Arithmetic — the actual hard skill

This is the core of DI and the most under-taught. Every technique below assumes "4 options, one is right, the others are >3% apart".

### The Percent-of-Total protocol

**Problem shape:** "What % of total sales in 2022 came from Product A?"
Given: Product A = 3847, Total = 12,450.

**Wrong:** Compute $\frac{3847}{12450} \times 100$ exactly.
**Right:**
1. Round both: $\frac{3800}{12500}$ or $\frac{3850}{12500}$.
2. Simplify: $\frac{3850}{12500} = \frac{77}{250} = \frac{308}{1000} = 30.8\%$.
3. Scan options for something near 30–31%. Done in 15 seconds.

**Alternative (faster when one is a clean multiple):** $\frac{3847}{12450} \approx \frac{3847}{12450}$. Is $12450 \approx 4 \times 3847 = 15388$? No. Is it $\approx 3 \times 3847 = 11541$? Close enough → A is slightly less than $1/3$ of total → ~30%.

### The %-change protocol

**Problem shape:** "By what % did sales grow from 2021 (₹4,250 Cr) to 2022 (₹5,610 Cr)?"

**Wrong:** $(5610 - 4250)/4250 \times 100 = 1360/4250 \times 100$ then long division.
**Right:**
1. Compute the difference (small number): $5610 - 4250 = 1360$.
2. Approximate ratio: $1360 / 4250 \approx 1400/4250 \approx \frac{14}{42.5} \approx \frac{1}{3} - \text{a bit} = 0.32$.
3. Answer ≈ 32%. Match to options.

**Faster:** $4250 \times 1.3 = 5525$; $4250 \times 1.32 = 5610$ exactly. So growth = 32%. Work from options backward.

### The Ratio protocol

**Problem shape:** "Ratio of A's 2022 to B's 2023 revenue."

1. Extract both cells. Call them $p$ and $q$.
2. Find the largest common factor you can **see** (usually 10, 100, or a small prime).
3. Reduce: $\frac{480}{720} = \frac{2}{3}$ instantly.
4. Not clean? Approximate each to nearest 50 or 100, then reduce.

### The Average protocol

**Problem shape:** "Average monthly sales across 5 months: 120, 135, 128, 142, 125 (in Cr)."

**Wrong:** Sum all five exactly, divide by 5.
**Right (deviation method):** Anchor on 130. Deviations: −10, +5, −2, +12, −5 = 0. Average = 130.

Always anchor on a middle-looking value; deviations sum to near zero and the arithmetic is one-line.

### Square / Cube Root approximation

$\sqrt{N}$: bracket between adjacent perfect squares.
- $\sqrt{624}$: $25^2 = 625$ → $\sqrt{624} \approx 24.98 \approx 25$.
- $\sqrt{2025} = 45$ (memorize: $45^2 = 2025$).

$\sqrt[3]{N}$: bracket between adjacent perfect cubes.
- $\sqrt[3]{8500}$: $20^3 = 8000, 21^3 = 9261$ → between, closer to 20 → $\approx 20.4$.

### Multi-step expression (the "find approx value" type)

**Problem shape:** $\sqrt{624} \times 16.02 + 289.97 \div 18.1 = ?$

1. Replace each chunk with nearest anchor: $\sqrt{624} \approx 25$; $16.02 \approx 16$; $289.97 \approx 290$; $18.1 \approx 18$.
2. $25 \times 16 = 400$.
3. $290 / 18 \approx 16$ (since $18 \times 16 = 288$).
4. $400 + 16 = 416$. Match to options.

Always approximate *before* multiplying, not after.

## Speed-Reading the Visuals (the under-taught primitive)

Top DI scorers don't compute ratios. They see them. Calibrate your eye on these anchors:

- Bar at **half** another → ratio 1:2, or 50%.
- Bar at **two-thirds** of another → ratio 2:3, or 66.67%.
- Bar at **three-quarters** of another → ratio 3:4, or 75%.
- Bar at **one-fifth** → 20%, one-quarter → 25%.

**Practice drill:** on every bar/pie chart you see, estimate each ratio by eye first, then compute. Calibrate your intuition for one week and the rest of your DI time-budget improves by 20%.

## DI Sub-types and Their Attack Protocols

### Tables

**Nature:** Dense grid of numbers. No visual. Hardest to eyeball.

**Attack:**
- Identify row and column precisely before reading the cell. Pointing at the cell with a finger (or pen) is not overkill.
- Row totals and column totals often save time — check if given before summing.
- Approximation wins here: if options spread by >5%, round every cell.
- Units — same table may mix lakhs and crores in different columns. Always read the header, not just the row.

**Trap:** Reading the wrong row (one off), misidentifying the "total" row, mixing header unit.

---

### Bar Graphs

**Nature:** Comparative quantities; single, grouped, or stacked.

**Attack:**
- **Grouped (side-by-side):** read each bar directly; confirm legend → category mapping every 2 questions.
- **Stacked:** total is the full bar height; a component is the segment height. Subtract the segment below to get a middle component.
- Eyeball ratios before computing (see Speed-Reading above).
- Y-axis scale — check start (not always zero) and increment (are gridlines every 50 or every 100?).

**Trap:** Swapped legend; stacked mis-read as grouped; non-zero Y-axis start exaggerating differences.

---

### Line Graphs

**Nature:** Trends over time. YoY change, growth rates, peaks.

**Attack:**
- "Highest increase" → largest upward slope, not the highest point.
- "Which year had highest growth rate?" → compute $(y_t - y_{t-1})/y_{t-1}$ for top 2–3 visual candidates only.
- Two lines: "when are they equal?" → intersection; "difference?" → vertical gap.
- **Dual Y-axis:** each line reads against its own axis. Read axis labels, not just the line.

**Trap:** Confusing the value with the change. "In which year was sales highest?" ≠ "In which year did sales grow most?". Also: mis-reading dual Y-axis.

---

### Pie Charts

**Nature:** Parts of a whole as angles or %.

**Attack:**
- Check: angles (degrees) or %? The question format depends on this.
- Convert degrees to %: $\times 5/18$. Or use anchors: $36° = 10\%$, $72° = 20\%$, $90° = 25\%$, $180° = 50\%$.
- Value of a slice = slice % × total. Total is almost always given separately.
- Two pie charts (two years): slices are % of *that year's* total. Convert to absolute values *first* before comparing.

**Trap:** "What % of total is category C?" when the chart already shows %: the answer IS the slice %. Don't divide again. Also: assuming same category % across two pies means same absolute value (it doesn't — totals differ).

**Angle ↔ % lookup table:**

| Degrees | % |
|---------|---|
| 18° | 5% |
| 36° | 10% |
| 54° | 15% |
| 72° | 20% |
| 90° | 25% |
| 108° | 30% |
| 120° | 33.33% |
| 135° | 37.5% |
| 144° | 40% |
| 180° | 50% |
| 216° | 60% |
| 270° | 75% |

---

### Caselets (Paragraph DI)

**Nature:** Data buried in prose. The hardest sub-type for time management.

**Attack protocol (strict — don't deviate):**
1. **Pre-read once.** Don't compute. Just understand the scenario (company / product / exam split / etc.).
2. **Re-read, table-first.** Draw a blank table with categories as columns, subdivisions as rows. Label both before entering numbers.
3. **Fill given cells, then derived cells.** If the caselet says "total = 600, A:B = 3:2", compute A=360, B=240 immediately. Don't wait for a question.
4. **Only then read the questions.** Most questions map to one cell; you've already done the work.

**Worked example (typical exam caselet):**
> In a college, total students are 1800. Ratio of boys to girls is 5:4. 40% of boys play cricket; 25% of girls play cricket. Of those who play cricket, 30% are in their final year.

**Table first:**

| | Boys | Girls | Total |
|---|------|-------|-------|
| All | 1000 | 800 | 1800 |
| Cricket | 400 | 200 | 600 |
| Cricket + Final-year | 120 | 60 | 180 |

Three lines of arithmetic, done before reading any question. Now any question answers in 5 seconds.

**Trap:** Jumping to Q1 before filling the table. You'll re-derive the same quantity 4 times across 4 questions.

---

### Mixed / Combo DI

**Nature:** Two or more charts covering the same data set (e.g., bar + pie, or table + line).

**Attack:**
- Label each chart's role in the 30-sec scan. Write on the margin: "bar = production, pie = export share".
- Most questions need both charts — identify "which chart gives what" before computing.
- Cross-reference: one chart often gives totals, the other gives splits. Combine to get individual values.

**Trap:** Using the wrong chart for a question. Assuming the same total across both charts when only one mentions it.

---

### Missing-Data DI

**Nature:** One or more cells marked "?". Solve sequentially using constraints.

**Attack:**
- Identify all constraints first: row totals, column totals, given ratios, given percentages.
- Solve cells in dependency order (most-constrained first).
- Fill the whole table before answering questions.

**Trap:** Trying to compute a missing cell when another cell it depends on is also missing. Order matters.

---

### Data Sufficiency (RBI / NABARD Mains)

**Nature:** A question is followed by 2 statements (sometimes 3). You don't answer the question; you determine *which statements are sufficient*.

**Answer pattern:**
- (A) Statement I alone is sufficient, II alone is not.
- (B) Statement II alone is sufficient, I alone is not.
- (C) Either I or II alone is sufficient.
- (D) Both I and II together are sufficient, neither alone.
- (E) Neither I nor II, even together, is sufficient.

**Attack:**
- **Do NOT compute the answer.** You only need to know if it's computable, not what it is.
- Check each statement in isolation first (I alone, then II alone).
- Only if neither alone works, check both together.
- Common trap: assuming a statement is sufficient because it "looks like enough" — verify by tracing what's unknown.

**Example:** "Find the ratio of A's salary to B's."
- I: A earns ₹5000 more than B.
- II: A's salary is 120% of B's.

Statement I: one equation, two unknowns → not sufficient alone.
Statement II: ratio is given directly → sufficient. Answer: B.

---

## Common Traps (memorize — where marks leak)

1. **Unit mismatch.** "Sales in Lakhs" vs "profit in Crores" in the same question. Convert before computing.
2. **"The following year" confusion.** "In the year following the highest-sales year" — identify highest-sales year first, then take year+1.
3. **Wrong base for % change.** % change is always over the OLD value.
4. **Pie chart double-division.** If pie shows %, slice value IS "% of total". Don't divide by 100 again.
5. **Bar graph legend swap.** Re-verify legend every 2 questions on grouped bars.
6. **"More than" vs "as a % of".** Absolute difference vs relative.
7. **Averages of averages.** Weighted, not arithmetic mean.
8. **Pie across years.** Same % in two pies ≠ same absolute value (totals differ).
9. **Cumulative total confusion.** "Upto year Y" vs "in year Y" → subtract to get per-year.
10. **Caselet "remaining" trap.** "After A and B take their shares, C gets the rest" — compute A+B and subtract.
11. **Non-zero Y-axis.** Line appears to double but only rose 20%.
12. **Dual Y-axis.** Two lines, two scales — easy to compare heights visually but wrong.

### Trap Pairs (drill side-by-side)

| Sounds similar | Correct reading |
|----------------|-----------------|
| "Highest value in 2022" | Read 2022 cell/bar directly |
| "Highest growth in 2022" | (2022 − 2021)/2021 × 100 |
| "Ratio of A to B" | A/B |
| "B as a % of A" | (B/A) × 100 |
| "% increase from X to Y" | (Y − X)/X × 100 (base = X) |
| "% decrease from Y to X" | (Y − X)/Y × 100 (base = Y) |
| "By how much did A exceed B?" | A − B (absolute) |
| "By what % did A exceed B?" | (A − B)/B × 100 |
| "Combined avg of A and B" | Weighted by count, not (avg A + avg B)/2 |
| "Average annual growth rate" | CAGR — geometric mean, not arithmetic |
| "Slice is 72°" | 20% of total (multiply by total to get value) |
| "Slice is 72%" | already 72% (no conversion) |
| "If sales grew 15%" | new = old × 1.15 |
| "If sales grew by 15 Cr" | new = old + 15 |

## DI Attack Plan by Question Type

| Question phrasing | One-line attack |
|-------------------|----------------|
| "Find value of X in year Y" | Read cell directly; apply unit |
| "% change from Y1 to Y2" | (Y2−Y1)/Y1; use approx + fraction table |
| "Ratio of A to B" | Simplify the two cell values; cancel |
| "Average over N years" | Deviation method around a middle anchor |
| "By how many units did X exceed Y?" | Absolute subtraction |
| "What % of total is category C?" | C / total × 100; confirm total is stated |
| "Which year had highest X?" | Visual scan, compute only top 2 candidates |
| "Combined value of A and B in year Y" | Sum the two cells; same unit |
| "Value in year Y if grew Z% from Y−1" | Cell × (1 + Z/100) |
| "Angle/slice for category C" | Value / total × 360 (or × 3.6 if % given) |
| "CAGR over N years" | (Final/Initial)^(1/N) − 1 — approximate via Rule of 72 |

## Question-Picking Strategy (exam-only)

Within a DI set, not all questions are equal.

| Question type | Difficulty | Pick first? |
|---------------|------------|-------------|
| Single-cell lookup | Low | Yes |
| % of single year/category | Low | Yes |
| Ratio of two values | Low–Medium | Yes |
| YoY % change | Medium | Yes |
| Average across years | Medium | Yes |
| Combined/total across all categories | Medium | Often |
| "Which year had highest X?" | Medium | After easy ones |
| Cross-chart (needs two data sources) | High | Late |
| Missing caselet cell | High | Late |
| Data Sufficiency | Variable | Read first, often easy |

**Set-level strategy:** Scan all 5 questions before answering any. Pick 3 easiest first. If Q4 is a multi-step monster, skip and move on. A 4-out-of-5 attempted set scores more than a 5-out-of-5 slow one that eats your time budget.

**Set-selection strategy (when choosing between 2 sets):**
- Table or bar > caselet (faster extraction).
- Set with 3+ "% of" or "ratio" questions > set with multi-step mains.
- Round numbers in data > ugly numbers (fewer computation steps).

## Links to Other Chapters

- **Percentages** — % change, % of total. Every second DI question.
- **Ratio & Proportion** — cross-category splits; the fraction↔% table is decisive.
- **Averages** — deviation method; weighted averages.
- **Profit & Loss** — revenue/cost/margin tables in RBI/NABARD DI.
- **SI/CI** — CAGR across years is CI.
- **Simplification & Approximation** — arithmetic speed. If DI is slow, the bottleneck is usually here.

## Time Budget (per-question targets)

| Question type | Target | Red flag if > |
|---------------|--------|---------------|
| Single cell lookup | 15 s | 25 s |
| Ratio of two cells | 20 s | 35 s |
| % change (two cells) | 25 s | 40 s |
| Average across N years | 30 s | 50 s |
| "Which year highest X" (needs scan) | 40 s | 60 s |
| Cross-chart (two data sources) | 45 s | 75 s |
| Caselet (after table filled) | 20 s/Q | 40 s |
| Data Sufficiency | 35 s | 60 s |

**Per-set target:** 5 questions in 5–6 minutes. If a set runs past 7 minutes, abandon the hardest question.

## Exam Phrasing Cues (Indian banking/insurance)

- **SBI / IBPS PO Prelims**: 2 DI sets, 10 questions. 1 table + 1 bar/line typically. Heavy on % change and ratio.
- **SBI / IBPS PO Mains**: 3–4 DI sets, 15–20 questions. Caselets and mixed DI. Approximation is decisive.
- **IBPS Clerk**: 1–2 sets, simpler data. Direct lookup + % change.
- **RBI Grade B**: hardest DI in the sector. Multi-chart, multi-step, data sufficiency appears. Read every label twice.
- **NABARD Grade A**: agriculture/rural data. Same mechanics; unfamiliar category names — read title.
- **LIC AAO**: revenue/expense/claim tables. P&L flavor common.
- **Keyword → attack:**
  - "approximately" → round aggressively; options spread
  - "exactly" / "find the value" → options are close; compute carefully
  - "the following/preceding year" → shift index
  - "combined" / "total" → sum
  - "difference between" → absolute subtraction
  - "how many times" → ratio A/B
  - "as a percentage of" → numerator/denominator × 100, confirm base
  - "average" → sum/count; weighted if group sizes differ
  - "grew at the same rate" → apply % growth to given base

## Stage-7 Drill (concrete problems)

Work these in under 45 seconds each. If over, diagnose which step (read / extract / approximate / compute) slowed you.

**Data block.** Sales (₹ Cr) in 5 divisions across 2 years:

| Division | 2022 | 2023 |
|----------|------|------|
| North | 480 | 612 |
| South | 360 | 420 |
| East | 540 | 648 |
| West | 300 | 324 |
| Central | 720 | 864 |
| Total | 2400 | 2868 |

1. **What % of total 2022 sales came from East?**
   *540/2400 = 9/40 = 22.5%.*

2. **Ratio of North 2022 to West 2023?**
   *480:324 = 40:27.*

3. **By what % did Central's sales grow from 2022 to 2023?**
   *(864−720)/720 = 144/720 = 1/5 = 20%.*

4. **Average 2023 sales per division?**
   *2868/5 = 573.6 Cr. Deviation anchor 570: (612+420+648+324+864) − 5×570 = 2868−2850 = 18 → avg = 573.6.*

5. **Which division had the highest % growth 2022 → 2023?**
   *Scan: N +27.5%, S +16.67%, E +20%, W +8%, Central +20%. North highest at 27.5%.*

6. **Combined 2022 sales of North and Central as % of total 2022?**
   *(480+720)/2400 = 1200/2400 = 50%.*

7. **If South grows by the same % in 2024 as it did in 2023, what will 2024 South sales be?**
   *2023 growth = 60/360 = 16.67%. 2024 = 420 × 7/6 = 490 Cr.*

8. **What is the ratio of 2022 total to 2023 total?**
   *2400:2868 = 600:717 = 200:239. (Messy ratio — the exam would phrase this differently; if it's "approximately", the answer rounds.)*

9. **If the 2022 East figure is revealed to be wrong and should be 480 instead of 540, what is the corrected 2022 total?**
   *2400 − 60 = 2340.*

10. **(Data sufficiency) Question: "What was the 2021 sales of East?" Given: (I) Growth from 2021 to 2022 was 20%. (II) Growth from 2022 to 2023 was 20%.**
    *I alone: 540 = 1.2 × 2021East → 2021East = 450. Sufficient. II alone: doesn't reference 2021. Not sufficient. Answer: A.*

**Self-review after attempting:**
1. Did I do the 30-second chart scan before Q1?
2. Did I pick the 3 easy questions (1, 2, 6) first?
3. Did I use deviation for averages (Q4) instead of long addition?
4. Did I scan visually for Q5 before computing top 2?
5. Did any question take more than 60 seconds?

## Revision Triggers

- If ratio questions slow you, revisit Ratio & Proportion fraction table.
- If % change slows you, Percentages Formula 5 + fraction table.
- If caselet extraction slows you, practice paragraph-to-table drills: take 5 paragraphs with embedded data and convert each to a 2×3 table in under 60 seconds.
- If cross-chart questions are consistently wrong, label both charts before reading questions — literally write on the margin.
- Any DI question > 90 seconds signals arithmetic-speed bottleneck — fix via Simplification warmup.
- If you miss Data Sufficiency, you're probably computing the answer instead of checking sufficiency. Reset: "Can I, in principle, compute the answer from this statement alone?" is the only question.
